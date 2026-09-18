# TV App Windows – Downloads

Öffentliche Windows-Installer und Update-Metadaten. Der App-Quellcode bleibt privat.

## Installation
Den Setup-x64.exe-Installer aus den Releases herunterladen und starten.
Windows 10/11 x64, Installation für den aktuellen Benutzer ohne Administratorrechte.
Bestehende IPTV-Profile und Einstellungen bleiben bei Updates erhalten.

Ab Version 0.9.2 prüft die App beim Start automatisch den Beta-Kanal.
Ältere Versionen müssen einmal manuell aktualisiert werden.

## Kanäle
- beta: Tester
- stable: reguläre Veröffentlichungen, sobald verfügbar

Die Kanaldateien sind Ed25519-signierte JSON-Umschläge; die enthaltenen Installer
werden zusätzlich mit SHA-256 geprüft. Releases enthalten Version und Änderungsnotizen.

Die mitgelieferten Player-Bibliotheken haben eigene Lizenzen. VLC-Lizenzhinweise
und der zugehörige VLC-Quelltext liegen im Installer im Ordner vlc/.
