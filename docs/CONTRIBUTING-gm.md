*[Lesen Sie dies in anderen Sprachen](README.md#translations)*

## Lizenzvereinbarung für Mitwirkende

Durch Ihren Beitrag stimmen Sie der [LIZENZ](../LICENSE) dieses Repositorys zu.

## Verhaltenskodex für Mitwirkende

Durch Ihren Beitrag stimmen Sie zu, den [Verhaltenskodex](CODE_OF_CONDUCT.md) dieses Repositorys zu respektieren. ([translations](README.md#translations))

## Kurz gesagt

1. „Ein Link zum einfachen Herunterladen eines Buches“ ist nicht immer ein Link zu einem *kostenlosen* Buch. Bitte tragen Sie nur kostenlose Inhalte bei. Stellen Sie sicher, dass sie kostenlos sind. Wir akzeptieren keine Links zu Seiten, die funktionierende E-Mail-Adressen *erfordern*, um Bücher zu erhalten, aber wir begrüßen Einträge, die diese anfordern.

2. Sie müssen Git nicht kennen: Wenn Sie etwas Interessantes gefunden haben, das *noch nicht in diesem Repo* ist, öffnen Sie bitte ein [Problem](https://github.com/EbookFoundation/free-programming-books/issues) mit Ihren Linkvorschlägen.
- Wenn Sie Git kennen, forken Sie bitte das Repo und senden Sie Pull Requests (PR).

3. Wir haben 6 Arten von Listen. Wählen Sie die richtige aus:

- *Bücher*: PDF, HTML, ePub, eine auf gitbook.io basierende Site, ein Git-Repo usw.
- *Kurse*: Ein Kurs ist ein Lernmaterial, das kein Buch ist. [Dies ist ein Kurs](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/).
- *Interaktive Tutorials*: Eine interaktive Website, auf der der Benutzer Code oder Befehle eingeben und das Ergebnis auswerten kann (mit „auswerten“ meinen wir nicht „benoten“). z. B.: [Probieren Sie Haskell aus](http://tryhaskell.org), [Probieren Sie Git aus](https://learngitbranching.js.org).
- *Spielplätze*: sind Online- und interaktive Websites, Spiele oder Desktop-Software zum Erlernen des Programmierens. Schreiben, kompilieren (oder ausführen) und teilen Sie Codeausschnitte. Auf Spielplätzen können Sie häufig Code abspalten und sich die Hände schmutzig machen, indem Sie mit Code spielen.
- *Podcasts und Screencasts*: Podcasts und Screencasts.
- *Problem Sets & Competitive Programming*: Eine Website oder Software, mit der Sie Ihre Programmierkenntnisse durch das Lösen einfacher oder komplexer Probleme mit oder ohne Codeüberprüfung und mit oder ohne Vergleich der Ergebnisse mit anderen Benutzern bewerten können.

4. Befolgen Sie unbedingt die [Richtlinien unten](#Richtlinien) und beachten Sie die [Markdown-Formatierung](#Formatierung) der Dateien.

5. GitHub Actions führt Tests durch, um **sicherzustellen, dass Ihre Listen alphabetisch sortiert sind** und **Formatierungsregeln eingehalten werden**. **Stellen Sie sicher**, dass Ihre Änderungen die Tests bestehen.

### Richtlinien

- Stellen Sie sicher, dass ein Buch kostenlos ist. Überprüfen Sie es bei Bedarf noch einmal. Es hilft den Administratoren, wenn Sie in der PR kommentieren, warum Sie denken, dass das Buch kostenlos ist.
- Wir akzeptieren keine Dateien, die auf Google Drive, Dropbox, Mega, Scribd, Issuu und anderen ähnlichen Datei-Upload-Plattformen gehostet werden.
- Fügen Sie Ihre Links in alphabetischer Reihenfolge ein, wie [unten] beschrieben (#alphabetische Reihenfolge).
- Verwenden Sie den Link mit der maßgeblichsten Quelle (d. h. die Website des Autors ist besser als die Website des Herausgebers, die wiederum besser ist als eine Website eines Drittanbieters)

- Keine Dateihostingdienste (dazu gehören (aber nicht ausschließlich) Dropbox- und Google Drive-Links)

- Ziehen Sie immer einen „https“-Link einem „http“-Link vor – solange sie sich auf derselben Domain befinden und denselben Inhalt bieten

- Entfernen Sie auf Stammdomains den abschließenden Schrägstrich: „http://example.com“ statt „http://example.com/“

- Ziehen Sie immer den kürzesten Link vor: „http://example.com/dir/“ ist besser als „http://example.com/dir/index.html“

- Keine URL-Shortener-Links

- Ziehen Sie normalerweise den „aktuellen“ Link dem „Versions“-Link vor: „http://example.com/dir/book/current/“ ist besser als „http://example.com/dir/book/v1.0.0/index.html“

- Wenn ein Link eine abgelaufenes Zertifikat/selbstsigniertes Zertifikat/SSL-Problem jeglicher Art:
1. *ersetzen* Sie es, wenn möglich, durch das entsprechende „http“-Gegenstück (da das Akzeptieren von Ausnahmen auf Mobilgeräten kompliziert sein kann).
2. *lassen Sie es*, wenn keine „http“-Version verfügbar ist, der Link aber weiterhin über „https“ zugänglich ist, indem Sie dem Browser eine Ausnahme hinzufügen oder die Warnung ignorieren.
3. Andernfalls *entfernen* Sie es.
- wenn ein Link in mehreren Formaten vorhanden ist, fügen Sie einen separaten Link mit einer Anmerkung zu jedem Format hinzu
- wenn eine Ressource an verschiedenen Stellen im Internet vorhanden ist
- verwenden Sie den Link mit der maßgeblichsten Quelle (d. h. die Website des Autors ist besser als die Website des Herausgebers ist besser als die Website eines Drittanbieters)
- wenn sie auf verschiedene Ausgaben verweisen und Sie der Meinung sind, dass diese Ausgaben unterschiedlich genug sind, um sie beizubehalten, fügen Sie einen separaten Link mit einer Anmerkung zu jeder Ausgabe hinzu (siehe [Problem Nr. 2353](https://github.com/EbookFoundation/free-programming-books/issues/2353), um zur Diskussion über die Formatierung beizutragen).
- ziehen Sie atomare Commits (ein Commit durch Hinzufügen/Löschen/Ändern) größeren Commits vor. Sie müssen Ihre Commits nicht zusammenfassen, bevor Sie einen PR einreichen. (Wir werden diese Regel niemals durchsetzen, da es nur eine Frage der Bequemlichkeit für die Betreuer ist)
- wenn das Buch älter ist, geben Sie das Veröffentlichungsdatum mit dem Titel an.
- geben Sie den Namen oder die Namen des Autors an, wo dies angebracht ist. Sie können Autorenlisten mit „et al.“ abkürzen.
- Wenn das Buch noch nicht fertig ist und noch daran gearbeitet wird, fügen Sie die Anmerkung „in Bearbeitung“ hinzu, wie [unten](#in_process) beschrieben.
- Wenn eine Ressource mithilfe der [*Internet Archive's Wayback Machine*](https://web.archive.org) (oder ähnlich) wiederhergestellt wird, fügen Sie die Anmerkung „archiviert“ hinzu, wie [unten](#archived) beschrieben. Die besten Versionen sind aktuell und vollständig.
- Wenn vor dem Aktivieren des Downloads eine E-Mail-Adresse oder die Einrichtung eines Kontos angefordert wird, fügen Sie sprachspezifische Anmerkungen in Klammern hinzu, z. B.: „(E-Mail-Adresse *angefordert*, nicht erforderlich)“.

### Formatierung

- Alle Listen sind `.md`-Dateien. Versuchen Sie, die [Markdown](https://guides.github.com/features/mastering-markdown/)-Syntax zu lernen. Es ist ganz einfach!
- Alle Listen beginnen mit einem Index. Die Idee ist, alle Abschnitte und Unterabschnitte dort aufzulisten und zu verlinken. Halten Sie es in alphabetischer Reihenfolge.
- Abschnitte verwenden Überschriften der Ebene 3 (`###`) und Unterabschnitte sind Überschriften der Ebene 4 (`####`).

Die Idee ist, Folgendes zu haben:

- `2` leere Zeilen zwischen dem letzten Link und dem neuen Abschnitt.
- `1` leere Zeile zwischen Überschrift und erstem Link des Abschnitts.
- `0` leere Zeile zwischen zwei Links.
- `1` leere Zeile am Ende jeder `.md`-Datei.

Beispiel:

```Text
[...]
* [Ein tolles Buch](http://example.com/example.html)
(leere Zeile)
(leere Zeile)
### Beispiel
(leere Zeile)
* [Ein anderes tolles Buch](http://example.com/book.html)
* [Ein anderes Buch](http://example.com/other.html)
```

- Setzen Sie keine Leerzeichen zwischen `]` und `(`:

```Text
SCHLECHT: * [Ein anderes tolles Buch] (http://example.com/book.html)
GUT: * [Ein anderes tolles Buch](http://example.com/book.html)
```

- Wenn Sie den Autor angeben, verwenden Sie `-` (einen Bindestrich, umgeben von einzelnen Leerzeichen):

```Text
SCHLECHT: * [Ein anderes tolles Buch](http://example.com/book.html)- John Doe
GUT: * [Ein anderes tolles Buch](http://example.com/book.html) - John Doe
```

- Setzen Sie ein einzelnes Leerzeichen zwischen den Link und sein Format:

```Text
SCHLECHT: * [Ein sehr tolles Buch](https://example.org/book.pdf)(PDF)
GUT: * [Ein sehr tolles Buch](https://example.org/book.pdf) (PDF)
```

- Der Autor kommt vor dem Format:

```Text
SCHLECHT: * [Ein sehr tolles Buch](https://example.org/book.pdf)- (PDF) Jane Roe
GUT: * [Ein sehr tolles Buch](https://example.org/book.pdf) - Jane Roe (PDF)
```

- Mehrere Formate (Wir bevorzugen einen einzelnen Link für jede Ressource. Wenn es keinen einzelnen Link mit einfachem Zugriff auf verschiedene Formate gibt, können mehrere Links sinnvoll sein. Aber jeder Link, den wir hinzufügen, verursacht Wartungsaufwand, also versuchen wir, ihn zu vermeiden.):

```Text
SCHLECHT: * [Ein weiteres großartiges Buch](http://example.com/)- John Doe (HTML)
SCHLECHT: * [Ein weiteres großartiges Buch](https://downloads.example.org/book.html)- John Doe (Download-Site)
GUT: * [Ein weiteres großartiges Buch](http://example.com/) - John Doe (HTML) [(PDF, EPUB)](https://downloads.example.org/book.html)
```

- Fügen Sie bei älteren Büchern das Erscheinungsjahr in den Titel ein:

```text
SCHLECHT: * [Ein sehr tolles Buch](https://example.org/book.html) - Jane Roe - 1970
GUT: * [Ein sehr tolles Buch (1970)](https://example.org/book.html) - Jane Roe
```

- <a id="in_process"></a>In Bearbeitung befindliche Bücher:

```text
GUT: * [Wird bald ein tolles Buch sein](http://example.com/book2.html) - John Doe (HTML) *(:construction: in process)*
```

- <a id="archived"></a>Archivierter Link:

```text
GUT: * [Ein weit zurückliegendes, interessantes Buch](https://web.archive.org/web/20211016123456/http://example.com/) - John Doe (HTML) *(:card_file_box: archiviert)*
```

- <a id="license"></a>Kostenlose Lizenzen (Obwohl wir Ressourcen einschließen, die „Alle Rechte vorbehalten“ sind, aber kostenlos gelesen werden können, empfehlen wir die Verwendung kostenloser Lizenzen wie Creative Commons):

```Text
GUT: * [Ein sehr tolles Buch](https://example.org/book.pdf) – Jane Roe (PDF) (CC BY-SA)
```

Unterstützte Lizenzen (keine Versionierung):

- `CC BY` „Creative Commons Namensnennung“
- `CC BY-NC` „Creative Commons nicht kommerziell“
- `CC BY-SA` „Creative Commons Weitergabe unter gleichen Bedingungen“
- `CC BY-NC-SA` „Creative Commons nicht kommerziell, Weitergabe unter gleichen Bedingungen“
- `CC BY-ND` „Creative Commons keine Bearbeitungen“
- `CC BY-NC-ND` „Creative Commons nicht kommerziell, keine Ableitungen“

- „GFDL“ „Gnu Free Documentation License“

### Alphabetische Reihenfolge

- Wenn mehrere Titel mit demselben Buchstaben beginnen, sortieren Sie sie nach der Sekunde und so weiter. Beispiel: „aa“ kommt vor „ab“.

- „one two“ kommt vor „onetwo“

Wenn Sie einen falsch platzierten Link sehen, überprüfen Sie die Linter-Fehlermeldung, um zu wissen, welche Zeilen vertauscht werden sollten.

### Hinweise

Obwohl die Grundlagen relativ einfach sind, gibt es eine große Vielfalt bei den von uns aufgelisteten Ressourcen. Hier sind einige Hinweise dazu, wie wir mit dieser Vielfalt umgehen.

#### Metadaten

Unsere Listen bieten einen minimalen Satz an Metadaten: Titel, URLs, Ersteller, Plattformen und Zugriffshinweise.

##### Titel

- Keine erfundenen Titel. Wir versuchen, Titel aus den Ressourcen selbst zu übernehmen; Mitwirkende werden ermahnt, keine Titel zu erfinden oder sie redaktionell zu verwenden, wenn dies vermieden werden kann. Eine Ausnahme gilt für ältere Werke; Wenn sie hauptsächlich von historischem Interesse sind, hilft eine Jahresangabe in Klammern, die an den Titel angehängt wird, den Benutzern zu erkennen, ob sie von Interesse sind.
- Keine Titel in GROSSBUCHSTABEN. Normalerweise ist die Groß-/Kleinschreibung angemessen, aber im Zweifelsfall verwenden Sie die Großschreibung aus der Quelle.
- Keine Emojis.

##### URLs

- Wir erlauben keine verkürzten URLs.
- Tracking-Codes müssen aus der URL entfernt werden.
- Internationale URLs sollten maskiert werden. Browserleisten rendern diese normalerweise in Unicode, aber verwenden Sie bitte Kopieren und Einfügen.
- Sichere (`https`) URLs sind immer nicht sicheren (`http`) URLs vorzuziehen, bei denen HTTPS implementiert wurde.
- Wir mögen keine URLs, die auf Webseiten verweisen, die die aufgeführte Ressource nicht hosten, sondern woanders hin.

##### Urheber

- Wir möchten die Urheber kostenloser Ressourcen, wo angemessen, nennen, einschließlich Übersetzer!
- Bei übersetzten Werken sollte der ursprüngliche Autor genannt werden. Wir empfehlen die Verwendung von [MARC-Relatoren](https://loc.gov/marc/relators/relaterm.html), um andere Urheber als Autoren zu nennen, wie in diesem Beispiel:

```Markdown
* [Ein übersetztes Buch](http://example.com/book.html) - John Doe, `trl.:` Mike The Translator
```

hier verwendet die Anmerkung `trl.:` den MARC-Relatorcode für „Übersetzer“.
- Verwenden Sie ein Komma `,`, um jedes Element in der Autorenliste abzugrenzen.
- Sie können Autorenlisten mit „`et al.`“ abkürzen.
- Wir erlauben keine Links für Urheber.
- Bei Zusammenstellungen oder Remixes benötigt der „Urheber“ möglicherweise eine Beschreibung. Beispielsweise werden die Bücher „GoalKicker“ oder „RIP Tutorial“ als „`Zusammengestellt aus der StackOverflow-Dokumentation`“ genannt.
- Wir verwenden keine Ehrentitel wie „Prof.“ oder „Dr.“ in den Namen der Urheber.

##### Zeitlich begrenzte Kurse und Testversionen

- Wir listen keine Dinge auf, die wir in sechs Monaten entfernen müssen.
- Wenn ein Kurs eine begrenzte Einschreibungsdauer oder Dauer hat, listen wir ihn nicht auf.
- Wir können keine Ressourcen auflisten, die für einen begrenzten Zeitraum kostenlos sind.

##### Plattformen und Zugangshinweise

- Kurse. Insbesondere für unsere Kurslisten ist die Plattform ein wichtiger Teil der Ressourcenbeschreibung. Dies liegt daran, dass Kursplattformen unterschiedliche Möglichkeiten und Zugangsmodelle haben. Während wir normalerweise kein Buch auflisten, für das eine Registrierung erforderlich ist, haben viele Kursplattformen Möglichkeiten, die ohne eine Art Konto nicht funktionieren. Beispiele für Kursplattformen sind Coursera, EdX, Udacity und Udemy. Wenn ein Kurs von einer Plattform abhängt, sollte der Plattformname in Klammern aufgeführt werden.
- YouTube. Wir haben viele Kurse, die aus YouTube-Wiedergabelisten bestehen. Wir listen YouTube nicht als Plattform auf, sondern versuchen, den YouTube-Ersteller aufzulisten, was oft eine Unterplattform ist.
- YouTube-Videos. Wir verlinken normalerweise nicht auf einzelne YouTube-Videos, es sei denn, sie sind länger als eine Stunde und wie ein Kurs oder ein Tutorial aufgebaut. Wenn dies der Fall ist, vermerken Sie dies unbedingt in der PR-Beschreibung.
- Keine verkürzten (z. B. youtu.be/xxxx) Links!
- Leanpub. Leanpub hostet Bücher mit einer Vielzahl von Zugriffsmodellen. Manchmal kann ein Buch ohne Registrierung gelesen werden; manchmal erfordert ein Buch für den kostenlosen Zugriff ein Leanpub-Konto. Angesichts der Qualität der Bücher und der Mischung und Fluidität der Leanpub-Zugriffsmodelle erlauben wir die Auflistung der letzteren mit dem Zugriffsvermerk `*(Leanpub-Konto oder gültige E-Mail-Adresse erforderlich)*`.

#### Genres

Die erste Regel bei der Entscheidung, in welche Liste eine Ressource gehört, besteht darin, zu sehen, wie sich die Ressource selbst beschreibt. Wenn sie sich selbst als Buch bezeichnet, dann ist sie vielleicht ein Buch.

##### Genres, die wir nicht auflisten

Weil das Internet riesig ist, nehmen wir in unsere Listen nicht auf:

- Blogs
- Blogbeiträge
- Artikel
- Websites (außer denen, die VIELE der von uns aufgelisteten Elemente hosten).
- Videos, die keine Kurse oder Screencasts sind.
- Buchkapitel
- Teaser-Beispiele aus Büchern
- IRC- oder Telegram-Kanäle
- Slacks oder Mailinglisten

Unsere Wettbewerbsprogrammierungslisten sind bei diesen Ausschlüssen nicht so streng. Der Umfang des Repos wird von der Community bestimmt. Wenn Sie eine Änderung oder Erweiterung des Umfangs vorschlagen möchten, verwenden Sie bitte ein Problem, um den Vorschlag zu machen.

##### Bücher vs. andere Sachen

Wir sind nicht so pingelig, was die Buchhaftigkeit angeht. Hier sind einige Attribute, die anzeigen, dass eine Ressource ein Buch ist:

- sie hat eine ISBN (International Standard Book Number)
- sie hat ein Inhaltsverzeichnis
- es wird eine herunterladbare Version angeboten, insbesondere ePub-Dateien.
- sie hat Ausgaben
- sie hängt nicht von interaktiven Inhalten oder Videos ab
- sie versucht, ein Thema umfassend abzudecken
- sie ist in sich geschlossen

Es gibt viele Bücher, die wir auflisten, die diese Attribute nicht haben; es kann vom Kontext abhängen.

##### Bücher vs. Kurse

Manchmal kann es schwierig sein, diese zu unterscheiden!

Kurse haben oft zugehörige Lehrbücher, die wir in unseren Bücherlisten auflisten würden. Kurse haben Vorlesungen, Übungen, Tests, Notizen oder andere didaktische Hilfsmittel. Eine einzelne Vorlesung oder ein Video allein ist kein Kurs. Eine PowerPoint-Präsentation ist kein Kurs.

##### Interaktive Tutorials vs. andere Sachen

Wenn Sie es ausdrucken und das Wesentliche behalten können, ist es kein interaktives Tutorial.

### Automatisierung

- Die Durchsetzung der Formatierungsregeln wird über [GitHub Actions](https://github.com/features/actions) mithilfe von [fpb-lint](https://github.com/vhf/free-programming-books-lint) automatisiert (siehe [`.github/workflows/fpb-lint.yml`](../.github/workflows/fpb-lint.yml))
- Die URL-Validierung verwendet [awesome_bot](https://github.com/dkhamsing/awesome_bot)
- Um die URL-Validierung auszulösen, pushen Sie ein Commit, das eine Commit-Nachricht mit `check_urls=file_to_check` enthält:

```properties
check_urls=free-programming-books.md free-programming-books-en.md
```

- Sie können mehr als eine zu prüfende Datei angeben, wobei Sie die einzelnen Einträge durch ein Leerzeichen trennen.
- Wenn Sie mehr als eine Datei angeben, basieren die Ergebnisse des Builds auf dem Ergebnis der zuletzt überprüften Datei. Sie sollten sich bewusst sein, dass Sie dadurch möglicherweise grüne Builds erhalten, die erfolgreich sind. Überprüfen Sie daher unbedingt das Build-Protokoll am Ende des Pull Request, indem Sie auf „Alle Prüfungen anzeigen“ -> „Details“ klicken.
