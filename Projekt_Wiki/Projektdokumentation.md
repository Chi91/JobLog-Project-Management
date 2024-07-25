**Inhaltsverzeichnis**

[[_TOC_]]

## Projektbeschreibung

Ziel dieses Projekts ist es, den Kommunikationsfluss zwischen Unternehmen und Studierenden im Kontext der Jobsuche und Jobangeboten zu vereinfachen und übersichtlicher zu gestalten. Die von der BHT genutzte Lösung bietet grundlegend schon die Möglichkeit, dass Unternehmen ihre Stellengesuche einstellen können und Suchende die Jobs filtern können. Unsere Jobbörse soll den gesamten Prozess der Arbeitssuche für Arbeitnehmer_innen und Arbeitgeber_innen optimieren. Jobangebote sollen sich an bestimmte Studiengänge richten, sowie über tag-basierte Suche personalisierte Ergebnisse bringen. Studierende sollen in der Lage sein, ihre zeitlichen Kapazitäten anzugeben, wodurch das Zeitmanagement zwischen Arbeit und Studium vereinfacht werden soll. Der Bewerbungsprozess soll durch Upload-Funktionen in den Stellenanzeigen direkter und unkomplizierter gestaltet werden, so dass Bewerbungsunterlagen über das Portal gesendet werden können.

## Features

* Progressive Web App
* minimalistisches, simples und übersichtliches Design
* filtern nach Jobs/Studenten
* Jobangebote zugeschnitten für Studiengänge
* Zeitangabe der studentischen Kapazität
* Schlagwort- und zeitbasierte Jobsuche
* Upload-Funktion der Bewerbungsunterlagen direkt in der Stellenanzeige

## Art des Projektes

Progressive Web App (PWA): “Eine Progressive Web App ist eine Website, die zahlreiche Merkmale besitzt, die bislang nativen Apps vorbehalten waren. Sie kann daher auch als Symbiose aus einer responsiven Webseite und einer App beschrieben werden.” Quelle: https://de.wikipedia.org/wiki/Progressive_Web_App

## Tech Stack

### Back-End

* Javascript
* Node.js (Framework: Express)
* Datenbank:
  * MongoDB
  * Mongoose (MongoDB - Objektmodellierungstool)
* Tests:
  * Mocha
  * PactumJS

### Front-End

* Javascript
* React
* Redux (State Manager)
* HTML
* CSS
* Apache (Webserver)

### **Versionen der benutzen Technologien**

**Frontend**

<kbd>
<img src="uploads/385a8f9c2480f2216b0767ac3699c064/image.png" />
</kbd>

<br>**Backend**

<kbd>
<img src="uploads/8ad232aaf807064fcc01b3f68c196e79/image.png" />
</kbd>

## Teilnehmer\*innen

* Nadine Brandes (916887) - Teamlead Frontend | UI/UX Designer | Testing
* Gerrit Behrens (918257) - Supervisor Backend & Frontend​ | Coding Frontend | Testing
* Leander Wendt (921663) - Teamlead Backend | Coding Backend | Testing
* Chi Thien Pham (922567) - Coding Backend | Testing | Dokumentation
* Jonas Spaller (925041) - Coding Backend & Frontend | Deployment | Testing
* Matthias Czernia (925042) - Coding Backend | Testing | Dokumentation

## Zeitplan

* 06.10.22 - Brainstorming: Themafindung
* 13.10.22 - Bearbeitung Projektbeschreibung
* 20.10.22 - Organisation & Bekanntgabe Pitch
* 27.10.22 - Fertigstellung Pitch & Präsentation
* 03.11.22 - Festlegung Milestone, Anlegung Projekt- & Developerdokumentation
* 10.11.22 - Umstrukturierung Teamorganisation & Kommunikation
* 17.11.22 - Besprechung Matching-Systems
* 24.11.22 - Online - Aktualisierung DB-Schema & Wiki
* 01.12.22 - Priorisierung Features & Issues - "aufräumen"
* 08.12.22 - Bekanntgabe PlayTest, Erstellung Testpläne & Umfragebogen
* 15.12.22 - Vorbereitungen PlayTest
* 22.12.22 - PlayTest - vorzeigbarer Prototype mit interaktiver Oberfläche (Kernidee)
* 05.01.23 - PlayTest Auswertung: Beobachtung / Umfragen, Ausblick letzter Milestone
* 12.01.23 - Informationen zur Abschlusspräsentation
* 19.01.23 - Vorbereitung Abschlusspräsentation
* 26.01.23 - Letztes Feedback Projekt, Klärung offener Fragen (Abschlusspräsentation)
* 02.02.23 - Abschlusspräsentation Part 1
* 09.02.23 - Abschlusspräsentation Part 2
* 16.02.23 - Ggf. Nachgespräch

## Meetings & Kommunikation

