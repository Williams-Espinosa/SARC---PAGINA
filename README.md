# 🚀 SARC – Sistema de Atención a Reportes Ciudadanos

> *"Tu voz mejora tu comunidad."*

SARC es una aplicación móvil que permite a los ciudadanos reportar incidencias urbanas en tiempo real, facilitando la comunicación directa con las autoridades para una gestión más eficiente y transparente.

---

## 📱 Descripción

SARC permite reportar problemas urbanos como:

- 🕳️ Baches  
- 💡 Alumbrado público dañado  
- 🗑️ Basura acumulada  
- 🔥 Incidentes urbanos  

Cada reporte incluye:

- 📷 Fotografía del problema  
- 📍 Ubicación GPS automática  
- 📝 Descripción del incidente  

Las autoridades pueden visualizar y gestionar los reportes desde un sistema centralizado.

---

## ⚙️ Funcionalidades principales

### 📷 Reporte con Foto y GPS
Captura incidencias en segundos con imagen y ubicación exacta.

### 🗺️ Mapa de incidencias
Visualización en mapa interactivo con filtros por:
- Categoría  
- Estado (Pendiente, En proceso, Resuelto)  

### 🔄 Seguimiento en tiempo real
Consulta el estado de tus reportes en cualquier momento.

---

## 🏗️ Arquitectura

El proyecto sigue una arquitectura moderna basada en:

- 🧩 Clean Architecture  
- 🧠 MVVM (Model-View-ViewModel)  
- 🔌 Inyección de dependencias con Hilt  
- 🔄 Manejo de estados y eventos  

---

## 🛠️ Stack Tecnológico

### 📱 Mobile
- Kotlin  
- Jetpack Compose  
- Hilt (Dependency Injection)  
- Navigation Compose  

### 🌐 Backend
- Ktor  
- JWT (Autenticación)  
- Arquitectura Hexagonal  

### 🗄️ Base de datos
- PostgreSQL  
- PostGIS (geolocalización)  
- Room (almacenamiento local)

### ☁️ Servicios
- Google Maps SDK  
- Cloud Storage (imágenes)

---
