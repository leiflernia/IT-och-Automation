# Styr och processystem

Moderna styr och processystem är idag uppbyggda kring mycket kraftfulla datorer och avancerad modern programvara.

Systemen kan ha tusentals mät, kontroll och reglerpunkter.

Ofta är systemens uppgift att styra, reglera och övervaka en process eller en maskin.

I de fall systemet inte har direkt tillståndsövervakande funktion kan man i driftsäkerhetsarbetet ändå ha stor nytta av de data och funktioner som finns i systemet.

Vid drifts eller kvalitetsstyrningar kan underhållspersonal spåra störningsorsaker och störningsförlopp genom att använda loggade data ur styrsystemet.

Många system har avancerad funktionalitet för att spåra avvikelser eller för at kunna visa trender.

Vissa system har funktionalitet at föreslå åtgärder i processen för att optimera utbyte och tillförlitlighet.

En del system kan också kopplas direkt till företagets underhållssystem och överföra drifttider, driftdata och drifttillstånd till underhållssystemet.

Inte sällan kopplas företagens all mät, styr och kontrollsystem ihop via kommunikations-nätverk s.k. fältbussar.

På detta sätt får man åtkomst till alla styr, kontroll och mätdata överallt i företaget.

Givetvis underlättar detta felsökning och analys i anläggningar.

### Automation

Alla skäl till automatisering är i grunden ekonomiska. Krav på stabilare produktion, stigande lönekostnader och bristen på arbetskraft har banat väg för automatisering. Även svårigheter att rekrytera folk till monotona och miljöfarliga arbeten har påverkat utvecklingen.

