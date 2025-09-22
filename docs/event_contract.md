# Contrato de eventos (E-commerce)

## Tipos de eventos
- **VIEW**: Usuario visualiza un producto.
- **CART**: Usuario agrega un producto al carrito.
- **PURCHASE**: Usuario compra un producto.

## Campos
- **event_id**: string (UUID único por evento)
- **event_type**: string → "VIEW" | "CART" | "PURCHASE"
- **user_id**: string
- **session_id**: string
- **product_id**: string
- **category**: string
- **price**: float
- **quantity**: int
- **order_id**: string | null
- **event_timestamp**: string (ISO 8601)
- **properties**: object

## Ejemplo
```json
{"event_id": "a1b2c3d4",
 "event_type": "VIEW",
 "user_id": "u123",
 "session_id": "session_u123_20180701",
 "product_id": "p987",
 "category": "beleza_saude",
 "price": 29.90,
 "quantity": 0,
 "order_id": null,
 "event_timestamp": "2018-07-01T14:05:00",
 "properties": {}}
