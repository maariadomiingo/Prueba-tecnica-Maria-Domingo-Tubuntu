# 🚀 Prueba Técnica: Aplicación Web con API REST

Este proyecto contiene una aplicación web desarrollada con **React, Vite y Tailwind CSS** en el frontend y una **API REST con Express y TypeScript** en el backend.

## 📂 Estructura del Proyecto

```
prueba-técnica/
├── api/             # API REST (Backend con Express.js y TypeScript)
│   ├── node_modules/  
│   ├── public/      
│   ├── src/         # Código fuente del backend
│   ├── package.json 
│   ├── tsconfig.json
│   ├── package-lock.json
│
├── web/             # Aplicación web (Frontend con React y Vite)
│   ├── node_modules/  
│   ├── public/      
│   ├── src/         # Código fuente del frontend
│   ├── .gitignore
│   ├── index.html
│   ├── package.json 
│   ├── package-lock.json
│   ├── eslint.config.js
│   ├── postcss.config.js
│   ├── tailwind.config.js
│   ├── tsconfig.app.json
│   ├── tsconfig.json
│   ├── tsconfig.node.json
│   ├── vite.config.ts
│
├── README.md        # Documentación del proyecto
```

---

## 🔥 Instalación y Ejecución

### 1️⃣ Clonar el Repositorio

```bash
git clone https://github.com/maariadomiingo/Prueba-tecnica-Maria-Domingo-Tubuntu.git
cd Prueba-tecnica-Maria-Domingo-Tubuntu
```

---

## 🌐 Instalación y Ejecución del Frontend (React + Vite)

1️⃣ Accede a la carpeta `web`:

```bash
cd web
```

2️⃣ Instala las dependencias:

```bash
npm install
```

3️⃣ Inicia el servidor de desarrollo:

```bash
npm run dev
```

📌 La aplicación se ejecutará en: `http://localhost:5173/`

---

## 🖥️ Instalación y Ejecución del Backend (API con Express)

1️⃣ Vuelve a la raíz del proyecto y accede a la carpeta `api`:

```bash
cd ../api
```

2️⃣ Instala las dependencias:

```bash
npm install
```

3️⃣ Inicia el servidor:

```bash
npx ts-node src/index.ts
```

📌 La API se ejecutará en: `http://localhost:3000/`

---

## 📡 Conexión entre Backend y Frontend
El frontend está configurado para realizar peticiones a `http://localhost:3000`, por lo que es importante que la API esté corriendo antes de iniciar la aplicación web.

Si necesitas modificar la URL base de la API, edita los archivos correspondientes en `web/src/`.

---

## 🚀 Tecnologías Utilizadas

- **Frontend:** React, Vite, TypeScript, Tailwind CSS
- **Backend:** Node.js, Express, TypeScript

📌 **Repositorio GitHub:** [Prueba Técnica - María Domingo](https://github.com/maariadomiingo/Prueba-tecnica-Maria-Domingo-Tubuntu)


