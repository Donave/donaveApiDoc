---
title: API Reference

language_tabs:
- bash
- javascript

includes:

search: true

toc_footers:
- <a href='http://github.com/mpociot/documentarian'>Documentation Powered by Documentarian</a>
---

# Info

Welcome to the generated API reference.

# Available routes
#general
## /api/medicamentos

> Example request:

```bash
curl "http://localhost//api/medicamentos" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost//api/medicamentos",
    "method": "GET",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET /api/medicamentos`

`HEAD /api/medicamentos`


## /api/medicamento/{id}

> Example request:

```bash
curl "http://localhost//api/medicamento/{id}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost//api/medicamento/{id}",
    "method": "GET",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET /api/medicamento/{id}`

`HEAD /api/medicamento/{id}`


## /api/medicamentos/nombre/{nombre}

> Example request:

```bash
curl "http://localhost//api/medicamentos/nombre/{nombre}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost//api/medicamentos/nombre/{nombre}",
    "method": "GET",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET /api/medicamentos/nombre/{nombre}`

`HEAD /api/medicamentos/nombre/{nombre}`


## /api/solicitudes/activas/{pagina}

> Example request:

```bash
curl "http://localhost//api/solicitudes/activas/{pagina}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost//api/solicitudes/activas/{pagina}",
    "method": "GET",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET /api/solicitudes/activas/{pagina}`

`HEAD /api/solicitudes/activas/{pagina}`


## /api/solicitudes/finalizadas/{pagina}

> Example request:

```bash
curl "http://localhost//api/solicitudes/finalizadas/{pagina}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost//api/solicitudes/finalizadas/{pagina}",
    "method": "GET",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET /api/solicitudes/finalizadas/{pagina}`

`HEAD /api/solicitudes/finalizadas/{pagina}`


## /api/solicitudes/{elemento}/{pagina}

> Example request:

```bash
curl "http://localhost//api/solicitudes/{elemento}/{pagina}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost//api/solicitudes/{elemento}/{pagina}",
    "method": "GET",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET /api/solicitudes/{elemento}/{pagina}`

`HEAD /api/solicitudes/{elemento}/{pagina}`


## /api/solicitud/{url}

> Example request:

```bash
curl "http://localhost//api/solicitud/{url}" \
-H "Accept: application/json"
```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost//api/solicitud/{url}",
    "method": "GET",
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```

> Example response:

```json
null
```

### HTTP Request
`GET /api/solicitud/{url}`

`HEAD /api/solicitud/{url}`


## /api/solicitud

> Example request:

```bash
curl "http://localhost//api/solicitud" \
-H "Accept: application/json" \
    -d "correo_electronico"="lenny.russel@example.com" \
    -d "id_elemento"="7" \

```

```javascript
var settings = {
    "async": true,
    "crossDomain": true,
    "url": "http://localhost//api/solicitud",
    "method": "POST",
    "data": {
        "correo_electronico": "lenny.russel@example.com",
        "id_elemento": 7
},
        "headers": {
    "accept": "application/json"
    }
}

$.ajax(settings).done(function (response) {
console.log(response);
});
```


### HTTP Request
`POST /api/solicitud`

#### Parameters

Parameter | Type | Status | Description
--------- | ------- | ------- | ------- | -----------
    correo_electronico | email |  required  | 
    id_elemento | integer |  required  | 

