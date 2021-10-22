Vi har valgt oppgaven om Ruter, 
der vi skal forutsi hvor mange passasjerer det er ombord 
utifra gitt dato.

Vi tenker en polynom regresjon vil fungere best for denne oppgaven.
Tanken bak er at dette ikke er en datasett som følger et bestemt mønster, 
som for eksempel en lineær model der antall passasjerer øker med hver dag.
Det vil være mye variasjon i antall passasjerer og polynom regresjon vil passe best med
dette mønsteret.


Ettersom datasettet er litt lite for å kunne forutsi hvor mange passasjerer det vil være på en gitt dato har vi 
valgt å dele det opp i ukedager for å kunne forutsi dette istedet ettersom det da vil være lettere å se trendene i datasettet. 

Vi har dermed trent datasettet vårt til algoritmen, for så å se "R-squared" verdien for å finne ut om polynom regresjon er det
beste for vårt tilfelle. Det viste at det ikke var det ettersom R verdien var så lav. Men dette er ikke nødvedigvis fordi det er
en dårlig "fit", men heller fordi datasettet er såpass lite at det vil ikke gi et nøyaktig resultat. 

Vi testet dermed for å se hva som er det forutsatte resultatet av antall passasjerer på en mandag og fikk resultatet 16 passasjerer. 
Vi testet i tillegg for en søndag for å se om det da er mindre, ettersom vi vet at det vanligvis er mindre passassjerer på en søndag. Det var da mindre dermed vet vi at det stemmer i det minste litt, selv om det ikke er et spessielt nøyaktig resultat. 
