# VIM-Tutorial

Dieses Tutorial besteht aus folgenden Teilen:

- [VIM Anleitung](./VIM_Anleitung.md)<br />
Die eigentliche Anleitung zu VIM (bevorzugt NeoVIM)

- [VIM Konfiguration](./VIM_Konfiguration.md)<br />
Anleitung, Beispiele und fertige Konfigurationen zum VIM (bevorzugt NeoVIM)

- Ordner `Dateien`
Hier befinden sich die Beispiel-Textdokumente, zum üben der einzellnen Abschnitte der Anleitung.
Diese werden in den YouTube-Videos verwendet.

- YouTube-Kanal #TODO{Link einfügen}
Geht die komplette Anleitung durch und zeigt die dort enthaltenen Abschnitte in der praktischen Anwendung.

# Anleitung

Die Anleitung liegt als **.pdf**-Datei und im **Markdown**-Format vor.

Die **.md** Dateien sind direkt mit dem Programm **Obsidian** verwendbar.

[Obsidian](https://obsidian.md) ist ein sehr gutes Programm zum erstellen von Notizen. Es ist kostenlos, benötigt keinen Account oder Server. Es unterstützt Markdown und erlaubt auch die Verwendung grundlegender VIM Funktionalitäten.

Die Beispiel-Textdateien sollten jedoch immer mit VIM (vorzugsweise NeoVIM) bearbeitet werden, da andere Programme / Erweiterungen (z.B. Visual Studio Code, Visual Studio, Eclipse, Obsidian) nicht den kompletten Funktionsumfang von VIM nachbilden.

# VIM oder NeoVIM

Ich verwende NeoVIM, d.h. alle Beispiele, Plugins, Konfigurationen usw. sind direkt mit NeoVIM nutzbar. Bei VIM kann es zu Abweichungen kommen.

## Installation von NeoVIM

NeoVIM kann auf https://neovim.io heruntergeladen werden. Es gibt Versionen für Windows, macOS und Linux.

Zusätzlich kann NeoVIM mit Paketmanagern wie `brew` (Mac), `chocolatey` (Windows) und `apt` (Linux) installiert werden:

Auf den [Downloadseite](https://github.com/neovim/neovim/wiki/Installing-Neovim) von Neovim wird diese Installationsart ebenfalls beschrieben.

## Konfigurieren von NeoVIM

In der Datei [VIM Konfiguration](./VIM_Konfiguration.md) sind Beispiel-Konfiguration (Minimal und Nützlich) aufgeführt.

Die Konfigurationsdateien liegen an folgenden Pfaden:

**Windows**<br />
NeoVIM: ~\AppData\Local\nvim<br />
VIM: ~

**Linux**<br />
NeoVIM: ~/.config/nvim/<br />
VIM: ~

**Mac**<br />
NeoVIM: ~/.config/nvim/<br />
VIM: ~

Die Konfigurationsdateien heißen `init.vim` bei NeoVIM und `.vimrc` bei VIM. Daraus ergeben sich folgende kompletten Pfade:

~\AppData\Local\nvim\init.vim<br />
~/.config/nvim/init.vim

bzw. für VIM:<br />
~\.vimrc

# Aufbau der Anleitung und Ablauf der YouTube-Videos
Die Anleitung ist grob von einfach zu schwer aufgebaut. Da die Anleitung in den YouTube-Videos von Anfang bis Ende vorgeführt wird, sind die Videos ebenfalls von einfach zu schwer geordnet.

In der Anleitung stehen neben manchen Überschriften rote Zeitangaben mit Angabe des Teils. z.B. `3:17 Teil 3`<br />
Dies sind die Positionen im Video, bei denen der folgende Abschnitt (Überschrift) behandelt wird.

Diese Angaben sind nicht im Markdown-Format sondern im HTML Format angegeben und werden nicht von allen Markdown-Readern korrekt angezeigt! Sie ist ein Link der sowohl in z.B. Obsidian als auch im PDF funktioniert und direkt die Stelle im YouTube Video öffnet.

## Wie soll ich das Tutorial bzw. die Videos ansehen

Zum einen kann das komplette Material von Anfang bis Ende durchgegangen werden. Bei den Videos empfielt es sich ab und zu pause zu machen um die Übungen und Beispiele anhand der `Dateien` nachzumachen.

Zum anderen kann natürlich auch ein bestimmte Abschnitt angesehen werden. Wenn bei der täglichen Arbeit bestimmte VIM Funktionalitäten gebraucht werden oder diese gerade in Vergessenheit geraten sind.

## Tipps zur Anleitung

Am besten die `VIM_Anleitung.md` irgendwo hin kopieren und die Inhalte raus löschen, die problemlos beherscht werden (in Fleisch und Blut übergegangen).

Damit beinhaltet diese Version nur noch Inhalte, die noch gelernt werden müssen (und natürlich auch die Links/Zeitangaben zu den Videos).

Die original-Version verbleibt im geklonten Git-Repository inkl. aller anderen Dateien.

Mit `git restore .` können alle Dateien zurück gesetzt werden. Auch die Übungsdateien. Damit lassen sich die Übungen und Beispiele aus den Videos beliebig oft wiederholen.

Es ist auch immer Hilfreich eigene Dateien zu erstellen um bestimmte Probleme mittels VIM (ohne Maus, Cursortasten, ...) zu lösen. Um eigene Text-Dateien mehrmals nutzen zu können können diese mit

```
git add .
git commit -m "Beschreibungstext"
```

dem Git-Repository hinzugefügt und dann mit `git restore .` zurück gesetzt werden.

Ansonsten gilt: Learning by doing

# Weiterführende Informationen

Online und Interaktive Tutorials:

- https://www.openvim.com 
- https://www.vim-hero.com

oder einfach: `vimtutor` eingeben (Bestandteil der VIM Installation).

