# Calenda

Este repositorio funciona como **documentación central** y punto de referencia del proyecto.  
El código está separado en dos repositorios independientes:

- Frontend (Netlify): [Calenda-frontend](https://github.com/Lesel22/GestorEvento-frontend)
- Backend (Render): [Calenda-backend](https://github.com/Lesel22/GestorEvento-backend)

---

## 🚀 Demo (Deploys)

- Frontend: [Calenda-app](https://calenda-d22.netlify.app/)
- Backend API: https://mi-proyecto.onrender.com

---

## 🧩 Capturas
<img width="1907" height="807" alt="image" src="https://github.com/user-attachments/assets/bcc6fecd-75dc-415f-8f9d-e07a570ca52e" />


---

## ✨ Descripción

Mi Proyecto es una aplicación web fullstack con una arquitectura **SPA + API REST**.  
El frontend consume la API del backend para gestionar autenticación, datos de usuario y funcionalidades principales.

---

## 🏗️ Arquitectura

- **Frontend**: SPA desplegada en Netlify  
- **Backend**: API REST desplegada en Render  
- **Autenticación**: JWT con refresh token en cookie `httpOnly`  
- **Comunicación**: HTTPS con endpoints protegidos  

---

## 📌 Estructura de repositorios

### Frontend
- Vite + React (Vue)
- UI responsive
- Manejo de estado y rutas
- Autenticación y manejo de sesión

### Backend
- Django 
- API REST con JWT
- Persistencia en DB (PostgreSQL)
- Endpoints de autenticación y CRUD

---

## 🧠 Roadmap (opcional)

- [ ] 2FA (OTP)
- [ ] Roles y permisos
- [ ] Tests e2e
- [ ] Mejoras de performance
