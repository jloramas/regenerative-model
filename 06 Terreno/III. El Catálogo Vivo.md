# El Catálogo Vivo

## 1\. El catálogo no es un lugar: es una vista

En modelos tradicionales, un catálogo suele entenderse como:

* una librería,  
* una colección de componentes,  
* o una documentación navegable.

En este modelo, el **catálogo vivo no es una capa separada**.

**El catálogo es una vista del ecosistema de artefactos existente.**

No introduce nuevos elementos. No duplica. No abstrae.

Simplemente **expone** lo que ya existe, cuando el sistema está en modo desarrollo.

---

## 2\. Catálogo vivo significa ejecutándose

La característica fundamental del catálogo vivo es esta:

**Los artefactos se muestran ejecutándose, no descritos.**

No son mocks. No son capturas. No son ejemplos inventados.

Son:

* artefactos reales,  
* con su código real,  
* en el estado real del sistema.

Esto cambia completamente su papel:

* de documentación → a herramienta,  
* de referencia estática → a sistema de exploración.

---

## 3\. El catálogo vive dentro de la aplicación

El catálogo:

* no es una app aparte,  
* no es un site paralelo,  
* no es una herramienta externa obligatoria.

Vive **dentro de la propia aplicación**, cuando esta se ejecuta en modo desarrollo.

Esto tiene varias consecuencias importantes:

* no hay divergencia entre “lo que se documenta” y “lo que existe”;  
* cualquier cambio en un artefacto se refleja inmediatamente;  
* el coste de mantenimiento del catálogo tiende a cero.

El catálogo **no se mantiene**. Se **deriva**.

---

## 4\. Qué se puede navegar en el catálogo

El catálogo permite navegar el sistema desde múltiples perspectivas, todas derivadas de los artefactos declarados:

* jerarquía estructural (aplicación, páginas, secciones);  
* tipo de artefacto;  
* intención declarada;  
* relaciones de referencia o composición;  
* estabilidad o madurez.

No todas estas vistas tienen que existir desde el primer día. Lo importante es que **puedan existir**, porque la información ya está ahí.

---

## 5\. Artefactos de aplicación y reutilización

Una consecuencia directa del catálogo vivo es esta:

**Un artefacto de aplicación puede ser usado como referencia igual que uno “reutilizable”.**

No hay una frontera rígida entre:

* “esto es de la app”  
* “esto es de catálogo”

Desde el catálogo:

* una página completa puede servir de inspiración,  
* una sección puede reutilizarse,  
* un patrón emergente puede detectarse.

El catálogo no impone reutilización. La **posibilita**.

---

## 6\. El catálogo como herramienta para humanos

Para una persona desarrollando, el catálogo vivo permite:

* explorar qué existe realmente;  
* comparar variantes;  
* detectar incoherencias visuales o de interacción;  
* decidir si construir algo nuevo o adaptar algo existente;  
* entender el sistema sin leer todo el código.

El catálogo **reduce la carga cognitiva** del proyecto a medida que crece.

---

## 7\. El catálogo como herramienta para la IA

Para la IA, el catálogo vivo es aún más potente.

Le permite:

* ver realizaciones completas;  
* observar patrones implícitos;  
* usar artefactos existentes como referencia visual y estructural;  
* validar regeneraciones comparando comportamientos reales.

Importante:

La IA no “descubre” artefactos en el catálogo. El catálogo solo muestra artefactos ya declarados.

Esto mantiene el modelo determinista y controlado.

---

## 8\. Catálogo y regeneración

El catálogo vivo es un aliado natural de la regeneración:

* antes de regenerar, se puede observar el estado actual;  
* después de regenerar, se puede verificar visual y funcionalmente;  
* las diferencias se hacen evidentes sin análisis abstracto.

Esto convierte la regeneración en:

* un proceso observable,  
* verificable,  
* y comprensible.

---

## 9\. Modo desarrollo, no producto

Un punto importante a fijar explícitamente:

**El catálogo vivo pertenece al modo desarrollo.**

No forma parte del producto final. No condiciona la experiencia del usuario. No introduce dependencias innecesarias en producción.

Es:

* una herramienta de trabajo,  
* una superficie de exploración,  
* un espacio compartido humano–IA.

---

## 10\. Lo que este documento fija

Este documento fija que:

* el catálogo vivo es una vista del sistema, no una capa;  
* vive dentro de la aplicación en modo desarrollo;  
* expone artefactos reales ejecutándose;  
* sirve tanto a humanos como a IA;  
* y emerge de la declaración explícita de artefactos.

No fija:

* cómo se implementa,  
* cómo se navega exactamente,  
* ni qué tooling concreto se usa.

Eso vendrá después, si es necesario.

---

## 11\. El siguiente paso

Con artefactos:

* declarados,  
* organizados,  
* y navegables como catálogo vivo,

la última pieza que falta es cerrar el círculo operativo:

**¿Qué reglas siguen humanos y IA para crear, modificar, regenerar y verificar artefactos sin romper el sistema?**

