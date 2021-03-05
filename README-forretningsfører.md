# Digital samhandling ved eiendomshandel (meglere-forretningsførere)
Digital samhandling mellom eiendomsmeglere og forretningsførere i forbindelse med gjennomføring av elektronisk eiendomshandel.
Samhandling mellom meglere og forretningsførere er et underprosjekt av DSVE og har sitt eget utvalg for faglige og tekniske avklaringer.

## Overordnede mål (meglere-forretningsførere)
Muliggjøre en sikker og effektiv utveklsing av standardiserte og strukturerte data mellom megler-fagsystem og forretningsfører-fagsystem som er nødvendige for å gjennomføre eierskifte og elektronisk tinglysing.

## Punkter til avklaring i DSVE
* Benytte Altinn Formidlingstjenester for meldingsutveksling for dette underprosjektet
* Benytte AKELDO for aktører og capabilites

## Planlagte arbeidsoppgaver (meglere-forretningsførere)
* Beslutte faglig enighet om prosessflyt, kontaktpunkter og foreslåtte meldingstyper (faglig utvalg)
* Avstemme feltstøtte (strukturert informasjon ja/nei) hos forretningsfører-systemleverandører (teknisk utvalg)
* Avstemme feltstøtte (strukturert informasjon ja/nei) hos megler-systemleverandører (teknisk utvalg)
* Beslutte feltliste (DSVE-modell) for hver av de foreslåtte meldingstypene, samt hvilke felter som skal være obligatoriske

# Begrep
[Oversikt over begrep](spesifikasjoner/forretningsfører/begrep/README.md)

# Prosesser og kontaktpunkter 
* [Forhåndsavklaring](spesifikasjoner/forretningsfører/prosesser/README-forhåndsavklaring.md)
* [Fastprisavklaring](spesifikasjoner/forretningsfører/prosesser/README-fastprisavklaring.md)

# Meldingstyper (under utarbeidelse)
### Opplysninger fra forretningsfører (meglerpakke) 
* Overføring av forretningsførerinformasjon til megler.
* Overføring av ustrukterte dokumenter (vedtekter, regnskap o.l) i tillegg til strukturerte data.
* Informasjon om hvordan forkjøpsrett avklares
* [Oversikt og spesifikasjoner](spesifikasjoner/forretningsfører/opplysningerfraforretningsfører/README.md)

### Eierskiftemelding fra megler
* Overføring av eierskiftemelding fra meglersystem til forretningsfører etter gjennomført aksept
* Kan sendes flere ganger fra meglersystem ved endringer i grunnlagsdata (tilsvarende DSVE Kjøpekontrakt)
* [Oversikt og spesifikasjoner](spesifikasjoner/forretningsfører/eierskiftemeldingframegler/README.md)


### Forespørsel (søknad) om styregodkjenning (via forretningsfører)
* Forespørsel fra megler til styret - sendt via forretningsfører 
* [Oversikt og spesifikasjoner](spesifikasjoner/forretningsfører/styregodkjenning/README-forespørsel.md)

### Svar på styregodkjenning  
* Overføring fra forrretningsfører til megler når styregodkjenning er gjennomført.
* Normalt sett alltid positivt utfall, men megler behøver dokumentasjon på godkjenningen
* [Oversikt og spesifikasjoner](spesifikasjoner/forretningsfører/styregodkjenning/README-svar.md)

### Forespørsel om restanser fra megler
* Forespørsel fra megler om utestående restanser som skal innfris som en del av sluttoppgjøret
* [Oversikt og spesifikasjoner](spesifikasjoner/forretningsfører/restanser/README-forespørsel.md)

### Svar på forepørsel om restanser 
* Svar fra forretningsfører om eventuelle restanser
* Kontonummer og KID for innfrielse
* [Oversikt og spesifikasjoner](spesifikasjoner/forretningsfører/restanser/README-svar.md)

