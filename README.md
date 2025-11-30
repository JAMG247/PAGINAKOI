# 🌐 Sitio Web Corporativo – Koisystems
### Integración dinámica con SQL Server · Backend con .NET + Dapper · Contenido administrado desde BD

Este proyecto corresponde a la integración backend del sitio web corporativo de **Koisystems**, donde se implementó la carga dinámica de contenido desde **SQL Server** mediante consultas optimizadas con **Dapper**.

La plataforma reemplaza contenido estático por datos controlados desde la base de datos, permitiendo una actualización rápida y centralizada.

---

## 🚀 Funcionalidades principales

### 📌 Contenido dinámico cargado desde SQL Server
- Clientes (nombre, rubro, logo, fondo)
- Banners corporativos
- Datos de contacto (correo, WhatsApp, textos)
- Promociones y anuncios
- Casos de éxito

### 📡 Integración backend
- Consultas con **Dapper**
- Estructura con servicios (`ClienteBLO`, `BannerBLO`)
- Controladores limpios y organizados
- Manejo de variables desde `appsettings.json`

---

## 🛠 Tecnologías utilizadas

### Backend
- .NET 6/7  
- C#  
- Dapper  
- Inyección de dependencias  
- Controladores REST  

### Base de datos
- SQL Server  
- Consultas optimizadas  
- Control de nulls y tipos  

### Frontend
- HTML5  
- CSS3  
- JavaScript  

### Control de versiones
- Git  
- Branching por funcionalidad  
- Commits limpios  
- Integración en la rama principal  

---

## 🔄 Flujo de Datos

1. Vista solicita información  
2. Controlador llama a servicio correspondiente  
3. Servicio ejecuta consulta con Dapper  
4. Se envía la respuesta hacia la vista  
5. Contenido se muestra dinámicamente  

---

## 🧪 Pruebas realizadas

- Verificación de consultas en SQL Server  
- Pruebas funcionales de carga de clientes y banners  
- Validación de endpoints en controladores  
- Pruebas de datos incompletos o nulos  
- Revisión de despliegue en la rama principal  

---

## 📌 Estado del Proyecto
✔ Backend funcional  
✔ Contenido dinámico  
✔ Integración estable  
✔ Código mantenible  

---

## 🧩 Arquitectura del Proyecto
✔ Controllers
✔ Models
✔ Services
✔ ClienteBLO.cs
✔ BannerBLO.cs
✔ Database
✔ SqlConnectionFactory.cs
✔ wwwroot
✔ views

---

## 🔄 Flujo de Datos

1. Vista solicita información  
2. Controlador llama a servicio correspondiente  
3. Servicio ejecuta consulta con Dapper  
4. Se envía la respuesta hacia la vista  
5. Contenido se muestra dinámicamente  

---

## 🧪 Pruebas realizadas

- Verificación de consultas en SQL Server  
- Pruebas funcionales de carga de clientes y banners  
- Validación de endpoints en controladores  
- Pruebas de datos incompletos o nulos  
- Revisión de despliegue en la rama principal  

---

## 📌 Estado del Proyecto
✔ Backend funcional  
✔ Contenido dinámico  
✔ Integración estable  
✔ Código mantenible  

---

## 👤 Autor
**José Ángel Mora Garrido**  
Desarrollador Backend / Full Stack Jr  
Santiago, Chile

