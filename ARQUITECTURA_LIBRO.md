# Harmonic Information Theory: Foundations
## Arquitectura del Libro — Documento Fundacional

**Versión**: 1.8 (2026-03-20)
**Autor**: Mariano Fernández Méndez
**Afiliación**: Asociación Civil AlterMundi
**Redacción asistida**: Claude (Anthropic) y Codex (OpenAI) — se reconocerá en Acknowledgments
**Status**: BORRADOR DE ARQUITECTURA — pendiente aprobación

---

## 0. Qué es este documento

Este archivo define la **arquitectura completa** del libro fundacional de HIT. No es el libro en sí — es su plano.

### Frontmatter

| Elemento | Contenido |
|----------|-----------|
| **Cover** | Title: *Harmonic Information Theory: Foundations*. "Compiled and written by Mariano Fernández Méndez." Research and development team: Anabella Scigliano, Federico Bonino, Julián De La Reta, Martín Fernández Méndez, Nicolás Echániz, Pablo Bustos, Saira Asua, Santiago Cetrán, Sofía Campagnoli. Affiliation: Asociación Civil AlterMundi. "Drafting assisted by Claude (Anthropic) and Codex (OpenAI)." |
| **Preface** | PENDING. Who is the compiler/writer, what is AlterMundi, what motivated the program, how the book was written (including the role of Claude and Codex in drafting), what the book expects from the reader. 2-3 pages. |
| **Acknowledgments** | PENDING. Thanks to external collaborators, institutions, and any recognition beyond the cover team. |
| **Table of Contents** | Automático (LaTeX). |

### Principio rector: Extractabilidad

Cada capítulo se escribe pensando en que pueda ser **extraído casi intacto** para un producto derivado. El libro es la cantera; los derivados son las piedras talladas.

### Productos derivados previstos

| Derivado | Capítulos fuente principales |
|----------|------------------------------|
| **Manifiesto HIT** | 1, 2, 5, 8, 9, 14, Apénd F (10 posible) |
| **Paper teórico** (journal) | 3, 4, 5, 6, 8, 10, 14, Apénd E, F |
| **Paper Phideus** (ML/signal) | 7, 11, 5 (H1-H3), Apénd B, C |
| **Propuesta Beacon** (grant) | 9, 10, 12, 13, 15, 16, Apénd B, D |
| **Paper metodológico** | 7, 11, Apénd C |
| **Divulgación** | 1, 2, 4, 9, 12, 16 |
| **Defensa epistémica** | 5, 8, 10, 16 |

---

## 1. Sistema de registros

Cada sección del libro opera en uno o más **registros**. Esto disciplina la escritura y facilita la extracción.

| Registro | Código | Función | Tono |
|----------|--------|---------|------|
| **Fundacional** | `[F]` | Tesis centrales, definiciones, axiomas | Afirmativo, preciso, citacional |
| **Histórico-documental** | `[H]` | Quién dijo qué, convergencias, genealogía | Narrativo, reconstrucción, mapeo |
| **Conceptual** | `[C]` | Argumentación, distinciones, derivaciones | Analítico, hedge calibrado |
| **Programático** | `[P]` | Métodos, experimentos, resultados, agenda | Técnico, replicable, falsificable |

En el texto final, los registros no se marcan explícitamente — pero el autor los tiene presentes al redactar cada párrafo. En este plano, se indican para guiar la escritura.

---

## 2. Arquitectura: Introducción + 6 Partes, 16 Capítulos

### INTRODUCCIÓN (v2)
*Función primaria: Hacer audible la convergencia que el libro va a nombrar. El lector debe terminar la introducción sabiendo qué tipo de fenómeno está en juego, qué tipo de teoría se propone, y qué le va a costar al libro sostener esa propuesta.*
*Función secundaria: Establecer la voz del autor — firme, precisa, epistemológicamente disciplinada.*
*Función terciaria: Orientar la entrada al libro — la posibilidad retroactiva (Appendix F) como invitación de cierre, no como apertura.*
*Extractabilidad: extractable para derivados (manifiesto, divulgación, grants, presentaciones orales), pero esa no es su función de diseño — viene por añadidura.*

**Registro**: `[C]` Conceptual (dominante) + `[F]` Fundacional (al nombrar HIT, al enunciar la apuesta) + `[H]` Histórico-documental (al evocar la convergencia empírica como fenómeno distribuido). **NO incluye** `[P]` Programático — ningún dato, métrica ni resultado experimental.

**Epígrafe**: Sin epígrafe — abrir directo con la primera frase de prosa.

**Lo que NO es**:
- NO es un resumen del libro (eso es Appendix F)
- NO es el planteamiento del problema (eso es Ch1)
- NO es la formulación de hipótesis (eso es Ch5)
- NO es la formalización del Jpsh! (eso es Ch10)
- NO es un manifiesto (eso es un derivado futuro)

**Analogía arquitectónica**: La Introducción es el **umbral** del edificio. No es el vestíbulo (Ch1), ni la escalera (Ch3-5), ni el mirador (Ch10), ni la terraza (Ch16). Es el momento en que el visitante cruza la puerta y percibe — antes de entender — la escala, la luz, y la dirección del espacio.

**Contenido — 4 movimientos / 6-8 párrafos** (prosa continua, sin headers. Los movimientos son unidades de diseño, invisibles en el texto final. Cada movimiento puede ocupar 1-2 párrafos según densidad — la regla de una función dominante por párrafo manda partir cuando la carga conceptual lo pida):

- **Movimiento 1 — La convergencia que no tiene nombre** `[F]` + `[H]`
  - Abrir con el fenómeno, no con el libro. A través de campos dispares, sistemas se estabilizan por ratios, procesos se acoplan por resonancia, señales adquieren interpretabilidad bajo organización armónica. (Prosa completa desde la primera oración — no fragmentos retóricos.)
  - La convergencia es empírica: física, neurociencia, psicoacústica, dinámica no lineal, ecología, biosemiótica, computación. Cada campo la nombra con vocabulario propio. Ninguno cita a los demás.
  - El problema: cuando el mismo patrón sigue apareciendo sin lenguaje compartido, o es coincidencia o es un problema no formulado.
  - *Directiva*: EVOCAR la convergencia, no mapearla campo por campo (eso es Ch1). Given-new contract: empezar cada oración con lo conocido, cerrar con lo nuevo.

- **Movimiento 2 — El nombre y lo que cuesta** `[F]` + `[C]` **← corazón de la Introducción** (2 párrafos):
  - **¶2a — El nombre y por qué *information***: Harmonic Information Theory. **OBLIGATORIO**: por qué es teoría de la *información*. Una relación armónica se vuelve informacional cuando opera como patrón detectable que reduce incertidumbre, aumenta compresibilidad, y produce diferencia funcional recurrente. La recurrencia no es mera repetición: puede almacenar legibilidad, bajar costos de corrección, abrir diferencia entre campo que fluctúa y campo articulable. (Semilla de Ch3 §3.1 + Ch8 §8.1-8.2.)
  - **¶2b — La disciplina epistémica y los instrumentos**: La ambición debe graduarse por evidencia. Observación / inferencia / conjetura — explícitamente estratificadas. Instrumentos (redes neuronales, modelos, dispositivos acústicos) entran como sondas construidas, no como oráculos. No revelan el mundo transparentemente; ayudan a construir realidades disciplinadas en las que el estatus de una afirmación puede cambiar.
  - *Directiva*: Hedging variado (Hyland). No repetir "may... may... may..."

- **Movimiento 3 — El sonido extraño** `[F]` + `[H]` (1 párrafo, estricto):
  - Jpsh! — palabra improvisada, corporal. Nombra algo preciso: perturbación bien colocada que libera organización latente en el medio. El mismo tipo de presión abductiva ilumina la emergencia del proyecto. Chapter 10 formaliza; aquí basta nombrar.
  - *Directiva estricta*: UN PÁRRAFO. Anuncio promisorio, no revelación. No definir φ, storage/retrieval, readout. No usar "not because... not because..." (prohibido BITACORA). Preferir corporalidad sobre abstracción.

- **Movimiento 4 — La trayectoria y el umbral** `[F]` (2 párrafos):
  - **¶4a — Trayectoria y apuesta**: Oración-cascada (enumeración musical, no tabla de contenidos): tendencia, dispersión, ontología, consonancia, hipótesis, mapa convergente, eficiencia y orientación, activación, instrumentos. Apuesta completa en positivo, sin disclaimers.
  - **¶4b — Entrada retroactiva y demanda**: Existe otra entrada — Appendix F comprime el programa; leerlo primero puede producir reconocimiento retroactivo. Cierre: forma disciplinada de atención. Ni creencia previa ni síntesis prematura. Handoff a Ch1 por tono, no por eco léxico.
  - *Directiva*: Retroactividad como INVITACIÓN DE CIERRE, no como apertura. No incluir kairos ("por qué ahora").

**Qué OMITIR**:

| Elemento | Razón |
|----------|-------|
| Nombres de autores / citas | Pertenecen a los capítulos |
| Datos experimentales | Pertenecen a Ch11 y Appendix B |
| Definición de φ / golden ratio | Pertenece a Ch10 |
| Storage vs retrieval como conceptos técnicos | Pertenece a Ch10 |
| Descripción de Phideus / Beacon como programas | Pertenece a Ch11-12 |
| Lista de hipótesis H1-H6 | Pertenece a Ch5 |
| Negaciones defensivas ("not Pythagoreanism") | Pertenece a Ch14; prohibido por regla anti-defensa preventiva |
| Auto-narración de estructura | Prohibido por regla anti-metadiscursiva |
| Mapeo campo-por-campo | Pertenece a Ch1 |

**Directivas de escritura (específicas)**:
1. **Anti-metadiscursiva reforzada**: cada párrafo HACE, no describe. Sujetos preferentemente fenómenos/sistemas, no "this book"/"this chapter" (default fuerte, no veto absoluto).
2. **No-anticipación**: nombrar que el problema de activación existe; NO definir qué es ni cómo funciona.
3. **No-defensa preventiva**: precisión positiva desarma objeciones sin nombrar enemigo.
4. **Prosa continua**: sin headers internos. Movimientos invisibles en texto final.
5. **Sin bibliografía**: voz del autor, no autoridad de la literatura.
6. **Voz**: firme, precisa, conceptualmente disciplinada. Ni tímida ni grandilocuente.
7. **Tono**: afirmativo, ontológico, sin adornos.

**Relación con frontmatter y capítulos**:
- **Reading note** (LaTeX): complementaria. La reading note instruye; la Introducción, en su cierre, conceptualiza por qué eso funciona.
- **Preface** (PENDING): diferente función. Personal vs conceptual.
- **Ch1**: La Introducción evoca; Ch1 mapea con citas y campos. Sin duplicación si se mantiene gesto vs sustancia.
- **Ch10**: La Introducción nombra Jpsh! y señala; Ch10 formaliza.
- **Appendix F**: La Introducción cierra mencionándolo; Appendix F es la síntesis comprimida.

**Longitud**: Criterio funcional — cada movimiento ocupa lo que necesite. Sin target numérico. Verificación cualitativa: ¿cada párrafo gana su lugar?

**Verificación** (para cuando Codex escriba la prosa):
1. Densidad funcional: ¿cada párrafo gana su lugar? ¿alguno cortable sin pérdida?
2. Test anti-metadiscursivo: ¿algún párrafo describe en vez de hacer?
3. Test de no-anticipación: ¿algún concepto de Ch10 explicado en vez de nombrado?
4. Test de no-duplicación con Ch1: ¿evoca o mapea?
5. Lectura corrida Introducción → Ch1: handoff natural.
6. Test de autonomía: ¿se entiende HIT sin ningún capítulo previo?
7. Después de insertar prosa: regenerar STRUCTURAL INDEX.
8. Complementariedad con reading note: no duplicar instrucción práctica.

---

### PARTE I — LA OBSERVACIÓN Y EL PROBLEMA
*Función: Plantar la bandera. Por qué este documento existe.*
*Extractabilidad: → Manifiesto (apertura), → Divulgación, → Intro de cualquier paper*

---

#### Capítulo 1. La tendencia
**Registro**: `[F]` + `[H]`
**Epígrafe**: *"Hay algo ahí que merece un nombre"*

**Contenido**:
- Observación fundante: campos dispares encuentran, independientemente, que las relaciones armónicas, resonantes y ondulatorias importan
- No hay hilo de Ariadna entre estos trabajos — cada campo cita a los suyos
- Mapa de convergencia: Maxwell/de Broglie/LIGO (ondas y campos), Large (neural resonance), Gill/Purves (vocal similarity), Canolty/Knight (CFC), Stolzenburg (periodicidad), Erlich (harmonic entropy), Krause (nicho acústico), Feng/Wang (neuronas template)
- Ventana de frontera: literatura peer-reviewed que empuja el problema hacia mente/materia/consciencia desde fisica y ontologia (`Orch OR`, dualismo interactivo cuantico, `conscious realism`, `analytic idealism`)
- HIT como propuesta de coordinación, no de unificación
- El sonido y la música como laboratorio privilegiado, no como límite ontológico del marco

**Bibliografía pertinente**:

*Primarias* (argumentos centrales — los hilos de convergencia):
- Maxwell (1865) §1.4 — campo electromagnético: primacía de propagación y modo
- de Broglie (1925) §1.4 — ondas de materia: extensión del lenguaje ondulatorio a la materia
- Abbott et al. (2016) §1.4 — ondas gravitacionales: confirmación empírica del registro gravitacional
- Large & Almonte (2012) §1.1 — resonancia neural como base de percepción tonal
- Canolty & Knight (2010) §1.1 — CFC: cerebro usa ratios simples como mecanismo de integración
- Jacobs et al. (2025) §1.1 — ondas viajeras codifican geometría vía eigenfrequency ratios
- Krause (2013) §1.3 — biofonía y nicho acústico: eficiencia espectral en ecosistemas
- Kuramoto (1984) §1.4 — osciladores acoplados, Arnold tongues: ratios simples tienen cuencas más anchas
- Trulla et al. (2018) §1.4 — RQA revela consonancia como propiedad de recurrencia de la señal
- Hoffmeyer (2008) §1.3 — biosemiótica: signos en sistemas vivos
- Schwartz et al. (2003) §1.2 — estadística del habla humana predice universales musicales

*Secundarias* (cada campo como hilo independiente):
- Davisson & Germer (1927) §1.4 — difracción de electrones: validación experimental de ondas de materia
- Engels et al. (2007) §1.4 — Faraday waves en BEC: patrón resonante en fluido cuántico
- Nguyen et al. (2019) §1.4 — excitación paramétrica y granulación en BEC
- Hameroff & Penrose (2014) §1.4 — `Orch OR`: frontera donde coherencia cuántica, materia y consciencia vuelven a encontrarse
- Stapp (2005) §1.4 — dualismo interactivo cuántico: reapertura del estatuto causal de la consciencia
- Hoffman (2008) §1.4 — `conscious realism`: spacetime como interfaz, no como primitivo último
- Kastrup (2017a, 2017b) §1.4 — idealismo analítico: materia como apariencia extrínseca de mentación
- Large & Tretakis (2005) §1.1 — resonancia no lineal y tonalidad
- Bidelman & Krishnan (2009) §1.1 — jerarquía de consonancia codificada en brainstem
- Bidelman & Heinz (2011) §1.1 — consonancia desde el nervio auditivo
- Plomp & Levelt (1965) §1.2 — modelo fundacional de roughness
- von Helmholtz (1863) §1.2 — tratado fundacional: sensaciones tonales
- Bowling & Purves (2015) §1.2 — justificación biológica de consonancia
- Roederer (2008) §1.2 — manual de referencia física-psicoacústica
- Oxenham (2012) §1.2 — revisión de percepción de pitch
- Feld (1982) §1.3 — Kaluli: sistema musical derivado de sonidos del bosque
- Barbieri (2008) §1.3 — síntesis biosemiótica
- Buxton et al. (2021) §1.3 — beneficios de salud de sonidos naturales
- Snowdon (2021) §1.3 — señales animales y bienestar emocional
- Strogatz (2000) §1.4 — dinámica no lineal: "la naturaleza tiene ansia de orden"
- Pikovsky et al. (2001) §1.4 — sincronización como concepto universal
- Gallozzi & Strollo (2023) §1.4 — Lissajous: ratios simples → curvas simples
- Lots & Stone (2008) §1.1 — consonancia como sincronización neural
- Foo et al. (2016) §1.1 — procesamiento cortical diferencial
- Hunt & Schooler (2019) §1.1 — teoría de resonancia de la consciencia
- Pankovski & Pankovska (2017) §1.1 — consonancia emergente en redes hebbianas
- Hoeschele et al. (2012) §1.5 — percepción cross-especie
- Toro & Crespo-Bojorque §1.5 — discriminación consonancia en ratas
- Walker et al. (2006) §1.5 — percepción de intervalos en aves
- Morton (1977) §1.5 — reglas motivación-estructura en vocalizaciones

**Longitud estimada**: 3000-4000 palabras (ESCRITO: ~2500 palabras)

---

#### Capítulo 2. El problema de la dispersión disciplinaria
**Registro**: `[H]` + `[C]`
**Epígrafe**: *"What converges in the world disperses in the disciplines."*

**Contenido**:
- Análisis de por qué estos campos no se reconocen mutuamente
- Barreras: vocabulario, ontologías locales, incentivos de publicación, tradiciones metodológicas
- Incluir explícitamente la fractura entre acústica, neurociencia, dinámica no lineal y física de campos/ondas
- Galison (trading zones), Star & Griesemer (boundary objects): marco para entender la no-comunicación
- La dispersión como problema epistémico: cada campo reinventa parcialmente la rueda
- HIT como categoría epistémica: no es una teoría cerrada, es el reconocimiento de un patrón y la propuesta de investigarlo coordinadamente
- Posicionamiento à la Lakatos: programa de investigación con hard core (los ratios importan) y protective belt (mecanismos por determinar)
- Guardrail metodológico: no confundir analogía fértil con isomorfismo estructural fuerte

**Bibliografía pertinente**:

*Primarias* (marco de análisis de la dispersión):
- Galison (1997) §2.5 — trading zones: intercambio entre subculturas científicas
- Lakatos (1970) §7.2 — programas de investigación: hard core + cinturón protector
- Popper (1959) §7.2 — falsificabilidad como criterio de demarcación

