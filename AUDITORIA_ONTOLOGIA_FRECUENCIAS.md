# Auditoría ontológica — La frecuencia como agente

**Fecha**: 2026-04-15
**Alcance**: `Harmonic_Information_Theory_Foundations.md` completo (2754 líneas, 16 capítulos + 6 apéndices).
**Objetivo**: determinar si el error ontológico identificado por el ingeniero lector del libro —tratar la *frecuencia* (escalar, propiedad de un sistema) como si fuera una entidad con agencia propia que oscila, se relaciona o propaga— es un error **puntual** (rhetórico, local) o **transversal** (teórico, estructural al programa).
**Uso del informe**: guía para (i) corregir el Markdown en los lugares señalados, y (ii) sincronizar después las correspondientes correcciones en el LaTeX una vez el Markdown esté cerrado.

---

## 1. Conclusión de alto nivel

**El error NO es transversal.** Está limitado a **tres instancias** de una misma figura aforística que aparece como epígrafe y se repite como cierre en un capítulo y como epígrafe en un apéndice. El resto del libro está **activamente vigilante** contra esta forma de reificación: en particular el Cap. 4 §4.1 (*"Against the isolated essence of the ratio"*) construye su argumento principal precisamente contra este tipo de error, y el glosario (Apéndice A) define los términos clave (ratio, mode locking, natural harmony, oscillatory portrait) en forma relacional y no sustantiva.

### Resumen cuantitativo

| Categoría | Cantidad | Naturaleza |
|---|---|---|
| **Error estricto** (frecuencia como agente de oscilación) | **3 instancias** | Epígrafes y cierre aforístico; figura única repetida |
| **Borderline** (abstracción como sujeto de verbo activo, pero consistente con la ontología relacional declarada de HIT) | 4 casos | Usos intra-marco del intervalo/ratio como primitivo relacional |
| **Seguro** (articulación relacional correcta; sistemas como agentes, propiedades como relaciones) | Todo el resto del libro | Rigor ontológico sostenido |

### Implicación editorial

El libro **no** reifica la frecuencia como un error teórico estructural. Lo que hay es un **desliz retórico en una figura aforística concreta**, repetida en dos lugares donde esa misma figura vuelve a aparecer. La corrección es quirúrgica, no requiere rediseño teórico.

---

## 2. Metodología de la auditoría

Se ejecutaron cinco búsquedas sistemáticas contra el Markdown completo, buscando patrones en los que una abstracción (frecuencia, ratio, intervalo, oscilación, onda) aparece como sujeto sintáctico de un verbo que implica agencia física:

1. `(a|the|two|single) frequency/frequencies + [verb-agent]`
2. `wave/waves + [verb-agent]`
3. `an interval/the interval/intervals + [carry|oscillate|relate|propagate|etc.]`
4. `oscillation/oscillations + [verb-agent]`
5. `ratio/ratios + [oscillate|vibrate|propagate|emit|travel|carry|generate|produce]`

Cada hit se analizó en contexto (leyendo el párrafo completo) para distinguir:

- **Error ontológico estricto**: la abstracción (frecuencia, ratio, intervalo) aparece haciendo algo que sólo un sistema puede hacer (oscilar, vibrar, propagarse).
- **Uso in-framework**: la abstracción aparece como agente de verbos que son coherentes con la tesis ontológica explícita de HIT (que el intervalo es primitivo relacional). Esto **no es el error** porque el libro defiende explícitamente esta ontología relacional.
- **Metonimia estándar**: giro expositivo donde "la frecuencia del oscilador" se reemplaza por "la frecuencia" sin confusión operativa.

---

## 3. Instancias del error estricto

**Las tres instancias son variaciones de la misma figura aforística.** El error es rhetórico: la figura comprime pasos y, al comprimir, atribuye oscilación a la frecuencia en vez de al oscilador/sistema. Corresponden al error que el ingeniero marcó como muy común en la ontología de ondas.

### Instancia 1 — L261 — Epígrafe del Capítulo 3 (Ontology of Harmonic Information)

