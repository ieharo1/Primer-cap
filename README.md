# 🛡️ Security Playground - Laboratorio de Seguridad Web

Una aplicación interactiva de análisis y simulación de seguridad web, desarrollada con Angular 17+. Totalmente funcional y lista para usar.

## 🚀 Características

### Módulos Disponibles

1. **🔐 Analizador de Contraseñas**
   - Cálculo de entropía real
   - Estimación de tiempo de crack (CPU, GPU, distribuido)
   - Detección de vulnerabilidades (patrones comunes, secuencias, repeticiones)
   - Generador de contraseñas seguras con opciones personalizables

2. **#️⃣ Generador de Hash**
   - SHA-256 y SHA-512 usando Web Crypto API
   - Comparador de hashes
   - Copiar al portapapeles

3. **🎫 Validador JWT**
   - Decodifica header y payload
   - Verifica expiración del token
   - Detecta tokens inseguros (alg: none)
   - Muestra advertencias de seguridad

4. **🔍 Detector de Vulnerabilidades en Inputs**
   - Detecta SQL Injection
   - Detecta XSS (Cross-Site Scripting)
   - Detecta Command Injection
   - Explicaciones y recomendaciones de remediación

5. **📋 Analizador de Headers de Seguridad**
   - CSP (Content-Security-Policy)
   - X-Frame-Options
   - HSTS (Strict-Transport-Security)
   - X-Content-Type-Options
   - Referrer-Policy
   - Permissions-Policy
   - Puntuación de seguridad

## 🛠️ Instalación y Ejecución

### Requisitos Previos
- Node.js 18+
- npm 9+

### Instalar Dependencias
```bash
npm install
```

### Iniciar Servidor de Desarrollo
```bash
npm start
```
Luego abre: **http://localhost:4200**

### Build para Producción
```bash
npm run build
```

### Desplegar a GitHub Pages
```bash
npm run deploy
```

## 📁 Estructura del Proyecto

```
├── src/
│   ├── app/
│   │   ├── core/services/       # Servicios principales
│   │   │   ├── crypto.service.ts
│   │   │   ├── password.service.ts
│   │   │   ├── jwt.service.ts
│   │   │   ├── input-detector.service.ts
│   │   │   └── headers-simulator.service.ts
│   │   ├── app.ts               # Componente principal
│   │   ├── app.html             # Template principal
│   │   └── app.css              # Estilos del componente
│   └── styles.css               # Estilos globales
├── angular.json
├── package.json
└── tsconfig.json
```

## 🎨 Diseño

- Tema oscuro con acentos neón (verde, cyan, ámbar)
- Tipografía: JetBrains Mono + Outfit
- UI profesional tipo herramienta SaaS
- Totalmente responsivo

## 📧 Contacto

👨‍💻 **Isaac Esteban Haro Torres**
- 📧 Email: zackharo1@gmail.com
- 📱 WhatsApp: 098805517
- 💻 GitHub: https://github.com/ieharo1
- 🌐 Portafolio: https://ieharo1.github.io/portafolio-isaac.haro/

---

© 2026 Isaac Esteban Haro Torres - Todos los derechos reservados.
