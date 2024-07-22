## helm lint


```
helm lint hace una validacion general del values

No se comunica con el cluster


muestra resultado 

= 0 bien
= 1 error

```

## helm --dry run 

```
Se comunica con el cluster y obtiene informaicon del cluster,entonces tambien valida que no tenga problemas contra el mismo"

```

## Chart testing

```
Investigar
```

## Json_schema

```
Sirve para validar un formato de json , tipo de datos , etc

- Dificil de armar

- Viene un plugin que se llama
helm json-schema -> te arma el json-schema a partir de tu values correcto.
```

## POST RENDER

```
Sirve para correr scripts despues de generar el template
- Es script puede ser bash,kustomize,python
```


## HELM TEST 

```
Testea lo que esta desplegado en el cluster

Carpetas por defecto = /templates/test 
```



## CHART MUSEUM

```
Es para generar un repositorio de charts en s3 
```

## HELM UPGRADE my-release my chart --atomic --timeout 500s 

```
Si algo falla atomic hace un roll back automatico
```