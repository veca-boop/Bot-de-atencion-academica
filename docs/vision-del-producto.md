# Visión del producto


---

**Autor: Ana Victoria Hernández Álvarez**

**Fecha de la última versión: 1 de septiembre de 2026**

**Repositorio: 
https://github.com/veca-boop/Project.Ingenier-a-de-Software-I**

---

## 1. Descripción del sistema

**Nombre del sistema: Bot de Atención Académica**

**Descripción: **
**Es un bot dentro del chat de Microsoft Teams del director de carrera de Ing.TI que responde automáticamente las preguntas frecuentes de los alumnos sobre la carrera; por ejemplo, trámites, materias, fechas y procesos académicos, utilizando información previamente proporcionada y aprobada por la dirección. Cuando Dirección realice cambios en la información, se actualizará únicamente la información afectada antes de que vuelva a ser utilizada por los alumnos. Como mínimo, la información será revisada al inicio de cada semestre.**

---

## 2. Problema y usuarios

**El problema: Los alumnos realizan constantemente preguntas similares al director de carrera, lo que genera tiempo de espera y trabajo repetitivo. Para lo cual no tiene tiempo suficiente y por lo tanto no puede dar un servicio personalizado en caso de ser necesario.**

**Cómo se resuelve hoy sin el sistema: Los alumnos tienen que enviar mensajes, correos o preguntar directamente su director/a para obtener respuestas, esperando a que esté disponible y el director/a debe contestar manualmente cada consulta**

**Usuarios del sistema:**

| Tipo de usuario | Qué necesita del sistema | Qué le preocupa |
|---|---|---|
| Alumno | Quieren obtener respuestas rápidas a sus dudas | Que la directora de carrera no esté disponible en ese momento |
| Dirección de carrera | Quiere tener acceso a modificar la información que el bot usa | Asegurar que los alumnos reciban información correcta y actualizada|

**Un conflicto entre usuarios: El alumno quiere que el bot responda la mayor cantidad de preguntas posibles y de manera inmediata, mientras que la dirección necesita limitar las respuestas del bot a información confiable y aprobada.**

---

## 3. Alcance

### Dentro del alcance
-Desplegar un menú de servicios con las sigientes opciones: 1.Materias, 2.trámites y bajas, 3.calendario y restricciones.

-Mostrar lista de materias disponibles de la carrera en el semestre con sus respectivos horarios y maestros.

-Desplegar lista de los siguientes trámites escolares disponibles: 1.BAJA de materias, 2.BAJA de carrera, 3.TRÁMITE de beca escolar, 4.TRÁMITE para solicitar ser becado de tu director de carrera, 5.JUSTIFICANTE médico o de faltas, 6.INTERCAMBIO para materias de tu carrera.

-Mostrar información general del trámite (qué es, para qué es, qué información debes de tener a la mano y a quién debes contactar para verlo) con un mensaje adjunto que diga: "Si requieres información más específica contacta a tu director de carrera".

-Mostrar calendario escolar.

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

 Web y SaaS  

**Por qué es de ese tipo: El bot funciona como un servicio integrado en el chat de  Microsoft Teams del director de carrera. Por lo cual Los usuarios no necesitan instalar una aplicación independiente. Además, el bot no manipula la información, no tiene grandes riesgos, ni usar un dispositivo físico, sino que el usuario interactúa con el bot directamente desde la plataforma de Teams.**

**Atributos de calidad que impone:**

| Atributo | Por qué importa en mi caso | Qué pasa si no se cumple |
|---|---|---|
|Disponibilidad | El bot debe estar disponible dentro de Teams cuando los usuarios necesiten consultar la información.|Los usuarios no podrán acceder a la información mediante el bot. |
|Usabilidad |Las respuestas deben ser claras y la interacción sencilla para que cualquier usuario pueda utilizarlo. | Los usuarios pueden confundirse o dejar de utilizar el bot.|
|Confiabilidad |El bot debe mostrar correctamente la información proporcionada por Dirección. |Puede generar confusión y hacer que los usuarios reciban información equivocada. |

**Reglas de negocio que ya identifiqué:**

1. El bot debe limitar sus respuestas a las categorías de información autorizadas por Dirección.

2. El bot debe proporcionar respuestas claras y relacionadas con la información solicitada por el usuario.

3. La información proporcionada por el bot debe corresponder a la información oficial proporcionada por Dirección.

---

## 5. Ciclo de vida elegido

**Modelo elegido: Prototipado rápido (Software a la medida)**

**Por qué le conviene a este proyecto: El bot de Teams requiere interacción directa con los usuarios, por lo que es importante comprobar desde las primeras versiones si sus respuestas y funcionalidades realmente satisfacen sus necesidades. El prototipado rápido permite crear una versión inicial del bot, probarla con usuarios, recibir retroalimentación y realizar ajustes antes de desarrollar la versión definitiva.**

### Alternativas descartadas

**Alternativa 1: Modelo en Cascada**

*Por qué la descarté: Se descartó porque requiere definir los requisitos desde el inicio y seguir las etapas de manera secuencial. En este proyecto, las necesidades y funcionalidades del bot pueden cambiar después de probarlo con los usuarios, por lo que un modelo tan rígido dificultaría realizar modificaciones.*

**Alternativa 2: Modelo en espiral**

*Por qué la descarté: Se descartó porque está orientado principalmente a proyectos grandes con un nivel elevado de incertidumbre y riesgos técnicos o económicos. Para un bot de Teams de alcance más limitado, su análisis constante de riesgos y sus iteraciones resultarían innecesariamente complejos.*
