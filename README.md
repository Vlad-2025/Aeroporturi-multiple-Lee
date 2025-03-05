${\textsf{\color{gold}Work in progress}}$
# Un program in consola pentru a obtine drumul cel mai scurt intre mai multe aeroporturi

A fost scris in timpul liceului, folosind cunostintele aferente perioadei.

## De ce acest program?

Fiind pasionat de aviatie, doream sa simulez (desi la un nivel foarte simplu) modul in care sunt gestionate zborurile.
Am ales 'algoritmul lui Lee' deoarece este adecvat pentru lucrul cu matrice si obstacole (zonele restrictionate).

## Cum functioneaza?

Programul functioneaza prin crearea unei matrice care reprezinta 'harta', ce contine mai multe aeroporturi, fiecare avand o zona circulara in jurul sau (e posibil sa nu aiba), cu diferite niveluri de restrictie (momentan, doar civil sau militar).

Pentru a obtine drumul cel mai scurt intre mai multe aeroporturi (de exemplu, 3 aeroporturi: 1, 2 si 3), extrage o submatrice, ce are in colturi diametral opuse aeroporturile intre care calculeaza distanta (prima data 1 si 2, apoi 2 si 3), procesul se repeta, iar la final se aduna distantele de la fiecare submatrice pentru a obtine distanta totala.
