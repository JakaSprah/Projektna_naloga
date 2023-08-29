# Projektna_naloga

V tej projektni nalogi sem analiziral rezultate maratonov s petih olimpijskih iger v letih 2000-2016. 
Podatke sem našel na [spletni strani olimpijskih iger](https://olympics.com/en).

S pomočjo datoteke *prenos.ipynb* sem prenesel html s petih spletnih strani in jih shranil v pet ločenih datotek v mapi *podatki*.  
V datoteki *obdelava.ipynb* sem iz html-ja z regularnimi izrazi izluščil podatke in jih pretvoril v skupno csv datoteko v mapi *obdelani_podatki*.  
V datoteki *analiza.ipynb* sem s pomočjo knjižnice Pandas naredil analizo podatkov.  

Za vsakega tekmovalca sem zajel naslednje podatke:
- Ime
- Priimek
- Leto
- Rezultat
- Država

S pomočjo zajetih podatkov sem analiziral:
- Povprečja in standardne odklone po posameznih letih
- Uspešnost po državah
- Uspešnost posameznikov
- Vpliv temperature na rezultate



