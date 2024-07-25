**Inhaltsverzeichnis**

[[_TOC_]]

Die Backend-API wird mit Integration-Tests abgeprüft. Um einen erfolgreichen Durchlauf zu garantieren, muss die Datenbank leer sein. Sie befinden sich im Verzeichnis `~/tests`. 

## CI/CD
Bei jedem _push_ auf das Remote Repository wird eine CI/CD Pipeline durchlaufen, die automatisch den Code aller Tests durchlaufen lässt. 
Die entsprechende Konfiguration findet sich im Backend Repository in der Datei `.gitlab-ci.yml`. GitLab liest diese Datei aus und beauftragt einen "Runner" damit, die Anweisungen auszuführen.

## Befehle
`npm run test`  
Lässt alle Tests laufen.  
  
`npm run test:auth`  
Lässt Tests für den **/authenticate** Endpoint laufen.  
  
`npm run test:students`  
Lässt Tests für den **/students** Endpoint laufen.  
  
`npm run test:companies`  
Lässt Tests für den **/companies** Endpoint laufen.  
  
`npm run test:jobs`  
Lässt Tests für den **/jobs** Endpoint laufen.  
  
## Dependencies
### Mocha
Mocha ist unser Testframework. PactumJS ist von Mocha abhängig.  
  
[Homepage](https://mochajs.org/) | [GitHub](https://github.com/mochajs/mocha)  
### Supertest
Supertest startet und beendet den Backendserver für die Tests.  
  
[GitHub](https://github.com/visionmedia/supertest)  

### PactumJS
Unsere Integration-Tests wurden alle mithilfe von PactumJS geschrieben.  
  
[Homepage](https://pactumjs.github.io/) | [GitHub](https://github.com/pactumjs/pactum)  