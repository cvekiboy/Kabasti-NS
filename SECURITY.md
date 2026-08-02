# Security Policy / Безбедносна политика / Bezbednosna politika / Biztonsági irányelvek / Bezpečnostná politika

Select your language / Изаберите језик / Izaberite jezik / Válasszon nyelvet / Vyberte si jazyk:
* [🇷🇸 Српски (Ћирилица)](#српски-ћирилица)
* [🇷🇸 Srpski (Latinica)](#srpski-latinica)
* [🇭🇺 Magyar](#magyar)
* [🇸🇰 Slovak](#slovak)
* [🇬🇧 English](#english)

---

## Српски (Ћирилица)

### Подржане верзије
Безбедносне исправке се активно обезбеђују за следеће верзије софтвера:

| Верзија | Подржано |
| ------- | -------- |
| v0.1.x  | ✅ Да    |

### Архитектура и безбедносни профил
Kabasti-NS је пројектован као потпуно независна апликација која ради у офлајн режиму.
* **Без серверске базе:** Главна апликација не поседује екстерне мрежне АПИ сервисе, базе података корисника, форме за регистрацију нити механизме за праћење.
* **Локална обрада података:** Све географске векторске мапе (.pmtiles) и распореди (GeoJSON) извршавају се потпуно изоловано (sandboxed) унутар локалне меморије самог уређаја корисника.
* **Безбедност меморије:** Позадинско окружење је компајлирано помоћу високо оптимизованог и меморијски безбедног {РЕДИГОВАНО} компајлера, чиме се елиминишу уобичајени пропусти у вези са нарушавањем меморије (memory corruption exploits).

### Пријава безбедносних пропуста
Уколико откријете критичан безбедносни проблем (као што је заобилажење безбедности меморије на клијентској страни, небезбедан приступ локалним системским директоријумима или пропусти у интегритету пакета), молимо вас да то пријавите одговорно:
1. **Немојте отварати јавне GitHub теме (Issues) за критичне безбедносне пропусте.**
2. Пошаљите детаљан извештај директно издавачу на: 👉 **kabasti-ns &#64; proton . me**
3. Молимо вас да укључите кораке за репродукцију пропуста, као и детаље о вашем оперативном систему (верзија Windows-а / Android-а).
4. Првобитни одговор ћете добити у року од 48 сати ради координације објављивања безбедносне исправке.

### Опсег јавног репозиторијума за преводе
Уколико приметите проблем у вези са open-source оквиром за локализацију или преводима који се налазе на нашем јавном [**Updates репозиторијуму**](https://github.com/cvekiboy/Kabasti-NS.updates):
* И даље можете приватно пријавити структуралне експлоите путем имејла.
* Обичне штампарске грешке или недостајући делови текста **нису** безбедносне претње. Молимо вас да њих исправите отварањем Pull Request-а директно на Updates репозиторијуму.

---

## Srpski (Latinica)

### Podržane verzije
Bezbednosne ispravke se aktivno obezbeđuju za sledeće verzije softvera:

| Verzija | Podržano |
| ------- | -------- |
| v0.1.x  | ✅ Da    |

### Arhitektura i bezbednosni profil
Kabasti-NS je projektovan kao potpuno nezavisna aplikacija koja radi u oflajn režimu.
* **Bez serverske baze:** Glavna aplikacija ne poseduje eksterne mrežne API servise, baze podataka korisnika, forme za registraciju niti mehanizme za praćenje.
* **Lokalna obrada podataka:** Sve geografske vektorske mape (.pmtiles) i rasporedi (GeoJSON) izvršavaju se potpuno izolovano (sandboxed) unutar lokalne memorije samog uređaja korisnika.
* **Bezbednost memorije:** Pozadinsko okruženje je kompajlirano pomoću visoko optimizovanog i memorijski bezbednog {REDIGOVANO} kompajlera, čime se eliminišu uobičajeni propusti u vezi sa narušavanjem memorije (memory corruption exploits).

### Prijava bezbednosnih propusta
Ukoliko otkrijete kritičan bezbednosni problem (kao što je zaobilaženje bezbednosti memorije na klijentskoj strani, nebezbedan pristup lokalnim sistemskim direktorijumima ili propusti u integritetu paketa), molimo vas da to prijavite odgovorno:
1. **Nemojte otvarati javne GitHub teme (Issues) za kritične bezbednosne propuste.**
2. Pošaljite detaljan izveštaj direktno izdavaču na: 👉 **kabasti-ns &#64; proton . me**
3. Molimo vas da uključite korake za reprodukciju propusta, kao i detalje o vašem operativnom sistemu (verzija Windows-a / Android-a).
4. Prvobitni odgovor ćete dobiti u roku od 48 sati radi koordinacije objavljivanja bezbednosne ispravke.

### Opseg javnog repozitorijuma za prevode
Ukoliko primetite problem u vezi sa open-source okvirom za lokalizaciju ili prevodima koji se nalaze na našem javnom [**Updates repozitorijumu**](https://github.com/cvekiboy/Kabasti-NS.updates):
* I dalje možete privatno prijaviti strukturalne eksploite putem imejla.
* Obične štamparske greške ili nedostajući delovi teksta **nisu** bezbednosne pretnje. Molimo vas da njih ispravite otvaranjem Pull Request-a direktno na Updates repozitorijumu.

---

## Magyar

### Támogatott verziók
A biztonsági frissítések aktívan biztosítottak a következő szoftververziókhoz:

| Verzió  | Támogatott |
| ------- | ---------- |
| v0.1.x  | ✅ Igen    |

### Architektúra és biztonsági profil
A Kabasti-NS egy teljesen független, offline működésű alkalmazásként lett kifejlesztve.
* **Nincs felhőalapú háttérrendszer:** A központi alkalmazás nem rendelkezik távoli webes API-kkal, külső felhasználói adatbázisokkal, regisztrációs űrlapokkal vagy követési mechanizmusokkal.
* **Helyi adatfeldolgozás:** Minden földrajzi vektoros térkép (.pmtiles) és menetrend (GeoJSON) teljesen izoláltan (sandboxed) fut a felhasználó eszközének helyi memóriájában.
* **Memóriabiztonság:** A háttérrendszer a rendkívül optimalizált és memóriabiztos {SZERKESZTETT} fordítóval van lefordítva, ami kiküszöböli a gyakori memóriasérülési réseket (memory corruption exploits).

### Sebezhetőség bejelentése
Amennyiben kritikus biztonsági problémát észlel (például kliensoldali memóriabiztonsági hibák, nem biztonságos helyi könyvtár-hozzáférés vagy csomagintegritási hibák), kérjük, felelősségteljesen jelentse be:
1. **Kérjük, ne nyisson nyilvános GitHub Issues-t a kritikus biztonsági sebezhetőségekhez.**
2. Küldjön részletes jelentést közvetlenül a kiadónak az alábbi elérhetőségre: 👉 **kabasti-ns &#64; proton . me**
3. Kérjük, mellékelje a sebezhetőség reprodukálásának lépéseit, valamint a futtató környezet részleteit (Windows / Android verzió).
4. Az első választ 48 órán belül megkapja a biztonsági javítás koordinálása érdekében.

### A nyilvános fordítási tárhely (repository) hatóköre
Amennyiben a nyilvános [**Updates adattárunkon**](https://github.com/cvekiboy/Kabasti-NS.updates) található nyílt forráskódú lokalizációs keretrendszerrel vagy fordítási elemekkel kapcsolatban észlel problémát:
* A strukturális biztonsági hibákat továbbra is e-mailben, bizalmasan jelentheti.
* Az egyszerű gépelési hibák vagy hiányzó szövegek **nem** jelentenek biztonsági kockázatot. Kérjük, ezeket egy közvetlenül a Updates tárhelyen megnyitott Pull Request segítségével javítsa ki.

---

## Slovak

### Podporované verzie
Bezpečnostné aktualizácie sa aktívne poskytujú pre tieto línie vydaní:

| Verzia  | Podporované |
| ------- | ----------- |
| v0.1.x  | ✅ Yes      |

### Architektonický a bezpečnostný profil
Aplikácia Kabasti-NS je navrhnutá ako plne nezávislá aplikácia fungujúca primárne v režime offline.
* **Žiadne cloudové backendy:** Jadro aplikácie neobsahuje žiadne vzdialené webové API, externé databázy používateľov, registračné formuláre ani mechanizmy sledovania. 
* **Lokálne spracovanie dát:** Všetky geografické vektorové mriežky (.pmtiles) a harmonogramy (GeoJSON) fungujú v úplne izolovanom prostredí (sandboxe) v rámci lokálnej pamäte klientskeho zariadenia.
* **Bezpečnosť pamäte:** Základné prostredie obalu je kompilované s vysoko optimalizovaným, pamäťovo bezpečným {UTAJENÉ} kompilátorom, čím sa eliminujú bežné chyby poškodenia pamäte.

### Nahlásenie zraniteľnosti
Ak objavíte kritický bezpečnostný problém (napríklad obídenie bezpečnosti práce s pamäťou na strane klienta, nezabezpečený prístup k súborom v lokálnych adresároch alebo nedostatky v integrite balíkov), nahláste ho, prosím, zodpovedným spôsobom:
1. **Nevytvárajte verejné hlásenia (Issues) na GitHub-e pre kritické bezpečnostné zraniteľnosti.**
2. Pošlite podrobnú správu priamo vydavateľovi na adresu: 👉 **kabasti-ns &#64; proton . me**
3. Prosím, uveďte kroky na zopakovanie zneužitia (exploitu) spolu s podrobnosťami o vašom runtime prostredí (verzia systému Windows / Android).
4. Prvotnú odpoveď dostanete do 48 hodín s cieľom skoordinovať proces vydania bezpečnostnej opravy.

### Rozsah verejného úložiska prekladov
Ak zaznamenáte problém týkajúci sa open-source lokalizačného rámca alebo prekladových súborov umiestnených v našom verejnom [**úložísku aktualizácií**](https://github.com/cvekiboy/Kabasti-NS.updates):
* Zneužitia štruktúry systému môžete naďalej nahlasovať súkromne e-mailom.
* Bežné preklepy alebo chýbajúce textové reťazce **nepredstavujú** bezpečnostnú hrozbu. Tie, prosím, opravte vytvorením žiadosti o zlúčenie (Pull Request) priamo v úložisku Updates.

---

## English

### Supported Versions
Security updates are actively provided for the following release tracks:

| Version | Supported |
| ------- | --------- |
| v0.1.x  | ✅ Yes    |

### Architecture & Security Profile
Kabasti-NS is engineered as a fully independent, offline-first application. 
* **Zero Cloud Backends:** The core application features no remote web APIs, external user databases, registration forms, or tracking mechanics. 
* **Local Data Ingestion:** All geographical vector grids (.pmtiles) and schedules (GeoJSON) run completely sandboxed inside the client device's local memory footprint.
* **Memory Safety:** The core wrapper environment is compiled with the highly optimized, memory-safe {REDACTED} compiler backend, eliminating common memory corruption exploits.

### Reporting a Vulnerability
If you discover a security-critical issue (such as client-side memory safety bypasses, insecure local directory file access, or package integrity flaws), please report it responsibly:
1. **Do not open public GitHub Issues for critical security exploits.**
2. Send a detailed report directly to the publisher at: 👉 **kabasti-ns &#64; proton . me**
3. Please include steps to reproduce the exploit, along with your runtime environment details (Windows / Android version).
4. You will receive an initial response within 48 hours to coordinate a patched security release pipeline.

### Public Translation Repository Scope
If you notice an issue regarding the open-source localization framework or translation assets hosted on our public [**Updates Repository**](https://github.com/cvekiboy/Kabasti-NS.updates):
* You may still report structural exploits privately via email.
* Simple typographical errors or missing text strings are **not** security threats. Please fix those by opening a Pull Request directly on the Updates repository.


