🌍 Web WordPress - ODS 3: Salud y Bienestar
Este proyecto es una página web desarrollada con WordPress y Docker, dedicada al Objetivo de Desarrollo Sostenible (ODS) 3 de la ONU: Garantizar una vida sana y promover el bienestar para todos en todas las edades.

🚀 Tecnologías utilizadas
🐳 Docker + Docker Compose
🖥️ WordPress
🐬 MariaDB
🔒 Backup de datos y volúmenes persistentes
📂 Estructura del proyecto
├── docker-compose.yaml # Configuración de los servicios WordPress y MariaDB ├── backup_wordpress/ # Copias de seguridad de los volúmenes (contenido + base de datos) │ ├── wordpress_data.tar.gz │ └── mariadb_data.tar.gz └── README.md # Este archivo

🛠️ Cómo ejecutar el proyecto Clona este repositorio:

git clone https://github.com/marinettoo/wordpress-ods3.git cd wordpress-ods3

Lanza los servicios:

docker-compose up -d Accede a tu sitio web en: http://localhost

🧠 Sobre el contenido La web incluye:

Secciones informativas sobre el ODS 3

Frases destacadas de líderes políticos

Socios comprometidos con la salud global

Diseño basado en el tema Peregrine

🧳 Créditos Desarrollado por Jesús Pérez Marinetto como parte de un proyecto educativo con fines sociales.

📝 Licencia Este proyecto puede usarse libremente con fines educativos o de concienciación. Si lo reutilizas, ¡menciona al autor!
