# Ionic Framework

## Što je Ionic? Temeljni principi i arhitektura

Ionic Framework je otvoreni izvorni kod (open-source) UI softverski razvojni komplet (SDK) namijenjen izradi modernih, visokoučinkovitih aplikacija koje se mogu izvršavati na više platformi iz jedinstvene baze koda. Ova arhitektura omogućuje razvoj mobilnih aplikacija (za iOS i Android), web aplikacija (uključujući Progresivne Web Aplikacije - PWA) te desktop aplikacija, pružajući širok doseg uz optimizirane razvojne napore.

### Tehnologije

Ionic se oslanja na standardne web tehnologije: HTML, CSS i JavaScript, uz podršku za TypeScript. Ova arhitektonska odluka čini Ionic izuzetno pristupačnim za web programere, omogućujući im da svoje postojeće veštine u razvoju web aplikacija primene na razvoj mobilnih aplikacija. Prelaz s web razvoja na mobilni razvoj s Ionicom zbog toga je značajno olakšan, smanjujući krivu učenja i ubrzavajući inicijalni razvoj.

### WebView arhitektura

Aplikacije razvijene pomoću Ionic Frameworka izvršavaju se unutar WebViewa, komponente koja je ugrađena u nativni broswer mobilnog operativnog sistema. WebView omogućava prikaz web sadržaja i interakciju sa hardverom i softverom uređaja. Ova arhitektura pruža ključnu prednost pristupa nativnim mogućnostima uređaja, kao što su kamera, GPS, kontakti, i mobilnim funkcionalnostima, dok istovremeno omogućava korišćenje standardnih web tehnologija za razvoj aplikacija.

### Fleksibilnost u odabiru JavaScript Framework-a

Ionic Framework omogućava korišćenje različite JavaScript framework-e, uključujući Angular, React, Vue.js ili čak Vanilla JavaScript. Ova sposobnost prilagođavanja različitim tehnologijama omogućuje timovima da iskoriste postojeće znanje i veštine bez potrebe za učenjem potpuno novog ekosistema za mobilni razvoj.

### Strateške prednosti

- **Prilagodljivost:** Ionic omogućuje organizacijama da koriste postojeće stručnosti u Angularu, Reactu ili Vue.js-u, čime se smanjuju prepreke za ulazak u mobilni razvoj.
- **Optimizacija resursa:** Minimizira potrebu za prekvalifikacijom timova ili angažiranjem novih stručnjaka.
- **Smanjenje rizika:** Izbjegava ovisnost o jednom tehnološkom stogu, čime se povećava fleksibilnost i dugoročna održivost.

Ionic Framework se pozicionira kao razvojni alat koji se prilagođava raznovrsnim web razvojnim ekosistemima, čime se povećava njegova privlačnost za kompanije sa različitim tipovima razvoja softvera.

### Ključne karakteristike i prednosti korišćenja Ionica

Ionic Framework nudi niz ključnih karakteristika koje ga čine privlačnim izborom za razvoj aplikacija na više platformi. Njegova primarna snaga leži u **cross-platform kompatibilnosti**, koja omogućava pisanje jedinstvene baze koda za implementaciju na različitim platformama, uključujući iOS, Android, web i desktop. Ova sposobnost značajno smanjuje vreme i troškove razvoja, što je posebno korisno za kompanije koje žele maksimizirati doseg uz minimalan dodatni napor.

Jedna od najvećih prednosti je **isplativost**. Održavanjem jedinstvene baze koda za sve platforme, Ionic značajno smanjuje ukupne troškove razvoja. Ovo ga čini idealnim rešenjem za startape, mala i srednja preduzeća, kao i projekte sa ograničenim budžetom, budući da je prosečan trošak razvoja Ionic aplikacije često niži u poređenju sa alternativama.

