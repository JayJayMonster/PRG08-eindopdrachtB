# PRG08 Eindopdracht deel 2

## Reflectie

## Techniek

### Heeft het gekozen algoritme / library goed gewerkt voor jouw toepassing? Zou een ander algoritme / library beter kunnen werken? Heb je dit geprobeerd?

Ik heb de feature extractor gebruikt voor mijn Trash Detector. Het werkt echt beter dan dat ik verwacht heb toen ik eenmaal mijn model goed getraind had. En ik weet ook hoe ik de accuracy nog hoger kan krijgen en hoe ik het model kan uitbreiden. Ik heb nog geprobeerd om het met een neural network te doen, maar dit bleek net iets te ingewikkeld voor de hoeveelheid foto's en vooral pixels die ik had. Mijn computer kon dat niet aan.

### Heb je genoeg data kunnen verzamelen? Zou jouw applicatie beter kunnen worden als er meer of betere data is? Hoe kom je aan betere data?

Ik had ongeveer 2500 foto's en 5 categorien. Dat is een goed begin maar als je echt een Trash Detector wil maken moet je veel meer categorien hebben. Ik ben nog opzoek gegaan naar extra data en op kaggle kun je nog wel wat extra 'trash' vinden maar niet extreem veel. Mijn TLE team wil bijvoorbeeld graag bananenschillen gebruiken. Hier gaan we dus zelf foto's voor maken zodat we het kunnen implementeren.

### Vindt er training van een model plaats in het prototype en/of in het eindproduct? Licht dit toe.

Ik heb het model getraind met de teachable machine. In het prototype wat je nu ziet wordt dus geen model meer getraind maar alleen nog maar ingeladen. Dit is heel fijn want nu kan ik gewoon alleen het model opnieuw trainen en inladen en hoeft mijn code niet te veranderen.

### Heeft de data een verborgen voorkeur? Wat wordt hier mee bedoeld?

Ik kan zelf niet heel goed zien waar mijn data precies opgetraind is en wat die getraind heeft dus ik weet ook niet of die een verborgen voorkeur heeft. Waarschijnlijk wel want ik ben ervan overtuigd dat er altijd een 'data bias' in datasets zit. Maar wat dat precies is kan ik je zo niet vertellen.

### Wat voor accuracy vind jij goed genoeg voor jouw toepassing?

Sowieso boven de 90% maar het liefst boven de 95%.

### Zijn er privacy concerns in je app? Denk aan het opslaan / versturen van gevoelige data.

Ik sla geen foto's op zelf en verstuur ook geen data dus op dit moment zijn er nog geen privacy concerns. Die gaan pas komen bij de andere features van onze applicatie van TLE.

## Conclusie

### Wat voor feedback heb je gekregen van je TLE team?

Ze vonden het allemaal een heel tof begin en vonden het gaaf. Ze hebben gezegd dat ik het meer moest vormgeven zoals onze wireframes en styleguide en dat ik te titel moest veranderen. Dit heb ik toen ook gedaan.

### Is jouw werk bruikbaar voor het eindproduct van TLE? Ga je er aan doorwerken? Waarom wel of niet?

Zeker! Het is een goed begin en we zijn er meteen mee doorgegaan. We hebben een github aangemaakt en zijn in verschillende branches uitbreidingen aan het maken.
Het was ongeveer wat we wilde doen met TLE alleen kijkt mijn model naar foto's en willen wij het liefst live camera output. Dit is dus ook hoe we het gaan uitbreiden.

### Heeft AI waarde toegevoegd aan je concept, of had dit ook zonder AI gekund?

De AI herkent het afval en verteld je wat je kunt doen met je afval. Ja dit zou ook kunnen door gewoon je afval te googlen maar wij maken het gebruiksvriendelijker en makkelijker om in een keer te zien wat je met je afval kunt doen. Je hoeft niet eerst te kijken wat het is, dan google te openen en door veel verschillende opties te gaan. Je kunt gewoon je afval scannen en krijgt meteen advies.

### Ben je zelf tevreden met het eindresultaat? Werkt het zo goed als je verwacht / gehoopt had? Waarom wel of niet?

Ik ben zeer tevreden met het eindresultaat. Ik vind het best knap dat ik een werkende AI applicatie heb gemaakt in 8 weken. Het werkt beter dan dat ik verwacht had. Ik had namelijk niet zulke hoge verwachtingen. Ik dacht dat iemand anders uit mijn team het zou moeten maken omdat ik het zelf niet zou kunnen. Dit bleek dus niet zo te zijn.

### Is je app zodanig goed dat eindgebruikers er zonder verdere instructies mee uit de voeten kunnen? Waarom wel of niet?

Ja je hebt geen verdere instructies nodig op dit moment. Het is zo makkelijk als je foto uploaden en op classify drukken.

### Link naar github pages

Ik heb geen screencast omdat het echt enorm voor zich spreekt als je de github pages link opent.

### Accuracy uitleg

Het eerste model dat ik zelf heb getraind crashte mijn laptop dus moest ik het met minder foto's doen. Dit was niet heel accuraat. Dus ging ik opzoek naar een andere manier om het model te trainen en kwam ik zo op de teachable machine. Hiermee heb ik mijn model getraind en de accuracy is nu (als hij het herkent) bijna altijd boven de 95%.

## Tweede prototype

Ik heb een tweede prototype gemaakt met een Neural Network ipv de feature Extractor om te kijken of ik daar mijn accuracy mee kon verbeteren. Op dit moment werkt het wel maar wordt mijn laptop er zo traag van dat hij niet echt het model wil trainen. Ik moet nog even wat verder onderzoek doen om te kijken of ik het met mijn andere laptop of PC het misschien wel zou kunnen doen. Ik was dit begonnen omdat de accuracy van mijn model van de feature extractor zo erg niet accuraat was dat ik iets anders wilde proberen. Nu heb ik mijn feature extractor model op een andere manier kunnen trainen waardoor die opeens echt redelijk accuraat is dus heb ik mijn tweede prototype niet meer nodig.
