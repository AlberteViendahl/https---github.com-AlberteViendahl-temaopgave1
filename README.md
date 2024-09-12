I starten af min kodeproces lavede jeg en plan over, hvordan jeg bedst muligt kunne komme i mål. Jeg startede med at danne et overblik over, hvilke komponenter jeg ville lave, hvorefter jeg lavede filer til dem i VS Code, så jeg visuelt kunne se, hvad jeg skulle lave.

Derefter begyndte jeg at lave mine variabler i min globale CSS. Da det var gjort, begyndte jeg slavisk at lave mine komponenter, og så snart de var lavet, puttede jeg dem ind på deres respektive side. Dette gjorde jeg, så jeg løbende kunne løse de konflikter, der kan opstå ved at putte flere komponenter ind på samme side. Dette fungerede rigtig godt for mig.

En af de nye teknikker, jeg har brugt, er popover-funktionalitet i HTML. Ved hjælp af attributterne popovertarget og popover kan jeg få et element til at poppe frem, når jeg klikker på en knap, og forsvinde igen – alt sammen uden at bruge JavaScript.

Noget andet, jeg har brugt for første gang, er at kunne scrolle elementer ved hjælp af kun CSS. For at tillade vandret scrolling bruger jeg overflow-x: auto. Listen har ingen punkter (list-style: none), og baggrundsfarven er sat via en CSS-variabel. scroll-snap-type sørger for, at elementerne snapper på plads, og padding-inline justerer indrykket i forhold til indholdets bredde.

FAQ
Her benytter jeg mig af elementet <summary>.

<summary>-elementet bruges til at give en kort, klikbar overskrift eller beskrivelse til et skjult indhold, der er inde i et <details>-element. Når brugeren klikker på <summary>, viser eller skjuler det indholdet, som typisk er pakket ind i <details>.

Eftertanker
Næste gang vil jeg gerne sætte mig mere ind i de nye koncepter og bruge dem så tidligt som muligt i opgaven, så jeg kan bruge dem gennem hele processen. Denne gang var jeg tidspresset og endte med at bruge de teknikker, jeg kendte. Så i stedet for at bruge container queries brugte jeg media queries.

Jeg synes også, det var rigtig svært at konvertere Figmas mål til VS Code. Ofte passede det ikke, og jeg endte med at gætte mig frem. Det vil jeg gerne sætte mig mere ind i til næste gang.
