# Proyecto Integrador NoSQL - Sesión 1

Este repositorio contiene los entregables de la primera sesión del proyecto integrador de **e-commerce con eventos**.

---

##  Archivos incluidos

- `generate_events.ipynb` → Notebook en Python (Google Colab) que genera eventos simulados a partir del dataset de Olist.  
- `sample_events.jsonl` → Archivo de salida con ~2000 eventos en formato JSONL.  
- `docs/event_contract.md` → Contrato de eventos (VIEW, CART, PURCHASE).

---

## Tipos de eventos

- **VIEW** → Usuario visualiza un producto.  
- **CART** → Usuario agrega un producto al carrito.  
- **PURCHASE** → Usuario compra un producto.  

El archivo `sample_events.jsonl` contiene una mezcla realista de estos tres tipos, simulando un funnel de conversión.

---

##  Cómo reproducir

1. Abre el notebook [`generate_events.ipynb`](generate_events.ipynb) en Google Colab.  
2. Descarga el dataset de Kaggle (ver abajo).  
3. Sube los CSV al notebook.  
4. Ejecuta todas las celdas.  
5. Se generará `sample_events.jsonl` con los eventos.

---

## Dataset de origen

Este proyecto utiliza el dataset **Brazilian E-Commerce Public Dataset by Olist**, disponible en Kaggle:  
 [https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## Documentación del contrato

La definición formal de los eventos se encuentra en:  
[`docs/event_contract.md`](docs/event_contract.md)

---

## Entregables de Sesión 1
-Script en Python (notebook) para generar eventos  
-Archivo JSONL con 1k–10k registros  
-Contrato de eventos documentado en Markdown  
