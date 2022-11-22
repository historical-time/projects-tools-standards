# Projects, tools, and standards

An annotated list of projects, tools, and standards related to the representation of historical time.

## Calendars / dating systems

* **ACDH-CH Linked Open Date Entities (LODE)**

    ACDH-CH Linked Open Date Entities (LODE) is a data service to provide information about (historical) dates, using Linked Open Data (LOD) techniques. Currently, the entities provide lookups for the time concepts for the precision of day, month, year, decade, century, and millennium. For practical reasons, the 1st implementation covers 6000 years between 3000 BC/BCE and AD/CE 3000 based on ISO8601.
    
    * [Linked Open Date Entities](https://vocabs.dariah.eu/date_entities/en/)
    * [Linked Open Date Entities Unit of Time](https://vocabs.dariah.eu/ut_entities/en/)

* **Buddhist Studies Time Authority Databases**

    These databases integrate information from various projects at the Library and Information Center at Dharma Drum Institute of Liberal Arts. By providing information on Chinese calendar dates they help with disambiguation and referencing of dates.
    
    * [Buddhist Studies Authority Database Project](https://authority.dila.edu.tw)
    * [Time Authority Database](https://authority.dila.edu.tw/time/)
    * [Documentation of the Time Authority Database](https://wiki.dila.edu.tw/pages/法鼓佛教學院時間規範資料庫說明：Notes_on_the_DDBC_Time_Authority_Database)
    
* **Geologic Time Scale (2020)**

    RDF representation of the Geologic Time Scale, as defined in the International Chronostratigraphic Chart (ICC) from the International Commission on Stratigraphy (ICS). The ICC embraces both chronostratigraphic (time-rock) units and their equivalent geochronologic (geologic-time) units, the former being related to the ‘Stratigraphic points’ referred to below, and the latter (geochronologic units) being employed in this RDF representation.
    
    * [Geologic Time Scale (2020)](http://resource.geosciml.org/vocabulary/timescale/gts2020)

* **HuTime Time Basic Data**

    Calendars are often different between countries, regions and cultures. This means a possibility that date expressions have to be converted to expressions according to the common calendar when various temporal information are analized. Tools and data for calendar conversion are provided here.
    
    * [HuTime Time Basic Data](http://www.hutime.org/basicdata/)
    * [HuTime Calendars](http://www.hutime.org/basicdata/calendar/calendars/)
    * [HuTime Calendars Linked Data](http://datetime.hutime.org/)
    * [HuTime Calendar Conversion Tool](http://www.hutime.org/basicdata/calendar/form.html)

* **Shanati**

    Shanati is working to compile and integrate all known relevant cuneiform and other textual attestations of dates relevant to the ancient daily Babylonian chronology.
    
    * [Shanati](http://www.shanati.org)

* **Trismegistos Time**

    A database of chronological aspects of texts from the ancient world. TM Time is still in its initial phase. Right now it should be seen as a tool to convert dates from old calendar systems to new and vice-versa, which also facilitates finding texts dated to specific periods in Trismegistos.
    
    * [Trismegistos Time](https://www.trismegistos.org/time/)
    
## Modeling / visualization tools

* **Aeon Timeline**

    Present historical events along an interactive visual timeline. Record precise times or use broad, uncertain dates. Map events to historical figures or important theories and movements. See individual timelines for specific people and concepts.
    
    * [Aeon Timeline](https://timeline.app)

* **ChronoLog Chronological Toolkit**

    ChronoLog is a software tool for chronological research in archaeology. It allows users to build complex models featuring chronological sequences, bounds on dates and durations, and various types of synchronisms. The software automatically checks the validity of such models, and computes the tightest possible chronological ranges for the date and duration of each chronological object in the  model.
    
    * [ChronoLog](https://chrono.ulb.be)
    
* **ChronoVis: Paintbox**

    A no-code graphical interface for generating temporal data visualizations, designed by the humanities for the humanities.
    
    * [Chronovis: Paintbox](https://huegor.github.io/chronovis-paintbox/)
    
* **HuTime Time Information System Software**

    HuTime is a time information system software application that can help users visualize and analyze temporal information based on time data. Researchers can create chronological tables and charts that include events over various time spans, from periods as short as a single day or hour, to periods as long as a year or century. Thus, users can examine the loaded data in its entirety using the expanded displayed temporal range, and gain an understanding of the times when event information is concentrated or when drastic changes occur. From that point, the user can shrink the displayed temporal range to investigate the details of various events in the most relevant periods.
    
    * [HuTime Time Information System Software](http://www.hutime.org/hutime/index.html)
    
## Periods

* **iDAI ChronOntology**

    iDAI.chronontology (short form: ChronOntology) is a web service that connects chronological terms, i.e. epochs, periods and events, with dating information. Hosted by the German Archaeological Institute (DAI) and part of the iDAI.welt, ChronOntology is an internet research tool for the Archaeology and Altertumswissenschaft (ancient studies and literature). Anyone can refer to its data, and anyone can add their additional project-specific or research-specific data on request. At the DAI, ChronOntology is the standard gazetteer for period names. Like the iDAI.gazetteer for place names, it serves as a norm data vocabulary for other information systems at the DAI and links them with other global time gazetteer systems.
    
    * [ChronOntology](https://chronontology.dainst.org)

* **PeriodO**

    PeriodO is a public domain gazetteer of scholarly definitions of historical, art-historical, and archaeological periods. It eases the task of linking among datasets that define periods differently. It also helps scholars and students see where period definitions overlap or diverge.
    
    * [PeriodO documentation](https://perio.do/)
    * [Browse PeriodO](https://client.perio.do/?page=backend-home&backendID=web-https%3A%2F%2Fdata.perio.do%2F)
    * [Data samples](https://github.com/historical-time/data-samples/tree/main/periodo)

## Standards

* **CIDOC Conceptual Reference Model**

    The CIDOC CRM is a formal ontology intended to facilitate the integration, mediation and interchange of heterogeneous cultural heritage information and similar information from other domains. It includes a set of properties relating to temporal entities supporting the documentation of dates as time-spans or dimensions, mereological relations between temporal entities, as well as a complete suite of topological relations.
    
    * [Definition of the CIDOC CRM (version 7.2.2, September 2022)](https://www.cidoc-crm.org/sites/default/files/cidoc_crm_version_7.2.2%5B20%20Oct%5D.pdf)
    * [Excerpt from the CRM definition focusing on the temporal modeling constructs](documents/CIDOC%20CRM%20SIG%20-%202022%20-%20Temporal%20relations.pdf)

* **Extended Date/Time Format (EDTF)**

    The Extended Date and Time Format (EDTF) was developed at the Library of Congress and is now incorporated into the ISO 8601 standard for representing dates and times. EDTF specifies a standard syntax for expressing uncertain or approximate Gregorian calendar dates, dates with missing parts, sets of possible dates, and open-ended or recurring intervals of time.
    
    * [Extended Date/Time Format](https://www.loc.gov/standards/datetime/)
    * [ISO 8601-2:2019 Date and time — Representations for information interchange — Part 2: Extensions](https://www.iso.org/standard/70908.html)
    * [EDTF Ontology](https://periodo.github.io/edtf-ontology/)
    

