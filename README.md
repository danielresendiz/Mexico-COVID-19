# Base de datos de casos de COVID-19 reportados en México / Database of reported cases of COVID-19 in Mexico.

Última actualización/Last update: 2020-12-14T20:43:48-06:00

## Nota importantes / Important notes

2020-11-28: A partir del día de ayer, 2020-11-27, se incluyen pruebas de antígeno en la clasificación de casos sospechosos y positivos en los datos abiertos.

2020-11-28: From yesterday (2020-11-27) onward, the open data includes antigen tests in the classification of suspect and positive cases.

2020-10-08: Las entradas en la tabla resumen difieren de los datos en los CTDs los días 2020-10-05 y 2020-10-06 debido a un cambio de metodología en la forma de dictaminar un caso confirmado de COVID-19.
Éste cambio se refleja en los datos abiertos, usados para construir la tabla resumen, a partir de 2020-10-07, por lo que los datos del CTD y de la tabla resumen coinciden de nuevo a partir de 2020-10-07.

2020-10-08: The entries in the briefing table differ from the data in the CTDs of 2020-10-05 and 2020-10-06 due to a change in metodology in determining a confirmed case of COVID-19.
This change is reflected in the open data, used to construct the briefing table, from 2020-10-07 onwards, so the data from the CTD and those of the briefing table match again from 2020-10-07 onwards.

2020-09-23: Los CTDs también son archivados históricamente de forma oficial.
El enlace se lista en el directorio de los mismos.
Adicionalmente, desde el 2020-08-25 ha habido un cambio en la definición de caso sospechoso.
El comunicado correspondiente se encuentra en la carpeta principal de los CTDs.

2020-09-23: The CTDs are also historically archived in an official page.
The link is in the main CTD directory.
Additionally, on 2020-08-25 the definition of suspect case was changed.
The communiqué describing this is in hte main CTD directory.

2020-07-21: He automatizado más la forma en la que construyo los paquetes de actualizaciones de las fuentes oficiales.
Desafortunadamente, el servidor de CONACyT bloqueó mi computadora debido a la automatización que adicioné para descargar los reportes.
Esto provocó que las actualizaciones de CONACyT del 2020-07-17 hasta 2020-07-21T22:31:04-05:00 fueran sólo para la fecha del directorio y no incluyeran nuevos reportes.
He descargado los reportes manualmente el día de hoy, y tendré más cuidado con la forma en la que son actualizados en el futuro.

2020-07-21: I've further automatized the way I build the update packages from the official sources.
Unfortunately, CONACyT's server flagged my computer due to the automation I included to download their reports.
This provoked that the CONACyT updates from 2020-07-17 to 2020-07-21T22:31:04-05:00 were just for the date itself and did not include the reports.
I've downloaded the reports manually today, and will be more mindful of how they're updated in the future.

