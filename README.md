# QMP-VII

[Enunciado](https://docs.google.com/document/d/1ERlDghk47Yc1_V1SQ7oCnZAC4bubHx7ZhQXS3naKMJA/edit#)

---

# Requerimientos

### 1. Como usuarie de QueMePongo quiero ver todas las prendas que tengo en mi guardarropas desde el navegador para poder administrarlas

+ Ruta REST (URI + Método)

GET/usuarios/{id_usuario}/guardarropas/prendas

+ Información que se enviaría en el cuerpo

id_usuario

+ Cuerpo de respuesta posible

conjunto de ids de prendas

<br/>
<br/>

### 2. Como usuario de QueMePongo, quiero crear una prenda desde el navegador

+ Ruta REST (URI + Método)

POST/prendas

+ Información que se enviaría en el cuerpo

no creo que haga falta

+ Cuerpo de respuesta posible

creo que no aplica, solo habria que revisar el codigo de respuesta

<br/>
<br/>

### 3. Como usuarie de QueMePongo quiero ver una prenda en particular que tengo en mi guardarropas para poder editarla

+ Ruta REST (URI + Método)

PUT/usuarios/{id_usuario}/guardarropas/prendas/{id_prenda}

+ Información que se enviaría en el cuerpo

id_usuario e id_prenda

+ Cuerpo de respuesta posible

creo que no aplica, solo habria que revisar el codigo de respuesta

<br/>
<br/>

### 4. Como usuarie de QueMePongo, quiero poder eliminar una prenda de mi guardarropas

+ Ruta REST (URI + Método)

DELETE/usuarios/{id_usuario}/guardarropas/prendas/{id_prenda}

+ Información que se enviaría en el cuerpo

id_usuario e id_prenda

+ Cuerpo de respuesta posible

creo que no aplica, solo habria que revisar el codigo de respuesta

<br/>
<br/>

### 5. Como usuarie de QueMePongo, quiero poder ver mis eventos para administrarlos

+ Ruta REST (URI + Método)

GET/usuarios/{id_usuario}/eventos

+ Información que se enviaría en el cuerpo

id_usuario

+ Cuerpo de respuesta posible

conjunto de ids de eventos

<br/>
<br/>

### 6. Como usuarie de QueMePongo, quiero poder abrir las sugerencias de prendas para un evento 
en mi navegador

+ Ruta REST (URI + Método)

GET/usuarios/{id_usuario}/sugerencias_de_prendas

+ Información que se enviaría en el cuerpo

id_usuario

+ Cuerpo de respuesta posible

conjunto de ids de prendas

<br/>
<br/>
