
==============================
🇪🇸 README - Tienda Puntana (Plantilla Marketplace PHP)
==============================

📌 Requisitos técnicos
- Hosting con PHP 7.4 o superior
- MySQL
- phpMyAdmin
- Permisos de escritura en carpetas: img/, qr/, vendor/

🔧 Instalación paso a paso
1. Subir archivos
- Ingresá a tu hosting (por ejemplo, Hostinger o DonWeb)
- Subí el archivo .zip al directorio public_html/ desde el Administrador de Archivos
- Descomprimí el .zip ahí mismo

2. Crear la base de datos
- Entrá a MySQL / Bases de datos y creá una nueva
- Luego accedé a phpMyAdmin y usá la opción "Importar"
- Seleccioná el archivo base_datos.sql incluido y ejecutá la importación

3. Configurar conexión a la base de datos
- Editá el archivo includes/conexion.php con los datos de tu hosting:

$conexion = mysqli_connect("localhost", "TU_USUARIO", "TU_CONTRASEÑA", "TU_BASE");

4. Acceso inicial
- Accedé a tu dominio y creá una cuenta o usá estas para pruebas:

Administrador:
Email: admin@demo.com
Clave: admin123

Vendedor:
Email: vendedor@demo.com
Clave: vendedor123

🧩 Personalización
- Logo principal: reemplazá img/logo.png
- Banner de portada: img/categorias/banner.jpg
- Nombre del sitio: editar en includes/header.php
- Colores y estilos: estilos.css

📞 Soporte Personalizado
Incluye atención personalizada por Meet o Zoom para guiarte paso a paso en la instalación, configuración y personalización de la plataforma.


==============================
🇺🇸 README - Tienda Puntana (Marketplace PHP Template)
==============================

📌 Requirements
- Hosting with PHP 7.4 or higher
- MySQL support
- phpMyAdmin
- Write permissions for: img/, qr/, vendor/

🔧 Installation steps
1. Upload the files
- Login to your hosting (e.g. Hostinger or DonWeb)
- Upload the .zip file to public_html/ using the File Manager
- Extract the contents there

2. Create the database
- Go to MySQL Databases and create a new one
- Open phpMyAdmin, go to “Import” and upload the base_datos.sql file

3. Database connection
- Edit includes/conexion.php with your credentials:

$conexion = mysqli_connect("localhost", "DB_USER", "DB_PASSWORD", "DB_NAME");

4. First access
- Visit your domain and create an account, or use:

Admin:
Email: admin@demo.com
Password: admin123

Seller:
Email: vendedor@demo.com
Password: vendedor123

🎨 Customization
- Main logo: replace img/logo.png
- Homepage banner: img/categorias/banner.jpg
- Site title: edit in includes/header.php
- Colors & styles: estilos.css

📞 Personalized Support
Includes one-on-one support via Meet or Zoom to guide you step by step through setup, configuration, and customization.
