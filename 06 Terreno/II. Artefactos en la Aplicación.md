# Artefactos en la Aplicación

## 1\. De artefactos aislados a sistema visible

Una vez que hemos definido qué es un artefacto y cómo se declara, el siguiente paso no es técnico, sino **organizativo y cognitivo**:

¿Cómo se disponen los artefactos cuando construimos una aplicación real?

Aquí el objetivo ya no es solo:

* declarar intención,  
* ni permitir regeneración,

sino algo más exigente:

**hacer que la estructura del proyecto sea legible como aplicación.**

---

## 2\. La aplicación como composición de artefactos

En este modelo, una aplicación **no es un contenedor de componentes**, sino:

**una composición jerárquica de artefactos.**

Cada artefacto:

* puede representar una página, un layout, una sección, un bloque o un elemento,  
* puede contener otros artefactos,  
* y puede ser comprendido como una unidad funcional y semántica.

Esta composición no es accidental:

* refleja la UI,  
* la navegación,  
* y el modelo mental del usuario.

---

## 3\. Jerarquía estructural como reflejo de la UI

En la parte de aplicación, la jerarquía de carpetas **no es un detalle técnico**, sino una decisión de diseño.

Es natural —y deseable— que:

* una página contenga subpáginas,  
* un layout contenga vistas,  
* una sección contenga bloques,  
* un bloque contenga elementos.

Por tanto, es legítimo que el árbol del proyecto se parezca a:

* la navegación principal,  
* los layouts visibles,  
* las subdivisiones reales del producto.

No se trata de imponer un patrón único, sino de permitir que:

**la estructura del proyecto imite la estructura de la interfaz.**

---

## 4\. Artefactos dentro de artefactos

Un artefacto puede contener otros artefactos de dos formas:

### 4.1 Composición estructural

El artefacto padre:

* define el contexto,  
* orquesta la composición,  
* y delega partes de su intención en artefactos hijos.

Ejemplo conceptual:

* una página contiene tabs,  
* cada tab es un artefacto,  
* cada tab puede contener otros.

---

### 4.2 Composición por referencia

Un artefacto puede:

* usar otro,  
* inspirarse en otro,  
* o alinearse con otro,

sin contenerlo físicamente en su estructura.

Ambas formas son válidas. La diferencia es semántica, no técnica.

---

## 5\. Artefactos de aplicación y artefactos reutilizables

Desde el punto de vista del sistema:

* un artefacto de aplicación,  
* y un artefacto “reutilizable”,

son **conceptualmente idénticos**.

La diferencia es solo de contexto:

* unos viven más cerca de la navegación,  
* otros se usan como referencia transversal,  
* algunos se reutilizan mucho,  
* otros solo una vez.

El modelo **no separa artificialmente**:

* “app” vs “catálogo”,  
* “producto” vs “librería”.

Todo son artefactos. La organización decide su rol.

---

## 6\. Simplicidad local, complejidad donde aporta valor

Un principio clave en la aplicación es este:

**La estructura debe ser tan simple como lo permita la intención local, y tan rica como lo exija la complejidad real.**

Esto implica que:

* una página sencilla puede ser un único artefacto,  
* una sección compleja puede desplegarse en múltiples niveles,  
* y no hay obligación de simetría entre ramas del árbol.

Cada parte del producto:

* crece a su ritmo,  
* según sus necesidades,  
* sin arrastrar al resto.

---

## 7\. Declaración explícita en contexto de aplicación

En la aplicación, declarar artefactos tiene un efecto adicional:

**convierte la estructura del proyecto en un mapa semántico.**

La IA no necesita:

* inferir qué es una página,  
* deducir qué es un layout,  
* adivinar qué es navegable.

Lo sabe porque:

* los artefactos están declarados,  
* su posición tiene significado,  
* y su jerarquía es intencional.

Esto reduce:

* ambigüedad,  
* exploración innecesaria,  
* y errores de regeneración.

---

## 8\. Preparando el terreno para el catálogo vivo

Cuando los artefactos de aplicación:

* están bien declarados,  
* organizados jerárquicamente,  
* y tienen intención explícita,

aparece de forma natural una posibilidad poderosa:

**navegar la aplicación como un catálogo de sí misma.**

No como documentación, no como mocks, sino como **ejemplos vivos ejecutándose**.

Este concepto no se desarrolla aquí, pero es importante notar algo:

La posibilidad del catálogo vivo **no depende de tooling**, depende de cómo organizamos los artefactos.

Y eso se decide aquí.

---

## 9\. Lo que este documento fija (y lo que no)

Este documento fija:

* que la aplicación es una jerarquía de artefactos,  
* que esa jerarquía refleja la UI,  
* que no hay separación ontológica entre tipos de artefactos.

No fija:

* nombres de carpetas,  
* frameworks,  
* formatos de declaración,  
* ni tecnologías concretas.

Eso es deliberado.

---

## 10\. El siguiente paso

Una vez que los artefactos:

* viven en la aplicación,  
* se organizan de forma legible,  
* y reflejan la experiencia del usuario,

la siguiente pregunta es inevitable:

¿Cómo se reutilizan, se comparan y se exploran estos artefactos sin salir de la propia aplicación?