![enter image description here](https://lernia.itslearning.com/data/1821/C33238/Bilder/IT%20och%20automation/effekter_automation.JPG)
Vid automatisering kan vi använda oss av allt ifrån det lilla fast­spänningsverktyget till avancerade robotar. Vi skall titta på olika former av automatisering från luftcylindrar och fotoceller till automatiskt styrda bearbetningsmaskiner och robotar.

::: warning Info
Automation ger en stabilare produktion, ökar produktionen med oförändrad personalstyrka samt ger ökad konkurrenskraft och högre lönsamhet
:::

#### Småskalig automation

En mycket användbar komponent vid automation är luftcylindern.

Automatisering med hjälp av luftcylindrar kan göras på de mest skiftande ställen. Vi kan t ex förbättra arbetsställningar, underlätta förflyttning av kartonger, öppna tunga luckor och placera material i förutbestämda lägen.

![enter image description here](https://lernia.itslearning.com/data/1821/C33238/Bilder/IT%20och%20automation/smaskalig.JPG)
Tillsammans med sensorer som känner av läget på de detaljer vi hanterar, gränslägesbrytare som styrcylinderns rörelser, ventiler och en programmerbar enhet kan vi bygga upp mycket effektiva system som förenklar och underlättar vårt arbete.

Utbudet är stort idag och det finns mycket avancerade lyftcylindrar inte bara för linjära rörelser utan också vridcylindrar och andra typer. Med lite finurlighet kan man idag bygga ihop system för att automatisera många olika monotona eller farliga moment.

![enter image description here](https://lernia.itslearning.com/data/1821/C33238/Bilder/IT%20och%20automation/lyftcylindrar.JPG)
Sensorer finns idag i en mängd olika utföranden. Det finns t ex sensorer som kan se skillnad på olika färger och sådana som är programmerbara. Med luftcylindrar, sensorer och andra komponenter går det idag att automatisera det mesta, bara vilja, tid och pengar finns.
![enter image description here](https://lernia.itslearning.com/data/1821/C33238/Bilder/IT%20och%20automation/sensorer.JPG)::: warning Info
Automation med t ex lyftcylindrar kan ofta enkelt eliminera farliga och monotona arbeten
:::

### Automatisering av bearbetningsmaskiner

När vi talar om automatisering av bearbetningsmaskiner använder vi oss av många olika engelska förkortningar. Vi skall här försöka förklara några av de vanligaste begreppen:

_NC_

Den första generationen automatiskt styrda bearbetningsmaskiner var s k _NC-styrda_ (numeriskt styrda) maskiner, som styrs via hålkort och hålremsa. Detta är den enklaste nivån av styrning där NC-systemet enbart utnyttjas för att styra en maskins verktygsrörelse. Nyheten med dessa maskiner var att verktygsväxling sköttes automatiskt samt att varvtal kunde ändras under bearbetningen.

Ett problem var dock att man slet ut hålkortet eller remsan, eftersom dessa lästes av vid varje arbetscykel.

_CNC_

Nästa steg var _CNC-styrning_ (datanumerisk styrning), där man byggde in en mikrodator i maskinen, men nu finns också redigeringsmöjligheter inbyggda. Det hade visat sig nödvändigt att kunna ändra i programmen direkt vid maskinen. Möjlighet att lagra flera program samtidigt i maskinens dator infördes också. Många styrsystem har dessutom möjlighet till direktprogrammering vid maskinen.

_DNC_

Steget efter CNC-styrning är att koppla samman en eller flera NC- och CNC-maskiner med en central dator, en s k DNC-dator. (DNC - direkt numerisk styrning).

Motivet till sådana kopplingar är att man vill underlätta överföringen av bearbetningsprogram, samordna materialtillförsel samt underlätta övervakning och styrning av tillverkningen. Kopplingar kan finnas mellan DNC-datorn (centraldatorn) och CAM-systemet (beredning) och MPS-systemet (planeringen).

![enter image description here](https://lernia.itslearning.com/data/1821/C33238/Bilder/IT%20och%20automation/dnc.JPG)

### PBB – Produktion med Begränsad Bemanning

PBB innebär att vi kan köra våra maskiner delvis obemannade, vilket ökar den produktiva tiden i maskinen.

För att kunna införa PBB bör en vanlig CNC-fleroperationsmaskin vara utrustad enligt följande:

- palettmagasin för automatisk frammatning av arbetsstycken

- automatiskt val av program för olika arbetsstycken

- stort antal dubblettverktyg i verktygsmagasinet

- skärkraftsövervakning för verktyg (maskinen känner av förslitning av verktyg)

- övervakning av verktygshaveri (avkänning av verktygsspets)

- automatiskt mätsystem (kontrollera att arbetsstycket har rätt mått efter utförd operation).

Ibland för man samman ett antal automatiskt styrda maskiner så att de utgör ett komplett tillverkningsavsnitt. Vi pratar då om en flödesgrupp eller en FMS-anläggning, där FMS står för ”Flexible Manufacturing System” (Flexibelt Tillverkningssystem).

::: warning Info
PBB ökar den produktiva tiden utan att antalet operatörstimmar ökar
:::

![enter image description here](https://lernia.itslearning.com/data/1821/C33238/Bilder/IT%20och%20automation/pnb.JPG)

### Robotar

En industrirobot kan definieras som en programmerbar hanterings­automat. En robot utför automatiskt förflyttningar och positioneringar efter ett eller flera förutbestämda rörelsemönster. Skälen till att införa robot kan vara flera:

- minska genomloppstiden

- minska stycktiden

- förbättra arbetsmiljön

- få jämnare kvalitet

- öka den produktiva tiden i maskinen.

Installation av robotar sker ofta vid miljöfarliga arbeten såsom:

- tunga lyft

- sprutlackering

- svetsning

- slipning och polering

- in- och urplockning i maskiner.

![enter image description here](https://lernia.itslearning.com/data/1821/C33238/Bilder/IT%20och%20automation/robot.JPG)

En robot består av två huvuddelar: en del som utför själva rörelserna och en styrenhet.

Styrenheten innehåller en dator som kontrollerar robotens rörelser och viss kringutrustning som t ex säkerhetssystem.

Styrenheten kan förses med olika programvaror för olika använd­ningsområden som t ex olika typer av svetsning, sprutlackering, plockning och montering.

Programmering av en robot kan göras på två olika sätt.

_”Teach-in”_ där vi kör fram roboten till önskat läge och sedan registrerar läget i roboten.

Justering av lägen görs oftast på detta sätt.

_”Off-line”_ programmering där de olika lägena hämtas direkt från CAD/CAM-systemet.

::: warning Info
En robot utför förflyttningar och positioneringar efter ett eller flera förutbestämda rörelsemönster
:::

Ett av de största användnings­områdena för robotar är montering. Robotarna är snabbare och noggrannare och dessutom utrustade med kringutrustning för ”seende”.

Robotar med kamera och bildbehandling kan också i stor utsträckning användas för att visuellt kontrollera att detaljer är rätt tillverkade.

![enter image description here](https://lernia.itslearning.com/data/1821/C33238/Bilder/IT%20och%20automation/robot2.JPG)
<br />
_Robotsäkerhet_

Robotar har avlastat människor en del tunga och ohälsosamma arbetsuppgifter. De har dock medfört nya riskmoment. Det är svårt att göra robotar helt säkra eftersom de är delar i ett system som består av både människor och rörliga maskiner.

En robot får inte starta när någon befinner sig i riskområdet. Detta måste inhägnas med skyddsgrindar och det måste finnas säkra stoppfunktioner. Det händer ofta att personalen tror att roboten har stannat när den i själva verket befinner sig i ett kort väntläge.

När roboten plötsligt börjar röra sig kan detta leda till svåra personskador.

![enter image description here](https://lernia.itslearning.com/data/1821/C33238/Bilder/IT%20och%20automation/robotskador.JPG)
::: warning Info
En robots arbetsområde måste vara spärrat vid drift
:::


### Ordlista

_Automation_

**Arbetscykel**  En komplett arbetssekvens från början till slut.

**Dubblettverktyg**  Flera identiskt lika verktyg i samma maskin.

**Ergonomi**  Läran om människans fysiska och psykiska förutsättningar i samspelet människa/ maskin

**Fotocell**  Sensor som påverkas av ljus i någon form.

**Gränslägesbrytare**  Brytare som stoppar en rörelse vid ett visst förutbestämt läge.

**Hålkort/hålremsa**  Kort/remsa med stansade hål som utgör program för styrning av NC-maskiner.

**Linjär rörelse**  Rörelse i en rak linje.

**Palett**  System med växlingsbara bärare för fixtur/ detalj där riggning sker utanför maskinen.

**Positionering**  Rörelse till ett exakt förutbestämt läge.

**Rationalisering**  Användning av resurser på ett bättre sätt.

**Sensor**  Avkännare. Olika typer finns som påverkas t ex av vidröring, läge, ljus, temperatur etc.

**Skyttelcylinder**  Luftcylinder utan kolvstång.

### Instuderingsfrågor B

1. Nämn några möjliga positiva effekter av automation.

2. Ge exempel på några enkla automatiseringsmöjligheter där man använder luftcylindrar.

3. Vad används en sensor till?

4. Beskriv kortfattat skillnaden mellan NC- och CNC-styrda maskiner.

5. Vad innebär PBB?

6. Vad finns det för skäl att installera en robot?

7. Ge några exempel på vad robotar kan användas till.

8. Förklara vad frihetsgrad för en robot är.

9. På vilket sätt kan en robot vara farlig?
 

### Svar instuderingsfrågor B

1. Möjliga positiva effekter av automation kan vara

- minskad frånvaro

- minskad personalomsättning
- minskad bemanning

- högre produktivitet

- färre kvalitetsproblem.

2. Exempel på automatisering med hjälp av luftcylindrar är

- reglering av arbetshöjd

- förflyttning av material

- plockning

- lucköppning

- kapning

- sprutmålning.

3. En sensor känner t ex av läget på den detalj vi hanterar.

4. Skillnaden mellan NC- och CNC-styrda maskiner är att NC-maskiner styrs via hålkort och hålremsa medan CNC-maskiner styrs med en inbyggd mikrodator. CNC-maskiner kan dessutom programmeras direkt vid maskinen.

5. PBB, Produktion med Begränsad Bemanning, innebär att vi kan köra våra maskiner delvis obemannade.

6. Robotar kan minska genomlopps- och stycktider, skapa bättre arbetsmiljö och ge jämnare kvalitet.
7. Robotar kan användas till tunga lyft, svetsning, sprutlackering, montering, avsyning m.m.

8. Frihetsgrad är en definition på hur mycket roboten kan röra sig, d v s det antal axlar den har.

9. En robot kan starta när någon finns inom riskområdet. Detta kan inträffa när personalen tror att roboten stoppat men i verkligheten bara står i vänteläge. En robot rör sig med en sådan kraft att personskador ofta uppstår om man blir träffad.

