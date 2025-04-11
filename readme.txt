# Samuel Patiño Lucumí - 2226503

Este proyecto implementa un microservicio CRUD de usuarios utilizando **FastAPI** como backend, **PostgreSQL** como base de datos, y monitoreo con **Prometheus** y **Grafana**, todo orquestado con **Docker y Docker Compose**.

---

## Objetivo

Diseñar una aplicación moderna con capacidad de observabilidad, permitiendo no solo crear y gestionar usuarios, sino también monitorear el comportamiento de la API con métricas personalizadas (como `user_created_created`) en tiempo real.

---

## Tecnologías Usadas

- Python 3.10+
- FastAPI
- PostgreSQL
- Prometheus
- Grafana
- Docker & Docker Compose

---

## Estructura del Proyecto
user-crud-monitoring/
│
├── app/
│   ├── main.py
│   ├── models.py
│   ├── database.py
│   ├── __init__.py
│   └── requirements.txt
│
├── prometheus/
│   └── prometheus.yml
│
├── docker-compose.yml
└── README.md


## Instalación y Ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/Lucu1232004/Practica1ReIspl
cd user-crud-monitoring

# Iniciar servicios con
docker-compose up --build