**Brza izrada prototipova** i **brzina razvoja** su takođe istaknute prednosti. Ionicovo oslanjanje na web tehnologije i bogat set unapred izgrađenih UI komponenti omogućavaju programerima da brzo kreiraju Minimalno Održive Proizvode (MVP) i prototipove. Značajke poput instantnog pregleda i Live Reloada olakšavaju brzu iteraciju, štedeći značajno vreme i resurse tokom razvojnog ciklusa.

Ionic se ističe svojom bogatom bibliotekom unapred izgrađenih **UI komponenti**. Sa više od 100 komponenti, tipografijom i osnovnim temama, Ionic omogućava razvoj vizuelno privlačnih i responzivnih korisničkih interfejsa. Ove komponente su dizajnirane da se automatski prilagođavaju izgledu i osećaju specifičnim za platformu (npr. Material Design za Android, iOS stil za Apple), osiguravajući dosledno, ali nativno korisničko iskustvo bez opsežne prilagodbe.

Iako je primarno baziran na web tehnologijama, Ionic aplikacije mogu pristupiti širokom spektru **nativnih funkcionalnosti uređaja** (npr. kamera, GPS, kontakti) putem robusnog ekosistema dodataka, koristeći Cordovu ili, češće, Capacitor. Ovo omogućava hibridnim aplikacijama da iskoriste puni potencijal mobilnih uređaja.

Ionic ima **snažnu podršku zajednice**. Okvir ima veliku, zrelu i aktivnu open-source zajednicu, koja nudi opsežnu dokumentaciju, forume, Discord kanale, prisutnost na Stack Overflow-u i lokalne meetupe. Ovaj robustan ekosistem podrške pruža obilje resursa za rešavanje problema i učenje, što je neprocenjivo za programere.

Na kraju, **jednostavnost održavanja** proizlazi iz pristupa jedinstvene baze koda, što pojednostavljuje tekuće održavanje, ažuriranja i dodavanje novih funkcionalnosti na svim implementiranim platformama.

### Nedostaci i ograničenja Ionica

Uprkos brojnim prednostima, Ionic Framework ima određena ograničenja koja treba uzeti u obzir. Jedan od glavnih izazova su ograničenja performansi. Iako je Ionic optimizovan za web performanse i teži nativnom osećaju, njegove aplikacije, budući da se izvršavaju unutar WebView okruženja, možda neće postići istu brzinu i odzivnost kao potpuno nativne aplikacije. Ovo je posebno primetno kod složenih aplikacija, onih sa intenzivnom grafikom ili zahtevnim animacijama, gde se može primetiti pad performansi od 10-15% u poređenju sa nativnim rešenjima. To znači da projekti koji zahtevaju vrhunske performanse, tešku grafiku ili složenu obradu podataka u realnom vremenu mogu naići na uska grla u performansama Ionica, što zahteva pažljivu optimizaciju ili razmatranje alternativnih okvira.

Izazovi u otklanjanju grešaka (debugging) takođe su prisutni. Apstrakcioni sloj koji uvodi okvir može ponekad otežati otklanjanje grešaka, posebno kada se problemi tiču interakcija između web koda i osnovne nativne platforme. Alati za otklanjanje grešaka možda ne pružaju detaljne uvide dostupne za nativni razvoj. Postoji i određena razlika u dokumentaciji. Dok neki izvori navode "izazove sa hot reloadingom" ili čak da "Ionic ne podržava hot reloading", zvanična dokumentacija jasno navodi da "Ionic CLI ima funkciju Live Reload, tako da se promene odmah ažuriraju!". Ova razlika verovatno proizlazi iz nijansiranog razumevanja pojmova "hot reloading" (koji pokušava da injektuje promene bez gubitka stanja aplikacije) i "Live Reload" (koji automatski osvežava celu aplikaciju pri promenama koda). Za programere to znači da je razvoj u pregledaču sa Ionicom veoma brz, ali otklanjanje grešaka koje uključuju nativne interakcije ili složeno upravljanje stanjem može i dalje zahtevati tradicionalnije ponovne izgradnje ili ponovno pokretanje na stvarnim uređajima.

