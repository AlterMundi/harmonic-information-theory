# Brief técnico para agentes de IA que construirán la web de *Harmonic Information Theory*

## 0. Propósito de este documento

Este documento funciona como **especificación operativa** para agentes de IA o sistemas automáticos encargados de diseñar, maquetar o implementar la web oficial del libro **Harmonic Information Theory**.

La prioridad de este brief es:
1. claridad;
2. consistencia editorial y legal;
3. correcta presentación del ecosistema de publicación;
4. distinción precisa entre formatos;
5. coherencia con la licencia y con el estado actual del ISBN.

**Nota sobre idioma:** Este brief está escrito en español, pero la web del libro debe estar **principalmente en inglés** (el libro está escrito en inglés), con posibilidad de una versión o sección en español. Los textos listos para pegar incluidos en este documento están en español como referencia de contenido; deben ser traducidos al inglés para la implementación principal de la web.

---

## 1. Datos editoriales y jurídicos que deben considerarse como fuente de verdad

### 1.1. Autoría
**Autores del libro:** Mariano Fernández Méndez y Nicolás Echániz

### 1.2. Compilación y redacción final
**Compilador y redactor final:** Mariano Fernández Méndez

### 1.3. Marco institucional
La obra fue realizada en el marco institucional de **Asociación Civil AlterMundi**.

### 1.4. Equipo de investigación y desarrollo
El sitio debe poder mostrar, en un bloque institucional o de créditos ampliados, el siguiente equipo de investigación y desarrollo:

- Anabella Scigliano
- Federico Bonino
- Julián De La Reta
- Martín Fernández Méndez
- Pablo Bustos
- Saira Asua
- Santiago Cetrán
- Sofía Campagnoli

### 1.5. Licencia
La obra se distribuye bajo licencia:

**Creative Commons Attribution 4.0 International (CC BY 4.0)**  
<https://creativecommons.org/licenses/by/4.0/>

### 1.6. Estado del ISBN
**El ISBN todavía no fue asignado.**  
La edición PDF circula actualmente como **edición preliminar oficial con ISBN en trámite**.

### 1.7. Formato con ISBN
Cuando el ISBN sea asignado, corresponderá **solo a la edición PDF oficial**.  
No debe presentarse el Markdown ni el repositorio LaTeX como formatos con ISBN independiente.

---

## 2. Principio editorial central del sitio

La web debe presentar una sola obra con varias capas de acceso:

- **PDF** = edición bibliográfica oficial del libro (actualmente preliminar; ISBN en trámite)
- **Markdown** = versión abierta y estructurada del libro, especialmente útil para lectura automatizada, navegación semántica y uso por LLMs
- **Repositorio LaTeX** = fuente editorial del libro
- **Repositorios relacionados del proyecto** = externos al repo del libro; pueden enlazarse, pero no deben confundirse con la fuente editorial del libro

La web debe evitar cualquier ambigüedad entre:
- obra;
- formato;
- edición bibliográfica;
- fuente técnica;
- ecosistema de investigación.

---

## 3. Arquitectura mínima recomendada del sitio

## 3.1. Página principal del libro
Debe incluir:

- título del libro;
- subtítulo o breve descripción;
- autores;
- compilador y redactor final;
- marco institucional;
- breve resumen del proyecto;
- botones visibles de acceso;
- bloque de licencia;
- estado del ISBN;
- enlace al repo LaTeX;
- espacio para créditos ampliados y equipo;
- fuente oficial.

## 3.2. Botones o llamadas de acción obligatorias
Debe haber al menos estos accesos principales:

- **Descargar PDF**
- **Leer o descargar Markdown**
- **Ver fuente LaTeX**
- **Ver créditos / equipo**
- opcionalmente: **Repositorios relacionados**

## 3.3. Sección “Formatos”
La web debe explicar con claridad:

### PDF
Edición oficial del libro.  
Actualmente circula como **edición preliminar oficial** con **ISBN en trámite**.

### Markdown
Versión textual abierta del libro, estructurada deliberadamente para facilitar lectura por inteligencias artificiales, navegación semántica y consulta parcial sin necesidad de cargar siempre la totalidad del manuscrito.

### Repositorio LaTeX
Fuente editorial del libro.  
No debe describirse como el repositorio general del proyecto de investigación.

## 3.4. Sección “Licencia”
Debe explicar:
- qué licencia tiene la obra;
- qué permite;
- que admite uso comercial;
- que exige atribución;
- que no autoriza sugerir aval de los autores o de Asociación Civil AlterMundi;
- que los materiales de terceros, si los hubiera, pueden quedar excluidos.

## 3.5. Sección “Créditos”
Debe distinguir con claridad:
- autores;
- compilador y redactor final;
- marco institucional;
- equipo de investigación y desarrollo.

---

## 4. Criterios obligatorios de presentación del ISBN

## 4.1. No inventar ISBN
Mientras no exista el número, no debe aparecer ningún número ficticio, marcador engañoso ni pseudocódigo.

