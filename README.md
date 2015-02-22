# coduripostale
#### Script pentru preluare date utile la generarea hărții codurilor poștale din București/România

Scriptul face request-uri către overpass cu numele străzilor citite dintr-un csv și obține coordonatele geografice pentru fiecare astfel de stradă.
Rezultatele obținute sunt salvate într-un fișier json în același folder cu csv-ul din care s-a făcut citirea străzilor.

### Warning:
Poate dura în jur de 3 ore, deoarece se execută un singur query pe secundă!