Iako Ionic pruža pristup nativnim funkcionalnostima putem dodataka, istorijski gledano, postojala su ograničenja u direktnom pristupu određenim nativnim API-jima. Ovo je moglo ograničiti funkcionalnost za funkcije koje su u velikoj meri zavisne od specifičnog hardvera uređaja ili mogućnosti operativnog sistema. Međutim, sa razvojem Capacitatora, ovaj problem je značajno ublažen.

Zbog svoje web-bazirane prirode i izvršavanja unutar WebViewa, Ionic aplikacije mogu biti podložne sigurnosnim ranjivostima tipičnim za web, kao što su Cross-Site Scripting (XSS) napadi ili presretanje podataka. Stoga su robusni procesi testiranja i sigurnosne prakse ključni za osiguranje kvaliteta i pouzdanosti Ionic aplikacija. Konačno, veličina aplikacije može biti veća. Aplikacije izgrađene sa Ionicom, posebno one sa brojnim dodacima i zavisnostima, mogu rezultirati većom konačnom veličinom aplikacije u poređenju sa čisto nativnim aplikacijama, iako su poboljšanja u Ionic verziji 4 i kasnijim verzijama značajno smanjila ovaj problem.

### Idealni slučajevi upotrebe za Ionic

Ionic je posebno dobro prilagođen projektima koji prioritizuju brz razvoj, isplativost i iskorišćavanje postojećih veština u web razvoju.

Za brzu izradu prototipova i MVP-ova, Ionic je izvanredan. Njegov brzi razvojni ciklus i unapred izgrađene komponente čine ga savršenim za brzo validiranje novih ideja i lansiranje minimalno održivih proizvoda na tržište radi testiranja i prikupljanja povratnih informacija. Kao Progresivne Web Aplikacije (PWA), Ionic je snažan kandidat. S obzirom na njegovu web tehnološku osnovu, idealan je za izgradnju PWA-a koje nude iskustvo slično nativnoj aplikaciji putem browser-a.

Ionic je takođe vrlo pogodan za interne poslovne alate, poput aplikacija za upravljanje zaposlenima, HR sisteme ili jednostavan unos podataka, gde vrhunske nativne performanse nisu primarni zahtev. Slično tome, za aplikacije bogate sadržajem, kao što su platforme za e-učenje, e-commerce aplikacije (koje ne zahtevaju visoke performanse) ili aplikacije za vesti, Ionic pruža efikasno rešenje za isporuku sadržaja.

Konačno, za web programere koji prelaze na mobilni razvoj, Ionic predstavlja prirodan izbor. Njegovo oslanjanje na HTML, CSS i JavaScript značajno smanjuje krivu učenja, omogućavajući programerima da glatko pređu na razvoj mobilnih aplikacija koristeći svoje postojeće veštine. To implicira da Ionic nije samo alat, već strateški omogućitelj za optimizaciju talenata i efikasnost budžeta, posebno za kompanije sa web-prvom strategijom ili one koje ulaze u mobilni razvoj sa ograničenim resursima.

## Ionicovo izvršno okruženje: Cordova vs. Capacitor

Izvršna okruženja, poput Apache Cordove i Ionicovog Capacitatora, igraju ključnu ulogu u omogućavanju hibridnim aplikacijama da pristupe nativnim funkcionalnostima uređaja, kao što su kamera, GPS, kontakti i druge mogućnosti koje nisu direktno dostupne web aplikacijama. Ova okruženja služe kao most između web tehnologija (HTML, CSS, JavaScript) i nativnih API-ja mobilnih platformi, omogućavajući programerima da koriste jedinstvenu bazu koda za razvoj aplikacija koje se mogu pokretati na različitim platformama.

Njihova važnost za Ionic proizlazi iz sledećih razloga:

