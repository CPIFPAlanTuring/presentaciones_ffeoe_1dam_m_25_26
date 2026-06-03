> 🎬 **Vídeo de presentación:** [Ver en YouTube](https://youtu.be/WryKsKz-sS0)

---

# Memoria de Prácticas — Andrés García Domínguez

## INTRODUCCIÓN

Buenas, soy Andrés García Domínguez y yo he hecho las prácticas en properly, la cual es una empresa pequeña con unos 8 empleados pero que dentro de su nicho es relativamente conocida que se dedica a proporcionar software de gestión empresarial mediante distintos servicios que son los siguientes:

- Properly Gestión Instaladores.
- Properly Gestión Mantenimientos.
- Reporte Móvil.
- Desarrollo de software.
- Desarrollo de aplicaciones móviles.

Mi horario era de 8 a 14 de forma presencial las 3 primeras semanas y las 3 últimas semanas igual pero de forma telemática.

---

## TAREAS DESEMPEÑADAS

**La primera semana** estuve haciendo un [curso de JMIX](https://www.udemy.com/course/rapid-application-development-with-jmix/), el cual es un framework basado en Java, XML y Spring que te facilita mucho la conexión entre base de datos, backend y frontend.

**La segunda semana** estuve repasando todo lo visto en el curso y realizando diagnósticos de la empresa para hacer los trabajos del módulo de digitalización e IPE I.

**La tercera semana** nos mandó un proyecto en el que teníamos que hacer un programa en conjunto entre mi compañero y yo que mostrase de un montón de artículos que nos dió nuestro tutor laboral artículos similares y duplicados de uno que buscara el usuario y que también pudiese generar una descripción con una ia a la que teníamos que conectarnos para pasarle el prompt.
Lo primero era hacer el modelo entidad relación de la base de datos y luego crear las tablas.

**La cuarta semana** hicimos las 4 vistas de la base de datos del sistema rag que necesitamos: una de ellas es para unir todo en una sola vista y generar una descripción de los artículos, otra es para que a la hora de vectorizar los artículos, que posteriormente explicaré qué es esto, se generen de la forma más óptima posible, otra vista está dedicada a la consulta del precio de los artículos y la última para mejorar el matching semántico cuando tu buscas un artículo. Por último usamos pg vector para vectorizar todos los artículos que nos dió nuestro tutor. Vectorizar algo es convertir el texto en un montón de números los cuáles representan el significado en vez del propio texto en sí para que a la hora de buscar similitudes o duplicados lo haga por significado.

**La quinta semana** conectamos la base de datos al proyecto en el IDE e hicimos el código java para procesar todos los artículos vectorizados en el proyecto y también hicimos una automatización con quartz que nos pidió el tutor que todos los días a las 2:00 am revisaba si había algún artículo nuevo y si era así lo vectorizar automáticamente.

**La sexta y última semana** nos conectamos a la ia local de ollama para generar la descripción de los artículos e hicimos el buscador semántico para poder buscar artículos mediante la consola de la terminal.

---

## CONOCIMIENTOS ADQUIRIDOS POR CADA MÓDULO PROFESIONAL

- **Programación:** conectarme a ias locales.
- **Base de datos:** uso de postgresql y pg vector.
- **Lenguaje de marcas:** uso de xml como forma de visualizar la página.
- **Entorno de desarrollo:** uso del IDE de intellij y del framework de JMIX.
- **Digitalización:** uso de IA para generar respuestas adecuadas.
- **Sistemas informáticos:** uso de ubuntu como sistema operativo.
- **IPE I:** Métodos de prevención de riesgos en el sector.
- **Sostenibilidad:** Métodos de una empresa para consumir lo menos posible.

---

## HERRAMIENTAS

`JMIX` `Intellij` `Pgadmin` `Pgvector` `Quartz` `Java` `XML` `Ollama`

---

## VALORACIÓN PERSONAL

Mi experiencia personal ha sido positiva pero si tengo que destacar algo negativo es que en la segunda semana ya habíamos terminado el curso y le pregunté a mi tutor que podía hacer varias veces y hasta la tercera semana no nos dijo nada, pero eso sería lo único por lo demás todo bien.

El **profesorado** revisará el material **de forma no presencial** (repositorio, `README.md`, vídeos enlazados por alumno y anexos en el repo), en su tiempo y según los criterios y el calendario del departamento.


