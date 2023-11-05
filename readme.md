
# LB 324
## Lokal starten
1. pip install requriment.txt
2. flask run zum lokal starten.


## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.

 Man gibt in dem terminal "pre-commit install" und so wird pre-commit installirt.Danach muss man nur noch ein pre-commit-comfig.yaml file dort drin muss man auf den pytest verwiessen und auch die formatierungen  und schon geht es.Um es aber auf psuh zu testen mussman pre-commit install --hook-type pre-commit --hook-type pre-push installiren das es auch beim push anschaut.Zudem muss die stage im pre-commit-comfig.yaml von commit zu psuh geändert werden, so kann man eine pre-commit vor einem push  machen.Zu ausführung gibt man den Befhele "git add ." danach
 "git commit -m "message"" und dann "git push origin branchname". Wenn es ein Fehler hat wird der Commit nicht gepusht nur wenn er den pytest besteht.Wenn es nach dem commit ein Fehler gibt geben sie einfacher nochmals "git add ." und "git commit" ein dan sollte es funktioniren.



## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.

1. Ich loge mich ein auf Azure.
2. Danach erstelle ich eine Web-App
   ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/bc5fd6cc-37e4-490d-978f-7981379ab579)
   klicken sie auf create a rescource
   ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/86c9d9dc-f225-4b15-ba88-e078830b11f9)
   create Web-App klicken

   ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/cf0f4cd9-d3d0-4e5a-bfe3-5b5d7e1e36a3)
 
   ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/8a427e9a-1ea2-498c-8cc8-47a382db936d)

   Nach dem Ausfüllen auf Create klicken
   ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/285b0302-50b7-4e62-8195-a78323ca6f51)
4. Wenn Web-App erstellt ist gehe ich auf Deploment centre.
 
5. ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/5d93a747-ed25-4a9b-9111-e7fb229e4eb4)
6. Source Github und auf mein Reposertory verweisen und save.
7. Automatisch wird ein yaml file zum starent des Server erstellt und auch gleich automatisch startet wenn ein merge gemacht wurde.
8. ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/e5175789-f0ec-40f1-b2af-045f0dd86b04)
9. ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/f4078fc2-3c62-4801-bdc0-2cac34301d6f)
10. Danach auf configuration klicken.
11. Dort ein neues Applicaktion Setting machen.
    ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/85faa346-7832-4e55-a863-60d5a956a169)
12. Als Name nehmen sie PASSWORD genau so schreiben und Value das was in der env datei steht.
13. ![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/fd16cac2-b0e8-409a-9e6a-b3fae70a6303)

14. Das noch speichern und schon haben sie ihre PASSWORD auf ihrer Web-App
![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/c0efd4d2-1678-46e1-aff6-8dbfc4f849e9)
![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/657fb0a5-fe7c-40a1-82ef-b9491d3654da)

15 Hier noch der beweis das es auch automatisch startet wenn man mergte 
![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/64454e09-1b05-4657-af6f-6343b1da81ae)
![image](https://github.com/LucaDalCorso2004/DalCorsoLuca-LB324/assets/89087875/0d48aae7-0ff9-4158-bdaf-68cd0dfa0b91)





[weblink](https://lb324v3.azurewebsites.net/)
