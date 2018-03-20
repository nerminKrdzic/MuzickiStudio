# MuzickiStudio

## **Opis teme**

###### Glavni fokus MusicBox aplikacije je omogućavanje korisnicima pristup raznim vrstama pjesama. Mnogi vole da slušaju muziku dok uče, bave se nekom fizičkom aktivnosti ili čisto radi relaksacije. Ova aplikacija će im to pružiti. Korisnici mogu odabrati sebi omiljene pjesme ili razvrstati ih u liste koje slušaju ovisno o aktivnosti koju rade ili u kojem su raspoloženju te tako jednostavno odabrati koju muziku žele slušati. Međutim, može nam dosaditi čak i naša omiljena pjesma te tada korisnici mogu istražiti neki potpuno novi tip muzike ili mogu zatražiti da im aplikacija preporuči neke nove pjesme slične onima koje su korisniku omiljene. Također, MusicBox podstiče korisnike na kreativnost te im omogućava i uploadovanje njihovih vlastitih djela na koja mogu dobiti feedback od ostalih korisnika u vidu ocjene i/ili komentara. Nekada fanovima muzike nije dovoljno čisto slušanje muzike kroz slušalice te tada mogu posjetiti profil svojih omiljenih izvođača i provjeriti da li imaju organizovan neki događaj kao i dobiti informacije o tom događaju. 



## **Procesi**

###### **Registracija** 
Korisnik unosi svoje podatke (ime,prezime, e-mail, korisnicko ime, sifru), zatim se vrsi validacija podataka. U slucaju da validacija ne prodje korinik mora unijeti validne podatke. Ako je validacija prosla kreira se korisnicki profil (account), i korisnik je u stanju da pravi svoje liste pjesama, da ocjenjuje i/ili komentarise djela drugih korisnika ukljucujuci i mogucnosti koje su date "guest" korisniku.  

###### **Prijavljivanje(logina)** 
Korisnik unosi korisnicko ime i sifru, Validiraju se podaci i, u slucaju pada validacije, ispisuju upozorenja u skladu s greskom npr.(nepostojece korisnicko ime, neispravna sifra td..). Prolaskom validacije se otvara profil korisnika   

###### **Preoporuka pjesama**
Nakon što korisnik zatraži preporuku pjesama sistem će analizirati njegove najslušanije pjesme te na osnovu toga filtrirati pjesme iz baze podataka te sastaviti listu pjesama za korisnika

###### **Pretraga po filterima**
Korisnik može na razne načine filtrirati pjesme. Može unijeti ime pjesme / izvođača, odabrati žanr. Nakon toga sistem u bazi podataka traži pjesme na osnovu unsenih filtera i prikazuje ih korisniku nakon čega on može neku od pjesama (ukoliko se pronađe pjesma koja zadovoljava te filtere) dodati u svoj playlist, poslušati je te ostaviti ocjenu ili komentar.

###### **Pretraga top pjesama**
Korisnik može da zatraži prikaz najslušanijih pjesama u mjesecu nakon čega se prikazuje ranije formirana lista koja je nastala analiziranjem broja slušanja za svaku pjesmu. Nakon toga, slično kao ranije korisnik može odabrati da je doda u svoj playlist ili naprosto da je posluša ili naravno da je ocijeni / ostavi svoj komentar. 

###### **Promovisanje**
VIP korisnici mogu rezervisati (ukoliko nisu već svi slotovi zauzeti) mjesto na promotivnom tabu aplikacije. Prilikom rezervisanja slota za reklamiranje korisnik odabire pjesmu ili event koji želi da promoviše, odabire vremenski period na koji želi da to promoviše (max 7 dana) i eventualno dodaje dodatni tekst na reklamu. Nakon toga se obračunava svota koja se naplaćuje za tu reklamu. Nakon toga drugi korisnici promovisani sadržaj pronalaze u posvećenom dijelu aplikacije te klik na reklamu ih dovodi na tu pjesmu/događaj.

###### **Upload pjesama**
Korisnik odabire pjesmu koju zeli da upload-uje, Nakon cega pise naziv pjesme, tip zanra, da li zeli dopustiti komentare na svoju pjesmu, i na kraju stavlja svoj komentar (ako hoce), i vrsi upload na aplikaciju. 

## **Funkcionalnosti**

######- Mogucnost slusanja raznih vrsta pjesama
- Mogucnost pretrage pjesama po nazivu pjesme
- Mogucnost pretrage pjesama po nazivu izvodjaca
- Mogucnost pretrage pjesama po zanru
- Mogucnost pretrage pjesama preporukom
- Mogucnost kreiranja privatne play-liste
- Mogucnost pracenja najpreslusnijih pjesama
- Mogucnost pracenja najnovijih(novododanih) pjesama
- Mogucnost ocjenjivanja pjesama
- Mogucnost ostavljanja komentara nad pjesmama
- Mogucnost upload-a sopstvenih pjesama
- Mogucnost dodavanja event-a
- Mogucnost prikaza event-a drugih korisnika
- Mogucnost rezervisanja reklame za pjesmu ili event