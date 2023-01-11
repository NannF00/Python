https://scalatutorial.wordpress.com/2011/07/27/teil-5-schleifen-und-rekursion/

# Rekursion

reuse the funktion

## Task

Beschreibung

Schreibt ein Python – Programm, das vom User ein Ganzzahl n erfragt und anschließend die die Summe der Zahlen von 1 bis n ermittelt. Bsp: Wenn n = 10 ist, dann soll das Programm als Ergebnis 55 ausgeben, da 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 + 9 + 10 = 55 ist.

Löst das Problem zwei Mal: einmal mit einer Schleife, einmal mit einer Rekursion.

Kennzeichnet die Aufgabe nach der Bearbeitung als erledigt / abgeschlossen.

Code:

    def Schleife(i):
        ss=0
        ii=0
        while(ii<i):
            ii+=1
            ss+=ii
        print(ss)

    i=int(input("please input your number:"))
    Schleife(i)


    def Rekursion(ss=0,ii=1):
        if ii<=10:
            ss+=ii
            ii+=1
            Rekursion(ss,ii)
        else:
            print(ss)

    Rekursion()

use two paramters