*Secundarias* (ejemplos de dispersión y constraint):
- Parncutt & Hair (2011) §7.1 — estudios críticos sobre consonancia
- McDermott et al. (2016) §3.5/§7.1 — Tsimane: constraint cultural sobre universalidad
- Elitzur & Vaidman §2.5 — zonas epistémicas
- Lotman (2005) §2.5 — semiosfera, frontera y traducción entre espacios semióticos
- Calvo Vélez (2006) §2.5 — crítica del isomorfismo: guardrail contra extrapolación estructuralista ingenua
- Star & Griesemer (1989) §2.5 — boundary objects: objetos reconocibles por múltiples comunidades
- Kuhn (1962) §7.2 — paradigmas: la convergencia HIT como estado pre-paradigmático

**Longitud estimada**: 2500-3500 palabras (ESCRITO: ~1900 palabras)

---

### PARTE II — FUNDAMENTOS ONTOLÓGICOS
*Función: Definir los conceptos centrales con rigor.*
*Extractabilidad: → Paper teórico, → Glosario técnico, → Defensa epistémica*

---

#### Capítulo 3. Ontología de la información armónica
**Registro**: `[F]` + `[C]`
**Epígrafe**: *"La información emerge de la relación, no de la sustancia"*

**Contenido**:
- **§3.1 Definición integradora de información**: 4 capas convergentes
  - Shannon: patrón que reduce incertidumbre
  - Algorítmica: patrón que aumenta compresibilidad (Dubnov: saliencia por predictibilidad estructurada)
  - Bateson: diferencia que hace una diferencia (efectos funcionales)
  - Oscilatorio: asociación a estabilidad/recurrencia en sistemas dinámicos y wave-bearing (Kuramoto, Canolty & Knight)
  - **Definición de trabajo**: información = relación estructurada o patrón detectable en señal o sistema que, para un observador/sistema/modelo dado, reduce incertidumbre, aumenta compresibilidad y produce diferencia funcional recurrente. Bajo condiciones físicas adecuadas puede participar también en reducciones locales de entropía efectiva, sin confundirse con incertidumbre shannoniana. Lo informacional no es ventana transparente al `the Real`, sino traza estructurada de una resistencia. Información armónica = subconjunto restringido a relaciones entre procesos oscilatorios o mode-bearing
- **§3.2 La relación como ontológicamente primaria** — bloque filosófico-semiótico expandido, organizado por ejes:
  - Heidegger + Bohm + Simondon + Barad: relación antes que sustancia (ser-en-el-mundo, orden implicado, individuación, intra-acción)
  - Hoffman + Kastrup: radicalizaciones contemporáneas de la prioridad de relación/apariencia/experiencia sobre la sustancia material clásica
  - Maturana + Varela: autopoiesis como caso paradigmático de ontología relacional en biología. El sistema vivo no se define por sus componentes sino por la *organización* (red de relaciones que los produce). Distinción organización/estructura: la organización es el patrón invariante de relaciones (≈ ratio como carrier invariante de escala en HIT); la estructura es la instanciación concreta (≈ frecuencias absolutas). HIT propone una analogía: el ratio es la organización, las frecuencias son la estructura. Clausura operacional como patrón relacional: el sistema genera los procesos que lo generan — circularidad productiva. Conexión con §3.3: la onda estacionaria es operacionalmente cerrada (su patrón se autosostiene) pero energéticamente abierta. Se desarrolla en Cap 4 (acoplamiento estructural como consonancia), Cap 8 (eficiencia vía precariedad) y Cap 9 (sentido biológico de la consonancia). **Cautela**: la analogía clausura operacional ↔ patrón de interferencia es programática, no demostrada. No estamos afirmando que las ondas estacionarias son autopoiéticas (no regeneran sus componentes materiales) — sino que comparten la propiedad de ser organizacionalmente invariantes bajo cambio de estructura
  - Derrida + Lacan: significación diferencial (différance, traza, "nunca ofrecida al presente", sujeto barrado, cadena significante, campo del Otro)
  - Jung + Von Franz: el Self como centro relacional de la psique — no sustancia fija sino principio organizador que no es ego ni inconsciente, sino la relación dinámica entre ambos. "Factor interno de orientación, muy diferente de la personalidad consciente" (Von Franz, 1964). Precedente de ontología relacional en psicología profunda: lo constitutivo no es una instancia sino un proceso de integración (individuación). Se desarrolla en Cap 9 (consonancia como orientación psíquica) y Cap 12 (articulación terapéutica con Beacon)
  - Lotman + Peirce + Bateson: espacio semiótico y traducción (semiosfera, frontera, signo triádico, diferencia eficaz)
  - Nietzsche + Wheeler: cautela anti-reificación + reversión ontológica de la información ("it from bit")
  - **Advertencia**: no colapsar esta ontología relacional en monismo ingenuo ("todo es onda"); la formulación prudente es que gran parte de la física moderna describe procesos en términos de campos, modos, propagaciones y patrones resonantes, y HIT toma ese paisaje como trasfondo de inteligibilidad
  - **Criterio de escritura**: si el bloque amenaza con saturarse, desplazar desarrollo adicional a nota o apéndice antes que comprimir autores densos en párrafos demasiado breves
- **§3.3 El intervalo como carrier informacional mínimo**: ratio f₁:f₂ genera un patrón de interferencia con 4 propiedades:
  - Robustez de escala (invariante bajo multiplicación por k)
  - Generación de patrón (Lissajous, Faraday, cymatics)
  - Privilegio dinámico (Arnold tongues, mode-locking: Kuramoto, Canolty, Jacobs)
  - Interpretabilidad diferencial (Bateson: un ratio es informativo cuando constrainta diferente que otro)
- **§3.4 Proposición ontológica mínima**: Formalización: dado f₁, f₂, el ratio r = f₁:f₂ crea un patrón de interferencia cuyas propiedades son independientes de las frecuencias absolutas. Tres niveles de compromiso: observación (convergencia distribuida), hipótesis (intervalos como carriers), inferencia (ontología relacional > sustancialista)
- Guardrail: HIT no afirma isomorfismo simple entre modelos acústicos y toda la realidad física (Calvo Vélez, 2006)

**Bibliografía pertinente**:

*Primarias* (las 4 capas de información + intervalo como unidad):
- Shannon (1948) §2.1 — teoría de la información: patrón que reduce incertidumbre
- Bateson (1972) §2.1 — "diferencia que hace una diferencia": capa funcional
- Maxwell (1865) §2.2 — campo y propagación: inteligibilidad física de procesos ondulatorios
- de Broglie (1925) §2.2 — ondas de materia: extensión del patrón relacional al dominio material
- Bohm (1980) §2.2 — orden implicado: la relación como fundamental
- Kuramoto (1984) §1.4 — mecanismo de ratios: asociación a estabilidad/recurrencia
- Canolty & Knight (2010) §1.1 — CFC: ratios como integración informacional en cerebro
- Jacobs et al. (2025) §1.1 — ratios como codificadores geométricos vía eigenespectros
- Gallozzi & Strollo (2023) §1.4 — Lissajous: recurrencia hecha visible por ratios
- Wheeler (1990) §2.1 — "it from bit": información como constitutiva del orden

*Secundarias* (marco filosófico y formalizaciones):
- Peirce (1931) §2.1 — semiótica triádica
- Dubnov (2004) §2.1 — información y expectativa musical
- Simondon (1958) §2.2 — individuación y proceso
- Barad (2007) §2.2 — realismo agencial: lo que existe es relacional
- Heidegger (1927) §2.2 — being-in-the-world: significatividad antes que objeto aislado
- Hoffman (2008) §2.2 — `conscious realism`: spacetime como interfaz relacional de agentes conscientes
- Kastrup (2017a) §2.2 — plausibilidad filosófica del idealismo como ontología
- Kastrup (2017b) §2.2 — formulación ontológica del idealismo analítico
- Derrida (1967/1976; 1968/1982) §2.2 — différance y traza: sentido por diferencia, no por presencia plena
- Lacan (1966) §2.2 — el sujeto como efecto de la cadena significante y del Otro
- Lotman (2005) §2.5 — semiosfera: primacía del espacio relacional y la traducción
- Jung (1959) CW 9/1 §2.2 — Self como centro relacional de la psique: no sustancia sino proceso de integración
- Von Franz (1964) §2.2 — individuación: "factor interno de orientación, muy diferente de la personalidad consciente"
- Nietzsche (1873) §2.2 — verdad y metáfora: advertencia contra reificar conceptos como esencias
- Strogatz (2000 Physica D) §1.4 — revisión canónica del modelo de Kuramoto
- Acebrón et al. (2005) §1.4 — chimera states: sincronización parcial como régimen estable
- Hermoso de Mendoza et al. (2016) §1.4 — Kuramoto cuántico: robustez cross-régimen
- Davisson & Germer (1927) §2.2 — difracción de electrones: confirmación experimental del registro ondulatorio
- Abbott et al. (2016) §2.2 — ondas gravitacionales: la relación propagante como objeto físico
- Lissajous (1857) §6.3 — estudio óptico de vibraciones perpendiculares
- Jenny (1967) §6.3 — cymatics: "el sonido tiene forma"
- Calvo Vélez (2006) §2.5 — crítica del isomorfismo: advertencia contra sobregeneralización estructural
- Maturana & Varela (1973/1980) §2.2 — autopoiesis: sistema como red de procesos que regenera sus componentes. Organización ≈ ratio (invariante), estructura ≈ frecuencias (cambiante)
- Maturana (1970/1980) §2.2 — biología de la cognición: clausura operacional, determinismo estructural, el observador
- Varela (1979) §2.2 — autonomía biológica: generalización de autopoiesis a sistemas autónomos. Clausura operacional como propiedad organizacional
- Varela, Maturana & Uribe (1974) §2.2 — artículo fundacional: autopoiesis como organización de los sistemas vivos
- Luhmann (1995) §2.2 — extensión de autopoiesis a sistemas sociales (NOTA: HIT NO sigue la extensión luhmanniana; mencionarla para demarcar)
- Fernández Méndez (2021b) §2.2 — "clausura relacional": sistemas de saber que logran autosostenimiento mediante clausura relacional sobre sus propios elementos. CONVERGENCIA con clausura operacional de Maturana/Varela, alcanzada desde tradición independiente (Lacan/Dejours/Mauss)
- Fernández Méndez (s.f.) §2.2 — clausura operacional alcanzada desde Gödel/Chaitin/recursividad computacional. CONVERGENCIA TRIPLE: Gödel (matemática) ≈ Maturana/Varela (biología) ≈ Varela 1975 (cálculo de auto-referencia). Tres tradiciones, mismo insight: la auto-referencia recursiva genera organización pero nunca cierra completamente

**Longitud estimada**: 3000-4000 palabras (ESCRITO: ~2800 palabras)

---

#### Capítulo 4. Consonancia como función relacional
**Registro**: `[F]` + `[C]`
**Epígrafe**: *"La armonía natural no reside en la rigidez del ratio puro"*

**Contenido**:
- **Tesis central**: Cons = F(ratio, constitución modal/espectral, medio_físico, régimen de acoplamiento, sistema_receptor, contexto)
  - La consonancia NO es propiedad absoluta del intervalo
  - La consonancia ES función relacional del sistema completo
  - El término "consonancia" se conserva desde el dominio sonoro, pero el problema es más amplio que la acústica
- **Estabilidad dinámica vs. rigidez matemática**:
  - No es pitagorismo: el ratio puro es un atractor, no un destino
  - "Suficientemente estable, suficientemente dinámica"
  - La desviación óptima como capacidad de amortiguación adaptativa
  - Rigidez perfecta = alto costo energético; entropía cero = detenimiento/muerte
- **Armonía natural vs. armonía temperada**:
  - La serie armónica como fenómeno físico (64, 128, 192, 256...)
  - La escala temperada como artefacto cultural (12-TET, modulación libre)
  - "Toda la música que hacemos está un poco desafinada respecto de cómo suena el universo"
  - Modulación natural = cambiar de perspectiva/centro; modulación temperada = desplazar grilla uniforme
- **Cada sistema físico tiene SU armonía natural**: las resonancias del medio divergen del ideal matemático
- **Consonancia como acoplamiento estructural** (Maturana & Varela → Kuramoto):
  - Acoplamiento estructural: historia de interacciones recurrentes entre sistema y entorno que resulta en congruencia estructural mutua. Los Arnold tongues formalizan esto para osciladores: ratios simples (2:1, 3:2) tienen cuencas de atracción más anchas → el acoplamiento estructural es más probable para ratios simples
  - Lectura HIT: la consonancia no es propiedad estática del intervalo sino resultado de un acoplamiento exitoso. La "estabilidad suficiente" de este capítulo es exactamente lo que el acoplamiento estructural describe: congruencia recurrente, no identidad rígida
  - La desviación óptima reinterpretada: el sistema acoplado mantiene organización (ratio) mientras permite variación estructural (frecuencias, amplitudes, fase). El drift es adaptativo, no degenerativo
  - Determinismo estructural: la respuesta del sistema al acoplamiento depende de su propia estructura, no de la señal entrante. Esto conecta con "cada sistema tiene SU armonía"
  - **Cautela**: el acoplamiento estructural de Maturana opera en sistemas vivos con memoria y plasticidad; el mode-locking de Kuramoto opera en osciladores genéricos. La convergencia formal no implica identidad ontológica
- La música funciona aquí como laboratorio histórico privilegiado, no como frontera ontológica

**Bibliografía pertinente**:

*Primarias* (consonancia relacional + estabilidad dinámica):
- Kuramoto (1984) §1.4 — Arnold tongues: cuencas de atracción proporcionales a simplicidad del ratio
- Sethares (2005) §3.2 — tuning y timbre: consonancia depende del espectro, no solo del ratio
- Trulla et al. (2018) §1.4 — consonancia como propiedad de recurrencia de la señal
- Acebrón et al. (2005) §1.4 — chimera states: parcialidad armónica como régimen estable
- Engels et al. (2007) §1.4 — Faraday waves en BEC: estabilidad resonante en fluido cuántico
- Nguyen et al. (2019) §1.4 — excitación paramétrica: orden y transición de régimen

*Secundarias* (modelos de roughness, historia, contexto):
- Plomp & Levelt (1965) §1.2 — modelo fundacional de roughness por banda crítica
- von Helmholtz (1863) §1.2 — sensaciones tonales: base fisiológica
- Partch (1949) §3.2 — entonación justa y límite de 11
- Tenney (1988) §3.2 — historia conceptual de consonancia/disonancia
- Heidegger (1927) §3.2 — mundo y significatividad: la consonancia aparece en horizonte relacional
- Derrida (1967) §3.2 — crítica de la presencia plena: contra esencializar el ratio puro
- Nietzsche (1873) §3.2 — verdad y metáfora: advertencia contra reificar categorías sonoras
- Glass & Mackey (1988) §1.4 — osciladores biológicos: escalera del diablo en fisiología
- Strogatz (2000) §1.4 — dinámica no lineal: mode-locking
- Cartwright et al. (2001) §4.1 — percepción de pitch como mode-locking
- Pikovsky et al. (2001) §1.4 — sincronización como concepto universal

- Erlich (2000) §1.2 — entropía armónica: formalización de privilegio armónico
- Stolzenburg (2015) §1.2 — periodicidad: consonancia como eficiencia de detección

*Autopoiesis y acoplamiento estructural* (§4 — consonancia como acoplamiento):
- Maturana & Varela (1973/1980) §2.2 — acoplamiento estructural: congruencia recurrente entre sistema y entorno
- Di Paolo (2005) §5.5 — precariedad como fuente de normatividad: la armonía importa porque la organización es frágil

*Fuentes no bibliográficas*:
- Formulación oral atribuida a Echaniz Nicolas; evitar citar documento interno en la versión pública

**Longitud estimada**: 3000-4000 palabras (ESCRITO: ~3200 palabras)

---

#### Capítulo 5. Hipótesis centrales de HIT
**Registro**: `[F]`
**Epígrafe**: *"A program becomes legible when its strongest claims stop hiding among its weakest ones."*

**Contenido**: Enumeración explícita y formal de las hipótesis, con nivel de evidencia.

| # | Hipótesis | Nivel | Evidencia |
|---|-----------|-------|-----------|
| H1 | Las señales naturales contienen distribuciones de ratios estructuradas (no aleatorias) | **Validada** | Phideus: distribuciones no-random en audio, MIDI, speech, EGG |
| H2 | Estas distribuciones son aprendibles por sistemas computacionales | **Validada** | Phideus: val_loss < 0.5 en múltiples arquitecturas |
| H3 | La estructura de ratios es compartida cross-modalmente | **En test** | Escalón 1: S=84.1%, evidencia causal. Escalón 2: en curso |
| H4 | Los ratios armónicos simples minimizan costo de procesamiento (eficiencia informacional) | **Conjetura informada** | Landauer + RQA + VFE: argumento teórico + evidencia indirecta |
| H5 | Los sistemas biológicos tienen un "sentido de la consonancia" funcional | **Conjetura informada** | Neurociencia (Large, Kawai, Zheng), psicoacústica, ecología (Krause), retratos oscilatorios y CFC computable |
| H6 | El intervalo (ratio) es un carrier de información invariante de escala | **Hipótesis fundante** | Marco teórico; tests parciales via cross-frequency |

- Para cada hipótesis: formulación precisa, predicciones falsificables, estado actual, qué experimento la resolvería
- Distinción clara entre lo que HIT *afirma*, lo que *conjetura*, y lo que *propone investigar*
- **Formalización mínima**:
  - ratio básico: `r = f_2 / f_1`
  - forma reducida: `r_red = p / q`
  - invariancia por reescalado: si `f'_1 = k f_1` y `f'_2 = k f_2`, entonces `r' = r`
- **Criterio editorial**: introducir solo la matemática que estabiliza el argumento; la futura versión LaTeX importa, pero no debe rigidizar la prosa actual

**Bibliografía pertinente** (organizada por hipótesis):

*H1 — Estructura*:
- Trulla et al. (2018) §1.4 — RQA: distribuciones no-random de recurrencia

*H2 — Aprendibilidad*:
- [Resultados Phideus — fuente interna: val_loss < 0.5]

*H3 — Cross-modality*:
- Canolty & Knight (2010) §1.1 — CFC como precedente de cross-frequency sharing
- Pearl (2009) §6.2 — diseño causal: controles negativos para claims causales