* Supervisor BE / FE: Gerrit Behrens (Nadine Brandes, Leander Wendt) - Montags, 11:00 Uhr.
* Teamlead BE: Leander Wendt (Matthias Czernia, Chi Thien Pham) - Dienstags, 15:00 Uhr.
* Teamlead FE: Nadine Brandes (Gerrit Behrens, Jonas Spaller) - Mittwochs, 11:00 Uhr.
* Teammeeting: Alle - Donnerstags, 13:15 Uhr mit Betreuer in Präsenz, mit anschließenden internen Team-Besprechungen

#### Kommunikationsart

* Discord - Supervisor Meetings & Teamlead Meetings BE | FE
* Whatsapp - für einzelne Absprachen zwischen den Mitgliedern

#### Versionskontrollsystem

* GitLab

## Projektplanung

### User Story

* Student:
  * US#101: Als studierende Person möchte ich Jobangebote sehen.
  * US#102: Als studierende Person möchte ich mich auf Jobangebote bewerben können.
  * <span dir="">US#103: Als studierende Person möchte ich mich registrieren können.</span>
  * US#104: Als studierende Person möchte ich mein Profil erstellen können.
  * US#105: Als studierende Person möchte ich mein Profil bearbeiten können.
  * US#106: Als studierende Person möchte ich mein Profil sehen.
  * US#107: Als studierende Person möchte ich mein Profil löschen können.
  * US#108: Als studierende Person möchte ich meine Bewerbungsunterlagen zu meinem Profil hinzufügen können.
  * US#109: Als studierende Person möchte ich meine möglichen Arbeitszeiten/Tage hinterlegen können.
  * US#110: Als studierende Person möchte ich Jobangebote suchen können.
  * US#111: Als studierende Person möchte ich bei der Suche filtern können.
  * US#112: Als studierende Person möchte ich meine Suchfilter speichern können.
  * US#113: Als studierende Person möchte ich Jobvorschläge zu meinem Profil bekommen.
  * US#114: Als studierende Person möchte ich Unternehmen favorisieren können.
  * <span dir="">US#115: Als studierende Person möchte ich mit den Unternehmen direkt kommunizieren können.</span>
* Unternehmen:
  * US#201: Als Unternehmen möchte ich mich registrieren.
  * <span dir="">US#202: Als Unternehmen möchte ich ein Profil erstellen.</span>
  * <span dir="">US#203: Als Unternehmen möchte ich mein Profil einsehen.</span>
  * <span dir="">US#204: Als Unternehmen möchte ich mein Profil bearbeiten.</span>
  * <span dir="">US#205: Als Unternehmen möchte ich mein Profil löschen.</span>
  * <span dir="">US#206: Als Unternehmen möchte ich ein Stellenangebot erstellen.</span>
  * <span dir="">US#207: Als Unternehmen möchte ich meine Stellenangebote einsehen.</span>
  * <span dir="">US#208: Als Unternehmen möchte ich alle Stellenangebote einsehen.</span>
  * <span dir="">US#209: Als Unternehmen möchte ich ein Stellenangebot bearbeiten</span>.
  * <span dir="">US#210: Als Unternehmen möchte ich ein Stellenangebot löschen.</span>
  * <span dir="">US#211: Als Unternehmen möchte ich alle Bewerbungen auf ein Stellenangebot einsehen.</span>
  * <span dir="">US#212: Als Unternehmen möchte ich eine Bewerbung ablehnen.</span>
  * <span dir="">US#213: Als Unternehmen möchte ich eine Bewerbung annehmen.</span>
  * <span dir="">US#214: Als Unternehmen möchte ich ein Studierendenprofil ansehen.</span>
  * <span dir="">US#215: Als Unternehmen möchte ich Unternehmensprofile ansehen.</span>
  * <span dir="">US#216: Als Unternehmen möchte ich mit den Studierenden direkt kommunizieren können.</span>
  * <span dir="">US#217: Als Unternehmen möchte ich Studierende favorisieren können.</span>
* Admin:
  * <span dir="">US#301: Als Admin möchte ich unangemessene Inhalte löschen.</span>
  * <span dir="">US#302: Als Admin möchte ich Profile erstellen können.</span>
  * <span dir="">US#303: Als Admin möchte ich Profile bearbeiten können.</span>
  * <span dir="">US#304: Als Admin möchte ich Profile löschen können.</span>
  * <span dir="">US#305: Als Admin möchte ich Profile sehen können.</span>

### Endpoints

**_Jobs:_**

