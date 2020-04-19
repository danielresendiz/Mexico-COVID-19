# Base de datos de casos de COVID-19 reportados en México / Database of reported cases of COVID-19 in Mexico.

Última actualización/Last update: 2020-04-18 T 19:30:00-05:00

**Nota/Note**:
Actualmente me encuentro reordenando el repositorio para hacerlo más legible. Una disculpa por la molestia y por la tardanza en contestar correos.
Am currently reordering the repository to make it more legible. I apologize for the inconvenience and for the delay in answering emails.

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

-**Daily**: The Daily Technical Communiqués (*CTD* by its acronym in Spanish) and the tables of positive and suspect cases that are published [along them](https://www.gob.mx/salud/documentos/coronavirus-covid-19-comunicado-tecnico-diario-238449).
(The CTD are archived in `CTD/Documents` from the first one that has been published in 2020-01-23.
The tables are archived since 2020-03-14 in `CTD/Tablas_casos`.
We are aware that there were tables published before, but [they aren't available](https://github.com/carranco-sga/Mexico-COVID-19/issues/1).)
- **Daily**: The open data published by the SSa of the confirmed and suspect patients of COVID-19 [here](https://www.gob.mx/salud/documentos/datos-abiertos-152127) in `Open_data/COVID-19`.
- **Sporadically**: (There are updates not archived here.) Files from the SSa related to epidemiological monitoring published [here](https://www.gob.mx/salud/documentos/aviso-epidemiologico-casos-de-infeccion-respiratoria-asociados-a-nuevo-coronavirus-2019-ncov) in ``Aviso_Epidemiológico``.

To facilitate the usage of the data:

-**Daily**: The tables of (positive, suspect and deceased by state) cases of the CTD are scraped into the `.csv` format.
The results are filed in `CTD/Scraped_data`.
-**Daily**: The historical briefing table (a time series) `Mexico_COVID19_CTD.csv` is updated with confirmed, suspect and deceased cases by state.
The description of the fields is available in `CTD/README.md`.
- **In necessary case**: We add notes on discrepancies and considerations on the data or news related to them in `CTD/Notes.md`.

## Contacto/Contact

¡Cualquier contribución  es bienvenida!
Contacto: carranco[punto]sga[arroba]ciencias[punto]unam[punto]mx

Any contribution is welcome!
Contact: carranco[dot]sga[at]ciencias[dot]unam[dot]mx
