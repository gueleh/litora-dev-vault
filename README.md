# Litora Development Vault

Test- und Entwicklungsinhalte für Litora, das KI-gestützte Autorentool.

## Zweck

- Testdaten für Unit- und Integrationstests
- Beispielstruktur für Funktionsvalidierung
- Referenz für korrekte Vault-Organisation

## Struktur

- Minimale Roman-Struktur mit 1 Kapitel und 2 Szenen
- Charaktere, Orte, Ereignisse und Objekte als Metadaten
- KI-Feedback-Beispiele

## Verwendung

1. Repository klonen
2. In Tests via Umgebungsvariable referenzieren:
   LITORA_TEST_VAULT_PATH=/pfad/zur/vault
3. Nicht direkt bearbeiten, wenn Tests laufen

## Hinweise

Diese Vault spiegelt den aktuellen Entwicklungsstand wider und wird erweitert,
wenn neue Funktionen implementiert werden.