2020-06-19: Todas mis contribuciones previas, presentes y futuras son liberadas bajo la licencia MIT.
@rodrigolece ha también liberado sus contribuciones a este repositorio bajo los mismos términos. (https://github.com/carranco-sga/Mexico-COVID-19/pull/7#issuecomment-636704565).
Esta licencia no aplica a ningún documento o información oficial archivada u ofrecida aquí, dado que pueden estar distribuídas o pudieron haber sido distribuídas bajo sus propias licencias.
Esto libera todas las aportaciones originales bajo la licencia MIT.

2020-06-19: All my prior, current and future contributions on this repository are being released under the MIT License.
@rodrigolece has kindly freed his contributions to this repository under the MIT license, too. (https://github.com/carranco-sga/Mexico-COVID-19/pull/7#issuecomment-636704565).
This license doesn't apply to any kind of official information or documents archived or mirrored here, since they are being or might have been distributed under their own licenses.
This releases all our original contributions under the MIT license.

2020-06-11: Los datos de la tabla `Mexico_COVID19_CTD.csv` discrepan estatalmente de los datos presentados en otras plataformas (por ejemplo [el dashboard oficial](https://coronavirus.gob.mx/datos/)), supongo, al menos desde el 2020-04-19.
Esto se debe a una *diferencia de procedimiento* a la forma de considerar los casos a partir de los datos abiertos.
La tabla mantenida en este repositorio se clasifica por *la entidad de la unidad de atención médica*, mientras que los datos del dashboard oficial se clasifica por *la entidad de residencia del paciente*.
El archivo `Comparativa_RES_UM.jl` muestra un ejemplo de la dos formas para su comparación.
Hasta dónde se mencione lo contrario, se seguirá manteniendo la clasificación por la entidad de la unidad médica de atención en el repositorio.
*Muchas gracias a Luis G. Canales por su observación.*

2020-06-11: The data of the table `Mexico_COVID19_CTD.csv`
isn't equal (by state) to the data presented in other platforms (such as the [official dashboard](https://coronavirus.gob.mx/datos/).)
This difference dates back, I suppose, at least to 2020-04-19.
This is due to a *difference in procedure* when classifying the data from the open data.
The table maintained in this repository is classified by the *state of the medical unit attending the case*, meanwhile, in the offical dashboard the data is classified by *state of residence of the patient*.
The file `Comparativa_RES_UM.jl` shows an example of the two methods so they may be compared.
*Special thanks to Luis G. Canales for his observation.*

2020-06-01: A partir del 2020-06-01 se dejan de transcribir las tablas de datos de defunciones en el CTD dado que esta información se reporta en los datos abiertos y la tabla resumen.
Se sigue archivando el CTD.

2020-06-01: From 2020-06-01 onwards, the tables of deaths in the CTD won't be transcribed since this information is reported in the open data and in the briefing table.
The CTD will be still be archived.

2020-05-26: El número de muertes en Coahuila reportado el día de hoy en los datos del CTD es una unidad menor al reportado ayer.
Este cambio también se refleja en los datos abiertos.

2020-05-26: The number of deaths in Coahuila reported today in the CTD is one unit less than the one reported yesterday.
This change also occurs in the open data.

2020-05-24: El número de muertes en Morelos reportado el día de hoy en los datos del CTD es dos unidades menor al reportado ayer.
Este cambio también se refleja en los datos abiertos.

2020-05-24: The number of deaths in Morelos reported today in the CTD is two units less than the one reported yesterday.
This change also occurs in the open data.

2020-05-06: Las bases de datos abiertas a partir del 24 de abril contienen algunos errores de codificación. (La forma en la que se tratan cosas como acentos.)
[rodrigolece](https://github.com/rodrigolece) y su equipo ([mexicovid19](https://github.com/mexicovid19)) publican las bases de datos con las correciones pertinentes para homogeneizar la codificación [aquí](https://github.com/mexicovid19/Mexico-datos/tree/master/datos_abiertos/raw).
Asimismo, han publicado las instrucciones para realizar las correciones [aquí](https://github.com/mexicovid19/Mexico-datos#c%C3%B3digo).
En el repositorio actual el archivo de bases de datos se mantiene de la forma en la que se publican oficialmente.
*Muchas gracias a Rodrigo por su observación y por compartir la solución.*

2020-05-06: The open databases from April 24 onward contain some encoding errors. (The way things like accents and diacritics are dealt with.)
[rodrigolece](https://github.com/rodrigolece) and his team ([mexicovid19](https://github.com/mexicovid19)) publish the databases with the respective corrections to homogenize the encoding [here](https://github.com/mexicovid19/Mexico-datos/tree/master/datos_abiertos/raw).
Additionally, they published the instructions to make the corrections [here](https://github.com/mexicovid19/Mexico-datos#c%C3%B3digo).
In the present repository the archive of databases is maintained in the way they're officially published.
*Special thanks to Rodrigo for his observation and for sharing the solution.*

2020-05-05: (Nota respecto a los datos de 2020-04-14.)
La base de datos abiertos de esta fecha al parecer contiene registrados más casos negativos que los reportados en el CTD.
Sin embargo, el número de casos positivos y sospechosos parece concordar.
Mario Romero [explica](https://github.com/mariorz/covid19-mx-time-series/wiki/Incidentes-encontrados-en-la-base-de-datos-DGE%E2%80%93COVID19) esto más a detalle.
*Gracias a Mario Romero por su comentario.*
(Una disculpa a todos por la tardanza en hacer la nota.)

2020-05-05: (Note regarding the data of 2020-04-14.)
The open database of this date apparently registers more negative cases than those reported in the CTD.
However, the number of positive and suspect cases seems to match.
Mario Romero [explains](https://github.com/mariorz/covid19-mx-time-series/wiki/Incidentes-encontrados-en-la-base-de-datos-DGE%E2%80%93COVID19) this more thoroughly.
*Thanks to Mario Romero for his comment.*
(A sincere apology to all for the delay in registering this note.)

2020-05-03: El número de muertes en Guerrero reportado el día de hoy en los datos del CTD es una unidad menor al reportado ayer.
Este cambio también se refleja en los datos abiertos.

2020-05-02: The number of deaths in Guerrero reported today in the CTD is one unit less than the one reported yesterday.
This change also occurs in the open data.

2020-05-02: El número de muertes en Coahuila reportado el día de hoy en los datos del CTD es una unidad menor al reportado ayer.
Este cambio también se refleja en los datos abiertos.

2020-05-02: The number of deaths in Coahuila reported today in the CTD is one unit less than the one reported yesterday.
This change also occurs in the open data.

2020-04-23: El CTD tiene un mapa de casos acumulados similar al reportado inicialmente, sin embargo, los datos de la tabla resumen se siguen actualizando con la información de los datos abiertos.
El número de muertes en Hidalgo reportado el día de hoy en los datos del CTD es una unidad menor al reportado ayer.
Este cambio también se refleja en los datos abiertos.

2020-04-23: The CTD includes a map of the accumulated cases similar to the one reported initially, however, the data of the briefing table is being updated with the information of the open data.
The number of deaths in Hidalgo reported today in the CTD is one unit less than the one reported yesterday.
This change also occurs in the open data.

2020-04-21: El CTD vuelve a tener un mapa con casos activos (con inicio de síntomas en los últimos 14 días) y la tabla de defunciones por estado.
La tabla de defunciones se vuelve a transcribir, sin embargo, la tabla resumen se actualiza con la información de los datos abiertos.

2020-04-21: The CTD again includes a map with active cases (those with initial symptoms date in the last 14 days) and the table of number of deaths by state.
The table of deaths by state is transcribed, however, the information of the briefing table is updated with the open data.

2020-04-20: La SSa aparentemente ha deprecado publicar la información de casos sospechosos, positivos y defunciones por estado de la forma en la que lo hacía.
La información ahora se reporta en forma abierta en forma de archivos `.csv`. (Cf. `Open_data`)
El último par de días, la información en la tabla resumen se ha obtenido de los datos abiertos.
Proximamente espero reemplazar esta por una tabla aún más desglosada, que está en proceso de construcción.

2020-04-20: The SSa has aparently deprecated publishing the information of suspect and positive cases along the number of deceased by state in the way it used to.
The information is now published as open data, as a `.csv` table. (Cf. `Open_data`)
The last couple of days, the infomation of the briefing table has been obtained from the open data.
Soon I expect to replace the old briefing table by one containing further information. It is currently being built.

2020-04-20 El día de ayer, 2020-04-19, la SSa no publicó tablas de casos sospechosos ni confirmados de la forma en la que se hizo desde marzo.
Para completar la tabla resumen se usaron los datos abiertos del día.

2020-04-20 Yesterday, 2020-04-19, the SSa did not publush tables of suspect and confirmed cases as it has been done since March.
To complete the briefing table the open data database of the day was used.


## Español
En este respositorio se busca archivar y poner en un formato más accesible la información oficial publicada por la Secretaría de Salud Federal de México. (SSa)

Actualmente se *archivan* tres tipos de documentos:

- **Diario**: Los Comunicados Técnicos Diarios (CTD) y las tablas de casos positivos y sospechosos que le [acompañan](https://www.gob.mx/salud/documentos/coronavirus-covid-19-comunicado-tecnico-diario-238449).
(Los CTD se archivan en `CTD/Documents` desde el primero que se tiene registro, el 2020-01-23. Las tablas se archivan desde el 2020-03-14 en `CTD/Tablas_casos`. Se conoce que existieron tablas publicadas antes, pero [no están disponibles](https://github.com/carranco-sga/Mexico-COVID-19/issues/1).)
- **Diario**: Los datos abiertos publicados por la SSa sobre los pacientes confirmados y sospechosos de COVID-19 [aquí](https://www.gob.mx/salud/documentos/datos-abiertos-152127) en `Open_data/COVID-19`.
- **Esporádicamente**: (Hay actualizaciones no archivadas aquí.) Archivos de la SSa respecto a vigilancia epideimiológica publicados [aquí](https://www.gob.mx/salud/documentos/aviso-epidemiologico-casos-de-infeccion-respiratoria-asociados-a-nuevo-coronavirus-2019-ncov) en ``Aviso_Epidemiológico``.

Para facilitar el uso de los datos:

- **Diario**: Se vacían las tablas de casos del CTD (positivos, sospechosos y fallecidos por entidad) a formato `.csv`.
Los archivos se encuentran en `CTD/Scraped_data`.
- **Diario**: Se actualiza la tabla resumen histórica (a modo de serie de tiempo) `Mexico_COVID19_CTD.csv` con casos confirmados, sospechosos y defunciones por entidad.
(La descripción de los campos se encuentra en `CTD/README.md`.)
- **En caso necesario**: Se agregan notas sobre consideraciones y discrepancias de los datos o noticias sobre los datos en `CTD/Notes.md`.

## English

In this repository we seek to archive and scrape into more usable formats the official data published by the Federal Health Secretariat of Mexico (*SSa* by its acronym in Spanish.)

Currently, we *archive* three types of documents:

- **Daily**: The Daily Technical Communiqués (*CTD* by its acronym in Spanish) and the tables of positive and suspect cases that are published [along them](https://www.gob.mx/salud/documentos/coronavirus-covid-19-comunicado-tecnico-diario-238449).
(The CTD are archived in `CTD/Documents` from the first one that has been published in 2020-01-23.
The tables are archived since 2020-03-14 in `CTD/Tablas_casos`.
We are aware that there were tables published before, but [they aren't available](https://github.com/carranco-sga/Mexico-COVID-19/issues/1).)
- **Daily**: The open data published by the SSa of the confirmed and suspect patients of COVID-19 [here](https://www.gob.mx/salud/documentos/datos-abiertos-152127) in `Open_data/COVID-19`.
- **Sporadically**: (There are updates not archived here.) Files from the SSa related to epidemiological monitoring published [here](https://www.gob.mx/salud/documentos/aviso-epidemiologico-casos-de-infeccion-respiratoria-asociados-a-nuevo-coronavirus-2019-ncov) in ``Aviso_Epidemiológico``.

To facilitate the usage of the data:

- **Daily**: The tables of (positive, suspect and deceased by state) cases of the CTD are scraped into the `.csv` format.
The results are filed in `CTD/Scraped_data`.
- **Daily**: The historical briefing table (a time series) `Mexico_COVID19_CTD.csv` is updated with confirmed, suspect and deceased cases by state.
The description of the fields is available in `CTD/README.md`.
- **In necessary case**: We add notes on discrepancies and considerations on the data or news related to them in `CTD/Notes.md`.

## Otros proyectos/other projects:

Están listados en `Other_resources.md`.
They're listed in `Other_resources.md`.

## Contacto/Contact

¡Cualquier contribución  es bienvenida!
Contacto: carranco[punto]sga[arroba]ciencias[punto]unam[punto]mx

Any contribution is welcome!
Contact: carranco[dot]sga[at]ciencias[dot]unam[dot]mx