1. **Cross-platform kompatibilnost**: Izvršna okruženja omogućavaju Ionic aplikacijama da se pokreću na iOS, Android, web i desktop platformama bez potrebe za pisanjem zasebnog nativnog koda za svaku platformu.
2. **Pristup nativnim funkcionalnostima**: Omogućavaju hibridnim aplikacijama da koriste nativne funkcionalnosti uređaja, čime se proširuje opseg mogućnosti aplikacije.
3. **Efikasnost razvoja**: Smanjuju kompleksnost razvoja i održavanja aplikacija, jer programeri mogu koristiti postojeće web veštine za izradu aplikacija koje izgledaju i ponašaju se kao nativne.
4. **Optimizacija resursa**: Omogućavaju organizacijama da smanje troškove razvoja i održavanja, jer se koristi jedinstvena baza koda za sve platforme.
5. **Podrška za PWA**: Capacitor, posebno, pruža inherentnu podršku za Progresivne Web Aplikacije, omogućavajući aplikacijama da funkcionišu kao web aplikacije sa nativnim iskustvom.

Izbor odgovarajućeg izvršnog okruženja direktno utiče na performanse, fleksibilnost i dugoročnu održivost Ionic aplikacija, čineći ga ključnim aspektom strategije razvoja.

### Razumevanje Apache Cordova

Apache Cordova, čija istorija počinje kao projekat otvorenog koda PhoneGap 2009. godine, predstavlja okvir otvorenog koda namenjen izvršavanju web aplikacija na različitim mobilnim platformama. Njegova funkcionalnost se zasniva na omotavanju web sadržaja (HTML, CSS, JavaScript) unutar nativnog WebView-a, omogućavajući da se web aplikacije prikazuju i izvršavaju kao mobilne aplikacije.

Web aplikacije koje se izvršavaju unutar WebView-a tradicionalno su izolovane (sandboxed) i nemaju direktan pristup hardverskim i softverskim funkcionalnostima uređaja, poput kamere ili kontakata. Cordova rešava ovaj problem pružanjem JavaScript API-ja koji su dostupni putem kolekcije dodataka (plugins). Ovi dodaci funkcionišu kao most između web aplikacije i nativnih funkcionalnosti uređaja, omogućavajući pristup širokom spektru mogućnosti.

Cordova ima dugu istoriju i zreo ekosistem, što je rezultiralo opsežnim tržištem dodataka i širokom podrškom zajednice. Njena struktura projekta je relativno jednostavna, što je čini pogodnom za postavljanje i razvoj manjih aplikacija. Međutim, ključni događaj koji je uticao na njenu budućnost jeste odluka Adobe-a da prekine zvaničnu podršku za PhoneGap/Cordovu 2020. godine, prepuštajući projekat isključivo održavanju open-source zajednice.

Ova situacija, gde je projekat prepušten isključivo zajednici, stvara određene izazove. Iako je održavanje zajednice dragoceno, gubitak korporativnog sponzorstva može usporiti napredak, potencijalno dovesti do manje doslednih ažuriranja za ključne funkcionalnosti i uneti neizvesnost za velike projekte koji se oslanjaju na Cordovu. To znači da projekti mogu ostati stabilni, ali manje inovativni ili manje prilagodljivi novim promenama operativnog sistema. Ova okolnost naglašava rizik prevelikog oslanjanja na jedan eksterno održavan open-source projekat bez snažne korporativne podrške, što je bio jedan od razloga zašto je Ionic razvio sopstveno rešenje, Capacitor.

### Predstavljanje Capacitatora od strane Ionica

Capacitor je predstavljen od strane Ionica 2018. godine kao moderno, cross-platform nativno izvršno okruženje, koje služi kao alternativa Cordovi. Njegov cilj je omogućiti jednostavniji i programerima nativnih aplikacija prihvatljiviji pristup izvršavanju web aplikacija nativno na Androidu, iOS-u, Electronu i Webu (uključujući PWA).

