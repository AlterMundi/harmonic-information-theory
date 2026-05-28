# Teoría armónica de la información: fundamentos

**Autores**: Mariano Fernández Méndez, Nicolás Echániz
**Compilación y redacción final**: Mariano Fernández Méndez
**Marco institucional**: Esta obra fue desarrollada y publicada en el marco institucional de la Asociación Civil AlterMundi.
**Equipo de investigación y desarrollo**: Anabella Scigliano Mattiauda, Federico Bonino, Javier Jorge, Julián De La Reta, Martín Fernández Méndez, Pablo Bustos, Saira Asua, Samanta Lañin, Santiago Rodríguez Cetrán, Sofía Campagnoli
**Primera edición digital**
**Lugar y fecha de edición**: José de la Quintana, Córdoba, Argentina — 2026
**Editorial y domicilio legal**: Asociación Civil AlterMundi — A. Las Acacias 0, S:U205 M:68, José de la Quintana, 5189, Córdoba, Argentina
**Fuente oficial**: https://hit.altermundi.net
**Contacto**: editorial@altermundi.net

© 2026 Mariano Fernández Méndez y Nicolás Echániz

Salvo que se indique expresamente lo contrario, el contenido original de esta obra está licenciado bajo **Creative Commons Atribución 4.0 Internacional (CC BY 4.0)** — https://creativecommons.org/licenses/by/4.0/. Usted es libre de copiar, redistribuir, compartir, adaptar, remezclar, transformar y crear a partir de esta obra en cualquier medio o formato, incluso con fines comerciales, siempre que otorgue el crédito correspondiente a los autores, proporcione un enlace a la licencia, indique si se realizaron cambios y no sugiera que los autores o la Asociación Civil AlterMundi respaldan su uso o versión derivada, salvo autorización expresa.

Este archivo Markdown es una versión abierta complementaria oficial de la misma obra. El ISBN de la edición bibliográfica oficial en PDF es **978-631-91761-0-0**.

**Atribución sugerida:**
Fernández Méndez, Mariano, y Nicolás Echániz. *Teoría armónica de la información: fundamentos*. José de la Quintana, Córdoba, Argentina: AlterMundi, 2026. ISBN 978-631-91761-0-0. https://hit.altermundi.net.
Compilación y redacción final: Mariano Fernández Méndez.
Marco institucional: Asociación Civil AlterMundi.
Licencia: CC BY 4.0.

**ISBN de la edición bibliográfica oficial en PDF**: 978-631-91761-0-0.
La edición bibliográfica oficial en PDF corresponde a la primera edición digital del libro. Este archivo Markdown sigue siendo una versión abierta complementaria y no constituye un producto bibliográfico independiente con ISBN propio.

**Formatos y edición oficial:**
La edición bibliográfica oficial del libro es el **PDF**. La versión Markdown y el repositorio LaTeX forman parte del ecosistema abierto de publicación y trabajo del libro, pero no constituyen por sí mismos la edición bibliográfica con ISBN.

**Materiales de terceros:**
Las imágenes, gráficos, fotografías, tablas, citas extensas o cualquier otro material identificado como perteneciente a terceros quedan excluidos de esta licencia, salvo que se indique expresamente lo contrario, y conservan sus respectivos términos de uso.

**Permisos especiales, prensa y consultas institucionales:**
editorial@altermundi.net

**Catalogación en la publicación (fuente):**
Fernández Méndez, Mariano.
*Teoría armónica de la información : fundamentos* / Mariano Fernández Méndez ; Nicolás Echániz ; Contribuciones de Anabella Scigliano Mattiauda ... [et al.]. - 1a ed. - José de la Quintana : AlterMundi, 2026.
Libro digital, PDF.
Archivo Digital: descarga.
Creada PARCIALMENTE con IA / Claude (Anthropic), Codex/OpenAI.
ISBN 978-631-91761-0-0.

1. Armonía. 2. Filosofía de la Información. 3. Ciencias de la Información. I. Scigliano Mattiauda, Anabella, colab. II. Título.
CDD 600.

**Agradecimientos**

