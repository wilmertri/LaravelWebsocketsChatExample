# Laravel WebSockets Chat Example 
Desarrollo de una Aplicación Chat de Ejemplo utilizando el Framework **Laravel** de PHP y haciendo uso de WebSockets

## Requerimiento de versiones
- Laravel: **10**

## Librerias y herramientas utilizadas

- [Laravel WebSockets of BeyondCode - version 1.14](https://beyondco.de/docs/laravel-websockets/getting-started/installation)
- [Laravel Pusher Notifications - version 7.2](https://pusher.com/tutorials/web-notifications-laravel-pusher-channels/)
- [Vue Js - version 2.6.4](https://cdnjs.com/libraries/vue/2.6.14)
- [JQuery - version 3.6.3](https://releases.jquery.com/)
- [Pusher JavaScript library for the browser - version 8.0.1](https://cdnjs.com/libraries/pusher)
- [Bootstrap Framework - version 5.0](https://getbootstrap.com/docs/5.0/getting-started/introduction/)


## Instalación de Aplicación

Primero clonar este repositorio, instalar las dependencias y configurar tu archivo .env

```
git clone https://github.com/wilmertri/LaravelWebsocketsChatExample.git
cd LaravelWebsocketsChatExample
composer install
cp .env.example .env
```

- Luego correr las migraciones

```
php artisan migrate
```

## Ejecución Aplicación
Escribir y ejecutar el comando:
```
php artisan serve
```

## Comando para procesar eventos/tareas en segundo plano

En una terminal diferente escribir y ejecutar el comando:
```
php artisan queue:work
```

## Comando para iniciar el servidor de WebSockets

En una terminal diferente escribir y ejecutar el comando:
```
php artisan websockets:serve
```

## Uso de Aplicación
1. En la aplicación habra un formulario para la conexión y desconexión de las notificaciones con Pusher donde podrá enviar un nombre (o ninguno).
2. Dar clic en el botón **Connect** o **Disconnect** según sea el caso.
3. Enviar y recibir mensajes escribiendo en la caja de texto y dando clic en el botón **Send Message**.

