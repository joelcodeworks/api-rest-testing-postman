# API REST Testing Project (Postman)

## 📖 Revisión del proyecto

Este proyecto demuestra la práctica de testing de una API REST simulada utilizando Postman.  
El objetivo fue ejecutar y documentar operaciones CRUD, validando respuestas HTTP, códigos de estado y el comportamiento general de la API.

La API utilizada es una API pública simulada (no existe persistencia real de datos).

---

## 🎯 Objetivos

- Ejecutar y documentar peticiones GET, POST y DELETE.
- Validar códigos de estado HTTP.
- Identificar escenarios positivos y negativos.
- Analizar comportamientos inconsistentes de la API.
- Practicar documentación de pruebas de forma estructurada.

---

## 🛠 Herramientas utilizadas

- Postman
- API REST pública simulada
- Notion (documentación estructurada)
- GitHub (publicación del proyecto)

---

## 🔎 Pruebas realizadas

### ✅ GET
- Consulta de usuario existente (escenario positivo).
- Consulta de usuario no existente (escenario negativo).

### ✅ POST
- Creación de usuario (escenario simulado – 201 Created).
- Respuesta de acción restringida (403 Forbidden).

### ✅ DELETE
- Eliminación de usuario existente (restricción simulada – 403).
- Eliminación de usuario no existente (403 con comportamiento inconsistente).

---

## 📌 Observaciones

- La API no tiene persistencia real de datos.
- Algunos endpoints devuelven 403 Forbidden en lugar del código REST esperado (por ejemplo, 404 para recurso inexistente).
- Se identificaron y documentaron comportamientos inconsistentes.

---

## 🧠 Aprendizajes clave

- Validación práctica de métodos HTTP y códigos de estado.
- Diferenciación entre errores de autenticación (401) y autorización (403).
- Importancia de documentar el comportamiento real de una API.
- Diferencias entre entornos simulados y sistemas con backend real.

---

## 📎 Tipo de proyecto

Testing Manual de API – Proyecto de portafolio QA Junior
