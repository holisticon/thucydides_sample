Thucydides - Oberflächentests mit Stil
=================
Wer kennt das nicht: Oberflächen-Tests werden in vielen Projekte stiefmütterlich behandelt. Wenn überhaupt automatisierte Oberflächen-Tests existieren sind diese meist schwer zu pflegen oder sind nicht wirklich stabil. Gerade vor dem Hintergrund von Continous Integration (CI) und Test Driven Development (TDD) eigentlich ein unhaltbarer Umstand. Gerade Oberflächen-Tests sind extrem wertvoll um kritischen Pfade abzutasten, z.B. als Smoke-Test vor einem Live-Deployment. Mit Thucydides ist es möglich Oberflächen-Tests lesbarer, wartbarer und wiederwendbar umzusetzen. Dabei wird das Page-Object-Pattern umgesetzt, um diesen Anforderung umzusetzen.

Link zum [Live-Beispiel](https://server.holisticon.de/jenkins/job/thucydides_sample/).

Link zur [Präsentation](http://holisticon.github.io/presentations/thucydides/).

Thucydides
* ist ein Tool für ATDD (acceptance test driven development)
* ermöglicht lesbare, wartbar und wiederwendbare Oberflächen-Tests 
* nutzt Selenium als technische Basis
* kann als Java und JBehave-Variante genutzt werden
* nutzt Page-Object-Pattern
    * Page als Model der Webseite mit allen Elemente. 
    * Steps als Gruppierung der möglichen Interaktionsmöglickeiten, z.B. Klicken
    * Test ist eine Kollektion von Tests die Benutzereingaben reflektieren und das Ergebnis verifizieren
* Stellt Reporting für Tracking & Fehlersuche zur Verfügung
* Wenn Report erstellt wurde, wird er unter target/site abgelegt
* Kann auch in Maven-Site eingebunden werden

![img](http://holisticon.github.io/presentations/thucydides/assets/thucydides_demo_7.png)

[![Build Status](https://server.holisticon.de/jenkins/buildStatus/icon?job=thucydides_sample)](https://server.holisticon.de/jenkins/job/thucydides_sample/)
