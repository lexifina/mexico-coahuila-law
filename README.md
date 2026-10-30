# Coahuila: law history in git

The law of the State of Coahuila (Estado Independiente, Libre y Soberano de Coahuila de Zaragoza, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-coa/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

192 ordenamientos with 1583 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO DE COAHUILA DE ZARAGOZA | 155 | as first published, then each reform: 22 February 1918 to 2 September 2026 |
| `codigo-civil/` | CODIGO CIVIL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 58 | as first published, then each reform: 28 June 1999 to 11 April 2026 |
| `codigo-de-procedimientos-familiares/` | CODIGO DE PROCEDIMIENTOS FAMILIARES PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 7 | as first published, then each reform: 12 June 2016 to 19 October 2019 |
| `codigo-electoral/` | CODIGO ELECTORAL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 32 | as first published, then each reform: 1 August 2016 to 1 September 2026 |
| `codigo-financiero-para-los-municipios/` | CODIGO FINANCIERO PARA LOS MUNICIPIOS DEL ESTADO DE COAHUILA DE ZARAGOZA | 10 | oldest version available, then each reform: 8 November 2013 to 9 January 2021 |
| `codigo-fiscal/` | CODIGO FISCAL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 19 | as first published, then each reform: 5 January 2004 to 29 December 2023 |
| `codigo-municipal/` | CODIGO MUNICIPAL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 94 | as first published, then each reform: 1 October 1999 to 20 May 2026 |
| `codigo-penal-de-coahuila-de-zaragoza/` | CODIGO PENAL DE COAHUILA DE ZARAGOZA | 68 | as first published, then each reform: 26 November 2017 to 20 May 2026 |
| `codigo-procesal-civil/` | CODIGO PROCESAL CIVIL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 31 | as first published, then each reform: 2 July 1999 to 19 October 2019 |
| `ley-apicola-y-de-proteccion-a-las-abejas-como-agentes-polini/` | LEY APICOLA Y DE PROTECCION A LAS ABEJAS COMO AGENTES POLINIZADORES PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 9 December 2023 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 44 | as first published, then each reform: 9 March 2016 to 20 May 2026 |
| `ley-de-adopciones-y-acogimiento-familiar/` | LEY DE ADOPCIONES Y ACOGIMIENTO FAMILIAR PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 21 October 2020 |
| `ley-de-adquisiciones-arrendamientos-y-contratacion-de-servic/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y CONTRATACION DE SERVICIOS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 11 | as first published, then each reform: 7 January 2009 to 13 February 2021 |
| `ley-de-aguas-para-los-municipios/` | LEY DE AGUAS PARA LOS MUNICIPIOS DEL ESTADO DE COAHUILA DE ZARAGOZA | 18 | as first published, then each reform: 25 February 2009 to 20 May 2026 |
| `ley-de-archivos-publicos/` | LEY DE ARCHIVOS PUBLICOS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 26 May 2007 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE COAHUILA DE ZARAGOZA | 13 | as first published, then each reform: 27 December 2017 to 20 May 2026 |
| `ley-de-asistencia-social-y-proteccion-de-derechos/` | LEY DE ASISTENCIA SOCIAL Y PROTECCION DE DERECHOS DEL ESTADO DE COAHUILA DE ZARAGOZA | 24 | as first published, then each reform: 28 April 2012 to 13 November 2024 |
| `ley-de-asociaciones-publico-privadas/` | LEY DE ASOCIACIONES PUBLICO PRIVADAS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 18 December 2019 to 20 March 2021 |
| `ley-de-camaras-de-agricultores-y-ganaderos/` | LEY DE CAMARAS DE AGRICULTORES Y GANADEROS DEL ESTADO DE COAHUILA | 3 | as first published, then each reform: 18 January 1951 to 11 April 1959 |
| `ley-de-camaras-de-la-propiedad-urbana/` | LEY DE CAMARAS DE LA PROPIEDAD URBANA PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 6 February 1957 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 9 December 2023 |
| `ley-de-cardioproteccion/` | LEY DE CARDIOPROTECCION DEL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 28 November 2018 to 20 May 2026 |
| `ley-de-ciencia-desarrollo-tecnologico-e-innovacion/` | LEY DE CIENCIA, DESARROLLO TECNOLOGICO E INNOVACION PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 5 | oldest version available, then each reform: 9 August 2017 to 9 December 2023 |
| `ley-de-condecoraciones-y-reconocimientos-al-valor-y-honor-de/` | LEY DE CONDECORACIONES Y RECONOCIMIENTOS AL VALOR Y HONOR DE LOS INTEGRANTES DE LAS FUERZAS DE SEGURIDAD PUBLICA DEL ESTADO DE COAHUILA DE ZARAGOZA Y SUS MUNICIPIOS | 2 | as first published, then each reform: 23 March 2013 to 26 June 2019 |
| `ley-de-condecoraciones-y-reconocimientos-del-congreso/` | LEY DE CONDECORACIONES Y RECONOCIMIENTOS DEL CONGRESO DEL ESTADO, INDEPENDIENTE, LIBRE Y SOBERANO DE COAHUILA DE ZARAGOZA (ANTES: LEY DE CONDECORACIONES Y RECONOCIMIENTOS DEL ESTADO DE COAHUILA DE ZARAGOZA) | 3 | as first published, then each reform: 10 April 2019 to 25 October 2023 |
| `ley-de-cooperacion-para-obras-publicas/` | LEY DE COOPERACION PARA OBRAS PUBLICAS DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 30 May 1990 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE COAHUILA | 4 | as first published, then each reform: 1 January 2008 to 9 May 2012 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE COAHUILA DE ZARAGOZA | 13 | as first published, then each reform: 18 June 2014 to 20 May 2026 |
| `ley-de-declaracion-especial-de-ausencia-para-personas-desapa/` | LEY DE DECLARACION ESPECIAL DE AUSENCIA PARA PERSONAS DESAPARECIDAS DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 29 May 2019 to 13 November 2024 |
| `ley-de-desarrollo-cultural/` | LEY DE DESARROLLO CULTURAL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 10 | as first published, then each reform: 30 April 2005 to 9 April 2022 |
| `ley-de-desarrollo-economico/` | LEY DE DESARROLLO ECONOMICO DEL ESTADO DE COAHUILA DE ZARAGOZA | 10 | as first published, then each reform: 31 December 2014 to 20 May 2026 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 9 December 2023 to 7 February 2026 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 22 October 2016 |
| `ley-de-ejecucion-de-sanciones-penales-y-reinsercion-social/` | LEY DE EJECUCION DE SANCIONES PENALES Y REINSERCION SOCIAL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 19 May 2013 to 22 October 2022 |
| `ley-de-entidades-paraestatales/` | LEY DE ENTIDADES PARAESTATALES DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 20 October 2012 |
| `ley-de-entrega-recepcion/` | LEY DE ENTREGA-RECEPCION DEL ESTADO Y MUNICIPIOS DE COAHUILA DE ZARAGOZA | 5 | as first published, then each reform: 30 April 2005 to 5 February 2020 |
| `ley-de-expropiacion-ocupacion-temporal-limitacion-de-dominio/` | LEY DE EXPROPIACION, OCUPACION TEMPORAL, LIMITACION DE DOMINIO Y SERVIDUMBRE ADMINISTRATIVA POR CAUSAS DE UTILIDAD PUBLICA PARA EL ESTADO DE COAHUILA | 1 | as first published: 3 March 2007 |
| `ley-de-filmaciones/` | LEY DE FILMACIONES DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 1 January 2014 |
| `ley-de-fomento-a-la-lectura-y-el-libro/` | LEY DE FOMENTO A LA LECTURA Y EL LIBRO PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 10 | as first published, then each reform: 16 February 2011 to 30 January 2021 |
| `ley-de-fomento-a-las-actividades-de-las-organizaciones-de-la/` | LEY DE FOMENTO A LAS ACTIVIDADES DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL EN EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 24 February 2021 |
| `ley-de-fomento-al-ahorro-de-los-servidores-publicos/` | LEY DE FOMENTO AL AHORRO DE LOS SERVIDORES PUBLICOS DEL ESTADO DE COAHUILA | 1 | as first published: 29 December 2007 |
| `ley-de-fomento-al-uso-racional-de-la-energia/` | LEY DE FOMENTO AL USO RACIONAL DE LA ENERGIA PARA EL ESTADO DE COAHUILA | 4 | as first published, then each reform: 14 July 2007 to 27 December 2017 |
| `ley-de-fomento-cooperativo/` | LEY DE FOMENTO COOPERATIVO DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 13 June 2012 to 27 December 2017 |
| `ley-de-ganaderia/` | LEY DE GANADERIA PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 29 February 2020 |
| `ley-de-gobiernos-de-coalicion/` | LEY DE GOBIERNOS DE COALICION DEL ESTADO COAHUILA DE ZARAGOZA | 1 | as first published: 13 May 2023 |
| `ley-de-hacienda/` | LEY DE HACIENDA PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 32 | as first published, then each reform: 1 January 2012 to 2 January 2026 |
| `ley-de-igualdad-entre-mujeres-y-hombres-en-el-estado-de-coah/` | LEY DE IGUALDAD ENTRE MUJERES Y HOMBRES EN EL ESTADO DE COAHUILA DE ZARAGOZA | 21 | as first published, then each reform: 1 June 2013 to 20 May 2026 |
| `ley-de-ingresos-del-municipio-de-acuna-coahuila-de-zaragoza/` | LEY DE INGRESOS DEL MUNICIPIO DE ACUÑA, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 26 December 2025 |
| `ley-de-ingresos-del-municipio-de-allende-coahuila-de-zaragoz/` | LEY DE INGRESOS DEL MUNICIPIO DE ALLENDE, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 26 December 2025 |
| `ley-de-ingresos-del-municipio-de-castanos-coahuila-de-zarago/` | LEY DE INGRESOS DEL MUNICIPIO DE CASTAÑOS, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 26 December 2025 |
| `ley-de-ingresos-del-municipio-de-francisco-i-madero-coahuila/` | LEY DE INGRESOS DEL MUNICIPIO DE FRANCISCO I. MADERO, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-frontera-coahuila-de-zarago/` | LEY DE INGRESOS DEL MUNICIPIO DE FRONTERA, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 26 December 2025 |
| `ley-de-ingresos-del-municipio-de-general-cepeda-coahuila-de/` | LEY DE INGRESOS DEL MUNICIPIO DE GENERAL CEPEDA, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 26 December 2025 |
| `ley-de-ingresos-del-municipio-de-hidalgo-coahuila-de-zaragoz/` | LEY DE INGRESOS DEL MUNICIPIO DE HIDALGO, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-jimenez-coahuila-de-zaragoz/` | LEY DE INGRESOS DEL MUNICIPIO DE JIMENEZ, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 26 December 2025 |
| `ley-de-ingresos-del-municipio-de-juarez-coahuila-de-zaragoza/` | LEY DE INGRESOS DEL MUNICIPIO DE JUAREZ, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-lamadrid-coahuila-de-zarago/` | LEY DE INGRESOS DEL MUNICIPIO DE LAMADRID, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-matamoros-coahuila-de-zarag/` | LEY DE INGRESOS DEL MUNICIPIO DE MATAMOROS, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-nava-coahuila-de-zaragoza-p/` | LEY DE INGRESOS DEL MUNICIPIO DE NAVA, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 26 December 2025 |
| `ley-de-ingresos-del-municipio-de-parras-coahuila-de-zaragoza/` | LEY DE INGRESOS DEL MUNICIPIO DE PARRAS, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 26 December 2025 |
| `ley-de-ingresos-del-municipio-de-piedras-negras-coahuila-de/` | LEY DE INGRESOS DEL MUNICIPIO DE PIEDRAS NEGRAS, COAHUILA DE ZARAGOZA, PARA EL EJERCICO FISCAL DEL AÑO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-sabinas-coahuila-de-zaragoz/` | LEY DE INGRESOS DEL MUNICIPIO DE SABINAS, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 26 December 2025 |
| `ley-de-ingresos-del-municipio-de-sacramento-coahuila-de-zara/` | LEY DE INGRESOS DEL MUNICIPIO DE SACRAMENTO, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-san-buenaventura-coahuila-d/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN BUENAVENTURA, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-san-juan-de-sabinas-coahuil/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN JUAN DE SABINAS, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-san-pedro-coahuila-de-zarag/` | LEY DE INGRESOS DEL MUNICIPIO DE SAN PEDRO, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-ingresos-del-municipio-de-viesca-coahuila-de-zaragoza/` | LEY DE INGRESOS DEL MUNICIPIO DE VIESCA, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-villa-union-coahuila-de-zar/` | LEY DE INGRESOS DEL MUNICIPIO DE VILLA UNION, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL DEL AÑO 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos-del-municipio-de-zaragoza-coahuila-de-zarago/` | LEY DE INGRESOS DEL MUNICIPIO DE ZARAGOZA, COAHUILA DE ZARAGOZA, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 29 December 2025 |
| `ley-de-ingresos/` | LEY DE INGRESOS PARA EL ESTADO DE COAHUILA DE ZARAGOZA PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 2 January 2026 |
| `ley-de-instituciones-y-asociaciones-de-beneficencia-privada/` | LEY DE INSTITUCIONES Y ASOCIACIONES DE BENEFICENCIA PRIVADA PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 28 October 2006 to 27 December 2017 |
| `ley-de-justicia-constitucional-local/` | LEY DE JUSTICIA CONSTITUCIONAL LOCAL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 13 July 2005 to 13 April 2019 |
| `ley-de-la-academia-interamericana-de-derechos-humanos-de-la/` | LEY DE LA ACADEMIA INTERAMERICANA DE DERECHOS HUMANOS DE LA UNIVERSIDAD AUTONOMA DE COAHUILA | 1 | as first published: 30 August 2017 |
| `ley-de-la-administracion-fiscal-general/` | LEY DE LA ADMINISTRACION FISCAL GENERAL DEL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 9 May 2012 to 27 December 2017 |
| `ley-de-la-comision-de-los-derechos-humanos/` | LEY DE LA COMISION DE LOS DERECHOS HUMANOS DEL ESTADO DE COAHUILA DE ZARAGOZA -ANTES LEY ORGANICA DE LA COMISION DE DERECHOS HUMANOS DEL ESTADO DE COAHUILA- | 7 | as first published, then each reform: 30 June 2007 to 15 August 2020 |
| `ley-de-la-comision-para-la-mediacion-conciliacion-y-arbitraj/` | LEY DE LA COMISION PARA LA MEDIACION, CONCILIACION Y ARBITRAJE MEDICO PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 27 December 2025 |
| `ley-de-la-direccion-de-pensiones-de-frontera-coahuila-de-zar/` | LEY DE LA DIRECCION DE PENSIONES DE FRONTERA, COAHUILA DE ZARAGOZA | 1 | as first published: 6 April 2016 |
| `ley-de-la-direccion-de-pensiones-de-monclova-coahuila-de-zar/` | LEY DE LA DIRECCION DE PENSIONES DE MONCLOVA, COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 6 April 2016 to 3 June 2016 |
| `ley-de-la-direccion-de-pensiones-de-piedras-negras-antes-ley/` | LEY DE LA DIRECCION DE PENSIONES DE PIEDRAS NEGRAS -ANTES LEY DE PENSIONES DE PIEDRAS NEGRAS -ANTES LEY DE LA DIRECCION DE PENSIONES DE PIEDRAS NEGRAS FRONTERA FUERTE, COAHUILA DE ZARAGOZA- | 3 | as first published, then each reform: 2 December 2015 to 29 May 2019 |
| `ley-de-la-promotora-para-el-desarrollo-rural-de-coahuila/` | LEY DE LA PROMOTORA PARA EL DESARROLLO RURAL DE COAHUILA | 6 | as first published, then each reform: 6 June 2001 to 27 December 2017 |
| `ley-de-la-unidad-de-cuenta/` | LEY DE LA UNIDAD DE CUENTA DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 26 September 2015 |
| `ley-de-los-derechos-de-las-personas-adultas-mayores/` | LEY DE LOS DERECHOS DE LAS PERSONAS ADULTAS MAYORES DEL ESTADO DE COAHUILA DE ZARAGOZA -ANTES LEY DE LAS PERSONAS ADULTAS MAYORES PARA EL ESTADO DE COAHUILA DE ZARAGOZA- | 37 | as first published, then each reform: 11 June 2005 to 30 August 2025 |
| `ley-de-los-derechos-de-los-seres-sintientes/` | LEY DE LOS DERECHOS DE LOS SERES SINTIENTES PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 9 December 2023 |
| `ley-de-medios-alternos-de-solucion-de-controversias/` | LEY DE MEDIOS ALTERNOS DE SOLUCION DE CONTROVERSIAS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 6 | as first published, then each reform: 13 July 2005 to 28 November 2018 |
| `ley-de-medios-de-impugnacion-en-materia-politico-electoral-y/` | LEY DE MEDIOS DE IMPUGNACION EN MATERIA POLITICO-ELECTORAL Y DE PARTICIPACION CIUDADANA PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 9 | as first published, then each reform: 19 November 2001 to 20 December 2024 |
| `ley-de-mejora-regulatoria/` | LEY DE MEJORA REGULATORIA PARA EL ESTADO DE COAHUILA DE ZARAGOZA Y SUS MUNICIPIOS | 1 | as first published: 8 July 2020 |
| `ley-de-nomenclatura-de-los-bienes/` | LEY DE NOMENCLATURA DE LOS BIENES DEL ESTADO DE COAHUILA DE ZARAGOZA Y DE SUS MUNICIPIOS | 1 | as first published: 18 January 2020 |
| `ley-de-obras-publicas-y-servicios-relacionados-con-las-misma/` | LEY DE OBRAS PUBLICAS Y SERVICIOS RELACIONADOS CON LAS MISMAS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 11 | as first published, then each reform: 7 January 2009 to 11 April 2026 |
| `ley-de-participacion-ciudadana/` | LEY DE PARTICIPACION CIUDADANA PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 5 | as first published, then each reform: 19 November 2001 to 11 July 2020 |
| `ley-de-paternidad-responsable/` | LEY DE PATERNIDAD RESPONSABLE DEL ESTADO DE COAHUIILA DE ZARAGOZA | 1 | as first published: 8 July 2020 |
| `ley-de-pensiones-complementarias-para-magistrados-y-jueces-d/` | LEY DE PENSIONES COMPLEMENTARIAS PARA MAGISTRADOS Y JUECES DEL PODER JUDICIAL DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 4 October 2014 |
| `ley-de-pensiones-del-municipio-de-cuatro-cienegas-coahuila-d/` | LEY DE PENSIONES DEL MUNICIPIO DE CUATRO CIENEGAS, COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 18 May 2016 to 18 December 2019 |
| `ley-de-pensiones-del-municipio-de-ramos-arizpe-coahuila-de-z/` | LEY DE PENSIONES DEL MUNICIPIO DE RAMOS ARIZPE, COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 30 December 2015 to 14 December 2019 |
| `ley-de-pensiones-del-municipio-de-zaragoza-coahuila-de-zarag/` | LEY DE PENSIONES DEL MUNICIPIO DE ZARAGOZA, COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 8 November 2017 to 14 December 2019 |
| `ley-de-pensiones-y-otros-beneficios-sociales-para-los-trabaj/` | LEY DE PENSIONES Y OTROS BENEFICIOS SOCIALES PARA LOS TRABAJADORES AL SERVICIO DEL ESTADO DE COAHUILA DE ZARAGOZA | 14 | as first published, then each reform: 25 August 1993 to 7 May 2022 |
| `ley-de-pensiones-y-otros-beneficios-sociales-para-los-trabaj-2/` | LEY DE PENSIONES Y OTROS BENEFICIOS SOCIALES PARA LOS TRABAJADORES DE LA EDUCACION PUBLICA DEL ESTADO DE COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 7 February 2016 to 30 July 2022 |
| `ley-de-planeacion-para-el-desarrollo/` | LEY DE PLANEACION PARA EL DESARROLLO DEL ESTADO DE COAHUILA DE ZARAGOZA | 7 | as first published, then each reform: 10 March 2012 to 27 November 2021 |
| `ley-de-poblacion-y-desarrollo-municipal/` | LEY DE POBLACION Y DESARROLLO MUNICIPAL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 12 September 2007 to 28 October 2020 |
| `ley-de-prestacion-de-servicios-para-la-atencion-cuidado-y-de/` | LEY DE PRESTACION DE SERVICIOS PARA LA ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL DEL ESTADO DE COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 1 December 2014 to 30 January 2021 |
| `ley-de-prevencion-del-suicidio/` | LEY DE PREVENCION DEL SUICIDIO PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 7 | as first published, then each reform: 10 April 2019 to 31 January 2024 |
| `ley-de-prevencion-asistencia-y-atencion-de-la-violencia-fami/` | LEY DE PREVENCION, ASISTENCIA Y ATENCION DE LA VIOLENCIA FAMILIAR | 14 | as first published, then each reform: 23 January 2003 to 29 November 2023 |
| `ley-de-procedimiento-administrativo/` | LEY DE PROCEDIMIENTO ADMINISTRATIVO PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 16 September 2007 to 22 November 2017 |
| `ley-de-procuracion-de-justicia/` | LEY DE PROCURACION DE JUSTICIA DEL ESTADO DE COAHUILA DE ZARAGOZA | 11 | as first published, then each reform: 17 May 2008 to 10 August 2016 |
| `ley-de-profesiones/` | LEY DE PROFESIONES PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 7 | as first published, then each reform: 7 November 1998 to 9 April 2022 |
| `ley-de-proteccion-a-la-maternidad-en-el-estado-de-coahuila/` | LEY DE PROTECCION A LA MATERNIDAD EN EL ESTADO DE COAHUILA | 8 | as first published, then each reform: 25 October 2008 to 20 May 2026 |
| `ley-de-proteccion-a-testigos-y-terceros-involucrados-en-el-p/` | LEY DE PROTECCION A TESTIGOS Y TERCEROS INVOLUCRADOS EN EL PROCESO PENAL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 7 January 2015 to 26 June 2019 |
| `ley-de-proteccion-civil/` | LEY DE PROTECCION CIVIL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 20 | as first published, then each reform: 15 May 2010 to 20 December 2025 |
| `ley-de-proteccion-de-datos-personales-en-posesion-de-sujetos/` | LEY DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DE COAHUILA DE ZARAGOZA | 1 | as first published: 28 June 2025 |
| `ley-de-proteccion-y-trato-digno-a-los-seres-sintientes/` | LEY DE PROTECCION Y TRATO DIGNO A LOS SERES SINTIENTES PARA EL ESTADO DE COAHUILA DE ZARAGOZA --ANTES: LEY DE PROTECCION Y TRATO DIGNO A LOS ANIMALES PARA EL ESTADO DE COAHUILA DE ZARAGOZA-- | 16 | as first published, then each reform: 30 November 2013 to 9 December 2023 |
| `ley-de-rendicion-de-cuentas-y-fiscalizacion-superior/` | LEY DE RENDICION DE CUENTAS Y FISCALIZACION SUPERIOR DEL ESTADO DE COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 23 September 2017 to 10 April 2021 |
| `ley-de-responsabilidad-ambiental/` | LEY DE RESPONSABILIDAD AMBIENTAL DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 27 November 2020 |
| `ley-de-responsabilidad-patrimonial/` | LEY DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO Y MUNICIPIOS DE COAHUILA DE ZARAGOZA | 1 | as first published: 1 March 2019 |
| `ley-de-responsabilidades-de-los-servidores-publicos-estatale/` | LEY DE RESPONSABILIDADES DE LOS SERVIDORES PUBLICOS ESTATALES Y MUNICIPALES DEL ESTADO DE COAHUILA DE ZARAGOZA | 11 | as first published, then each reform: 25 April 1984 to 14 August 2017 |
| `ley-de-salud-mental-y-bienestar-de-las-personas-con-trastorn/` | LEY DE SALUD MENTAL Y BIENESTAR DE LAS PERSONAS CON TRASTORNOS MENTALES PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 16 February 2021 |
| `ley-de-sociedades-mutualistas/` | LEY DE SOCIEDADES MUTUALISTAS DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 30 December 1950 to 27 December 2017 |
| `ley-de-transparencia-y-acceso-a-la-informacion-publica/` | LEY DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 28 June 2025 |
| `ley-de-transporte-y-movilidad-sustentable/` | LEY DE TRANSPORTE Y MOVILIDAD SUSTENTABLE PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 9 | as first published, then each reform: 11 November 2017 to 21 May 2025 |
| `ley-de-turismo/` | LEY DE TURISMO DEL ESTADO DE COAHUILA DE ZARAGOZA | 5 | as first published, then each reform: 28 December 2019 to 30 January 2021 |
| `ley-de-urgencias-medicas/` | LEY DE URGENCIAS MEDICAS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 5 | as first published, then each reform: 20 December 2014 to 13 February 2021 |
| `ley-de-victimas/` | LEY DE VICTIMAS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 12 | as first published, then each reform: 3 May 2014 to 13 November 2024 |
| `ley-de-vida-silvestre/` | LEY DE VIDA SILVESTRE PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 28 November 2020 |
| `ley-de-vigilancia-y-revision-de-medidas-cautelares/` | LEY DE VIGILANCIA Y REVISION DE MEDIDAS CAUTELARES PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 12 July 2014 to 27 December 2017 |
| `ley-de-vivienda/` | LEY DE VIVIENDA PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 13 | as first published, then each reform: 18 December 2010 to 20 May 2026 |
| `ley-del-centro-de-conciliacion-laboral/` | LEY DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 7 December 2019 to 10 July 2021 |
| `ley-del-colegio-coahuilense-de-investigaciones-historicas/` | LEY DEL COLEGIO COAHUILENSE DE INVESTIGACIONES HISTORICAS | 2 | as first published, then each reform: 19 March 1977 to 27 December 2017 |
| `ley-del-equilibrio-ecologico-y-la-proteccion-al-ambiente/` | LEY DEL EQUILIBRIO ECOLOGICO Y LA PROTECCION AL AMBIENTE DEL ESTADO DE COAHUILA DE ZARAGOZA | 29 | as first published, then each reform: 9 December 1998 to 7 February 2026 |
| `ley-del-fondo-de-la-vivienda-para-los-trabajadores-de-la-edu/` | LEY DEL FONDO DE LA VIVIENDA PARA LOS TRABAJADORES DE LA EDUCACION AL SERVICIO DEL ESTADO DE COAHUILA DE ZARAGOZA -ANTES LEY DEL FONDO DE LA VIVIENDA PARA LOS TRABAJADORES DE LA EDUCACION AL SERVICIO DEL ESTADO DE COAHUILA DE ZARAGOZA Y SUS MUNICIPIOS- | 5 | as first published, then each reform: 7 May 2011 to 14 December 2019 |
| `ley-del-instituto-coahuilense-de-las-personas-adultas-mayore/` | LEY DEL INSTITUTO COAHUILENSE DE LAS PERSONAS ADULTAS MAYORES | 9 | as first published, then each reform: 12 December 2001 to 30 August 2025 |
| `ley-del-instituto-de-becas-y-apoyos-financieros-para-la-educ/` | LEY DEL INSTITUTO DE BECAS Y APOYOS FINANCIEROS PARA LA EDUCACION DEL ESTADO DE COAHUILA | 4 | as first published, then each reform: 14 March 2001 to 13 November 2024 |
| `ley-del-instituto-estatal-de-defensoria-publica-de-coahuila/` | LEY DEL INSTITUTO ESTATAL DE DEFENSORIA PUBLICA DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 23 March 2013 to 26 June 2019 |
| `ley-del-instituto-registral-y-catastral/` | LEY DEL INSTITUTO REGISTRAL Y CATASTRAL DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 31 December 2020 |
| `ley-del-notariado/` | LEY DEL NOTARIADO DEL ESTADO DE COAHUILA | 14 | as first published, then each reform: 8 March 1979 to 30 December 2017 |
| `ley-del-organismo-publico-descentralizado-de-la-administraci/` | LEY DEL ORGANISMO PUBLICO DESCENTRALIZADO DE LA ADMINISTRACION MUNICIPAL DENOMINADO "DIRECCION DE PENSIONES Y BENEFICIOS SOCIALES PARA LOS TRABAJADORES AL SERVICIO DEL MUNICIPIO DE TORREON, COAHUILA | 4 | as first published, then each reform: 20 February 2016 to 14 December 2019 |
| `ley-del-procedimiento-contencioso-administrativo/` | LEY DEL PROCEDIMIENTO CONTENCIOSO ADMINISTRATIVO PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 12 August 2017 to 11 January 2020 |
| `ley-del-registro-civil/` | LEY DEL REGISTRO CIVIL PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 30 November 2018 to 23 November 2019 |
| `ley-del-seguro-de-los-trabajadores-de-la-educacion/` | LEY DEL SEGURO DE LOS TRABAJADORES DE LA EDUCACION DEL ESTADO DE COAHUILA | 4 | as first published, then each reform: 7 May 2011 to 14 December 2019 |
| `ley-del-servicio-medico-para-los-trabajadores-de-la-educacio/` | LEY DEL SERVICIO MEDICO PARA LOS TRABAJADORES DE LA EDUCACION DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 10 November 2018 to 14 December 2019 |
| `ley-del-sistema-anticorrupcion/` | LEY DEL SISTEMA ANTICORRUPCION DEL ESTADO DE COAHUILA DE ZARAGOZA | 7 | as first published, then each reform: 15 July 2017 to 23 November 2024 |
| `ley-del-sistema-de-informacion-estadistica-y-geografica/` | LEY DEL SISTEMA DE INFORMACION ESTADISTICA Y GEOGRAFICA DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 23 December 2009 to 28 November 2020 |
| `ley-del-sistema-de-seguridad-publica/` | LEY DEL SISTEMA DE SEGURIDAD PUBLICA DEL ESTADO DE COAHUILA DE ZARAGOZA | 9 | as first published, then each reform: 10 March 2016 to 28 June 2025 |
| `ley-del-sistema-estatal-para-la-garantia-de-los-derechos-hum/` | LEY DEL SISTEMA ESTATAL PARA LA GARANTIA DE LOS DERECHOS HUMANOS DE NIÑOS Y NIÑAS DEL ESTADO DE COAHUILA DE ZARAGOZA | 26 | as first published, then each reform: 19 March 2014 to 13 November 2024 |
| `ley-del-sistema-integral-de-justicia-para-adolescentes/` | LEY DEL SISTEMA INTEGRAL DE JUSTICIA PARA ADOLESCENTES DEL ESTADO DE COAHUILA DE ZARAGOZA | 5 | as first published, then each reform: 14 July 2014 to 22 October 2022 |
| `ley-en-materia-de-desaparicion-de-personas/` | LEY EN MATERIA DE DESAPARICION DE PERSONAS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 13 November 2024 |
| `ley-estatal-de-educacion-de-coahuila-de-zaragoza/` | LEY ESTATAL DE EDUCACION DE COAHUILA DE ZARAGOZA | 46 | as first published, then each reform: 29 May 1996 to 9 May 2026 |
| `ley-estatal-de-salud/` | LEY ESTATAL DE SALUD DEL ESTADO DE COAHUILA DE ZARAGOZA | 71 | as first published, then each reform: 2 August 1993 to 20 May 2026 |
| `ley-general-de-bienes/` | LEY GENERAL DE BIENES DEL ESTADO DE COAHUILA | 6 | as first published, then each reform: 7 September 1974 to 14 June 2014 |
| `ley-organica-de-la-administracion-publica/` | LEY ORGANICA DE LA ADMINISTRACION PUBLICA DEL ESTADO DE COAHUILA DE ZARAGOZA | 14 | as first published, then each reform: 20 December 2017 to 15 November 2025 |
| `ley-organica-de-la-fiscalia-general/` | LEY ORGANICA DE LA FISCALIA GENERAL DEL ESTADO DE COAHUILA DE ZARAGOZA | 5 | as first published, then each reform: 13 September 2017 to 28 June 2025 |
| `ley-organica-de-la-secretaria-de-seguridad-publica/` | LEY ORGANICA DE LA SECRETARIA DE SEGURIDAD PUBLICA DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 28 June 2025 to 27 December 2025 |
| `ley-organica-de-universidad-autonoma-de-coahuila/` | LEY ORGANICA DE UNIVERSIDAD AUTONOMA DE COAHUILA | 1 | as first published: 5 January 1991 |
| `ley-organica-del-congreso/` | LEY ORGANICA DEL CONGRESO DEL ESTADO INDEPENDIENTE LIBRE Y SOBERANO DE COAHUILA DE ZARAGOZA | 52 | as first published, then each reform: 1 January 2015 to 11 April 2026 |
| `ley-organica-del-organismo-publico-descentralizado-de-la-adm/` | LEY ORGANICA DEL ORGANISMO PUBLICO DESCENTRALIZADO DE LA ADMINISTRACION MUNICIPAL DENOMINADO "DIRECCION DE PENSIONES Y OTROS BENEFICIOS SOCIALES PARA LOS TRABAJADORES AL SERVICIO DEL MUNICIPIO DE SALTILLO" | 2 | as first published, then each reform: 17 July 1999 to 25 December 2013 |
| `ley-organica-del-organismo-publico-descentralizado-de-la-adm-2/` | LEY ORGANICA DEL ORGANISMO PUBLICO DESCENTRALIZADO DE LA ADMINISTRACION MUNICIPAL DENOMINADO DIRECCION DE PENSIONES Y OTROS BENEFICIOS SOCIALES PARA LOS TRABAJADORES AL SERVICIO DEL MUNICIPIO DE SALTILLO, COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 30 December 2015 to 14 December 2019 |
| `ley-organica-del-poder-judicial/` | LEY ORGANICA DEL PODER JUDICIAL DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 19 July 2025 |
| `ley-organica-del-tribunal-de-justicia-administrativa-de-coah/` | LEY ORGANICA DEL TRIBUNAL DE JUSTICIA ADMINISTRATIVA DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 12 August 2017 to 6 September 2022 |
| `ley-para-combatir-el-ruido-en-el-estado-de-coahuila-de-zarag/` | LEY PARA COMBATIR EL RUIDO EN EL ESTADO DE COAHUILA DE ZARAGOZA | 5 | as first published, then each reform: 17 October 2012 to 31 January 2024 |
| `ley-para-el-aprovechamiento-integral-de-alimentos-y-su-donac/` | LEY PARA EL APROVECHAMIENTO INTEGRAL DE ALIMENTOS Y SU DONACION ALTRUISTA DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 24 January 2018 |
| `ley-para-el-desarrollo-e-inclusion-de-las-personas-con-disca/` | LEY PARA EL DESARROLLO E INCLUSION DE LAS PERSONAS CON DISCAPACIDAD DEL ESTADO DE COAHUILA DE ZARAGOZA | 25 | as first published, then each reform: 30 June 2013 to 31 January 2024 |
| `ley-para-el-desarrollo-integral-de-la-juventud/` | LEY PARA EL DESARROLLO INTEGRAL DE LA JUVENTUD DEL ESTADO DE COAHUILA DE ZARAGOZA | 9 | as first published, then each reform: 29 October 2014 to 30 January 2021 |
| `ley-para-el-desarrollo-social/` | LEY PARA EL DESARROLLO SOCIAL DEL ESTADO DE COAHUILA DE ZARAGOZA | 8 | as first published, then each reform: 27 December 2017 to 13 November 2024 |
| `ley-para-el-fomento-a-la-gastronomia-en-el-estado-de-coahuil/` | LEY PARA EL FOMENTO A LA GASTRONOMIA EN EL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 10 April 2019 to 8 August 2020 |
| `ley-para-el-fomento-y-desarrollo-de-la-fruticultura-en-el-es/` | LEY PARA EL FOMENTO Y DESARROLLO DE LA FRUTICULTURA EN EL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 28 October 2006 to 27 December 2017 |
| `ley-para-el-impulso-emprendedor/` | LEY PARA EL IMPULSO EMPRENDEDOR DEL ESTADO DE COAHUILA DE ZARAGOZA | 10 | as first published, then each reform: 31 December 2014 to 20 May 2026 |
| `ley-para-el-impulso-y-desarrollo-de-la-actividad-vitivinicol/` | LEY PARA EL IMPULSO Y DESARROLLO DE LA ACTIVIDAD VITIVINICOLA DEL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 27 August 2016 to 23 October 2019 |
| `ley-para-jefas-de-familia/` | LEY PARA JEFAS DE FAMILIA DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 8 July 2020 |
| `ley-para-la-administracion-de-bienes-asegurados-abandonados/` | LEY PARA LA ADMINISTRACION DE BIENES ASEGURADOS, ABANDONADOS O DECOMISADOS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 23 February 2015 to 26 June 2019 |
| `ley-para-la-distribucion-de-participaciones-y-aportaciones-f/` | LEY PARA LA DISTRIBUCION DE PARTICIPACIONES Y APORTACIONES FEDERALES A LOS MUNICIPIOS DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 2 January 2026 |
| `ley-para-la-donacion-altruista-de-alimentos-y-su-fomento-en/` | LEY PARA LA DONACION ALTRUISTA DE ALIMENTOS Y SU FOMENTO EN EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 15 February 1997 |
| `ley-para-la-emision-y-seguimiento-de-las-medidas-de-protecci/` | LEY PARA LA EMISION Y SEGUIMIENTO DE LAS MEDIDAS DE PROTECCION PARA MUJERES EN SITUACION DE VIOLENCIA DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 9 January 2021 to 20 May 2026 |
| `ley-para-la-familia-de-coahuila-de-zaragoza/` | LEY PARA LA FAMILIA DE COAHUILA DE ZARAGOZA | 24 | as first published, then each reform: 12 June 2016 to 31 January 2024 |
| `ley-para-la-implementacion-de-los-sistemas-de-pensiones-de-l/` | LEY PARA LA IMPLEMENTACION DE LOS SISTEMAS DE PENSIONES DE LOS MUNICIPIOS DEL ESTADO COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 4 October 2014 to 3 October 2015 |
| `ley-para-la-implementacion-seguimiento-y-evaluacion-del-sist/` | LEY PARA LA IMPLEMENTACION, SEGUIMIENTO Y EVALUACION DEL SISTEMA DE JUSTICIA PENAL ACUSATORIO Y ORAL EN EL ESTADO DE COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 20 October 2012 to 26 June 2019 |
| `ley-para-la-inclusion-y-garantia-de-los-derechos-de-las-pers/` | LEY PARA LA INCLUSION Y GARANTIA DE LOS DERECHOS DE LAS PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 25 January 2017 |
| `ley-para-la-integracion-y-funcionamiento-de-las-juntas-munic/` | LEY PARA LA INTEGRACION Y FUNCIONAMIENTO DE LAS JUNTAS MUNICIPALES DE MEJORAMIENTO, MORAL CIVICO Y MATERIAL, DEL ESTADO DE COAHUILA | 1 | as first published: 17 December 1957 |
| `ley-para-la-localizacion-e-identificacion-forense-de-persona/` | LEY PARA LA LOCALIZACION E IDENTIFICACION FORENSE DE PERSONAS DEL ESTADO DE COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 21 December 2016 to 28 November 2020 |
| `ley-para-la-prevencion-social-de-la-violencia-y-la-delincuen/` | LEY PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA, CON PARTICIPACION CIUDADANA DEL ESTADO DE COAHUILA DE ZARAGOZA -ANTES LEY PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA, DEL ESTADO DE COAHUILA DE ZARAGOZA- | 4 | as first published, then each reform: 9 April 2012 to 30 January 2021 |
| `ley-para-la-prevencion-y-combate-a-la-pobreza-extrema-en-el/` | LEY PARA LA PREVENCION Y COMBATE A LA POBREZA EXTREMA EN EL ESTADO DE COAHUILA DE ZARAGOZA | 6 | as first published, then each reform: 30 November 2013 to 22 October 2022 |
| `ley-para-la-prevencion-y-gestion-integral-de-residuos/` | LEY PARA LA PREVENCION Y GESTION INTEGRAL DE RESIDUOS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 6 | as first published, then each reform: 2 March 2006 to 13 December 2025 |
| `ley-para-la-prevencion-atencion-y-combate-del-sobrepeso-y-la/` | LEY PARA LA PREVENCION, ATENCION Y COMBATE DEL SOBREPESO Y LA OBESIDAD PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 15 October 2016 to 8 August 2020 |
| `ley-para-la-prevencion-atencion-y-control-del-acoso-escolar/` | LEY PARA LA PREVENCION, ATENCION Y CONTROL DEL ACOSO ESCOLAR PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 7 | as first published, then each reform: 14 November 2015 to 9 December 2023 |
| `ley-para-la-prevencion-deteccion-y-combate-de-incendios-fore/` | LEY PARA LA PREVENCION, DETECCION Y COMBATE DE INCENDIOS FORESTALES EN EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 8 November 2025 |
| `ley-para-la-prevencion-proteccion-atencion-y-asistencia-a-la/` | LEY PARA LA PREVENCION, PROTECCION, ATENCION Y ASISTENCIA A LAS VICTIMAS Y OFENDIDOS DE LOS DELITOS EN MATERIA DE TRATA DE PERSONAS DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 21 November 2012 to 26 June 2019 |
| `ley-para-la-proteccion-de-las-personas-defensoras-de-derecho/` | LEY PARA LA PROTECCION DE LAS PERSONAS DEFENSORAS DE DERECHOS HUMANOS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 10 August 2016 to 26 June 2019 |
| `ley-para-la-proteccion-de-las-y-los-periodistas/` | LEY PARA LA PROTECCION DE LAS Y LOS PERIODISTAS PARA EL ESTADO DE COAHUILA DE ZARAGOZA | 4 | as first published, then each reform: 19 July 2014 to 5 December 2020 |
| `ley-para-la-proteccion-de-los-no-fumadores-en-el-estado-de-c/` | LEY PARA LA PROTECCION DE LOS NO FUMADORES EN EL ESTADO DE COAHUILA | 11 | as first published, then each reform: 2 June 2007 to 11 April 2026 |
| `ley-para-la-proteccion-y-promocion-de-los-derechos-del-contr/` | LEY PARA LA PROTECCION Y PROMOCION DE LOS DERECHOS DEL CONTRIBUYENTE DEL ESTADO DE COAHUILA DE ZARAGOZA | 2 | as first published, then each reform: 10 May 2017 to 19 October 2024 |
| `ley-para-la-regulacion-de-establecimientos-privados-para-la/` | LEY PARA LA REGULACION DE ESTABLECIMIENTOS PRIVADOS PARA LA ATENCION A LAS ADICCIONES DEL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 7 February 2026 |
| `ley-para-la-regulacion-de-la-venta-y-consumo-de-alcohol-en-e/` | LEY PARA LA REGULACION DE LA VENTA Y CONSUMO DE ALCOHOL EN EL ESTADO DE COAHUILA DE ZARAGOZA | 16 | as first published, then each reform: 19 September 2012 to 4 October 2025 |
| `ley-para-la-regulacion-de-los-albergues-publicos-y-privados/` | LEY PARA LA REGULACION DE LOS ALBERGUES PUBLICOS Y PRIVADOS DEDICADOS AL CUIDADO Y ATENCION DE PERSONAS ADULTAS MAYORES EN EL ESTADO DE COAHUILA DE ZARAGOZA | 1 | as first published: 18 November 2020 |
| `ley-para-la-transferencia-de-funciones-y-servicios-publicos/` | LEY PARA LA TRANSFERENCIA DE FUNCIONES Y SERVICIOS PUBLICOS DEL ESTADO A LOS MUNICIPIOS PARA EL ESTADO DE COAHUILA | 1 | as first published: 18 March 2005 |
| `ley-para-prevenir-y-sancionar-la-tortura-en-el-estado-de-coa/` | LEY PARA PREVENIR Y SANCIONAR LA TORTURA EN EL ESTADO DE COAHUILA DE ZARAGOZA | 3 | as first published, then each reform: 12 July 2014 to 28 November 2020 |
| `ley-para-prevenir-y-sancionar-las-practicas-de-corrupcion-en/` | LEY PARA PREVENIR Y SANCIONAR LAS PRACTICAS DE CORRUPCION EN LOS PROCEDIMIENTOS DE CONTRATACION PUBLICA DEL ESTADO DE COAHUILA DE ZARAGOZA Y SUS MUNICIPIOS | 2 | as first published, then each reform: 20 October 2012 to 27 December 2017 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Monterrey, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication, the state rule SCJN cites.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