Capacitor omogućava programerima da izgrade jedinstvenu aplikaciju i koriste unificirani skup API-ja na različitim platformama, čime eliminiše potrebu za upravljanjem višestrukim API-jima specifičnim za platformu. Ključna prednost Capacitatora je njegova sposobnost direktnog pristupa nativnim API-jima bez stalnog oslanjanja na dodatke, kao i podrška za PWA "out-of-the-box".

Fundamentalna razlika u pristupu Capacitatora je u tome što tretira svaki platformski projekat (npr. Xcode za iOS, Android Studio za Android) kao izvorni resurs. To znači da se programeri podstiču da ove nativne projekte čuvaju u sistemima za kontrolu verzija i koriste nativne IDE-ove za konfiguraciju, izgradnju i testiranje specifično za platformu. Ovo se razlikuje od Cordovine apstrakcije putem config.xml datoteke.

Ovaj pristup upravljanju nativnim projektima, gde se nativni projekti "poseduju", predstavlja strateški potez Ionica. On programerima pruža veću vidljivost i kontrolu nad osnovnim nativnim kodom, olakšava rešavanje problema i omogućava složenije nativne prilagodbe bez potrebe za izradom posebnih dodataka. Capacitor je aktivno podržan od strane Ionic tima, što osigurava redovna ažuriranja i posvećenu podršku. Takođe, nudi kompatibilnost unazad sa većinom postojećih Cordova dodataka, što olakšava proces migracije za postojeće projekte.

Razvijanjem i podržavanjem Capacitatora, Ionic je preuzeo veću kontrolu nad kritičnim nativnim slojem hibridnog razvoja. To smanjuje oslanjanje na spoljne projekte koje održava zajednica (kao što je Cordova nakon Adobea), omogućava Ionic timu brže implementiranje ispravki i osigurava "kohezivniji stog". Ova posvećenost signalizira Ionicovu predanost poboljšanju iskustva nativne integracije i dugoročne održivosti svog okvira, direktno rešavajući neke od tradicionalnih izazova i rizika povezanih sa hibridnim razvojem.

### Usporedna tablica: Cordova vs. Capacitor

Ova tabela pruža jasan pregled i poređenje dva izvršna okruženja, ističući njihove ključne razlike i implikacije za razvoj. Takva usporedba je korisna za tehničke korisnike jer omogućava brzo razumevanje ključnih razlika i izbor okruženja koje najbolje odgovara specifičnim zahtevima projekta.

| Značajka / Aspekt                   | Apache Cordova                                                                                         | Ionic Capacitor                                                                                                     |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------- |
| **Porijeklo/Podrška**               | Otvoreni kod PhoneGapa (Adobeova podrška do 2020.), sada održava zajednica.                            | Razvijen i podržan od strane Ionica.                                                                                |
| **Starost**                         | Stariji, duže prisutan na tržištu.                                                                     | Relativno noviji (kreiran 2018.), brzo se razvija.                                                                  |
| **Pristup nativnom API-ju**         | Primarno putem opsežnog ekosistema dodataka.                                                           | Direktan pristup nativnom API-ju; podržava i dodatke.                                                               |
| **Ekosistem dodataka**              | Veći, etabliraniji ekosistem dodataka.                                                                 | Rastući ekosistem dodataka; kompatibilan unazad sa većinom Cordova dodataka.                                        |
| **Upravljanje nativnim projektom**  | Apstrahirano putem config.xml; platformski projekti su resursi vremena izgradnje.                      | Nativni projekti (Xcode, Android Studio) su izvorni resursi; direktno uređivanje datoteka specifičnih za platformu. |
| **CLI izgradnja za nativno**        | Podržava izgradnju nativnih aplikacija putem naredbenog retka (npr. `cordova build android`).          | Ne nudi izgradnju nativnih aplikacija putem naredbenog retka; preporučuje alate/IDE-ove specifične za platformu.    |
| **PWA podrška**                     | Nema inherentnu PWA podršku (fokus na nativne aplikacije).                                             | Out-of-the-box PWA podrška.                                                                                         |
| **Kohezija s Ionicom**              | Ionic ga je isprva koristio, zatim zamenio.                                                            | Ionicovo preferirano i integrisano izvršno okruženje.                                                               |
| **Lakoća prilagodbe nativnog koda** | Zahteva izgradnju namenskih dodataka za prilagođeni nativni kod.                                       | Lakše dodavanje prilagođenog nativnog koda direktno unutar projekta.                                                |
| **Održivost**                       | Može biti podložno greškama sa apstrahiranim alatima; potencijalni problemi sa kompatibilnošću unazad. | Bolja vidljivost promena nativnog projekta; poboljšana održivost sa novim verzijama OS-a.                           |

