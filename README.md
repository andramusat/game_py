# game_py

Acest cod implementează un joc simplu de zaruri pentru 2-4 jucători. Funcționalitățile sale:

Funcția roll(): Simulează aruncarea unui zar, generând un număr aleatoriu între 1 și 6.

Inițierea jocului: 
--> Utilizatorul este întrebat să introducă numărul de jucători (între 2 și 4).
--> Validarea intrării se asigură că este un număr întreg în intervalul specificat.

Stabilirea condițiilor de câștig:
-->Se stabilește un scor maxim pentru joc (50 puncte).

Inițializarea scorurilor jucătorilor:
--> Se creează o listă pentru a stoca scorurile fiecărui jucător, toți pornind cu scorul 0.

Desfășurarea jocului:
--> Jocul continuă până când cel puțin un jucător atinge sau depășește scorul maxim.

Runde de joc:
-->Fiecare jucător are propriile sale runde.
--> La fiecare tur, jucătorii sunt întrebați dacă doresc să arunce zarurile.
--> Dacă un jucător obține un 1, scorul său pentru runda curentă este resetat la 0 și runda se termină.
--> Altfel, scorul său pentru runda curentă este actualizat cu suma obținută aruncând zarurile.

Determinarea câștigătorului:
--> La final, jucătorul cu cel mai mare scor este declarat câștigător.

Afisarea rezultatelor:
--> Se afișează numărul jucătorului câștigător și scorul său.
