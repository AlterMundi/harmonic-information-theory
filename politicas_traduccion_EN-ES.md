# Políticas de traducción EN-ES para HIT

> Estado: v1.1, 2026-05-28
> Jerarquía normativa: `DIRECTIVAS_HERMENEUTICAS.md` y `DIRECTIVAS_EDITORIALES_ALTERMUNDI.md` prevalecen en lo hermenéutico y epistemológico. Este archivo fija solo decisiones lingüísticas y de traducción.

## 1. Alcance y función

Este archivo fija las decisiones de base para la traducción del manuscrito `Harmonic_Information_Theory_Foundations.md` al archivo `Hamonic_Information_Theory_Foundations_ES.md`.

El archivo en inglés es la fuente canónica de lectura, contraste y verificación. No se edita. El archivo en español es el texto de trabajo.

Estas políticas no reemplazan la revisión línea por línea del original. Ordenan el trabajo para que esa revisión no derive en inconsistencias terminológicas, sintácticas u ortotipográficas.

## 2. Variante de español y criterio de lector

La variante de destino es **español rioplatense culto, sin marcas locales fuertes**.

La base normativa es panhispánica, pero la resolución editorial del libro no será neutra artificial. Cuando el castellano admita varias soluciones igualmente correctas, se preferirá la que resulte natural en un registro culto rioplatense sin caer en coloquialismos locales.

## 3. Registro, tono e interpelación

El registro del libro en español debe ser **académico, preciso y legible**. El inglés del original es conceptualmente denso pero no pomposo; la traducción debe conservar esa virtud. No se autoriza barroquizar el texto por el solo hecho de que el español académico admita períodos más largos o mayor nominalización.

La traducción prioriza claridad argumental, continuidad lógica y precisión conceptual. Cuando una formulación literal suene opaca, dura o artificial en castellano, debe reformularse sin alterar el sentido.

En el **texto expositivo** se evita la interpelación directa al lector. Si aparece interpelación en prólogos, prefacios o paratextos conversacionales, la forma elegida es **vos** rioplatense culto. No se mezclan `vos`, `tú`, `usted` ni formas pseudo-neutras dentro de una misma obra.

## 4. Principio de traducción para texto teórico

Para HIT rige, por defecto, una política de **equivalencia formal** antes que equivalencia dinámica. Esto significa preservar:

- la estructura conceptual de las distinciones;
- el orden argumental cuando sea significativo;
- las recurrencias terminológicas;
- las marcas textuales de definición, contraste o énfasis;
- las referencias internas del manuscrito.

Esto no autoriza calcos sintácticos. Se preserva la forma conceptual, no la rigidez inglesa de la oración.

## 5. Ortotipografía y convenciones editoriales

La traducción se escribe en **español editorial normal**, con tildes, eñes y ortografía completa. El uso de ASCII puede servir de contingencia técnica en otros frentes del repo, pero **no es la norma editorial del libro**.

Decisiones de base:

- **Mayúsculas en títulos y encabezados**: solo la primera palabra y los nombres propios, no `Title Case`. Aplica también al título del libro: `Teoría armónica de la información: fundamentos`.
- **Cursivas y negritas**: se conservan las jerarquías del original salvo que una convención española mejor justificada exija ajuste puntual.
- **Comillas**: norma RAE. Jerarquía `«…»` primarias, `"…"` secundarias, `'…'` terciarias. La pasada de normalización ortotipográfica debe aplicarla en todo el archivo ES.
- **Notas del traductor**: se usarán solo cuando hagan falta, marcadas como `[N. del T.]`. Aparecen tanto en el archivo Markdown público como en la edición LaTeX/PDF.
- **Bibliografía**: las referencias se conservan en su forma original; no se hispanizan los datos bibliográficos.
- **Números decimales**: para HIT se fija **punto decimal**, por convivencia con fórmulas, notación científica y bibliografía internacional.
- **Separador de miles**: punto (`1.600`), consistente con el uso castellano y con la convención ya aplicada en el archivo.
- **Espaciado**: no se deja espacio antes de `:`, `;`, `?` ni `!`. No después del paréntesis de apertura ni antes del de cierre.
- **Guiones**: `—` para incisos, `–` para rangos numéricos, `-` para palabras compuestas.
- **URLs, código y nombres técnicos**: sin traducir (`Markdown`, `LaTeX`, `PDF`, `ISBN`, `CC BY 4.0`, software, formatos).