## Zašto je Capacitor preporučeni izbor za nove Ionic projekte

Capacitor je moderno rešenje koje Ionic podržava, što osigurava bolju dugoročnu podršku, redovna ažuriranja i brža rešenja problema od strane Ionic tima. Nudi pojednostavljen pristup nativnim funkcionalnostima, omogućavajući direktne API pozive umesto isključivog oslanjanja na dodatke. Pristup "izvornog resursa" za nativne projekte pruža programerima veću kontrolu, vidljivost i lakše rešavanje problema, omogućavajući nativnim i web timovima efikasniju saradnju. Out-of-the-box podrška za PWA aplikacije usklađena je sa modernim trendovima web razvoja. Iako Cordova zajednica i dalje održava projekat, korporativna podrška Capacitatora od strane Ionica pruža veću pouzdanost i predvidljivost za budući razvoj. Za postojeće Cordova projekte dostupni su vodiči za migraciju na Capacitor, što prelazak čini izvedivim.

---

## Izgradnja prve Ionic aplikacije

Ovaj odeljak objašnjava postupak za programere kako da započnu izradu Ionic aplikacije, uključujući postavljanje okruženja i pokretanje aplikacije.

### Preduslovi i postavljanje okruženja

Za optimalno iskustvo razvoja sa Ionicom, potrebno je instalirati nekoliko ključnih alata:

- **Node.js**: Preuzmite i instalirajte LTS (Long Term Support) verziju Node.js-a. Node.js je neophodan za interakciju sa Ionic ekosistemom i uključuje npm (Node Package Manager).
- **npm (Node Package Manager)**: Koristi se za instalaciju, nadogradnju ili deinstalaciju paketa. Važno je osigurati da je ispravno postavljen u varijablama okruženja.
- **Uređivač koda**: Preporučuje se Visual Studio Code zbog odlične podrške za web razvoj i dostupnih proširenja za Ionic.
- **Ionic CLI**: Instalirajte Ionic Command Line Interface globalno koristeći npm: `npm install -g @ionic/cli native-run cordova-res`. Paketi `native-run` i `cordova-res` korisni su za nativni razvoj i generisanje resursa.
- **Nativni SDK-ovi** (opciono za testiranje na uređajima): Za izgradnju i pokretanje na stvarnim uređajima potrebni su odgovarajući platformski SDK-ovi (npr. Android SDK za Android razvoj, Xcode za iOS razvoj na Macu).

### Kreiranje novog Ionic projekta

Nakon što su preduslovi ispunjeni, novi Ionic projekat može se brzo inicijalizovati:

1. Otvorite terminal i navigirajte do željenog direktorijuma za projekat.
2. Koristite naredbu `ionic start` za kreiranje novog Ionic projekta. Ova naredba omogućava specificiranje naziva projekta, početnog predloška i JavaScript okvira (Angular, React, Vue) koji želite koristiti, uz integraciju Capacitatora za nativnu funkcionalnost.

   - Primer za Angular: `ionic start photo-gallery tabs --type=angular --capacitor`
   - Primer za React: `ionic start photo-gallery tabs --type=react --capacitor`

   Predložak "tabs" je uobičajen izbor, pružajući tri unapred izgrađene stranice i najbolje prakse za Ionic razvoj.

