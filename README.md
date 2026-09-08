# MultiControl

Steuer- und Auslesesoftware für CertoClav-MultiControl-Autoklaven.

## Download

Die aktuelle Fassung liegt unter **[Releases](../../releases/latest)** — die Datei
`MultiControlSetup-<Version>.exe` herunterladen und ausführen. Die Installation braucht
Administratorrechte, weil die Software unter „Programme" landet.

## Updates

Eine bereits installierte MultiControl-Fassung aktualisiert sich selbst:
**Einstellungen → Updates → „Nach Updates suchen"**. Einstellungen, Log-Verzeichnis und
Premium-Freischaltungen bleiben dabei erhalten.

## Hinweis zur Windows-Warnung

Die Installationsdatei ist derzeit nicht mit einem Codesignatur-Zertifikat versehen. Windows
zeigt bei der Rückfrage nach Administratorrechten deshalb „Herausgeber: Unbekannt". Die
Prüfsumme jeder veröffentlichten Fassung ist in
[`update.json`](update.json) hinterlegt; die Software vergleicht sie vor der Installation
selbst.

## Was hier liegt — und was nicht

Dieses Repository enthält ausschließlich die fertigen Installationspakete und die Datei
`update.json`, über die die Software eine neuere Fassung findet. **Quellcode liegt hier
nicht.**

---

CertoClav Sterilizer GmbH · Peintnerstrasse 10, 4060 Leonding, Österreich ·
[support@certoclav.com](mailto:support@certoclav.com) · [www.certoclav.com](https://www.certoclav.com)
