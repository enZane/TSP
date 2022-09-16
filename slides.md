---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: "text-center"
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

# TSP

Team Software Process

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">

  </span>
</div>

<div class="abs-br m-6">
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: center
---
<Toc />

---

# ¿Qué es el TSP?

<div class="mt-12 p-12 flex items-center">
  <span class="text-center text-1.4em ">
    Es una metodología de desarrollo de software desarrollada por Watts Humphrey
  </span>
  <img src="https://www.sei.cmu.edu/sei-images/images/humphrey-watts-96_2622.jpg" class="w-24 rounded-full" />
</div>

<div class="p-12 flex items-center">
  Diseñada para proveer a los ingenieros un proceso para trabajar con calidad de manera consistente
</div>

<style>
h1 {
  color: #2B90B6;
}
</style>

<!--
In 1996, Watts Humphrey developed the initial version of the TSP process.

Proveer proceso operacional para ayudar a los ingenieros

He designed the initial TSP0 process to be as simple as possible, tried it with two teams, and then reviewed the results to see how it worked. He then identified where the teams needed further
guidance and enhanced the process to provide that guidance.
 -->

---
layout: center
---
# Los equipos son necesarios para casi todos proyectos de ingenieria.

<style>
  h1 {
    color: #2B90B6;
  }
</style>

---
preload: false
layout: image-right
image: https://www.sportscasting.com/wp-content/uploads/2019/11/Zach-LaVine-of-the-Chicago-Bulls.jpg?w=1024
---
# Trabajo en equipo

<div
  v-motion
  :initial="{x: -80}"
  :enter="{x: 0}"
  class="mt-12"
>
Un equipo es mas que un grupo de personas que trabajan juntos. el trabajo en equipo involucra un grupo de habilidades
</div>

<br>
<br>

<v-click>

Un equipo requiere de procesos, necesitan metas en comun, y un liderazgo efectivo.

</v-click>

<!-- 
En ingenieria los equipos son similares a equipos de baseball o basketball

Todos trabajan para un objetivo.

Pero, al momento de la ejecución, mucho es realizado de manera independiente,
-->

---

# Procesos

### ¿Por qué es necesario un proceso?

- El desarrollo de sistemas depende de la calidad de la ingenieria

<v-click>

- Debido a que el equipo se enfoca mucho mas en el producto y deja de lado preguntas operacionales
</v-click>

<v-click>

- Los miembros pueden ser un obstaculo si no hay un proceso
</v-click>

<v-click>

- Los equipos gastan mucho tiempo en lograr un manejo del mismo y surgen preguntas
  - ¿Cómo repartir el trabajo?
  - ¿Cómo coordinar tareas?
  - ¿Cómo asignar responsabilidades?
</v-click>

<style>
  h1 {
    color: #2B90B6;
  }

  h3 {
    margin-top: 2rem;
  }

  li {
    margin-top: .8rem;
  }
</style>

---

# Las condiciones para el trabajo de equipo

<div class="grid grid-cols-2 mt-12">

- Un equipo consiste de al menos 2 personas
- Los miembros deben trabajar hacia una meta en común
- Cada persona tiene un rol asignado
- Completar la misión requiere alguna manera de cada miembro del equipo

<v-click>

<div class="border-l border-l-4px border-l-#2B90B6 pl-4 grid grid-col">

### ¿Por qué asignar roles?

Para generar un sentido de pertenencia, así como otorgar al equipo una guia de como realizar su trabajo, evitando conflictos y duplicación de trabajo
</div>
</v-click>

</div>

<style>
  li {
    margin-top: .6rem;
  }
</style>

---

# Equipos eficientes.
___
Para ser efectivos, los equipos deben ser habilidosos y ser capaces de trabajar de manera cohesiva.

<v-click>
<div class="grid grid-cols-3 gap-4 p-8">

<p class="border-l-2px pl-1 border-l-blue-400" >La meta es importante, definida, visible y realistica</p>

<p class="border-l-2px pl-1 border-l-blue-400" >Los recursos del equipo son adecuados para el trabajo</p>

<p class="border-l-2px pl-1 border-l-blue-400" >Los miembros están motivados y comprometidos en llegar a la meta</p>

<p class="border-l-2px pl-1 border-l-blue-400" >Los miembros cooperan y se apoyan</p>

<p class="border-l-2px pl-1 border-l-blue-400" >Los miembros son diciplinados en su trabajo</p>
</div>
</v-click>

### Las personas trabajan más duro cuando se enfrentan a un reto importante y con sentido

<style>
  h3 {
    color: #2B90B6;
  }
</style>

<!-- 
Otras habilidades importantes es la capacidad de innovar, que es mas que traer ideas, requiere creatividad y mucho trabajo duro. para serlo es necesario que el ambiente los apoye y confie ene ellos
 -->

---

# Construir un equipo efectivo

- Los miembros del equipo establecen metas en común y sus respectivos roles
- El equipo desarrolla una estrategia previamente aceptada por todos
- Los miembros definen un proceso en común para su trabajo
- Todos los miembros participan en producir el plan, y cada miembro conoce su rol en él
- El equipo negocia el plan con la administración
- La administración revisa y acepta el plan negociado
- Los miembros realizan el trabajo de acuerdo al plan, comunicándose seguido y libremente
- El equipo forma un grupo cohesivo: los miembros cooperan, y todos están comprometidos a alcanzar la meta
- Los ingenieros conocen su status, son retroalimentados, tienen liderazgo que los mantiene motivados

