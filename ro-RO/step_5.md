## În așteptarea unui câștigător

Să adăugăm codul pentru a aștepta până când se apasă un buton.

+ După afișarea unei imagini, va trebui să aștepți până când cineva își apasă butonul.

Un alt mod de a spune acest lucru este că va trebui să aștepți atâta timp cât butonul A și (**and**) butonul B nu (**not**) au fost apăsate.

Pentru a face acest lucru, adaugă o buclă `while` din secțiunea „Control“. Bucla `while` trebuie adăugată imediat după blocul `show leds`.

![captură de ecran](images/reaction-while.png)

+ Trage un bloc `and` din secțiunea „Logic” în blocul tău `while`:

![captură de ecran](images/reaction-and.png)

+ Trage un bloc `not` din „Logic” în partea stângă a blocului `and`:

![captură de ecran](images/reaction-not.png)

+ Trage un bloc `button A is pressed` din „Input” după blocul `not`:

![captură de ecran](images/reaction-button-a.png)

+ Repetă cei doi pași de mai sus pentru a adăuga `not button B is pressed` în partea `dreapta` a buclei tale „while”.

![captură de ecran](images/reaction-button-b.png)

+ Poți să adaugi o întârziere foarte scurtă (20ms), astfel încât bucla ta `while` să aștepte atâta timp cât nu a fost apăsat un buton.

![captură de ecran](images/reaction-delay.png)

+ Testează proiectul tău. Jocul tău ar trebui să afișeze acum o imagine și apoi să aștepte atâta timp cât butoanele A **și** B **nu** au fost apăsate.