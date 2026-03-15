# Rapport Assistent

**Rapport Assistent** analyserer valgt tekst og gir innsikt i innholdet. Den foreslår også en forbedret versjon som gjør rapporten klarere, mer strukturert og profesjonell. Dette verktøyet er laget som en React-komponent med AI-integrasjon, som gjør det enkelt å bruke direkte i rapporterings- eller dokumentverktøy.

---

## Funksjoner

- Analyserer valgt tekst automatisk
- Genererer en forbedret versjon av teksten
- Viser status for teksten (`complete`, `incomplete` eller `unknown`)
- Kopier og sett inn forbedret tekst direkte i dokumentet
- Rediger forbedret tekst før innsetting
- Brukervennlig og responsivt UI med MUI-komponenter

---

## Installasjon og bruk

Alt du trenger å gjøre for å komme i gang:

```bash
# 1. Klon repository
git clone https://github.com/<ditt-brukernavn>/rapport-assistent.git
cd rapport-assistent

# 2. Installer avhengigheter
npm install
# eller
yarn install

# 3. Opprett .env i prosjektets rotmappe med din AI API-nøkkel
# REACT_APP_AI_API_KEY=din_api_nokkel

# 4. Start utviklingsserveren
npm start
# eller
yarn start

# 5. Åpne http://localhost:3000 i nettleseren

# Bruk:
# - Marker tekst i rapporten eller dokumentet.
# - Rapport Assistent analyserer automatisk teksten.
# - Se analysen og den forbedrede versjonen foreslått av AI.
# - Dobbeltklikk den forbedrede teksten for å redigere den manuelt om ønskelig.
# - Bruk knappene for å sette inn teksten tilbake i dokumentet eller kopiere den til utklippstavlen.