AgendaContactosJavaFX

Aplicación de escritorio real para la gestión de contactos personales y profesionales con autenticación, estadísticas visuales y almacenamiento seguro de datos.
Desarrollada en JavaFX como proyecto open source de referencia y práctica para DAM.

Jonatan Tajada Rico – 2025

📑 Tabla de contenidos
Resumen

Estado del desarrollo

Mapa mental

Características principales

Tecnologías utilizadas

Instalación y puesta en marcha

Estructura del proyecto

Documentación

Autoría y créditos

Licencia

📝 Resumen
AgendaContactosJavaFX es una aplicación de gestión de contactos con enfoque en seguridad, usabilidad y buenas prácticas de desarrollo. Permite almacenar, buscar y editar contactos, con autenticación de usuarios y generación de estadísticas visuales gracias a la integración de una librería profesional de gráficos.
Incluye interfaz gráfica moderna con JavaFX + CSS y almacenamiento persistente.
Pensada para aprender Java modular, arquitectura DAO-Service y desarrollo de GUIs reales.

🧠 Estado del desarrollo
Proyecto completo y funcional: CRUD de contactos, autenticación y gestión de usuarios, estadísticas visuales, gestión de imágenes y estructura modular.

En evolución: Preparado para ampliar nuevas funcionalidades o integrar otros módulos (exportación/importación, backup, etc.) en futuras versiones.

🗺️ Mapa mental
![Mapa mental de la arquitectura de AgendaContactosJavaFX](../assets/img/agendaJavaFX/markmap AgendaFX.png)

🚀 Características principales

CRUD completo de contactos (añadir, editar, borrar, listar)

Autenticación de usuarios y registro seguro

Gestión de imágenes de los contactos (avatar personalizado)

Generación de estadísticas visuales
(gráficas y reportes usando librería de gráficos para JavaFX)

Validaciones estrictas de datos (email, teléfono, duplicados…)

Interfaz gráfica profesional con JavaFX + CSS

Arquitectura modular: separación clara de modelo, vista y controlador (MVC)

Patrón DAO-Service y buenas prácticas para mantenimiento y escalabilidad

Documentación clara y ejemplos de uso

🛠️ Tecnologías utilizadas

Java 17+

JavaFX 17 (GUI y gráficos)

FXML (diseño de vistas)

CSS (estilizado visual)

Laflat / JFreeChart (librería de gráficos para estadísticas visuales)

DAO-Service (acceso y lógica de negocio)

IDE: Eclipse

Git (control de versiones)

🏗️ Instalación y puesta en marcha

Clona el repositorio:
git clone https://github.com/jonatanTajada/AgendaContactosJavaFX.git

Configura las dependencias de JavaFX y la librería de gráficos (laflat/JFreeChart) si tu IDE lo requiere.

Ejecuta el proyecto:

Abre el archivo Main.java dentro de /src/application/ y ejecútalo como aplicación Java.

Requiere Java 17+ y JavaFX configurado en el IDE.

(Opcional) Usa el ejecutable:

También puedes descargar el .jar generado para ejecución directa.

📁 Estructura del proyecto

AgendaContactosJavaFX/
├── src/
│   ├── application/              # Main y estilos
│   ├── controlador/              # Controladores JavaFX
│   ├── modelo/                   # Entidades y DAO
│   ├── modelo.dao/               # DAO e interfaces
│   ├── modelo.service/           # Lógica de negocio (services)
│   ├── utilities/                # Utilidades generales (gestor de archivos, etc)
│   └── vista/                    # Vistas FXML (pantallas GUI)
│
├── imágenes/                     # Carpeta de imágenes de usuarios/contactos
├── markmap AgendaFX.png          # Mapa mental de la arquitectura
├── Guía de Uso AgendaFX.pdf      # Manual de usuario (si disponible)
└── README.md

📚 Documentación
Guía de uso (PDF): ver Guía de Uso AgendaFX.pdf

Mapa mental: incluido en /assets/img/agendaJavaFX/

Ejemplos de uso: capturas y pasos incluidos en la documentación y en el portfolio.

👤 Autor
Jonatan Tajada Rico

🏷️ Licencia
Uso libre para revisión y aprendizaje.
Para uso comercial, contactar con el autor.
