# La Forma del Artefacto

## 1\. Bajar a tierra sin perder intención

Las series anteriores han construido un marco conceptual: intención, regeneración, coherencia, convergencia. **Terreno** comienza cuando esas ideas deben vivir en un proyecto real: carpetas, ficheros, decisiones prácticas y fricción cotidiana.

El objetivo no es definir una estructura “correcta”, sino un modelo que permita:

* crear rápido,  
* crecer sin rigidez,  
* regenerar con fiabilidad,  
* y mantener coherencia sin imponer arquitectura prematura.

Para ello necesitamos una unidad operativa clara. A esa unidad la llamamos **artefacto**.

---

## 2\. Qué es un artefacto (y qué no)

Un **artefacto** es una **agrupación explícitamente declarada de intención y comportamiento**, reconocida como unidad por el sistema (humano \+ IA).

Un artefacto:

* tiene identidad,  
* tiene intención declarada,  
* y participa en los flujos de generación, verificación y regeneración.

Un artefacto **no se descubre**. Un artefacto **se declara**.

Todo aquello que no está explícitamente declarado como artefacto:

* no forma parte del sistema de intención,  
* no es objeto de regeneración,  
* y puede evolucionar libremente como implementación.

Esta distinción no es un detalle técnico: es el mecanismo que reduce ambigüedad y no determinismo.

---

## 3\. Elevar algo a artefacto es una decisión consciente

No todo código debe ser artefacto. De hecho, **la mayoría no debería serlo**.

Declarar algo como artefacto implica aceptar un coste:

* intención explícita,  
* posibles especificaciones,  
* verificación futura,  
* trazabilidad.

Por eso, el modelo adopta una regla clara:

**Solo aquello que decidimos elevar entra en el sistema de intención.**

Esto libera al resto del proyecto:

* de reglas innecesarias,  
* de inspección por la IA,  
* de obligaciones de coherencia semántica.

Aunque el sistema se basa en declaraciones explícitas de artefactos, herramientas externas pueden asistir en su descubrimiento y declaración, pero su existencia efectiva comienza únicamente cuando la declaración es materializada.

---

## 4\. Artefactos simples: el caso del fichero único

Un artefacto **puede** estar compuesto por un único fichero, pero **solo si se declara explícitamente como tal**.

No porque sea pequeño, sino porque:

* su intención es clara,  
* su complejidad es baja,  
* y queremos tratarlo como unidad semántica.

Ese fichero:

* no se “descubre”,  
* no se infiere,  
* se reconoce como artefacto porque existe una declaración explícita asociada.

Esta declaración:

* no tiene por qué vivir dentro del fichero,  
* puede ser mínima,  
* y puede evolucionar más adelante.

Un fichero no declarado **no es un artefacto**, aunque sea importante o reutilizable.

---

## 5\. Crecimiento natural: de fichero a directorio

Cuando un artefacto crece:

* aparecen subcomponentes,  
* especificaciones más ricas,  
* pruebas,  
* o múltiples responsabilidades,

el artefacto **evoluciona naturalmente a un directorio**.

Este cambio:

* no altera su identidad,  
* no rompe referencias,  
* no requiere migraciones conceptuales.

Es simplemente una mejora de legibilidad y estructura.

El modelo no fuerza este crecimiento: **lo permite cuando es necesario**.

---

## 6\. Artefactos compuestos y jerarquía emergente

Los artefactos pueden contener otros artefactos.

Esta composición refleja:

* la estructura de la UI,  
* la navegación,  
* o el modelo mental del sistema.

Especialmente en la parte de aplicación, es natural que:

* los artefactos se organicen jerárquicamente,  
* unos contengan a otros,  
* y la estructura del proyecto se parezca a la estructura del producto.

No hay una taxonomía impuesta:

**la jerarquía emerge del uso, no del framework.**

---

## 7\. Artefactos Elementales: el límite inferior del sistema

Dentro del conjunto de artefactos existe un tipo especial: los **elementales**.

Los artefactos elementales son:

* elementos fundamentales,  
* definidos deliberadamente por el equipo,  
* que no dependen de otros artefactos del sistema.

Pueden tener intención y especificaciones, pero **no se consideran regenerables** en sí mismas.

Son:

* el vocabulario base,  
* los puntos de anclaje del proyecto,  
* la materia prima sobre la que se construyen artefactos más complejos.

La granularidad de estos artefactos:

* no es universal,  
* pero debe ser coherente dentro de un mismo proyecto,  
* y compartida entre sus distintas ramas o ciclos.

---

## 8\. Un modelo deliberadamente no exhaustivo

Este modelo no intenta:

* capturar todo,  
* ni estructurar todo,  
* ni someter todo a intención explícita.

Al contrario:

**Reduce el sistema a aquello que decidimos gobernar.**

Eso hace posible:

* coherencia sin rigidez,  
* regeneración sin caos,  
* y evolución sin parálisis.

En los siguientes documentos de **Terreno** abordaremos:

* cómo estos artefactos viven dentro de la aplicación,  
* cómo se navegan,  
* cómo se reutilizan,  
* y cómo se convierten en un sistema vivo en tiempo de desarrollo.

Aquí fijamos lo esencial:

**la forma mínima que permite que la intención exista, sin imponer coste donde no aporta valor.**  