* **<span dir="">READ / GET:</span>**
  * <span dir="">/jobs --> getAllJobs (ungefiltert)</span>
  * <span dir="">/jobs/{jobID} --> getJobByID (gibt ein spezifisches Jobangebot zurück)</span>
  * <span dir="">/jobs/{fieldID} --> getAllJobsByFieldID (gefiltert nach Fachbereich)</span>
  * <span dir="">/jobs/{courseID} --> getAllJobsByCourseID (gefiltert nach Studiengang)</span>
  * <span dir="">/jobs/{companyID} --> getAllJobsByCompanyID (gefiltert nach Unternehmen)</span>
* **<span dir="">CREATE / POST:</span>**
  * <span dir="">/jobs</span>
    * <span dir="">Header: Bearer Token... (e.g. companyID)</span>
    * <span dir="">Body:</span>
      * <span dir="">fieldIDs</span>
      * <span dir="">courseIDs</span>
      * <span dir="">tagList - (Help the search, Skills etc.)</span>
      * <span dir="">jobTitle</span>
      * <span dir="">jobSummary</span>
      * <span dir="">jobType - (e.g working student, internship, full Times)</span>
      * <span dir="">salaryPerHour</span>
      * <span dir="">vacation</span>
      * <span dir="">workTimeAmount</span>
      * <span dir="">mandatoryPresenceTime</span>
      * <span dir="">benefits</span>
* **<span dir="">UPDATE / PUT:</span>**
  * <span dir="">/jobs/{jobID}</span>
    * <span dir="">Header: Bearer Token... (e.g. companyID)</span>
    * <span dir="">Body:</span>
    * <span dir="">fieldIDs</span>
    * <span dir="">courseIDs</span>
    * <span dir="">tagList - (Help the search, Skills etc.)</span>
    * <span dir="">jobTitle</span>
    * <span dir="">jobSummary</span>
    * <span dir="">jobType - (e.g working student, internship, full Times)</span>
    * <span dir="">salaryPerHour</span>
    * <span dir="">vacation</span>
    * <span dir="">workTimeAmount</span>
    * <span dir="">mandatoryPresenceTime</span>
    * <span dir="">benefits</span>
* **<span dir="">DELETE / DELETE:</span>**
  * <span dir="">/jobs/{jobID}</span>
    * <span dir="">Header: Bearer Token... (e.g. companyID, isAdmin=true)</span>

**<span dir="">_S_</span>_tudents_**

* **<span dir="">READ / GET:</span>**
  * <span dir="">/students --> getAllStudents</span>
  * <span dir="">/students/{studentID} --> getStudentByID</span>
  * <span dir="">/students/{fieldID} --> getStudentsByFieldID</span>
  * <span dir="">/students/{courseID} --> getStudentsByCourseID</span>
* **<span dir="">CREATE / POST:</span>**
  * <span dir="">/students</span>
  * <span dir="">Header: Authorisierung?</span>
  * <span dir="">Body:</span>
    * <span dir="">courseID</span>
    * <span dir="">fieldID</span>
    * <span dir="">username - public/email... ???</span>
    * <span dir="">firstname</span>
    * <span dir="">lastname</span>
    * <span dir="">password</span>
    * <span dir="">phone - not required</span>
    * <span dir="">email</span>
  * **<span dir="">UPDATE / Put:</span>**
    * <span dir="">/students/{studentID}</span>
    * <span dir="">Header: Bearer Token... (e.g. studentID, isAdmin=true)</span>
    * <span dir="">Body:</span>
      * <span dir="">courseID</span>
      * <span dir="">fieldID</span>
      * <span dir="">username</span>
      * <span dir="">- public/email... ???</span>
      * <span dir="">firstname</span>
      * <span dir="">lastname</span>
      * <span dir="">password</span>
      * <span dir="">phone</span>
      * <span dir="">email</span>
      * <span dir="">availability - (Key-Value?)</span>
      * <span dir="">savedSearches - (List with saved filters and search bar content)</span>
      * <span dir="">favoriteCompany - (List with company profil IDs)</span>
      * <span dir="">fileStorage - (List with pdfs)</span>
* **<span dir="">DELETE / DELETE:</span>**
  * <span dir="">/students/{studentID}</span>
  * <span dir="">Header: Bearer Token... (e.g. companyID, isAdmin=true)</span>

**<span dir="">_C_</span>_ompanies_**

* **<span dir="">READ / GET:</span>**
  * <span dir="">/companies --> getAllCompanies</span>
  * <span dir="">/companies/{compnayID} --> getCompanyByID</span>
* **<span dir="">CREATE / POST:</span>**
  * <span dir="">/companies</span>
  * <span dir="">Body:</span>
    * <span dir="">companyName</span>
    * <span dir="">password</span>
    * <span dir="">contactPerson - (Name of the person)</span>
    * <span dir="">phone - required</span>
    * <span dir="">email - required</span>
    * <span dir="">adress (street, number, postal code, city, country) - required</span>
    * <span dir="">homePage</span>
    * <span dir="">applicationEmail - ??? (Bei Dokumentenfreigabe und (Downloadoption) nicht nötig)</span>
    * <span dir="">companyDescription</span>
