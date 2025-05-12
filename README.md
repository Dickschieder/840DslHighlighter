# Notepad++ Syntax Highlight für 840Dsl
Notepad++ ist ein Texteditor, der mich schon seit Jahren begleitet. Dabei gehen die Funktionen aber weit über die von Notepad hinaus. Eine Funktion, die ich in meinem beruflichen Alltag nicht mehr missen möchte, ist die Syntax Hervorhebung. Viele Sprachen sind bereits integriert, allerdings beschäftige ich mich überwiegend mit der Sinumerik und somit sind NC-Programme, Zyklen und Easyscreenbilder meine gewohntes Arbeitsumfeld. Notepad++ bietet aber die Möglichkeit sich eigene Syntaxhervorhebungen zu erstellen und zu nutzen.

Ich nutze in der Regel den dunklen Hintergrund von Dracula. Der ist frei verfügbar auf GitHub zu bekommen. Wie der eingebunden wird, beschreibe ich weiter unten.

Da ich immer mal wieder gefragt wurde, die Highlighting Funktion auch für das helle Design zu machen, stelle ich beide Varianten zur freien Verfügung. Wie die eingebunden wird, beschreibe ich auch im Anschluss. HGier zumindest schonmal die beiden Downloads:


Syntax Importieren

Das entsprechende Design importieren. Bei Design White ist hier Schluss. Bei Black wird noch zusätzlich das Design Dracula benötigt.
https://github.com/dracula/notepad-plus-plus

Design Dracula.xml auswählen und importieren


Einstellungen für Dracula entsprechend anpassen


Alternative zum Design laden
Die Datei Dracula.xml in das Verzeichnis:

%AppData%\Notepad++\themes

kopieren. Der Ordner „Themes“ muss in der Regel angelegt werden. Anschließend kann das Design ausgewählt werden.

Automatische Syntax Anwahl
Soll die Syntax automatisch umgeschaltet werden muss, die Dateiendung eingetragen werden

iso nc cnc spf mpf com arc def

