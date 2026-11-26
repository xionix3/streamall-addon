# Streamall Portale

[Streamall-App herunterladen](https://github.com/xionix3/streamall#downloads) · [Aktueller Portal-Release](https://github.com/xionix3/streamall-addon/releases/latest)

## Installation

| Plattform | Vorgehen |
| --- | --- |
| Android, Android TV, Windows und Linux | Streamall öffnen und **Portale → Portalpaket installieren** wählen, sobald diese Funktion in deiner App-Version verfügbar ist. Releases mit einer `streamall-portals.zip` erlauben auch den manuellen Import in der App. |
| Enigma2 (SF8008) | [Add-on-IPK herunterladen](https://github.com/xionix3/streamall-addon/releases/latest), auf den Receiver nach `/tmp/` kopieren, installieren und Enigma2 neu starten. |

```sh
opkg install /tmp/enigma2-plugin-extensions-streamall-addon_*_sf8008.ipk
```

Das Portalpaket ist optional und hat einen eigenen Update-Kanal. Streamall prüft installierte Portalpakete beim Start auf Updates. Enigma2 bietet dazu die Installation der neuen IPK an. Ein GitHub-Token auf dem Gerät ist dafür nicht erforderlich.

[Alle Portal-Versionen und Prüfsummen](https://github.com/xionix3/streamall-addon/releases)

Hier liegen die Beschreibung und die fertigen Pakete. Quellcode und Build-Workflows liegen intern.
