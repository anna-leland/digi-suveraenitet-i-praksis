---
title: 2. Analyse - audit.os.eu hjemmesiden
nav_order: 6
parent: Specialeforberedende forløb hos OS2 2026
---

2.  **UI-hjemmeside analyse:**
   - udpege hvor problemerne er nav og struktur på sitet 
   - forsigtigt sketch/forslag til ny sideopsætning på audit.os2.eu, som gør det nemmere at navigere rundt
   - lav en bedre skelnen mellem det brugerrettede og 'backend' generator, som ligger åbent for åbentheden skyld, men man er i tvivl om man skal orientere sig i.
   - omarrangering af undersider, forsiden, overskrifter, beskrivelser etc
   - kunne en illu på figma være brugbar?
   - ellers brug en form for Ai til at illustrere hvordan navnene og siderne skal laves om/flyttes
   - empiri: UX-walkthrough analyse m MS

teori: Norman, "the design of everyday things" og Davis "Affordances of artifacts"


Intro: 
~ Intro som kort ridser hvad, hvordan, hvilke fund og ændringsforslag ~ 


## **HVAD UNDERSØGES:**
Analyse af **audit.os2.eu** med fokus på hvordan forløbet formidles med forslag til ændring i struktur og navigation, så sitet bliver mere overskueligt. Der ses blandt andet på skellet mellem brugerrettet indhold og den mere tekniske backend/generator samt organiseringen af sider, overskrifter og beskrivelser. 

## **HVORDAN**: -->

**Min egen analyse: walkthrough (Light et al., 2018).**\
Jeg gennemgår audit.os2.eu systematisk med inspiration fra walkthrough-metoden hos Light et al. (2018) og undersøger, hvordan sitets struktur, navigation og indhold guider produktforvalteren gennem governanceprocessen. I analysen inddrager jeg særligt Light et al.s begreb _environment of expected use_ som analytisk blik på, hvilket formål og hvilken brug sitets enkelte dele lægger op til, og hvilken bruger de synes at forudsætte. 

**Brugertest med Mathias fra OS2ai (Hertzum, 2020).**\
For en detaljeret gennemgang af, hvordan sitet opleves af en produktforvalter, har jeg lavet en brugertest med Mathias, product owner på sandkasseprojektet OS2ai, som ikke har udfyldt selvevalueringen endnu – han ser sitet med friske øjne. Mathias gennemgår en række opgaver, jeg har forberedt, tænker højt undervejs, og jeg observerer ham og følger op med spørgsmål undervejs og efter hver opgave. Det tager udgangspunkt i Hertzums model med grundelementerne: instruktioner og opgaver, verbalisering og aflæsning af brugeren (Hertzum, 2020, s. 2–3).

**Affordances som analytisk linse (Davis, 2020).**\
Som analytisk blik på brugerfladen inddrager jeg Davis’ affordancebegreb. Frem for blot at spørge, _hvad_ en teknologi muliggør, foreslår Davis at undersøge, _hvordan_ den guider, muliggør eller begrænser bestemte handlinger. I analysen bruger jeg især begreberne **perception** og **dexterity**: om brugeren kan gennemskue, hvilke funktioner og handlemuligheder sitet tilbyder, og om brugeren har de nødvendige kompetencer til at benytte dem. Dermed bliver det relevant at undersøge, hvordan audit.os2.eu fungerer for produktforvaltere med forskellige grader af teknisk erfaring. Fra de 6 interviews har jeg netop spurgt produktforvalterne til deres kendskab til sitet og hvordan det opleves at navigere der; interviewempirien indgår som baggrund for, hvordan jeg forestiller mig sitet opleves.

Referencer: 
Light, B., Burgess, J., & Duguay, S. (2018). The walkthrough method: An approach to the study of apps. _New Media & Society, 20_(3), 881–900. https://doi.org/10.1177/1461444816675438](https://doi.org/10.1177/1461444816675438)**

Hertzum, M. (2020). _Usability testing: A practitioner's guide to evaluating the user experience_. Morgan & Claypool. https://doi.org/10.1007/978-3-031-02227-2

