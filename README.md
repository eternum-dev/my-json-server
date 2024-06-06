# My-json-server

## Descripción

Esta es mi implementación de json-server con las configuraciones básicas para poder aplicarlas a mis proyectos.

## Scripts

### Clonar proyecto

```
   git clone https://github.com/eternum-dev/my-json-server
```

### Instalar dependencias

```
   npm install
```

### Levantar el proyecto

```
    npm start
```

## Configuración

Desde `db.json` puedes agregar tanto endpoints como datos para ser consumidos.

```
   "nombre-de-tu-endpoint": [
   { "id": "1", "clave": "valor a guardar" },
   { "id": "2", "clave2": "valor2 a guardar" }
  ],
```

## Uso

Una vez que el servidor está en funcionamiento, puedes realizar peticiones HTTP a los endpoints que hayas definido en `db.json`. Por ejemplo:

- **_GET_** /nombre-de-tu-endpoint para obtener todos los datos del endpoint.
- **_POST_** /nombre-de-tu-endpoint para agregar un nuevo dato.
- **_PUT_** /nombre-de-tu-endpoint/:id para actualizar un dato existente.
- **_DELETE_** /nombre-de-tu-endpoint/:id para eliminar un dato existente.

## Recursos adicionales

Para más información sobre json-server y sus capacidades, puedes visitar la [documentación oficial](https://github.com/typicode/json-server).
