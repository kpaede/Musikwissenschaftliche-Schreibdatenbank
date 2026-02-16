# Schreibwerkstatt und Ordnungssystem in Obsidian für Dramaturg:innen, Geistes- und Musikwissenschaftler:innen (die mit zettelkastenmäßigen Ansätzen nichts anfangen können)

Dieser Text geht davon aus, dass bekannt ist, was Obsidian ist, was Markdown ist und wie beide grundsätzlich funktionieren. Ich schreibe all das hier auf, weil ich den Eindruck habe, dass viele der Systeme, die kursieren, eigentlich ungeeignet sind, weil sie entweder zu naturwissenschaftlich zugeschnitten sind oder zu wenig thematisch funktionieren. Die vielen Zettelkasten-Tutorials online geben davon einen Eindruck: Die wenigsten von uns sind Luhmann und in einem zettelkasten den Überblick zu behalten funktioniert wegen der Binnenverlinkunken auch nur, wenn man seinen eigenen Kopf kennt. Meiner Meinung nach teilt es eine zentrale Schwachstelle auch mit dem, was einem oft „Atomic Notes“ verkauft wird: Um der Verknüpfungslogik gerecht zu werden, darf ein Gedanke dann nur eine einzige Notiz sein, was – zumindest für mich – total stgark gegen das Denken in komplexen Zusammenhängen funktioniert. Manchmal kommt es mir so vor, als wären viele der PKM-Leute, die einem diesen Konzepte andrehen wollen, eigentlich nur verliebt in eine hübsch visualisierte Datenorganisation selbst, aber hätten überhaupt kein Interesse an den Inhalten darin. Anyway. Ich persönlich habe in solchen Systemen überhaupt keine Chance, zusammengehörige Gedanken zu erfassen. Ich arbeite deswegen anders, nämlich gröber uind thematischer.  Dafür habe ich mir unterdessen ein System gebaut, das sicher nicht für alle praktikabel ist, für mich aber sehr gut funktioniert. Disclaimer: Ich bin Dramaturg für Musiktheater und Musikwissenschaftler; daher habe ich vor allem mit geisteswissenschaftliches Konzepten in komplexen gedanklichen Bögen zu tun; mit anspruchsvollen Texten und Kunstwerken.

# Disclaimer zu Zotero und Annotationen
Entgegen einem weitverbreiteten Ansatz halte ich nichts davon, Zotero-Annotationen automatisiert in Obsidian zu integrieren. Ich nutze Zotero intensiv zum wissenschaftlichen Schreiben innerhalb von Obsidian, aber  der automatische Import hat für mich zwei Probleme:
Viele PDFs, vor allem ältere Scans, sind qualitativ schlecht, dass ein Import ohne Korrekturaufwand des OCR-erkannten Texts möglich wäre. Ich habe keine Muße, hunderte Notizen händisch nachzubessern, nur weil sie automatisch implementiert wurden. Außerdem halte ich es für Unsinn, automatisch jedes Buch, das man gelesen und annotiert hat, in Obsidian zu haben. Manchmal braucht man etwa kleinere inhaltliche Abschnitte, manchmal größere. Für mich ist also nicht die Frage, was in der Hegel-Biografie steht, sondern ich würde eine Notiz aufmachen, in der ich mir selbst eine Frage beantworte, wie: Wie funktioniert der Begriff des Geistes bei Hegel.

Außerdem ist es eine wahnsinnige Errungenschaft von Programmen wie Zotero, dass man Exzerpte in ihrem Kontext erfassen kann. Wenn ich aber nur die Exzerpte in Obsidian importiere, fehlt mir dieser Kontext. In Obsidian kommt für mich da nur das, was eben die Frage beantwortet oder ein Thema bestimmt.

# Ordner, Tags, Properties

## Ordner
Bei mir kommt alles, was einen akademischen Großbereich betrifft (der geht bei mir von Philosophie über Geschichte bis Musikwissenschaft) erstmal in einen großen Ordner. Ich trenne nicht nach Disziplinen (das erledigen dann Tags), aber ich trenne strikt zwischen

- einem Datenbank-Ordner (in dem alle thematischen Notizen landen)
- meiner Schreibwerkstatt (in der alle Arbeitsdateien für Dinge landen, die Publikziert werden: Programmhefte, wissenschaftliche Texte, Bücher – aber auch erste Schlagwortsammlungen für einen neuen Beitrag)
- Sonderbereiche (Separate Ordner für Themen wie Gesundheit oder Fashion, die nichts mit meiner sonstigen Tätigkeit zu tun haben)

