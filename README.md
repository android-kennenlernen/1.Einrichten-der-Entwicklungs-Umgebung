### 1. Für wen ist diese Projekt-Seite geeignet?

Für jeden, der über gefestigte Kenntnisse in JAVA verfügt.  
D.h., man sollte schon JAVA-Quelltexte verstehen und zielgerichtet ändern können.  
Ein Erfahrungsschatz, wenn auch in einer anderen Sprache, betreffs
- Sql-Datenbanken-Anbindung
- Internet-Kommunikation

erleichtert das Verständnis der Beispiel-Projekte.

### 2. Was ist die Absicht dieser Projekt-Seite?

Anhand von einfachen Beispiel-Apps soll der Einstieg in die Android-Programmierung erleichtert werden.  
Dies umfasst
- wie ist eine Android-App grundsätzlich aufgebaut
- wie interagiert man mit den Steuer-Elementen(Auslesen, Beschreiben, auf Touch/Click reagieren)
- wie wechselt man zwischen verschiedene Screens(Activity's) innerhalb einer App
- wie speichert man Daten lokal in einer einfachen Datei
- wie speichert man Daten lokal per SQL

Die Einfachheit der Apps schliesst jegliche Paradigmen wie 'separation of concerns', 'inversion of control' usw. aus.  
Nicht, daß wir dies nicht können, sondern weil dadurch nur der Blick auf das Eigentliche, Unbekannte, Neue schlichtweg getrübt würde.

Zudem ist jede App __genau__ einem Thema gewidmet.

Derzeitige Themen sind
- also das Einrichten einer Entwicklungs-Umgebung
- Kennenlernen der Zustände, welche ein App in ihrem Lebenszyklus einnehmen kann
- Beleben einer Nutzer-Oberfläche mit Steuerelementen
- Einbinden dieser Steuerelemente in den Programm-Code
- Internationalisierung der Anwendung
- restliches wird nach Fertigstellung hier fortgeschrieben.

Mag sein, daß diese Vorgehensweise dem einen oder dem anderen zu feingranular erscheint.
Nur, packt man alles eine Mega-App, denke ich, verschwimmen die einzelnen Konzepte, welche in einer App zum Tragen kommen.

Anmerken möchte ich noch, daß die Beispiel-Apps natürlich nicht die eigene mehr oder minder tiefgreifende Literatur-Recherche zum Thema Android-Programmierung ersetzen können.

### 3. Wie lade ich mir die Beispiel-Apps herunter?

Diese Projekt-Seite ist in _erster Linie_ für Windows-Nutzer gedacht.  
Ladet Euch einfach die zip-Datei des jeweiligen Projektes herunter und entpackt diese!  
Dazu ist auf der  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;jeweiligen Github-Projekt-Seite  
der Schalter  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;'Download ZIP'  
zu betätigen.  
Diesen findet Ihr auf der rechten Seite ganz unten!!!  

### Anmerkung für die 'git'-Nutzer unter Euch ###

Damit das jeweilige zip-Archiv für Windows-Nutzer keine Probleme herauf beschwört, habe ich in meiner  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;.git/config  
folgendes Attribut gesetzt :

    [core]
        autocrlf = false  

Hintergrund ist einfach der, sich nach den Windows-Leuten zu richten und __deren__ 'eol conventions' einzuhalten. Sorry.  

Also, viel Erfolg und Spaß bei allem!  

Los geht's nun mit [1.1 Beschaffen der Entwicklungs-Umgebung](https://github.com/android-kennenlernen/1.Einrichten-der-Entwicklungs-Umgebung/blob/master/1.1 Beschaffen%20der%20Entwicklungs-Umgebung.md)

__PS:__  
In loser Folge werden zunächst an _dieser_ Stelle weiterführende Android-bezogene Websites benannt:  

- [CS 282: Principles of Operating Systems II: Systems Programming for Android](http://www.dre.vanderbilt.edu/~schmidt/cs282/index.html)
- [Pattern-Oriented Software Architectures for Concurrent and Networked Mobile Devices and Clouds](https://www.coursera.org/course/posa)



