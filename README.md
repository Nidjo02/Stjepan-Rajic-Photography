# Stjepan-Rajic-Photography

Seminarske	vježbe:
Izraditi vlastitu internetsku stranicu s temom koju je student prijavio na početku
kolegija uz upotrebu znanja i tehnologija naučenih na ovom kolegiju.
Seminarski rad se sastoji od 2 dijela koji se međusobno nadograđuju. Predaja
svakog djela će biti u tjednu prije kolokvija putem LMS sustava.
Korišteni sadržaj (tekstovi, slike i drugi multimedijski sadržaj) te sam njegov
vizualni prikaz (fontovi, boje, razmještaj elemenata na stranici, međusobna
poravnanja elemenata itd.) je isključivo prepušteno studentu na odabir pod
uvjetom da zadovoljava niže zadane smjernice.
Nije dozvoljeno koristiti „naprednije“ znanje za rješavanje zadatka u smislu
upotreba tehnika koja niste u danom trenutku još prošli na ranijim predavanjima ili
vježbama.
Smjernice:
1. DIO
Općenito
- Treba napraviti 3 podstranice:
o Naslovnica
o O nama
o Kontakt
- Svaka stranica treba imati isto zaglavlje i podnožje
- U zaglavlju stranice potrebno je postaviti „logo“ teme i poveznice na ostale
podstranice, a u podnožju stranice potrebno je biti vidljivo studentovo ime i
prezime te JMBAG
- Stranica Kontakt treba biti u poddirektoriju
- Stranice trebaju imati ispravne naslove i meta podatke
- Stranice trebaju biti ispunjene proizvoljnim sadržajem imajući na umu
studentovu prijavljenu temu
- Sve slike koje se upotrebljavaju na stranici trebaju biti lokalno preuzete i
postavljene u direktorij „images“ koji je dio seminarskog rada
- Stranice trebaju imati vizualnu osobnost (u duhu prijavljene teme) upotrebom
box modela (padding, margin), boja (color), pozadina (background-image),
tipografije (font), obruba (border) i poveznica (hover i druga stanja)
- Stranice trebaju biti semantički ispravne (validator.w3.org)
Naslovnica
- Stranica treba imati nekoliko sekcija s podnaslovima te nekoliko paragrafa
teksta o odabranoj temi
- Tekstovi trebaju biti obogaćeni sa slikama (i po želji drugom multimedijom) o
odabranoj temi
- Na početku stranice trebaju biti poveznice na poglavlja putem kojih posjetitelj
može brzo preskočiti na pojedine poglavlja koja se nalaze na naslovnici
- Tekstovi trebaju biti semantički ispravni i obogaćeni s barem 5 različitih HTML
elemenata
- Na dnu stranice treba biti tablica I x P (I = broj slova u imenu studenta, P = broj
slova u prezimenu studenta). U tablicu treba unijeti proizvoljne podatke vezane
uz odabranu temu te minimalno tri odabrane ćelije trebaju biti spojene
O nama
- Stranicu treba realizirati upotrebom pozicioniranja, samu tehniku
pozicioniranja (relative, absolute…) student sam odabire
- Stranica ne treba biti responzivna odnosno treba biti realizirana tako da na
određenoj širokoj (desktop) rezoluciji izgleda ispravno
- Jedan, proizvoljno odabran element na stranici od strane studenta treba biti
pozicioniran na takav način da se ne smije pomicati prilikom scrolla stranice
- Potrebno je minimalno 3 sadržajne sekcije realizirati s time da jedna od tih
sekcija treba biti u stilu sidebara odnosno treba biti pozicionirana ili lijevo ili
desno od ostatka glavnog sadržaja
- Sadržaj na stranici student sam osmišljava u skladu s vlastitom temom te ga
treba imati barem onoliko da se postigne scroll stranice
Kontakt
- Stranicu treba realizirati upotrebom plutanja
- Stranica treba biti responzivna odnosno treba biti realizirana tako da se na
određenoj proizvoljnoj rezoluciji layout mijenja iz mobile u desktop i obrnuto
(student sam odlučuje koje sve elemente treba promijeniti)
- Osim sadržaja poput teksta i slika, stranica treba sadržavati ispravu formu za
slanje upita
- Forma se treba sastojati od barem 3 različita tipa polja za unos podataka
(input, select, checkbox, textarea itd.)
- Klikom na gumb za slanje forme svi uneseni podaci se ispravno trebaju pojaviti
u URL-u
- Također treba sadržavati poveznicu koja otvara slanje poruke na e-mail adresu
od studenta



