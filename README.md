Notas Liceo - Sistema de Gestión de Equipos

Aplicación web desarrollada en React y Firebase para el registro y gestión técnica de equipos del Liceo La Portada.

Descripción

Esta herramienta permite a los usuarios técnicos registrar especificaciones de equipos informáticos (procesador, RAM, almacenamiento, etc.) y dejar notas de mantenimiento. Los datos se almacenan en tiempo real en la nube utilizando Firebase Firestore.

Tecnologías Utilizadas

React: Biblioteca para la interfaz de usuario.

Firebase Firestore: Base de datos NoSQL en tiempo real.

Firebase Auth: Autenticación anónima para permitir el uso sin registro previo.

Tailwind CSS: Framework para el diseño responsivo y moderno.

Lucide React: Biblioteca de iconos para la interfaz.

Configuración y Despliegue

Para desplegar este proyecto en plataformas como Vercel o Netlify:

Requisitos: Asegúrate de tener instalado Node.js.

Instalación:

npm install


Ejecución local:

npm run dev


Build:

npm run build


Nota: En Vercel, asegúrate de configurar el "Output Directory" como dist y el "Build Command" como npm run build.

Estructura del Proyecto

App.jsx: Contiene toda la lógica de la aplicación, incluyendo el formulario de registro, la conexión a Firebase y la visualización de notas.

index.html: Punto de entrada del proyecto.

Licencia

Proyecto interno para el equipo técnico del Liceo La Portada.