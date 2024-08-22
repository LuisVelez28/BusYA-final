# PROYECTO BUSYA

### Este proyecto ofrece una solución integral para la gestión de servicios de transporte público. A continuación, se detallan los requisitos y pasos necesarios para ejecutar nuestro proyecto de manera local.
## Requisitos y pasos para ejecutar nuestro proyecto:
### Clonar el repositorio: https://github.com/jpinchao/BusYaPruebas.git

### Instalar Composer, herramienta de administración de dependencias: https://getcomposer.org/download/    

### Instalar y ejecutar un entorno de servidor web local que incluye Apache y MySQL: https://www.apachefriends.org/es/index.html

### Acceder a phpMyAdmin a través de http://localhost/phpmyadmin/ y crear una base de datos llamada "laravel"

### Abrir el repositorio, copiar el archivo .env.example y dejarlo nombrado solo con .env

### reemplazar los datos del .env que tengan este tipo de datos por estos de acá
    MAIL_MAILER=smtp
    MAIL_HOST=smtp.mailersend.net
    MAIL_PORT=587
    MAIL_USERNAME=MS_6ZEpsw@trial-ynrw7gy8wzn42k8e.mlsender.net
    MAIL_PASSWORD=03zL5VvaI3WxEoeU
    MAIL_ENCRYPTION=tls
    MAIL_FROM_ADDRESS=MS_6ZEpsw@trial-ynrw7gy8wzn42k8e.mlsender.net
    MAIL_FROM_NAME="${APP_NAME}"
     
### Ejecutar los siguientes comandos(uno a la vez) en una terminal dentro de nuestro repositorio:
    composer update
    php artisan migrate:fresh --seed
    php artisan key:generate
    php artisan serve 

## Credenciales para Pruebas:
### Admin

    Email:
    admin@admin.com

    Contraseña:
    admin

### Cliente

    Email:
    cliente1@gmail.com

    Contraseña:
    cliente1

### Empleado(Conductor)

    Email:
    empleado1@gmail.com

    Contraseña:
    empleado1

### aduditor

    Email:
    auditor@auditor.com

    Contraseña:
    auditor