**Contexto**: frase de apertura (epígrafe italizado) del capítulo que construye la ontología relacional del programa.

**Texto original (L261)**:

> *A single frequency can oscillate. Two frequencies can enter into relation. From relation comes interference; from interference, pattern; from pattern, the possibility of differential uptake.*

**Naturaleza del error**: frase 1 (*"A single frequency can oscillate"*) y frase 2 (*"Two frequencies can enter into relation"*) atribuyen oscilación y agencia relacional a la frecuencia en sí. Estrictamente, una frecuencia es un escalar (1/s) y no oscila: oscila un sistema (o un oscilador) a determinada frecuencia; son oscilaciones/osciladores los que pueden entrar en relación.

**Prioridad**: alta. Es epígrafe del capítulo que establece la ontología relacional del programa; el error contradice programáticamente la tesis que el capítulo va a construir.

**Recomendación de corrección quirúrgica (sólo referencia, la prosa se decide después)**:

- Reemplazar "frequency/frequencies" por "oscillator/oscillators" (o "oscillating system") en las dos primeras frases.
- Preservar la forma aforística, la escalera de cinco pasos, y el cierre en "differential uptake" (Bateson / información).

### Instancia 2 — L323 — Cierre de §3.3 (The interval as a minimal informational carrier)

**Contexto**: último párrafo que cierra la sección sobre las cuatro propiedades del intervalo (robustez escalar, generación de patrón, privilegio dinámico, interpretabilidad diferencial). La cuarta propiedad (interpretabilidad diferencial) se apoya en Bateson y cierra con una versión breve de la figura del epígrafe del capítulo.

**Texto original (L323, oración final del párrafo)**:

> One frequency alone can oscillate. Two frequencies can relate. With relation comes interference; with interference comes pattern; with pattern comes the possibility of differential uptake.

**Naturaleza del error**: mismo error que la instancia 1. Versión ligeramente más corta. Ocurre DENTRO de la prosa del párrafo (no como epígrafe), lo que tiene dos consecuencias: (a) la corrección es aún más conveniente porque la contradicción con la argumentación explícita inmediatamente precedente (donde el ratio es tratado cuidadosamente como relación, no sustancia) es más visible; (b) la frase abre el párrafo siguiente, que retoma en clave positiva la tesis del intervalo como portador relacional: la coherencia mejora si la figura se corrige en línea con esa tesis.

**Prioridad**: alta. Aparece en prosa corrida y cierra la sección más ontológicamente sensible del capítulo.

**Recomendación**: misma corrección que Instancia 1, con la nota de que aquí "Two frequencies can relate" debe recomponerse por "Two oscillators can relate" (o "Two oscillating systems can enter into relation"), y que el resto de la cadena ("With relation comes interference; with interference comes pattern; with pattern comes the possibility of differential uptake") puede preservarse íntegramente.

### Instancia 3 — L2680 — Epígrafe del Apéndice F (Working Conceptual Synthesis)

**Contexto**: apéndice de síntesis conceptual operativa del libro; es la "segunda puerta de entrada" propuesta explícitamente en la Introducción (*"Appendix F can serve as a second entrance to this book. Begin there, let its compression strike once..."*). Se espera que el lector vuelva al libro después de leer este apéndice, por lo que la frase funciona como **síntesis operativa de la ontología**, no como mero aforismo decorativo.

**Texto original (L2680)**:

> *One frequency alone can oscillate. Two frequencies can enter into relation. From relation comes interference; from interference, pattern; from pattern, the possibility of differential uptake.*

**Naturaleza del error**: mismo error. Aquí el impacto es potencialmente mayor porque la Introducción posiciona este apéndice como entrada privilegiada al libro; el lector que empiece por ahí encuentra la forma comprimida del programa y luego vuelve a los capítulos con esa síntesis en la cabeza.

**Prioridad**: alta. Al ser la "síntesis de trabajo" posicionada como entrada privilegiada, la corrección aquí tiene impacto proporcional.

