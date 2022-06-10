Denne programvaren er utviklet som en del av bachelorprosjektet "Selvkjørende mobil robot for datainnsamling fra frukt- og bærproduksjon på Vestlandet".
Oppgaven er skrevet av Aril Torheim, Chris Louis Johnsen og Isak Vamråk Førde våren 2022 ved Høgskulen på Vestlandet, Bergen.

Det er opplastet 3 ulike versjoner av programvaren:

*raspberry_bot simulering:
   -Software som har blitt brukt til simulering i Gazebo

*raspberry_bot fysisk robot:
   -Software som skal kjøres på den fysiske robotplattformen

*raspberry_bot Leikanger:
   -Software som ble kjørt på fysisk robotplattform i Leikanger



"Fysisk robot" versjon er en forbedret utgave av "Leikanger" versjon. Her har det blitt gjort forbedringer som
vi mente var hensiktsmessige etter testing i Leikanger. Eksempelvis er det laget egne launch filer for rekkesentrering, 
høyre rekkefølging og venstre rekkefølging. I Leikanger ble dette gjort med å endre variabler i selve Python skriptene, noe som er tungvint.
De ulike launch filene i denne versjonen har ikke blitt testet på fysisk robot. Det er derfor en fare for "typos" i disse 
filene. Derfor følger også softwaren som er testet i Leikanger.

Egen fil for simulering er også vedlat, da topics for feks. kamera stream har andre navn i simulering enn på fysisk robot.

PDF for installasjon- og brukerveiledning ligger også vedlagt, i tillegg til en beskrivelse av de ulike nodene i programmet. 
Disse vedleggene er klipper ut fra bachelorrapporten.