*H4 — Eficiencia informacional*:
- Landauer (1961) §4.2 — costo energético mínimo de borrar información
- Still et al. (2012) §4.2 — termodinámica de predicción: estructura → eficiencia
- Friston (2010) §2.4 — free energy principle: minimizar sorpresa

*H5 — Sentido biológico*:
- Large & Almonte (2012) §1.1 — resonancia neural en brainstem
- Blood & Zatorre (2001) §5.1 — recompensa dopaminérgica ante música
- Levin (2021) §5.5 — bioelectricidad: comportamiento depende de RATIOS iónicos
- Glass & Mackey (1988) §1.4 — mode-locking biológico: ratio 4:1 respiratorio-cardíaco
- Kawai (2023) §1.1 — acoplamiento armónico lento entre ritmos cardiorrespiratorios y tronco encefálico
- Zheng et al. (2025) §1.1 — relaciones alfa-theta cercanas a armónicos y estados atencionales
- Bahuguna et al. (2025) §1.1 — retratos oscilatorios multifrecuencia con poder predictivo conductual
- Medvedev & Lehmann (2025) §1.1 — matrices de coupling cross-frequency como objeto computable para clasificación EEG

*H6 — Intervalo como carrier*:
- Shannon (1948) §2.1 — teoría de la información
- Kuramoto (1984) §1.4 — Arnold tongues: universalidad de ratios simples
- Jacobs et al. (2025) §1.1 — eigenfrequency ratios codifican geometría

*Fuentes no bibliográficas*:
- Documentación Phideus (resultados experimentales por gate/escalón)
- Echaniz HackMD §7.4 (formulaciones originales HIT)

**Longitud estimada**: 2500-3000 palabras (ESCRITO: ~3300 palabras)

---

### PARTE III — ESTADO DEL CONOCIMIENTO
*Función: Mapear qué se sabe, quién lo sabe, y qué falta.*
*Extractabilidad: → Review section de cualquier paper, → Background de grants*

---

#### Capítulo 6. Convergencia empírica: el mapa del SOTA
**Registro**: `[H]` + `[C]`

**Contenido**:
- **Neurociencia**: Large (neural resonance), Canolty/Knight (cross-frequency coupling), Feng/Wang (template neurons), SSR, entrainment
- **Actualización 2023-2025 de neuroseñales**: Kawai (tronco encefálico y armónicos lentos), Zheng (alpha-theta y atención), Bahuguna (retratos oscilatorios), Medvedev & Lehmann (CFC + deep learning)
- **Extensión multimodal reciente**: Soriano et al. (respiración, corazón y EEG durante foco atencional / breath-focus) como caso donde la coordinación entre sistemas fisiológicos también puede describirse en términos de proporciones y direccionalidad entre ritmos
- **Psicoacústica**: Gill/Purves (vocal similarity), Stolzenburg (periodicidad), Erlich (harmonic entropy), modelos de rugosidad
- **Ecología acústica**: Krause (nicho acústico, biofonía vs. geofonía vs. antropofonía), benchmarks de conservación
- **Dinámica de sistemas**: Recurrencia, atractores, estabilidad en osciladores acoplados
- **Topologías visibles de interferencia**: Chladni, Lissajous, singularidades de fase, patrones nodales
- **Medios de interferencia controlada**: estabilidad, drift y transiciones topológicas bajo barridos racional vs. irracional; distinción entre medio, excitación e interacción
- **Biosemiótica**: Hoffmeyer (código dual), Barbieri (códigos orgánicos), la recurrencia como mecanismo de compresión entre niveles
- **Teoría de la información**: Shannon, Landauer, free energy principle (Friston), predictive coding
- **Frontera adyacente**: neurobiología cuántica y programas de consciencia cuántica como borde activo del mismo espacio de preguntas, pero no como fundamento empírico principal del capítulo
- **Para cada campo**: qué descubrieron, qué vocabulario usan, qué no ven del panorama completo
- **Criterio de escritura**: la justificación de por qué cada campo importa al argumento de convergencia debe estar integrada dentro de la primera oración del primer párrafo de la subsección, no como encabezado separado ni como párrafo independiente previo

**Bibliografía pertinente** (organizada por subcampo del SOTA):

*Neurociencia — resonancia neural y CFC* (§1.1):
- Large & Almonte (2012), Large & Tretakis (2005) — resonancia no lineal y tonalidad
- Bidelman & Krishnan (2009), Bidelman & Heinz (2011) — jerarquía de consonancia pre-cortical
- Canolty & Knight (2010) — CFC: ratios simples como mecanismo de integración
- Jacobs et al. (2025) — ondas viajeras: eigenfrequency ratios codifican geometría
- Kawai (2023) — armónicos lentos y coupling fisiológico en tronco encefálico
- Zheng et al. (2025) — relaciones alfa-theta y decodificación de atención
- Soriano et al. (2025) — interacciones cardiorrespiratorias y neurales durante foco atencional y breath-focus
- Bahuguna et al. (2025) — retratos oscilatorios multifrecuencia y comportamiento visuomotor
- Medvedev & Lehmann (2025) — clasificación de ausencias basada en matrices de coupling cross-frequency
- Foo et al. (2016) — registros intracorticales de discriminación consonancia
- Lots & Stone (2008) — consonancia como sincronización neural
- Pankovski & Pankovska (2017) — consonancia emergente en redes hebbianas
- Hunt & Schooler (2019) — resonancia y consciencia
- Jedlicka (2017) — quantum neurobiology como frontera teórica activa
- Hameroff & Penrose (2014) — `Orch OR` como borde fuerte de la pregunta consciencia/coherencia/organización
- Varela, Lachaux, Rodriguez & Martinerie (2001) — "The Brainweb": integración neural a gran escala por sincronización de fase entre ensambles distribuidos. No hay "director" central — autoorganización resonante. Cita clave: "The oscillation patterns produced in different parts of the brain are actually converging with a kind of synchrony of resonance. It is like an orchestra coming together musically, but without a director." Conexión HIT: si la integración neural usa sincronización de fase (ratios de frecuencia), HIT describe una propiedad fundamental del mecanismo de integración neural, no solo de la acústica
- Rodriguez, George, Lachaux, Martinerie, Renault & Varela (1999) — sincronización gamma durante percepción gestáltica: la percepción coherente emerge de resonancia inter-areal
- Singer (1999) — sincronía neuronal como código relacional: complemento del marco de Varela

*Psicoacústica* (§1.2):
- Plomp & Levelt (1965) — modelo roughness / banda crítica
- von Helmholtz (1863) — sensaciones tonales: base histórica
- Roederer (2008) — manual física-psicoacústica
- Schwartz et al. (2003) — estadística del habla predice universales musicales
- Bowling & Purves (2015) — justificación biológica de consonancia
- Oxenham (2012) — revisión percepción de pitch

*Ecología acústica y biosemiótica* (§1.3):
- Krause (2013) — biofonía y nicho acústico
- Hoffmeyer (2008) — biosemiótica: signos en sistemas vivos
- Barbieri (2008) — códigos orgánicos
- Buxton et al. (2021) — beneficios de salud de sonidos naturales
- Feld (1982) — Kaluli: música derivada del bosque
- Snowdon (2021) — señales animales y bienestar

*Autopoiesis y autonomía biológica* (§2.2/§5.5 — marco integrador):
- Maturana & Varela (1973/1980) — autopoiesis: sistema como red de procesos que regenera sus propios componentes. Marco más amplio que la biosemiótica: Hoffmeyer describe los signos; Maturana/Varela describen el sistema que produce y responde a esos signos. Los "códigos orgánicos" de Barbieri son instancias de acoplamiento estructural
- Di Paolo (2005) — precariedad como fuente de normatividad: un sistema autónomo es normativo porque es precario — su organización puede desintegrarse. La armonía importa porque su pérdida amenaza la organización. Conexión HIT: la consonancia no es estéticamente preferible sino organizacionalmente necesaria

*Dinámica de sistemas y recurrencia* (§1.4):
- Kuramoto (1984) — modelo de osciladores acoplados
- Trulla et al. (2018) — RQA revela consonancia como recurrencia
- Eckmann et al. (1987) — introducción de recurrence plots
- Marwan et al. (2007) — revisión comprensiva de RQA
- Strogatz (2000 textbook + Physica D) — dinámica no lineal + revisión Kuramoto
- Pikovsky et al. (2001) — sincronización como concepto universal
- Acebrón et al. (2005) — chimera states
- Glass & Mackey (1988) — osciladores biológicos
- Schroeder (1990) — escalera del diablo como huella de mode-locking
- Cartwright et al. (2001) — pitch como mode-locking
- Gallozzi & Strollo (2023) — Lissajous: topología de recurrencia visual
- Berry & Dennis (2001) — singularidades de fase y topología nodal en campos ondulatorios
- Maynard et al. (1985) §6.5 — medición de campos e inferencia espacial: guardrail para pasar de patrón visible a problema de campo

*Percepción cross-especie* (§1.5):
- Hoeschele et al. (2012), Toro & Crespo-Bojorque, Walker et al. (2006)
- Morton (1977), Wagner et al.

*Consonancia, percepción tonal y tradiciones* (§3.1-3.5):
- Gonzalez-Garcia et al., Koelsch et al. (2005), Koelsch & Mulder — procesamiento neural
- Wang, Piana, Park et al., Frova — modelos y percepción
- Sethares (2005), Partch (1949), Tenney (1988) — entonación justa y temperamento
- Arom (1991) — polifonía Aka basada en armónicos naturales
- Levin & Suzukei (2006) — canto de garganta tuvánico: armónicos aislados
- Turnbull (1961) — Mbuti: polifonía armónica cíclica
- Jordania, Kubik, Turino, Grauer, Merriam, Blacking (1973), McNeil & Mitran — etnomusicología
- Conard et al. (2009) — flautas de 40,000 años: ratios simples
- Reznikoff & Dauvois, Morley, Fazenda et al., Turk et al. — arqueoacústica
- McDermott et al. (2016) — Tsimane: constraint cultural sobre universalidad
- Nees & Phillips, Nikolsky — pareidolia y escalas prehistóricas

*Teoría de la información y procesos* (§2.1-2.4):
- Shannon (1948) — teoría de la información
- Peirce (1931) — semiótica triádica
- Dubnov (2004) — información y expectativa musical
- Friston (2010), Friston & Stephan — free energy principle
- Grossberg, Smolensky — representaciones neuronales

*Bioelectricidad y biología molecular* (§5.5):
- Levin (2021) — bioelectricidad: ratios de conductancia iónica
- Celardo et al. (2023) — resonancia molecular en microtúbulos
- Scholes (2010) — coherencia cuántica en fotosíntesis

**Longitud estimada**: 5000-7000 palabras (el capítulo más largo — es la revisión de literatura) (ESCRITO: ~4400 palabras)

---

#### Capítulo 7. Epistemological and Methodological Framework
**Registro**: `[F]` + `[C]` + `[P]` (escala de F→P a lo largo del capítulo)
**Epígrafe**: *"Knowledge begins where translation becomes explicit."*

**Estructura**: 7 secciones, de posicionamiento epistemológico amplio → herramientas concretas. Este capítulo fundamenta qué tipo de conocimiento produce HIT, por qué considera autores de cualquier campo, y cómo organiza su evidencia. Universal a todo HIT (Phideus + Beacon + teoría), no solo a un escalón.

**§7.1 — What kind of knowledge HIT produces** `[F]+[C]` (~900-1100 palabras)
- HIT opera en la intersección de tres tradiciones: ciencia natural (medición, falsificación), investigación basada en práctica artística/terapéutica (saber corporal, efecto experiencial), y teoría crítica (reflexividad epistémica, análisis de poder, límites de la formalización)
- El método científico es UN sistema de saber entre muchos — potente para ciertas preguntas, estructuralmente limitado para otras
- **Las formas de la verdad (Nietzsche, *La gaya ciencia*, §§110 y 121)**: La ciencia opera con una verdad pragmática — si funciona, es verdadero. Nietzsche muestra que el conocimiento humano surgió como "errores conservadores de vida" (*life-preserving errors*): conceptos seleccionados por su utilidad para la supervivencia, no por su correspondencia transparente con lo real. La verdad pragmática/funcional es UNA forma de verdad, no LA verdad. HIT reconoce esta pluralidad sin escribirla como acceso directo a lo Real: la evidencia experiencial del Beacon, el saber corporal, la intuición estética y la convergencia formal son modos distintos de construir, articular e inscribir realidad bajo regímenes heterogéneos
- Los efectos terapéuticos que reportan participantes del Beacon constituyen material fenomenológico válido ANTES de que llegue la explicación científica formal. Ciencia que ignora esa evidencia porque no tiene mecanismo aprobado no es rigurosa — es incuriosa
- Esto NO es anti-ciencia: HIT se compromete plenamente con rigor científico en sus programas. Lo que rechaza es la pretensión totalizante de que solo existe lo que la ciencia ya explicó
- La investigación científica misma está guiada por intuiciones, deseos, pasiones, traumas y contingencias que el método no puede dar cuenta dentro de su propio marco
- **Por eso HIT considera autores de cualquier campo**: si toda forma de verdad es parcial, y si el lenguaje natural mismo tiene límites de interfaz enormes (ver §7.3), entonces ninguna disciplina tiene monopolio sobre la comprensión. La convergencia inter-disciplinaria es el único correctivo disponible ante la parcialidad de cada perspectiva
- **Reflexividad radical (Maturana)**: "todo lo dicho es dicho por un observador" — el conocimiento es inseparable del sistema biológico que lo produce. Maturana proporciona una versión biológica del argumento de Haraway: el observador no puede separarse de lo observado porque ES un sistema biológico acoplado al medio. Varela (1996) propone la neurophenomenology como puente metodológico: la experiencia de primera persona es dato, no artefacto
- **Refs**: Borgdorff (2012), Smith & Dean (2009), Haraway (1988), Harding (1991), Kindon et al. (2007), Dejours (1980/2000), Nietzsche (1882/1887), Maturana (1970/1980), Varela (1996), Maturana & Varela (1987)

**§7.2 — Science, power, and the limits of formalization** `[C]+[F]` (~600-800 palabras)
- Las instituciones científicas no son ventanas transparentes a la verdad — son estructuras sociales que producen, validan y circulan conocimiento dentro de relaciones de poder (Foucault)
- Peer review, prestigio de journals, métricas de citación, patrones de financiación, enforcement de fronteras disciplinarias: no son neutrales
- La propia dispersión descrita en Cap 2 es parcialmente producto de cómo las instituciones organizan el conocimiento
- El vocabulario de "vibración" y "armonía" está especialmente expuesto al policiamiento institucional por solaparse con new age (ver Cap 14)
- Conviene introducir un ejemplo concreto: en contextos de ML/neurociencia, términos como *harmony*, *resonance* o *vibration* pueden activar rechazo automático antes de que se evalúe su contenido formal. El problema no es solo conceptual, sino institucional y retórico
- Foucault: lo que cuenta como conocimiento está parcialmente determinado por quién tiene poder para definir los criterios. HIT reconoce esto sin disolverse en parálisis
- La cadena de externalización progresiva del saber (cuerpo→discurso→máquina→digital) de Fernández Méndez & San Emeterio muestra que toda formalización implica traducción, y toda traducción implica pérdida + creación. Cuando la experiencia Beacon se traduce a datos de bioseñal, se gana mensurabilidad y se pierde la cualidad irreductible de primera persona
- Desde ese marco, ningún concepto queda agotado por la disciplina que primero lo estabilizó. `Entropy` puede viajar más allá de su origen solo bajo reformulación explícita, preservando historia técnica y restringiendo el uso expandido
- **Refs**: Foucault (1980), Foucault (1978), Fernández Méndez & San Emeterio (2020), Lotman (2005), Nietzsche (1873)

**§7.3 — An epistemology of inconsistency** `[C]+[F]` (~700-900 palabras)
- Epistemología de la inconsistencia, de la falla, del agujero, del límite de los sistemas representacionales
- El `the Real` aparece como límite, resistencia, resto y failure of closure; no como objeto plenamente capturable por el símbolo
- Fórmula fuerte a fijar en la prosa: los modelos no acceden al `the Real` por éxito pleno, sino donde sus propios fines explicativos tropiezan con contradicción, resto o no-cierre
- 8 mil millones de personas actúan cada día movidos por fuerzas que no son científicas — deseo, hábito, estética, memoria corporal, herencia cultural. La ciencia describe una porción delgada. El resto no es por ello irreal
- Marco de automatismos corporales (5 tipos: corporal, diseñado, maquínico, organizacional, digital) — el conocimiento existe en múltiples registros simultáneamente. El cuerpo sabe cosas que el discurso no captura. El discurso sabe cosas que la formalización no captura
- Beacon ya produce efectos que los participantes reportan consistentemente. Estos reportes son evidencia experiencial válida dentro de un marco de investigación basada en práctica. HIT investiga el mecanismo sin negar el fenómeno
- **El límite de interfaz del lenguaje natural (Lacan, Seminario XI, Cap. XII: "La sexualidad en los desfiladeros del significante")**: El lenguaje natural no es solo técnicamente limitado — está estructuralmente atado a las lógicas del goce, la repetición, el deseo y las pasiones del cuerpo. El sujeto no habla desde una posición neutral sino que circula por los *desfiladeros del significante*, donde jouissance, pulsión y deseo configuran lo decible. TODO conocimiento expresado en lenguaje — incluido el científico — arrastra esta limitación constitutiva. Esto no es un defecto a corregir sino la condición misma bajo la cual la simbolización opera. La cadena significante no transmite información pura; transmite información marcada por el goce del cuerpo que la enuncia
- Consecuencia epistemológica: si el lenguaje natural tiene este límite de interfaz enorme, entonces HIT está justificada en considerar autores de cualquier campo y tradición, porque ningún discurso disciplinario escapa a esta condición. La formalización matemática reduce pero no elimina el problema (la elección de qué formalizar sigue siendo un acto de deseo y perspectiva)
- Tríada lacaniana (real/simbólico/imaginario) como observación estructural aplicable al propio conocimiento de HIT: siempre hay un resto que escapa la formalización (lo real), un sistema de representaciones (lo simbólico), y una dimensión imaginaria que motiva la investigación
- "Il n'y a pas de hors-texte" (Derrida), "no hay hechos, solo interpretaciones" (Nietzsche): no relativismo sino reconocimiento de los límites constitutivos de todo sistema representacional
- **El rechazo de la transmisión de información (Maturana)**: convergencia desde la biología. Maturana rechaza explícitamente la metáfora de Shannon aplicada a sistemas vivos: no hay "transmisión de información" entre organismos — solo perturbación y respuesta determinada por la estructura propia del receptor. Para Maturana, no hay input/output en sentido informacional. Lacan lo dice desde el lenguaje (la cadena significante no transmite información pura), Maturana lo dice desde la biología (el sistema nervioso no recibe información, es perturbado). Convergencia: dos campos radicalmente distintos coinciden en la insuficiencia del modelo de transmisión
- **Incompletitud de Gödel como caso concreto de la epistemología de la inconsistencia (Fernández Méndez, s.f.)**: El lenguaje digital nace de la imposibilidad de un sistema formal completo. Las "verdades por accidente" (Chaitin) — enunciados verdaderos pero indemostrables dentro del sistema — son condición de posibilidad del sistema mismo. Esto es exactamente lo que Lacan llama lo Real: lo que escapa la captura simbólica pero es condición de posibilidad de la simbolización. Fernández Méndez nota que para ser consistente, el sistema debe operar con recursividad, "algo relacionado con lo que en teoría de sistemas se conoce como clausura operacional". Convergencia triple: Gödel/Chaitin (matemática/computación), Lacan (psicoanálisis), Maturana/Varela (biología) — tres campos que coinciden en que todo sistema representacional es constitutivamente incompleto
- **Descorporalización como evidencia de límites del sistema representacional (San Emeterio & Fernández Méndez, 2017b)**: cuando el acto de trabajo corporal prescinde del cuerpo humano físico, el saber corporal se pierde en la traducción — ejemplo concreto de que el cuerpo sabe cosas que el discurso y la máquina no capturan
- Falta un párrafo puente hacia §7.4: si ningún discurso agota su objeto, HIT necesita instrumentos capaces de producir evidencia estructurada que no dependa solo de la autodescripción en lenguaje natural. Allí entran las redes neuronales como otro régimen de inscripción, no como salida fuera de la mediación
- **Refs**: Fernández Méndez (2021a, 2021b, s.f.), Fernández Méndez & San Emeterio (2015), San Emeterio & Fernández Méndez (2017a, 2017b), Dejours (1980/2000), Lacan (1964/1973) Seminario XI, Lacan (1966), Lacan (1972-73/1975) Seminario XX, Le Bretón (1992/2002, 1995), Derrida (1967), Nietzsche (1873), Maturana (1970/1980)

