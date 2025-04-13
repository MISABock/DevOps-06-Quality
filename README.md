# DevOps 06 Quality

## Lernjournal


als erstes habe ich die Extension "HTMLHint" im Vs Code Installiert. 

In der Datei `index.html` wurde absichtlich ungültiges HTML eingefügt, um das Linting zu testen: (![lintFehler](images/lintFehler.png))

Dannach habe ich den Fehler korrigiert. (![lintFehlerlos](images/lintFehlerlos.png))


Hier sieht man wie ich den SeleniumTest erfolgreich bestanden habe:  (![lintFSeleniumTestSuccessehlerlos](images/SeleniumTestSuccess.png))


Desweiteren habe ich die Docker Container gestartet in dem ich das docker-compose gestartet habe und localhost 9000 im browser geöffnet. (![newProjectSonarQube](images/newProjectSonarQube.png))

als nächstest habe ich SonarQube-Scan mit Gradle gestartet, der korrekt durchgelaufen ist (![SonarQubeSuccessful](images/SonarQubeSuccessful.png)) 

Dabei scheint alles funktioniert zu haben (![runningOnSonar](images/runningOnSonar.png))

als letztes habe ich noch das gleiche fürd Frontend gemacht. siehe Bild: (![FrontendSonarQube](images/FrontendSonarQube.png))
