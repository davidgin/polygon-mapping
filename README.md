# polygon-mapping
# Polygon Mapping with FastAPI & OpenStreetMap

This project allows users to **draw polygons on OpenStreetMap, save them in PostgreSQL/PostGIS, and retrieve them later**.

## 🚀 Features
- 🗺️ **Draw polygons** on OpenStreetMap (Leaflet.js)
- 📡 **FastAPI backend** with PostgreSQL/PostGIS
- 🔄 **Auto-import OpenStreetMap world data**
- 📂 **Stores polygons with client ID and name**
- 🐳 **Dockerized environment for easy setup**

## 🛠️ Setup Instructions
### 1️⃣ Install Dependencies
```sh
pip install fastapi uvicorn asyncpg sqlalchemy[asyncio] geoalchemy2 psycopg2 requests
