# GiTeX

Willkommen zu `GiTeX`, einem kleinen Einführungsspiel zu `Git` und `LaTeX`.
In kleinen Gruppen soll hier kollaborativ ein LaTeX-Dokument erstellt werden.
Jede Gruppe erhält Teilaufgaben, die zu der Datei beitragen.

## Voraussetzungen

 1. Du hast einen GitHub-Account angelegt.
 1. Eine Git-Umgebung deiner Wahl läuft auf deinem Laptop. Egal ob auf der [Kommandozeile](https://git-scm.com/downloads) oder ein [GUI](https://git-scm.com/downloads/guis).
 1. Du hast eine [LaTeX-Distribution](https://www.latex-project.org/get/) inklusive Editor installiert, oder einen Accout bei einer LaTeX-Onlineplattform, wie [Overleaf](https://www.overleaf.com/).
 1. Idealerweise hast Du alles bereits einmal kurz getestet.

## Ein paar Spielregeln und Best Practices

* Ziel des Spiels: **Jeder** soll hinterher die Grundlagen von Git und LaTeX beherrschen.
* Ihr spielt in Zweierteams, mit je einer erfahrenen und einer lernenden Person.
* Profis: Hände weg von den Tastaturen! Greift eurem Lehrling unter die Arme und helft ihm durch die Schritte, wenn es Probleme gibt. Erklärt, warum wie was funktioniert.
* Nicht schummeln! Googlen ist natürlich erlaubt.
* Sicherlich gibt es die eine oder andere Abkürzung, aber Sportler werden auch nicht besser, indem sie Trainingseinheiten schwänzen. ;)
* Bei LaTeX-Dokumenten generell, in Verbindung mit Git sogar im Speziellen sinnvoll: Jeder Satz kommt in eine neue Zeile. Ungewohnt, erspart aber viel Ärger!

## Aufgaben

Spielregeln und Best Practices gelesen? Los gehts:

1. Wechselt auf den Branch, der euren Themen-Namen trägt.
1. Hier findet ihr ein konkretes Thema, über das ihr ein Dokument erstellen sollt.
1. Erstellt von dem aktuellen Branch aus einen neuen Branch nach dem Schema „thema_a_2“, wenn ihr Thema A, Gruppe 2 seid.
1. Auf diesem Branch arbeitet ihr nun in den nächsten Schritten. Hier findet ihr auch die Informationen, wie ihr euer Dokument befüllen sollt. Sobald ihr das durchgearbeitet habt, geht es hier weiter!
1. Fertig? Eröffnet auf GitHub einen Pull Request. Das ist eine Anfrage, die Änderungen von eurem Branch in einen anderen Branch zu übernehmen. In diesem Fall möchtet ihr euren Entwurf zurück in den Branch eures Themas bringen. Also z.B. von „thema_a_2“ in „thema_a“. Sobald ihr den PR eröffnet habt, geht die Review-Runde los:
1. Ihr bekommt einen anderen PR zugeordnet. Hier seid ihr nun Reviewer. Schaut euch die Änderungen der anderen Gruppe an und achtet vor allem auf die Anforderungen an die LaTeX-Dokumente aus Schritt 6. Auch solltet ihr den entsprechenden Branch einmal lokal laden und prüfen, ob daraus eine fehlerfreie PDF-Datei erstellt werden kann.
1. Je nachdem, ob alles in Ordnung ist könnt ihr dem PR zustimmen („approve“), oder per Kommentar Änderungen vorschlagen. Bitte keine PRs selbst mergen!
1. Nun solltet ihr selbst mal in euren PR reinschauen. Ist alles in Ordnung, oder solltet ihr an der einen oder anderen Stelle noch nachbessern? Dann ist jetzt die Gelegenheit dafür 😊. Am Ende sollte euer PR von einem der Reviewer akzeptiert sein.
1. Nun könnt ihr auf den großen grünen „Merge pull request“-Button drücken!

 > Hilfe! Mein Button ist rot! Dann war wohl die andere Gruppe eures Themas etwas schneller. Das heißt: Git hat nun versucht eure Änderungen an der main.tex Datei mit denen der anderen Gruppe zusammenzuführen („zu mergen“). Das hat aber leider nicht geklappt, da ihr teilweise die gleichen Zeilen bearbeitet habt. Nun müsst ihr euch mit dem anderen Team eures Themas zusammensetzen. Ihr könnt die Konflikte zusammen direkt in GitHub über den Button „resolve conflicts“ lösen, oder aber lokal die Änderungen zusammenführen. Die Anleitung dazu liefert GitHub direkt neben dem roten Button.

10. In jedem Falle ist nun das Ziel, den Button wieder grün zu bekommen, also alle Konflikte zu lösen. Vor dem Mergen solltet ihr auch noch mal testen, ob das Dokument überhaupt noch richtig von LaTeX verarbeitet werden kann!
1. Schlussendlich könnt ihr den Button drücken und in eurem Themen-Branch sollte nun eine vollständige und funktionierende main.tex Datei mit den Inhalten beider Teams liegen.
1. Der letzte Schritt: Committet die PDF-Datei, die aus der jetzigen main.tex Datei entsteht auf den „base“ Branch.
1. Fertig! Nun kennst Du die Grundlagen von Git und LaTeX 😊 (und nebenbei haben wir nun drei informative Dokumente).
