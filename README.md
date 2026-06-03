# 🎬🎵 Video als Instrument – TouchDesigner Workshop

> *Wie kann ein Video zum Instrument werden?*

In diesem Workshop entwickeln Teilnehmende audiovisuelle Systeme mit [TouchDesigner](https://derivative.ca/release/202531760/73310), in denen Bewegungen in Videos Sound auslösen. Der Fokus liegt auf der Erstellung eigener Videos, die Sound in Echtzeit triggern und steuern.

---

## Voraussetzungen

Um die Projektdateien öffnen und nutzen zu können, wird folgende Software benötigt:

### 1. TouchDesigner (Build 2025.31760)

→ [Download & Release Notes](https://derivative.ca/release/202531760/73310)

### 2. VST3-Instrument

Ein VST3-Instrument wird benötigt, um Sound über TouchDesigner zu erzeugen. Empfehlungen:

| Plugin | Beschreibung | Download |
|---|---|---|
| **Spitfire LABS** | Verschiedene Instrumente (kostenlos) | [Installationsanleitung](https://support.spitfireaudio.com/en/articles/12034689-how-to-install-labs) |
| **Vital** | Synthesizer (kostenlos) | [vital.audio](https://account.vital.audio/) |
| **Emergence v0.3** | Granularsynthese (kostenlos) | [danielgergely.net](https://danielgergely.net/emergence#emergence-v0.3) |

### 3. VST-Effekt *(optional)*

| Plugin | Beschreibung | Download |
|---|---|---|
| **Valhalla Supermassive** | Reverb / Delay (kostenlos) | [valhalladsp.com](https://valhalladsp.com/demos-downloads/) |

---

## Konzept

Bewegungen in einem Video werden analysiert und in Echtzeit in Klangereignisse übersetzt. TouchDesigner fungiert dabei als Schaltzentrale zwischen Bild und Ton:

- Bewegungsdaten aus dem Video werden als Steuersignale genutzt
- Diese Signale triggern und modulieren VST-Instrumente
- Eigene Videos können direkt in das System eingespeist werden

---

## Lizenz

Dieses Projekt ist für Workshop-Zwecke erstellt. Verwendete Drittanbieter-Plugins unterliegen ihren jeweiligen Lizenzbedingungen.
