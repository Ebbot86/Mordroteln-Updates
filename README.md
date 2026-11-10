# MORDROTELN — Android-uppdateringar

Detta är den **offentliga nedladdningskanalen** för spelet MORDROTELN på Android.

Den kompletta spelkoden finns i ett separat, **privat** repository. Här kommer endast officiella Android-installationsfiler och versionsinformation att publiceras.

## Så fungerar uppdateringar

När MORDROTELNs release-signering har aktiverats, publicerar GitHub Actions automatiskt en ny version under [Releases](https://github.com/Ebbot86/Mordroteln-Updates/releases). Varje version innehåller:

- `MORDROTELN-release.apk` — den signerade appen.
- `latest.json` — version, kontrollsumma (SHA-256), nyheter och nedladdningsadress.

Android-appen kan då läsa [senaste versionsfilen](https://github.com/Ebbot86/Mordroteln-Updates/releases/latest/download/latest.json), kontrollera om en ny version finns och erbjuda nedladdning. Android begär alltid användarens godkännande innan installation.

**Status:** Förberedd. Det finns ännu ingen permanent signerad publicerad release. Ladda inte ner några APK-filer från inofficiella källor.

## Säkerhet och sekretess

Spelkod och utveckling hålls privat. Signeringsnycklar, lösenord och GitHub-tokens hör **aldrig** hemma i detta publika repo. Appens kontrollsumma och Androids signaturkontroll skyddar mot felaktiga uppdateringspaket.
