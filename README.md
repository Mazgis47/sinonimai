# Sinonimai

Lietuvių kalbos sinonimai, generuoti automatiškai, šiek tiek anotuoti rankiniu būdu, ištaisant akivaizdžias klaidas populiariausiuose žodžiuose. 
- **sinonimai.txt** - originalūs sinonimai kiekvienai žodžio formai.
- **synonyms-merged.txt** - pagrindinė žodžio forma (bendratis, vns.V., ir t.t.) automatiškai pašalinant priešingus žodžius, kurie gali būti sutinkami pirmame faile pvz. geras - negeras. Taip pat išmesta keletas populiariausių antonimų pvz. aukštas - žemas, panaudojant antonimų failą.
- **antonimai.txt** - antonimai, naudoti sudarant antrą failą.

## Naudojimas

Kam norite, tam ir naudokite :)

## Technologija

- Pirmas failas sudarytas naudojant [GloVe](https://github.com/stanfordnlp/GloVe). Panaudota apie 4,7 GB lietuviško teksto.
- Antras failas - imant pirmojo failo duomenis, bandant nustatyti pagrindinę žodžio formą ir sujungiant formų sinonimus į vieną, taip pat pakeičiant formų sinonimus į pagrindinę formą.

## Komentarai, Idėjos ir Palildymai

Sukurkite "Issue" diskusijai, taip pat galite kelti "Pull Request".