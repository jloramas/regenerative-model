# Artefactos Vivos

## De qué está hecho realmente un proyecto regenerativo

Hasta ahora hemos hablado de visión, de creación, de horizonte. Hemos definido **qué tipo de software queremos construir** y **cómo queremos construirlo con ayuda de IA**.

En esta nueva serie —*Camino*— el objetivo es distinto: empezar a **caminar de verdad**, es decir, decidir **con qué unidades trabajamos**, cómo se organizan y cómo se sostienen en el tiempo sin perder coherencia ni capacidad de regeneración.

El primer paso es responder a una pregunta aparentemente sencilla:

¿Cuál es la unidad real de trabajo en un sistema regenerativo?

No un archivo. No un componente React. No una página. Tampoco una abstracción genérica.

La respuesta es: **el artefacto**.

---

## El artefacto como unidad viva

En el modelo tradicional, un proyecto está compuesto por archivos de código y carpetas que los agrupan. La coherencia emerge —cuando emerge— de convenciones, revisiones humanas y disciplina.

En un modelo regenerativo, eso no es suficiente.

Aquí, la unidad mínima con sentido no es un archivo, sino algo más rico:

Un **artefacto** es una unidad viva que agrupa intención, realización y verificación, y que puede ser comprendida, evaluada y regenerada como un todo.

Un artefacto no es solo “algo reutilizable”. Tampoco es necesariamente “algo genérico”.

Puede ser:

* una página completa,  
* un layout,  
* un flujo de usuario,  
* un patrón de UI,  
* o incluso un elemento más pequeño.

Lo que define al artefacto no es su tamaño, sino su **coherencia interna**.

---

## Intención y realización: una relación explícita

En un artefacto, el código deja de ser la única fuente de verdad.

El artefacto contiene —de forma explícita—:

* **qué pretende ser** (intención declarada),  
* **cómo se manifiesta** (realización: código, UI, lógica),  
* **cómo se valida** (criterios de verificación).

Esto no significa que todo esté formalizado al máximo desde el principio. Significa que **lo que importa debe poder declararse**.

Y, sobre todo, significa que el artefacto puede ser:

* analizado por una IA,  
* comparado con otros artefactos,  
* usado como referencia,  
* o regenerado a partir de su intención.

---

## No todo es regenerable: el papel de los artefactos elementales

Aquí aparece un matiz importante.

Aunque el modelo regenerativo tiende a favorecer artefactos capaces de regenerarse, **no todo en un proyecto tiene por qué ser regenerable**.

Existen elementos más fundamentales, que actúan como base común y estable del sistema.

A estos elementos podemos llamarlos **artefactos elementales**.

### Qué son los artefactos elementales

Los artefactos elementales son unidades básicas que:

* no dependen de otros artefactos,  
* expresan decisiones constitutivas del proyecto,  
* encapsulan intención básica compartida,  
* **no se regeneran**, sino que se asumen como dadas.

Ejemplos conceptuales (no prescriptivos):

* una primitiva visual base,  
* una convención de navegación,  
* una regla estructural esencial,  
* una decisión algorítmica no negociable,  
* un contrato semántico mínimo del proyecto.

Los artefactos elementales **también tienen especificaciones**, pero su función no es ser reinterpretados, sino **servir de suelo común**.

---

## Granularidad y coherencia entre ciclos

La granularidad de estos artefactos elementales no es universal. Es una **decisión del equipo y del proyecto**.

Lo importante no es cuántos artefactos elementales haya, sino que:

* su definición sea explícita,  
* su alcance esté claro,  
* y su uso sea consistente entre ramas o ciclos del proyecto.

Esto es clave para algo que veremos más adelante:

La coherencia entre ramas no se garantiza copiando código, sino compartiendo un mismo conjunto de artefactos elementales y de intención declarada.

Sobre estos artefactos elementales se construyen artefactos más complejos, que sí pueden ser regenerables, reinterpretables y adaptables.

---

## Artefactos como sistema, no como jerarquía rígida

Un proyecto real no es un árbol limpio de componentes.

Es más bien:

* un grafo de referencias,  
* de inspiraciones,  
* de dependencias semánticas.

Un artefacto puede:

* usar otro como referencia,  
* inspirarse en una realización existente,  
* componer varios artefactos previos,  
* o incluso tomar como referencia una página completa ya existente.

Desde este punto de vista:

* construir una página nueva,  
* agrupar elementos reutilizables,  
* o refinar un patrón existente,

son variaciones del mismo acto conceptual: **crear un nuevo artefacto a partir de otros**.

---

## Catálogo vivo y aplicación: una falsa dicotomía

En este modelo, no hay una diferencia esencial entre:

* artefactos “de catálogo”  
* y artefactos “de aplicación”.

La diferencia es organizativa, no ontológica.

Un artefacto puede:

* vivir en un catálogo navegable,  
* o formar parte de la aplicación en producción,  
* o ambas cosas a la vez.

Lo importante es que siga siendo:

* identificable,  
* verificable,  
* y comprensible como unidad viva.

---

## Por qué empezar aquí

Este documento no define aún:

* estructuras de carpetas,  
* formatos concretos,  
* ni workflows de generación.

Eso vendrá después.

Lo que fija es algo más fundamental:

Antes de decidir cómo generar o regenerar, debemos decidir **qué consideramos una unidad con sentido**.

Sin esta decisión, cualquier intento de coherencia se vuelve frágil, y cualquier regeneración se convierte en un acto ciego.

---

## Lo que viene a continuación

En el siguiente documento abordaremos una pregunta inevitable:

Si los artefactos son unidades vivas, ¿cómo se declaran, verifican y sostienen en el tiempo?

Ahí entraremos de lleno en:

* intención declarada,  
* verificación semántica,  
* y fiabilidad regenerativa.

Este es solo el primer paso del camino.  
