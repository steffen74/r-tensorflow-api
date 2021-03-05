# Erhebungs-Events

## Projekt

`StartProject` Der Benutzer startet das Projekt/die Erhebung.

`EndProject` Das Projekt wird durch Beenden des letzten Projektelements beendet.

`ResumeProject` Das Projekt wird wiederaufgenommen.

`StartScenario` Der Benutzer startet ein Szenario.

`EndScenario` Der Benutzer beendet ein Szenario.

`ResumeScenario` Der Benutzer nimmt ein Szenario wieder auf.

`StartTutorial` Analog zu StartScenario.

`EndTutorial` Analog zu EndScenario.

`ResumeTutorial` Analog zu ResumeScenario.

`StartIntro` Analog zu StartScenario.

`EndIntro` Analog zu EndScenario.

`ResumeIntro` Analog zu ResumeScenario.

`StartQuestionnaire` Analog zu StartScenario.

`EndQuestionnaire` Analog zu EndScenario.

`ResumeQuestionnaire` Analog zu ResumeScenario.

## Szenario

`OpenTool` Ein Tool wird per Klick auf das entsprechende Icon in der Taskleiste geöffnet oder per Klick auf das
jeweilige "Fenster" in den Vordergrund geholt (nur möglich, wenn ein nicht bildschirmfüllendes Tool im Vordergrund und
ein bildschirmfüllendes Tool im Hintergrund geöffnet ist).

`CloseTool` Der Benutzer schließt das Tool.

`MinimizeTool` Der Benutzer minimiert das Tool.

`RestoreTool` Der Benutzer stellt ein minimiertes Tool wieder her.

`CopyToClipboard` Der Benutzer hat etwas in die Zwischenablage kopiert.

`PasteFromClipboard` Der Benutzer hat etwas aus der Zwischenablage eingefügt.

`StartEvent` Ein Fragebogen-Ereignis wird aktiviert.

`EndEvent` Ein Fragebogen-Ereignis wird beendet.

`ResumeEvent` Ein Fragebogen-Ereignis wird wiederaufgenommen.

## Fragebogen

`SelectQuestionnaireAnswer` Der Benutzer wählt eine Antwort aus.

`DeselectQuestionnaireAnswer` Der Benutzer wählt eine Antwort ab.

`UpdateQuestionnaireFreeTextAnswer` Der Benutzer ändert den Antworttext einer Freitextfrage. Dieses Event wird auch für
die "Sonstiges"-Option bei geschlossenen Items (Multiple-Choice oder Single-Choice) verwendet.

`EnlargeQuestionnaireImage` Der Benutzer vergrößert das Bild eines Fragebogens.

`ShrinkQuestionnaireImage` Der Benutzer verkleinert das Bild eines Fragebogens wieder.

`PlayQuestionnaireVideo` Der Benutzer spielt das Video eines Fragebogens ab.

`PauseQuestionnaireVideo` Der Benutzer pausiert das Video eines Fragebogens.

`EnterFullscreenQuestionnaireVideo` Der Benutzer aktiviert den Vollbildmodus des Video-Players eines Fragebogens.

`LeaveFullscreenQuestionnaireVideo` Der Benutzer deaktiviert den Vollbildmodus des Video-Players eines Fragebogens.

`QuestionnaireVideoPlaybackEnded` Das Video eines Fragebogens wurde vollständig abgespielt. Hierbei wird allerdings
nicht sichergestellt, dass der Benutzer nicht Teile des Videos übersprungen hat.

`EnlargeQuestionnaireQuestionImage` Analog zu EnlargeQuestionnaireQuestionImage.

`ShrinkQuestionnaireQuestionImage` Analog zu ShrinkQuestionnaireQuestionImage.

`PlayQuestionnaireQuestionVideo` Analog zu PlayQuestionnaireQuestionVideo.

`PauseQuestionnaireQuestionVideo` Analog zu PauseQuestionnaireQuestionVideo.

`EnterFullscreenQuestionnaireQuestionVideo` Analog zu EnterFullscreenQuestionnaireQuestionVideo.

`LeaveFullscreenQuestionnaireQuestionVideo` Analog zu LeaveFullscreenQuestionnaireQuestionVideo.

`QuestionnaireQuestionVideoPlaybackEnded` Analog zu QuestionnaireQuestionVideoPlaybackEnded.

## Tools

### E-Mail-Client

`CreateEmail` Der Benutzer legt eine neue E-Mail an.

`ShowEmail` Der Benutzer öffnet eine E-Mail, dabei wird nicht unterschieden, ob es sich um einen Draft handelt oder
nicht.

`DeleteEmailDraft` Der Benutzer löscht einen Entwurf. Dieser wird komplett gelöscht.

`MoveEmailToTrash` Der Benutzer löscht eine E-Mail. Diese wird in den Papierkorb verschoben. Von dort aus kann nicht
mehr gelöscht werden.

`SendEmail` Der Benutzer schickt eine E-Mail ab.

`SelectEmailDirectory` Der Benutzer wählt einen Ordner aus.

`SearchEmails` Der Benutzer durchsucht die E-Mails.

`UpdateEmail` Änderungen der Metadaten einer E-Mail (Empfänger, Betreff etc.). Änderungen sollen nicht zeichenweise
erfasst werden, sondern bei Fokusverlust oder nach einer bestimmten Zeitspanne.

`UpdateEmailText` Bei jeder Änderung des Texts einer E-Mail wird der vollständige neue Text erfasst. Eine Änderung kann
normales Tippen eines Zeichens oder aber auch z. B. das Einfügen eines ganzen Worts sein.

### Taschenrechner

`CalculatorKeyPressed` Der Benutzer hat eine Taste gedrückt.

### Dateibrowser

`ViewDirectory` Ein Ordner wird ausgewählt, die Detail-Ansicht öffnet sich

`ViewFile` Eine Datei wird ausgewählt, die Detail-Ansicht öffnet sich

### Nachschlagewerke

`ViewReferenceBookChapter` Ein Kapitel wird ausgewählt, die Detail-Ansicht öffnet sich

`ViewReferenceBookArticle` Ein Artikel wird ausgewählt, die Detail-Ansicht öffnet sich

`SearchReferenceBook` Der Benutzer durchsucht das Nachschlagewerk

### Video-Player

`PlayVideo` Das Video wird gestartet

`PauseVideo` Das Video wird pausiert

### Spreadsheet

`UpdateSpreadsheetCellValue` Der Benutzer ändert den Inhalt einer Zelle.

`UpdateSpreadsheetCellType` Der Benutzer ändert den Typ (das Format) einer Zelle.

`SelectSpreadsheetCell` Der Benutzer wählt eine Zelle aus.

`AddSpreadsheetColumn` Der Benutzer fügt eine Spalte ein.

`AddSpreadsheetRow` Der Benutzer fügt eine Zeile ein.

`RemoveSpreadsheetColumn` Der Benutzer löscht eine Spalte.

`RemoveSpreadsheetRow` Der Benutzer lösche eine Zeile.

`SelectSpreadsheetCellRange` Der Benutzer wählt mehrere Zellen aus.
