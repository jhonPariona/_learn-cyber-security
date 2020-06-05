# Gestión de riesgos

Marco de trabajo del NICS

## Pasos

### Preparar

- No es un paso en si es un pre paso
- QUien es el responable
- cuanto tiempo llevara
- Costo
- Identificar los canales de comunicación entre el evaluador y la organización

### Categorizar SP800-60

Que impacto tendria la perdida del CID(confidencialidad, integridad y disponibilidad) en los activos de la organización

Mantener una documentación adecuada de todos los procesos

**Formato BRM(Bussines reference Model)** Ofrece categorizaciones para el sector público

Los responsables de los activos o dueños son los encargados de categorizar el grado de impacto para los activos

```
CS <TipoInformcaion> = {(Confidencialidad, <Grado de impacto>), (Integridad, <Grado de impacto>), (Disponibilidad, <Grado de impacto>)}
```

### Seleccionar Control para cada activo

Seleccionar, adaptar y documentar los controles

Los controles deben de ser neutrales y generales (no debe de ser especifico de una marca o para un sector especifico)

Se debe de elegir un contro = control base el NIST 800-53 contempla 20 familias de controles y cada una de estas tiene sub familias

En 800-53r5-draft se puede encontrar estos controles

**AU-4 <NAME SUBCONTROL>**

- AU representa a la familia
- 4 representa a un subcontrol específico de dicha familia

### Implementar

Redacción y seguimiento de politicas, planes

Configuración de hardware y software

Usar Checklist(harrdening, benchmarking) Son instrucciones y procedimientos a seguir para configurar un producto TI. podemos encontrar algunos en [National Checklist Program Repository](https://nvd.nist.gov/ncp/repository)
Se requiere bastante doumentación en este paso

### Evaluar

Detectar si se implemento de manera correcta

Recopilar información

Se debe tener claro los parámetros de categorización, por que el impacto es alto, medio o bajo, ...

