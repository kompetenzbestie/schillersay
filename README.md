# schillersay

A simple zsh script that uses the [ImageMagick](https://imagemagick.org) command-line tools to make [Jochen Schiller](https://de.wikipedia.org/wiki/Jochen_Schiller) or [Margarita Esponda-Argüero](https://www.mi.fu-berlin.de/inf/groups/ag-pr/members/Professoren/Margarita_Esponda.html) say the big funny.

## Installation and Usage

Simply clone the repository into a directory of your choosing.
You may have to use `chmod +x schillersay` to make the script execute properly.

`schillersay` uses the syntax `$ ./schillersay <String> -f <Format> -o <Output File>`

All parameters must be specified and the string must be enclosed in quotation marks.

Currently available formats (examples below):

| ID | Image           |
|----|-----------------|
| 0  | Schiller Quote  |
| 1  | Schiller Speech |
| 2  | Esponda         |

## Examples

![SchillerQuoteGitHub.png](https://cdn.discordapp.com/attachments/742070822528745473/746312304664117258/SchillerGitHub.png)

`$ ./schillersay "All parameters must be specified and the string must be enclosed in quotation marks." -f 0 -o SchillerQuoteGitHub.png`

![SchillerSpeechGitHub.png](https://cdn.discordapp.com/attachments/742070822528745473/746445493919285268/SpeechGitHub.png)

`./schillersay "Ich studiere Mono-Bachler Informatik im 8ten Semester und habe den ertsen Teil dieser Veanstaltung letztes Semester belegt (Übungen + aktive Teilnahme). Das hat mir viel Zeit gekostet. Laut Studienordnung ist der Aufwand 300 Stunden. Klausurvorbereitung 30 -> 270, geteilt duch 2 -> 135 Stunden. Davon Anwesenheit in der Vorlesung 2 Stunden und im Tutorium 2 Stunden. Vorlesungzeit 14 Wochen oder 15 das weiß ich nicht geanu 135-56 = 79 Stunden, d.h. ungefär 6 Stunden Aufwand für Vor- und Nachbeabeitung und Übungsblätter. Is das realistisch. Aus meiner Erfahrung stimmte das für mich im letzten Semster gar nicht und dieses Semsetr scheint auch genauso zu sein. Es gibt auch einen Leernraum, was an sich ein tolles Angebot ist. Anscheinend gibt es trotz Vorlesung und Tutorium Bedarf oder auch die Studierenden sind interessiert tiefer zu gehen. Trotzdem kann man nicht davon ausgehen, dass wegen diesem extra Angebot, extra Leistung gebrach wird. Ich weiß auch nicht ob Programmieren zu lernen , Assembler und C, mit drin in den 6 Stundigen Aufwand. Es gibt ja dafür einen tollen C-Kurz unter Ressources. In der Vorlesung werden Kozepte vermittelt, die gut erkläret sind. In den Übungzettel werden Fragen gestellt die zu tief und zu delatiert sind im Vergleich zur Vorlesung. Ich recherchiere viel und versuche es, nachzuvollziehen aber ich verstehe auch oft nicht ganz genau, ich hab die Grundlage dafür nicht das alles kauen zu können und dann in eigenen Worter wiedergeben. Es sei dann, ich investiere mindesten 15 Stunden der Woche um ein 5 LP Modul bestehn zu können." -f 1 -o SpeechGitHub.png`

![EspondaGitHub.png](https://cdn.discordapp.com/attachments/742070822528745473/746445891774316564/EspondaGitHub.png)

`./schillersay "cannot execute binary file" -f 2 -o EspondaGitHub.png`
