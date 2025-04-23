# Actividad: Servidor HTTP Básico

En esta actividad, implementarás un servidor HTTP básico utilizando Node.js. El objetivo es crear un servidor que pueda manejar diferentes rutas y métodos HTTP, sirviendo archivos HTML y recursos estáticos.

## Estructura del Proyecto

```
.
├── public/          # Archivos estáticos (CSS, imágenes)
├── views/           # Archivos HTML
│   ├── home.html
│   ├── login.html
│   └── register.html
├── index.js         # Servidor principal
└── getContentType.js # Utilidad para determinar tipos MIME
```

## Requisitos

1. Node.js instalado en tu sistema
2. Git instalado en tu sistema
3. Cuenta en GitHub

## Pasos para Comenzar

### 1. Fork del Repositorio

1. Ve al repositorio original en GitHub
2. Haz clic en el botón "Fork" en la esquina superior derecha
3. Selecciona tu cuenta personal como destino del fork

### 2. Clonar el Repositorio

1. Abre tu terminal
2. Navega al directorio donde quieres clonar el proyecto
3. Ejecuta:
   ```bash
   git clone https://github.com/TU-USUARIO/servidor-mercado-liebre.git
   cd servidor-mercado-liebre
   ```

### 3. Instalar Dependencias

```bash
npm install
```

## Tareas a Implementar

### 1. Servir Archivos HTML

Completa la implementación para servir los archivos HTML desde la carpeta `views`:
- `/` → `home.html`
- `/login` → `login.html`
- `/register` → `register.html`

### 2. Servir Archivos Estáticos

Implementa el manejo de archivos estáticos desde la carpeta `public`:
- CSS
- Imágenes
- Otros recursos

### 3. Manejo de Formularios

Implementa el manejo de solicitudes POST para:
- `/login`
- `/register`

## Pasos para Completar la Actividad

1. Completa el código en `index.js` siguiendo los comentarios TODO
2. Crea los archivos HTML necesarios en la carpeta `views`
3. Agrega algunos archivos estáticos en la carpeta `public`
4. Prueba el servidor localmente

## Comandos Git para Subir los Cambios

1. Verifica el estado de tus cambios:
   ```bash
   git status
   ```

2. Agrega los archivos modificados:
   ```bash
   git add .
   ```

3. Crea un commit con tus cambios:
   ```bash
   git commit -m "Implementación del servidor HTTP básico"
   ```

4. Sube los cambios a tu repositorio:
   ```bash
   git push origin main
   ```

## Evaluación

Tu implementación será evaluada en base a:
- Correcto manejo de rutas
- Servicio adecuado de archivos estáticos
- Manejo apropiado de métodos HTTP
- Código limpio y bien comentado
- Estructura de proyecto organizada

## Recursos Adicionales

- [Documentación de Node.js HTTP](https://nodejs.org/api/http.html)
- [Documentación de Node.js File System](https://nodejs.org/api/fs.html)
- [Documentación de Node.js Path](https://nodejs.org/api/path.html)

## Dudas y Consultas

Si tienes alguna duda durante la implementación, no dudes en consultar con el profesor o tus compañeros. 