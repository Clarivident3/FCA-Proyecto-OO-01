# ID
- UC - 003
  
# Caso de uso
 * Registrar alumno
   
## Actores
 * Profesor
    
## Tipo 
 * Primario
   
## Partes interesadas e intereses:
- El profesor desea registrar un nuevo alumno 
- El alumno podrá utilizar su tarjeda de "MI" para el registro de asistencia
  
## Breve descripcion
- El profesor podra dar de alta un nuevo alumno en el sistema, asignandole un grupo y enlazando el registro del alumno en la tarjeta de MI (movilidad integrada)

## Disparador
- El profesor ingresara a la opcion de "Registrar nuevo alumno"

## Relaciones
- **Inclusion**: Registro Tarjeta

## Flujo normal de eventos
1. El profesor selecciona el grupo al que registrara el alumno
2. El profesor ingresa al apartado de registro de alumno
3. El profesor ingresa el nombre, número de cuenta y NFC de la tarjeta de Movilidad Integrada (MI) del alumno que se desea agregar
4. El sistema verifica que no exista un registro previo del alumno que se desea agregar
5. El flujo continua en el caso de uso Registro Tarjeta
6. Se da de alta el NFC con los datos asignados
7. El sistema muestra mensaje de éxito con los datos que se le asignaron