---

# ¿Dónde entra el TSP?


Para ser diciplinados, los ingenieros necesitan lo que Deming llama "Operational Process" que son procesos definidos precisamente sobre como debe ejecutarse el trabajo


<h3 class="mt-12 text-emerald-800 underline">
TSP provee un Operational Process definido
</h3>

<div class="mt-12">

Con un proceso correctamente definido los ingenieros pueden ser altamente eficientes.
Mientras que el PSP le da al ingeniero la disciplina necesaria para ejecutar procesos, el TSP lo junta con los principios del CMM para generar equipos efectivos
</div>
<!-- 
Mientras que los procesos de software son largos y extendidos en descripciones de text, un proceso operacional es mas como un script
 -->

---
layout: center
---

<img src="https://i0.wp.com/fernandoarciniega.com/wp-content/uploads/TSP-team-software-process.jpg?resize=590%2C347&ssl=1" />

---

# Estructura del TSP

<div class="flex justify-center mt-12">

<img class="w-50%" src="https://d3i71xaburhd42.cloudfront.net/1541f4cb4677469c1a8378ac365eb281d46ba74f/23-Figure2-1.png" />
</div>

<span class="w-50% px-4">

Antes de que los miembros puedan participar en TSP deben saber como trabajar disciplinadamente.

</span>

---

<div class="grid grid-cols-3 grid-rows-2">
<img class="col-start-1 col-end-3 row-start-1 row-end-3 w-100%" src="https://slideplayer.com/slide/16942263/97/images/2/Process+Flow+5%2F26%2F2019+%C3%A3+2007%2C+Spencer+Rugaber.jpg" />
<span class="col-start-3">
Los equipos usando TSP tienen un reinicio periodico, porque TSP sigue un proceso iterativo que evoluciona la estrategiad de desarrollo
</span>
<span class="col-start-3 col-end-4 justify-self-center row-start-2">
Los equipos usando TSP tienen un reinicio periodico porque los planes detallados dificilmente pueden ser utiles para mas de unos cuantos meses.
</span>
</div>

---

# Lanzamiento de un equipo TSP

<div class="flex">

<img class="w-50%" src="https://d3i71xaburhd42.cloudfront.net/1541f4cb4677469c1a8378ac365eb281d46ba74f/25-Figure4-1.png" />
<p class="pl-12">
  Siguiendo el proceso de lanzamiento, los equipos producen un plan detallado donde todos los miembros tienen que estar comprometidos, para ello todos deben participar en producir dicho plan y estar de acuerdo
</p>
</div>

---
hideInToc: true
---

# Dia 1

<div class="my-12">

### Project and Managment objetives
</div>

- Revisar el proceso de lanzamiento e introducir miembros del equipo
- Discutir los objetivos del proyecto y hacer preguntas

---
hideInToc: true
---

# Dia 2

<div class="my-12">

### Team Goals and Roles
</div>

- Escoger roles de equipo y respaldo
- Definir y documentar los objetivos de equipo

---
hideInToc: true
---

# Dia 3

<div class="my-12">

### Project Strategy and Support
</div>

- Producir un Design System y lista de arreglos si es necesario
- Determinar la estrategia de desarrollo y productos
- Definir el proceso de desarrollo a utilizar
- Producir el proceso y planes de ayuda

---
hideInToc: true
---

# Dia 4

<div class="my-12">

### Overral plan
</div>

- Desarrollar estimaciones de tiempo y el plan general

---
hideInToc: true
---

# Dia 5

<div class="my-12">

### Quality plan
</div>

- Desarrollar el plan de calidad

---
hideInToc: true
---

# Dia 6

<div class="my-12">

### Balanced Plan
</div>

- Designación del trabajo para cada miembro
- Preparar la siguiente fase del trabajo para cada miembro

---
hideInToc: true
---

# Dia 7

<div class="my-12">

### Project Risk Analysis
</div>

- Identificar y evaluar riesgos
- Definir puntos de riesgo y responsabilidades
- Proponer acciones de mitigación para riesgos de alto impacto

---
hideInToc: true
---

# Dia 8

<div class="my-12">

### Launch Report Preparation
</div>

- Preparar un reporte de Lanzamiento

---
hideInToc: true
---

# Dia 9

<div class="my-12">

### Management Review
</div>

- Revisar las actividades de arranque and los planes del proyecto
- Discutir los riesgos, responsabilidades y planear acciones


---
layout: center
class: text-center
---

# Referencias

[Interview with Watts Humphrey](https://www.informit.com/articles/article.aspx?p=1626327) · [The Team Software Process (TSP)](https://resources.sei.cmu.edu/asset_files/TechnicalReport/2000_005_001_13754.pdf) · [EVALUATING TEN SOFTWARE DEVELOPMENT METHODOLOGIES](https://web.archive.org/web/20130629005257/http://namcookanalytics.com/evaluating-ten-software-development-methodologies/) · [Deming](https://www.redalyc.org/journal/290/29065286036/html/#:~:text=El%20Ciclo%20de%20Deming%20consta,1989%20y%20Summer%2C%202006)
