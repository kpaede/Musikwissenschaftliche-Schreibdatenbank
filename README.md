# Schreibwerkstatt und Ordnungssystem in Obsidian für Dramaturg:innen, Geistes- und Musikwissenschaftler:innen (die mit zettelkastenmäßigen Ansätzen nichts anfangen können)

<img width="1355" height="836" alt="Pasted image 20240829115502 (2)" src="https://github.com/user-attachments/assets/11e760fb-60b7-4492-81f5-4c9d4a8989cf" />

Software wie Obsidian erlebt in diesen Jahren einen gewaltigen Boom. Und das hat gute Gründe. Denn damit lässt sich in Markdown, einer Auszeichnungssprache, eine Art eigene Wissensdatenbank erstellen, in der die einzelnen Notizen untereinander verlinkt sind. Das meine Leute, wenn sie einem erzählen, sie hätten sich nun ein Second Brain angelegt. Und in der Tat sind die Möglichkeiten unüberschaubar und vielfältig. Doch während die theoretische Vorstellung eines morfe or less eigenen Wikipedia für den eigenen Wissensgebrauch und eine Art Appendix für das eigene Gehirn eine nette Vorstellung ist, ist die praktische Umsetzung dessen eine ganz andere Geschichte. 

Systgemedie dafür kursieren, sind häufig ungeeignet, weil sie entweder zu naturwissenschaftlich zugeschnitten sind oder zu wenig inhaltlich funktionieren. Die vielen Zettelkasten-Tutorials online geben davon einen Eindruck: Die wenigsten von uns sind Luhmann und in einem Zettelkasten den Überblick zu behalten funktioniert wegen der Binnenverlinkunken auch nur, wenn man seinen eigenen Kopf kennt. Meiner Meinung nach teilt es eine zentrale Schwachstelle auch mit dem, was einem oft „Atomic Notes“ verkauft wird: Um der Verknüpfungslogik gerecht zu werden, darf ein Gedanke dann nur eine einzige Notiz sein, was – zumindest für mich – total stgark gegen das Denken in komplexen Zusammenhängen funktioniert. Manchmal kommt es mir so vor, als wären viele der PKM-Leute, die einem diesen Konzepte andrehen wollen, eigentlich nur verliebt in eine hübsch visualisierte Datenorganisation selbst, aber hätten überhaupt kein Interesse an den Inhalten darin. Anyway. Ich persönlich habe in solchen Systemen überhaupt keine Chance, zusammengehörige Gedanken zu erfassen. Ich arbeite deswegen anders, nämlich gröber uind thematischer.  Dafür habe ich mir unterdessen ein System gebaut, das sicher nicht für alle praktikabel ist, für mich aber sehr gut funktioniert. Disclaimer: Ich bin Dramaturg für Musiktheater und Musikwissenschaftler; daher habe ich vor allem mit geisteswissenschaftliches Konzepten in komplexen gedanklichen Bögen zu tun; mit anspruchsvollen Texten und Kunstwerken.

# Disclaimer zu Zotero und Annotationen
Entgegen einem weitverbreiteten Ansatz halte ich nichts davon, Zotero-Annotationen automatisiert in Obsidian zu integrieren. Ich nutze Zotero intensiv zum wissenschaftlichen Schreiben innerhalb von Obsidian, aber  der automatische Import von Textmarkierungen hat für mich zwei Probleme, die damit zusammenhängen, dass man sich damit die Wissensdatenbank zumüllt.
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


## Properties
Wenn ich thematisch arbeite, ist die Einteilung in Tags absichtsvoll grob, weil sie bei mir dazu dienen, schnell nach Oberkategorien zu navigieren. Sie sind bei mir nich dazu da, alle möglichen Informationen darin zu erfassen. Das übernehmen sogenannte Properties, die im "Header" einer Datei gespeichert werden und die man auch zum FIltern und sortieren nutzen kann. Das könnte etwa so aussehen.

