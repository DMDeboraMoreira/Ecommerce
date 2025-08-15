# 🛒 E-commerce Fullstack con Next.js y Express

Este es un proyecto **fullstack de E-commerce** donde construí una interfaz de usuario moderna usando **React** con el framework **Next.js** y conecté con un servidor backend desarrollado en **Express.js**.

El objetivo es renderizar información de productos electrónicos, permitiendo:
- Agregar al carrito
- Registrarse como usuario
- Ver órdenes de compra  

Todo esto mediante **peticiones HTTP hacia el backend** provisto.

---

## ⚙️ Tecnologías Utilizadas

### 🧠 Frontend (`/front`)
- **Next.js** 15.2.4  
- **React** 19  
- **Zustand** para manejo de estado global  
- **TailwindCSS** para estilos utilitarios  
- **React Hook Form** para formularios  
- **Lucide React** y **React Icons** para íconos  
- **Slick Carousel** para carruseles  
- **React Hot Toast** para notificaciones  

### 🚀 Backend (`/back`)
- **Express.js** + TypeScript  
- **TypeORM** para conexión a base de datos **PostgreSQL**  
- **JWT** para autenticación  
- **bcrypt** para encriptación de contraseñas  
- **Swagger** para documentación de la API  

---

## 🧩 Funcionalidades
- ✅ Renderizado dinámico de productos desde la API  
- ✅ Vista principal y vista de detalle de producto  
- ✅ Carrito de compras persistente  
- ✅ Registro y login de usuarios  
- ✅ Autenticación basada en tokens JWT  
- ✅ Visualización de órdenes del usuario  
- ✅ Panel de usuario con perfil y logout  

---

## 🚀 Cómo ejecutar el proyecto

### 🔧 Requisitos previos
- Node.js v18+  
- PostgreSQL (con base de datos configurada)  
- Yarn o NPM  

### 🖥 Backend
```bash
cd back
npm install
npm start
