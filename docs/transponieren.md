[1. Horizontalisierung](#horizontalisierung)  
[2. Vertikalisierung](#vertikalisierung)

## Horizontalisierung
### Ausgangslage
![image](https://user-images.githubusercontent.com/42339363/98912170-015e1680-24c6-11eb-918e-a2041e28d89d.png)

### Ziel  
![image](https://user-images.githubusercontent.com/42339363/98912375-4f731a00-24c6-11eb-89ee-ec834e3e4106.png)

### Lösungsweg SAS Enterprise Guide  
1. Anwendungsroutine "Transponieren" auswählen.  
 
![image](https://user-images.githubusercontent.com/42339363/98913315-7e3dc000-24c7-11eb-8fba-1b8e100a0e06.png)  

2. Die Variablen den richtigen Rollen zuordnen:
* `Variable transponieren`: Hier muss die Analysevariable ausgewählt werden, deren Werte auf verschiedene Spalten aufgeteilt werden soll. In diesem Beispiel also _Wert_.  
* `Neue Spaltennamen (Maximal: 1)`: Hier wird die Variable ausgewählt, deren Ausprägungen die neuen Variablen bilden bzw. benennen sollen. In diesem Beispiel also _Merkmal_.
* `Analyse gruppieren nach`: In diesem Beispiel die Variablen _Name_ und _Geschlecht_. Hier können auch noch mehr Variablen gewählt werden, z.B. wenn der Wert nicht nur nach Name und Geschlecht, sondern z.B. auch noch nach Nationalität ausgewiesen würde.

![image](https://user-images.githubusercontent.com/42339363/98917395-99f79500-24cc-11eb-9cba-9cd36e46ae57.png) 
  
3. Das Häkchen bei "Präfix verwenden" rausnehmen, damit die neuen Spaltennamen nicht mit dem Wort "Spalte" (Default) ergänzt werden.

![image](https://user-images.githubusercontent.com/42339363/98912893-fb1c6a00-24c6-11eb-9fd4-e042648ac9f5.png)


## Vertikalisierung
### Ausgangslage 
![image](https://user-images.githubusercontent.com/42339363/98918378-d677c080-24cd-11eb-9a9e-5ae481d24e42.png)


### Ziel   
![image](https://user-images.githubusercontent.com/42339363/98920490-746c8a80-24d0-11eb-9cd9-d99a2817ec4c.png)

### Lösungsweg SAS Enterprise Guide  
1. Anwendungsroutine "Transponieren" auswählen.  
 
![image](https://user-images.githubusercontent.com/42339363/98913315-7e3dc000-24c7-11eb-8fba-1b8e100a0e06.png)  

2. Die Variablen den richtigen Rollen zuordnen: 
* `Variable transponieren`: Hier müssen die Analysevariablen ausgewählt werden, deren Werte in einer Spalte zusammengefasst werden sollen. In diesem Beispiel also _Alter_, _Grösse_ und _Gewicht_.  
* `Analyse gruppieren nach`: In diesem Beispiel die Variablen _Name_ und _Geschlecht_. Hier können auch noch mehr Variablen gewählt werden, z.B. wenn der Wert nicht nur nach Name und Geschlecht, sondern z.B. auch noch nach Nationalität ausgewiesen würde.  

![image](https://user-images.githubusercontent.com/42339363/98919201-d3c99b00-24ce-11eb-82c3-92cf35cb245f.png)  

3. Namen für Quellspalte setzen, in diesem Fall soll sie _Merkmal_ heissen.  

![image](https://user-images.githubusercontent.com/42339363/98920246-29eb0e00-24d0-11eb-8205-f2b0d5a9eef8.png)
