# Buenas practicas de Control de Versiones

- Grupo de trabajo en github
- ReadMe del proyecto
  - Detallando caracteristicas y requerimientos principales

- Cada versión importante se documente
  - Num de versión. Usando Tags de git. Los tags en github se usan con la sintaxis
  > git tag nombreVersión Ejemplo: git tag v0.1-Beta1, git tag v0.1.1, git tag 0.1

  - Para crear y subir el tag se usa:  
  > git tag vX.X-caracteristica \
    git push --tags
  
  - Para eliminar un tag se usa
  > git tag --delete Nombre_de_la_etiqueta
  
  - Para crear los releases se accede a la pestaña release de GitHub y se selecciona el tag desde el cual se va a crear el release.
  Los cambios se van documentando en el checklist en la sección de descripción y debe concordar con los commits que se hagan en git y github.
  - Cambios del FW. Cuando el programa ya ha sido probado y se decida que esta listo para producció se usará la sección de release de github para documentar los cambios realizados.
  - Pruebas realizadas (Checklist ❓)
  - Fecha de realización ✅
  - Tarjetas asociadas ✅

## Ejemplo de Formato

### ReadMe

#### Detalles del programa

- Tarjetas asociadas.
- Descripción de uso y funcionamiento.

#### Versión 1.1 [10/03/2025] (Stable o pre)

##### Correcciones y Cambios

1. Se corrigió el bloqueo de pantalla para que funcione a bloquearse a 30 segundos.
2. Alerta de "Aviso de Carga de Equipo" solucionado a mostrarse en cuanto se desconecte de la tomacorriente y este apagado el equipo.
3. Revisión de la alarma de pantalla completa de "Falla de Sistema".

##### Nuevas Caracteristicas

1. Nuevo diseño de botón
2. Nueva tarjeta de control
3. Cambio de componente