**Recomendación**: misma corrección que Instancia 1. Para preservar la coherencia entre las tres instancias, es conveniente adoptar **la misma formulación** en las tres (epígrafe Ch. 3, cierre §3.3, epígrafe Ap. F), con la pequeña variación que ya existe hoy entre la versión larga y la versión corta del cierre de §3.3.

---

## 4. Casos borderline (intra-marco, no son errores estrictos)

Estos casos usan abstracciones como sujetos sintácticos de verbos activos, pero lo hacen **coherentemente con la ontología relacional explícita de HIT**. Se listan para completitud; no requieren corrección obligada. Su eventual revisión es una decisión editorial sobre cuán estrictamente se quiere marcar el umbral entre "lenguaje técnico de HIT" y "lenguaje de física estricta".

### Caso B.1 — L265 — §3.1 (Information as pattern, not only as quantity)

**Texto**: *"More specifically, an interval ... may function as a minimal carrier of organization insofar as it generates recurrent, scale-robust, and differentially interpretable patterns."*

**Análisis**: el sujeto implícito de *"generates"* es "the interval". Bajo la tesis central de HIT (intervalo como primitivo relacional), esta atribución es consistente: el intervalo es precisamente lo que HIT propone como agente organizacional. Sin embargo, bajo una lectura de física estricta, lo que genera el patrón es el sistema (las dos componentes en relación), no la relación en sí.

**Recomendación**: no corregir sin decisión editorial. Si se decide corregir, bastaría con explicitar: *"...insofar as the relation it names generates recurrent, scale-robust, and differentially interpretable patterns when instantiated in a physical system."*

### Caso B.2 — L319 — §3.3 (The interval as a minimal informational carrier)

**Texto**: *"Intervals are not abstract ratios floating above the material world; they generate concrete interference organizations."*

**Análisis**: el mismo patrón que B.1. Aquí hay una complicación interesante: la oración explícitamente niega que los intervalos "floten sobre" el mundo material, lo que es una defensa contra la reificación. Pero a renglón seguido les atribuye generación de interferencias. La prosa ESTÁ pidiendo "en sistemas concretos" sin decirlo.

**Recomendación**: no corregir sin decisión editorial. Alternativa fuerte: *"...they organize concrete interference patterns when realized in physical media."* O mantener bajo la licencia ontológica de HIT.

### Caso B.3 — L540 — §6.4 (Dynamical systems, recurrence, and synchronization)

**Texto**: *"Gallozzi and Strollo's work makes clear that simple ratios generate topologically cleaner and more easily closed trajectories than more complex relations do (Gallozzi & Strollo, 2023)."*

**Análisis**: reporte de literatura. "Simple ratios generate" es lenguaje estándar en la literatura de sincronización y figuras de Lissajous. Técnicamente quienes generan las trayectorias son los osciladores cuyas frecuencias están en ratio simple. Pero la formulación es convención científica consolidada en ese campo.

**Recomendación**: no corregir. Lenguaje de campo estándar.

### Caso B.4 — L2718 — Apéndice F §F.6 (Storage, recurrence, and entropy)

**Texto**: *"Thus, when two oscillations relate according to simple proportions, for example `3:2`, the resulting system may exhibit greater dynamic recurrence."*

**Análisis**: "Two oscillations relate" es menos problemático que "two frequencies relate" porque una oscilación **es** un proceso temporal (no un escalar). Sin embargo, estrictamente quienes se relacionan son los dos osciladores, y sus oscilaciones están en ratio. Es metonimia aceptable pero se podría tightening-up.

**Recomendación**: no corregir sin decisión editorial. Alternativa: *"when two oscillators sustain oscillations in simple proportions, for example `3:2`..."*

---

## 5. Lo que funciona bien en el resto del libro

Para contextualizar la corrección y documentar que el error no es estructural, se listan los lugares clave donde el libro articula la misma cuestión **correctamente**:

### 5.1 Capítulo 4 §4.1 — Defensa explícita contra la reificación del ratio