3. Nakon kreiranja projekta, promenite radni direktorijum u novostvorenu mapu aplikacije: `cd photo-gallery`.

### Integracija Capacitatora za nativnu funkcionalnost

Capacitor koristi dodatke za apstrahovanje složenih nativnih funkcionalnosti u jedinstven JavaScript API, što pojednostavljuje cross-platform razvoj.

1. Instalirajte osnovne Capacitor dodatke za uobičajene nativne funkcionalnosti:  
   `npm install @capacitor/camera @capacitor/preferences @capacitor/filesystem`
2. Za web-baziranu funkcionalnost i UI koje pružaju određeni Capacitor dodaci (poput Camera API-ja), instalirajte Ionic PWA Elements biblioteku:  
   `npm install @ionic/pwa-elements`
3. Uvezite `defineCustomElements` iz `@ionic/pwa-elements/loader` u glavnu ulaznu tačku vaše aplikacije (npr. `src/main.ts` za Angular ili `src/main.tsx` za React) i pozovite `defineCustomElements(window);` pre pokretanja aplikacije.

### Pokretanje i testiranje aplikacije

- **Pokretanje u pregledniku**: Primarno razvojno okruženje za Ionic je web browser. Pokrenite aplikaciju koristeći:  
  `ionic serve`  
  Ova naredba pokreće aplikaciju u vašem web pregledniku, omogućavajući brz razvoj i testiranje. Ionic CLI ima funkciju Live Reload, što znači da se sve promene odmah odražavaju u pregledniku. Takođe možete koristiti `ionic serve -l` za pregled aplikacije u Ionic Labu, koji pruža usporedni prikaz iOS i Android prikaza.

- **Izgradnja za nativne platforme**:

  - Dodavanje projekata nativnih platformi:  
     `ionic capacitor add android` ili `ionic capacitor add ios`
  - Sinhronizacija web resursa sa nativnim projektima:  
     `ionic capacitor sync`
  - Izgradnja nativne aplikacije:  
     `ionic capacitor build android` ili `ionic capacitor build ios`
  - Pokretanje na uređaju ili emulatoru:  
     `ionic capacitor run android` ili `ionic capacitor run ios`
  - Otvaranje nativnog projekta u njegovom IDE-u:  
     `ionic capacitor open android` ili `ionic capacitor open ios`

- **Stvaranje produkcijske verzije**:  
  Za implementaciju, stvorite optimizovanu produkcijsku verziju vaših web resursa:  
  `ionic build --prod`  
  Ova naredba kompilira vaš web kod u folder `www`, koji Capacitor zatim kopira u nativne projekte.

### Osnovna struktura aplikacije i korišćenje komponenti

Ionic projekti obično prate standardnu strukturu web aplikacije, često nalikujući Angular, React ili Vue projektima, u zavisnosti od odabranog okvira. Ključne datoteke uključuju `src/index.html` (glavna ulazna tačka), `src/main.ts/tsx` (inicijalizacija aplikacije) i datoteke komponenti unutar `src/app/` ili `src/pages/`.

Ionic pruža bogat skup UI komponenti (npr. `<ion-header>`, `<ion-toolbar>`, `<ion-title>`, `<ion-content>`, `<ion-fab>`, `<ion-icon>`) koje pojednostavljuju razvoj korisničkog interfejsa i automatski se prilagođavaju stilovima platforme. Programeri primarno rade unutar HTML, CSS i TypeScript/JavaScript datoteka ovih komponenti, koristeći Ionicovu biblioteku komponenti za izgradnju korisničkog interfejsa i logike aplikacije.
