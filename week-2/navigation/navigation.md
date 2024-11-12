# Opdracht: Navigation

## Opzet
Start met een nieuw project met Expo Router en copy/paste wat je nodig hebt uit je vorige project

## Basis opdracht
We gaan nu de bestaande schermen die je eerder maakte aan elkaar koppelen.

Zorg voor een tab navigatie met:
- Listings
- Settings

### ListingsScreen
Zorg voor een knop in `ListingsScreen` (je kiest zelf waar).
Bij het klikken op deze knop open je de `AddListingScreen`.

### AddListingScreen
Na het klikken op de knop in het formulier sluit je dit scherm terug

## Advanced
We bouwen een simpele authenticatie.

Toon eerst het WelcomeScreen.
Na klikken op de Login knop:
- Sla je dit op ahv `useContext`
- Toon je (op basis van de context) het scherm met de tabs

Na klikken op Logout (in AccountScreen):
- Sla je dit op ahv `useContext`
- Toon je (op basis van de context) het WelcomeScreen

## Super advanced
- Hou de status (ingelogd / uitgelogd) bij via `AsyncStorage`
- Maak een LoginScherm waarbij je inlogt met een username. Deze toon je eenmaal ingelogd in de AccountScreen