Smjernice:
2. DIO
Općenito
- Stranicu realiziranu u 1. dijelu treba proširiti s 2 nove podstranice:
o Novosti
o Trgovina
- Sadržaj novih podstranica treba pratiti temu seminarskog rada
- Stranice je potrebno stilski urediti u vizualnom tonu s ranijim zadatkom
- Postojeće jednostavne poveznice između stranica napraviti na semantički
ispravan način u obliku navigacije te osigurati da se prilikom responzivnosti
promijeni iz horizontalne u vertikalnu (ili obrnuto), drugim riječima ako su na
desktopu poveznice u navigaciji jedna pokraj druge, na mobitelu trebaju biti
jedna ispod druge
- Prema vlastitim željama, dodati dva vizualno različita Google Fonts fonta na
stranicu i primijeniti jedan font za cijelu stranicu, a drugi za naslove
o https://fonts.google.com
- Dodati Font Awesome font i upotrijebiti ikonice na barem 3 mjesta, ikonice
stilizirati u skladu s dizajnom stranice (veličina, boje…)
o https://fontawesome.com
- Na Kontakt stranicu dodati ugrađenu Google Maps kartu
o https://www.google.com/maps
- Na O nama stranicu dodati ugrađeni YouTube video
o https://www.youtube.com
Novosti
- Raspored elemenata na stranici treba realizirati upotrebom Bootstrap razvojne
rešetke
- Stranica treba biti responzivna odnosno treba se prilagođavati širini ekrana
tako da prilikom smanjivanja širine stranice, ako sadržaj vizualno više ne stane
jedan pokraj drugog, isti se mora preslagivati jedan ispod drugoga, odnosno
drugim riječima stranica treba vizualno ispravno izgledati kako na širokom
ekranu (desktop), tako i na uskom (mobitel)
- Stranica treba prikazati sadržaj u nekoliko stupaca i redova (ne manje od 3
stupca i 3 reda na desktopu), odnosno drugim riječima stranica treba koristiti
Bootstrap rešetku putem koje će prikazati najmanje 9 objava
- Sadržaj na stranici se treba prikazati u obliku objava odnosno „blog postova“
tako da svaka objava ima sliku, naslov, kratki opis, kategoriju i poveznicu za
otvaranje cijelog članka (pojedinačnu stranicu članka ne treba napraviti tako da
sama poveznica može imati npr. „#“ za URL)
- Pri vrhu stranice treba osim samog naslova podstranice realizirati element koji
će u sebi tehnikom plutanja s desne strane sadržavati poveznice koje
simboliziraju kategorije (teme) novosti, drugim riječima ako se radi o temi
„Sport“, element bi sadržavao poveznice npr. „Nogomet“, „Košarka“,
„Rukomet“, poveznice također mogu imati prazne („#“) URLove te klikom na
njih se ne treba ništa događati
Trgovina
- Stranica se treba izraditi upotrebom Flexbox-a za potrebe pozicioniranja
elemenata na stranici, određeni elementi mogu imati druge vrste
pozicioniranja ako isto nije moguće postići s Flexbox-om
- Stranica treba biti responzivna odnosno treba se ispravno prikazivati i na
mobilnim rezolucijama
- Potrebno je izraditi novu podstranicu „Trgovina“ koja će sadržavati prikaz od
najmanje 9 artikla za kupnju, predmeti za kupnju mogu biti digitalni i/ili fizički,
ovisno o studentovoj temi
- Svaki artikl treba sadržavati sliku, naziv, kratki opis, cijenu i gumb za dodavanje
u košaricu (gumb ne treba ništa raditi)
- Određeni predmeti trebaju biti naglašeni tako da se prekriže određene cijene i
stave nove, snižene cijene (drugim riječima određeni predmeti su na akciji
odnosno popustu što treba vizualno naglasiti)
- Na vrhu stranice treba napraviti banner koji će u pozadini imati fotografiju, a
preko nje tekst u kojem će pisati da je trenutačno aktualna određena akcija na
pojedine artikle
- Gumb za dodavanje u košaricu treba imati zaobljene rubove i na hover treba
postepeno s tranzicijom mijenjati boje
