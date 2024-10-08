# Cursed Worlds Datapack

## Beschreibung

**Cursed Worlds** ist ein Minecraft-Datapack, das dir eine einzigartige Spielerfahrung mit benutzerdefinierten Mechaniken und Dimensionen bietet. Entdecke verschiedene Dimensionen, nutze spezielle Items und Fähigkeiten und meistere herausfordernde Abenteuer.

## Features

### 1. Grundlegende Spieler-Einstellungen
- **Start-Leben**: Jeder Spieler startet mit 3 Herzen (1,5 Herz als Basisleben).
- **Wiederbelebung**: Bei Tod wird der Spieler auf 3 Herzen zurückgesetzt.

### 2. Berry of Life
- **Effekt**: Die „Berry of Life“ erhöht die maximale Gesundheit eines Spielers um 0,5 Herzen. Es gibt keine Begrenzung für die Anzahl der Berries, die gegessen werden können.
- **Wiederbelebung**: Wenn ein Spieler stirbt und Berries konsumiert hat, startet er mit der erhöhten Herzanzahl (z.B. 3,5 Herzen).

### 3. Passive Magie „Razhy“
- **Erwerb von Razhy**: Spieler erhalten Razhy basierend auf ihrer maximalen Herzanzahl:
  - 3 Herzen: 1 Razhy pro Minute (max. 100 Razhy)
  - 4,5 Herzen: 1,5 Razhy pro Minute (max. 110 Razhy)
  - 6 Herzen: 2 Razhy pro Minute (max. 120 Razhy)
  - 7,5 Herzen: 2,5 Razhy pro Minute (max. 130 Razhy)
  - 9 Herzen: 3 Razhy pro Minute (max. 140 Razhy)
  - 10,5 Herzen: 3,5 Razhy pro Minute (max. 150 Razhy)
- **Zusätzliche Razhy**: Ab 10,5 Herzen erhält man für jede weiteren 1,5 Herzen zusätzlich 0,2 Razhy pro Minute.
- **Unabhängigkeit**: Razhy wird regelmäßig erhöht und ist unabhängig vom Astral Mana-System.

### 4. Custom Villager „Magie Lehrmeister Kyuul“
- **Handel**: Kyuul bietet einen Handel an, bei dem Spieler für einen Stack Stein Astral Mana freischalten können.
- **Effekte**:
  - Kyuul hat eine benutzerdefinierte Textur, bleibt an Ort und Stelle und kann nur durch Befehle getötet werden.
  - Wenn Kyuul angegriffen wird, verleiht er dem Spieler den Wither-Effekt und verursacht eine schwarze Blitz-Attacke, die 15 Herzen Schaden anrichtet.
  - Diese Attacke ist nicht mit Milch entfernbar und kann nur durch Tod beendet werden. Kyuul wiederholt die Attacke, bis der Spieler stirbt.

### 5. Astral Fähigkeiten
- **Automatisches Verwenden von Totems der Unsterblichkeit (1)**: Wird bei Kyuul für ein Beacon freigeschaltet. Spieler verwenden automatisch ein Totem der Unsterblichkeit, wenn es im Inventar vorhanden ist, egal ob in der Haupt- oder Nebenhand.
- **Automatisches Verwenden von Totems der Unsterblichkeit (2)**: Wird bei Kyuul für eine Wither Rose freigeschaltet. Auch Totems in Shulkerboxen werden automatisch verwendet.
- **Automatisches Verwenden von Totems der Unsterblichkeit (3)**: Verhindert den Tod im Void. Spieler werden bei Tod mit einem Totem der Unsterblichkeit zu ihrem Home gespawnt.

### 6. Herzen gegen Astral Mana
- **Handel bei Kyuul**: Ab einer Herzanzahl von 3,5 Herzen kann Kyuul einen Zauberspruch zeigen, der einmalig 0,5 Herzen dauerhaft verliert. Dies wird bei einem Tod beibehalten.
- **Astral Mana Regeneration**: Nach 20x Herzverlust erhält man 20 Astral Mana Regeneration pro Sekunde, die es dem Spieler ermöglicht, ohne Elytra zu fliegen.

## Dimensionen

