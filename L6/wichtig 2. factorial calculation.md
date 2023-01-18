
Arbeitsauftrag

Schreibt ein Python – Programm, das vom User ein Ganzzahl n erfragt und anschließend die Fakultät von N berechnet. (Falls Ihr es braucht: n! = 0).

Löst dieses Programm auf 2 Arten: einmal mit einer Schleife und einmal mit einer Rekursion. Ladet abschließend die beiden Python – Skripte (*.py – Datei) als Lösung hoch.

    def Schleife(n):
        i=1
        ss=1
        if n==0:
            print(0)
            return 
        while i<=n:
            ss*=i
            i+=1
        print(ss)

    n=int(input("Which number you want to make factoral calculation:"))
    Schleife(n)

# false Tree
    def Rekursion(n,ss=1,ii=1):
        if n==0:
            print(0)
            return
        if ii<=n:
            ss*=ii
            ii+=1
            Rekursion(n,ss,ii)
        else:
            print(ss)

    n=int(input("Which number you want to make factoral calculation:"))
    Rekursion(n)
    

    
 result:
 
 ![image](https://user-images.githubusercontent.com/117897416/211791262-50ee138c-8b4e-427a-b611-d0926ac40f15.png)
