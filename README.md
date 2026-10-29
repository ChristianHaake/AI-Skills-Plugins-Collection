# AI-Skills-Plugins-Collection

![Lizenz](https://img.shields.io/badge/Lizenz-CC%20BY--SA%204.0-blue) ![Kuratiert](https://img.shields.io/badge/kuratiert-ja-brightgreen)

Kuratierte Liste von KI-Skills, Plugins und MCP-Servern. Enthält auch Kandidaten, die noch nicht im Einsatz sind. Lesbar für Menschen und KI-Agenten.

Eintragsformat: `- [Name](Primärquelle) – Kurzbeschreibung.` Ein Eintrag steht in genau einer Kategorie. Regeln: [docs/automatisierung-und-regelwerk.md](docs/automatisierung-und-regelwerk.md).

Kategorien: Skills, Plugins, MCP-Server, Tools & Frameworks, Schule.

## Skills

Agent-Skills (SKILL.md-Pakete) für Claude und andere Agenten.

- [caveman](https://github.com/juliusbrussee/caveman) – Skill und Proxy für Coding-Agents, der den Token-Verbrauch senkt: knappe Antworten, Kompression großer Eingaben (Logs, JSON, CSV) vor dem Modell; Claude Code, Gemini CLI u.a.
- [humanizer](https://github.com/blader/humanizer) – Skill (`/humanizer`), der Merkmale KI-generierter Texte anhand von 26 Mustern entfernt (Entwurf, Kritik, Endfassung); Claude Code, Codex, Claude.ai.
- [marketingskills](https://github.com/coreyhaines31/marketingskills) – 52 Marketing-Skills (CRO, Copywriting, SEO, Analytics, Growth) nach Agent-Skills-Spezifikation.
- [mattpocock/skills](https://github.com/mattpocock/skills) – Skill-Sammlung für Entwicklung (tdd, diagnosing-bugs, to-spec, code-review) und Produktivität (grill-me, handoff).
- [diagram-design](https://github.com/cathrynlavery/diagram-design) – Skill, der Diagramme als einzelne HTML-Datei mit Inline-SVG im Markenstil erzeugt; 45 Diagrammtypen, Import von draw.io, Mermaid und Excalidraw, Export als SVG oder PNG.
- [impeccable](https://github.com/pbakaus/impeccable) – Design-Skill (`/impeccable`, 24 Befehle) zum Prüfen und Polieren von Frontend-Design, mit 62 deterministischen Regeln gegen typische KI-Designfehler; auch als CLI und Browser-Extension.
- [academic-research-skills](https://github.com/Imbad0202/academic-research-skills) – Claude-Code-Skills für den akademischen Workflow: Deep Research (13 Agenten), Paper-Schreiben (12), simuliertes Peer-Review (7) und eine 10-stufige Pipeline.
- [karpathy-skills](https://github.com/forrestchang/andrej-karpathy-skills) – CLAUDE.md, Skill und Plugin mit vier Prinzipien gegen typische LLM-Codingfehler (vor dem Coden klären, einfach halten, gezielte Änderungen, überprüfbare Ziele); auch als Cursor-Regel.
- [ui-ux-pro-max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) – Skill mit Design-Wissensbasis für UI/UX (79 Stile, 192 Farbpaletten, 74 Schriftpaarungen, 119 UX-Richtlinien, 22 Stacks); erzeugt per Suchskript (BM25) ein Design-System; für viele Agenten.

## Plugins

Plugin-Bündel aus Skills, Befehlen, Hooks und Connectoren.

- [obra/superpowers](https://github.com/obra/superpowers) – Skills-Framework und Methodik für Software-Entwicklung mit Agenten (Brainstorming, Plan, TDD, Subagenten, Code-Review); Claude Code, Codex, Cursor, Gemini CLI u.a.
- [anthropics/financial-services](https://github.com/anthropics/financial-services) – Referenz-Agenten, Skills, Slash-Commands (`/dcf`, `/lbo`, `/comps`) und 12 MCP-Connectoren für Investmentbanking, Equity Research, Private Equity und Wealth Management; Cowork- und Claude-Code-Plugins.

## MCP-Server

MCP-Server, die Dienste und Daten an KI-Agenten anbinden.

_Leer._

## Tools & Frameworks

Eigenständige Frameworks und CLIs für KI-Agenten, die weder Skill noch Plugin noch MCP-Server sind.

- [TradingAgents](https://github.com/TauricResearch/TradingAgents) – Python-Framework (LangGraph), in dem mehrere LLM-Agenten eine Handelsfirma simulieren (Analysten, Bull/Bear-Debatte, Trader, Risikomanagement); nur zu Forschungszwecken.
- [agent-reach](https://github.com/Panniantong/agent-reach) – Python-CLI mit Skill, die Agenten Lese- und Suchzugriff auf Plattformen gibt (YouTube, GitHub, Bilibili, Reddit u.a.); nur lesend.
- [hyperframes](https://github.com/heygen-com/hyperframes) – HeyGen-Framework (TypeScript), das HTML/CSS-Kompositionen deterministisch zu MP4 rendert; mit CLI und Agent-Skills, benötigt Node.js 22+ und FFmpeg.
- [CLI-Anything](https://github.com/HKUDS/CLI-Anything) – generiert per 7-Phasen-Pipeline Python-CLIs (Click, JSON-Ausgabe) für bestehende Software, damit Agenten sie bedienen; mit Community-Registry CLI-Hub.
- [Paper2Agent](https://github.com/jmiao24/Paper2Agent) – CLI-Pipeline (Python 3.10+, Claude Code, fastmcp), die aus dem Repository eines Forschungspapers dessen Tutorials ausführt, daraus Tools extrahiert und als MCP-Server verpackt.

## Schule

Skills, Plattformen, Tools und OER für den schulischen Einsatz. Auswahlkriterien: Datenschutz, lokale Verarbeitung, freie Lizenzen.

Claude-Skills (.zip, für Claude Code):

- [Learning Artifacts Builder (lab-o5)](https://3ducation.org/skills/lab-o5.zip) – erzeugt interaktive Lernumgebungen; auf Opus 5 optimiert.
- [Learning Artifacts Builder (lab-f5)](https://3ducation.org/skills/lab-f5.zip) – wie lab-o5, auf Fable 5 optimiert.
- [AIS.chat Builder](https://3ducation.org/skills/aischat-builder.zip) – erzeugt kopierfertige AIS.chat-Konfigurationen (Lernszenarien, Dialogpartner, Assistenten).
- [Lernplakat-Reflexion auswerten](https://3ducation.org/skills/lernplakat-reflexion-auswerten.zip) – wertet ausgefüllte Reflexionsbögen zum Lernplakat aus; lokale Verarbeitung, personenbezogene Daten beachten.
- [Präsentation-Reflexion auswerten](https://3ducation.org/skills/praesentation-reflexion-auswerten.zip) – wertet Reflexionsbögen zu PowerPoint-Präsentationen aus.

Plattformen und Apps:

- [AIS.chat](https://app.ais-chat.schule) – Schulplattform für KI-Lernszenarien, Dialogpartner und Assistenten; DSGVO-konform, deutsche Server, proprietär.
- [Unterrichtsplanung-App](https://github.com/dk-3du/unterrichtsplanung) – native macOS-App (SwiftUI, macOS 26+) für Unterrichtsplanung und Materialkuration; lokal, AES-256-verschlüsselt, Web-Leseansicht für iPad.
- [Erwartungshorizont-Studio](https://github.com/simonhartmannedu/Erwartungshorizont-Studio) – local-first Web-App für Erwartungshorizonte, Notenschlüssel und Klausurkorrektur; Export DOCX, ODS, PDF.
- [LernWerkstatt](https://github.com/maltedreyer-5/lernwerkstatt) – selbst gehostete Web-App (Python, Gradio, Docker), die per Sprachmodell eigenständige interaktive HTML-Lerneinheiten mit Diagrammen, Formeln, Simulatoren und Selbsttests erzeugt; beliebiger OpenAI-kompatibler Endpoint, Fachinhalte werden nicht geprüft.
- [Prompt-Bibliothek des Deutschen Schulportals](https://campus.deutsches-schulportal.de/promptbibliothek) – 22 Prompts für Schulentwicklung in vier Phasen; Registrierung für Volltexte nötig.

Browser-Tools (lokal, ohne Account):

- [Pinnwand zur Projektplanung](https://3ducation.org/allgemein/pinnwand.html) – Pinnwand mit Export zur KI-Weiterarbeit.
- [QR-Code-Generator](https://3ducation.org/allgemein/qrcodegenerator.html) – QR-Codes ohne Tracking, offline nutzbar.
- [Scratch SB3 Merger](https://3ducation.org/dw/scratch-sb3-merger.html) – verschmilzt zwei .sb3-Dateien.
- [KomPo7-Beobachtungstool](https://lbs-50.de/kompo7/) – Beobachtungsdokumentation Berufsorientierung Klasse 7.

OER (3ducation.org):

- [3ducation.org](https://3ducation.org) – Einstiegspunkt: Lernumgebungen, Skills, Feedback- und Reflexionsbögen.
- [Feedbackbogen Erarbeitungsphase Lernplakat](https://3ducation.org/biologie/feedback_erarbeitung_lernplakat.html) – Feedbackbogen, themenübertragbar.
- [Reflexionsbogen Erarbeitungsphase Lernplakat](https://3ducation.org/biologie/reflexion_erarbeitung_lernplakat.html) – angeleitete Reflexion.
- [Feedbackbogen Präsentation](https://3ducation.org/informatik/feedback_erarbeitung_ppp.html) – Feedback zu Inhalt und Gestaltung, fachübergreifend.
- [Reflexionsumgebung Klasse 5](https://3ducation.org/klassenleitung/reflexion_5-1.html) – Halbjahresreflexion als Gesprächsbasis.
- [Zwischen den Räumen](https://3ducation.org/dw/zwischen_den_raeumen/zwischen_den_raeumen.html) – interaktive Podcastserie, 8 Episoden, KI und Medientheorie.
- [Lernfelder Digitale Welt](https://3ducation.org/dw/inhaltsuebersicht.html) – Lernfelder 1 bis 4 (Hessen), interaktiv im Browser.

## Verwandte Sammlungen

- [Tool-Collection_MacOS](https://github.com/ChristianHaake/Tool-Collection_MacOS) – Tools für macOS
- [Tool-Collection_Linux](https://github.com/ChristianHaake/Tool-Collection_Linux) – Tools für Linux

## Mitmachen

Vorschläge als [Issue](https://github.com/ChristianHaake/AI-Skills-Plugins-Collection/issues/new) mit Name, Link, Kategorie und einem Satz Beschreibung.

## Kontakt

Christian Haake · [haak3.de](https://haak3.de) · [GitHub](https://github.com/ChristianHaake)

## Lizenz

CC BY-SA 4.0, siehe [LICENSE](LICENSE).