- **L341**: *"A ratio does not sound, radiate, interfere, stabilize, or become salient in a vacuum. It does so only within a concrete field composed of modal constitution, physical transmission, coupling regime, receptive organization, and contextual framing."*
- **L349**: *"The problem begins when one mistakes this recurrent privilege for a complete ontology of consonance."*
- **L355**: *"The deeper conceptual issue is that an isolated ratio easily becomes a metaphysics of presence."*
- **L357**: *"the ratio must be retained without being absolutized. It is best understood as an attractor of structured coordination, not as an autonomous essence."*
- **L361**: *"A stable ratio is therefore not best imagined as a frozen number. It is better understood as a dynamically favored regime..."*
- **L369**: *"the ratio should be treated as an attractor rather than a destiny."*

Este capítulo es, literalmente, el argumento teórico contra el error que el ingeniero marca. El libro ya sabe el problema y lo tematiza.

### 5.2 Capítulo 10 §10.1 — La distinción sistema/perturbación tematizada explícitamente

- **L854**: *"When a bell is struck, the strike does not impose the bell's organization on the metal. It provides energy. The bell supplies the information through its own resonant structure: material, geometry, thickness, and boundary conditions. What rings out is the bell's organization rather than the hammer's content."*

Esta es una exposición explícita de la distinción correcta: sistema (la campana, con sus propiedades) vs. perturbación (el golpe). La organización pertenece al sistema, no al golpe ni a la frecuencia.

### 5.3 Capítulo 12 §12.2 — El Beacon y el principio operativo

- **L1151**: *"The object of study is therefore not a recorded sound file. It is a physically maintained acoustic condition."*
- **L1179**: *"The central operation is therefore not 'play a frequency' but stabilize a proportional field."*

Explícitamente contra la reificación de la frecuencia como objeto de estudio o de producción. El objeto es el campo sostenido (propiedad de un sistema), no una frecuencia aislada.

### 5.4 Apéndice A — Glosario

- **L1991** (*Mode locking*): *"Mode locking names a regime in which oscillatory elements settle into a stable phase or frequency relation."* Agentes: los elementos oscilatorios. Frecuencia: relación. Correcto.
- **L1994** (*Natural harmony*): *"...ratios, overtone-like structures, or linear frequency relations that arise from the resonant organization of the measured system rather than from a perceptual normalization applied afterward."* Agente: el sistema medido. Correcto.
- **L2000** (*Oscillatory portrait*): *"...multiple oscillatory components relate across time, scale, or frequency."* Agentes: componentes oscilatorios. Correcto.
- **L2021** (*Ratio*): *"A ratio is a proportional relation between magnitudes, frequencies, durations... In HIT, ratios matter because they can function as carriers of organization rather than as mere arithmetic descriptors. The manuscript consistently resists turning the ratio into a metaphysical absolute..."* Marca explícita de la tesis relacional sin reificación. Correcto y **lleva además la advertencia editorial**.

### 5.5 Introducción

- **L180**: *"Oscillatory systems settle into preferred regimes, coupled processes lock or nearly lock under simple constraints..."*

Agentes: sistemas oscilatorios, procesos acoplados. Correcto.

### 5.6 Capítulo 3 §3.3 — Prosa inmediatamente previa al cierre errado

- **L315**: *"An interval, in the sense relevant to HIT, is not primarily a named musical object such as a fifth or a third. It is a ratio relation between oscillatory frequencies or, more generally, between modes capable of entering patterned coupling."* Correcto: el intervalo es relación entre frecuencias, y las frecuencias son propiedades de modos/osciladores.
- **L319**: *"When perpendicular oscillations stand in simple relations, the resulting curves exhibit repeatable closure..."* Agentes: oscilaciones (correcto, porque oscilaciones son procesos temporales, no escalares).

Estos párrafos rigurosos hacen aún más visible la grieta rhetórica de la frase aforística que los cierra en L323.

---

## 6. Patrones que se revisaron y resultaron limpios

Los siguientes patrones sintácticos fueron buscados específicamente y no produjeron hits problemáticos:

- `wave/waves + [verb-agent]`: 0 hits relevantes. El único match (L293) habla de "standing-wave organizations preserve a recognizable relational form" — uso técnico correcto (la organización es propiedad del sistema, no de la onda aislada).
- `intervals + [oscillate|propagate|exist]` como agentes físicos: 0 hits. Cuando "intervals" aparece como sujeto, es siempre en relación con "function as carriers", "generate patterns" (intra-marco de HIT), o como objeto de estudio.
- `oscillation/oscillations + [carry|enter|relate]`: 1 hit (L2718, ya listado como Caso B.4 borderline).
- `ratios + [oscillate|vibrate|propagate|emit|travel]`: 0 hits. Los usos de "ratios + verb" que aparecen son todos compatibles con la tesis relacional ("ratios matter", "ratios tend to lock", "ratios can function as carriers", "ratios generate trajectories"), ninguno atribuye oscilación física a la ratio en sí.

---

## 7. Síntesis para el autor

**El ingeniero tiene razón, pero su preocupación queda contenida.** El error específico que identificó está presente, en efecto, pero localizado en tres instancias de una misma figura aforística que se repite en el libro (epígrafe Ch. 3 → cierre §3.3 → epígrafe Ap. F). El libro, en cambio, está globalmente construido sobre una ontología relacional cuidadosa que **ya tematiza** y **defiende contra** el tipo de reificación que el ingeniero señala (Ch. 4 §4.1 es, literalmente, el argumento).

La corrección necesaria es quirúrgica. No hay deriva teórica, no hay contaminación distribuida por los capítulos, no hay un error de fondo en la ontología del programa. Hay una figura rhetórica comprimida que sacrifica precisión física para ganar cadencia aforística, y esa figura aparece tres veces.

---

## 8. Uso de este informe como guía de sincronización LaTeX

Una vez decididas y aplicadas las correcciones al Markdown:

- **Instancia 1** (L261 MD, epígrafe Ch. 3): localizar el epígrafe correspondiente en `LaTeX/chapters/ch03_ontology.tex` (o equivalente) y aplicar la misma corrección.
- **Instancia 2** (L323 MD, cierre §3.3): localizar la oración final del párrafo que cierra §3.3 en el mismo archivo LaTeX y aplicar la misma corrección.
- **Instancia 3** (L2680 MD, epígrafe Apéndice F): localizar el epígrafe en `LaTeX/chapters/appendix_f.tex` (o equivalente) y aplicar la misma corrección.

Las instancias son formas gemelas. Adoptar **una sola fórmula corregida** y aplicarla uniformemente en los tres lugares mantiene la coherencia intra-libro y simplifica la sincronización.

Cualquier decisión sobre los casos borderline del §4 debe tomarse **antes** de pasar al LaTeX, para evitar tener que ejecutar una segunda ronda de sincronización por ajustes menores.

---

## 9. Archivos revisados

- `Harmonic_Information_Theory_Foundations.md` (2754 líneas, leído en su totalidad en las secciones relevantes: introducción, Ch. 1, Ch. 2, Ch. 3 completo, Ch. 4 completo, Ch. 5, Ch. 6 completo, Ch. 7, Ch. 8 completo, Ch. 9 completo, Ch. 10 completo, Ch. 11 §11.1–§11.8, Ch. 12 completo, Ch. 13 completo, Ch. 14, Ch. 15, Ch. 16, Apéndice A glosario, Apéndice F completo).
- Grep sistemático sobre el archivo completo con cinco patrones.

## 10. Qué NO se hizo en esta auditoría

- No se tocó el LaTeX.
- No se modificó el Markdown.
- No se propuso la redacción final de las correcciones (la prosa se decide después).
- No se auditaron las figuras ni las tablas por este error específico (aunque en las tablas hay lenguaje compatible con la ontología relacional, p. ej. Table 5.1 "Ratio is a scale-invariant carrier").
- No se auditó la bibliografía (`bibliografia_HIT.md`) ni `ARQUITECTURA_LIBRO.md`.
