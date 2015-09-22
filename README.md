# turnoclick
Objetivo

La idea de la aplicación es de que una persona pueda reservar en forma rápida y eficiente un turno médico usando la API de google calnedar.

Descripción del problema

Generalmente el proceso que una persona realiza para reservar un turno médico es el siguiente:

1. Entrar en la página de la prepaga.

2. Completar los parámetros de la búsqueda

3. La página devuelve un listado de los médicos que cumplen las condiciones ingresadas.

4. Si no se tiene referencia sobre ninguno de los profesionales, se hace una pre selección en función de la cercanía

5. Se llama al consultorio pre seleccionado para acordar una fecha y hora

6. Si no logra acordar una fecha en el punto 5 debe volver a buscar un nuevo profesional y averiguar su disponibilidad hasta que de ambos lados lleguen a un acuerdo.

El proceso de búsqueda de un turno médico es ineficiente tanto desde la perspectiva del paciente como de la del médico.

Por el lado el paciente, no puede observar toda la disponibilidad de turnos y cada vez que quiere acordar una cita, necesita llamar telefónicamente a n consultorios hasta encontrar el médico que tenga disponibilidad en la fecha y hora deseada.

Desde el lado del médico, se necesita destinar un recurso especialmente para gestionar los turnos.

Beneficios del uso de la aplicación

Para el paciente:

- Se puede encontrar todos los médicos disponibles para la fecha deseada de manera más rápida

- Los tiempos de espera hasta concurrir a la cita médica son más cortos

- Se necesita menos tiempo para coordinar un turno ya que no se necesita estar llamando a varios consultorios

Para el médico:

- No necesita destinar un recurso humano especialmente dedicado a la gestión de los turnos

- Puede incrementar la cantidad de pacientes a atender

Estructura de la aplicación

Features para las siguientes iteraciones

Incluir los siguientes filtros en la búsqueda:

* Obra social o prepaga

* Plan

* Provincia

* Localidad

* Profesional

* Los resultados aparezcan por orden de cercanía a la ubicación de la persona que realiza la búsqueda.
