# Streamall Add-on

Öffentliches Binary-Repository für das optionale Streamall-Erweiterungspaket.
Der Quellcode wird getrennt in einem privaten Repository verwaltet.

## Installation

1. Aktuelle IPK unter [Releases](https://github.com/xionix3/streamall-addon/releases/latest) herunterladen.
2. Auf den Receiver nach `/tmp/` kopieren.
3. Über SSH installieren:

```sh
opkg install /tmp/enigma2-plugin-extensions-streamall-addon_*_sf8008.ipk
```

Danach Enigma2 einmal neu starten. Das Add-on prüft bei späteren Enigma2-Starts
selbständig den öffentlichen Releasekanal und bietet neue Versionen zur Installation an.
Ein GitHub-Token ist auf dem Receiver nicht erforderlich.

Das Add-on setzt Streamall 3.4.0 oder neuer voraus und verändert keine Dateien
der Streamall-Oberfläche.
