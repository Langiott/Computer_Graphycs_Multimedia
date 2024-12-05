### Computer_Graphycs_Multimedia vs Computer Visions
La computer graphics e la computer vision sono due discipline fondamentali dell'informatica che si concentrano su immagini e dati visivi, ma con obiettivi opposti. 
##Computer Graphics:
- Obiettivo: Creare immagini e contenuti visivi a partire da modelli matematici, dati e scene virtuali.
- Input e Output: Riceve dati o modelli matematici (es. coordinate 3D, texture) e genera immagini, video o scene visive.
- Applicazioni: Videogiochi, simulazioni, effetti speciali nei film, rendering architettonico, visualizzazioni scientifiche.
- Tecnologie chiave:Rendering 2D e 3D.Modellazione di superfici e texture.Ray tracing e rasterizzazione per effetti realistici.Shader per illuminazione, ombre e materiali.
- Esempio: Creare un modello 3D di una città e visualizzarlo in modo realistico con luci e ombre.

## Computer Vision:
- Obiettivo: Permettere ai computer di comprendere ed estrarre informazioni utili dalle immagini o dai video.
- Input e Output: Riceve immagini o video (fotografie, flussi video) e restituisce interpretazioni o analisi (es. identificazione di oggetti, tracciamento di movimenti).
- Applicazioni: Riconoscimento facciale, guida autonoma, diagnostica medica basata su immagini, sistemi di sorveglianza, robotica.
- Tecnologie chiave:Riconoscimento di pattern e oggetti.Segmentazione delle immagini.Visione stereoscopica per la percezione della profondità.Algoritmi di apprendimento automatico (reti neurali convoluzionali, deep learning).
- Esempio: Identificare pedoni e segnali stradali in un video per un'auto a guida autonoma.

 
Gli strumenti software utilizzati in computer graphics si dividono in categorie specifiche per affrontare diversi aspetti della creazione, manipolazione e rendering di immagini e modelli 3D. Ecco una panoramica dettagliata dei tipi di strumenti menzionati:

## Librerie Grafiche
Queste librerie forniscono API (Application Programming Interface) che consentono agli sviluppatori di creare e gestire contenuti visivi. Si concentrano sull'elaborazione di grafica 2D e 3D a basso livello.
•	Direct3D: Parte della piattaforma DirectX di Microsoft, Direct3D è una libreria per lo sviluppo di grafica 3D, utilizzata soprattutto nei videogiochi e nelle applicazioni Windows. Supporta il rendering hardware, la gestione di shader e tecniche avanzate come il ray tracing.

•	OpenGL: Una libreria multipiattaforma sviluppata originariamente da Silicon Graphics Inc. (SGI), OpenGL è molto diffusa in applicazioni 3D e CAD grazie alla sua flessibilità. È open standard e supporta funzionalità avanzate come effetti di illuminazione e texture.

•	Performer (SGI): Un'estensione ad alto livello di OpenGL sviluppata da Silicon Graphics Inc. È progettata per applicazioni in tempo reale, come simulazioni e visualizzazioni, fornendo astrazioni che semplificano lo sviluppo di scene complesse.

## Programmi di Rendering
Questi strumenti si concentrano sull'elaborazione finale delle immagini 3D a partire da modelli e dati visivi. Il rendering può essere fotorealistico (con simulazioni realistiche di luce e materiali) o stilizzato.

•	PovRay (Persistence of Vision Raytracer): Un software open source per il ray tracing. Consente la creazione di immagini fotorealistiche partendo da descrizioni testuali di scene 3D. È noto per la sua flessibilità ma ha una curva di apprendimento ripida.

•	Rayshade: Un altro motore di rendering che utilizza il ray tracing. È meno sofisticato rispetto a PovRay ma offre funzionalità essenziali per creare immagini con ombre e riflessioni realistiche.

•	BMRT (Blue Moon Rendering Tools): Compatibile con RenderMan, è un motore di rendering che supporta shader complessi, ombre morbide e altri effetti avanzati. Molto utilizzato in passato per la produzione cinematografica.

## Strumenti di Modellazione
Questi strumenti permettono la creazione di modelli 3D attraverso interfacce interattive, consentendo agli artisti di manipolare oggetti nello spazio virtuale.

•	Gli strumenti di modellazione offrono funzioni come estrusione, suddivisione di superfici, modellazione basata su curve (NURBS) e gestione di mesh poligonali.

•	Utilizzati in applicazioni che vanno dalla progettazione industriale all'animazione 3D e al game design.

•	Alcuni software includono anche funzionalità di texturing, rigging e animazione.

## Suite di Strumenti Integrati
Questi pacchetti software combinano strumenti di modellazione e rendering in un unico ambiente, semplificando il flusso di lavoro per artisti e designer.

•	3D Studio MAX: Ora noto come 3ds Max, è sviluppato da Autodesk. È molto utilizzato nell'industria dei videogiochi, dell'architettura e degli effetti visivi. Offre potenti strumenti di modellazione e un motore di rendering integrato.

•	LightWave: Una suite completa per la modellazione e il rendering. È conosciuta per il suo uso nell'industria televisiva e cinematografica, grazie alla qualità del rendering e alle sue capacità di animazione.

•	TrueSpace: Era uno strumento di modellazione e rendering facile da usare, ma è stato dismesso. Era popolare per i principianti e gli hobbisti.

•	Maya: Uno degli strumenti più completi per la creazione di contenuti 3D, sviluppato da Autodesk. È uno standard nell'industria cinematografica e dei videogiochi, grazie alla sua flessibilità e ai potenti strumenti di scripting.

•	Blender: Una suite open source che include strumenti per modellazione, texturing, rendering, rigging, animazione e compositing. È apprezzato sia dai professionisti che dagli hobbisti per le sue funzionalità avanzate e la comunità attiva.

•	Unity è una piattaforma di sviluppo 3D in tempo reale che combina funzionalità di modellazione, rendering, scripting e interazione per creare applicazioni grafiche e giochi interattivi.Utilizzato per giochi AAA per realtà virtuale e aumentata o cinematografia

##Integrazione e Flusso di Lavoro
Spesso, questi strumenti non operano isolatamente. Ad esempio, un artista può:
1.	Usare un software di modellazione come Blender o Maya per creare i modelli 3D.
2.	Affinare l'aspetto visivo con una libreria come OpenGL per sviluppare un'applicazione interattiva.
3.	Finalizzare il rendering con un motore avanzato come PovRay o BMRT per immagini o video di alta qualità.