<img width="498" height="367" alt="Bildschirmfoto 2026-02-16 um 20 33 32" src="https://github.com/user-attachments/assets/f37511ec-707f-4708-9ae9-d750a55011a8" />

dass damit etwas anzufangen ist, dürfte einleuchten. Man könnte zum Beispiel eine Reihe von Notizen nach einem bestimmten Jahr aufsteigend anordnen. Man könnte sich aber für einen bestimmten Bereich nur die Frauen anzeigen lassen oder Menschen, die einen bestimmten Wohnort hatten. Gleichzeitig ist es völlig uferlos, diese ganzen Dinge manuell einzutragen. Hier kommt eine Lösung ins Spiel, die ich bisher noch bei keiner anderen person gesehen haben. Die GND.

### Arbeitsersparnis durch automatische Abfrage der gemeinsame Normdatei (GND)

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



## Schreibstube: Fußnoten, Zotero und Export
### Fußnoten
Für wissenschaftliche Texte nutze ich ausschließlich Inline-Fußnoten ^[Das ist eine Fußnote], weil Obsidian keine Seiten kennt. Wenn ich einen Textabschnitt lösche, verschwindet so außerdem die Inline-Fußnote mit – man vergisst keine Fußnotenleichen am Ende des Dokuments. Ich habe [hier](https://github.com/kpaede/convert-to-linine-footnotes) außerdem ein Python-Script erstellt, dass  klassische Fußnoten in Inline-Fußnoten umwandeln.

### Literaturverwaltung mit Zotero
Wie gesagt, lese ich in Zotero und annotiere meine Texte da auch. Ich halte nichts davon, in Obsidian nur die Annotationen zu übernehmen, weil, wie gesagt, der Kontext dieser Annotation ja entscheidend ist – und der ist innerhalb von Zotero. Gleichwohl halte ich es für einen sehr legitimen Ansatz, wenn man Exzerpte und Zusammenfassungen als Einzelnotizen in Obsidian hat. Für solche Workflows gibt es online haufenweise Tutorials. Hier geht es etwas anderes. 

### Live-Zitationen in Obsidian
Das Plugin [Obsidian Pandoc Reference List](https://github.com/mgmeyers/obsidian-pandoc-reference-list) zeigt mir im Seitenpanel eine Live-Vorschau der Bibliografie im gewünschten Zitierstil an und liefert noch dazu eine Zotero-Suche und Live-Vorschau von Literaturangaben mir.

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

### RISM / Abruf von Komponist:innendaten
Ähnlich wie oben für die GND geschildert, habe ich ein [Plugin](https://github.com/kpaede/Obsidian-RISM-fetcher) erstellt, mit dem man auf die (mit der MGG abgestimmten) RISM-Daten zugreifen kann und sie in Properties verwandeln. Weil ich dieses Template zuerst erstellt habe, hat es noch nicht die Möglichkeit, so elaboriert mit Front Matter umzugehen, wie das GmD-Plug-in. Ich denke, es ist trotzdem ganz brauchbar. Jeder kann es sich gerne auch für seine eigenen Zwecke anpassen. Es muss einfach als Template mit dem Templator Plugin ausgeführt werden und ruft sich die Daten automatisch ab . EWs ist hier zu finden: [https://github.com/kpaede/Obsidian-RISM-fetcher](https://github.com/kpaede/Obsidian-RISM-fetcher)

![ezgif-12d1036ee86f6750|400](https://github.com/user-attachments/assets/290babbd-6767-4f0d-8488-cb95614d91e8)

## Verwendung von musikalischen Glyphen im Text

<img width="687" height="90" alt="Pasted image 20240829115502 (1)" src="https://github.com/user-attachments/assets/20769162-d840-47f6-9cec-12f741c0e254" />

Standardmäßig ist Obsidian nicht darauf ausgelegt, verschiedene Schriftarten inline (im Textfluss) zu verwenden. Mit ein paar Schritten lässt sich dies jedoch erreichen:

Installiere zuerst das [Obsidian Custom Font Plugin](https://github.com/pourmand1376/obsidian-custom-font#obsidian-custom-font-plugin).

Füge dann die gewünschten Schriftarten innerhalb des Plugins hinzu. Ich empfehle die folgenden Musik-Schriftarten von Dan Kreider: [MusGlyphs](https://www.notationcentral.com/product/musglyphs/) und [MusAnalysis](https://www.notationcentral.com/product/musanalysis/).

Nachdem du die Schriftarten hinzugefügt hast, wähle "Multiple Fonts" unter dem Menüpunkt "Font" in den Einstellungen aus.

Um diese Schriftarten zu verwenden, müssen wir ein zusätzliches CSS-Snippet in den allgemeinen Darstellungseinstellungen von Obsidian hinzufügen, wie folgt. Dies stellt auch sicher, dass Ligaturen aktiviert sind, was für die Verwendung dieser Schriftarten notwendig ist.

```code
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
    line-height: 1.5; /* Adjust this as needed */
}
}

span.MusGlyphs {
    font-family: "MusGlyphs", sans-serif !important;
    font-feature-settings: "liga" 1, "clig" 1, "dlig" 1, "hlig" 1;
    font-variant-ligatures: common-ligatures discretionary-ligatures historical-ligatures contextual;
    line-height: 1.5; /* Adjust this as needed */
}
```

Dann lassen sich musikalische Symbole (gemäß Font-Handbuch) folgendermaßen einsetzen:

```code
<span class="MusAnalysis">
    &8Dv  &3T  &5DD/ &4Sg  
</span>
```
Oder auch als separater Absatz:

```code
<div class="MusAnalysis">
    &8Dv  &3T  &5DD/ &4Sg  
</span>
```

Wenn man sich mit dem [Templater Plugin](https://github.com/SilentVoid13/Templater) diesen Code vorbereitet, kann man musikalische Glyphen mit einem einfachen Shortcut einfügen.<span class="MusGlyphs">TC B3b T6# 5/4</span>



### Notation in Obsidian
Notenbeispiele müssten normalerweise ald Bilddateien eingebettet werden, was bedeutet, dass jede Änderung an einem Musikbeispiel mehrere Schritte erfordert: Neuerstellung in der Notensatzsoftware, Exportieren und anschließendes erneutes Einbetten. Zudem kann man in normalerweise Musikbeispiele nicht anhören, keine Layout-Optionen ändern oder nur einen bestimmten Takt anzeigen lassen. Man arbeitet mit Bildern und nicht mit Musik. Das ist frustrierend, solange die musikalische Seite noch Work in Progress ist.

Ich möchte deswegen den von mir erstellten [Verovio Music Renderer](https://github.com/kpaede/Verovio-Music-Renderer) verwenden – aber schauen wir uns zuerst andere Lösungen an.

- Für [LilyPond](https://github.com/fuzzbyte/obsidian-lilypond): LilyPond ist ein offener Standard für textbasierte Musiknotation und liefert sehr schöne grafische Ergebnisse. Der Nachteil ist, dass die Notation textbasiert ist und daher nicht gerade einsteigerfreundlich. Dennoch ist es sehr nützlich, LilyPond innerhalb von Obsidian zu rendern, falls man es nutzt.

- ABC ist ein offener Standard für Musiknotation in Textform. Es dient als Eingabe-Markup-Sprache in Musiksoftware sowie als Speicherformat für Musikdateien. Mit dem Obsidian ABC.JS Plugin kannst du ABC-Dateien nicht nur bequem rendern und abspielen, sondern den ABC-Code auch direkt in MuseScore in einen Code-Block eingeben. Es ist textbasiert, aber sehr einsteigerfreundlich und perfekt für kleine Skizzen.

- Das [MuseScore integration plugin for Obsidian](https://github.com/RyotaUshio/obsidian-musescore#musescore-integration-plugin-for-obsidian) für Obsidian verfolgt einen anderen Ansatz. Es nutzt das PDF-Rendering von MuseScore als Auto-Export und ist ein weiterer sehr spannender Ansatz für dynamische Notation innerhalb von Obsidian. Im Gegensatz zum Verovio-Plugin (das wir verwenden werden) benötigt es keinen Export-Schritt nach MusicXML oder MEI innerhalb von MuseScore. Installiere es über BRAT. Der Ersteller dieses Plugins stellt es hier im Obsidian-Forum in einem sehr informativen Thread vor.

# Das Verovio-Plugin

![demo (1)](https://github.com/user-attachments/assets/fba77f9e-5aee-4469-8156-d0071950413c)

Dieses Plugin für Obsidian nutzt Verovio, eine leichtgewichtige Open-Source-Bibliothek, um Musiknotation im MEI-Format (Music Encoding Initiative) sowie ABC-, MusicXML- und PAE in hochwertigen SVG-Grafiken einzubetten. Mit diesem Tool lässt sich Notation direkt in Obsidian rendern, bearbeiten und abspielen, was den Workflow viel komfortabler macht.

Die wichtigsten Funktionen im Überblick:
- Dynamisches Rendering: Rendert MEI, ABC, MusicXML und PAE direkt aus dem Obsidian-Ordner (relative Pfade), von URLs (absolute Pfade) oder direkt aus Code-Blöcken.
- Interaktiver Editor: Eine Seitenleiste ermöglicht das Bearbeiten des Notencodes (mit Syntax-Highlighting für XML und MEI). Besonders komfortabel: Wenn man auf eine gerenderte Note klickst, springt der Cursor direkt zur entsprechenden Codezeile (derzeit nur für MEI in Code-Blöcken möglich).
- SVG-Export: Über eine Toolbar (erscheint beim Drüberfahren mit der Maus) lässt sich die gerenderte Notation als SVG-Datei herunterladen.
- Individuelle Einstellungen: Ein Menü bietet Optionen für das Rendering, inklusive Dark Mode und anpassbarer Hervorhebungsfarben.
- Audio-Wiedergabe: Man kann Musik direkt abspielen, wobei die aktuell gespielten Noten synchron zum Ton optisch hervorgehoben werden.
- Externe Bearbeitung: Öffne die Quelldatei mit nur einem Klick mit dem jeweiligen Standardeditor (Sibelius, Musescore usw.)
- Präzise Auswahl: Es lassen sich gezielt bestimmte Takte auswählen und rendern.
- Navigation: Enthält Schaltflächen zum Umblättern sowie eine automatische Blätterfunktion während der Wiedergabe

Installiere das Plugin aus dem Obsidian-PLugin-Store, aktiviere es und kopier dann bspw. diesen Code.

```
COPY FROM HERE
```verovio
https://www.verovio.org/examples/downloads/Schubert_Lindenbaum.mei
```COPY UNTIL HERE

```

Auch lokale Dateien funktionieren:

```
COPY FROM HERE
```verovio
Schubert_Lindenbaum.mei
```COPY UNTIL HERE

```
Sowie der jweilige Code direkt im Codeblock:

```
COPY FROM HERE
```verovio
<mei xmlns="http://www.music-encoding.org/ns/mei">
  <music>
    <body>
      <mdiv>
        <score>
          <section>
            <measure n="1">
              <staff n="1">
                <layer n="1">
                  <note pname="c" oct="4" dur="4"/>
                  <note pname="e" oct="4" dur="4"/>
                  <note pname="g" oct="4" dur="4"/>
                </layer>
              </staff>
            </measure>
          </section>
        </score>
      </mdiv>
    </body>
  </music>
</mei>
```COPY UNTIL HERE
```

Auch mit ABC Notation 

```
COPY FROM HERE
```verovio
X:1
T: Test-Melody
M:4/4
K:C
C D | G A B c |
```COPY UNTIL HERE
```

und MEI

```
COPY FROM HERE
```verovio
<mei xmlns="http://www.music-encoding.org/ns/mei" meiversion="4.0.0">
  <meiHead>
    <fileDesc>
      <titleStmt>
        <title>Another Test</title>
      </titleStmt>
      <pubStmt/>
    </fileDesc>
  </meiHead>
  <music>
    <body>
      <mdiv>
        <score>
          <scoreDef meter.count="4" meter.unit="4" key.sig="0">
            <staffGrp>
              <staffDef n="1" lines="5" clef.shape="G" clef.line="2"/>
            </staffGrp>
          </scoreDef>
          <section>
            <measure n="1">
              <staff n="1">
                <layer n="1">
                  <note pname="c" oct="4" dur="4"/>
                  <note pname="d" oct="4" dur="4"/>
                  <note pname="e" oct="4" dur="4"/>
                  <note pname="f" oct="4" dur="4"/>
                </layer>
              </staff>
            </measure>
          </section>
        </score>
      </mdiv>
    </body>
  </music>
</mei>
```COPY UNTIL HERE
```
sowie zuletzt PAE
```
COPY FROM HERE
```verovio
@clef:G-2
@keysig:
@timesig:c
@data:2''C'B/=/''CC/=/2-4DE/2-8{'B''C+C'B}/2''C-//
```COPY UNTIL HERE
```
## Side Panel
Man kann über die Obsidian-Befehlspalette eine Seitenleiste öffnen, um den Notatations-Code direkt zu bearbeiten – inklusive Syntax-Hervorhebung für XML und MEI. Wenn man auf eine gerenderte Note klickt, springt der Cursor automatisch zur entsprechenden Codezeile. Das funktioniert jedoch nur bei MEI-Code innerhalb eines Codeblocks, nicht bei extern verknüpften Dateien.

<img width="1431" height="923" alt="sidepanel" src="https://github.com/user-attachments/assets/42b47436-4acc-4b7a-af3d-7f3fa5ed2860" />

## Rendering Options
Im Einstellungsmenü des Obsidian-Plugins lassen sich verschiedene wichtige Parameter global für alle Renderings anpassen, einschließlich eines Dark Modes und der Auswahl einer Hervorhebungsfarbe.
Zudem können benutzerdefinierte Einstellungen für ein spezifisches Rendering angewendet werden, indem man diese direkt dem jeweiligen Code-Block in Obsidian hinzufügt. Informationen zu den verfügbaren Optionen finden sich in der [Verovio documentation](https://book.verovio.org/toolkit-reference/toolkit-options.html). Es ist zu beachten, dass nicht alle Optionen funktionieren und diese sich gegenseitig beeinflussen können. Bitte berücksichtigen Sie zudem, dass diese Funktionen beim Rendering direkt aus einem Code-Block heraus (noch) nicht unterstützt werden.


```
COPY FROM HERE
```verovio
Schubert_Lindenbaum.mei
font: Leland
scale: 10
breaks: encoded
```COPY UNTIL HERE

```

Ein besonderes Merkmal dieses Plugins ist das Rendern vordefinierter Takte. Um beispielsweise die Takte 1–10 darzustellen, kann man den Befehl measureRange verwenden. Bitte beachten Sie, dass in diesem Fall Takt 20 nicht im Rendering enthalten wäre. Die gewählte Art der Zeilenumbrüche (breaks) kann das Ergebnis stark beeinflussen (oder im schlimmsten Fall dazu führen, dass gar nichts gerendert wird). So kann die Einstellung „encoded“ zu einer leeren Anzeige führen, wenn in der getroffenen Auswahl kein kodierter Umbruch existiert. Daher wird im folgenden Beispiel breaks: none verwendet, was oft eine gute Standardoption für das Rendern kurzer Musikfragmente ist. Man kann zudem „start“ und „end“ anstelle von Zahlen nutzen, z. B. 'measureRange: 15-end' – oder auch nur einzelne Takte ausgeben lassen: 'measureRange: 5'


```
COPY FROM HERE
```verovio
Schubert_Lindenbaum.mei
scale: 50
breaks: none
measureRange: 1-20
```COPY UNTIL HERE

```
