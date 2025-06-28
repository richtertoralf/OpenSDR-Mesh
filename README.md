# OpenSDR-Mesh: Offenes SDR-Mesh-Netz für IP-Kommunikation in Krisengebieten

## 🌍 Projektidee
OpenSDR-Mesh ist ein Open-Source-Projekt, das ein skalierbares Mesh-Netzwerk auf Software Defined Radio (SDR) Basis entwickelt, um IP-Dienste wie Internet, Sprache und Video in Regionen ohne oder mit zerstörter Infrastruktur bereitzustellen.

## 🚨 Hintergrund
In Krisen- und Katastrophengebieten fehlen oft verlässliche Kommunikationsmöglichkeiten. Konventionelle Systeme (z. B. Satellit oder Mobilfunk) sind teuer, schwer zugänglich oder lokal nicht einsetzbar. Ein flexibles, offenes und unabhängiges Kommunikationsnetz kann in solchen Situationen entscheidend sein, um humanitäre Hilfe effizient zu koordinieren und Menschenleben zu retten.

## 🎯 Ziele
- Entwicklung eines selbstheilenden, SDR-basierten Mesh-Netzwerks für IP-Verkehr.
- Bereitstellung von standardisierten IP-Schnittstellen (Ethernet/WLAN) für Endgeräte, sodass Nutzer keine Spezialsoftware benötigen.
- Nutzung offener Frequenzbereiche außerhalb kommerzieller Bänder zur Reduktion von Interferenzen.
- Offenheit: Alle Soft- und Hardwarekomponenten sollen auf Open-Source-Software und offener Hardware basieren.

## 💡 Konzept
- **Mesh-Knoten:** Jeder Node besteht aus einem SDR-Transceiver und einem kleinen Embedded-System oder Computer.
- **Mesh-Protokoll:** Protokolle wie B.A.T.M.A.N. Advanced oder OLSR ermöglichen ein sich selbst organisierendes Netz.
- **Frequenzhopping & adaptive Modulation:** Robustheit gegen Störungen und dynamische Anpassung an Umgebungsbedingungen.
- **IP-Tunnel:** Übertragung von SRT-, RIST-Streams oder anderen IP-Diensten mit starker FEC und optionaler Ende-zu-Ende-Verschlüsselung (z. B. WireGuard).

## 🌐 Einsatzszenarien
- Notfallkommunikation nach Naturkatastrophen.
- Koordination humanitärer Einsätze in Gebieten ohne Netzabdeckung.
- Bereitstellung von Internetzugang in temporären Camps oder abgelegenen Regionen.

## 📈 Skalierbarkeit
- Startfähig ab 4 Nodes.
- Ausbau auf 20–25 Nodes für größere Einsatzgebiete.

## 🔓 Offenheit & Nachhaltigkeit
- Entwicklung und Dokumentation aller Komponenten unter offenen Lizenzen.
- Fokus auf Open-Source-Software (z. B. GNU Radio) und Hardware mit offenen Spezifikationen oder Community-Support.
- Förderung lokaler Anpassung und Wartung durch Vermeidung proprietärer Abhängigkeiten.

## ✅ Nächste Schritte
- Aufbau eines Konsortiums aus interessierten Organisationen und Experten.
- Entwicklung eines Prototyps mit mind. 4 Mesh-Knoten.
- Feldtests in realen Einsatzszenarien mit humanitären Partnern.
- Veröffentlichung von Software, Hardware-Designs und Dokumentationen in diesem Repository.

## 📬 Kontakt
Wir freuen uns über Mitstreiter:innen, Organisationen, Techniker:innen oder Interessierte, die sich beteiligen möchten. Bitte kontaktiert uns via Issues oder Pull Requests.

---
