---
name: Aufgabe 1 Template
about: Das erste Issue, welches Aufgabe 1 abbildet.
title: Titel der Webseite hinzufügen
labels: good first issue
assignees: ''

---

#### Beschreibung
Wenn Besucher auf deine Website kommen, dann wissen sie im Moment nicht, worum es geht, da noch nichts auf der Website ist. Du solltest einen Titel hinzufügen, sodass die Besucher verstehen, um welchen Charakter es sich auf dieser Webseite handelt.

#### Dateien
Wenn du nicht weißt, wie man einen Titel erstellt, schau mal auf dieses Cheatsheet unter Header. Du sollst einen H1 Header verwenden.
https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf

#### Aufgaben
Führe folgende Schritte aus:
- [ ] Erstelle einen neuen Branch mit dem Namen ```feature1_new_title```. Dafür verwendest du den Befehl git branch feature1_new_title
- [ ] Wechsle auf den erstellten Branch mit dem Befehl ```git checkout feature1_new_title```
- [ ] Navigiere in der Git Bash zu deinem Repository. Das sollte durch den Befehl ```cd \<dein github name\>.github.io``` klappen.
- [ ] Nun wollen wir das Repository im Explorer (oder einem anderen Programm, welches Ordner anzeigen kann) öffnen. Navigiere dafür einfach zum Ordner, worin dein Repository geclont wurde. Als Hilfe kannst du auch unsere Shortcuts probieren: Dafür gibtst du in der Git Bash unter Windows den Befehl ```explorer.exe .``` ein. Unter Linux gibst du den Befehl ```nautilus ./``` ein. 
- [ ] Nun sollst du den Titel zu der Webseite hinzufügen. Öffne dafür die index.md Datei mit einem Editor. Lösche alles, was bereits in der Datei steht und nutze Github flavoured Markdown, um einen Titel zu der Website hinzuzufügen. Falls du nicht weißt wie, schau in das Cheatsheet.
- [ ] Nachdem du den Titel hinzugefügt hast, musst du die index.md Datei speichern. Füge dann in der Git Bash die Datei ```index.md``` der Staging Area hinzu. Das machst du mit dem Befehl ```git add index.md```. Anschließend musst du die Veränderungen commiten. Führe einen Commit mit dem Befehl ```git commit -m „Added Title“``` aus. Pushe dann die Veränderungen mit dem Befehl ```git push```. Dabei wird vielleicht ein Fehler auftreten, weshalb du eine Fehlermeldung siehst. Kopiere dann einfach den Befehl aus der Fehlermeldung und führe diesen aus.
- [ ] Erstelle auf Github einen Pull Request von deinem feature Branch in den Master Branch. Wähle dafür einen Titel, um in ein paar Worten auszusagen, was in diesem Pull Request geschehen ist. Im Textkörper des Pull Request beschreibst du das gelöste Problem. Was war das Problem? Wie hast du es gelöst? Welche betroffenen Dateien gibt es?
- [ ] Nun werden von uns geschriebene Tests deine Veränderungen prüfen. Sollten alle Tests (2 Stück) bestanden worden sein, dann kannst du deine Änderungen in den Master Branch mergen. Falls die Tests fehlschlagen, schaue in die Kommentare des Pull Requests, um herauszufinden woran es lag. Behebe die Fehler, sodass die Tests durchlaufen. Eine gute Idee ist es die Schritte des Issues erneut zu durchlaufen und zu schauen, ob alles richtig geschrieben ist. Außerdem kannst du dir die Index.md Datei auf Github anschauen und die richtige Formattierung überprüfen. Wenn du es für 15 Minuten ohne Erfolg nicht hingekriegt hast, kannst du in das Kursforum schauen.
- [ ] Lösche deinen Feature Branch. Wechsle in deiner Git Bash auf den master Branch und führe ```git pull``` aus, um dein Repository auf den neuesten Stand zu bringen. 
- [ ] Schließe dieses Issue. 
- [ ] Betrachte deine Webseite und schau, ob sich etwas verändert hat. Gegebenenfalls musst du ein paar Mal die Seite aktualisieren.
 
Solltest du Fragen haben, kannst du einen Blick ins Kurs Forum werfen.
