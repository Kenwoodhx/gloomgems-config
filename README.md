# Gloomgems – Versionsprüfung

Die App liest beim Start `version.json`. Ist die installierte Version älter als `minimum` der Plattform,
sperrt sie das Spiel und führt in den Store.

Auf iOS sperrt die App zusätzlich von selbst, sobald im App Store eine neuere Version steht.
Für Android ist diese Datei der einzige Hebel: nach dem Veröffentlichen einer neuen Version im Play Store
`android.minimum` auf die neue Versionsnummer setzen.

Nur erhöhen, wenn die neue Version im Store bereits für alle sichtbar ist.
