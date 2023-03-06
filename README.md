# SWEN_MTCG
SWEN Repo for MTCG Project

Monster Trading Card Game - Protokoll:
Marcel Sziener

Anmerkungen:
Trading eventuell nicht ganz funktional.
In seltenen Fällen wird kein Battle ausgegeben. Warum genau, weiß ich leider nicht.
Das Battlelog ist leider nicht gerade sonderlich "clean"...

1. Design:

Das Projekt wurde in C# und in der IDE Visual Studio 2022 geschrieben. Als Datenbank dient eine PostgreSQL Database, welche mit PgAdmin4 aufgesetzt wurde.
Für das Testing wurden einige benötigte NuGet Pakete installiert. Darunter fallen NUnit, NUnit3TestAdapter, Microsoft.NET.Test.Sdk und coverlet.collector.
Npgsql wird ebenso für die Verbindung und Verarbeitung von Querys mit der Datenbank benötigt.
Es wurden auch einige Interfaces eingebaut die vielleicht gar nicht hätten sein müssen.

2. Gelernte Lektionen:

NEVER EVER werde ich jemals wieder ein Projekt anfangen, ohne es mit GitHub oder Gitlab zu verbinden UND REGELMÄßIG zu pushen!!!
Durch diesen Fehler habe ich einen großen Teil meines Codes verloren, welcher einige Zeit in Anspruch nahm um diesen wiederherzustellen...

Datenbanken am Besten wenn möglich in der IDE verwalten. Das ermöglicht einen besseren und schnelleren Einblick in die Datenbank Ebene.
In PgAdmin ist es zwar auch möglich, aber deutlich umständlicher (+ ich hab einige GUI Bugs entdeckt, welche das Bearbeiten der Datenbank ohne SQL-Queries deutlich lästiger gestalten lassen.)
Außerdem fiel es mir schwer die Datenbanken anzulegen, weil ich Angst davor hatte einen Fehler in der Erstellung zu machen und folglich alles neu erstellen zu müssen.

Unit-Tests am Besten am Anfang schreiben:
Mir fiel es später leichter Funktionen zu schreiben zu denen der Test schon geschrieben wurde. Viele Tests wurden erst im Nachhinein geschrieben. Das wird zukünftig nicht mehr so geschrieben.

3. Zeitaufwand:

Ich habe eindeutig VIEL zu Lange daran gearbeitet: 
Durch mentale Barrieren und der Tatsache dass es hier keinen direkten Userinput gibt, sondern alles von einer Curl eingegeben wird 
(Für mich neue Art der Datenverarbeitung) habe ich deutlich mehr Zeit gebraucht als es wahrscheinlich hätte sein müssen. 
ca. 230 Stunden
