# konkurranse-utviklingstjenester

Repo for oppgaver til konkurranse om utviklingstjenester.

## Frontend

Lag en løsning som skal erstatte dagens [ansattsøk](http://apps.t-fk.no/ansatte).

Leverer dere også tilbud i kategorien backend skal dere bruke deres egenutviklede API.

Hvis ikke kan dere benytte dere av våre eksisterende APIer for [ansatte](http://ws.t-fk.no/help/persons.html) og [virksomheter](http://ws.t-fk.no/help/departments.html) eller vedlagte [json](data/ansatte.json)

### Ressurser

- [Designmanual](https://designmanual.t-fk.no)
- [ansatte.json](data/ansatte.json)

### Levering

Leveransen skal være et repo på GitHub og en kjørende utgave av løsningen.
I konkurransebesvarelsen legger dere link til repo og løsning.

## Backend

Lag en løsning for et API som skal kunne brukes av ny løsning for ansattsøk [ansattsøk](http://apps.t-fk.no/ansatte).

Leverer dere også tilbud i kategorien frontend skal dere bruke dette APIet som kilde.

Dere står fritt til å designe APIet, men det skal kunne oppfylle de samme funksjonene som våre eksisterende APIer for [ansatte](http://ws.t-fk.no/help/persons.html) og [virksomheter](http://ws.t-fk.no/help/departments.html)

Definisjon av samme funksjonalitet er opp til dere.

[ansatte.json](data/ansatte.json) skal være kilden til APIet. Se for dere at dette er noe som oppdateres f.eks. en gang i døgnet.

### Ressurser

- [Designmanual](https://designmanual.t-fk.no)
- [ansatte.json](data/ansatte.json)

### Levering

Leveransen skal være et repo på GitHub og en kjørende utgave av løsningen.
I konkurransebesvarelsen legger dere link til repo og løsning.

## Drift

Her er det to alternativer.

### Alternativ 1

Dersom dere leverer besvarelse på [Frontend](Frontend) og/eller [Backend](Backend) er oppgaven å sette opp et driftsmiljø for løsningene.

### Alternativ 2

Sett opp et driftsmiljø for MinElev.

Dette er en løsning som består av frontend og mange bakenforliggende tjenester.

Det er også utviklet dummyløsninger for innlogging mm som kan brukes for å få et fungerende oppsett.

### Ressurser

- [minelev-web](https://github.com/telemark/minelev-web) frontend for MinElev
- [minelev-logs](https://github.com/telemark/minelev-logs) logs service for MinElev
- [minelev-logs-stats](https://github.com/telemark/minelev-logs-stats) stats service for MinElev logs
- [minelev-buddy](https://github.com/telemark/minelev-buddy) buddy service for MinElev
- [minelev-buddy-dummy](https://github.com/telemark/minelev-buddy-dummy) dummy for buddy backend

### Levering

Leveransen skal være et repo på GitHub og en kjørende utgave av løsningen.
I konkurransebesvarelsen legger dere link til repo og løsning.

## License

[MIT](LICENSE)

![Robohash image of konkurranse-utviklingstjenester](https://robots.kebabstudios.party/konkurranse-utviklingstjenester.png "Robohash image of konkurranse-utviklingstjenester")