**§7.4 — Neural networks as scientific instruments: the atoms-bits-atoms bridge** `[C]+[P]` (~700-900 palabras)
- Phideus usa redes neuronales NO como targets de optimización sino como instrumentos de observación — análogos a espectrómetros, no a clasificadores
- Doble línea de Phideus: (a) NNs como campo de experimentación y exploración sin buscar mejorar métricas; (b) experimentar y desarrollar arquitecturas ML que contemplen ratios
- Puente átomos→bits→átomos: fenómenos físicos son digitalizados, procesados por modelos, y los resultados se interpretan como evidencia sobre el objeto científico tal como queda construido por esa cadena de transducción. Validez depende de: fidelidad de la cadena, convergencia de evidencia, tipo de claim
- Analogía del espectrómetro: los datos = la luz, la red = el prisma, los embeddings = el espectro, los descriptores = filtros. Cuando el filtro cambia el espectro de maneras controladas y replicables, eso es evidencia sobre la estructura de la luz, no sobre el prisma
- Jerarquía de claims: estructurales (más fuertes) → geométricos (moderados) → mecanísticos (más débiles). Phideus opera primariamente a nivel estructural
- Realismo estructural modesto: los invariantes que sobreviven cambios de instrumento, dominio y configuración ganan estatus epistémico como candidatos a la estructura del objeto científico construido por la investigación
- Fernández Méndez (s.f.) desarrolla la cadena analógico→digital como caso concreto de transducción: la señal continua se discretiza via umbrales, ganando operabilidad recursiva y perdiendo continuidad. Las señales que Phideus procesa atraviesan exactamente esta cadena
- **Refs**: Pearl (2009), Kornblith (CKA), Lakatos (1970), Popper (1959), Fernández Méndez (s.f.)

**§7.5 — The rectification: natural harmony and perceptual harmony** `[F]+[P]` (~500-700 palabras)
- La distinción metodológica central del programa experimental HIT: armonía natural (ratios lineales, serie armónica física) vs. armonía perceptual (log2, semitonos, temperamento igual)
- La rectificación se vuelve necesaria cuando efectos positivos de representación ya no alcanzan para decidir qué tipo de organización armónica quedó privilegiada. Una representación útil no es automáticamente una representación físicamente natural
- Natural harmony: ratios lineales, serie armónica física, organizaciones proporcionales que emergen del fenómeno o del medio
- Perceptual harmony: log2, semitonos, temperamento igual y otros codificados psicoacústicos/culturales
- En Phideus, la distinción aparece como comparación controlada entre distintas construcciones de un mismo fenómeno bajo condiciones computacionales comparables
- En Beacon, la distinción aparece primero como orientación del dispositivo, del sonido sintético, de los campos de interferencia y de la exploración Lissajous desde el lado de la armonía natural, sin requerir de entrada un contraste explícito con codificados perceptuales
- La regla metodológica: donde la comparación directa sea posible, debe explicitarse; donde todavía no lo sea, debe quedar explícita la orientación ontológica y metodológica del diseño
- **Refs**: Sethares (2005), Partch (1949), Pearl (2009)

**§7.6 — Beacon's methodological arsenal** `[P]+[C]` (~500-700 palabras)
- Beacon produce evidencia irreductible al marco computacional de Phideus. Arsenal:
  - **Métodos cualitativos**: entrevistas semiestructuradas, testimonios, relatos de sesión, entrevista no estructurada
  - **Bioseñales**: EEG (bandas, coherencia), ECG/HRV (coherencia cardíaca, tono vagal), conductividad de piel, respiración. Protocolos pre/post sesión
  - **Corazófono**: micrófono torácico que captura centro de resonancia propio del participante
  - **Cymatics como instrumento**: verificación visual de afinación armónica via patrones de interferencia (Chladni, Jenny) — no decoración sino protocolo de calibración
- Evidencia Beacon y evidencia Phideus son complementarias, no competidoras. La convergencia de ambas es más fuerte que cualquiera sola
- Cautela: N pequeño, protocolos en evolución, claims terapéuticos observacionales (no experimentalmente controlados todavía). Programa temprano, no terapia validada
- **Refs**: Porges (2011, 2017), Chladni (1787), Jenny (1967), Blood & Zatorre (2001), Borgdorff (2012), Kindon et al. (2007)

**§7.7 — The architecture of evidence** `[P]` (~500-700 palabras)
- Tres pilares: convergencia, controles, principio adversario
- **Convergencia**: ningún resultado aislado establece un claim. Multi-arquitectura, multi-seed, multi-métrica, multi-dominio. Lógica Galileo: múltiples telescopios, múltiples noches
- **Controles**: negativos, parameter-matched, adversariales o contra-condiciones fuertes según la rama experimental. El control informativo no es un placeholder neutral, sino la mejor alternativa cercana al claim
- **Principio adversario**: los controles no son línea base neutral — son la mejor hipótesis alternativa. Si el adversario gana, la tesis se debilita
- **Pre-registro**: predicciones comprometidas antes de resultados. Matrices de patrón con interpretaciones explícitas
- **Multi-seed**: 5+ seeds antes de que un resultado entre en la base de evidencia
- **Jerarquía de claim** (operativa): qué puede afirmar el programa a cada nivel de evidencia
- Conviene mantener anclaje empírico ligero en la prosa de esta sección, pero sin convertirla en scoreboard de resultados. Los datos duros deben desarrollarse más adelante, no colonizar el capítulo epistemológico
- **Refs**: Pearl (2009), Popper (1959), Lakatos (1970)

**Herramientas analíticas** (transversales a §§7.4-7.7):
- RQA (Recurrence Quantification Analysis): la consonancia correlaciona con perfil de recurrencia
- Mutual information entre señales multimodales
- Cross-frequency coupling como evidencia de integración
- Descriptores topológicos de patrones nodales y barridos racional vs. irracional en campos de interferencia controlados
- Protocolos de *impulse-response probing* para distinguir aporte del medio, de la excitación y de su interacción
- Sensibilidad local/global por armónico en espacios de fase y ganancia
- Contrastive learning (VICReg, InfoNCE) para testear correspondencia cross-modal
- Retrieval como métrica de transferencia
- Bootstrap pareado con agrupamiento por sujeto (protocolo Phideus)

**Bibliografía pertinente**:

*Nuevas — epistemología crítica y metodológica (§§7.1-7.3)*:
- Nietzsche (1882/1887) *La gaya ciencia* — formas de la verdad, errores conservadores de vida
- Lacan (1964/1973) Seminario XI §7.3 — desfiladeros del significante, jouissance y límites del lenguaje
- Lacan (1972-73/1975) Seminario XX (*Encore*) §7.3 — lalangue, jouissance y cuerpo
- Foucault (1980) *Power/Knowledge* §7.2 — saber/poder, producción institucional del conocimiento
- Foucault (1978/1990) *History of Sexuality* §7.2 — dispositivos de poder
- Haraway (1988) *Situated Knowledges* §7.1 — parcialidad epistémica como virtud
- Harding (1991) *Whose Science?* §7.1 — standpoint theory
- Borgdorff (2012) *Conflict of the Faculties* §7.1 — investigación basada en práctica artística
- Smith & Dean (2009) *Practice-led Research* §7.1 — práctica como método de investigación
- Kindon et al. (2007) *Participatory Action Research* §7.1 — conocimiento experiencial junto a indagación sistemática
- Dejours (1980/2000) *Travail, usure mentale* §7.1 — brecha trabajo prescrito/real, saber del cuerpo
- Le Bretón (1992/2002) *Sociologie du corps* §7.3 — sociología del cuerpo
- Fernández Méndez & San Emeterio (2020) §7.2 — cadena de externalización: cuerpo→discurso→máquina→digital
- Fernández Méndez (2013) §7.3 — automatismos corporales (5 tipos)
- Maturana (1970/1980) §7.1/§7.3 — "todo lo dicho es dicho por un observador": reflexividad radical. Rechazo de transmisión de información Shannon en sistemas vivos
- Varela (1996) §7.1 — neurophenomenology: experiencia de primera persona como dato, no artefacto
- Maturana & Varela (1987) §7.1 — *The Tree of Knowledge*: biología de la cognición para público amplio
- Maturana (1988) §7.1 — objetividad entre paréntesis: el observador no puede separarse de lo observado

*Existentes — herramientas analíticas y rectificación epistemológica (§§7.4-7.7)*:
- Trulla et al. (2018) §1.4 — RQA como herramienta de análisis de recurrencia
- Marwan et al. (2007) §1.4 — manual de referencia para RQA
- Pearl (2009) §6.2 — inferencia causal: controles negativos, diseño experimental
- Sethares (2005) §3.2 — tuning y timbre: armonía natural vs. temperada
- Partch (1949) §3.2 — entonación justa: marco de referencia
- Berry & Dennis (2001) §1.4 — singularidades de fase y topología de interferencia
- D'Angelo & Laracca (2018) §6.5 — features geométricos sobre figuras de Lissajous
- Pinasco & Scarola (2021) §6.5 — problema inverso nodal
- Maynard et al. (1985) §6.5 — medición de campos y límites del pasaje patrón → reconstrucción
- Bardes et al. (VICReg) §6.1 — contrastive learning: loss function Phideus
- Zbontar et al. (Barlow Twins) §6.1 — loss contrastiva alternativa
- Kornblith et al. (CKA) §6.2 — métrica de similitud representacional
- Lakatos (1970) §7.2 — programa de investigación como marco
- McDermott et al. (2016) §3.5 — constraint: universalidad requiere evidencia cross-cultural
- Echaniz (NaturalHarmony HackMD) §7.4 — ratios lineales, nunca log2

*Fuentes no bibliográficas*:
- Documentación Phideus (protocolos, preregistro, bootstrap pareado, taxonomía A/B/C/D)

**Longitud estimada**: 4500-6200 palabras

---

### PARTE IV — LA TEORÍA: EFICIENCIA, VIDA, SENTIDO
*Función: El corazón teórico. Conectar lo físico con lo biológico y lo experiencial.*
*Extractabilidad: → Paper teórico, → Manifiesto (centro), → Divulgación*

---

#### Capítulo 8. Armonía natural como eficiencia informacional
**Registro**: `[F]` + `[C]`
**Epígrafe**: *"Recurrence conserves intelligibility."*

**Contenido**:
- **Argumento central**: ratios armónicos simples → alta recurrencia → pocas correcciones disipatorias → bajo costo energético → eficiencia informacional
- **Cadena formal**:
  1. Ratios simples maximizan recurrencia (RQA empírico)
  2. Alta recurrencia → minimiza costo de procesamiento (Landauer: borrar info cuesta kT ln 2)
  3. Minimizar costo de procesamiento → minimiza costo de inferencia/predicción (VFE, Friston)
  4. Por lo tanto: la armonía natural es un atractor de eficiencia
- **Aclaración terminológica obligatoria**: distinguir explícitamente entre reducción de incertidumbre (Shannon), entropía termodinámica y uso expandido/transdisciplinario de `entropy`. Relacionados, sí; intercambiables, no
- **Formalización mínima esperada en este capítulo**:
  - ecuación de Kuramoto: `dθ_i/dt = ω_i + (K/N) Σ_j sin(θ_j - θ_i)`
  - matriz de recurrencia: `R_ij = Θ(ε - ||x_i - x_j||)`
  - una métrica RQA solo si cumple función argumental clara (`RR`, `DET` o equivalente)
- **Lectura autopoiética de la cadena de eficiencia** (Maturana & Varela → Di Paolo → Friston):
  - Un sistema autónomo precario (Di Paolo, 2005) necesita mantener su organización con mínimo gasto. Ratios simples minimizan la "sorpresa" (Friston) = minimizan la desviación de la organización = mantienen la autopoiesis
  - La firma "armonía natural = estabilidad recurrente = eficiencia" se lee autopoiéticamente como: "los ratios simples son los que mejor sostienen la organización del sistema"
  - **Cautela**: esta lectura es interpretativa, no formal. La autopoiesis no tiene (todavía) una métrica de eficiencia comparable a RQA o VFE. El puente es programático, no demostrado
- **Biosemiosfera**: la recurrencia de ratios como sistema de compresión entre niveles biosemióticos
  - Fundamento físico de la repetición: permite interpretar y almacenar información sobre restricciones (Lo Real) con menor costo
- **Ecología**: Krause y el nicho acústico
  - La biofonía particiona espacio espectral/temporal
  - Minimiza interferencia + maximiza eficiencia energética
  - = disminuir entropía sin llegar a cero
- **La firma**: armonía natural = estabilidad recurrente = eficiencia informacional

**Bibliografía pertinente**:

*Primarias* (la cadena formal: ratios → recurrencia → eficiencia):
- Landauer (1961) §4.2 — costo energético mínimo de borrar información (kT ln 2)
- Still et al. (2012) §4.2 — termodinámica de predicción: patrones predecibles = más eficientes
- Trulla et al. (2018) §1.4 — RQA: ratios simples maximizan recurrencia
- Friston (2010) §2.4 — free energy principle: minimizar correcciones = eficiencia
- Kuramoto (1984) §1.4 — basins de atracción: ancho ~ K^(p+q−1) para ratio p:q
- Canolty & Knight (2010) §1.1 — CFC: eficiencia de integración via ratios
- Jacobs et al. (2025) §1.1 — ondas locales rivalizan con atención global: eficiencia computacional
- Krause (2013) §1.3 — nicho acústico como eficiencia informacional ecológica

*Secundarias* (contexto termodinámico + evidencia molecular):
- Bennett (1982) §4.2 — termodinámica de la computación
- Parrondo et al. §4.2 — límites termodinámicos generales
- Celardo et al. (2023) §5.5 — resonancia molecular: transferencia de energía en microtúbulos
- Scholes (2010) §5.5 — coherencia cuántica en fotosíntesis: eficiencia a escala fundamental
- Hermoso de Mendoza et al. (2016) §1.4 — Kuramoto cuántico: eficiencia robusta cross-régimen
- Cartwright et al. (2001) §4.1 — pitch como mode-locking en osciladores no lineales
- McCauley §4.1 — estabilidad dinámica
- Orsucci et al. §4.1 — recurrencia en sistemas complejos
- Trulla et al. (2005) §4.1 — RQA temprano
- Webber & Zbilut §4.1 — RQA: cuantificación de recurrencia aplicada
- Mandelbrot §4.3 — fractales y auto-organización
- Taylor et al. (1999, 2011) §4.3 — patrones fractales en estética
- Gallozzi & Strollo (2023) §1.4 — simplicidad → recurrencia: Lissajous como evidencia visual

*Recursividad y economía constructiva* (§8 — convergencia con lenguaje digital):
- Fernández Méndez (s.f.) §8.1 — recursividad como principio de eficiencia: "un sistema cuyo potencial está basado en la recursividad de unos pocos elementos sobre sí mismos". Pocas operaciones booleanas → todo el lenguaje digital. Pocos ratios simples → toda la organización armónica. Convergencia: economía recursiva como patrón transversal

*Autopoiesis y precariedad* (§8 — lectura autopoiética de la eficiencia):
- Maturana & Varela (1973/1980) §2.2 — organización como patrón invariante que la eficiencia sostiene
- Di Paolo (2005) §5.5 — precariedad: sistema autónomo precario necesita mantener organización con mínimo gasto

*Fuentes no bibliográficas*:
- Echaniz HackMD §7.4 ("armonía como compresión de información", "sistema de coordenadas natural")

**Longitud estimada**: 3000-4000 palabras

---

#### Capítulo 9. El sentido de la consonancia
**Registro**: `[C]` + `[F]`
**Epígrafe**: *"Homeostasis espiritual"*

**Contenido**:
- **Del argumento físico al biológico**: si los patrones más simples/coherentes son más eficientes, entonces tender a ellos es tender a la homeostasis
- **El sentido de la consonancia como sentido biológico**: no metáfora, sino función — el sistema detecta y prefiere estados de mayor coherencia armónica
  - "Cuando una persona va a la naturaleza, baja 8000 cambios — se le están acomodando los simáticos"
  - El Beacon como referencia armónica: "como un bosquecito portátil"
