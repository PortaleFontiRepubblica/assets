# La rete di ontologie del progetto Portale delle Fonti della Storia della Repubblica Italiana

## L'ontologia IRHO - Italian Republic History Ontology

È il punto di entrata di tutta la rete in quanto importa tutti i moduli creati, aggiungendo proprietà generali come title, shortName, ecc.

## I moduli ontologici della rete
I moduli della rete sono introdotti brevemente nel seguito.

### [Ontologia delle Organizzazioni (Politiche)](https://w3id.org/italia/republic-history/onto/org)

![Rappresentazione grafica dell'ontologia sulle organizzazioni (politiche)](https://raw.githubusercontent.com/PortaleFontiRepubblica/assets/main/ontologies/org/Grafici/org.png)

L'ontologia rappresenta vari tipi di organizzazioni anche nel contesto costituzionale e politico (e.g., partiti politici, gruppi parlamentari, ecc.).

### [Ontologia delle Persone (pubbliche)](https://w3id.org/italia/republic-history/onto/person)

![Rappresentazione grafica dell'ontologia sulle persone](https://raw.githubusercontent.com/PortaleFontiRepubblica/assets/main/ontologies/person/Grafici/person.png)

Il modulo ontologico sulle persone consente di rappresentare persone con una certa rilevanza pubblica e con un mandato politico. All'interno dell'ontologia sono modellati i vari ruoli applicando design pattern noti e già presenti in ontologie relative nazionali.

### [Ontologia degli eventi pubblici](https://w3id.org/italia/republic-history/onto/event)
![Rappresentazione grafica dell'ontologia degli eventi](https://raw.githubusercontent.com/PortaleFontiRepubblica/assets/main/ontologies/event/Grafici/event.png)

![Rappresentazione grafica dell'ontologia degli eventi](https://raw.githubusercontent.com/PortaleFontiRepubblica/assets/main/ontologies/event/Grafici/sitting-debate-discussion/sitting-debate-discussion.png)

Il modulo ontologico sugli eventi pubblici riutilizza quello nazionale per rappresentare eventi significativi del dominio del progetto. È infatti attraverso questo modulo che vengono modellati eventi quali l'elezione del Presidente della repubblica, il suo giuramento, eventuali sedute parlamentari con i vari discorsi, dibattiti.

### [Ontologia degli archivi](https://w3id.org/arco/ontology/archive)
![Rappresentazione grafica dell'ontologia degli eventi](https://raw.githubusercontent.com/PortaleFontiRepubblica/assets/main/ontologies/archive/Grafici/archive.png)

Il modulo ontologico degli archivi del portale è stato integrato pienamente nella rete di ontologie ArCo del Ministero della Cultura. È pertanto mantenuto in quel contesto. Essendo integrato in quella rete riutilizza tutti gli elementi indipendenti dallo specifico dominio (e.g., date, luoghi, responsabilità) che si trovano in ArCo aggiungendo elementi specifici degli archivi, e.g., il concetto di ArchivalResource e ArchivalResourceCollection, la gerarchia archivistica.


### [Ontologia dei lavori (creativi)](https://w3id.org/italia/republic-history/onto/work)
![Rappresentazione grafica dell'ontologia dei lavori (creativi)](https://raw.githubusercontent.com/PortaleFontiRepubblica/assets/main/ontologies/work/Grafici/work.png)

Il modulo ontologico dei lavori è un modulo di meta livello creato per racchiudere in concetti più astratti, e principalmente derivati dal modello FRBR - Functional Requirements for Bibliographic Records a cui il modulo si allinea semanticamente, una serie di elementi del dominio riconducibili a lavori creativi, o documentazione creata dai rappresentanti di quell'epoca, e alle loro rappresentazioni fisiche.
In particolare, è attraverso questo modulo che vengono poi creati e tenuti insieme concetti specifici (e.g., i bollettini redatti a seguito di sedute parlamentari) e moduli ontologici specifici relativi a discorsi (e.g., specifici discorsi dei presidenti della repubblica) e gli atti con valenza legale/leggi.

### [Ontologia dei lavori (creativi)](https://w3id.org/italia/republic-history/onto/work)
![Rappresentazione grafica dell'ontologia dei lavori (creativi)](https://raw.githubusercontent.com/PortaleFontiRepubblica/assets/main/ontologies/work/Grafici/work.png)

Il modulo ontologico dei lavori è un modulo di meta livello creato per racchiudere in concetti più astratti, e principalmente derivati dal modello FRBR - Functional Requirements for Bibliographic Records a cui il modulo si allinea semanticamente, una serie di elementi del dominio riconducibili a lavori creativi, o documentazione creata dai rappresentanti di quell'epoca, e alle loro rappresentazioni fisiche.
In particolare, è attraverso questo modulo che vengono poi creati e tenuti insieme moduli ontologici specifici relativi ai bollettini (e.g., i bollettini del senato), i discorsi (e.g., specifici discorsi dei presidenti della repubblica), gli atti con valenza legale/leggi.

## Licenza
Tutti i moduli ontologici sono rilasciati secondo la licenza aperta Creative Commons Attribution 4.0.
