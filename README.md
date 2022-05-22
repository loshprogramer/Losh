# LoshV0.1
  Python program za pracenje laznih jutjub kanala u strimu

## Uputstvo za instaliranje i koriscenje
[![youtube uputstvo](https://i.imgur.com/yuSsNGf.png)](https://www.youtube.com/watch?v=Wy8qqWN3Mjg)

## Boje
Cela poruka se boji u zavisnosti od starosti kanala
| Starost kanala | Boja pozadine |
| ----------- | ----------- |
| 0 dana | Crvena |
| 1,2 dana | Zuta |
| 3,7 dana | Zelena |
| 8,30 dana | Plava |
| 31,90 dana | Siva |
| svi ostali | Crna |

## Datoteke
Samo u pouzdani-kanali.txt mogu da se dodaju kanali ostale fajlove ne menjati!

Ubacio sam bazu od 10 000 ljudi sa kanala Nolifer, Mosar i Gajbotron	
| Datoteka | Objasnjenje |
| ----------- | ----------- |
| LOSH.cmd | Pokretanje programa u cmd |
| LOSH-WT.cmd | Pokretanje programa u WindowsTerminalu (instalirati sa Microsoft Store) bolji od cmd prikazuje emoji i moze direktno da se klikne na kanal |
| kod.py | Python kod programa |
| potrebne-biblioteke.cmd | Pokrenuti prvi put posle instalacije python da bi se instalirale potrebne biblioteke. Moze ponekad da se pokrene da nadogradi biblioteke |
| baza-svih-kanala.txt | Svaki kanal se proverava samo jednom svaki sledeci put datum se povlaci iz baze. Kanali koji se prvi put pojavljuju pocinju sa crvenom strelicom, a kanali iz baze sa zelenom strelicom |
| pouzdani-kanali.txt | Dodati pouzdane kanale kako sam zapoceo oni ce pocinjati sa plavom kockicom |



## Folderi

| Folder | Objasnjenje |
| ----------- | ----------- |
| ISTORIJA | Istorija svih strimova ostaje u ovom folderu u formatu id_snimka.html |
| TEMP | Fajlovi koje program koristi, izvestaj svih greski se nalazi u izvestaj-o-greskama.txt |

## Boja strelice
| Boja strelice | Objasnjenje |
| ----------- | ----------- |
| zelena | Kanali koji su se vec pojavljivali i nalaze se u baza-svih-kanala.txt |
| crvena | Kanali koji se prvi put pojavljuju |
| punjena plava | Kanali koji su uneti u pouzdani-kanali.txt |
| punjena crvena | Kanali koji se prvi put pojavljuju i mladji su od 30 dana |
