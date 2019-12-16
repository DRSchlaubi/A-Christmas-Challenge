## Die OOP-Weihnachts-Challenge

Sie kriegen nicht genug vom Programmieren? In den Weihnachtsferien ist Ihnen langweilig? Dann nehmen Sie doch an der **OOP-Weihachts-Challenge** teil und entwerfen Sie Ihr ganz persönliches Weihnachtsspiel!

## Die Aufgabe

Programmieren Sie ein [*Jump and Run*-Spiel](https://en.wikipedia.org/wiki/Platform_game) auf der Basis der *GraphicsApp*-Umgebung. Sie können alle inhaltlichen Aspekte frei gestalten, im Spiel muss aber eine grundlegende Weihnachtsthematik erkennbar sein.

## Teilnahme

Laden Sie das [Starterpaket](https://github.com/OOP-Regensburg/A-Christmas-Challenge-Starter/archive/starter.zip) herunter und beginnen Sie mit der Arbeit. Entwickeln Sie ein *Jump and Run*-Spiel und schicken Sie Ihre fertige Lösung als ZIP-Datei bis zum 5. Januar 2020 an **alexander.bazo@ur.de**.


### Neue Funktionen in der GraphicsApp

Im Starterpaket zur *Challenge* wird eine neue Version der GraphicsApp verwendet, in der Sie diese zusätzlichen Funktionen verwenden können:

#### Audio

Mithilfe der Klasse `AudioClip` können Sie [`WAV`-Dateien](https://en.wikipedia.org/wiki/WAV) wiedergeben. Bestehende Audiodateien können Sie z.B. mit dem kostenlosen Werkzeuge [Audacity](https://www.audacityteam.org/) in das `WAV`-Format konvertieren.


``` java
Audio Clip backgroundMusic = new AudioClip("sound.wav");
backgroundMusic.loop();
```

#### Label

Die `Label`-Klasse verfügt jetzt über neue Methoden zum Ändern der Schriftart und -Größe. Die verwendete Schriftart muss auf dem jeweiligen Rechner installiert sein - verwenden Sie am besten Standardschriften.

``` java
Label label = new Label(0, 0, "Hello World");
label.setFont("Monospaced");
label.setFontSize(24);
label.setColor(Colors.WHITE);
```

## Bewertung und Gewinne

Das OOP-Team spielt und bewertet alle Einreichungen. Die drei besten Einreichungen werden im Kurs vorgestellt und werden als Dankeschön mit kleinen Preisen ausgezeichnet. Mitmachen lohnt sich. Wenn Sie wollen, machen wir Ihr Spiel auch für die übrigen KursteilnehmerInnen zugänglich.
