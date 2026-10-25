# StockManager – Pakete

Hier liegen die fertigen Android-Pakete von **StockManager**, einer privaten App zur
Haushaltsverwaltung. Dieses Repository enthält **keinen Quellcode** – nur das, was
installiert wird.

Die App ist für einen Haushalt gedacht und steht nicht im Play Store. Sie prüft selbst,
ob hier eine neuere Fassung liegt, und bietet sie zum Installieren an.

## Installieren

Unter [Releases](../../releases) das `.apk` der neuesten Fassung herunterladen und
öffnen. Android fragt dabei einmal nach der Erlaubnis, Apps aus unbekannter Quelle zu
installieren.

Ab dann meldet sich die App selbst, wenn es etwas Neues gibt.

## Warum ein eigenes Repository

Der Quellcode bleibt privat, die Pakete müssen öffentlich erreichbar sein: Ein privates
Release liefert GitHub nur gegen ein Zugangstoken, und ein Token in einer App, die auf
fremden Telefonen liegt, ist keines mehr.
