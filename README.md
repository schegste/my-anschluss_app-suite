# 🚉 *Anschluss!* – App Suite zur Fahrplananalyse
[Zur Webseite von OpenTransportData](https://opentransportdata.swiss/de/)

Willkommen im zentralen Repository zur Masterarbeit **„Anschluss!“** – einer prototypischen Anwendung zur Analyse von Fahrplanveränderungen im öffentlichen Verkehr.  
Diese *App Suite* vereint alle relevanten Repositories, Tools und Dokumente für Datenaufbereitung, Analyse und Visualisierung von GTFS-basierten Fahrplandaten.

---

## 🔗 Komponentenübersicht

| 🧩 Komponente         | 📄 Beschreibung                                                  | 🔗 Repository Link                                                                 |
|----------------------|------------------------------------------------------------------|------------------------------------------------------------------------------------|
| 🌐 Spring Boot App    | Enthält Frontend & Backend der Webanwendung                     | [anschluss_v1_1](https://github.com/schegste/anschluss_v1_1)                      |
| 🗄 SQL-Skripte         | SQL-Statements zur GTFS-Datenbankstruktur                       | [0_sql_Statements](https://github.com/schegste/0_sql_Statements)                  |
| 📦 Extract            | Skripte zur Modifikation der GTFS-Rohdaten                      | [01_transform_gtfs_txt_data_v1](https://github.com/schegste/01_transform_gtfs_txt_data_v1) |
| 🔁 Transfer           | GTFS-Text → SQL-Konvertierungsskripte                           | [02_transform_txt_to_sql_v1](https://github.com/schegste/02_transform_txt_to_sql_v1) |
| 🧰 Load               | Erstellt & befüllt die GTFS-Datenbank                           | [03_create_load_gtfs_db_v1](https://github.com/schegste/03_create_load_gtfs_db_v1) |
| 📘 Masterarbeit        | PDF-Dokumentation inkl. Anhänge                                 | [Dokumente_MaTh_Anschluss_SSchegg](https://github.com/schegste/Dokumente_MaTh_Anschluss_SSchegg) |

---

## 📥 Nutzungshinweise

Die Repositories sind modular aufgebaut und können einzeln verwendet oder geklont werden.  
🔒 *Einige Repositories sind privat. Zugriffsanfragen bitte an* **Stefan Schegg** *richten.*

---

## 🛠 Architekturüberblick *(folgt bald)*

In Kürze verfügbar unter dem Pfad: [`/docs`](./docs)



