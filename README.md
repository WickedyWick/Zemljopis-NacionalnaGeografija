# Nacionalna geografija / zemljopis web aplikacija

Nacionalna geografija / zemljopis web aplikacija

Repo -> https://github.com/WickedyWick/zemljopis

## OPIS

- Backend projekta je napisan sa NODEJS i EXPRESS i SOCKETIO frameworkovima
- Početna stranica radi na princip HTTP requstova, dok game stranica radi u real time-u sa soketima
- Android verzija je trenutno u razvoju i biće opcija crossplaya izmedju svih uredjaja
- Baza podataka je MySQL
[DEMO](https://youtu.be/CoAYXbh9bSI] - starija verzija projekta gde se demonstrira mogućnost realizacije projekta

## LINK

[www.zemljopis.rs](https://zemljopis.rs) - web aplikacija
- Android verzija je i dalje u razvoju

##PLANOVI I RAZVOJ

- Projekat je planiran da bude hostovan i potpuno besplatan za sve korisnike , projekat će sadrzati reklame (jedan baner na strani koji ne ometa rad igre, GOOGLE AD SENSE).
- Cilj je da se barem isplati cena hostovanja i domena.
- U planu je da se dodaju rankovane liste, akaunti i autentifikacija
- Planira se upotreba neke frontend js biblioteke (React, next, nest...?)
- Android verzija se razvija u javi 

## STATE 
 
  DESKTOP BETA
  ANDROID U RAZVOJU

### FUNKCIONALNOSTI
- Podaci prihvaćeni u latinici (sa kvačicama i bez) i ćirilici
- Bodovovanje i pregled rezultata drugih igrača u sobi po rundama
- Vote kick sistem, da ne mora da se pravi nova soba ako jedan igrač odluči da prestane da igra
- Jednostavan Base64 sessionToken koji se čuva u localStorage-u koji ograničava da korisnik ne može da bude u više soba u isto vreme 
- -> Takođe omogućava da samo registrovani korisnik u tom browseru može da pristupi sobi , a ne neko drugi ko zna sobu i ime 
- Room-based sistem
- Pošto je baza još mala i jako je teško pa skoro nemoguće imati SVE podatke , napravljen je predloži sistem gde mogu da se predlože nepravilni rezultati , koji idu na razmatranje 
- Funkcionalnosti su prikazane u [full demo videu](https://youtu.be/COptxK_RlOs) 