## Tags
In der Datenbank hat jede Notiz einen Titel und einen Großbereich, der ihr per hierarchischem (!) Tag in den Properties zugeteilt wird (z. B. #Musikwissenschaft, #Philosophie).
Wenn ich eine Note über einen RnB-Song schreibe, der Barockmusik zitiert, bekommt diese Notiz: #Musik/Barock und #Musik/Pop/RnB.

<img width="554" height="121" alt="Bildschirmfoto 2026-02-16 um 20 27 40" src="https://github.com/user-attachments/assets/ac05d99a-76a6-49ab-8408-ab21ebd0d4a8" />

Vorteil: Ich kann nach dem Obertag (#Musik) filtern und sehe alles , oder spezifischer in die Unterkategorien gehen.

Ich nutze das fantastsiche Plugin Notebook Navigator. Damit kann ich Dateien aus einer Ordneransicht einfach per Drag & Drop auf die Tags ziehen, um sie zuzuweisen.

<img width="315" height="172" alt="Bildschirmfoto 2026-02-16 um 20 26 41" src="https://github.com/user-attachments/assets/73cf3cbf-e74e-4463-9e32-8a7f632f521c" />


## 2. Properrties und Stammdatengenerierung mit der GND (Gemeinsame Normdatei)
Wenn ich thematisch arbeite, ist die Einteilung in Tags absichtsvoll grob, weil sie bei mir dazu dienen, schnell nach Oberkategorien zu navigieren. Sie sind bei mir nich dazu da, alle möglichen Informationen darin zu erfassen. Das übernehmen sogenannte Properties, die im "Header" einer Datei gespeichert werden und die man auch zum FIltern und sortieren nutzen kann. Das könnte etwa so aussehen.

<img width="498" height="367" alt="Bildschirmfoto 2026-02-16 um 20 33 32" src="https://github.com/user-attachments/assets/f37511ec-707f-4708-9ae9-d750a55011a8" />

dass damit etwas anzufangen ist, dürfte einleuchten. Man könnte zum Beispiel eine Reihe von Notizen nach einem bestimmten Jahr aufsteigend anordnen. Man könnte sich aber für einen bestimmten Bereich nur die Frauen anzeigen lassen oder Menschen, die einen bestimmten Wohnort hatten. Gleichzeitig ist es völlig uferlos, diese ganzen Dinge manuell einzutragen. Hier kommt eine Lösung ins Spiel, die ich bisher noch bei keiner anderen person gesehen haben. Die GND.

### Automatische Abfrage über die gemeinsame Normdatei (GND)

Die GND ist, wie der Name schon sagt, eine Normdatei, die alle möglichen nützlichen Daten beinhaltet: Zahlen, Orte, Synonyme, weiterführende Iformationen, Linklisten usw. Sie wird von wissenschaftlichen Institutionen gepflegt und ist der perfekte Grundstock, wenn man eine thematische Notzig anlegt. Mein Template ermöglicht den Abruf aus der Normdatei in die Properties automatisiert. Angenommen wir wollen eine Notiz zu Sarah Connor anlegen – dann lässt sich in einer Suchmaske  nach ihr suchen, dann auswählen, welche Felder man in die Properties übernehmen möchte. Anschließend wird unsere Notiz vorausgefüllt.

![Kapture 2026-02-16 at 20 41 57](https://github.com/user-attachments/assets/4aa5c8a0-8d03-45c4-b15d-32452eb02ccd)

Gleichzeitig dürfte im obigen Video aufgefallen sein, dass bestimmte Häkchen, was Daten angeht, schon gesetzt waren und dass sie auch schon deutsche Bezeichnungen hatten. Das ist kein Zufall. Es gibt hier nämlich eine Mapping-Datei, in der ich sowohl einstellen kann, welche Felder übernommen werden, als auch wie sie übersetzt werden sollen, falls ich zum Beispiel nicht "dateOfBirth" haben möchte, sondern "Geburtsdatum". Porträts oder Abbildungen werden automatisch als eingebetteter Markdown-Link integriert. Diese Datei sieht so aus

```
firstComposer: Komponist_in
biographicalOrHistoricalInformation: Historische Information
broaderTermPartitive: Teil von
placeOfActivity: Wirkungsort
depiction: depiction
```
Das heißt: 
"depiction: depiction" bedeutet: Das Feld "depiction" soll automatisch vorausgewählt werden, weil ich es immer brauche und nicht extra anhaken möchte.
"firstComposer: Komponist_in" heißt: Das Feld "firstComposer" soll automatisch vorausgewählt werden, weil ich es immer brauche – er soll aber bei mir "Komponist_in" heißen

Das Skript ist hier zu finden: [https://github.com/kpaede/Obsidian-Normdatei-Fetcher](https://github.com/kpaede/Obsidian-Normdatei-Fetcher)



## Die Schreibstube: Fußnoten, Zotero und Export
### Fußnoten
Für wissenschaftliche Texte nutze ich ausschließlich Inline-Fußnoten ^[Das ist eine Fußnote], weil Obsidian keine Seiten kennt. Wenn ich einen Textabschnitt lösche, verschwindet so außerdem die Inline-Fußnote mit – man vergisst keine Fußnotenleichen am Ende des Dokuments. Ich habe [hier](https://github.com/kpaede/convert-to-linine-footnotes) außerdem ein Python-Script erstellt, dass  klassische Fußnoten in Inline-Fußnoten umwandeln.

### Literaturverwaltung mit Zotero
Wie gesagt, lese ich in Zotero und annotiere meine Texte da auch. Ich halte nichts davon, in Obsidian nur die Annotationen zu übernehmen, weil, wie gesagt, der Kontext dieser Annotation ja entscheidend ist – und der ist innerhalb von Zotero. Gleichwohl halte ich es für einen sehr legitimen Ansatz, wenn man Exzerpte und Zusammenfassungen als Einzelnotizen in Obsidian hat. Für solche Workflows gibt es online haufenweise Tutorials. Hier geht es etwas anderes. 

### Live-Zitationen in Obsidian
Das Plugin Obsidian Pandoc Reference List: zeigt mir im Seitenpanel eine Live-Vorschau der Bibliografie im gewünschten Zitierstil an und liefert noch dazu eine Zotero-Suche und Live-Vorschau von Literaturangaben mir.

### Export nach Word
Für Export in andere Formate empfehle ich das [Obsidian Enhancing Export](https://github.com/mokeyish/obsidian-enhancing-export#obsidian-enhancing-export-plugin) plugin .

In [diesem Thread](https://forum.obsidian.md/t/exporting-with-citations/75428/3) beschreibt Feralflora was man tun muss, um Zitationen in Word nicht quasi-einzubrennen, sondern sie als Zotero-Referenzen zu bekommen: [https://retorque.re/zotero-better-bibtex/exporting/pandoc/index.html#from-markdown-to-zotero-live-citations](https://retorque.re/zotero-better-bibtex/exporting/pandoc/index.html#from-markdown-to-zotero-live-citations).

> [!NOTE]
> 1. Download the `zotero.lua` filter from the link above.
> 2. Find your Pandoc **user data folder** using the `pandoc --version` command in your OS’s terminal / command prompt.
>     - In this Pandoc folder, create a “filters” subfolder, and put the downloaded `zotero.lua` file into this folder.
>     - If no such user data folder exists at path you found in the terminal, create it and then also the aformentioned “filters” folder.
> 3. Put the following argument in the extra arguments of your **command template for Word** (docx) exports in Enhancing Export’s settings:
>     
>     `--lua-filter zotero.lua`
>     
>     - Double-check that you selected the right command template: Edit command template → Choose template → Word (.docx) template, before making any changes!
>     - Make sure to remove the `--citeproc`, `--bibliography`, `--csl` arguments, if you had added these. The `zotero.lua` filter will handle all this instead.
> 4. If necessary, specify additional arguments for `zotero.lua`.
>     - For example, if you are citing items in a group library, you should specify that with the `library` property (see below).
>     - This can be done in the note’s [properties 9](https://help.obsidian.md/Editing+and+formatting/Properties), like so:

## Musikwissenschaftliches Arbeiten

# Notation in Obsidian
Notenbeispiele müssten normalerweise ald Bilddateien eingebettet werden, was bedeutet, dass jede Änderung an einem Musikbeispiel mehrere Schritte erfordert: Neuerstellung in der Notensatzsoftware, Exportieren und anschließendes erneutes Einbetten. Zudem kann man in normalerweise Musikbeispiele nicht anhören, keine Layout-Optionen ändern oder nur einen bestimmten Takt anzeigen lassen. Man arbeitet mit Bildern und nicht mit Musik. Das ist frustrierend, solange die musikalische Seite noch Work in Progress ist.

Ich möchte deswegen desn von mir erstellten [Verovio Music Renderer](https://github.com/kpaede/Verovio-Music-Renderer) verwenden – aber schauen wir uns zuerst andere Lösungen an.

- Für [LilyPond](https://github.com/fuzzbyte/obsidian-lilypond): LilyPond ist ein offener Standard für textbasierte Musiknotation und liefert sehr schöne grafische Ergebnisse. Der Nachteil ist, dass die Notation textbasiert ist und daher nicht gerade einsteigerfreundlich. Dennoch ist es sehr nützlich, LilyPond innerhalb von Obsidian zu rendern, falls man es nutzt.

- ABC ist ein offener Standard für Musiknotation in Textform. Es dient als Eingabe-Markup-Sprache in Musiksoftware sowie als Speicherformat für Musikdateien. Mit dem Obsidian ABC.JS Plugin kannst du ABC-Dateien nicht nur bequem rendern und abspielen, sondern den ABC-Code auch direkt in MuseScore in einen Code-Block eingeben. Es ist textbasiert, aber sehr einsteigerfreundlich und perfekt für kleine Skizzen.

- Das [MuseScore integration plugin for Obsidian](https://github.com/RyotaUshio/obsidian-musescore#musescore-integration-plugin-for-obsidian) für Obsidian verfolgt einen anderen Ansatz. Es nutzt das PDF-Rendering von MuseScore als Auto-Export und ist ein weiterer sehr spannender Ansatz für dynamische Notation innerhalb von Obsidian. Im Gegensatz zum Verovio-Plugin (das wir verwenden werden) benötigt es keinen Export-Schritt nach MusicXML oder MEI innerhalb von MuseScore. Installiere es über BRAT. Der Ersteller dieses Plugins stellt es hier im Obsidian-Forum in einem sehr informativen Thread vor.

## Rendering, Wiedergabe und SVG-Download von MusicXML, MEI und ABC mit dem Verovio-Plugin

Obsidian ist kein Notensatzprogramm. Damit wir trotzdem gut arbeiten können, nutzen wir den Verovio Music Renderer, ein Plugin, das ich mangels Alternativen für diesen Fall entwickelt habe. Dies ist ein Plugin für Obsidian, das Verovio nutzt – eine Open-Source-Bibliothek zum Rendern von Noten in diversen Standards: MEI, MusicXML, ABC – und auch PAE, ein Format  mit dem man sehr gut kurze Notenskizzen anfertigen kann, ohne Obsidian zu verlassen. 

Dieses Plugin ist Teil der Obsidian Community-Plugins, was der einfachste Weg zur Installation ist. Du kannst es auch über BRAT installieren (füge einfach die URL hinzu, auf der du dich gerade befindest, als Beta-Plugin). Du kannst es auch manuell tun: Kopiere die Dateien main.js und manifest.json aus dem Release (siehe rechts) in den Plugin-Ordner deines Vaults wie folgt: VaultOrdner/.obsidian/plugins/Verovio-Music-Renderer/.

Installiere das Plugin und kopiere dann Folgendes in dein Obsidian-Dokument:

VON HIER KOPIEREN
```verovio
https://www.verovio.org/examples/downloads/Schubert_Lindenbaum.mei
```BIS HIER KOPIEREN


oder verwende einfach einen Dateinamen einer Datei in deinem Obsidian-Vault wie folgt:

VON HIER KOPIEREN
```verovio
Schubert_Lindenbaum.mei
```BIS HIER KOPIEREN


Rendering-Einstellungen

Im Einstellungsmenü des Obsidian-Plugins kannst du mehrere wichtige Parameter global für alle Renderings anpassen. Du kannst auch benutzerdefinierte Einstellungen für ein spezifisches Rendering anwenden, indem du sie deinem Code-Block in Obsidian hinzufügst. Bitte konsultiere die Verovio-Dokumentation für verfügbare Optionen. Beachte, dass nicht alle Optionen funktionieren könnten und sie sich gegenseitig beeinflussen können.

VON HIER KOPIEREN
```verovio
Schubert_Lindenbaum.mei
font: Leland
scale: 10
breaks: encoded
```BIS HIER KOPIEREN


Rendering spezifischer Takte

Eine Besonderheit dieses Plugins ist das Rendering vordefinierter Takte. Um die Takte 1–10 zu rendern, kannst du den Befehl measureRange wie in diesem Beispiel verwenden. Bitte beachte, dass in diesem Beispiel Takt 20 nicht im Rendering enthalten ist. Die Art der gewählten Umbrüche (breaks) kann das Ergebnis stark beeinflussen (oder sogar dazu führen, dass das Plugin gar nichts rendert). Aus diesem Grund wird im folgenden Beispiel breaks: none hinzugefügt, was oft eine gute Standardoption für das Rendern von Musik-Snippets ist. Du kannst auch "start" und "end" anstelle von Zahlen verwenden, z. B. measureRange: 15-end – oder nur einzelne Takte rendern: measureRange: 5

VON HIER KOPIEREN
```verovio
Schubert_Lindenbaum.mei
scale: 50
breaks: none
measureRange: 1-20
```BIS HIER KOPIEREN


Öffnen mit MuseScore

Die Schaltfläche "Open" öffnet die gerenderte Datei automatisch mit dem Programm, das im Betriebssystem damit verknüpft ist. MuseScore kann sowohl MEI- als auch MusicXML-Dateien importieren und exportieren. Nachdem du eine Datei mit MuseScore geöffnet hast, musst du sie als MusicXML oder MEI exportieren und die Datei, mit der du arbeitest, überschreiben.

Verwendung von musikalischen Glyphen im Text

Standardmäßig ist Obsidian nicht darauf ausgelegt, verschiedene Schriftarten inline (im Textfluss) zu verwenden. Mit ein paar Schritten lässt sich dies jedoch erreichen:

Installiere zuerst das Obsidian Custom Font Plugin.

Füge dann die gewünschten Schriftarten innerhalb des Plugins hinzu. Ich empfehle die folgenden Musik-Schriftarten von Dan Kreider: MusGlyphs und MusAnalysis.

Nachdem du die Schriftarten hinzugefügt hast, wähle "Multiple Fonts" unter dem Menüpunkt "Font" in den Einstellungen aus.

Um diese Schriftarten zu verwenden, müssen wir ein zusätzliches CSS-Snippet in den allgemeinen Darstellungseinstellungen von Obsidian hinzufügen, wie folgt. Dies stellt auch sicher, dass Ligaturen aktiviert sind, was für die Verwendung dieser Schriftarten notwendig ist.

 div.MusAnalysis {
    font-family: "MusAnalysis", sans-serif !important;
    font-feature-settings: "liga" 1, "clig" 1, "dlig" 1, "hlig" 1;
    -webkit-font-feature-settings: "liga" 1, "clig" 1, "dlig" 1, "hlig" 1;
    -moz-font-feature-settings: "liga" 1, "clig" 1, "dlig" 1, "hlig" 1;
    font-variant-ligatures: common-ligatures discretionary-ligatures historical-ligatures contextual;
    line-height: 3; /* Erhöhen Sie diesen Wert bei Bedarf */
}

div.MusGlyphs {
    font-family: "MusGlyphs", sans-serif !important;
    font-feature-settings: "liga" 1, "clig" 1, "dlig" 1, "hlig" 1;
    -webkit-font-feature-settings: "liga" 1, "clig" 1, "dlig" 1, "hlig" 1;
    -moz-font-feature-settings: "liga" 1, "clig" 1, "dlig" 1, "hlig" 1;
    font-variant-ligatures: common-ligatures discretionary-ligatures historical-ligatures contextual;
    line-height: 3; /* Erhöhen Sie diesen Wert bei Bedarf */
}

span.MusAnalysis {
    font-family: "MusAnalysis", sans-serif !important;
    font-feature-settings: "liga" 1, "clig" 1, "dlig" 1, "hlig" 1;
    font-variant-ligatures: common-ligatures discretionary-ligatures historical-ligatures contextual;
    line-height: 1.5; /* Bei Bedarf anpassen */
}

span.MusGlyphs {
    font-family: "MusGlyphs", sans-serif !important;
    font-feature-settings: "liga" 1, "clig" 1, "dlig" 1, "hlig" 1;
    font-variant-ligatures: common-ligatures discretionary-ligatures historical-ligatures contextual;
    line-height: 1.5; /* Bei Bedarf anpassen */
}


Danach kannst du musikalische Symbole wie folgt inline hinzufügen (und analog für andere Schriftarten):

<span class="MusAnalysis">
    &8Dv  &3T  &5DD/ &4Sg  
</span>


oder als separaten Absatz wie diesen:

<div class="MusAnalysis">
    &8Dv  &3T  &5DD/ &4Sg  
</div>


Ich empfehle dringend, diese mit dem Templater Plugin als Shortcuts einzurichten, damit du sie nicht jedes Mal ausschreiben musst. Auf diese Weise kannst du eine musikalische Glyphe mit einem einfachen Tastenkürzel hinzufügen. <span class="MusGlyphs">TC B3b T6# 5/4</span>
