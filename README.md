# Streamall Portale

[Streamall-App herunterladen](https://github.com/xionix3/streamall#downloads) · [Aktueller Portal-Release](https://github.com/xionix3/streamall-addon/releases/latest)

## Installation

| Plattform | Vorgehen |
| --- | --- |
| Android, Android TV, Windows und Linux | In Streamall oben beim **S → Portale verwalten → Portalpaket installieren** wählen. In Streamall 3.4.32 findest du den Punkt im Menü **Portale**. Alternativ die [Portal-ZIP](https://github.com/xionix3/streamall-addon/releases/latest/download/streamall-portals.zip) in der App importieren. |
| Enigma2 (SF8008) | [Add-on-IPK 1.0.10 herunterladen](https://github.com/xionix3/streamall-addon/releases/download/v1.0.10/enigma2-plugin-extensions-streamall-addon_1.0.10_sf8008.ipk), auf den Receiver nach `/tmp/` kopieren, installieren und Enigma2 neu starten. |

```sh
opkg install /tmp/enigma2-plugin-extensions-streamall-addon_*_sf8008.ipk
```

Das Portalpaket ist optional und hat einen eigenen Update-Kanal. Streamall prüft installierte Portalpakete beim Start auf Updates. Enigma2 bietet dazu die Installation der neuen IPK an. Ein GitHub-Token auf dem Gerät ist dafür nicht erforderlich.

[Alle Portal-Versionen und Prüfsummen](https://github.com/xionix3/streamall-addon/releases)

Hier liegen die Beschreibung und die fertigen Pakete. Quellcode und Build-Workflows liegen intern.
