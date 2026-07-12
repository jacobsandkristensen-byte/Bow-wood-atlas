
# JSK Bow Wood Atlas v0.2

Mobiltilpasset feltprototype for å:

- vise et ekte OpenStreetMap-kart
- hente GPS-posisjon
- registrere trær med koordinater og notater
- filtrere funn etter treslag og status
- føre enkel feltjournal
- eksportere/importere sikkerhetskopi som JSON
- installere siden på iPhone-hjemskjermen

## Publisering med GitHub Pages

1. Slett den feilnavngitte filen `index.html.html` i repositoryet.
2. Last opp alle tre appfilene i rotmappen:
   - `index.html`
   - `manifest.webmanifest`
   - `service-worker.js`
3. Gå til **Settings → Pages**.
4. Velg **Deploy from a branch**.
5. Velg **main** og **/(root)**.
6. Trykk **Save**.

GitHub Pages for et offentlig repository krever ikke abonnement.

## Begrensninger i v0.2

- Kartflisene krever internett.
- Registreringene lagres lokalt i nettleseren.
- Bilder og automatisk Artskart-import er ikke med ennå.
- Demopunkter er kun eksempler, ikke verifiserte lokaliteter.
