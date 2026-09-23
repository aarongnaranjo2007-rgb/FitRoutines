# FitRoutines
Fit Routines sería una aplicación web para crear rutinas de gimnasio, registrar entrenamientos y consultar la evolución del usuario.
Un usuario podría:

    Registrarse e iniciar sesión.

    Crear rutinas de entrenamiento.

    Añadir ejercicios, series, repeticiones y peso.

    Registrar cada entrenamiento realizado.

    Consultar su progreso mediante estadísticas.

    Editar o eliminar sus rutinas.

    Marcar ejercicios como completados.

Información básica sobre el stack MERN.
MERN es un stack de desarrollo web formado por MongoDB, Express.js, React y Node.js. MongoDB lo describe como una variante del stack MEAN en la que React sustituye a Angular.

La característica principal de MERN es que permite utilizar JavaScript en prácticamente toda la aplicación:

MongoDB

MongoDB es la base de datos del proyecto.

En lugar de guardar la información en tablas y filas como ocurre en una base de datos relacional, MongoDB utiliza documentos con formato parecido a JSON. Estos documentos se agrupan en colecciones.
En TurnoFit se podrían utilizar estas colecciones:

    users: usuarios registrados.

    routines: rutinas de entrenamiento.

    exercises: ejercicios disponibles.

    workouts: entrenamientos realizados.

MongoDB resulta útil cuando los datos pueden evolucionar con facilidad y cuando se trabaja con objetos que encajan bien con la estructura de una aplicación JavaScript. La documentación oficial de MongoDB incluye ejemplos de aplicaciones completas con MongoDB, Express, React y Node.js.

Express.js

Express.js es un framework para crear servidores y APIs web sobre Node.js.

Su función sería recibir peticiones del frontend y responder con datos o realizar operaciones en la base de datos.

Express permite organizar el backend mediante:

    Rutas.

    Controladores.

    Middleware.

    Validación de datos.

    Gestión de errores.

    Autenticación.

Un middleware, por ejemplo, podría comprobar si el usuario ha iniciado sesión antes de permitirle consultar sus rutinas.

React

React se utilizaría para construir la interfaz de usuario.

La aplicación se dividiría en componentes reutilizables, por ejemplo:

    Navbar.

    LoginForm.

    RoutineCard.

    ExerciseForm.

    WorkoutHistory.

    ProgressChart.

React permite actualizar únicamente las partes de la página que cambian. Por ejemplo, al añadir un ejercicio a una rutina, no sería necesario recargar toda la aplicación.

Node.js

Node.js permite ejecutar JavaScript fuera del navegador, especialmente en el servidor.

En este proyecto se encargaría de:

    Ejecutar el backend.

    Recibir peticiones HTTP.

    Comunicarse con MongoDB.

    Gestionar la autenticación.

    Ejecutar Express.js.

    Proporcionar la API al frontend.


