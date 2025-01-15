## Descipcion de la  aplicacion.

Aplicacion desarrollada para simular la interacion mediante un chat de texto en tiempo real entre usuarios/moderadores durante una clase virtual en vivo.



# Instrucciones para Iniciar la Aplicación

Esta guía detalla los pasos necesarios para clonar, configurar y ejecutar la aplicación **Kuepa Chat**. Asegúrate de seguir cada paso cuidadosamente para un correcto funcionamiento.

---

## Requisitos Previos

1. **Node.js**: Asegúrate de tener instalada la versión `16.20.2` de Node.js.
2. **MongoDB**: La aplicación utiliza MongoDB como base de datos. Debes tener MongoDB instalado y funcionando localmente.
3. **Git**: Es necesario para clonar el repositorio.

---

## Tecnologías Utilizadas

### Frontend

- **React**: `18.3.1`
- **Bootstrap**: `5.3.3`
- **React Router DOM**: `7.1.1`
- **React Hook Form**: `7.54.2`
- **Socket.io Client**: `4.8.1`

### Backend

- **Express**: `4.21.2`
- **Mongoose**: `8.9.5`
- **Socket.io**: `4.8.1`
- **JSON Web Token**: `9.0.2`
- **Dotenv**: `16.4.7`

---

## Pasos para la Configuración

### 1. Clonar el Repositorio

```bash
git clone https://github.com/](https://github.com/CardoneLeandro/Kuepa-Demo-Tecnica.git
```

### 2. Instalar Dependencias

Accede a los directorios `API` y `CLIENT` por separado e instala las dependencias necesarias ejecutando:

```bash
npm install
```

### 3. Configuración del Backend

Crea un archivo `.env` en la carpeta `API` con las siguientes variables de entorno:

```env
PORT=5001
DB_URL=mongodb://localhost:27017/
```

- `PORT`: Puerto en el que correrá la API.
- `DB_URL`: URL de conexión a la base de datos MongoDB.

### 4. Configuración de MongoDB

1. Inicia el servicio de MongoDB ejecutando en una terminal:

   ```bash
   mongod
   ```

2. Verifica la conexión utilizando **MongoDB Compass** (opcional).

---

## Ejecutar la Aplicación

### 1. Backend (API)

Abre una terminal en el directorio `API` y ejecuta:

```bash
npm run dev
```

### 2. Frontend (CLIENT)

Abre otra terminal en el directorio `CLIENT` y ejecuta:

```bash
npm run dev
```

---

## Notas

- Asegúrate de tener el servicio de MongoDB corriendo antes de iniciar la aplicación.
- Si encuentras algún problema, revisa los logs de la terminal para identificar posibles errores.

---

## Vista Previa

![Vista previa de la aplicación]((https://leandro-cardone.imgbb.com/))