* **<span dir="">UPDATE / PUT:</span>**
  * <span dir="">/companies/{companyID}</span>
  * <span dir="">Header: Bearer Token...</span>
  * <span dir="">Body:</span>
    * <span dir="">companyName</span>
    * <span dir="">password</span>
    * <span dir="">contactPerson - (Name of the person)</span>
    * <span dir="">phone</span>
    * <span dir="">email</span>
    * <span dir="">adress (street, number, postal code, city, country)</span>
    * <span dir="">homePage</span>
    * <span dir="">applicationEmail</span>
    * <span dir="">companyDescription</span>
* **<span dir="">DELETE / DELETE:</span>**
  * <span dir="">/companies/{companyID}</span>
  * <span dir="">Header: Bearer Token... (e.g. companyID isAdmin=true)</span>

**<span dir="">_Management_</span>**<span dir=""> (Zur Pflege der Listen (Studiengang, Fachbereich))</span>

* **<span dir="">READ / GET:</span>**
  * <span dir="">/management/fields --> getAllFields (fieldID, description)</span>
  * <span dir="">/management/fields/{fieldID} --> getFieldByFieldID</span>
* **<span dir="">CREATE / POST:</span>**
  * <span dir="">/management/fields</span>
  * <span dir="">Header: Bearer Token (isAdmin=true)</span>
  * <span dir="">Body: description</span>
* **<span dir="">UPDATE / PUT</span>**
  * <span dir="">/management/fields/{fieldID}</span>
  * <span dir="">Header: Bearer Token (isAdmin=true)</span>
  * <span dir="">Body: description</span>
* **<span dir="">DELETE / DELETE:</span>**
  * <span dir="">/management/fields/{fieldID}</span>
  * <span dir="">Header: Bearer Token (isAdmin=true)</span>

**<span dir="">_M_</span>_anagement_**

* **<span dir="">READ / GET:</span>**
  * <span dir="">/management/courses --> getAllCourses (courseID, description)</span>
  * <span dir="">/management/courses/{courseID} --> getCourseByCouresID</span>
* **<span dir="">CREATE / POST:</span>**
  * <span dir="">/management/courses</span>
  * <span dir="">Header: Bearer Token (isAdmin=true)</span>
  * <span dir="">Body: description</span>
* **<span dir="">UPDATE / PUT</span>**
  * <span dir="">/management/courses/{courseID}</span>
  * <span dir="">Header: Bearer Token (isAdmin=true)</span>
  * <span dir="">Body: description</span>
* **<span dir="">DELETE / DELETE:</span>**
  * <span dir="">/management/courses/{courseID}</span>
  * <span dir="">Header: Bearer Token (isAdmin=true)</span>

### LDAP BHT

Recherche zur Anbindung des Logins über das LDAP der BHT mit Herrn Prof. Dr. Peter Tröger führte zu folgendem Ergebnis: Es gäbe theoretisch drei Varianten zur Realisierung. Das Rechenzentrum der BHT ist jedoch technisch für zwei Varianten noch nicht umsetzungsfähig. Die dritte Variante würde den Austausch der Benutzerkennung im Klartext beinhalten, was unsere Gruppe einstimmig aus Sicherheitsaspekten ablehnt.

## Schichten Architektur

**Allgemeine Architektur**

<kbd>
<img src="uploads/8c9d9ff520f87e5b3086c12d87711187/image.png" width="416" height="468" />
</kbd>

<br>**Frontend**

<kbd>
<img src="uploads/6da0d49955963b4a56b0e1149418dd68/image.png" width="594" height="369" />
</kbd>

<br>**Backend**

<kbd>
<img src="uploads/3cd9a647e4989aa91c5da5469bdcfa78/image.png" width="610" height="369" />
</kbd>

## Herausforderung & Erkenntnisse

* Herausforderung:
  * Teamstruktur und Zuständigkeiten
  * Verwirrung in den Aufgabenzuteilungen
* Erkenntnisse(negativ):
  * "Ich mache mal, wie ich denke"
  * "Teamstruktur ist wichtig"
  * "Einfach mal schnell coden"
  * "Betriebsblindheit"
* Erkenntnisse(positiv):
  * Einteilung der Aufgaben nach individuellen Stärken
  * Selbstständiges Arbeiten
  * Wissensaustausch innerhalb der Gruppe bei offenen Fragen
  * Kommunikation auf Augenhöhe

## Ausblick - Future Work

* Chatfunktion - zwischen Studenten & Company
* Error Handling - beim Ausfall des Backends
* Jobsuche - per Schlagwörter
* Account Verifizierung - per Mail bestätigen
* Cookiebanner - Akzeptieren beim Login oder Registrieren
* "Passwort vergessen" Funktion