## 6. Estructura y paratextos

Debe preservarse siempre la estructura Markdown del original:

- encabezados y niveles de encabezado;
- negritas, cursivas y citas en bloque;
- listas y sublistas;
- separadores;
- arquitectura editorial del front matter;
- índice estructural;
- referencias internas.

Los paratextos bibliográficos y catalográficos se revisan con el mismo rigor que el cuerpo principal. No deben perderse numeraciones, marcas de lista, énfasis ni información editorial.

## 7. Citas textuales y referencias bibliográficas

- **Citas textuales de otras obras incorporadas al cuerpo del libro**: traducir al castellano. Si el original de la cita está en idioma distinto al inglés (alemán, francés, griego, latín u otro), conservar el original entre comillas y agregar traducción castellana al pie con `[N. del T.]`.
- **Cuando la cita en inglés tenga implicancia terminológica fuerte**, agregar entre paréntesis el término original en cursiva en su primera aparición.
- **Bibliografía y lista de referencias**: tal como están en el original. No se hispaniza el orden autor/año/título ni se traducen títulos de obras citadas.
- **Notas a pie de página del autor**: se traducen como cualquier otro texto.

## 8. Neologismos, términos clave y glosario maestro

Los términos centrales de HIT no se resolverán de manera improvisada párrafo por párrafo. Toda decisión relevante debe asentarse en un **glosario maestro** dentro de este archivo.

Regla de decisión para neologismos o términos propios del marco:

1. verificar si existe uso estabilizado en español en la literatura pertinente;
2. si no existe, decidir entre traducir, calcar o conservar en inglés;
3. sostener esa decisión de manera consistente;
4. registrar la decisión y su justificación breve en el glosario.

Cuando el término siga abierto, debe registrarse como abierto antes de seguir multiplicando variantes en el texto.

### Glosario maestro

