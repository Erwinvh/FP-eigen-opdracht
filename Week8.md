# Reflectie van week 8

## Situatie 1: live updaten en Map objecten
### Context:
Na op maandag druk bezig te zijn geweest waren we gestopt met een functioneel product. Echter wilde ik nog door gaan om fouten er uit te halen. Een van de fouten die ik op hoge prioriteit had staan was het live updaten. Een ander probleem was dat de map zijn objecten hernoemd moeten worden zodat de NPC's door zouden hebben dat de artist op de stage moet en de visitors er voor.

Ik heb niet genoeg tijd om het onderzoek te doen op waarom de live updaten niet wil lukken bij de artist/stage en om de map aan te passen in de avond. 

___
### De mogelijkheden:
#### Mogelijkheid 1: Map aanpassen
Ik kan de map aanpassen daardoor werkt de simulator weer zoals hij hoort en kan de rest van de groep door.

#### Mogelijkheid 2: live updaten
Ik kan de agenda module zijn laatste issue op proberen te lossen, hierna hoeft er bijna niks meer aan gedaan te worden. Echter weet ik geen oplossing en zou het me veel tijd kosten om er achter te komen hoe ik het moet oplossen. 

____
### Resultaat:
Ik heb besloten om met mogelijkheid 1 te gaan. Na dit te hebben gedaan kreeg ik een idee over hoe ik het live updaten kon oplossen. Dit ben ik toen snel gaan proberen en kwam tot de conclusie dat het uiteindelijk maar een simpele methode was die ik moest toevoegen. nu werkt het live updaten als een zonnetje. Hieronder bevind zich de code van de toegevoegde update die in andere classen wordt gebruikt om de update uit te voeren.

```Java

    public void resetData(){
        this.data = FXCollections.observableArrayList();
createTable();
    }

``` 

----
### De Redenering
Ik had noet veel tijd aan mijn handen en heb de makkelijkste taak gepakt. Toen ik een idee kreeg dat misschien zou werken wilde ik hem uitvoeren ook al zat ik zonder tijd. Na wat plannen te hebben verschoven heb ik mijn idee uitgevoerd en het was een success. De reden dat ik alsnog door ben gegaan is omdat naar mijn mening je altijd moet reageren op een idee op het moment anders loop je het risico om het te vergeten.