- **La inarmonía como distanciamiento**: la ciudad, el ruido, los dispositivos no-armónicos como fuentes de desajuste
- **La homeostasis espiritual**: capacidad recurrente de recuperar y sostener patrones de resonancia, orientación y coherencia a través de niveles biológicos, afectivos, simbólicos y ecológicos
  - No nombra equilibrio final sino orden vivible recuperado por reorganización
  - La consonancia importa no solo como relación acústica o alivio regulatorio, sino como operador de reorientación entre registros acoplados de experiencia
  - Se formula como hipótesis fuerte de trabajo dentro del capítulo, no como adorno terminológico
- **La pareidolia armónica**: el cerebro busca estructura en sonidos complejos, encuentra sentido en la armonía natural
  - Conexión con predictive coding: el cerebro minimiza sorpresa, la armonía natural es lo menos sorprendente
- **Polifonía humana**: "los humanos somos polifónicos — todo el tiempo emitimos acordes, y el acorde codifica la emoción"
- **Actualización empírica puntual**: Kawai y Zheng como anclajes recientes de que la orientación del sistema cambia con la calidad de la relación oscilatoria que puede sostener
- **§9.Y La consonancia como acoplamiento estructural** — subsección nueva (~400-600 palabras):
  - El "sentido de la consonancia" reformulado autopoiéticamente: el sistema biológico detecta y prefiere estados de acoplamiento exitoso con su entorno
  - Maturana: los sistemas vivos no reciben información del entorno — son perturbados por él, y su respuesta depende de su propia estructura. El Beacon no "transmite" armonía al sujeto: perturba al sistema, que responde según su propia organización. "Cada cuerpo tiene SU armonía" (§11 existente) = cada sistema tiene su propia estructura de acoplamiento
  - Enactivismo (Varela, Thompson & Rosch, 1991): cognición = acción efectiva, no representación. El "sentido de la consonancia" no es representación interna de un ratio externo — es el sistema actuando coherentemente en relación al medio
  - Precariedad (Di Paolo, 2005): la consonancia importa PORQUE el sistema es precario — su organización puede desintegrarse. La inarmonía (§9: "la ciudad, el ruido") es amenaza a la organización, no solo incomodidad. El "sentido de la consonancia" es detección de compatibilidad entre la organización del sistema y las perturbaciones del entorno
  - Ensambles resonantes de Varela (2001) como mecanismo neurofisiológico: el cerebro integra via sincronización de fase = es un sistema cuya organización depende de ratios de frecuencia. Si la coherencia armónica del campo perceptual (Beacon) facilita la formación de ensambles resonantes, entonces el Beacon facilita la integración neural. **Esto es hipótesis, no claim**
  - **Cautela**: no estamos afirmando que el Beacon es autopoiético ni que el organismo "necesita" armonía para sobrevivir. Lo que proponemos es que el marco de acoplamiento estructural ofrece un vocabulario biológico más preciso que "sentido" o "preferencia" para describir la relación sistema-campo armónico
- **§9.X La consonancia como orientación psíquica** — subsección nueva (~500-700 palabras):
  - La consonancia opera no solo como sensación neurofisiológica sino como orientación psíquica. La psicología analítica (Jung) ofrece un marco: el Self jungiano como homólogo de la "referencia armónica" introducida en Cap 3
  - Self = "factor interno de orientación, muy diferente de la personalidad consciente" (Von Franz, 1964). Centro de la psique, simultáneamente interior y exterior. No es ego ni inconsciente — es el principio relacional que integra ambos
  - Función trascendente (Jung, 1916/1958): mecanismo que trae material del inconsciente a la consciencia, creando una "tercera posición" que trasciende los opuestos. Propuesta HIT: la armonía natural funciona análogamente como referencia que orienta hacia coherencia
  - El monomito del héroe (Campbell, 1949) como mapa estructural de transformación psíquica: descenso, confrontación, retorno — la misma lógica de pérdida y recuperación de equilibrio que el Beacon materializa acústicamente
  - **Cautela fuerte**: analogía programática, no probada. Hipótesis de trabajo, no claim. Marco interpretativo para la práctica Beacon (Cap 12), no identificación ontológica. No estamos afirmando que el Self "es" la referencia armónica — sino que ambos nombran funciones de orientación en registros distintos
  - Conexión con §7.3 (epistemología de la inconsistencia): el Self es lo que escapa la formalización pero produce efectos observables — exactamente el tipo de objeto que la metodología de HIT necesita aprender a investigar

**Bibliografía pertinente**:

*Primarias* (del argumento físico al biológico):
- Blood & Zatorre (2001) §5.1 — núcleo accumbens activo ante música: mismas vías que comida/sexo
- Ferreri et al. (2019) §5.1 — dopamina necesaria para placer musical (manipulación farmacológica)
- Porges (2011, 2017) §5.4 — teoría polivagal: regulación autonómica via nervio vago
- Levin (2021) §5.5 — bioelectricidad: comportamiento depende de RATIOS de conductancia iónica
- Friston (2010) §2.4 — predictive coding: armonía natural = menor sorpresa
- Glass & Mackey (1988) §1.4 — osciladores biológicos: ratio 4:1 respiratorio-cardíaco
- Acebrón et al. (2005) §1.4 — chimera states: parcialidad armónica como régimen estable
- Kawai (2023) §1.1 — acoplamientos armónicos lentos como anclaje fisiológico de la orientación
- Zheng et al. (2025) §1.1 — relaciones alfa-theta y estabilidad atencional como caso de consonancia funcional

*Secundarias* (autopoiesis y enactivismo — §9.Y):
- Maturana & Varela (1973/1980) §2.2 — autopoiesis: acoplamiento estructural como marco del sentido biológico
- Varela, Thompson & Rosch (1991) §5.3 — enactivismo: cognición = acción efectiva, no representación. El sentido de la consonancia como acoplamiento, no como percepción pasiva
- Di Paolo (2005) §5.5 — precariedad: la consonancia importa porque la organización puede desintegrarse
- Varela et al. (2001) §1.1 — ensambles resonantes: sincronización de fase como mecanismo neurofisiológico del sentido
- Thompson (2007) §5.3 — Mind in Life: continuidad entre vida y mente via autonomía biológica
- Weber & Varela (2002) §5.3 — fines naturales y autopoiesis: individuación biológica como precedente del sentido

*Secundarias* (automatismos, descorporalización, acoplamiento corporal — §9.3, §9.4, §9.5):
- San Emeterio & Fernández Méndez (2017b) §9.3 — descorporalización del acto de trabajo corporal como forma de estrangement/inarmonía estructural: pérdida de acoplamiento entre sujeto y base corporal del saber
- San Emeterio & Fernández Méndez (2017d) §9.3 — el acto de trabajo corporal sin cuerpo: formulación paradojal de la descorporalización
- Fernández Méndez (2021a) §9.4 — malabarismo como acto polirrítmico corporal construido via automatismos: ejemplo concreto de polifonía humana como acto corporal, no solo vocal
- Fernández Méndez (2021b) §9.5 — relación piloto↔todoterreno como caso de acoplamiento estructural: "la identificación subjetiva de todo un automóvil con la propia corporalidad y su incorporación en el registro imaginario-simbólico del cuerpo"

*Secundarias* (psicología analítica — §9.X):
- Jung (1916/1958) CW 8 §5.3 — función trascendente: síntesis de consciente e inconsciente como "tercera posición"
- Jung (1959) CW 9/1 §5.3 — Self como centro organizador de la psique
- Von Franz (1964) §5.3 — individuación: factor de orientación no-consciente
- Campbell (1949) §5.3 — monomito: estructura narrativa de transformación psíquica

*Secundarias* (neurociencia, terapia, entrainment, regulación):
- Panksepp & Bernatzky (2002) §5.1 — emociones primordiales y música
- Koelsch (2014) §5.1 — cerebro y música: procesamiento emocional
- Chanda & Levitin (2013) §5.1 — neuroquímica de la música
- Lacan (1966) §5.3 — sujeto, voz y alteridad como registro posible de la consonancia
- Rebecchini §5.2 — musicoterapia: revisión de evidencia
- de Witte et al. §5.2 — efectos restaurativos de la música
- Thoma et al. §5.2 — música y reducción de estrés (cortisol)
- Bradt et al. (2021) §5.2 — intervenciones musicales en cáncer
- Storr §5.3 — música y mente
- Maxfield §5.3 — tambores chamánicos y estados de conciencia
- Winkelman §5.3 — entrainment y estados alterados
- Koelsch et al. (2011) §5.4 — procesamiento emocional en amígdala
- Mojtabavi et al. §5.4 — estimulación del nervio vago
- Pietak & Levin §5.5 — oscilaciones multicelulares: morfogénesis
- Buxton et al. (2021) §1.3 — beneficios de sonidos naturales
- Schwartz et al. (2003) §1.2 — estadística del habla: ecología acústica
- Large & Almonte (2012) §1.1 — resonancia neural como base tonal
- Nees & Phillips §3.5 — pareidolia auditiva
- Nikolsky §3.5 — escalas prehistóricas y percepción

**Longitud estimada**: 3000-4000 palabras

---

#### Capítulo 10. The Activation Problem
**Registro**: `[F]` + `[C]`
**Epígrafe**: *"A system does not only store. It must be asked."*

**Arco narrativo**: Culminación del arco teórico de la Parte IV. Cap 8 estableció la eficiencia de almacenamiento via recurrencia de ratios enteros. Cap 9 estableció el sentido biológico de la consonancia. Cap 10 aborda la pieza faltante: el mecanismo de lectura (retrieval). φ entra como candidato para un subproblema específico (retrieval no destructivo), NO como nuevo centro de gravedad del programa.

**Contenido**:
- **§10.1 The problem of reading without writing** `[F]` (~500 palabras): Distinción storage vs retrieval. Analogía campana/impulso. Green's function como mecanismo de lectura. El activation problem: ¿qué tipo de perturbación puede leer la topología de un sistema sin sobreescribirla?
- **§10.2 The mathematical character of φ** `[F]+[C]` (~600 palabras): φ como el número irracional más difícil de aproximar por racionales (Hurwitz). Expansión en fracciones continuas [1;1,1,...]. Consecuencia física: máxima no-resonancia con la estructura almacenada en ratios enteros. Complemento formal de Cap 8: almacenamiento = recurrencia, lectura = incompatibilidad productiva.
- **§10.3 Three convergent lines** `[F]+[C]` (~700 palabras): SOLO 3 líneas en el cuerpo:
  1. *Diophantine extremality* — φ como el irracional más resistente a aproximación racional (Hurwitz, Sós)
  2. *KAM theory* — el último toro estable bajo perturbación es el golden-mean torus; φ-spacing maximiza estabilidad
  3. *MRI golden angle* — el ángulo áureo ya es estándar en muestreo radial de k-space, confirmación práctica directa
  Las otras 3 líneas (Weyl/equidistribución, almost Mathieu, Penrose QEC) + todo el formalismo van a Appendix E.
- **§10.4 The Jpsh! as a formal event** `[C]` (~300 palabras): Comprimido a ~1 párrafo. En la práctica de rope flow (atribuido a Nicolás Echániz), hay un momento preciso — el *Jpsh!*, onomatopeya del sonido del látigo al alcanzar su estado de phase-lock — en que un impulso mínimo y coordinado especifica la configuración de fase completa del sistema. El sistema resuelve en el patrón implícito en sus propiedades físicas. Es una instancia del mecanismo Green's function: el impulso provee energía; el medio provee información. Paralelo breve con reservoir computing y redes de Hopfield: inferencia = excitación, almacenamiento = estructura.
- **§10.5 What this changes and what it does not** `[C]+[F]` (~500 palabras): Tres proposiciones. (1) La organización armónica sirve a dos funciones informacionales formalmente distintas: storage (recurrencia, ratios enteros) y retrieval (no-resonancia, φ). (2) La distinción storage/retrieval puede mapear a dos modos fenomenológicamente distintos de experiencia armónica: consonancia (estabilidad recuperada) vs activación (transparencia momentánea de la estructura). (3) φ NO redefine HIT — resuelve un subproblema específico dentro del programa existente.
  **Directiva de modulación**: este capítulo completa el arco Ch8-9, no lo reemplaza. φ es candidato para retrieval, no centro gravitacional nuevo.
- **§10.6 Status and open directions** `[F]+[P]` (~400 palabras): Status de conjetura estructural: bien fundamentada, convergente con evidencia independiente, suficientemente precisa para generar predicciones, no cerrada formalmente. El Harmonic Activation Lemma (enunciado formal completo en Appendix E) es un problema abierto. Las consecuencias experimentales para Phideus y Beacon se desarrollan en Cap 11 y Cap 12 respectivamente — aquí solo se anuncia la promesa general sin elaborarla.