| Término EN | Término ES | Estado | Nota |
|---|---|---|---|
| Harmonic Information Theory | Teoría armónica de la información | cerrado | Título del marco y de la obra (sentence case). Sigla `HIT` se mantiene en inglés en todo el libro castellano. |
| HIT | HIT | cerrado | Sigla del marco. Se conserva en inglés en el cuerpo del texto castellano por consistencia con bibliografía internacional, paper Phideus y comunidad académica. |
| Harmonic Beacon | Harmonic Beacon | cerrado | Nombre propio del dispositivo. Se mantiene en inglés. Cursiva en primera aparición de cada capítulo. Sin sigla castellana. |
| Personal Myth Projection | Proyección del Mito Personal | cerrado | Se traduce al castellano. La sigla `PMP` se mantiene en todo el libro. Primera aparición de cada capítulo expone forma extendida + sigla. |
| Harmonically Aware Technology | Tecnología armónicamente consciente | cerrado | Se traduce al castellano en la primera aparición de cada capítulo y se acompaña con la sigla `HAT` en inglés. Después, solo `HAT`. |
| Phideus | Phideus | cerrado | Nombre propio del programa experimental. Sin cursiva. Sin traducir. |
| Jpsh! | Jpsh! | cerrado | Marca corporal/expresiva del autor. Cursiva preservada. |
| ratio | proporción | cerrado | No traducir como `razón` en contextos teóricos o musicales, salvo necesidad matemática explícita. |
| probe | sonda | cerrado | Mantener salvo contexto muy excepcional. |
| patterned relation | patrones relacionales | cerrado | Decisión 2026-05-28. Reemplaza decisión previa (`relación pautada`). Aplicar en toda revisión hacia atrás. |
| legibility | legibilidad / volver legible | abierto | Resolver según contexto; evitar rigidez cuando el sustantivo opaque la frase. Soluciones alternativas: `inscribir en forma legible`, `hacer legible`. |
| field | campo | abierto | Puede requerir glosa contextual en pasajes físicos, acústicos o teóricos densos. |
| constraint | restricción | cerrado | Mantener salvo que la sintaxis exija expansión. |
| harmonic information | información armónica | provisional | Término central del marco; mantener así salvo conflicto en capítulos posteriores. |
| harmonic organization | organización armónica | provisional | Traducción de trabajo. |
| harmonic field | campo armónico | provisional | Revisar cuando aparezca desarrollo técnico más fino. |
| harmonic configuration | configuración armónica | provisional | Traducción de trabajo. |
| working conceptual synthesis | Síntesis conceptual de trabajo | cerrado | Ya aparece en el manuscrito. |
| inscription | inscripción | cerrado | Sentido foucaultiano/derridiano. No `escritura`. |
| recurrence | recurrencia | cerrado | Sentido técnico (dinámica, información). No `repetición`. |
| coupling | acoplamiento | cerrado | Sentido físico y biológico. |
| consonance | consonancia | cerrado | Sentido técnico musical y ampliado HIT. |
| disharmony | disarmonía | cerrado | En HIT NO es sinónimo de `disonancia`. |
| claim | afirmación | cerrado | En contexto `central claim`, `afirmación central`. NO `claim` ni `reclamo`. |
| escalon (sic) | escalón | cerrado | Conservado en español. |
| descriptor | descriptor | cerrado | Término técnico Phideus. |
| arm | brazo (experimental) | cerrado | Sentido experimental. |
| gate | gate | cerrado | Sin traducir. Término técnico Phideus consolidado. |

## 9. Criterios sintácticos y de estilo

Patrones que deben vigilarse de manera sistemática:

- evitar pasivas inglesas calcadas cuando el español admita una solución mejor con activa o pasiva refleja;
- evitar sujetos pronominales innecesarios;
- evitar posesivos ingleses cuando el castellano pide artículo;
- evitar anglicismos sintácticos en gerundios, adjetivación y conectores;
- explicitar conectores cuando la yuxtaposición inglesa suene entrecortada en español;
- no conservar frases que solo se entiendan bien con el original al lado.

En pasajes de alta densidad retórica, revisar especialmente construcciones del tipo:

- `make available`;
- `what follows`;
- `gathered itself`;
- `strike once`;
- `carried into legibility`;
- `do more than [verbo]`;
- `across widely separated [sustantivo]`;
- `annex the rest`.

La consigna es simple: si la literalidad endurece la frase, se reformula.

## 10. Cognados falsos y adverbios calcados

Tabla de vigilancia para la pasada léxica y la revisión sintáctica.

| EN | Trampa típica | Forma correcta según contexto |
|---|---|---|
| actually | actualmente | en realidad, de hecho |
| eventually | eventualmente | finalmente, con el tiempo |
| consistent | consistente (denso) | coherente, sistemático |
| sensitive | sensitivo | sensible |
| evidence | evidencia (en sentido tribunal) | indicios, prueba, datos, evidencia (cuidado con el matiz) |
| realize | realizar | darse cuenta, advertir |
| assume | asumir | suponer, presuponer |
| support | soportar | sostener, apoyar, fundamentar |
| substantial | sustancial | considerable, importante |
| relevant | relevante (que destaca) | pertinente, atinente |
| ultimately | últimamente | en última instancia |
| effective | efectivo (dinero) | eficaz, eficiente |
| significant | significante | significativo |
| approach (a topic) | aproximar | abordar, enfocar |
| address (a problem) | direccionar | abordar, tratar |
| genuinely | genuinamente | realmente, de manera sustantiva |
| theory (uso laxo) | teoría | hipótesis, conjetura (según contexto) |

