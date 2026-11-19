# 13. Warum habe ich Wartezeiten in meinem Routenplan?

Der Optimierungsalgorithmus kann aus folgenden Gründen Wartezeiten einführen:

1. Der Zusteller erreicht den Kundenstandort **vor den Öffnungszeiten**.
2. Der Zusteller erreicht das Depot **bevor es in Betrieb genommen wird**.

Kunden- und Depotöffnungszeiten sind strikte Einschränkungen mit hoher Priorität, daher muss der Algorithmus sie respektieren.

**Tipp:** Um unnötige Wartezeiten zu reduzieren, verwenden Sie das **Automatische Startzeit** Constraint. Diese Funktion passt die Abfahrtszeit an, sodass der Zusteller später startet und zum richtigen Zeitpunkt beim Kunden oder Depot eintrifft, wodurch Leerlaufzeiten an unbekannten Orten minimiert werden.
