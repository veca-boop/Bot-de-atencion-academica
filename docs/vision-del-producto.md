# Visión del producto

> **Plantilla del curso · Ingeniería de Software I · SIS3407
> Huecos importantes: definir donde estaría ubicado el bot (chat de la directora), definir si se actualiza completa la información o solo la necesaria**

---

**Autor: Ana Victoria Hernández Álvarez**

**Fecha de la última versión: 18 de agosto de 2026**

**Repositorio: 
https://github.com/veca-boop/Project.Ingenier-a-de-Software-I**

---

## 1. Descripción del sistema

**Nombre del sistema: Bot de Atención Académica**

**Descripción: Es un bot dentro del chat de Microsoft Teams del director de carrera que responde automáticamente las preguntas frecuentes de los alumnos sobre la carrera; por ejemplo, trámites, materias, fechas y procesos académicos, utilizando información previamente proporcionada y aprobada por la dirección. En caso de cambios en la información se actualizará específicamente esa información dentro de la base de datos del bot inmediatamente o en su defecto cada semestre.**

---

## 2. Problema y usuarios

**El problema: Los alumnos realizan constantemente preguntas similares a la dirección de carrera, lo que genera tiempo de espera y trabajo repetitivo. Para lo cual la direccción no tiene tiempo suficiente y por lo tanto no puede dar un servicio personalizado.**

**Cómo se resuelve hoy sin el sistema: Los alumnos tienen que enviar mensajes, correos o preguntar directamente su director/a para obtener respuestas, esperando a que esté disponible y el director/a debe contestar manualmente cada consulta**

**Usuarios del sistema:**

| Tipo de usuario | Qué necesita del sistema | Qué le preocupa |
|---|---|---|
| Alumno | Quieren obtener respuestas rápidas a sus dudas | Que la directora de carrera no esté disponible en ese momento |
| Dirección de carrera | Quiere reducir las preguntas repetitivas | Asegurar que los alumnos reciban información correcta y actualizada|

**Un conflicto entre usuarios: El alumno quiere que el bot responda la mayor cantidad de preguntas posibles y de manera inmediata, mientras que la dirección necesita limitar las respuestas del bot a información confiable y aprobada.**

---

## 3. Alcance

### Dentro del alcance
-Desplegar un menú de servicios con las sigientes opciones: 1.Materias, 2.trámites y bajas, 3.calendario y restricciones.
-Mostrar lista de materias disponibles de la carrera en el semestre con sus respectivos horarios y maestros.
-Desplegar lista de los siguientes trámites escolares disponibles: 1.BAJA de materias, 2.BAJA de carrera, 3.TRÁMITE de beca escolar, 4.TRÁMITE para solicitar ser becado de tu director de carrera, 5.JUSTIFICANTE médico o de faltas, 6.INTERCAMBIO para materias de tu carrera.
-Mostrar información general del trámite (qué es, para qué es, que información debes de tener a la mano y a quién debes contactar para verlo) con un mensaje adjunto que diga: "Si requieres información más específica contacta a tu director de carrera".
-Mostrar calendario escolar adjunto a la base de datos.
-Mostrar lista de restricciones escolares con explicación del motivo por el cual puede llegar a ocurrir: inglés, tercer idioma o por mala conducta.

### Explícitamente fuera del alcance

-El bot no te puede hacer el trámite.
-El bot no puede resolver dudas fuera de su menú de servicios.
-El bot no puede dar información detallada de los pasos para ningún trámite.

**Por qué queda fuera:**
El bot es una ayuda para que el director de carrera no gaste tiempo contestando preguntas frecuentes, no una IA de ayuda estudiantil.
---

## 4. Tipo de sistema y restricciones

**Tipo de sistema:**

*(De información · Embebido · Crítico · Web y SaaS · De datos y análisis)*

**Por qué es de ese tipo:**

**Atributos de calidad que impone:**

| Atributo | Por qué importa en mi caso | Qué pasa si no se cumple |
|---|---|---|
| | | |
| | | |
| | | |

**Reglas de negocio que ya identifiqué:**

1.
2.
3.

---

## 5. Ciclo de vida elegido

**Modelo elegido:**

**Por qué le conviene a este proyecto:**

### Alternativas descartadas

**Alternativa 1:**

*Por qué la descarté:*

**Alternativa 2:**

*Por qué la descarté:*

---

## Antes de entregar

Reviso que el documento cumpla lo siguiente:

- [ ] La descripción del apartado 1 se entiende sin ser del área
- [ ] Hay al menos dos tipos de usuario con necesidades distintas
- [ ] Identifiqué un conflicto real entre usuarios
- [ ] El alcance dice qué queda fuera, no solo qué queda dentro
- [ ] Las exclusiones son específicas, no genéricas
- [ ] Identifiqué el tipo de sistema y al menos dos atributos de calidad
- [ ] Anoté al menos tres reglas de negocio no obvias
- [ ] Justifiqué el ciclo de vida contra dos alternativas descartadas
- [ ] El documento está en mi repositorio y se puede leer desde el navegador
- [ ] Borré todas las instrucciones en cursiva de la plantilla
