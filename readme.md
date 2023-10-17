# VIM-Tutorial

Dieses Tutorial besteht aus folgenden Teilen:

- [VIM Anleitung.md](VIM Anleitung.md)
Die eigentliche Anleitung zu VIM (bevorzugt ==NeoVIM==)

- [[VIM Konfiguration.md]]
Anleitung, Beispiele und fertige Konfigurationen zum VIM (bevorzugt ==NeoVIM==)

- Ordner `Dateien`
Hier befinden sich die Beispiel-Textdokumente, zum üben der einzellnen Abschnitte der Anleitung.
Diese werden in den YouTube-Videos verwendet.

- YouTube-Kanal #TODO{Link einfügen}
Geht die komplette Anleitung durch und zeigt die dort enthaltenen Abschnitte in der praktischen Anwendung.

# Anleitung

Die Anleitung liegt als ==.pdf== Datei und im ==Markdown==-Format vor.

Die ==.md== Dateien sind direkt mit dem Programm ==Obsidian== verwendbar.

[Obsidian](https://obsidian.md) ist ein sehr gutes Programm zum erstellen von Notizen. Es ist kostenlos, benötigt keinen Account oder Server. Es unterstützt Markdown und erlaubt auch die Verwendung grundlegender VIM Funktionalitäten.

Die Beispiel-Textdateien sollten jedoch immer mit VIM (vorzugsweise NeoVIM) bearbeitet werden, da andere Programme / Erweiterungen (z.B. Visual Studio Code, Visual Studio, Eclipse, Obsidian) nicht den kompletten Funktionsumfang von VIM nachbilden.

# VIM oder NeoVIM

Ich verwende NeoVIM, d.h. alle Beispiele, Plugins, Konfigurationen usw. sind direkt mit NeoVIM nutzbar. Bei VIM kann es zu Abweichungen kommen.

## Installation von NeoVIM

NeoVIM kann auf https://neovim.io heruntergeladen werden. Es gibt Versionen für Windows, macOS und Linux.

Zusätzlich kann NeoVIM mit Paketmanagern wie `brew` (Mac), `chocolatey` (Windows) und `apt` (Linux) installiert werden:

Auf den [Downloadseite](https://github.com/neovim/neovim/wiki/Installing-Neovim) von Neovim wird diese Installationsart ebenfalls beschrieben.

## Konfigurieren von NeoVIM

In der Datei [[VIM Konfiguration.md]] sind Beispiel-Konfiguration (Minimal und Nützlich) aufgeführt.

Die Konfigurationsdateien liegen an folgenden Pfaden:

**Windows**
NeoVIM: ~\AppData\Local\nvim
VIM: ~

**Linux**
NeoVIM: ~/.config/nvim/
VIM: ~

**Mac**
NeoVIM: ~/.config/nvim/
VIM: ~

Die Konfigurationsdateien heißen `init.vim` bei NeoVIM und `.vimrc` bei VIM. Daraus ergeben sich folgende kompletten Pfade:

~\AppData\Local\nvim\init.vim
~/.config/nvim/init.vim

bzw. für VIM:
~\.vimrc


