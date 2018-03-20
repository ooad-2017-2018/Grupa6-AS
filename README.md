# VIParking 

1. Amila Ljutović
2. Selma Lekić
3. Ajla Kremo

## OPIS TEME

VIParking je osmišljen kao programsko rješenje koje korisniku omogućava online odabir željene parking lokacije, rezervaciju mjesta na 
istom te online plaćanje ,ili ukoliko korisnik želi posebne pogodnosti, plaćanje putem parking kartice. Svi korisnici parkinga moraju
biti registrovani korisnici aplikacije te se time pruža dodatna sigurnost svih korisnika parkinga. Prvenstveno se ovom aplikacijom
omogućava registracija određenih parking lokacija firme koja posjeduje aplikaciju te upravljanje istim. Čitav proces je
zamišljen da se odvija online, bez upotrebe parking listića koji su naširoko popularni i time se, barem u maloj dozi, pokušava probuditi 
ekološka svijest korisnika. 

## PROCESI 

##### REGISTRACIJA PARKING LOKACIJE 
Omogućava se registracija svih parking lokacija firme koja upravlja aplikacijom. To se omogućava unošenjem adrese, eventualnog naziva
parking lokacije, broja slobodnih mjesta predviđenih za parkiranje, cijena po satu, radno vrijeme i broj raspoloživih mjesta. Svaka
parking lokacija treba da postavi minimalnu rezervaciju parking mjesta. Unos broja parking lokacija je neograničen. 

#### REGISTRACIJA KORISNIKA 
Korisnik registracijom omogućava sebi prvenstveno pristup parkingu a nakon toga i rezervaciju određenog parking mjesta. Proces 
rezervacije je završen ukoliko korisnik unese osnovne informacije kao što su ime i prezime, broj telefona, adresa, korisničko
ime i lozinku, broj registarskih tablica, i da li želi vlastitu parking karticu koja vrijedi na toj parking lokaciji. 

#### REZERVACIJA PARKING MJESTA 
Ukoliko je uslov za rezervaciju parking mjeta ispunjen, odnosno ako je korisnik registrovan, korisnik odabire parking lokaciju
koja mu odgovara, i ukoliko ima slobodnih mjesta na istoj, rezerviše svoje parking mjesto. Korisnik odabire ili jednokratni pristup 
ili mjesečnu/godišnju članarinu. Minimalna rezervacija parking mjesta mora biti ispoštovana i potvrdom rezervacije pristaje 
na uplaćivanje cijene parking mjesta za odabrano vrijeme. Omogućena je produživanje rezervacije parking mjesta. 

#### ODABIR PLAĆANJA
Nakon rezervacije mjesta, korisnik odabira da li želi uplaćivanje prediđenog iznosa putem elektronskog plaćanja ili da li želi da koristi
svoju parking karticu. Parking kartica se može novčano dopuniti osoblju koje to evidentira, ili online i posjeduje određeni limit i 
odredjene pogodnosti.

#### ULAZ/IZLAZ 
Prilikom dolaska na rezervisano mjesto korisnik može pristupiti parkingu na dva načina. Ukoliko posjeduje svoju parking karticu 
provlači je, pri tome se skenira tablica da se može potvrditi da je to zaista korisnik koji je rezervisao mjesto, i omogućen je dolazak
na rezervisano mjesto. Ukoliko korisnik plaća parking putem elektronskog plaćanja, na njegovom mobitelu se pojavljuje online parking 
listić sa QR kodom koje skenira prilikom ulaska. Proces izlaska s parkinga je identičan. 

#### UVID U KORISNIČKI RAČUN
Korisnik ima opciju pregledavanja svih parking sesija koje je imao od kada je registrovan. 

#### IZVJEŠTAJ 
Administrator ima mogućnost pregledavanja svih izvještaja određene parking lokacije te odobravanja transakcije koje je korisnik 
uputio osoblju u svrhu dopune parking kartice.


## FUNKCIONALNOSTI 

- Mogućnost registracije parking lokacije od strane administratora
- Mogućnost registracije korisnika
- Mogućnost odabira parking lokacije i jednokratnog pristupa ili članarine
- Mogućnost odabira posjedovanja posebne parking kartice
- Mogućnost online plaćanja ili uplate na parking karticu
- Uvid korisnika u sve njegove prethodne parking sesije
- Uvid administratora u poslovanje,promet i profit parking mjesta

## AKTERI
- Administrator - vrši potrebna ažuriranja aplikacije, registruje parking lokacije koje firma posjeduje, odobrava uplaćene iznose korisnika
  osoblju na svoju parking karticu
- Korisnik - osoba koja ima mogućnost rezervisanja parking mjesta na određenoj lokaciji i plaćanja istog ali samo uz prethodnu registraciju, 
- Osoblje - zaduženo je za uručivanje parking kartica registrovanih korisnika, i korisnik osoblju uplaćuje dopune za parking karticu 