## 4.2. Fórmula correcta
Mientras el número no haya sido asignado, la web debe usar una fórmula explícita como esta:

**ISBN:** en trámite  
**Estado de edición:** edición preliminar oficial de circulación

## 4.3. Ubicación recomendada
El estado del ISBN debe aparecer:
- cerca del bloque editorial del PDF;
- y, si existe una sección legal o de créditos ampliados, también allí.

## 4.4. Qué no hacer
No presentar:
- el PDF como “edición definitiva con ISBN”;
- el Markdown como si compartiera automáticamente el ISBN del PDF;
- el repositorio como si fuera la edición bibliográfica.

---

## 5. Criterios obligatorios de licencia

## 5.1. Denominación exacta
No usar solo “Creative Commons”.  
Debe figurar siempre:

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

## 5.2. Enlace
Siempre enlazar a:
<https://creativecommons.org/licenses/by/4.0/>

## 5.3. Resumen funcional de la licencia
La web debe explicar, en lenguaje humano, que:
- se permite copiar, compartir y adaptar;
- se permite uso comercial;
- se exige atribución;
- deben indicarse cambios;
- no debe sugerirse aval de autores o institución.

## 5.4. Recomendación técnica
Usar el bloque HTML/marcado estándar de Creative Commons en la web para favorecer legibilidad por máquinas y detección correcta de licencia por sistemas automáticos.

---

## 6. Textos listos para pegar

## 6.1. Texto editorial principal para la página del libro

**Harmonic Information Theory**  
**Autores:** Mariano Fernández Méndez y Nicolás Echániz  
**Compilador y redactor final:** Mariano Fernández Méndez  
**Marco institucional:** Asociación Civil AlterMundi

Esta obra se publica en acceso abierto y se distribuye bajo licencia **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
Puede compartirse, copiarse, redistribuirse, adaptarse y reutilizarse, incluso con fines comerciales, siempre que se reconozca adecuadamente la autoría, se enlace la licencia y se indiquen los cambios realizados.

**ISBN:** en trámite  
**Estado de edición:** edición preliminar oficial de circulación  
**Fuente oficial:** [URL OFICIAL]  
**Contacto:** [MAIL DE CONTACTO]

## 6.2. Texto corto junto al botón PDF

**PDF oficial**  
Edición preliminar oficial del libro.  
**ISBN:** en trámite.

## 6.3. Texto corto junto al botón Markdown

**Markdown abierto**  
Versión estructurada del libro para lectura abierta, consulta segmentada y navegación optimizada para sistemas automáticos e inteligencias artificiales.  
Esta versión no constituye la edición bibliográfica con ISBN.

## 6.4. Texto corto junto al repo LaTeX

**Repositorio LaTeX**  
Fuente editorial del libro.  
Contiene exclusivamente la fuente del libro y materiales editoriales asociados.

## 6.5. Texto para bloque de licencia

**Licencia:** CC BY 4.0  
Esta obra puede compartirse y adaptarse, incluso con fines comerciales, siempre que se reconozca adecuadamente la autoría, se indique si hubo cambios y no se sugiera aval de los autores o de Asociación Civil AlterMundi.  
<https://creativecommons.org/licenses/by/4.0/>

## 6.6. Texto para bloque de créditos ampliados

**Autores:** Mariano Fernández Méndez y Nicolás Echániz  
**Compilador y redactor final:** Mariano Fernández Méndez  
**Marco institucional:** Asociación Civil AlterMundi

**Equipo de investigación y desarrollo:**  
- Anabella Scigliano
- Federico Bonino
- Julián De La Reta
- Martín Fernández Méndez
- Pablo Bustos
- Saira Asua
- Santiago Cetrán
- Sofía Campagnoli

---

## 7. Criterios de tono y diseño

La web no debe sentirse como:
- un sitio comercial convencional;
- una landing vacía;
- ni una plataforma genérica de descarga.

Debe sentirse como:
- una publicación abierta y seria;
- una pieza editorial e intelectual;
- y un punto de acceso al libro y a su infraestructura abierta.

Se recomienda:
- tono sobrio;
- jerarquía tipográfica clara;
- buena separación entre autoría, institucionalidad y equipo;
- diferenciación visual entre PDF, Markdown y repo;
- y evitar toda ambigüedad legal.

---

## 8. Placeholders a completar

Dejar previstos estos campos:

- `[URL OFICIAL]`
- `[MAIL DE CONTACTO]`
- `abril 2026`
- eventualmente `Córdoba, Argentina`

---

## 9. Regla de actualización futura

Cuando se asigne el ISBN:
1. actualizar el número en la web;
2. actualizar el PDF oficial;
3. actualizar la documentación del repositorio;
4. mantener el Markdown sin ISBN propio, salvo decisión editorial futura en sentido contrario.

No modificar la lógica de fondo:
- el ISBN sigue perteneciendo a la edición PDF oficial;
- el Markdown sigue siendo una versión abierta complementaria.
