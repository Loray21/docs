## AWS CLOUD PARTICIONER

## Regiones
Es global se encuntra en todo el mundo.
Por ejemplo us-east-1

## que es un region?
Es un grupo de centro de datos?

## Como elegir una region de aws?

- Cumplimiento de requisitos legales
- Proximidad a los clientes: latencia reducida
- Servicios disponibles es un una region
- Precios: los precios varian segun la region.

## Zonas de disponibilidad
Una region se divide en zonas de disponibilidad, normalmente 3(min 3,max 6)  
Cada zona es un centro de datos independiente y se encuentan aisladas por si ocurre una catastrofe
los datos se encuentran replicados.

## Como se paga?

Por uso.

##  EDGE LOCALTIONS.
+450 PTOS

## SERVICIOS GLOBALES

IAM: Acceso a la cuenta de amazon  
ROUTE 53(Servicio DNS)  
CLOUDFront( Red de entrega de contenido)    
WAF(Firewal de apps webs)

## SERVICOS REGIONALES
Amazon EC2(INFRA COMO SERVICIO)
Elastic beanstalk(Pass)
Lambda(Funcion como servicio)
Rekognition(Sass)


# Responsabilidad compartida cliente/aws

El cliente tiene la siguiente responsabilidad:
- datos del cliente
- administracon de acceso, identidades, apps, plataforma
- firewal, redes, y sist operativo
- cifrado  
Aws
- software(computacion,almacenamiento, bbdd,redes)
- global (regiones,z disponibilidad, ubicaciones)
