# TBZ_Modul_146
**Gruppe: Sharon, Luca, Eric**

<h1>Internetservices</h1>

<h2>Ausgangslage/Ist-Situation</h2>

Ein Unternehmen hat einen veralteten Internetzugang mit einer Übertragungsrate von 50 Mbit/s im Download und 5 Mbit/s im Upload mit ADSL. Die Firma produziert Kaffeemaschinen in einer städtischen Gegend in der Schweiz. Das Marketing benutzt moderne Webapplikationen mit viel Multimediaanwendungen und ein Shop für Endkunden ist ebenfalls vorhanden. Alle Mitarbei-tenden benutzen Mail und Browserapplikationen. Die Firma hat 90 Internetnutzer.
Eine Firewall ist nicht vorhanden und die Server stehen alle beim Provider.


<h3>Aufgabenstellung:</h3> <br>

Vergleichen sie folgenden Möglichkeiten die Internetservices zu betreiben: 

- eigene Server „inhouse“ 
- dedizierte Server (Root-Server) bei Provider 
- Services beim Provider (Shared hosting) 

Nehmen Sie dafür für 2 Fälle einige Eckdaten an (z.B. Speicherplatz, Traffic, Dienste, …). 
Erstens eine einfache Webpräsenz zu Werbezwecken und Mail, zweitens eine komplexe 
Datenbankanwendung mit PHP für den Kundenzugriff.  

Welche Vergleichskriterien finden Sie, welche sind wie wichtig? 

Konstruieren Sie „typische Fälle“ und vergleichen Sie.

---


<h3>Einfache Webpräsenz und Mail:</h3>
Wenn man davon ausgeht das diese Firma eine Start Up ist (rund 10 Mitarbeiter), mit wenig Speicherplatz und wegen den 10 Mitarbeiter nur sehr begrenzter Traffic verfügt. Da durch die einfache Webpräsenz auch nicht viele Dienste gebraucht werden, würden wir folgendes empfehlen:

Ein Shared Hosting, weil es Nutzer ermöglicht, sich so vollkommen auf die Ziele ihres Webprojekts zu konzentrieren. Darüber hinaus kommen viele Shared-Hosting-Anbieter ihren Kunden mit übersichtlichen Konfigurationstools entgegen. Ein weiteres Plus ist es, das die kosten hier am niedrigsten sind. Als Nachteil des Shared Hosting geht zwangsläufig mit einer eingeschränkten Hardware-Nutzung einher. Da sämtliche Server-Ressourcen unter allen gehosteten Websites aufgeteilt werden, steht den Nutzern dieses Hosting-Modells nur ein Teil der gesamten Serverleistung zur Verfügung.

Einen eigenen Server (inhouse), wäre nicht zu empfehlen, da der Kosten/Aufwand viel zu hoch wäre und man einen erfahrenen Spezialisten vor Ort braucht, um die Server und Leitungen zu betreiben.

Generell könnte man einen Root-Server in Betracht ziehen, da man dabei einen eigenen Server zu Verfügung bekommt und er nicht „geteilt“ wird. Der einzige Nachteil hier ist der Kostenpunkt, da der Server beim Provider steht und er auch zusätzliche Leitung wie Überwachung und Hardwarebetreuung. Jedoch werden hier nicht, wie beim Shared Hosting die Kosten allein Übernehmen.

Im Fazit, wenn es das Budget des Kunden zulässt, würden wir eher zu einem Root Server tendieren, da man dort einfach mehr Optionen hat. Hat der Kunde jedoch ein eher Begrenztes Budget, würde sich das Shared Hosting im Preis/Leitungsvergleich mehr lohnen.

---

<h3>Komplexe Datenbankanwendung:</h3>
Hier gehen wir davon aus das, die Firma mit rund 100 Mitarbeiter 24/7 auf die Server zugreifen müssen. Die komplexe PHP-Datenbankanwendung beansprucht viel Speicherplatz. Die Firma ist seit Längerem in der Hotel-Branche und verfügt über mehrere Standorte, dazu sind sie bereit mehr Geld für (Ausfall)Sicherheit auszugeben.

Mit einem Shared Hosting würde der Kunde hier wahrscheinlich nicht zufrieden sein, weil die Hardwarenutzung hier beschränkt wird. Zudem sind des Zugriffes und Verwaltungsoptionen beschränkt, was in unserem Fall gar nicht gut wäre.

Hier könnte man einen eigenen Server in Betracht ziehen, wenn es die Räumlichkeiten erlauben. Nachteil hier ist das der Kunde jegliche Kosten unmittelbar tragen muss und man ein gutes Monitoring, zum Aufzeichnen der Ausfälle, bereitstellen. Zudem ist es auch immer eine Frage von Sicherheit, ob man wirklich den Server bei sich vor Ort haben möchte.

Am meisten empfehlen wir hier das man sich auf einen Root Server einigt. Den dadurch liegen alles an Hardware, Service und Überwachung beim Provider. Zusätzlich ist man hier abgesichert da man einen Vertrag aushandelt der z.B. bis 1h Ausfallzeit toleriert. Dazu wird hier auch eine höhere Sicherheit gewährleistet da nur bestimmte Personen zutritt zu einem Rechenzentrum haben.

Im Fazit würden wir für diesen Kunden ein dedizierter Server empfehlen. Da der Ihre Anforderungen am meisten erfüllt und die höchste Ausfall Sicherheit gewährleiten kann.

Jedoch könnte man hier auch ein Inhouse Server In Betracht ziehen, wenn man ein gutes Sicherheitskonzept ausarbeitet und man einen Techniker vor Ort mit einem guten Management System arrangieren kann.

<h3>Welche Vergleichskriterien finden Sie, welche sind wie wichtig?</h3>

Der Traffic             - eher wichtiger <br>
Die Arbeitszeiten       - zu beachten<br>
Speicherplatz           - nicht so wichtig<br>
Kosten                  - zu beachten<br>
Ausfall-Sicherheit:     - sehr wichtig<br>