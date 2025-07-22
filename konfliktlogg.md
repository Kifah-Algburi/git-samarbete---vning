# Konfliktlogg – Git-samarbete

## Hur uppstod konflikten?
Konflikten uppstod när två olika branches (main och person-a) ändrade samma rad i `artikel.md`. Git kunde inte automatiskt avgöra vilken version som skulle behållas.

## Hur löste jag konflikten?
Jag gick in i konfliktfilen och redigerade den manuellt. Jag valde att behålla den nya texten från person-a och tog bort konfliktmarkeringarna (`<<<<<<<`, `=======`, `>>>>>>>`).

Sedan gjorde jag en commit med meddelandet: `Löst merge-konflikt i artikel.md`.

## Vad lärde jag mig?
Jag lärde mig hur Git visar konflikter, hur man läser markeringarna och hur man manuellt redigerar för att lösa dem. Det var lite svårt i början, men lärorikt.