**Adverbios en `-ly`**: no traducir automáticamente con `-mente`. `genuinely`, `essentially`, `naturally`, `effectively`, `actually` rara vez piden el adverbio correspondiente en castellano académico.

## 11. Líneas rojas

- **Vocabulario de rigor, no de disciplina** (directiva hermenéutica HIT 2026-03-31). No usar `disciplina`, `disciplinado`, `disciplinario` como sinónimos automáticos de seriedad, cientificidad o buena práctica. Cuando corresponda nombrar esa cualidad, preferir `rigor`, `precisión`, `claridad epistemológica`, `trazabilidad`, `control metodológico`, `cuidado experimental`, `consistencia`, `seriedad`. Sí se admite `disciplinario/disciplinaria` cuando refiere a campos del saber, no a la cualidad.
- **No introducir metadiscurso adicional**. Si el EN tiene una frase argumental, la traducción la entrega como frase argumental. No agregar anuncios del tipo `en esta sección veremos`, `a continuación se presenta`, etc., que no estén en el original.
- **No suavizar contradicciones del autor**. Si el EN afirma con fuerza, la traducción afirma con fuerza. No introducir hedge donde el original no lo tiene.
- **No reificar lo Real**. La traducción debe respetar la distinción estricta entre `lo Real` y `la realidad` cuando aparezca, sin deslizar hacia formulaciones de acceso transparente al objeto.
- **No traducir nombres propios de proyectos, dispositivos o personas** salvo decisión registrada en el glosario.
- **No mezclar `vos`, `tú` y `usted`** dentro del libro.

## 12. Workflow de traducción y revisión

El trabajo sobre el libro debe seguir estas capas, en este orden:

1. lectura del original en paralelo al tramo a traducir o revisar;
2. primer borrador o corrección de contenido;
3. revisión terminológica contra glosario;
4. revisión sintáctica y de fluidez en español;
5. revisión ortotipográfica;
6. cotejo final línea por línea con el original;
7. lectura en voz alta de los pasajes más densos;
8. auditoría cruzada Codex ↔ Claude cuando esté disponible.

No se considera cerrada una sección solo porque su sentido general sea correcto. Debe estar resuelta también en terminología, sintaxis y forma editorial.

## 13. Pasada de normalización pendiente sobre el archivo ES

Antes de seguir traduciendo capítulos nuevos, debe ejecutarse una pasada sobre las 242 líneas ya traducidas del archivo `Hamonic_Information_Theory_Foundations_ES.md` que aplique:

- el nuevo título del libro en sentence case (`Teoría armónica de la información: fundamentos`) en H1, atribución sugerida, ficha CIP, página legal;
- corrección de los calcos sintácticos identificados en la auditoría 2026-05-28 (líneas 230, 232, 233, 235, 242);
- normalización terminológica de `patterned relation` → `patrones relacionales` (donde apareciera `relación pautada`);
- aplicación del criterio de comillas RAE allí donde aparezcan comillas;
- revisión léxica contra la tabla de cognados falsos.

La actualización del título del libro en castellano debe propagarse también a la edición LaTeX, a la página legal, al sitio web y a la ficha CIP del PDF como decisión editorial separada.

## 14. Política de actualización

Si aparece una duda relevante de traducción, debe registrarse aquí junto con la decisión adoptada.

Si una decisión cambia, el cambio debe quedar asentado explícitamente con fecha. No se permite deriva silenciosa de términos centrales, ortotipografía o variante de español.

Antes de emprender una normalización amplia del archivo `Hamonic_Information_Theory_Foundations_ES.md`, estas políticas deben considerarse vigentes y suficientes como base de esa pasada.
