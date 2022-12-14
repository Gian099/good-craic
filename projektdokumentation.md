# Projekt-Dokumentation

Gian-Marco Mileti

| Datum | Version | Zusammenfassung                                              |
| ----  | -----   | --------- 
| 24.08 | 0.0.1   | Angefangen mit Projekt                                       |
| 01.09 | 0.0.2   | Basis des Spiels steht                                       |
| 08.09 | 0.0.3   | Programm zählt jetzt Versuche                                |
| 15.09 | 0.0.4   | Programm erkennt jetzt Fehler                                |
| 15.09 | 0.0.5   | Programm ändert jetzt die Farbe des Texts (falsch oder richtig geraten)|
| 22.09 | 1.0.0   | Prgramm ist fertig                                           |

## 1 Informieren

### 1.1 Ihr Projekt

Ich bin gerade dabei, ein "Random Number guessing game" zu programmieren.

### 1.2 User Stories

| US-№ | Verbindlichkeit |  Typ        | Beschreibung  |  
| ---- | -----           | ---------   | ------------- |
| 1    |    muss         |  Funktional | Als Spieler möchte ich, dass der Spieler eine Zufallszahl zwischen 1 und 100 raten kann, damit die Auswahl nicht allzu gross ist.|
| 2    |    muss         |  Funktional | Als Spieler möchte ich eine Anzeige dafür, ob die Zahl höher oder kleiner ist, damit ich die Zahl schnellere rate. |
| 3    |    muss         |  Funktional | Als Spieler möchte ich wissen, wann die Geheimzahl erraten wurde, damit ich weiss, wann ich eine neue Zahl raten muss. |
| 4    |    muss         |  Funktional | Als Spieler möchte ich wissen, wie viele Versuche ich gebraucht habe, damit ich weiss, wie gut ich geraten habe. |
| 5    |    muss         |  Funktional | Als Spieler möchte ich, dass das Programm mit Fehlereingaben umgehen kann, damit das Spiel richtig läuft.|
| 6    |    kann         |  Qualität   | Als Spieler möchte ich, dass das Programm eine Hintergrund-Farbe (Grün (richtig) oder Rot (falsch)) passend auf die
Genauigkeit, auf die ich geraten habe, anpasst, damit ich als Spieler weiss, eine besser Visualisierung habe.|
| 7    |    kann         |  Qualität   | Als Spieler möchte ich, dass das Programm einen Timer ausgibt, damit ich weiss, wie lange ich als Spieler gebraucht habe.
| 8    |    kann         |  Qualität   | Als Spieler möchte ich, dass das Programm einen Titel hat, damit ich sofort sehe, um was für ein Programm es sich handelt.
| 9    |    kann         |  Qualität   | Als Spieler möchte ich, dass das Programm eine Wiederholfunktion hat, damit ich das Programm nicht immer neu starten muss, wenn ich noch einmal spielen will.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | --------| ----------------- |
| 1.1  | Geheimzahl testen zwischen 1 und 1000 | 5 | das ist eine Geheimzahl |
| 2.1  | random zahl erraten | 76 | richtig oder falsch |
| 3.1  | geratene Zahl ist falsch | 45 | Programm gibt an, ob Zahl richtig oder falsch ist
| 4.1  | Beim 3ten mal erraten | 7,10,11 | Programm gibt Versuche an
| 5.1  | Spieler gibt Buchstabe ein | b | Programm sagt: gib eine Zahl ein
| 6.1  | Spieler gibt die richtige Zahl ein | 187 | Programm gibt grüne Farbe aus |
| 7.1  | Spieler spielt das, Spiel| richtige Zahl wurde geraten| Programm zeigt Zeit an|
| 8.1  | Visual Studio ist offen|Programm startet|Titel wird angezeigt|
| 9.1  | Programm ist gestartet|Spieler ist fertig| Wiederholfunktion wird angezeigt|

### 1.4 Diagramme

![image](https://user-images.githubusercontent.com/111044245/191704121-cc60c655-d770-410f-b101-59a9d181fdd4.png)

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | -------------| --------------|
| 1.A  | bis 01.09| Gian-Marco| speichert Zufallszahl zwischen 1 und 1000| 45min |
| 2.A  | bis 01.09| Gian-Marco| Anzeige ob Zahl höher oder kleiner ist| 60min|
| 3.A  | bis 01.09| Gian-Marco| Anzeige, wenn Zahl richtig geraten wurde|   45min    |
| 4.A  | bis 08.09| Gian-Marco| Anzeige für wie viele Versuche der Spieler gebraucht hat |  50min      |
| 5.A  | bis 15.09| Gian-Marco| Programm muss Fehler umgehen |  3x 45min |
| 6.A  | bis 15.09| Gian-Marco| Als Spieler möchte ich, dass das Programm eine Hintergrund-Farbe (Grün (richtig) oder Rot (falsch)) passend auf wie ich geraten habe anpasst.| 45min |
| 7.A  | bis 15.09| Gian-Marco| Programm zeigt Timer an| 45min |
| 8.A  | bis 15.09| Gian-Marco| Programm hat Titel | 30min|
| 9.A  | bis 15.09| Gian-Marco| Programm zeigt Wiederholfunktion an| 60min |
Total: 

## 3 Entscheiden

Ich habe mich entscheiden, alle User-Stories, ausser den Timer, umzusetzen.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.1  | 01.09 | Gian-Marco|    45min      |      15min        |
| 2.1  | 01.09 | Gian-Marco|    60min      |      45min        |
| 3.1  | 01.09 | Gian-Marco|    45min      |      30min        |
| 4.1  | 08.09 | Gian-Marco|    50min      |      45min        |
| 5.1  | 15.09 | Gian-Marco|    3x45min    |      45min        |
| 6.1  | 15.09 | Gian-Marco|    45min      |      60min        |
| 7.1  | /     | /         |    /          |      /            |
| 8.1  | 15.09 | Gian-Marco|    30min      |      15min        |
| 9.1  | 15.09 | Gian-Marco|    60min      |      90min        |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |01.09|funktioniert|Gian-Marco|
| 2.1  |01.09|funktioniert|Gian-Marco|
| 3.1  |01.09|funktioniert|Gian-Marco|
| 4.1  |08.09|funktioniert|Gian-Marco|
| 5.1  |15.09|funktioniert|Gian-Marco|
| 6.1  |15.09|funktioniert|Gian-Marco|
| 7.1  |  /  |     /      |    /     |
| 8.1  |15.09|funktioniert|Gian-Marco|
| 9.1  |15.09|funktioniert|Gian-Marco|

Ich konnte alles, ausser den Timer gut ausführen.

## 6 Auswerten

https://github.com/Gian099/good-craic/blob/main/Lernbericht%20Gian-Marco%20LA1100.md