Davis, J. L. (2020). _How artifacts afford: The power and politics of everyday things_. MIT Press. [https://doi.org/10.7551/mitpress/11967.001.0001](https://doi.org/10.7551/mitpress/11967.001.0001?utm_source=chatgpt.com)

Hvilke fund: xxxx


Hvad jeg foreslår ændret: xxxx


Min walkthrough analyse - skal koges ned til 'fund' bagefter


# Walkthrough af audit.os2.eu – observationsark

**Metode:** Walkthrough-teknikken fra Light et al. (2018), kontekstualiseret af sitets forventede brugskontekst (vision, driftsmodel, governance). Gestalt-principperne er min analytiske linse. Formuleringen til metodeafsnittet: jeg låner teknikken og kontekstanalysen, ikke den sociokulturelle dagsorden.

**Gennemgangsvilkår (udfyld før start):**

* Dato for gennemgang: 3. november 2026

* Siteversion (stående på forsiden): Version v0.1.0 – udgivet 4. maj 2026

* Browser: Safari, version 26.5.2 

* Screenshots gemmes: i repo mappen her 

***

## Fund 1: Forsiden har fine info, men mangler at italesætte modtageren 

Forventet brugskontekst (environment of expected use)

Sitet fremstiller sig som et overblik over "OS2-produkt evalueringer og vurderinger", som også er overskriften på forsiden. Overblikket fremstår dog forvirrende, da der er en tvetydighed om hvad det præcis indebærer, når der også bruges ord som: evaluering, vurdering, formular, evalueringsrapport, governancerapport, kladde, processbeskrivelse og tjekliste. Det er uklart om det alt sammen er forskellige dokumenter, eller om nogle af ordene dækker over det samme. 

forventninger til brugeren (og hvem er brugeren?)
Med mandat fra bestyrelsen stiller sekretariatet krav til produktfællesskaberne efter OS2s styringsmodel. Forsiden formulerer selvevaluering to gange årligt som en "forudsætning" for at være OS2-produkt. Dermed er deltagelse i evaluringsprocessen en reel en betingelse for at bevare status som OS2-produkt, men konsekvensen står ikke beskrevet direkte på forsiden, men må antages at man kan blive smidt ud af OS2, hvis ikke evalueringen laves - eller den laves og man ikke lever op til kravene. 

Rollen som fremhæves er  styregruppen, hvis ansvar det det er produktet gennemfører og opdaterer en selvevaluering og er i dialog med sekretariatet - men det ligger skrevet mellem linjerne, at trods ansvaret er forankret i styregruppen, bliver det i praksis produktforvalteren, som er tovholder på udfyldningen, hvilket man evt kunne nævne. 

Det er ikke tydeligt, hvem sitet henvender sig til. Der står ikke "hej produktforvalter – her starter du"; sitet er snarere et åbent overblik for enhver, der vil forstå, hvordan OS2s governance. Det er værd at bemærke, at der fra os2.eus side "OS2s styringsmodel (governance)" netop linkes hertil som dokumentation for hvordan OS2 evaluerer governance. Sitet har altså reelt to slags læsere – den interesserede iagttager og styregruppen, der via produktforvalteren har pligt til at udfylde deres produkts selvevaluering – men taler mest til den første. Forsiden omtaler først "alle produkter" og "styregruppen" i tredje person – og først når værktøjerne specificeres ("På denne side finder du…"), dukker "du" op, uden at der noget sted står, hvem der menes.


## Fund 2: For mange udefinerede ' begreber'
evaluering, vurdering, selvevaluering, formular, evalueringsrapport, governancerapport, kladde, procesbeskrivelse, checkliste …

definitionerne og relationen mellem dem ikke bliver tydeliggjort.

Det fremgår i interviews og i mathias brugertest, at de ikke tydeligt kender forskellen

Så en principiel anbefaling: 

> Saml og forklar det centrale begrebsapparat og brug betegnelserne konsekvent.

“Vidste du?”-boks fra governance-siden være et eksempel på en eksisterende OS2-løsning


## Fund 3: Navigationsmenuen er for indforståede 






***

## Fravær (på sit-niveau)

Hvad er der _ikke_? Hjælpeside, FAQ, kontakt, intro til nye produktforvaltere, eksempler på en udfyldt selvevaluering, søgefunktion, engelsk version … kan fraværet kan læses som en antagelse om brugeren...?

> findes frist, status eller konsekvens nogen steder på sitet?
 



# Mathias' brugertest på audit.os2.eu (OS2ai)

Mathias er teknisk stærk; han arbejder selv med JSON, Git og bruger en AI-agent (MCP) til at søge i OS2-dokumentation. Det er en fordel, fordi han kan vurdere sitet ud fra ideelle principper for softwaredesign og har et godt sprog for det. Det tæller dog også med i analysen, at aspekter, der er intuitive for ham, kan volde produktforvaltere med mindre teknisk snilde problemer – og at én testperson kan indikere problemer, men ikke bevise dem. 
***

## 1. Førsteindtryk og procesdiagrammet

* Mathias læser forsiden først og leder efter en overordnet introduktion: hvad bruges evalueringen til, og hvad er forudsætningerne? Han finder bullet-listen ("denne side finder du") og klikker videre til procesbeskrivelsen – og lander korrekt på det, opgaven bad om.

* **Positivt:** Procesdiagrammet kan skannes hurtigt: "et styregruppespor, et bestyrelsesspor" giver overblik over "hvad bliver gjort hvor". Sektionen med roller og ansvar roses specifikt – i et centralt projekt er det ellers "svært... at lige blive skarpe på hvem gør hvad", især hvis man "bare tager teten og løber med noget".

* **Negativt:** Første blik er "måske en lille smule overvældende"; der er mange detaljer på ét view. Ønske: diagrammet bør gå fra venstre mod højre i stedet for at "gå rundt" (top-ned/cirkulært mermaid-layout).

## 2. Informationsarkitektur og navigation

* Uden det direkte link på forsiden ville han folde "Evalueringer" ud i venstremenuen og gætte sig frem: først "formular"/"generator" (forkert), derefter "vurderingsgrundlag" → underside "Processen" → samme side.

* Samme side nås altså via flere veje, og menuens navne matcher ikke brugerens mentale sprog ("vurderingsgrundlag" som vej til processen er kontraintuitivt).

* Selvevalueringssformularen findes via bullet-listens direkte link eller som første underpunkt under "Evalueringer" – findbar, men navngivningen er uklar nok til at han skal gætte.

## 3. Tre rapporter – sitets største forvirringspunkt

* Selvevalueringssformularen, governance-rapporten og evalueringsrapporten: Mathias' første reaktion er "Jamen er det ikke et og samme?" Selv efter at læse 30 sekunder kan han ikke udlede flowet: "man starter med Governance Rapporten når man først går i gang og så hvis man vil opdatere det så bliver det en evaluering rapport eller hvad? Det forstår jeg faktisk ikke." (Det reelle flow – formular → generator → governance-rapport → evalueringsrapport med vurdering og vurderingsgrundlag – må Anna forklare ham.)

* **Hans diagnose (centralt for analysen):** "man er supertransparent omkring det, men det er så måske lidt på bekostning af forståelsen af processen og det samlede forløb og stadierne derunder."

* Generatoren tilhører sekretariatets arbejdsgang – i den brede menu "støjer det mere eller forvirrer end det gavner". Foreslag: dokumentér den i procesdiagrammet eller som små fodnoter.

* Anna foreslår at dele menuen op ("det her er for dem der udfylder, det her er for dem der evaluerer") – Mathias er enig.

## 4. Manglende startpunkt

* "Der er meget jeg lige skal overskue for at forstå den store hele kontekst og også bare 'hvor skal jeg starte' – det kan komme til at virke overvældende, fordi der er faktisk ikke en klar tid hvor der står hvor skal du starte henne."

* Alt på sitet fremstår lige vigtigt; der mangler en tydelig entry point/CTA for den nye bruger.

## 5. Udfyldelsesflow og teknisk barriere

* Flowet forstår han efter læsning: visuel formular i browseren → JSON-fil med struktureret data → lægges på GitHub-repo eller sendes pr. e-mail; import/eksport af kladde er muligt.

* For ham giver det god nok mening ("understøtte versionsstyring og publicering på GitHub repository") – men en projektleder-kollega "ville være forvirrede" og opleve "en teknisk barriere" ved "hvordan gør jeg det her".

* De fleste vil starte i den visuelle formular i browseren; barrieren opstår ved indsendelse/publicering ("når man så skal indsende den eller... publicere på et repo... så tror jeg mange vil møde den der teknik"). Selv "den nemme løsning" forekommer svær for ikke-tekniske.

* Holdning: fint at starte "lidt simpelt eller scrappy", men der er "potentiale for nogle forbedringer ved... at lave en nemmere løsning for de ikke-tekniske" – sætte barren lidt ned og gøre det intuitivt for en bredere målgruppe. Alternativ lovende praksis: spørge en kollega, der "ved hvad JSON er".

## 6. Åbenhed: skal læses mellem linjerne

* Under "Evalueringsrapporten" står, at den endelige vurdering "udgør OS2s officielle vurdering på det givne tidspunkt" – men at den bliver offentligt synlig "skal man lidt læse mellem linjerne". Konkret forslag: tilføj "og den vil være synlig på XYZ under produkt- eller projektsiden og indgå i bestyrelsens kvartalsmæssige beretning".

* På evalueringssiderne/under "Processen" kan han ikke finde tegn på offentliggørelse ("nej, det synes jeg \[ikke]") – og er enig i, at sitet kan tolkes som "noget meget internt, der aldrig kom ud noget sted".

* **Bias-konsekvensen (vigtigste analytiske pointe):** Er åbenheden ikke kendt upfront, bliver den "baghovedet på dem der udfylder" → "der kommer jo en... uhensigtsmæssigt bias i hvad man egentlig skriver og hvad man er åben om". Man får "chancen til at beskytte sig selv" – fx om sikkerhedshuller, fordi "alle vil jo gå ind og finde det link". Uklar UX omå offentlighed påvirker altså selve datakvaliteten i selvevalueringerne.

* Løsning: holde vurderingen som kladdedokument indtil feedback fra sekretariatet – "lavpraktisk med en fil om den så er på et privat repo eller om den ligger i en lukket OS2-boks på Nextcloud", men stadig med bevidsthed om, at der publiceres på et tidspunkt. Feedback fra sekretariatet inden endelig publicering er "god stil".

* Mathias ville selv have spurgt sekretariatet mundtligt – "men det er jo nok også en luksus for mig, fordi jeg... har kontor i Aarhus": nærheden til sekretariatet er en fordel, ikke alle produktkoordinatorer har.

## 7. Log-siden

* "Det er også meget transparent" – men formålet er uklart: er det en beslutningslog eller en versionshistorik? "Det kan jeg ikke helt gennemskue... det virker egentlig bare som, hvad har der været aktivitet med evalueringsværktøjer og governance-styringsmodeller."

## 8. Forventning til next steps

* Efter udfyldelse forventer han publicering til sekretariatet, styregruppen, koordinationsgruppen og "interesserede anvender-myndigheder", hvorefter projektet internt kan sige "her er der mere vi kan arbejde med... hvad vil fordelene være, og hvordan kommer vi derhen" med trafiklysene – i dialog med koordinations- og styregruppe.

* Det matcher det faktiske flow – dvs. sidens rækkefølge kan udledes med intuition, men ikke med sikkerhed fra sitet alene.

***

## 9. Samlede forbedringsforslag til UX/UI (fra walkthrough'en)

1. **Tydelig "start her"/CTA** på forsiden – et klart svar på "hvor skal jeg starte".

2. **Skil de tre artefakter ad** (formular / governance-rapport / evalueringsrapport) med tydeligere navngivning eller ét samlet procesview; generatoren ud af den brede menu (fodnote eller ind i procesdiagrammet).

3. **Del menuen op** efter målgruppe: dem der udfylder vs. dem der evaluerer/læser.

4. **Enklere indsendelsesflow for ikke-tekniske** – "sætte barren lidt ned", bredere målgruppe.

5. **Horisontalt procesdiagram** (venstre mod højre i stedet for top-ned/cirkulært).

6. **Eksplicit angivelse af, hvor vurderingen publiceres** (projekt-/produktside, bestyrelsens kvartalsberetning) – ikke kun "mellem linjerne".

7. **Understøt et kladde-/privat-stadie** indtil vurdering fra sekretariatet, med tydelig kommunikation om, at der publiceres senere.

## 10. Metode- og generaliserbarhedsbemærkninger

* Mathias er den teknisk stærkeste af de interviewede (JSON/Git/agent-harness) – **og stadig** oplever han procesdiagrammet som overvældende, de tre rapporter som uadskillelige og loggen som uklar. Det tyder på, at forvirringspunkterne er strukturelle i sitets IA snarere end et spørgsmål om brugernes kompetencer.

* Sandkasseperspektiv: OS2ai har ikke udfyldt endnu; walkthrough'en viser sitet som en førstegangsbruger møder det (finde proces, formularen og afleveringsmåden) – et komplement til de øvrige interviews, der alle kendte sitet overfladisk på forhånd.

* Hans fund om manglende synlighed om offentliggørelse validerer de øvrige PK'ers overraskelse ("ikke klar over at selveva ligger åbent") – nu dokumenteret live i selve interfacet.

* Koblingen UX → bias → datakvalitet er et stærkt argument i analysen: uklar kommunikation om offentlighed ændrer ikke kun oplevelsen, men potentielt også indholdet af de indsendte selvevalueringer.








