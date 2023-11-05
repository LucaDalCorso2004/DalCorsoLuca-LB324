# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.


 Man gibt in dem terminal "pre-commit install" und so wird pre-commit installirt.Danach muss man nur noch ein pre-commit-comfig.yaml file dort drin muss man auf den pytest verwiessen und auch die formatierungen  und schon geht es.Um es aber auf psuh zu testen mussman pre-commit install --hook-type pre-commit --hook-type pre-push installiren das es auch beim push anschaut.Zudem muss die stage im pre-commit-comfig.yaml von commit zu psuh geändert werden, so kann man eine pre-commit vor einem push  machen.Zu ausführung gibt man den Befhele "git add ." danach
 "git commit -m "message"" und dann "git push origin branchname". Wenn es ein Fehler hat wird der Commit nicht gepusht nur wenn er den pytest besteht.

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
