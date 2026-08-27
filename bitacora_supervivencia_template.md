# Bitácora de supervivencia — CitasSalud+

**Estudiante:** Sebastián Villalobos Taborda
**Sección:** 11-6
**Fecha:** 27/08/2026

## Escenario

Durante la ejecución de la prueba de performance (JMeter, listado de citas con
500 registros simulados — ver Anexo 1), el servidor principal de CitasSalud+
se satura y queda fuera de línea.

## 1. Identificación

<!-- ¿Cómo se detectó que el servidor había caído? ¿Qué señal o dato lo evidenció? -->
La falta de servicio total, el servidor se encontraba saturado y no recibía ni enviaba información, por lo que la no funcionalidad del servicio era una prueba.


## 2. Contención

<!-- ¿Qué acción se tomó de inmediato para limitar el impacto? -->}
En caso de tener un servidor de respaldo activarlo hubiera sido bueno, sino poner el sitio inmediatamente en mantenimiento, hacer un anuncio con esta información para los usuarios y mandar el programa a revisión.


## 3. Recuperación

<!-- ¿Qué acción concreta permitió que la aplicación siguiera operando para
     citas de emergencia? Esta acción debe reflejarse en un commit de este
     repositorio con un mensaje descriptivo. -->
Poner en funcionamiento los servidores de respaldo.


**Commit de recuperación:** (pegue aquí el hash o el mensaje del commit)

## 4. Aprendizaje / mejora

<!-- ¿Qué estrategia complementaria (respaldo, redundancia o monitoreo)
     hubiera anticipado este resultado, en relación con el criterio de
     performance del Anexo 1 (listado de citas en menos de 3 segundos)? -->

