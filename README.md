# ZacharyKyberkey

**Benannte Post-Quantum-Schlüsselidentität für Nexus.**

CRYSTALS-Kyber (ML-KEM) · Hybrid-PQC · Key Generation · Encapsulation · Decapsulation · Sichere Schlüsselverwaltung

Teil von **Esslinger & Co.** / **Nexus** · Öffentliches Repository

---

## Zweck

`ZacharyKyberkey` ist die öffentliche, benannte Kyber-Schlüsselidentität innerhalb des Nexus-Stacks.
Sie dient als klare, versionierbare Identität für Post-Quantum-Schlüsselmaterial, Hybrid-KEM-Operationen und die Anbindung an Mesh, Agenten-Schwärme und sichere Systeme.

Verwandtes Kernprojekt: [`kyberkey`](https://github.com/digitaldesignerjazz/kyberkey)

## Status

- Repository: **public**
- Algorithmus: CRYSTALS-Kyber / ML-KEM (NIST PQC)
- Empfohlene Parameter: Kyber-768 (ML-KEM-768) für ausgewogenes Sicherheitsniveau
- Hybrid: Kombination mit klassischer Kryptographie (z. B. X25519) empfohlen, solange PQC-Implementierungen weiterhärten

## Geplante Inhalte

- Schlüsselgenerierung und -rotation
- Encapsulation / Decapsulation Interfaces
- Sichere Ablage- und Transportformate
- Anbindung an Nexus-Mesh und Agenten-Identitäten
- Dokumentation und Testvektoren

## Sicherheitshinweis

Dieses Repository verwaltet **keine Live-Geheimnisse** im Klartext.
Private Schlüssel, Seeds und Session-Material bleiben außerhalb von Git.
Nur öffentliche Schlüssel, Spezifikationen, Schnittstellen und nicht-geheime Artefakte gehören hierher.

## Lizenz

Siehe `LICENSE` (folgt der Linie der Nexus-PQC-Werkzeuge).

---

*Lumia / Nexus · Esslinger & Co.*
