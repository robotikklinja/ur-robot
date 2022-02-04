# UR5e prosjekt

![UR-Robot](https://github.com/robotikklinja/ur-robot/tree/master/UR5e/Bilder/UR-Robot.jpg)
## Introduksjon

"UR5e" er et prosjekt som handler om å utvikle applikasjoner og arbeidsoppgaver for en UR-Robotarm. UR5 er en enkel RRR manipulator. Armen skal brukes til å lære opp elever til programmere og kontrollere en robot. 

Målet for prosjektet er at alle elever skal lære seg å programmere og anvende en robot. I tilegg skal roboten implementeres i en evighetsmaskin sammen med Kuka roboten ved veicellen.

Roboten sin foreløpige applikasjon er et sorteringssystem av klosser på et transportbånd. Denne sorteringen gjennomføres ved at ulike sensorer (konduktive eller kapasative) sender et signal til armen som gjennomfører sorteringen.

### Generelt om roboten

- Roboten heter **UR5e**.git add

### Datablader

Data sheet for denne modellen finner du [her](https://github.com/robotikklinja/ur-robot/blob/master/ur5e-32528_ur_technical_details_.pdf). Data sheets for andre modeller finner du [her](https://www.universal-robots.com/download-center/#/).

### Notater

Det vi har fått gjort er å lære om hvordan ta backup av UR-Roboten, vi har lært om hvordan en skal programmere en UR-Robot. Vi har også fått lagd et program som får roboten til å plukke en boks opp fra transportbåndet som sorterer mellom 3D-printet plastikkbokser og metallbokser, deretter legger den boksen på sin tidligere spesifikkerte plass som foreløpig er på benken ved siden av armen. 

Foreløpig er det laget samtlige programmer med sine funksjoner. Disse finner man under "start programming" og "load program". Her er følgende program; "Test_Sverre_Henrik_2elr" og "sorting_system_2ELR". "sorting_system_2ELR" er programmet som sorterer klosser om de er av metall eller ei. Derimot er "Test_Sverre_Henrik_2elr" et program som prøver ut ulike funksjoner.
I tillegg har det blitt laget to program for å stable paller: "attal plate" og "sorting_W_palle_2ELR " derimot kan ikke disse to programmene benyttes ettersom bordet UR-Roboten sto på er byttet ut. For å igjen benyte disse programmene må waypoints byttes, og også avgrensning av område.

For å sikre mennekser kan ekstra sikkerhetsensorer være ideelt. UR-Roboten kan ta signal fra de fleste sensorer. Og en avgrensning av området (innenfor gult bur) kan gis slik at hvis personell går inn vil roboten arbeide med redusert hastighet. Spørsmålet er om dette er nødvendig når roboten allerede har en egen stopp ved møtt motstand.
