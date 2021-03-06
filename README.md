# Chat asíncrono

Este proyecto le permite gestionar  un modelo cactus a través de una Api creada con Django restframework.

el protocolo WebSocket proporciona una comunicación bidireccional entre el servidor y el cliente. Podemos intercambiar información asíncrona sin la obligación de hacer más peticiones u obligar a un refresco del navegador; es posible enviar información al servidor en cualquier momento o recibirla
### Algunas caracteristicas principales: 

#### -Integración completa con Django y Websockets, por medio de Channels.
#### -Respuestas asincronas con el objetivo de mejorar el rendimiento.
#### -Salas individuales para mantener conversaciones privadas.
#### -Front-End minimalista con Javascript para su fácil implementación en otros sistemas.


## Getting Started

Estas instrucciones le proporcionarán una copia del proyecto en funcionamiento en su máquina local con fines de desarrollo y prueba.

### Prerrequisito

Si quieres probar, necesitarás estos requisitos previos

```
Python > 3.6
```

### Instalación

Primero, clona el proyecto en tu computadora

```

```

luego, cree un entorno virtual para el proyecto, puede usar virtualenvwrapper-win si su sistema operativo es Windows

```
pip install virtualenvwrapper-win
mkvirtualenv <nombre_del_entorno>
```

después de eso, instale los paquetes en requirements.txt para asegurarse de tener todo lo necesario

```
pip install -r requirements.txt
```

finalmente, realice las migraciones correspondientes al modelo

```
py manage.py makemigrations
py manage.py migrate
```

Listo! ya puedes ejecutarlo

```
py manage.py runserver
```

Ingresa a localhost:8000/admin o localhost:8000/swagger y explore

Nota: necesitará credenciales de usuario para acceder al panel de administración de Django y para poder hacer uso de los diferentes endpoints de Swagger, asegúrese de crear un usuario con

```
py manage.py createusersuperuser
```

## Autor

* **John Vega**

## Screenshots