**Directivas editoriales**:
- φ entra como candidato para el problema de retrieval, NO como nuevo centro de gravedad de HIT
- El capítulo NO desarrolla consecuencias experimentales específicas para Phideus ni Beacon — cierra con una promesa general; Cap 11 y Cap 12 las recogen en sus propios registros
- Solo 3 líneas convergentes en el cuerpo; las otras 3 + todo el formalismo van a Appendix E
- Takalo/Riemann, Venkatesh/Gauss, sociología del conocimiento NO entran en el cuerpo del capítulo
- Jpsh! se mantiene comprimido (~1 párrafo), con contexto de origen (rope flow, Nicolás) y encuadre como onomatopeya de un evento físico preciso (Green's function / impulse)
- La voz narrativa debe ser la del resto del libro: argumentativa, con ecuaciones puntuales, sin cambiar de género a paper de matemática

**Bibliografía pertinente**:

*Primarias*:
- Hurwitz (1891) — Diophantine approximation, extremalidad de φ
- Weyl (1916) — equidistribución de secuencias irracionales
- Sós (1958) — three-distance theorem, cobertura óptima de φ
- Avila & Jitomirskaya (2009) — Ten Martini Problem, operador almost Mathieu

*Secundarias*:
- Pletzer et al. (2010) — bandas EEG en ratio φ, arquitectura de reposo
- Li & Boyle (2023) — Penrose tilings como códigos correctores cuánticos
- Spurrier & Cooper (2018) — holonomía espiral en cuasicristales ópticos

**Longitud estimada**: 3000 palabras

**ESCRITO**: pendiente (Codex)

---

### PARTE V — EL PROGRAMA EXPERIMENTAL
*Función: Mostrar qué hacemos y qué hemos encontrado.*
*Extractabilidad: → Paper Phideus, → Propuesta Beacon, → Grants*

**Umbral de Parte V (sin numeración, antes de Cap. 11)**:
- breve bloque de 2 párrafos (~170-240 palabras) como texto propio de la parte, no del capítulo;
- función: aclarar que `Phideus` y `Beacon` son los probes que ya venían tomando forma por razones heterogéneas y a través de los cuales HIT se fue volviendo necesaria;
- dejar explícito que no se presentan como brazos privilegiados ni exhaustivos de HIT;
- formular que muchas convergencias citadas antes pueden leerse como brazos experimentales que rozan el mismo objeto, y que el espacio de probes posibles bajo una hermenéutica HIT no tiene cierre evidente;
- tono: afirmativo, sobrio, no defensivo, sin roadmap editorial ni lenguaje del campo `disciplina/disciplinado`.

---

#### Capítulo 11. Phideus: la sonda computacional
**Registro**: `[P]` + `[C]`
**Epígrafe**: *"The only way to test whether ratios organize information is to build something that tries to speak their language."*

**Arco narrativo**: Relato de cómo se diseñó y ejecutó el programa experimental computacional de HIT. Hilo de Ariadna cronológico, presentado como diseño deliberado. Focalizado en las mejores métricas y evidencia más fuerte.

**Estructura de secciones (9 secciones)**:

**§11.1 — The Question and Why It Needed a Machine** (800–1000 palabras)
`[C]` + `[P]`
- Situación epistemológica al final del arco teórico (Caps 8-9-10): la eficiencia del almacenamiento, el sentido biológico de la consonancia, y el mecanismo de activación/lectura están conceptualmente articulados — la teoría necesita ahora un instrumento
- Phideus como instrumento, no como ontología (NNs como espectroscopios, conecta con Cap 7)
- **Primera introducción del concepto "descriptor"**: resumen numérico compacto de una organización relacional candidata; en los casos fuertes, ratio-based o armónica, y en otros casos explícitamente no-ratio como control.
- **Capa operacional literal**:
  - el programa empieza con datasets pareados: dos dominios del mismo evento, alineados por segmento, ventana o unidad de análisis;
  - desde ahí se construye una arquitectura dual con un encoder por modalidad y projection heads hacia un espacio compartido;
  - se computa un descriptor por modalidad y se lo inyecta por una ruta explícita;
  - primero se entrena un baseline unguided y recién después se comparan los arms descriptor-guided contra ese baseline.
- **Incluir ecuaciones paraguas mínimas**:
  - `z_a = P_a(E_a(x_a), d_a)`, `z_b = P_b(E_b(x_b), d_b)`
  - `L = L_VICReg(z_a, z_b)`
- Qué contaría como evidencia: retrieval, geometría, causalidad, mecanismo

**§11.2 — Experimental Design: Four Escalones, One Logic** (1200–1500 palabras)
`[P]`
- Definir `escalon` como experimental front / staged level del mismo programa.
- Escalón 1: Audio ↔ MIDI. MAESTRO v3 (200h piano). Audio → MERT (330M params); MIDI → Transformer. Espacio compartido 256d. VICReg.
- Escalón 2: Speech ↔ EGG. French Lombard v1.1, 38 hablantes. Diferente física de sensor. Primera pasada deliberadamente trazable antes de fundation encoders más fuertes.
- Escalón 3: Audio XY ↔ figuras de Lissajous. Frente planificado, con ground truth paramétrico y convergencia experimental con Beacon.
- Escalón 4: ECG ↔ PPG. Frente planificado fuera de acústica.
- Métrica S = min(A→B, B→A), 500 queries. Pool=256 en Escalón 1 y 128 en Escalón 2. Conservadora por diseño.
- **[TABLA 11.1]**: Frentes experimentales (4 escalones: E1 cerrado, E2 en curso, E3-E4 planificados)
- **[FIGURA 11.1]**: Diagrama de arquitectura dual encoder + descriptor injection + VICReg

**§11.3 — What Counts as a Descriptor in Phideus** (800–1000 palabras)
`[P]` + `[C]` — Vocabulario conceptual, genealogía e inventario operativo.

**Movimiento 1: Descriptor, mechanism, arm** (~200 palabras)
- Descriptor: estructura informacional inyectada (qué el modelo debe atender).
- Mecanismo: ruta arquitectónica de inyección (cómo entra el descriptor).
- Arm: combinación concreta de descriptor + mecanismo + receta de training.
- Aclarar desde el inicio: no todo descriptor del programa es ratio puro; algunos testean hipótesis armónicas primarias y otros son controles no-ratio.
- Ejemplos de lo que NO es un descriptor nuevo:
  A4r = A4 + reverse cross-attention (cambio de mecanismo).
  pcd = projection conditioning sobre d4+a4 (cambio de mecanismo).
  d4a4 = arm que combina D4 + A4 (combinación, no descriptor nuevo).

**Movimiento 2: Genealogía de representaciones** (~200 palabras)
- Antes de la era descriptor-guided, el programa exploró representaciones
  más densas: histogramas de distribuciones de ratios, tokens sparse
  inspirados en fingerprinting acústico, y matching exacto por voting.
- Lección conceptual: representaciones densas con estructura temporal
  capturan organización discriminativa; esparsificación y matching exacto
  la destruyen. Transición a embeddings aprendidos con descriptores compactos.
- Tono: genealogía metodológica, no changelog. Sin tensor shapes.
  Sin detalles de arquitectura VAE/HRM.
- Fuentes: INFORME_HISTORICO, CATALOGO_NARRATIVO (docs transversales).

**Movimiento 3: Descriptores operativos de Escalón 1** (~400 palabras)
- Escalón 1 operó con descriptores pragmáticos:
  - D4 (4d): intervalos MIDI locales — estructura simbólica relacional.
  - A4 (8d): dinámica espectral en octave bands — riqueza espectral, NO ratio.
- **Incluir fórmula mínima de D4**:
  - prev/next semitone interval + prev/next octave-normalized log-ratio.
- **Incluir fórmula mínima de A4**:
  - log-magnitude por banda de octava + delta temporal entre frames.
- El arm más fuerte (d4a4, un descriptor por modalidad) produjo la
  evidencia central del programa, desarrollada en §11.5.
- Lo que Escalón 1 validó: la mecánica descriptor-guided funciona,
  los descriptores reorganizan geometría cross-modal.
- Lo que Escalón 1 NO resolvió: si la ventaja es de ratios armónicos naturales
  o de riqueza espectral genérica. A4 es rico pero no ratio-based.
  D4 codifica intervalos en semitonos (perceptual, no natural).
- Los números estrella se reservan para §11.5 (sección flagship).
- Remisión explícita: `Table 11.2` como mapa compacto; `Appendix C` + paper metodológico + repositorio público como capa exhaustiva.

**[TABLA 11.2]**: Inventario de descriptores del programa

Solo descriptores reales. Arms y mecanismos NO entran en esta tabla.

| Front | Descriptor | Dim | Domain | Encodes | HIT hypothesis |
|-------|-----------|-----|--------|---------|----------------|
| Escalón 1 | D4 | 4 | MIDI | Local intervals | Symbolic structure |
| Escalón 1 | A4 | 8 | Audio | Spectral dynamics | Control (non-ratio) |
| Gate 9 | A7 | 12 | Audio | JI spectral ratios | Natural harmony (retrospective) |
| Gate 9 | A9 | 12 | Audio | JI variant | Natural harmony (retrospective) |
| Gate 9/A10 | A10a-e | 6–32 | Audio | Recurrence ratios | Ontology-free / continuous |
| Escalón 2 | V4-lin | var | Speech | Linear F0 ratios | Natural harmony (primary) |
| Escalón 2 | V4-log | var | Speech | Log2 F0 ratios | Perceptual comparison |
| Escalón 2 | H-series | 12 | Speech | Harmonic amplitudes | Series structure (primary) |
| Escalón 2 | A4-16k | 8 | Speech | Spectral dynamics | Control (non-ratio) |

Nota al pie: arms canónicos (d4a4, a4r, d4-a4r) y mecanismos (concat,
cross-att, attn_bias, rev-xattn, FiLM/pcd) se tratan en §11.4.
Inventario técnico exhaustivo en Appendix C.

**§11.4 — How Descriptors Enter the Model: Mechanism as Variable** (600–800 palabras)
`[P]`
- 5 mecanismos: concat, cross-att, attn_bias, reverse cross-att, FiLM/projection conditioning
- **Incluir fórmulas mínimas de mecanismo**:
  - concat: `h_tilde = [h; d]`
  - attention: `Attn(Q,K,V) = softmax(QK^T / sqrt(d_k)) V`
  - FiLM: `h' = (1 + gamma(d)) * h + beta(d)`
- Aclarar configuración:
  - cross-att: `Q=h`, `K=d`, `V=d`
  - reverse cross-att: `Q=d`, `K=h`, `V=h`
  - attention bias: modifica logits internos, no crea descriptor nuevo.
- Hallazgo: atención >> concatenación consistentemente
- Reverse cross-att: Q=descriptor(188), K/V=features(2400). 163x más barato.
- FiLM (Gate 8): descriptor modula projection head. Señal sobrevive al final del pipeline.
- Frase disciplinaria: route != descriptor.
- **[FIGURA 11.2]**: Esquema de 3 mecanismos de inyección (concat, cross-att, FiLM)

**§11.5 — The Central Result: Descriptor-Guided Cross-Modal Learning Works** (1500–2000 palabras)
`[P]` — Sección estrella. Métricas más fuertes, evidencia convergente.
- Leer esta sección contra el pipeline explícito de §11.1–§11.4: baseline, descriptor, mechanism, projection.
- Lead: d4a4 = 84.1% ± 2.3pp (5 seeds), Cohen d = 4.50 vs D0 = 75.2%. Zero overlap.
- Causal: (1) Inference zero → 7.8% (-76pp); (2) Param-matched → +9.4pp gap; (3) Pre-registro.
- Geométrica: CKA +82%, pero más alineación ≠ mejor retrieval.
- Mecanística: Gate 8 pcd=84.2% (record). Señal sobrevive en projection head.
- Hard negatives: >94%. Identidad temporal fina.
- **[TABLA 11.3]**: Resumen de Evidencia Escalón 1 (tabla flagship, 7 dimensiones)
- **[TABLA 11.4]**: Replicación Multi-Seed (4 arms × 7 columnas)
- **[TABLA 11.5 opcional]**: Gate 8 conditioned projection ranking

**§11.6 — The Second Front: Speech and Electroglottography** (800–1000 palabras)
`[P]`
- D0 = 77.8% bajo bootstrap agrupado por hablante — notable por sí solo
- El baseline neural ya existe; los descriptor arms se leen como delta contra D0, no como números aislados.
- 12 condiciones testeadas, ninguna superó D0. Framing: frente abierto, no fallido.
- La pregunta ya no es si la estructura cross-modal existe (existe), sino bajo qué condiciones se vuelve legible.
- **OMITIR**: tabla arm-por-arm del null descriptor. Resumir en una oración.

**§11.7 — The Discovery: Representation Organizes Geometry** (600–800 palabras)
`[P]` + `[C]` — Eleva de reporte a contribución científica.
- Descriptores cambian CÓMO, no SI. Linear probes = no más decodificables, pero CKA = +82%.
- +29% información pre-projection, requiere readout no lineal.
- Conexión a Cap 3 (ontología relacional): el descriptor reestructura relación, no agrega contenido.
- **Frase clave**: "The descriptor does not enrich what the model knows. It reorganizes how the model relates what it already knows across modalities."

**§11.8 — Phideus as Constructive Process** (500–600 palabras)
`[P]` + `[C]`
- Utilidad ingenieril ≠ confirmación teórica.
- Horizonte: Escalón 3 (Audio↔Lissajous, convergencia Phideus-Beacon, sintético+analógico), Escalón 4 (ECG↔PPG). Nombrados, no elaborados.
- **Puente a Cap 12**: "The computational branch can make harmonic hypotheses operational, but it cannot exhaust the phenomenon."

- **§11.9 Experimental implications of the activation conjecture** `[P]+[C]` (~300 palabras): subsección que recoge la implicancia del activation problem (Cap 10) para Phideus. φ-probe vs integer-ratio probe en redes de phase-manifold. Se desarrolla cuando se aborde el manuscrito.

**Qué OMITIR de Cap 11**:
1. UOEMD/Rosetta como frente experimental fallido (SÍ incluir genealogía
   de representaciones en §11.3 como contexto metodológico,
   sin narrar el NO-GO del frente ni sus resultados)
2. Gate 9/A10: sin sección propia.
   Mantener solo una mención compacta dentro de §11.3 como parte del mapa descriptorial; no incluir tabla arm-por-arm ni S% individuales.
3. Gate 10: OMITIR del cuerpo principal del capítulo.
   Si hace falta, solo dejar su presión metodológica indirecta fuera de la prosa central.
4. Tabla arm-por-arm del null de S2 (sigue omitida)
5. Velocity/octave invariance collapse (sigue omitido)
6. Test 13G generative encoder (sigue omitido)

**Bibliografía pertinente**:

*Primarias* (arquitecturas y métodos usados en Phideus):
- Li et al. (MERT, 2024) §6.1 — audio encoder backbone (330M params)
- Bardes et al. (VICReg) §6.1 — loss function: invariance + variance + covariance
- Perez et al. (FiLM, 2018) §6.2 — Feature-wise Linear Modulation: condicionamiento
- Kornblith et al. (CKA) §6.2 — Centered Kernel Alignment: medida de reorganización geométrica
- Pearl (2009) §6.2 — inferencia causal: controles negativos (shuffle, zero, random)
- Vaswani et al. (Attention, 2017) §6.2 — Transformer: base de encoder y cross-attention

*Secundarias* (métodos alternativos, contexto ML):
- Zbontar et al. (Barlow Twins) §6.1 — loss contrastiva alternativa
- Baevski et al. (wav2vec 2.0) §6.1 — pretraining autosupervisado de audio
- ImageBind (Girdhar et al., 2023) §6.1 — unified embedding para 6 modalidades
- DeCUR (Liang et al., 2024) §6.1 — separación common/unique representations
- CLAP (Elizalde et al., 2023) §6.1 — SOTA audio↔text retrieval

*Escalón 3 — Lissajous* (§6.5):
- Chen et al. (2024) §6.5 — "images that sound": espacio latente compartido imagen↔audio
- Pejovic (2018) §6.5 — atlas Lissajous: recurso para dataset sintético
- Selvam & Rao (2024) §6.5 — Chladni→frecuencia: 99% accuracy con deep learning

**Longitud estimada**: 7000–9000 palabras

**Recursos visuales**: 2 figuras (arquitectura, mecanismos) + 4-5 tablas (frentes, descriptores, evidencia, multiseed, Gate 8)

---

#### Capítulo 12. Harmonic Beacon: la sonda experiencial
**Registro**: `[P]` + `[H]`
**Epígrafe**: *"It is not a sound object. It is a field."*

**Arco narrativo**: Historia de un dispositivo que convierte la teoría armónica en experiencia física. De la guitarra+motor al horizonte HAT. Incluye la conjunción PMP como programa terapéutico independiente que se articula con el Beacon.

**Estructura de secciones (7 secciones)**:

**§12.1 — What the Beacon Is** (1000–1200 palabras)
`[H]` + `[P]`
- Historia de origen: guitarra + motor → descubrimiento de interferencia armónica continua
- Distinción: NO metrónomo, NO drone, NO sound bath. Patrón de interferencia estructurado.
- **Capa operacional literal**:
  - fuente resonante física;
  - método de excitación continua;
  - afinación por coherencia del patrón;
  - instalación en una sala;
  - luego lectura perceptiva, fisiológica o visual del campo.
- Afinación por calidad de patrón de interferencia (láser + cymatics), no por frecuencia
- Pareidolia armónica: el cerebro encuentra melodías, voces, gaitas — paraeidólico, no ilusorio
- Por qué importa para HIT: fuente controlada de organización armónica natural
- **[FIGURA 12.1]**: Esquema del Beacon (guitarra, motor, onda estacionaria) o foto
- **[FIGURA 12.2]**: Visualización cymatics a diferentes puntos de afinación

**§12.2 — Principle of Operation: The Harmonic Gravitational Field** (800–1000 palabras)
`[P]` + `[C]`
- Física: cuerda excitada produce serie armónica completa simultáneamente; motor mantiene excitación
- Campo = superposición de armónicos con amplitudes y batimiento propio
- **Incluir fórmulas mínimas**:
  - serie armónica: `f_n = n f_0`
  - superposición sostenida: `s(t) = \sum A_n cos(2\pi n f_0 t + \phi_n)`
  - criterio de afinación: `\theta^* = argmax C(\theta)`
- Metáfora gravitacional: "Si le corrés la afinación, incomoda — esa incomodidad es de la que estás saliendo". Cuenca de atracción.
- Conexión a Cap 4 (consonancia como función) y Cap 8 (eficiencia)
- Rol de la habitación: interacción con acústica del espacio

**§12.3 — Evolution of the Device** (800–1000 palabras)
`[H]`
- Reescribir con la lógica fija:
  - problema heredado;
  - solución material;
  - ganancia experimental;
  - nueva limitación abierta.
- Gen 1: Beacon Guitarra
  - cuerda + motor + afinación manual;
  - máxima riqueza espectral;
  - fragilidad operativa, retuning constante y dependencia de sala.
- Gen 2: Pequeño Pico Robot
  - diapasones / resonadores más estables;
  - gana robustez y portabilidad;
  - pierde parte de la densidad espectral de la guitarra.
- Gen 3: Versión Digital / OSC
  - banco armónico programable, grilla de 64 pads, control remoto;
  - gana repetibilidad, acople con sensores y precisión;
  - reabre la pregunta por la materialidad del soporte resonante.
- Gen 4: App / Distributed Beacon
  - acceso remoto a un Beacon vivo, red distribuida, plataforma;
  - deja de ser solo instrumento local.
- **[TABLA 12.1]**: Generaciones del Beacon
  - columnas: generación, fuente física, método de excitación, cómo se afina, problema que resolvió, tradeoff introducido, portabilidad, riqueza espectral

**§12.4 — Four Experimental Lines** (1500–1800 palabras)
`[P]`
- **Línea 1: Lectura de Bioseñales.** Corazófono: acoplador/resonador torácico + membrana + micrófono direccional + lectura espectral. Objetivo: estimar centro resonante personal bajo prompts vocales repetidos.
- **Línea 2: Respuesta Fisiológica.** Pre/post HRV, EEG bajo exposición controlada. Pregunta: ¿parámetros autonómicos cambian de forma consistente con menor fricción?
- **Línea 3: EEG-to-Harmonics Feedback.** Biofeedback donde el sistema medido es también el perturbado. Infraestructura explícita: streams de sensores → OSC → control armónico en tiempo real. Dirección de investigación, no resultado.
- **Línea 4: Exploración sistemática de organización armónica visible.**
  Lissajous como objeto experimental: figuras producidas por resonancia física
  (tubos a medida, membranas vibrantes, espejo + láser, cámara).
  Exploración conducida por sistema multi-agente sobre OpenClaw (nombrar),
  con arquitectura jerárquica de agentes que delegan, descomponen y coordinan.
  Dataset en dos fases: sonido sintético → figuras analógicas;
  sonido analógico → figuras analógicas (pipeline enteramente físico).
  Convergencia con Escalón 3 de Phideus (Cap 11): ambas sondas llegan
  independientemente al mismo objeto.
- **OMITIR** resultados cuantificados (no hay publicables)
- **Directiva**: agregar un párrafo (~200 palabras) en §12.4 sobre el φ-offset en el campo Beacon como signature experiencial distinta, recogiendo la consecuencia experimental del Cap 10.

**§12.5 — Personal Myth Projection: a therapeutic practice articulated with the Beacon** (1000–1200 palabras)
`[H]` + `[C]`
- Autor: Julián De La Reta. Raíces: Jung (imaginación activa), Moreno (psicodrama), Campbell (monomito)
- Vera Imaginatio vs. Fantasia
- Protocolo resumido: Pregunta → warm-up → Llamada → Puerta → Descenso (22 escalones) → Guardián del Umbral (Sombra) → Cruce → Imaginación activa libre (60-90 min) → Retorno → Integración → Retorno al Mito
- Conceptos: Self, Sombra, Función Trascendente, betrachten, Individuación
- Monomito como mapa de transformación psíquica, no fórmula narrativa
- Inversión de roles (Moreno) como catalizador de la función trascendente
- **Demarcación firme**: NO musicoterapia, NO sound healing, NO entrainment. Psicoterapia jungiana/psicodramática que PUEDE integrarse con dispositivos resonantes. PMP no depende del Beacon, Beacon no depende de PMP.

**§12.6 — The PMP+Beacon Conjunction: Theoretical Assembly and Observations** (800–1000 palabras)
`[P]` + `[C]`
- Tres nodos:
  1. Self jungiano ↔ Referencia Armónica (centros de orientación no-intelectuales)
  2. Función Trascendente ↔ Proceso armónico (inconsciente→consciente ≈ equilibrio armónico)
  3. Sombra + Beacon (PMP abre puentes; Beacon sostiene campo durante sesión)
- Observación clínica repetida: múltiples aplicaciones con convergencia fuerte en acceso más fluido a material profundo, mayor permanencia y mejor integración
- Prosa a usar: la pregunta ya no es si algo ocurre, sino cómo describirlo, medirlo e interpretarlo mejor bajo protocolo comparativo
- Demarcación no defensiva: PMP sigue siendo práctica terapéutica propia; Beacon no se agota en ella; la conjunción es una práctica ya existente cuyo mecanismo se está aclarando

**§12.7 — HAT: Harmonically Aware Technology** (500–700 palabras)
`[P]`
- "¿Por qué nuestra casa no se siente naturaleza? ¿Por qué no es la madriguera del humano?"
- HAT: principio de diseño para infraestructura cotidiana no ciega a organización armónica
- Ejemplos concretos: router, electrodomésticos, habitación, casa
- Red de Beacons: mesh / app / fuente viva distribuida
- Beacon como actuador, Phideus como sensor
- Introducir como especulación posible `intuitive coprocessor` y `PPU` (`Proportional Processor Unity`), sin convertirlo en roadmap ni producto
- Visión, no plan. Puente a Cap 13.

**Bibliografía pertinente**:

*Primarias* (acústica del Beacon y cymatics):
- Chladni (1787) §6.3 — patrones nodales de ondas estacionarias
- Lissajous (1857) §6.3 — topología de ratios
- Jenny (1967) §6.3 — cymatics: "el sonido tiene forma"
- Rayleigh §6.3 — fundamentos acústicos
- Benade (1973) §6.3 — resonadores como series armónicas ricas
- Fletcher (1996) §6.3 — didgeridoo como resonador

*Secundarias* (instrumentos, bioseñales, feedback):
- Smith et al. §6.3, Tarnopolsky et al. §6.3, Abel et al. §6.3, Lohri §6.3
- Miller & Goss §6.4, Philips et al. §6.4, Puhan et al. §6.4, Di Nasso et al. §6.4

*Secundarias* (psicología analítica, psicodrama, monomito — §12.5, §12.6):
- Jung CW 8, CW 9/1, CW 16; Jung (1961) Memories, Dreams, Reflections
- Campbell (1949) — monomito cross-cultural
- Von Franz (1964) — individuación
- Moreno (1959, 1966) — psicodrama e inversión de roles
- Hannah (1998) — imaginación activa; Johnson (1986) — guía práctica
- Jacobi (1959), Chodorow (2015) — si se citan en prosa

**Longitud estimada**: 7000–9000 palabras

**Recursos visuales**: 2 figuras (esquema Beacon, cymatics) + 1 tabla (generaciones)

---

#### Capítulo 13. Convergencia Phideus-Beacon
**Registro**: `[P]` + `[C]`
**Epígrafe**: *"The probes do not agree; they become answerable to one another."*

**Arco narrativo**: Lectura integradora. No repite contenido de Caps 11-12 — sintetiza. Dos sondas, tres registros, feedback bidireccional, visión de futuro.

**Estructura de secciones (4 secciones)**:

**§13.1 — Two Perspectives on the Same Hypothesis** (600–800 palabras)
`[C]`
- Abrir desde la formulación amplia de HIT: la organización armónica/proporcional importa para información, estabilidad y experiencia
- Phideus: datasets pareados + descriptores + baseline/arms + reorganización representacional (registro computacional)
- Beacon: campo armónico sostenido + calibración + respuesta corporal/situada (registro fisiológico-experiencial)
- PMP+Beacon: setting terapéutico estructurado donde el campo puede importar para acceso y manejo de material profundo (registro psicológico)
- No la misma pregunta, pero sí la misma familia de hipótesis
- Asimetría de madurez honesta, sin tono defensivo: Phideus tiene evidencia cerrada; Beacon tiene observaciones repetidas y programa coherente; PMP+Beacon tiene práctica repetida y formalización comparativa en desarrollo

**§13.2 — The Feedback Loop: How Each Probe Informs the Other** (800–1000 palabras)
`[P]`
- Phideus → Beacon: taxonomía de descriptores como sensores de armonicidad para dispositivos
- Beacon → Phideus: Corazófono informa qué descriptores son biológicamente relevantes
- Feedback metodológico: cultura adversarial de Phideus adaptable a Beacon; validez ecológica de Beacon empuja Phideus más allá de leaderboards
- PMP como tercer vértice: aporta vocabulario de proceso y preguntas sobre acceso, sostén e integración que no emergen ni del retrieval ni de la bioseñal por sí solos
- Convergencia más tangible: tercera fase experimental (Lissajous), donde ambas sondas estudian el mismo objeto. Phideus vía generación sintética con ground truth paramétrico; Beacon vía captura analógica de patrones físicos de resonancia. El cruce sintético-analógico produce una pregunta cross-modal propia: ¿la organización aprendida del dataset sintético transfiere al capturado del mundo físico?
- **[FIGURA 13.1]**: Diagrama triangular del feedback loop Phideus-Beacon-PMP (bidireccional entre los tres vértices)

**§13.3 — The Triangle: Computational, Physiological, Psychological** (800–1000 palabras)
`[P]` + `[C]`
- Phideus (computacional): descriptores proporcionales reorganizan representación computable → sí, con evidencia cerrada
- Beacon (fisiológico): inmersión armónica modifica estados corporales y condiciones de resonancia → observaciones repetidas y protocolos en formalización
- PMP+Beacon (psicológico): el campo armónico modifica acceso, sostén e integración de material profundo → práctica repetida y observación clínica estructurada
- Tres registros irreducibles, convergentes en la pregunta
- Insistir en triangulación, no cadena causal entre registros
- Las preguntas fuertes son los cruces entre registros, no la reducción de uno al otro
- **[TABLA 13.1]**: Tres registros de evidencia (5 columnas: registro, sonda, pregunta, estado actual, tipo de evidencia)

**§13.4 — Vision: A Network of Beacons, a Landscape of Harmony** (500–700 palabras)
`[P]` + `[C]`
- Phideus como sensor de armonicidad
- Beacon como actuador de campos armónicos
- PMP como setting estructurado donde esos campos adquieren espesor procesual e interpretativo
- Integrar HAT como horizonte de infraestructura: salas, dispositivos y redes no ciegos a la organización proporcional del entorno
- Integrar PPU / intuitive coprocessor como nombre especulativo y controlado para el horizonte sensor + actuador + lectura proporcional
- **Cierre**: la convergencia ya no pertenece a un único instrumento sino a una arquitectura de sondas heterogéneas que vuelve el fenómeno más observable y más operable sin agotarlo

**Qué OMITIR de Cap 13**:
1. Planes técnicos futuros detallados (van en Cap 15)
2. Lenguaje defensivo o demarcaciones reactivas entre registros
3. Arquitecturas ML o hiperparámetros (Cap 13 opera a nivel convergencia)

**Bibliografía pertinente**:

*Secundarias* (precedentes de convergencia multimodal):
- ImageBind (Girdhar et al., 2023) §6.1 — convergencia multimodal via bridging modality
- Kornblith et al. (CKA) §6.2 — métricas para medir convergencia representacional
- DeCUR (Liang et al., 2024) §6.1 — separación common/unique
- Lotman (2005) §2.5 — semiosfera y traducción entre espacios heterogéneos

**Longitud estimada**: 3000–4000 palabras

**Recursos visuales**: 1 figura (feedback loop) + 1 tabla (tres registros)

---

### RESUMEN DE RECURSOS VISUALES — PARTE V

**Tablas (7)**:
| Tabla | Sección | Contenido |
|-------|---------|-----------|
| 11.1 | §11.2 | Frentes experimentales (4 escalones) |
| 11.2 | §11.3 | Inventario de descriptores del programa (por frente) |
| 11.3 | §11.5 | Resumen de Evidencia Escalón 1 (tabla flagship) |
| 11.4 | §11.5 | Replicación Multi-Seed |
| 11.5 | §11.5 | Gate 8 conditioned projections (opcional) |
| 12.1 | §12.3 | Generaciones del dispositivo Beacon |
| 13.1 | §13.3 | Tres registros de evidencia |

**Figuras (5)**:
| Figura | Sección | Contenido |
|--------|---------|-----------|
| 11.1 | §11.2 | Arquitectura dual encoder + descriptor injection + VICReg |
| 11.2 | §11.4 | Tres mecanismos de inyección (concat, cross-att, FiLM) |
| 12.1 | §12.1 | Esquema/foto del Beacon |
| 12.2 | §12.2 | Cymatics a diferentes puntos de afinación |
| 13.1 | §13.2 | Feedback loop Phideus-Beacon (circular, bidireccional) |

**Conteo de palabras total Parte V**: ~18,000–23,000 palabras (20 secciones)

---

### PARTE VI — ALCANCES, LÍMITES Y FUTURO
*Función: Honestidad epistémica + agenda.*
*Extractabilidad: → Defensa epistémica, → FAQ, → Manifiesto (cierre)*

---

#### Capítulo 14. Lo que HIT no es
**Registro**: `[F]` + `[C]`
**Epígrafe**: *"Demarcation is not retreat. It is precision."*

**Arco narrativo**: Capítulo de demarcación positiva. No funciona como lista reactiva de acusaciones, sino como clarificación de objeto, límites y malas lecturas posibles después de la convergencia de Parte V.

**Movimientos internos**:
- **Demarcación ontológica**: HIT no es pitagorismo ni metafísica de pureza. Los ratios valen como restricciones relacionales locales y dinámicas, no como absoluto.
- **Demarcación de alcance**: HIT no es universalismo ingenuo y no es una teoría del sonido en sentido estrecho. La armonía natural es local a sistemas concretos; lo acústico funciona como laboratorio privilegiado, no como frontera del marco.
- **Demarcación epistemológica**: HIT no es teoría cerrada ni vocabulario inmune a contraste. Es un programa de investigación con jerarquía de claims, falsabilidad y belt revisable.
- **Demarcación de registro**: HIT no convierte lenguaje simbólico, espiritual o experiencial en pseudo-física. Articula registros heterogéneos sin colapsarlos en una sola explicación.
- **Posicionamiento relativo**: HIT conversa con ontologías consciousness-first y programas de consciencia cuántica sin reducirse a ninguno de ellos.
- **Demarcación interdisciplinaria**: HIT no es reduccionismo ni autopoiesis aplicada. La triangulación entre lo computacional, lo fisiológico y lo psicológico no implica identidad ontológica ni cadena causal lineal.
- **Demarcación aplicada**: HIT no es psicoterapia ni marca terapéutica cerrada. PMP conserva su marco propio; su articulación con Beacon pertenece a un programa de investigación y práctica comparativa, no a una prescripción universal.
- **Cierre**: reconocer límites reales sin debilitar el programa. El valor está en la pregunta coordinada y en la disciplina comparativa que el programa vuelve posible.

**Bibliografía pertinente**:

*Primarias* (demarcación epistémica):
- Popper (1959) §7.2 — falsificabilidad: criterio de demarcación HIT
- Lakatos (1970) §7.2 — programa de investigación: HIT tiene hard core falsificable
- Derrida (1967) §7.2 — crítica de presencia y pureza originaria: guardrail anti-esencialista
- Nietzsche (1873) §7.2 — verdad y metáfora: guardrail contra reificar conceptos como esencias
- Calvo (2006) §2.2 — guardrail contra isomorfismo ingenuo entre modelo y realidad

*Secundarias* (estudios críticos y frontera):
- Parncutt & Hair (2011) §7.1 — estudios críticos sobre consonancia
- McDermott et al. (2016) §3.5 — Tsimane: constraint sobre universalismo ingenuo
- Maturana & Varela (1987) §3.2/§9 — guardrail: organización/estructura y acoplamiento sin identidad ontológica
- Di Paolo (2005) §9 — precariedad y regulación sin colapsar lo vivo en patrón armónico
- Hoffman (2008) §2.2 — `conscious realism` como programa ontológico vecino
- Kastrup (2017a, 2017b) §2.2 — idealismo analítico como vecino ontológico contemporáneo
- Stapp (2005) §1.4 — dualismo interactivo cuántico como frontera mind-matter
- Hameroff & Penrose (2014) §1.4 — `Orch OR` como programa adyacente de consciencia cuántica

**Longitud estimada**: 2200-2600 palabras

---

#### Capítulo 15. Preguntas abiertas y agenda de investigación
**Registro**: `[P]` + `[C]`
**Epígrafe**: *"The future of the program is not one horizon but several distances."*

**Contenido**:
- **§15.1 — Why an Agenda Is Needed Now**:
  - abrir desde el pasaje `convergencia/demarcación -> programa`;
  - explicar por qué la agenda debe ordenar tareas por distancia epistemológica y no como lista plana;
  - fijar la jerarquía `próximos pasos inmediatos / expansión de mediano plazo / horizonte teórico-tecnológico`.
- **Preguntas fundamentales**:
  - ¿Cuánta información transporta un patrón armónico?
  - ¿Qué de ese patrón transporta qué información?
  - ¿Cómo lo aislamos y medimos?
  - ¿Es ergódico?
  - ¿La eficiencia informacional de los ratios simples es un principio general o un artefacto del sistema receptor?
  - ¿Qué parte de una topología nodal pertenece al medio, cuál a la excitación y cuál a la interacción entre ambos?
  - ¿Dónde están las fronteras topológicas del espacio de parámetros y cómo se comportan cerca de razones irracionales?
- **Criterio interno de escritura**: ordenar la agenda por distancia epistemológica y proximidad programática, distinguiendo explícitamente entre (a) próximos pasos inmediatos, (b) expansión experimental de mediano plazo y (c) horizontes teórico-tecnológicos más especulativos.
- **§15.2 — Immediate Questions and Programmatic Next Steps**:
  - Multi-seed validation (5+ seeds por brazo) allí donde todavía falte cierre comparable
  - `S2-P3` como contraste de régimen de encoder: ¿el paso de un encoder speech `from-scratch` a un foundation encoder congelado vuelve legible la señal descriptor-guided en `Speech↔EGG`?
  - Consolidación del contraste descriptor × mecanismo en la rama retrospectiva de Escalón 1 antes de generalizar la lectura a nuevos dominios
- **§15.3 — Phideus Beyond the Current Fronts**:
  - Escalón 3 (Lissajous): retrieval audio XY ↔ figura, recuperación de parámetros generativos, descriptores topológicos y geométricos, barridos racional vs. irracional, cruce sintético↔analógico con dataset Beacon, y problema inverso nodal en medios de interferencia controlada
  - Descriptores de recurrencia (A10) como test de la cadena teórica
  - Retratos oscilatorios multifrecuencia, en la línea de Bahuguna et al., como doble herramienta: nueva familia de descriptores trial-by-trial y métrica complementaria al retrieval para leer organización relacional
  - Transfer learning: ¿un modelo entrenado en `Audio↔MIDI` transfiere a `Speech↔EGG` o a dominios de señal más alejados?
  - Escalón 4 (ECG↔PPG): extensión fuera de acústica a fisiología cardiovascular
  - Extensión a vibración estructural y sensing mecánico: datasets tipo Chakraborty et al. como banco para probar si la lógica descriptor-guided sobrevive cuando el carrier es vibración en medios construidos y no sonido aéreo
  - Toy models de computación resonante: medios fijos, excitación, lectura y estabilidad bajo perturbación
- **§15.4 — Beacon and PMP+Beacon: From Observation to Protocol**:
  - Protocolo corazófono → medición pre/post exposure
  - EEG-to-harmonics feedback loop
  - Estudio de pareidolia armónica con N suficiente
  - Beacon personalizado vs. genérico: diferencia en métricas fisiológicas
  - Construcción del dataset analógico de Lissajous: exploración sistemática vía OpenClaw de conjunciones armónicas con captura física (láser + cámara). Dos fases: sonido sintético → figuras analógicas, y sonido analógico → figuras analógicas. Convergencia con Escalón 3 de Phideus.
  - Protocolo PMP+Beacon con medición pre/post: bioseñales (HRV, EEG) + cuestionarios estandarizados (STAI, PANAS, o equivalente) + análisis de contenido simbólico de las sesiones
  - Comparación PMP sola vs PMP+Beacon: ¿modifica la presencia del campo armónico alguna variable medible (profundidad de acceso, sostenimiento de tensión, calidad del material simbólico)?
  - N mínimo para claims publicables: estimación de power estadístico necesario dado variabilidad esperada
  - Estudio de la inversión de roles como momento de activación de la función trascendente: ¿detectable en bioseñales? (HRV, EEG, conductancia cutánea como proxies de cambio de estado)
  - Codificación del contenido simbólico: ¿las imágenes producidas en sesiones con Beacon difieren cualitativamente de las producidas sin Beacon? (análisis temático, jueces ciegos)
- **§15.5 — Theoretical Formalization and Long-Horizon Technology**:
  - Formalización matemática de la eficiencia armónica
  - Relación con free energy principle (Friston)
  - Relación con biosemiótica (Hoffmeyer, Barbieri)
  - Nuevas familias de descriptores relacionales: estimadores tipo Harmonic Aggregation Entropy (Wang et al.) para medir consistencia armónica y estructura de agregación en series temporales ruidosas
  - Formalización de la relación entre acoplamiento estructural y mode-locking: ¿puede formularse una métrica cuantitativa de "éxito de acoplamiento" que conecte el ancho del Arnold tongue con propiedades del sistema receptor? (Maturana/Varela → Kuramoto)
  - Relación con autonomía biológica (Varela, Di Paolo): ¿la precariedad del sistema receptor predice la magnitud del efecto del campo armónico?
  - Horizonte adyacente: quantum neurobiology y ontologías consciousness-first como programas vecinos para pensar relaciones entre coherencia, información, materia y mente sin convertirlos en fundamento probatorio principal de HIT
  - PPU (`Proportional Processor Unity`) / `intuitive coprocessor` como horizonte a explicitar: no producto ni roadmap cerrado, sino nombre provisional para una arquitectura futura donde lectura proporcional (`Phideus`) y modulación/actuación armónica (`Beacon`) puedan acoplarse en un mismo sistema

**Bibliografía pertinente**:

*Primarias* (agenda teórica):
- Friston (2010) §2.4 — free energy principle: formalización pendiente de la eficiencia armónica
- Hoffmeyer (2008) §1.3 — biosemiótica: investigar ratios como sistema semiótico
- Barbieri (2008) §1.3 — códigos orgánicos: ¿los ratios son un código biológico?
- Bahuguna et al. (2025) — retratos oscilatorios multifrecuencia como objeto descriptorial y predictivo
- Wang et al. (2025) — Harmonic Aggregation Entropy como precedente de descriptor relacional/entrópico para series temporales
- Chakraborty et al. (2025) — dataset de vibración estructural para reconocimiento de marcha como expansión de dominio más allá del audio
- Pinasco & Scarola (2021) §6.5 — límites y posibilidades del problema inverso nodal
- Maynard et al. (1985) §6.5 — medición de campos: qué exigir a una inferencia física seria

*Secundarias* (fronteras especulativas):
- Rocco & Guff §7.4 — simetría temporal cuántica: enlace especulativo
- Picard & McEwen §5.5 — psicología mitocondrial: música→estrés→mitocondria→homeostasis
- Picard et al. (2019) §5.5 — mitocondria y señalización celular
- Turin §5.5 — olfato vibracional: percepción de frecuencia molecular
- Celardo et al. (2023) §5.5 — transferencia energética molecular en microtúbulos
- Levin (2021) §5.5 — bioelectricidad: ratios iónicos en morfogénesis
- Jaeger (2001) §6.1 — echo state / reservoir computing: medio fijo + dinámica rica + readout
- Ramsauer et al. (2021) §6.1 — atención como memoria asociativa / estabilización energética
- Rahaman et al. (2019) §6.1 — spectral bias: jerarquías de frecuencia en el aprendizaje
- Tancik et al. (2020) §6.1 — Fourier features: parametrización sinusoidal y alta frecuencia
- Sitzmann et al. (2020) §6.1 — activaciones periódicas y representaciones implícitas

**Longitud estimada**: 2500-3000 palabras

---

#### Capítulo 16. Aplicaciones y derivaciones
**Registro**: `[P]`
**Epígrafe**: *"What follows is not closure. It is a larger field of consequences."*

**Contenido**:
- **§16.1 — What a Derivation Means Here**:
  - abrir desde el pasaje `agenda -> consecuencia pública`;
  - fijar que una derivación no equivale ni a aplicación validada ni a fantasía tecnológica;
  - ordenar el capítulo por distancia epistemológica y no por entusiasmo.
- **§16.2 — Near Instrumental Derivations: Health, Physiology, Ecology**:
  - Salud y fisiología: perturbaciones o desviaciones de organización armónica como candidatos a indicador exploratorio de coherencia/regulación del sistema, siempre bajo protocolos explícitos y sin convertir todavía esa lectura en marcador clínico cerrado
  - Relación con HRV, coherencia cardíaca y otros marcadores como línea de contraste, no como equivalencia ya demostrada
  - Ecología: métricas de salud ecosistémica basadas en distribución espectral y organización del nicho acústico
- **§16.3 — Technological and Computational Derivations**:
  - HAT (`Harmonically Aware Technology`) como criterio de diseño para dispositivos, salas y redes técnicas que no sean ciegas a su impacto armónico en el entorno
  - Sensores de armonicidad distribuidos (`Phideus`) + actuadores/campos armónicos (`Beacon`) como reparto funcional posible de una infraestructura futura
  - Interfaces cimáticas y sensado topológico de campos de interferencia
  - `PPU` / `intuitive coprocessor` como extrapolación más ambiciosa de esta línea: arquitectura especulativa donde lectura, comparación y respuesta proporcional se acoplan sin presentarse como producto ya existente
  - Cross-modal understanding basado en estructura armónica
  - Sonificación armónica de estados de red/sistema
  - Medios resonantes como inspiración arquitectónica: reservoirs, parametrizaciones periódicas, memoria asociativa y lectura de estados
- **§16.4 — Biomechanics and Material Infrastructure**:
  - Gait, vibración estructural y sensing mecánico como dominios donde la organización proporcional puede portar identidad, estado o degradación del sistema
  - Monitoreo estructural, biomecánica y manufactura sensorizada como familias de aplicación independientes de salud biológica y ecología
- **§16.5 — Cultural, Artistic, and Educational Derivations**:
  - Arte: instrumentos en afinación natural, experiencias inmersivas y dispositivos donde la pareidolia armónica se vuelve medio de exploración
  - Educación: formación auditiva y material en armonía natural, no como slogan espiritual sino como alfabetización en organización proporcional
  - cierre del libro: volver desde las derivaciones públicas al núcleo del programa sin caer en triunfalismo

**Bibliografía pertinente**:

*Primarias* (aplicaciones con evidencia):
- Krause (2013) §1.3 — métricas ecosistémicas basadas en distribución espectral
- Buxton et al. (2021) §1.3 — sonidos naturales y salud: meta-análisis
- Chakraborty et al. (2025) §7.2 — vibración estructural y gait recognition como dominio de aplicación fuera del audio aéreo
- Wang et al. (2025) §7.2 — descriptores armónico-entrópicos robustos para series temporales en entornos ruidosos

*Secundarias* (por área de aplicación):
- *Salud*: Blood & Zatorre (2001) §5.1, Rebecchini §5.2, Bradt et al. (2021) §5.2, de Witte et al. §5.2, Thoma et al. §5.2, Puhan et al. §6.4
- *Entrainment/experiencias*: Winkelman §5.3, Maxfield §5.3
- *Cultura/educación*: Feld (1982) §1.3 — sonido en cultura
- *IA multimodal*: ImageBind (Girdhar et al., 2023) §6.1
- *IA/computación resonante*: Jaeger (2001) §6.1 — echo state / reservoir computing; Ramsauer et al. (2021) §6.1 — Hopfield moderno; Rahaman et al. (2019) §6.1 — spectral bias; Tancik et al. (2020) §6.1 y Sitzmann et al. (2020) §6.1 — parametrizaciones sinusoidales
- *Biomecánica e infraestructura*: Chakraborty et al. (2025) §7.2 — gait vía vibración estructural; Chen et al. (2023) §7.2 — cycle-informed sensing; Wang et al. (2025) §7.2 — HaAgEn como family of descriptors en series temporales
- *Síntesis/arte*: DDSP (Engel et al., 2020) §6.1 — síntesis diferenciable
- *Sensado/interferencia*: Maynard et al. (1985) §6.5 — nearfield acoustic holography y reconstrucción espacial de campos

**Longitud estimada**: 2000-3000 palabras

---

## 3. References

Bibliografía general del manuscrito, organizada por campo temático.
Formato: APA 7th Edition. Fuente canónica: `bibliografia_HIT.md` (APA) + `LaTeX/references.bib` (BibTeX, 294 entradas).

Orden por campo (NO alfabético global — el lector ubica cada referencia por el dominio al que pertenece):

1. **La tendencia: convergencia empírica entre campos**
   1.1 Resonancia neural y percepción armónica
   1.2 Psicoacústica y consonancia
   1.3 Ecología acústica y biosemiótica
   1.4 Sistemas dinámicos y recurrencia
   1.5 Percepción cross-especie

2. **Ontología: qué es la información armónica**
   2.1 Teoría de la información
   2.2 Filosofía de proceso y relacionalismo
   2.3 Autopoiesis y enacción
   2.4 Principio de energía libre y eficiencia
   2.5 Interdisciplinariedad y zonas de intercambio

3. **Epistemología: qué sabemos**
   3.1 Consonancia, disonancia y percepción tonal
   3.2 Entonación justa y temperamento
   3.3 Etnomusicología y tradiciones armónicas
   3.4 Arqueoacústica y evidencia prehistórica
   3.5 Estudios cross-culturales y pareidolia

4. **Eficiencia informacional: armonía y termodinámica**
   4.1 Recurrencia y estabilidad dinámica
   4.2 Landauer, costo energético y computación
   4.3 Fractales, ratio áureo y auto-organización

5. **El sentido de la consonancia como sentido biológico**
   5.1 Neurociencia de la recompensa musical
   5.2 Musicoterapia y efectos restaurativos
   5.3 Entrainment y estados alterados
   5.4 Teoría polivagal y regulación autonómica
   5.5 Bioelectricidad, biología cuántica y señalización oscilatoria

6. **Programa experimental**
   6.1 Phideus: aprendizaje cross-modal y representaciones
   6.2 Phideus: mecanismos de inyección y condicionamiento
   6.3 Harmonic Beacon: acústica de instrumentos y resonancia
   6.4 Harmonic Beacon: bioseñales y feedback
   6.5 Phideus: figuras de Lissajous y aprendizaje cross-modal audio-visual
   6.6 Psicología analítica, psicodrama y Proyección del Mito Personal

7. **Diferenciación epistémica**
   7.1 Estudios críticos
   7.2 Falsificabilidad y controles negativos
   7.3 Epistemología de la inconsistencia
   7.4 Fronteras especulativas (quantum neurobiology, consciousness-first)
   7.5 Epistemología crítica y metodológica

Dentro de cada subsección: orden alfabético por primer autor.
Estructura replicada de `bibliografia_HIT.md`.

---

## 4. Appendices

| Apéndice | Contenido | Extractabilidad |
|----------|-----------|-----------------|
| **A. Glossary** | Apéndice híbrido breve: `Table A.1` con las hipótesis canónicas `H1-H6` (`claim`, capítulos primarios, estado actual, experimento/probe clave) seguida de un glosario alfabético de terminos canónicos tal como se usan en el manuscrito. Definiciones operativas breves, con remisiones mínimas, para nociones transversales de HIT, vocabulario de Phideus, Beacon/PMP/HAT y distinciones metodológicas (`descriptor`, `mechanism`, `arm`, `natural harmony`, `perceptual harmony`, `Information`, `Entropy`, `The Real`, `register`, `HAT`, `PPU`, `VICReg`, etc.). | → Cualquier derivado |
| **B. Experimental Results** | Apéndice tabular con cuatro bloques: `B.1` convenciones de lectura y estados; `B.2` Escalón 1 canónico (multi-seed, causalidad, CKA, hard negatives, Gate 8); `B.3` ramas retrospectivas (Gate 9/A10 closed, Gate 10 closed — 9/9 arms @e30, concat > FiLM/pca >> attn_bias); `B.4` inventario completo del null mecanístico de Escalón 2, arm-by-arm. | → Paper Phideus |
| **C. Technical Specifications** | Apéndice metodológico de `Phideus` con seis bloques: `C.1` alcance y estados; `C.2` familias descriptoriales; `C.3` variantes de mecanismo; `C.4` arms canónicos; `C.5` esqueletos arquitectónicos y shape conventions; `C.6` protocolos de evaluación (`pool builder`, bootstrap, `S=min(...)`, reporting rules). | → Paper metodológico |
| **D. Project Chronology** | Cronología híbrida de programa con seis bloques: `D.1` criterio de lectura; `D.2` formación del programa; `D.3` hitos Phideus; `D.4` generaciones y líneas Beacon; `D.5` momentos de convergencia; `D.6` corte actual del libro. | → Histórico, grants |
| **E. Mathematical Substrate of Harmonic Activation** | Sustrato matemático formal diferido del Cap 10: teorema de Hurwitz y fracciones continuas, equidistribución de Weyl y teorema de tres distancias (Sós), tratamiento formal de KAM y toro golden-mean, operador almost Mathieu en acoplamiento crítico, números nobles y generalización alto-dimensional, Harmonic Activation Lemma (enunciado conjectural completo). Sección opcional final: convergencias externas (Takalo interferencia prime-weighted, Penrose QEC, spectral gaps). Registro: `[F]`. | → Paper teórico, → Defensa epistémica |
| **F. Working Conceptual Synthesis** | Síntesis programática breve del núcleo conceptual de HIT: armonía como estabilidad dinámica, información como patrón detectable, recurrencia, eficiencia, biosemiosfera, nicho acústico, `spiritual homeostasis`, y la dualidad storage/retrieval. **Directiva de reescritura**: no se trata de agregar un §F.11 suelto. Codex debe reescribir la síntesis para absorber orgánicamente: (1) dualidad storage/retrieval como ciclo completo de la información armónica, (2) activation problem como complemento de Cap 8-9, (3) φ como candidato para un subproblema de query, no como centro nuevo de HIT. El resultado debe sentirse como síntesis actualizada, no como apéndice con bloque pegado al final. | → Manifiesto, talks, grants |

---

## 5. Mapa de extractabilidad detallado (6 derivados principales; Defensa epistémica omitida del diagrama — ver tabla §0)

```
                    ┌─────────────────────────────────────┐
                    │       LIBRO (16 capítulos)           │
                    └──────────────┬──────────────────────┘
                                   │
         ┌─────────────────────────┼─────────────────────────┐
         │                         │                         │
    ┌────▼────┐             ┌──────▼──────┐           ┌──────▼──────┐
    │Manifiesto│             │Paper Phideus│           │Grant Beacon │
    │  HIT     │             │  (ML/signal)│           │             │
    ├─────────┤             ├─────────────┤           ├─────────────┤
    │Cap 1,2  │             │Cap 7,11     │           │Cap 12,13    │
    │Cap 5    │             │Cap 5 (H1-H3)│           │Cap 9,10     │
    │Cap 8,9  │             │Apénd B,C    │           │Cap 15,16    │
    │Cap 14   │             │             │           │Apénd B,D    │
    │Apénd F  │             │             │           │             │
    │(10?)    │             │             │           │             │
    └─────────┘             └─────────────┘           └─────────────┘
         │                         │                         │
    ┌────▼────────┐         ┌──────▼──────┐           ┌──────▼──────┐
    │Paper teórico│         │Paper método │           │Divulgación  │
    ├─────────────┤         ├─────────────┤           ├─────────────┤
    │Cap 3,4,5    │         │Cap 7        │           │Cap 1,2      │
    │Cap 6,8,10   │         │Cap 11       │           │Cap 4,9      │
    │Cap 14       │         │Apénd C      │           │Cap 12,16    │
    │Apénd E,F    │         │             │           │             │
    └─────────────┘         └─────────────┘           └─────────────┘
```

---

## 6. Diferencias con propuestas anteriores

### vs. Estructura Claude original (7 secciones)
- Se mantiene el flujo: observación → ontología → epistemología → eficiencia → sentido → programa → diferenciación
- Se **expande**: lo que era 1 sección (programa experimental) ahora son 3 capítulos (Phideus, Beacon, convergencia)
- Se **agrega**: capítulo de hipótesis formales (5), capítulo de metodología (7), capítulo de aplicaciones (16)
- Se **separa**: lo que era "estado del arte" ahora tiene su propio capítulo largo (6)

### vs. Propuesta GPT5.4 (20 secciones)
- Se **fusionan** secciones que eran redundantes: ontología info armónica + ontología relacional consonancia → 2 capítulos (3+4) con contenido más denso
- Se **fusionan**: cuerpo/percepción + homeostasis espiritual → 1 capítulo (9) con framing más cuidado
- Se **fusiona**: dispersión disciplinaria con genealogía → capítulo 2 integrado
- Se **elimina**: prefacio redundante (la intro cumple esa función)
- Se **agrega**: capítulo de convergencia Phideus-Beacon (13) — ausente en GPT
- Se **agrega**: la rectificación epistemológica (en cap 7) — GPT no conoce este avance
- De 20 secciones → 16 capítulos: más manejable, mismo alcance

### vs. Draft "Conceptual Framework" existente
- El draft (Chapter 1: Interval Hypothesis) cubre parcialmente lo que serán capítulos 3 y 5
- Tono demasiado hedged para un libro fundacional — se recuperará contenido pero se reescribirá con más convicción donde la evidencia lo soporta
- Las 10 secciones del draft se redistribuyen en la estructura nueva

---

## 7. Plan de escritura (sugerido)

### Fase 1: Esqueleto (lo que existe)
- Consolidar material de: draft Chapter 1, estructura Claude, transcripción Nico, resultados Phideus
- Crear outline detallado de cada capítulo (secciones internas, argumentos clave)

### Fase 2: Capítulos nucleares (primero lo irrenunciable)
1. **Cap 5** — Hipótesis: el corazón formal, todo lo demás refiere a esto
2. **Cap 3+4** — Ontología: los fundamentos conceptuales
3. **Cap 8 + 10** — Eficiencia + Activation: la tesis fuerte y su complemento de retrieval

### Fase 3: Capítulos empíricos
4. **Cap 11** — Phideus (cuando Gate 9 / A10 / Escalón 2 tengan resultados)
5. **Cap 12** — Beacon
6. **Cap 6** — SOTA review (el más largo, puede escribirse en paralelo)

### Fase 4: Marco y cierre
7. **Cap 1+2** — Apertura (se escribe mejor cuando se sabe qué se va a decir)
8. **Cap 7** — Metodología
9. **Cap 9** — Sentido de la consonancia
10. **Cap 13-16** — Convergencia, diferenciaciones, agenda, aplicaciones

### Fase 5: Apéndices y pulido
- Glosario, tablas, mapas, cronología
- Revisión de registros y coherencia
- Verificación de extractabilidad

### Criterios de redacción vigentes
1. No sobrecargar un bloque corto con demasiados autores densos; cuando haga falta, organizar por ejes conceptuales o derivar parte del material a nota/apéndice.
2. Cada subsección de review debe declarar su función en el argumento, no limitarse a enumerar hallazgos del campo.
3. Variar la retórica del hedge; mantener cautela sin repetir siempre la misma sintaxis correctiva.
4. Introducir matemática solo cuando estabiliza el argumento; que sea compatible con una futura migración a LaTeX, pero sin volver LaTeX la fuerza rectora de esta versión.
5. No reexplicar contexto ya consolidado salvo que cambie su función en el nuevo paso argumental.

---

## 8. Decisiones pendientes

| Decisión | Opciones | Impacto |
|----------|----------|---------|
| **Idioma** | EN / ES / Bilingüe | Alcance de audiencia vs. autenticidad |
| **Título** | Ver candidatos abajo | Posicionamiento |
| **Extensión target** | 40K-60K palabras (libro corto) vs. 20K-30K (libro breve) | Profundidad vs. manejabilidad |
| **Nivel de formalismo** | Semi-formal (prosa argumentativa) vs. formal (proposiciones numeradas) | Accesibilidad vs. rigor |
| **Inclusión de la transcripción** | Como fuente citada vs. como apéndice vs. integrada en texto | Autenticidad vs. rigor académico |

### Candidatos a título
1. *Harmonic Information Theory: Foundations*
2. *Toward a Harmonic Information Theory*
3. *HIT: A General Framework for Harmonic Information*
4. *The HIT Compendium: Ontology, Epistemology, and Methodology of Harmonic Information*
5. *Foundations of Harmonic Information Theory: From Interval to Meaning*

---

---

## 9. Referencias pendientes — RESUELTO ✅

**Todas las 17 referencias pendientes han sido agregadas a `bibliografia_HIT.md` (v6, 2026-03-13).**

- 7 ya existían en la bibliografía: Maxwell, de Broglie, Davisson & Germer, Abbott, Engels, Nguyen, Calvo Vélez
- 10 agregadas en v6: Kuhn (§7.2), Star & Griesemer (§2.5), Wheeler (§2.1), Heidegger (§2.2), Derrida (§2.2), Lacan (§2.2), Lotman (§2.5), Nietzsche (§2.2), Erlich (§1.2), Stolzenburg (§1.2)
- Total actualizado: 211 entradas

---

*Arquitectura v1.3 (2026-03-13). Pase editorial aplicado: bloque filosófico expandido, formalización ligera en Caps. 5 y 8, criterios de redacción vigentes. Pendiente revisión por el equipo.*
