# TaskMaster - Aplicación de Gestión de Tareas

## Descripción

TaskMaster es una aplicación diseñada para mejorar la productividad, permitiendo gestionar tareas de manera eficiente. Con esta herramienta, los usuarios pueden organizar sus activadades diarias de manera sencilla y eficaz.

## Características

- :white_check_mark:Creación y edición de tareas
- :calendar:Asignación de fechas límite y prioridades.
  - Prioridad baja, media y alta.
  - Fechas límite personalizadas con control de calendario.
- :file_folder:Organización en categorías y etiquetas.
- :white_check_mark:Marcar tareas como completadas.
- :bell:Notificaciones y recordatorios automáticos.
- :clipboard:Visualización en lista y tablero Kanban.

## Instalación

Para instalar y ejecutar la aplicación, sigue los siguientes pasos:

\# Clonar el repositorio
git clone https://github.com/usuario/taskmaster.git  
cd taskmaster

\# Instalar dependencias
npm install

\# Ejecutar la aplicación
npm start

## Uso de la API

TaskMaster proporciona una API REST para gestionar tareas. A continuación, un ejemplo de cómo crear una tarea usando JavaScript:

```javascript
fetch('https://api.taskmaster.com/tasks', {
  method: 'POST',
  headers: {
    'Content-Type': 'application/json'
  },
  body: JSON.stringify({
    title: 'Comprar leche',
    description: 'Comprar leche en el supermercado',
    priority: 'alta',
    dueDate: '2024-07-01'
  })
})

```

## Fórmula de Productividad

La eficiendia del usuario es calcula con la siguiente fórmula: 