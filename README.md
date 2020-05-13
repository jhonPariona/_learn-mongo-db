# 💾 Learning MongoDB

## Learning

[🐧 Mongo university](https://university.mongodb.com/)

## mongod

🚀 **Demonio** : programa o proceso que es ejecutado pero no interactuamos
directamente con el.

🦊 **mongod** proceso principal del demonio mongoDB, maneja las conecciones,
solicitudes, persistencia de datos. contiene las configuraciones.

```bash
$ mongod
```

🎈 **Configuracion defecto:**

- port:27017
- dbpath:`/data/db`
- bind-ip: localhost (solo los clientes localhost pueden conectarse)
- auth:disable (la autenticacion de los clientes esta desactivado)

## Clientes

⚡ **mongo shell** Está programado para comunicarse con mongod.

```bash
# iniciar mongo para insertar consultas
$ mongo

# cerrar la conexion y apagar mongod
$ use admin
$ db.shutdownServer()
$ exit
```
