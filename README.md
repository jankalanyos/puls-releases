# PULS – LJ Monitor · Update-Pakete

Öffentliche Ablage der ausgelieferten PULS-Update-Pakete.

**Hier liegt kein Quellcode.** Dieses Repository enthält ausschließlich die
fertigen Installationsdateien für Kunden.

## Apple (macOS)

Die aktuelle DMG steht unter [Releases](../../releases/latest):

- `PULS-Setup-<Version>-arm64.dmg`
- Apple Silicon (arm64), mindestens macOS 11.0
- SHA-256 steht in den Versionshinweisen und in der Datei `release-mac-<Version>.json`

Die DMG ist ad-hoc signiert und nicht notarisiert. Beim ersten Start daher
Rechtsklick auf **PULS.app → Öffnen → Öffnen** wählen. Alternativ:

```bash
xattr -dr com.apple.quarantine /Applications/PULS.app
```

## Windows

Windows-Updates werden als `.puls`-Paket über die PULS-Sammelstelle verteilt
und erscheinen nicht in diesem Repository.

## Lizenz

PULS ist proprietäre Software. Installation und Nutzung nur mit gültiger
Lizenz; alle Rechte bei Janos Kalanyos. Siehe `LICENSE.txt` in der App.
