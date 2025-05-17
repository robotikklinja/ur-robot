# Universal Robots prosjket på Kuben videregående skole

![UR-Robot](https://github.com/robotikklinja/ur-robot/blob/master/Bilder/universal-robots-vector-logo.jpg)

## Introduksjon

"UR-Robot" er et prosjekt som handler om å utvikle applikasjoner og arbeidsoppgaver for en UR-Robotarm. UR-Roboten er en enkel RRR manipulator med 6 degrees of freedom. Armen skal brukes til å lære opp elever til å ha kontroll over en robot. 

Målet for prosjektet er at alle elever skal lære seg å programmere og anvende en robot. I tilegg skal roboten implementeres i en evighetsmaskin.

Roboten sin foreløpige applikasjon er et sorteringssystem av klosser på et transportbånd. Denne sorteringen gjennomføres ved at ulike sensorer (konduktive eller kapasative) sender et signal til armen som gjennomfører sorteringen.

### Generelt om robotenene

- Robotene heter **UR5e** og **UR3e**.
- Begge robotene er koblet opp som en Master. Det betyr at modbusene sender informasjon til armen. Den kan også brukes som en slave til et annet system.
- Robotene kontrolleres gjennom en teachpendant.  
- For spesifikk informasjon om UR-Robotene se Datablader under.

<<<<<<< HEAD
### UR5 finner du mer om [her](https://github.com/robotikklinja/ur-robot/tree/master/UR5e) 

### UR3 finner du mer om [her](https://github.com/robotikklinja/ur-robot/tree/master/UR3e)
=======
### UR5 finner du mer om [her](https://github.com/robotikklinja/ur-robot/UR5e/) 

### UR3 finner du mer om [her](https://github.com/robotikklinja/ur-robot/UR3e/)
>>>>>>> 860530308ceedbc00a86ef233c128c8da0a7688b

### Lær UR-ROBOT, Kursmoduler

Lurer du på hvordan en bruker en UR-Robot? Du finner informasjon om hvordan en bruker en av ur-robotene [her](https://github.com/robotikklinja/ur-robot/blob/master/tutorial/01.md).

## Bordet 

### UR5
![UR5 bord](https://github.com/robotikklinja/ur-robot/assets/3476653/d5283d0e-4226-467a-b334-0b3627136c3c)

[Fusion modell av bodet](https://a360.co/46JmKKY)

![hullbilden](https://github.com/robotikklinja/ur-robot/assets/3476653/75d62ced-324f-4a8c-b06a-59e9ed94c8ce)
[DXF fil av bare hullbilden, kan importeres til fusion](hullbilde_ur5.dxf)


![image](https://github.com/robotikklinja/ur-robot/assets/3476653/38d58e98-47cc-4efc-bf40-b55ff1d5af10)

### UR3 bord

![image](https://github.com/robotikklinja/ur-robot/assets/3476653/0e0b8f20-1fde-4ce2-a22f-e8fae047ab68)

[UR3 Bord Fusion 360](https://a360.co/48Xx9Tm)

![image](https://github.com/robotikklinja/ur-robot/assets/3476653/5e92c999-27d8-4146-8dc5-36b4bd22adc5)

[U2x R3 Bord Med torso](https://a360.co/4a5kdMm)

### Head inspiration:
* Affectve https://www.thingiverse.com/thing:384962
* InMoov https://inmoov.fr/ https://www.thingiverse.com/thing:6030262 https://www.thingiverse.com/thing:67676 
* Ez-inmoov https://www.ez-robot.com/store/p86/ez-inmoov-robot-head.html

![image](https://github.com/robotikklinja/ur-robot/assets/3476653/625d5c0a-87fe-463c-b3b4-63886f172d3d)


### Ta Backup
Hver gang før en benytter seg av UR-Roboten skal det alltid tas en backup av armen ved oppstart.

For å ta backups av en UR-Robot må du innstallere [magic files](https://www.universal-robots.com/download/?option=16449#section16447) og velge en av de tre backupene (Backup Programes, Backup Log Files eller Backup Configurations files) til en minnepinne. Dette er allerede gjort. USB for backup finner du i kontroll boksen.
Deretter følger du tutorialen under ![Utføre Backup](https://github.com/robotikklinja/ur-robot/blob/master/Bilder/Magic%20files.png) 

## Kommunikasjon med roboterne over nettverk

Alternativer:

* Modubus server
* [Primary /secondary and realtime way to send URScript commands , rom UR](https://docs.universal-robots.com/tutorials/urscript-tutorials/socket-communication.html)
* Using Sockets to pass info to a regular program 
  * SIMPLEST! ->[Python or C++ Sockets XML-RPC communication](https://www.universal-robots.com/articles/ur/interface-communication/xml-rpc-communication/)
  * [URScript_socket_with python](https://gist.github.com/Shawn-Armstrong/001c14d8496f1362dace27bd6e1535e1)
* [Facetracking demo Uses the UR - RTDE- protocol to send continuous updates to a Robot](https://github.com/robin-gdwl/UR_Facetracking?tab=readme-ov-file)
  * [Real-Time Data Exchange (RTDE) Guide](https://www.universal-robots.com/articles/ur/interface-communication/real-time-data-exchange-rtde-guide/)  
