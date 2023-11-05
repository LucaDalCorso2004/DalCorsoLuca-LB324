# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.





 Man gibt in dem terminal "pre-commit install" und so wird pre-commit installirt.Danach muss man nur noch ein pre-commit-comfig.yaml file dort drin muss man auf den pytest verwiessen und auch die formatierungen  und schon geht es.Um es aber auf psuh zu testen mussman pre-commit install --hook-type pre-commit --hook-type pre-push installiren das es auch beim push anschaut.Zudem muss die stage im pre-commit-comfig.yaml von commit zu psuh geändert werden, so kann man eine pre-commit vor einem push  machen.Zu ausführung gibt man den Befhele "git add ." danach
 "git commit -m "message"" und dann "git push origin branchname". Wenn es ein Fehler hat wird der Commit nicht gepusht nur wenn er den pytest besteht.Wenn es nach dem commit ein Fehler gibt geben sie einfacher nochmals "git add ." und "git commit" ein dan sollte es funktioniren.



## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

1. Ich loge mich ein auf Azure.
2. Danach erstelle ich eine Web-App
3. Wenn Web-App erstellt ist gehe ich auf Deploment centre.
4. Source Github und auf mein Reposertory verweisen und save.
5. Automatisch wird ein yaml file zum starent des Server erstellt.
6. Danach auf configuration klicken.
7. Dort ein neues Applicaktion Setting machen.
8. Als Name nehmen sie PASSWORD genau so schreiben und Value das was in der env datei steht.
9. Das noch speichern und schon haben sie ihre PASSWORD auf ihrer Web-App

