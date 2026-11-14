# 🎲 Mini-Games

Kleine Online-Spiele für die Runde am Tisch – jeder spielt auf dem eigenen Handy, verbunden über einen Raum-Code oder einen geteilten Link. Kein Server, kein Login: jedes Spiel ist eine statische Seite auf GitHub Pages.

| Spiel | Link | Ordner |
|---|---|---|
| 🍞 **Knäckebrot** (Shithead) – 2 bis 12 Spieler | https://zahngel18.github.io/knaeckebrot/ | `/` |
| 😈 **Niveaulimbo** – Lückentext-Partyspiel mit schwarzem Humor, ab 3 Spielern | https://zahngel18.github.io/knaeckebrot/niveaulimbo/ | `niveaulimbo/` |

## Knäckebrot

- Einer tippt „Neues Spiel starten" und teilt den 5-stelligen Code
- Die anderen geben den Code ein und treten bei
- Tutorial über den ❓-Button, Joker-Option in der Lobby

## Niveaulimbo

- Einer macht eine Runde auf und teilt den Link (AirDrop, WhatsApp) oder zeigt den QR-Code – wer den Link öffnet, sitzt direkt am Tisch
- Jede Runde ist jemand Boss, liest die Frage vor und krönt die beste (schlimmste) Antwortkarte
- In der Lobby: Punkte zum Sieg, „Kollege Zufall" als blinder Mitspieler und eigene Karten für Insider
- Karten stehen in `niveaulimbo/karten.js` und lassen sich dort einfach ergänzen

## Neues Spiel hinzufügen

Eigener Ordner mit einer `index.html`, gemeinsame Bibliotheken liegen in `vendor/`. Alles auf `main` wird automatisch nach GitHub Pages veröffentlicht.
