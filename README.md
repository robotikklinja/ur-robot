# Universal Robots prosjekt
"Bilde"
## Intro
"UR-Robot" er et prosjekt som handler om å utvikle applikasjoner og arbeidsoppgaver for en UR-Robotarm. UR-Roboten er en enkel RRR manipulator med 6 degrees of freedom. Armen skal brukes til å lære opp elever til å ha kontroll over en robot. 


### Generelt om roboten

- Roboten heter **UR5e**.
- Roboten er koblet opp som en Master. Det betyr at modbusene sender informasjon til armen. Den kan også brukes som en slave til et annet system.
- Roboten kontrolleres gjennom en teachpendant.  

### Bruk av UR-Robot
Lurer du på hvordan en bruker en UR-Robot? Finner du informasjon om hvordan en bruker en ur-robot [her](https://github.com/robotikklinja/ur-robot/blob/master/tutorial/01.md).

### Datablader
Data sheet for denne modellen finner du [her](https://github.com/robotikklinja/ur-robot/blob/master/ur5e-32528_ur_technical_details_.pdf). Data sheets for andre modeller finner du [her](https://www.universal-robots.com/download-center/#/).

### Ta Backup
For å ta backups av en UR-Robot må du innstallere [magic files](https://www.universal-robots.com/download/?option=16449#section16447) og velge en av de tre backupene (Backup Programes, Backup Log Files eller Backup Configurations files). Deretter følger du tutorialen under (USB for backup finner du i Kontroll boksen), Dette gjør du for alle de tre formene for backup før dere begynner deres to uker.

### Notater
Det vi har fått gjort er å lære om hvordan ta backup av UR-Roboten, vi har lært om hvordan en skal programmere en UR-Robot. Vi har også fått lagd et program som får roboten til å plukke en boks opp fra transportbåndet som sorterer mellom 3D-printa plastikk bokser og metal bokser, deretter legger den boksen på sin presatte plass som per nå er på benken ved siden av armen. 

### To do
- [x] Ting å gjøre senere: Lage en hylle til boksene, finne en ny applikasjon for armen.
- [ ] Utvikle applikasjoner 
- [ ] Eventuellt Sikkerhetssensorer, sikre arbeidsområde
- [ ] Sammkjøre UR-Robot med Veicelle
