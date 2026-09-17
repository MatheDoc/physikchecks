# Physikchecks

Dieses Repository enthält gegliedert nach Lernbereichen Kompetenzlisten und passende Tests in Form von Moodle XML-Dateien.

## Referenz-Inhalte

- Allgemein unter https://www.leifiphysik.de
- genaueres in den README-Dateien der Lernbereiche
- Die hinterlegten Websites dienen als Orientierung, nicht alles muss genau so vorkommen und auch die Reihenfolge kann ggf. angepasst werden.

## Zielformat für Moodle XML-Dateien
- siehe `bsp.xml`, Dateiname: `moodle.xml`, 

## Didaktische Regeln für Test

- Single-Choice, genau 4 Optionen, genau 1 richtig.
- Keine Hilfsmittel (kein Taschenrechner, keine Formelsammlung); ca. 10–20 Sekunden pro Frage.
- **Atomarität:** Jede Frage prüft möglichst eine kleine Teilkompetenz, kein mehrschrittiges Verfahren.
  - Zu groß: „Aus zwei Punkten die Funktionsgleichung bestimmen."
  - Geeignet: „Welche Formel brauchst du zuerst, um m zu berechnen?" – oder bei bewusst trivialen Zahlen nur die Berechnung von m.
- Keine künstliche Komplexität: keine unnötigen Informationen, komplizierten Zahlen oder Zusatzschritte. Im Mittelpunkt steht der schnelle Abruf, nicht die Rechenlast.
- **Distraktoren:** möglichst konkrete, plausible typische Fehler oder Fehlvorstellungen, idealerweise aus der korrekten Lösung durch genau diesen Fehler entstehend. Allgemeine Fehlerantworten sind zulässig.
- Umfang: 10 verschiedene atomare Fragen pro Check; punktuell mehrere Varianten einer Frage, wo Auswendiglernen der Antwort droht.
- **Keine Grafiken:** Test-Fragen kommen ohne Abbildungen aus. Didaktisch oft wünschenswert, aber im Moodle-XML-Export nur mit Workarounds (Base64/Dateianhänge) machbar und im 10–20-s-Format kaum sinnvoll erfassbar.

## Fragenarten

- **Wert bestimmen:** Mini-Rechnung mit bewusst einfachen Zahlen, z. B. „Ein Körper legt in 2 s gleichförmig 6 m zurück. Wie groß ist seine Geschwindigkeit?"
- **Größen und Notation deuten:** Formelzeichen, Vorzeichen oder Vektorrichtung verstehen, z. B. „Was bedeutet eine negative Geschwindigkeit bezüglich der gewählten positiven Richtung?"
- **Einheiten zuordnen oder umrechnen:** z. B. „Welche Einheit hat die elektrische Feldstärke?" oder „Wie viele Meter sind 200 cm?" – jeweils nur eine Zuordnung oder Umrechnung.
- **Formel-/Ansatzwahl:** Aus gegebenen und gesuchten Größen die passende Beziehung wählen, z. B. „Welche Formel liefert die elektrische Feldstärke aus Kraft und positiver Probeladung?"
- **Qualitativen Zusammenhang erkennen:** Änderungen ohne vollständige Rechnung vorhersagen, z. B. „Der Abstand zweier Punktladungen wird verdoppelt. Wie verändert sich bei unveränderten Ladungen der Betrag der elektrischen Kraft?"
- **Satzvervollständigung:** Ein physikalisches Gesetz oder einen Zusammenhang ergänzen, z. B. „Bei gleichförmiger geradliniger Bewegung ist die Beschleunigung …"
- **Aussage beurteilen:** Vier kurze Aussagen zu einem klar beschriebenen Sachverhalt; genau eine ist richtig. Typische Fehlvorstellungen aufgreifen, z. B. „Ein Körper bewegt sich geradlinig mit konstanter Geschwindigkeit. Was gilt für die resultierende Kraft?"
- **Richtung bestimmen:** Bewegungs-, Kraft- oder Feldrichtung in einer sprachlich eindeutigen Situation zuordnen, z. B. „Ein Elektron befindet sich in einem nach rechts gerichteten elektrischen Feld. In welche Richtung wirkt die elektrische Kraft?"
- **Voraussetzung oder Modellgrenze erkennen:** z. B. „Unter welcher Bedingung darf das Feld zwischen zwei großen, parallelen Kondensatorplatten näherungsweise als homogen gelten?"
- **Experiment oder Messung deuten:** Eine Beobachtung vorhersagen, eine Messgröße identifizieren oder eine Kontrollbedingung erkennen, z. B. „Du untersuchst den Einfluss des Abstands auf die Kraft zwischen zwei Punktladungen. Welche Größen müssen dabei konstant bleiben?"
- **Plausibilität/Schätzen ohne Rechnung:** Größenordnungen oder physikalisch mögliche Ergebnisse erkennen, z. B. „Welche Geschwindigkeit passt am ehesten zu einem gehenden Menschen?" – Antwortoptionen mit deutlich verschiedenen Größenordnungen.
- **Begriff ↔ Definition zuordnen:** z. B. „Welche Größe beschreibt die Änderung der Geschwindigkeit pro Zeit?"; auch umgekehrt nach der Bedeutung eines Begriffs fragen.

Die Liste ist offen – zulässig ist jede Frageart, die die Regeln oben erfüllt (atomar, ohne Hilfsmittel, ohne Grafik, in 10–20 s beantwortbar).



