# Reglas Operativas y Flujos

## 1\. Del modelo a la práctica diaria

Con **Terreno I–III** hemos definido:

* qué es un artefacto,  
* cómo vive en la aplicación,  
* y cómo el sistema puede observarse a sí mismo mediante el catálogo vivo.

Ahora toca responder a la pregunta inevitable:

¿Cómo se trabaja día a día con este modelo sin volverlo pesado, rígido o frágil?

La respuesta no está en más estructura, sino en **reglas simples, explícitas y estables**, que puedan seguir:

* personas,  
* IA,  
* y herramientas auxiliares.

---

## 2\. Principio rector: lo explícito gobierna

La regla base de todo el sistema es clara:

**La IA no infiere intención estructural. Solo actúa sobre lo que está explícitamente declarado.**

Esto implica:

* no hay “descubrimiento mágico”,  
* no hay inspección masiva,  
* no hay heurísticas implícitas en el flujo normal.

La inferencia puede existir como **asistencia**, pero nunca como base del modelo.

---

## 3\. Flujo básico de trabajo con artefactos

### 3.1 Crear algo nuevo

Cuando se crea algo nuevo, hay tres opciones legítimas:

1. **Código libre**  
     
   * No se declara como artefacto.  
   * No entra en el sistema de intención.  
   * Evoluciona sin restricciones.

   

2. **Artefacto simple**  
     
   * Se declara explícitamente.  
   * Puede ser un único fichero.  
   * Intención mínima, coste bajo.

   

3. **Artefacto estructurado**  
     
   * Se declara como directorio.  
   * Contiene intención, realización y verificación.  
   * Preparado para crecer.

Elegir una u otra **no es técnico**, es estratégico.

---

### 3.2 Elevar algo existente a artefacto

Un elemento existente puede convertirse en artefacto cuando:

* empieza a repetirse,  
* se vuelve relevante para la coherencia,  
* o se quiere usar como referencia.

El acto clave es:

**materializar su declaración**.

A partir de ahí:

* entra en el catálogo vivo,  
* se vuelve visible para la IA,  
* y pasa a estar sujeto a reglas de regeneración y verificación.

---

## 4\. Flujo de modificación y evolución

### 4.1 Modificar un artefacto

Al modificar un artefacto, la prioridad es esta:

**Mantener coherencia entre intención declarada y realización.**

No todo cambio requiere:

* ampliar intención,  
* ni añadir verificación.

Pero cuando:

* el comportamiento cambia,  
* la estructura se altera,  
* o la responsabilidad crece,

la intención debe actualizarse.

Esto evita que la regeneración futura rompa silenciosamente.

---

### 4.2 Crecimiento estructural

Cuando un artefacto simple deja de ser legible:

* se despliega en directorio,  
* se organizan sus partes,  
* se mantiene su identidad.

Este paso:

* no requiere aprobación global,  
* no rompe dependencias,  
* y no cambia su rol en la aplicación.

Es una optimización local, no un rediseño.

---

## 5\. Flujos de generación y regeneración

### 5.1 Generación (orientada a feedback)

La generación se usa cuando:

* se explora,  
* se prueba una idea,  
* se busca velocidad.

Características:

* intención parcial,  
* verificación mínima,  
* foco en funcionalidad observable.

El catálogo vivo permite:

* validar visualmente,  
* comparar con artefactos existentes,  
* decidir rápidamente si seguir o descartar.

---

### 5.2 Regeneración (orientada a coherencia)

La regeneración se activa cuando:

* se quiere alinear,  
* se cambia de contexto,  
* o se prepara un salto de ciclo.

Aquí:

* la intención declarada guía el proceso,  
* la verificación actúa como contrato,  
* el no determinismo se reduce deliberadamente.

La regeneración es un **experimento controlado**: si falla, revela intención incompleta o verificación insuficiente.

---

## 6\. Verificación como etapa explícita

La verificación no es un subproducto:

**es una etapa visible y deliberada del flujo.**

Puede existir:

* en runtime,  
* en design-time,  
* de forma determinista o semántica (IA).

Antes de:

* reutilizar un artefacto,  
* elevarlo entre etapas,  
* o usarlo como referencia fuerte,

debe existir un nivel mínimo de verificación aceptado.

Esto hace que el sistema escale sin perder fiabilidad.

---

## 7\. Uso del catálogo en los flujos

El catálogo vivo actúa como:

* **superficie de exploración** (antes de generar),  
* **espacio de comparación** (durante),  
* **herramienta de validación** (después).

No sustituye:

* specs,  
* ni tests,  
* ni revisión consciente.

Los complementa, haciéndolos observables.

---

## 8\. Qué NO hacen estas reglas

Estas reglas no:

* imponen frameworks,  
* fuerzan formatos,  
* ni dictan tecnologías.

Tampoco:

* hacen que todo sea artefacto,  
* obligan a regenerar todo,  
* ni eliminan la libertad local.

Su función es otra:

**hacer que lo importante sea visible, y que lo visible sea gobernable.**

---

## 9\. El siguiente paso

Con **Terreno I–IV** queda fijado:

* cómo se declara un artefacto,  
* cómo vive dentro de la aplicación,  
* cómo se explora como catálogo vivo,  
* y cómo se trabaja con él sin fricción.

El próximo documento cierra la serie Terreno, fijando la naturaleza de la unidad fundamental sobre la que se construirá todo lo demás.

