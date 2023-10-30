# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.
 

 Man gibt in dem terminal "pre-commit install" und so wird pre-commit installirt.Danach muss man nur noch ein pre-commit-comfig.yaml file einbauen. dor verweisst man das man die precommits erste beim push regarien soll. Un d das diese Funktioniern muss man die pytst in diesem File verwiessen. So kann ein der pre-commit nur Funktioniren, wenn py-test bestanden sind. Wenn man dann den befehle git commit -m [message] und es eine Fehler bei den py-test hat wird der commit nicht aus geführt. das gleich passiert wenn man git push origin main macht.

## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