Los experimentos computacionales del programa Phideus informados en este libro consumieron más de 1.600 horas-núcleo en el clúster Mendieta (nodos NVIDIA A30) durante 2026. Esta obra utilizó recursos computacionales de UNC Supercómputo (CCAD) – Universidad Nacional de Córdoba (https://supercomputo.unc.edu.ar), que forman parte de SNCAD, República Argentina.

---

## ÍNDICE ESTRUCTURAL

> **Para navegación por LLM.** Este manuscrito contiene una introducción, 16 capítulos en 6 partes, más 6 apéndices (~68.900 palabras). El índice siguiente asigna cada encabezado a su número de línea. Cuando se trabaje con un capítulo específico, use los números de línea para leer solo la sección pertinente, en lugar de cargar el archivo completo.

- **Introducción** (L216)

- **Capítulo 1. La tendencia** (L237)
- **Capítulo 2. El problema de la dispersión disciplinaria** (L263)
- **Capítulo 3. Ontología de la información armónica** (L297)
  - 3.1 La información como patrón, no solo como cantidad (L305)
  - 3.2 Por qué la relación puede ser ontológicamente primaria (L319)
  - 3.3 El intervalo como portador informacional mínimo (L351)
  - 3.4 Una proposición ontológica mínima para HIT (L365)
- **Capítulo 4. La consonancia como función relacional** (L375)
  - 4.1 Contra la esencia aislada de la proporción (L385)
  - 4.2 La consonancia como estabilidad dinámica más que como perfección rígida (L397)
  - 4.3 Armonía natural y armonía temperada (L413)
  - 4.4 Cada sistema físico tiene su propia armonía natural (L425)
  - 4.5 Una proposición relacional mínima sobre la consonancia (L435)
- **Capítulo 5. Hipótesis centrales de HIT** (L443)
  - 5.1 Por qué el marco requiere una jerarquía de afirmaciones (L451)
  - 5.2 H1 y H2: los puntos de apoyo empíricos (L459)
  - 5.3 H3 y H6: estructura compartida y portadores invariantes (L469)
  - 5.4 H4 y H5: las conjeturas principales (L481)
  - 5.5 Estado, falsadores y las próximas pruebas decisivas (L495)
- **Capítulo 6. Convergencia empírica: un mapa del estado del arte** (L522)
  - 6.1 Neurociencia: resonancia, acoplamiento y organización neural (L530)
  - 6.2 Psicoacústica y percepción tonal (L548)
  - 6.3 Ecología acústica y biosemiótica (L558)
  - 6.4 Sistemas dinámicos, recurrencia y sincronización (L570)
  - 6.5 Evidencia comparativa, transcultural e histórica (L586)
  - 6.6 Información, predicción y organización de procesos (L596)
  - 6.7 Bioelectricidad y organización biológica más allá de la audición (L606)
  - 6.8 Lo que sabe cada campo y lo que cada campo pasa por alto (L614)
- **Capítulo 7. Marco epistemológico y metodológico** (L636)
  - 7.1 Qué tipo de conocimiento produce HIT (L644)
  - 7.2 Ciencia, poder y los límites de la formalización (L656)
  - 7.3 Una epistemología de la inconsistencia (L666)
  - 7.4 Las redes neuronales como instrumentos científicos (L680)
  - 7.5 La rectificación: armonía natural y armonía perceptual (L688)
  - 7.6 El arsenal metodológico de Beacon (L698)
  - 7.7 La arquitectura de la evidencia (L706)
- **Capítulo 8. La armonía natural como eficiencia informacional** (L716)
  - 8.1 De la proporción a la recurrencia (L724)
  - 8.2 Recurrencia informativa y reducción de la carga correctiva (L752)
  - 8.3 Eficiencia informacional y organización viviente (L766)
  - 8.4 La biosfera y semiosfera de la recurrencia (L778)
  - 8.5 Una proposición mínima para HIT (L790)
- **Capítulo 9. El sentido de la consonancia** (L800)
  - 9.1 De la eficiencia a la orientación viviente (L808)
  - 9.2 Consonancia, afecto y facilidad predictiva (L820)
  - 9.3 Disarmonía, sobrecarga y extrañamiento (L830)
  - 9.4 Pareidolia armónica y polifonía humana (L840)
  - 9.5 La consonancia como acoplamiento estructural (L850)
  - 9.6 La consonancia como referencia orientadora (L866)
- **Capítulo 10. El problema de la activación** (L878)
  - 10.1 El problema de leer sin escribir (L888)
  - 10.2 El carácter matemático de phi (L900)
  - 10.3 Tres líneas convergentes (L926)
  - 10.4 El *Jpsh!* como evento formal (L936)
  - 10.5 Qué cambia esto y qué no cambia (L942)
  - 10.6 Estado y direcciones abiertas (L952)
- **Capítulo 11. Phideus: la sonda computacional** (L972)
  - 11.1 La pregunta y por qué necesitaba una máquina (L976)
  - 11.2 Diseño experimental: cuatro escalones, una lógica (L1006)
  - 11.3 Qué cuenta como descriptor en Phideus (L1033)
  - 11.4 Cómo ingresan los descriptores en el modelo: el mecanismo como variable (L1080)
  - 11.5 El resultado central: el aprendizaje transmodal guiado por descriptores funciona (L1112)
  - 11.6 El segundo frente: habla y electroglotografía (L1145)
  - 11.7 El descubrimiento: la representación organiza la geometría (L1153)
  - 11.8 Phideus como proceso constructivo (L1163)
  - 11.9 Implicancias experimentales de la conjetura de activación (L1171)
- **Capítulo 12. Harmonic Beacon: la sonda experiencial** (L1179)
  - 12.1 Qué es Harmonic Beacon (L1183)
  - 12.2 Principio de funcionamiento: el campo gravitacional armónico (L1197)
  - 12.3 Evolución del dispositivo (L1233)
  - 12.4 Cuatro líneas experimentales (L1251)
  - 12.5 Personal Myth Projection (L1275)
  - 12.6 La conjunción PMP y Beacon: ensamblaje teórico y observaciones (L1285)
  - 12.7 HAT: tecnología armónicamente consciente (L1299)
- **Capítulo 13. Convergencia Phideus-Beacon** (L1313)
  - 13.1 Dos perspectivas sobre la misma hipótesis (L1317)
  - 13.2 El bucle de retroalimentación: cómo cada sonda informa a la otra (L1325)
  - 13.3 El triángulo: computacional, fisiológico, psicológico (L1337)
  - 13.4 Visión: una red de Beacons, un paisaje de armonía (L1347)
- **Capítulo 14. Qué no es HIT** (L1357)
- **Capítulo 15. Preguntas abiertas y agenda de investigación** (L1379)
  - 15.1 Por qué se necesita una agenda ahora (L1387)
  - 15.2 Preguntas inmediatas y próximos pasos programáticos (L1393)
  - 15.3 Phideus más allá de los frentes actuales (L1401)
  - 15.4 Beacon y PMP+Beacon: de la observación al protocolo (L1411)
  - 15.5 Formalización y tecnología de largo horizonte (L1423)
- **Capítulo 16. Aplicaciones y derivaciones** (L1433)
  - 16.1 Qué significa aquí una derivación (L1441)
  - 16.2 Derivaciones instrumentales cercanas: salud, fisiología, ecología (L1447)
  - 16.3 Derivaciones tecnológicas y computacionales (L1455)
  - 16.4 Biomecánica e infraestructura material (L1467)
  - 16.5 Derivaciones culturales, artísticas y educativas (L1475)
  - 1.1 Resonancia neural y percepción armónica (L1491)
  - 1.2 Psicoacústica y consonancia (L1505)
  - 1.3 Ecología acústica y biosemiótica (L1517)
  - 1.4 Sistemas dinámicos y recurrencia (L1527)
  - 1.5 Percepción entre especies (L1549)
  - 2.1 Teoría de la información (L1564)
  - 2.2 Filosofía del proceso y relacionalismo (L1574)
  - 2.3 Autopoiesis y enacción (L1591)
  - 2.4 Principio de energía libre y eficiencia (L1613)
  - 2.5 Interdisciplinariedad y zonas de intercambio (L1622)
  - 3.1 Consonancia, disonancia y percepción tonal (L1635)
  - 3.2 Afinación justa y temperamento (L1647)
  - 3.3 Etnomusicología y tradiciones armónicas (L1655)
  - 3.4 Arqueoacústica y evidencia prehistórica (L1671)
  - 3.5 Estudios transculturales y pareidolia (L1680)
  - 4.1 Recurrencia y estabilidad dinámica (L1692)
  - 4.2 Landauer, costo energético y computación (L1701)
  - 4.3 Fractales, proporción áurea y autoorganización (L1710)
  - 4.4 Activación, recuperación y sustrato matemático (L1718)
  - 5.1 Neurociencia de la recompensa musical (L1732)
  - 5.2 Musicoterapia y efectos restaurativos (L1742)
  - 5.3 Entrainment y estados alterados (L1752)
  - 5.4 Teoría polivagal y regulación autonómica (L1760)
  - 5.5 Bioelectricidad, biología cuántica y señalización oscilatoria (L1767)
  - 6.1 Phideus: aprendizaje transmodal y representaciones (L1789)
  - 6.2 Phideus: mecanismos de inyección y condicionamiento (L1813)
  - 6.3 Harmonic Beacon: acústica instrumental y resonancia (L1823)
  - 6.4 Harmonic Beacon: bioseñales y retroalimentación (L1837)
  - 6.5 Phideus: figuras de Lissajous y aprendizaje transmodal audiovisual (L1845)
  - 6.6 Psicología analítica, psicodrama y Personal Myth Projection (L1862)
  - 7.1 Estudios críticos (L1881)
  - 7.2 Falsabilidad y controles negativos (L1890)
  - 7.3 Diferenciación respecto de la pseudociencia y límites (L1898)
  - 7.4 Referencias de contexto y uso interno (L1908)
  - 7.5 Epistemología crítica y metodológica (L1916)
- **Apéndice A. Glosario** (L1946)
- **Apéndice B. Resultados experimentales** (L2080)
  - B.1 Cómo leer este apéndice (L2084)
  - B.2 Escalón 1 - Resultados cerrados canónicos (L2090)
  - B.3 Escalón 1 - Ramas retrospectivas omitidas del capítulo principal (L2134)
  - B.4 Escalón 2 - Inventario nulo completo y por descriptor-mecanismo (L2168)
- **Apéndice C. Especificaciones técnicas** (L2205)
  - C.1 Cómo leer este apéndice (L2209)
  - C.2 Familias de descriptores (L2213)
  - C.3 Variantes de mecanismo (L2231)
  - C.4 Brazos canónicos (L2248)
  - C.5 Esqueletos arquitectónicos y convenciones de forma (L2280)
  - C.6 Protocolos de evaluación (L2296)
- **Apéndice D. Cronología del proyecto** (L2309)
  - D.1 Cómo leer esta cronología (L2313)
  - D.2 De la intuición del problema a la arquitectura del programa (L2317)
  - D.3 Cronología de Phideus (L2323)
  - D.4 Cronología de Beacon (L2345)
  - D.5 Cronología de la convergencia (L2368)
  - D.6 Corte presente (L2383)
- **Apéndice E. Sustrato matemático de la activación armónica** (L2387)
  - E.1 Por qué se separa el sustrato formal (L2391)
  - E.2 Extremalidad de Hurwitz y fracciones continuas (L2446)
  - E.3 Equidistribución y el problema de las tres distancias (L2494)
  - E.4 KAM y el toro de media áurea (L2555)
  - E.5 Operadores cuasiperiódicos y la línea casi Mathieu (L2587)
  - E.6 Números nobles, salvedad de mayor dimensionalidad y el Lema de Activación Armónica (L2636)
  - E.7 Convergencias externas (L2697)
- **Apéndice F. Síntesis conceptual de trabajo** (L2717)
  - F.1 Formulación general (L2721)
  - F.2 Lo que no se está proponiendo (L2727)
  - F.3 Hipótesis central (L2733)
  - F.4 La armonía natural como estabilidad dinámica (L2739)
  - F.5 Información: definición operacional (L2747)
  - F.6 Almacenamiento, recurrencia y entropía (L2753)
  - F.7 Activación, consulta y recuperación (L2761)
  - F.8 Eficiencia energética y costo de procesamiento (L2769)
  - F.9 Del sistema físico al sistema interpretante (L2777)
  - F.10 Caos organizado y estabilidad recurrente (L2783)
  - F.11 Hipótesis del nicho acústico, biosemiosfera y homeostasis espiritual (L2787)

## Introducción

En dominios muy distantes entre sí, los patrones relacionales no se limitan a acompañar los acontecimientos; contribuyen a estabilizarlos. Los sistemas oscilatorios se asientan en regímenes preferidos, los procesos acoplados se sincronizan o casi se sincronizan bajo restricciones simples, y las señales se vuelven más legibles cuando su organización interna no es arbitraria. Proporción, resonancia, recurrencia, interferencia y estructura modal reaparecen allí donde la materia, los organismos y los sistemas interpretativos deben mantener coherencia sin rigidez. Lo que al principio parece una familia de regularidades locales comienza gradualmente a parecer un fenómeno distribuido: algunas relaciones no se limitan a describir la organización a posteriori; participan en volverla disponible.

La física, la neurociencia, la psicoacústica, la dinámica no lineal, la ecología, la biosemiótica y la computación encuentran cada una ese fenómeno bajo sus propios vocabularios, escalas e instrumentos. Ninguna de ellas lo agota. Ninguna puede validarlo para todas las demás. Sin embargo, la recurrencia se vuelve difícil de tratar como accidental cuando patrones relacionales similares siguen reapareciendo allí donde los sistemas deben coordinar, discriminar, comprimir o permanecer inteligibles bajo el cambio. La pregunta pendiente, por lo tanto, no es si una disciplina puede absorber a las demás, sino si un objeto ha sido encontrado repetidamente sin haber sido ensamblado adecuadamente como objeto de indagación.

El nombre propuesto para ese objeto es Teoría armónica de la información. La propuesta no descansa en la armonía como ornamento, residuo estético o metafísica nostálgica de la proporción. Descansa en una afirmación más acotada y más exigente: algunas organizaciones armónicas pueden funcionar como restricciones informacionales. Vuelven más disponible la estructura detectable, reducen la carga descriptiva y correctiva, y producen diferencias funcionales recurrentes para sistemas que deben registrar, almacenar, interpretar o responder. En este sentido, la recurrencia no es mera repetición. Es una de las formas en que se estabiliza la legibilidad. Un campo se vuelve informacional aquí no simplemente porque algo ocurra dentro de él, sino porque los patrones relacionales cambian lo que puede ser captado, retenido y llevado a la acción.

Una propuesta de este tipo solo conserva su seriedad si sus afirmaciones están estratificadas desde el comienzo. Algunas partes del argumento se apoyan en convergencias ya visibles en literaturas establecidas. Otras avanzan un paso más y coordinan esas convergencias en inferencias más fuertes. Otras permanecen explícitamente conjeturales, por fértiles que puedan resultar para el programa que sigue. Esta jerarquía no es un gesto de cautela agregado para guardar las apariencias. Pertenece al método mismo. Un campo no se funda declarando que sus posibilidades más fuertes ya han sido demostradas; se funda distinguiendo qué ha sido observado, qué ha sido inferido y qué permanece lo bastante abierto como para que una indagación posterior pueda alterar realmente su estatuto.

La misma exigencia metodológica gobierna el papel de los instrumentos. Las redes neuronales, los modelos computacionales y los dispositivos acústicos aparecen aquí no como ornamentos de la modernidad ni como puntos de acceso privilegiados a la realidad. Son sondas construidas. Intervienen, registran y exponen relaciones bajo condiciones controladas; ayudan a producir escenarios controlados dentro de los cuales una afirmación puede volverse más precisa, más débil o volver a ponerse a prueba. Phideus y el Harmonic Beacon pertenecen al manuscrito exactamente en este sentido. No resuelven la ontología por decreto. Amplían el rango de inscripción a través del cual pueden formularse preguntas explícitas sobre la organización armónica.

Una figura adicional pertenece al argumento, aunque su tratamiento completo llega más adelante. Hay momentos en que una perturbación breve no impone orden desde afuera, sino que libera una organización ya latente en un medio. Los capítulos posteriores dan un nombre a ese acontecimiento: *Jpsh!* La palabra es corporal y un poco indócil, pero apunta a algo exacto. Ciertos reconocimientos no llegan ni como deducción ni como revelación, sino como liberación restringida bajo presión acumulada. El proyecto fue tomando forma en ese registro: no como una doctrina acabada en busca de ejemplos, sino como un patrón que se volvió más difícil de ignorar a medida que la evidencia convergente siguió presionando más allá de los vocabularios destinados a contenerla.

Lo que sigue comienza con una tendencia, entra en el problema de la dispersión, construye una ontología de la relación, se orienta hacia la consonancia, ordena sus hipótesis, examina un estado convergente del conocimiento, replantea la eficiencia y la orientación, alcanza el problema de la activación y solo entonces llega a las sondas mediante las cuales la propuesta se somete a una exposición controlada. La afirmación central es exigente pero delimitada: bajo condiciones especificables, las relaciones armónicas pueden actuar como restricciones privilegiadas sobre la estabilidad, el acoplamiento, la interpretabilidad y la economía informacional a través de dominios que todavía carecen de un lenguaje común para ellas. Esa es también la razón por la cual el apéndice *Síntesis conceptual de trabajo* puede servir como una segunda entrada a este libro. Comience allí, deje que esa condensación produzca su impacto una vez, luego vuelva al Capítulo 1 y avance en secuencia. Leído de ese modo, el apéndice puede producir un *Jpsh!* abductivo: una activación de lo que está latente en la estructura del libro mismo, de modo que los capítulos puedan leerse como el despliegue de una forma ya inscripta en una configuración legible.