### Hub
![Hub](https://static.wikia.nocookie.net/minecraft_de_gamepedia/images/6/6a/Canvas_32-2_5.png/revision/latest?cb=20220830124207)
- **Beschreibung**: Der zentrale Punkt für die Erkundung der anderen Dimensionen. Hier gibt es am Anfang abgesehen von Luft und der hubbase nichts.

### Ozean
![Ozean](https://static.wikia.nocookie.net/minecraft_de_gamepedia/images/d/d7/Gem%C3%A4lde_Wasser.png/revision/latest?cb=20220830114934)
- **Beschreibung**: Eine Dimension, die nur aus Ozeanen besteht und keine Strukturen hat. Hier gibt es am Anfang abgesehen von Luft und der ozeanbase nichts.

### Hell
![Hell](https://static.wikia.nocookie.net/minecraft_de_gamepedia/images/b/b5/Gem%C3%A4lde_Feuer.png/revision/latest?cb=20220830114921)
- **Beschreibung**: Eine feurige Dimension mit gefährlichen Lava-Strömen und Hitze. Basiert auf dem Nether, jedoch fließt Lava nun wie Wasser, sodass unendliche Quellen erstellt werden können. Außerdem gibt es hier die Möglichkeit, Wasser zu platzieren und sich ins Bett zu legen, ohne eine Explosion zu verursachen. Die Struktur-Generierung ist deaktiviert, es gibt keinen Wirrwald und keinen Karmesinwald. Die Netherdecke ist 20 Blöcke dicker. Hier gibt es am Anfang abgesehen von geschmolzenem Gestein und anderen Höllensteinen und der hellbase nichts.

### Sky
![Sky](https://static.wikia.nocookie.net/minecraft_de_gamepedia/images/4/49/Gem%C3%A4lde_Luft.png/revision/latest?cb=20220830114941)
- **Beschreibung**: Eine Dimension über den Wolken, wo du die Freiheit des Himmels erleben kannst. Hier gibt es am Anfang abgesehen von Luft und der skybase nichts.

### Stone
![Stone](https://static.wikia.nocookie.net/minecraft_de_gamepedia/images/f/fb/Gem%C3%A4lde_Erde.png/revision/latest?cb=20220830114913)
- **Beschreibung**: Eine solide Dimension im wahrsten Sinne des Wortes mit einer rauen, steinigen Umgebung. Oben gibt es normales Gestein, unten ist Deep Dark. Hier gibt es auch keine Strukturen, keine Höhlen oder Klippen und keine Sculk-Features. Hier gibt es am Anfang abgesehen von Gestein und der stonebase nichts.

## Installation

1. **Herunterladen und Entpacken**: Lade das Datapack herunter und entpacke die Datei.
2. **Datapack einfügen**: Verschiebe den entpackten Ordner (`xois_cursed_worlds`) in den `datapacks`-Ordner deiner Minecraft-Welt.
3. **Welt laden**: Starte Minecraft und lade die Welt, in die du das Datapack eingefügt hast.
4. **Datapack aktivieren**: Das Datapack wird automatisch aktiviert, wenn du die Welt lädst. Initialisiere die Funktionen mit dem Befehl `/function xois_cursed_worlds:setup`.

## Nutzung

- **Berry of Life**: Konsumiere Beeren, um deine maximale Herzanzahl zu erhöhen und die Vorteile bei Wiederbelebung zu nutzen.
- **Razhy**: Überwache deinen Razhy-Wert und nutze ihn für spezielle Fähigkeiten.
- **Kyuul**: Nutze Kyuuls Handelsangebote und sei vorsichtig bei seinen Angriffen. Kyuul kann nur mit Befehlen getötet werden und fügt starken Schaden zu.
- **Astral Fähigkeiten**: Schalte automatische Totems frei und nutze Herzverlust für Astral Mana Regeneration.

## Kein Bug, ein Feature

- **Tag-Nacht-Rhythmus**: Der Tag-Nacht-Rhythmus ist beschädigt aufgrund zufälliger Anpassungen und wird dadurch gewollt unregelmäßig erscheinen.
- **Kyuuls Attacken**: Die Angriffe von Kyuul können schwierig sein und enden nur durch Tod.

## Bekannte Probleme

- **hmmm**: Werden wir sehen, was kommt.

## Zukünftige Updates

- **Gesperrte Welten**: Der echte Nether, eine normale Overworld und das End werden in zukünftigen Updates hinzugefügt.
- **Weitere Dimensionen**: Zusätzliche benutzerdefinierte Dimensionen könnten ergänzt werden.

## Kontakt

Bei Fragen oder Problemen kannst du uns über [Discord](https://discord.gg/BbcURrCb) erreichen.

Weitere Informationen findest du in der [CONTRIBUTING](https://github.com/McCursedWorld/McCursedWorld/blob/main/CONTRIBUTING.md). 