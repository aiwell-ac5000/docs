# Regulering

Alle regulatorparametre (P, I og D-ledd o.l.) i Aiwells system er proprietær informasjon og er ikke åpent tilgjengelig. Systemet konfigureres basert på kundens behov og anlegges egenskaper. Det reguleres basert på:

* Tur-temperatur sekundærside (T25)
* Retur-temperatur sekundærside (T26)
* Retur-temperatur primærside (T24)
* Tur-temperatur sekundærside på veksler (T27)
* Overflatetemperatur
* Effekt

Anlegget må alltid bestykkes med T24 og T25, siden disse er kritiske for å unngå frostskader og overoppheting. Anlegget må også ha minst èn overflatetemperaturføler. Dersom anlegget har flere overflatetemperaturfølere, vil kaldeste benyttes. T27 benyttes kun til regulering når Aiwell styrer ventil på vekslerens primærside.

Reguleringen vil alltid levere laveste pådrag basert de ulike kriteriene. Det vil si at dersom temperaturen på T26 retur eller overflate er nærme settpunkt, vil reguleringen prioritere disse før T25 selv om denne er lavere enn ønsket driftstemperatur. Regulatoren må også ta hensyn til hvor raskt veksler reagerer på endringer i pådrag, slik at systemet ikke overstiger ønsket temperatur. Normalt vil derfor pådraget ligge under 100%, selv om målt temperatur er lavere enn settpunktet, så lenge temperaturen er stigende. Pådraget vil økes gradvis intill temperaturen stiger med ønsket hastighet.

Regluering basert på T24 er invers, slik at pådraget senkes ved lavere temperatur. Dette for å unngå frostskader, primært under oppstart med svært kald glykol.

Siden varmeveksler ikke leveres av Aiwell, og det er stor variasjon i disse, vil reguleringen alltid måtte tilpasses den aktuelle varmeveksleren. Kundens ønsker og behov vil også være avgjørende for hvordan reguleringen settes opp. Utstyret leveres derfor med en standard konfigurasjon som kan tilpasses etter behov og i dialog med kunden under prøvedrift.

## Tuning av regulator

AC5000 leveres med standard innstillinger som er tilpasset de fleste innstillinger. Kunder som ønsker en raskere eller tregere regulering, eller har spesielle behov, kan få dette tilpasset. 

Spesielt når det er ønskelig med raskere øking av pådrag, er det viktig å merke seg at dette begrenses av hvor rask varmeveksleren og eventuelt fjernvarmen reagerer. Dersom reguleringen økes for mye, vil det kunne føre til overoppheting eller svingninger i pådraget som hindrer anlegget i å nå ønsket driftstemperatur. Anlegget kan derfor ikke øke pådraget raskere enn at det klarer å regulere ned igjen før temperaturen overstiger ønsket nivå. Dersom Aiwell ikke styrer tilførsel av varme på primærsiden, vil det være nødvendig å tilpasse regulator til det enkelte anlegg. 