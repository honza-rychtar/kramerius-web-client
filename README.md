Digitální knihovna
==================
http://www.digitalniknihovna.cz

Webové rozhraní systému [Kramerius](https://github.com/ceskaexpedice/kramerius)
## Novinky
### Verze 0.4.5 (18.3.2017)
* Možnost získat výřez obrázku v plném rozlišení
* Zobrazení zdrojové knihovny v podrobnostech
* Zobrazení čísla otevřené strány z celkového počtu v seznamu stránek
* Podrobnější informace o otevřené straně v podrobnostech
* Drobné opravy zobrazení v podrobnostech

### Verze 0.4.4 (8.3.2017)
* Oprava problému načítání aplikace s aktivním AdBlockem

### Verze 0.4.3 (5.3.2017)
* Povinné vyplnění zprávy u zpětné vazby a volitelné vyplnění emailu

### Verze 0.4.2 (18.12.2016)
* Oprava chybějících údajů o ročníku a čísle periodika

### Verze 0.4.1 (12.12.2016)
* Drobné opravy v překladech

### Verze 0.4.0 (9.12.2016)
* Zobrazení roku a data vydání na kartách u fulltextového vyhledávání v periodiku
* Korekce německého překladu

### Verze 0.3.9 (29.11.2016)
* Nová prohlížečka PDF dokumentů
* Opravy menších chyb

### Verze 0.3.8 (12.10.2016)
* Optimalizace prohlížečky
* Přesun tlačítek PDF, JPEG, TXT do toolbaru
* Příprava k tisku

### Verze 0.3.7 (6.10.2016)
* Optimalizace vykreslování

### Verze 0.3.6 (23.8.2016)
* Kopírování odkazů do schránky přes tlačítko
* Oprava kopírování odkazů přes označení ve Firefoxu

### Verze 0.3.5 (22.8.2016)
* Oprava menších chyb

### Verze 0.3.4 (11.8.2016)
* Formulář pro odeslání zpětné vazby

### Verze 0.3.3 (13.5.2016)
* Jiný způsob načítání ročníků, čísel a příloh periodika
  - Datum vydání čísla periodika je nyní i tam, kde dříve nebylo
  - Zařazení příloh mezi čísla podle data
* Zobrazení ikony u náhledu stránky přílohy a popisek u stránky v metadatech přílohy v prohlížečce

### Verze 0.3.2 (11.5.2016)
* Relevantnější uspořádání výsledků hledání
* Relevantnější nálezy v našeptávači
* Zobrazení příloh
  - Stránky příloh v knihách, číslech periodika, hudebninách (a dalších) se zobrazují v seznamu stránek
  - Přílohy ročníků periodika se zobrazuji v seznamu čísel periodika

### Verze 0.3.1 (17.4.2016)
* Sdílení poznámek
  - Při vytváření a editaci poznámy se v dialogu generuje odkaz poznámky, který je možné někomu poslat nebo si ho uložit
  - Otevřením odkazu dojde k načtení vybrané stránky vybraného dokumenty, do které se přidá poznámka
* Přesun zámečků nad náhled na kartách
* Oprava vyhodnocení odkazu s fulltextem v prohlížečce
* Odtranění typu stránky z prodrobností
* Zobrazení čísla a názvu části v podrobnostech
* U dvoustran se stáhne obrázek a textový přepis pro obě strany
* Úprava a lokalizace textu s vyvětlením neveřejného dokumentu

### Verze 0.3.0 (9.4.2016)
* Oprava německého překladu
* Odkazy na sociální sítě
* Použití Noviny a časopisy místo Noviny

### Verze 0.2.9 (30.3.2016)
* Lokalizace
  - Internacionalizace celé aplikace
  - Lokalizace do češtiny, slovenštiny, angličtiny a němčiny
  - Výběr jazyka přes toolbar
  - Lokalizace kódových polí: jazyk, sigla, role autora, typ stránky
  - Výchozí jazyk se nastavuje v konfiguračním souboru aplikace (zde je to čeština)
* Povolena možnost mít ve vybraných stránky
* Zjednodušení dialogu pro generování PDF
* Nový vzhled tlačítek
* Nový vzhled šoupátka
* Odstranění nevhodných znaků v názvech a datech na kartách
* Více informací o ročníku v metadatech v prohlížečce
* Oprava nemožnosti zoomovat první stránku při otevření prohlížečky z fulltextu
* Oprava nefunkční šipky zpět v prohlížeči při otevření stránky přes persistentní link
* Oprava nutnosti dvojího kliku na zpět v prohížeči u otevření prohlížečky a návratu zpět
* Oprava špatného hlavního názvu pokud je relatedItem před hlavním názvem
* Tlačítko pro otevření dialogu s informacemi o autorech v metadatech se zobrazí vždy (pokud je alespoň jeden autor)

### Verze 0.2.8 (14.3.2016)
* Více responzivní design
  - Na telefonu se skryje většina panelů (metadata, kategorie procházení, fasety, náhledy, ...)
  - Toto je dočasné řešení, tak aby se aplikace na telefonu vhodně zobrazovala, i když zatím s omezenou funkcionalitou
  - Výchozí preference dvoustránkového zobrazení se zapne jen při šířce alespoň 1400px (lze přepnout)
  - Při šířce menší než 920px se při otevření prohlížečky schová panel s náhledy (lze zobrazit)
  - Při hodně malé šířce (telefon) se skryje panel s náhledy, metadaty a ovládacími prvky (trvale)
  - U hudebního přehrávače se při snižování šířky prohlížeče postupně skrývaji prvky
* Nový progress bar
* Zobrazení typu dokumentu v metadatech
* Změna výchozí kategorie u procházení na typ dokumentu
* Přesun hřebtu knihy na konec seznamu stránek
* Page title obsahuje vybranou knihovnu
* Oprava nedočítání náhledů po zrušení fulltextu
* Oprava navrácení z prohlížečky do vyhledávaání na správný dotaz
* Přidání partName do metadat

### Verze 0.2.7 (4.3.2016)
* Oprava nedočítání dat v hledání a procházení u velkého rozlišení obrazovky
* Zobrazení hlášky pokud v hledání nebo procházázení není nalezen žádný výsledek
* Hledat z hlavního menu vede do vyhledávání bez filtru, s filtrem na veřejné dokumenty se dá dostat přes Zobrazit více u Veřejně dostupných novinek
* Zobrazení obrázku zvukové nahrávky v hodubním přehrávači, pokud nejsou k dispozici žádné stránky, z nichž by se náhled použil
* Nezalamování textů v hudebním přehrávači
* Oprava menších chyb v zobrazení

### Verze 0.2.6 (2.3.2016)
* Změna hlavní obrazovky
  - Označeno jako Domů místo Doporučené
  - Zobrazují se vybrané (Mohlo by se vám líbit) i nejnovější (Veřejně dostupné novinky), které jsou filtrovány jen na public
  - Zobrazí se nějaký obsah i knihovnám, které nemají nastaveny vybrané
  - Vybrných se zobrazí maximalně 3 řádky, další se zobrazí po kliku na Zobrazit více
  - Kliknutím na Zobrazit více u nejnovějších se přejde do vyhledávací obrazovky s filtrem na veřejné dokumenty seřazeny od nejnovějších (bývalo v hlavním menu jako Novinky)
* Změna hlavního menu
  - Rozděleno na 2 sekce
  - Domů, Sbírky a Informace zůstavají na hlavní obrazovce s hlavním menu a mění obsah
  - Hledat a Procházet přejdou do obrazovky vyhledáváni a procházení
* Změna procházení
  - Zahozena obrazovka s výběrem podle čeho procházet
  - Přejde se rovnou do obrazovky procházení, kde se dá zvolit podle čeho procházet
  - V obrazovce procházení přibylo procházet podle typu dokumentu, které bylo předtím zvlášť

### Verze 0.2.5 (28.2.2016)
* Přesnější vyhledávání podle roku - pokud není v datech rok, tak se použije průnik zadaného intervalu s intervalem [datum_begin, datum_end]
* Ve fasetech v hledání se už nescrolluje. Místo toho se zobrazí jen maximálně 8 výsledků a přes "Zobrazit více" se dočtou další výsledky, které lze zase přes "Zobrazit méně" schovat
* Zobrazení roku vydání pokud není uveden autor
* Změna zobrazení metadat - hodnoty jsou výraznější, uvození méně výrazné, údaje o periodikách jsou strukturovanější
* V hlavním menu je místo Novinky použito Hledat
* Drobné změny vzhledu faset u hledání a procházení, hlavního menu a změna fontu

### Verze 0.2.4 (27.2.2016)
* Počty výskytů typů dokumentu u fulltextového hledání
* Název aplikace (Digitální knihovna) v toolbaru jako link, aby přes něj šlo oteřít aplikaci v novém tabu

### Verze 0.2.3 (25.2.2016)
* Sdílení na sociálních sítích
* Generování persistentních url

### Verze 0.2.2 (24.2.2016)
* HTML5 mód
  - Url má nově tvar http://www.digitalniknihovna.cz/PATH/ místo původního http://www.digitalniknihovna.cz/#/PATH/
  - U starších prohlížeču, které nepodporují HTML5 history API, se použije hashbang mód, tzn url bude mít tvar http://www.digitalniknihovna.cz/#!/PATH/
* Responzivní rozložení karet u seznamu ročníků a čísel periodika
* U map a grafik se použije jednostránkové zobrazení jako výchozí
* Správné načtení posledních výsledků hledání po návratu zpět na výsledky hledání přes tlačítko zpět v toolbaru aplikace

### Verze 0.2.1 (20.2.2016)
* Automatické schovávání ovládacích prvků v prohlížečce
  - Při otevření prohlížečky jsou ovládací prvky zobrazené
  - Pokud po dobu tří sekund není pohyb kurzoru nad prohlížečkou, tak se ovládací prvky schovají
  - Při pohybu kurzorem nad prohlížečkou se schované ovladací prvky zase zobrazí
* 3 režimy v prohlížečce
  - Klasický režim prohlížení
  - Režim výběru textu na stránce (původně přes Shift)
  - Režim poznámek
* Poznámky v dokumentu
  - Do režimu poznámek se přejde z ovládacích prvků v prohlížečce
  - Označením oblasti na stránce se otevře dialog s novou poznámkou, kde se zvolí barva a text poznámky
  - Po vytvoření se vybraná oblast zvýrazní zvolenou barvou
  - Najetím kurzoru nad poznámku se dole v prohlížečce zobrazí text poznámky
  - Kliknutím na oblast se zobrazí dialog pro editaci poznámky, kde je možne změnit barvu nebo text anebo smazat poznámku
  - Poznámky se ukládají a při procházení aplikace a znovu navštívení stránky s poznámkama se poznámky zase načtou.
  - Poznámky se ukládaji pouze lokálně pro jednu návštěvu aplikace. Zavřením aplikace, refreshem stránky apod. se poznámky ztratí.

### Verze 0.2.0 (14.2.2016)
* Fulltextové vyhledávnání v periodikách a ročnících periodika
  - Stejně jako u hledání v dokumentu přes vyhledávácí pole s našeptávačem v metadatech
  - Vyhledávat lze v celém periodiku nebo jen v konkrétním ročníku
  - Výsledky vyhledávaní se zobrazí jako seznam stránek s kontextem seřazený podle data
  - Hledaný řetězec se propaguje do všech vrstev procházení periodika, dokud se nezruší ve vyhledávacím poli
  - Při vstupu do prohlížečky se stránkama čísla periodika, posunu na předchozí/další číslo, posunu na předchozí/další ročník, při návratu na seznam čisel a seznam ročníku
* Zrušení přepočtu rozměrů obrázků u dvoustránek
  - U Zoomify je nutné zadat přesné rozměry, jejich přepočtem docházi k artefaktům
  - Teď se u dvoustránky zobrazí obrázky správně, ale nesedí k sobě přesně na výšku
* Schování/zobrazení panelu s metadaty v hudebním přehrávači
* Oprava scollování v metadatech
* Oprava scollování výběru knihovy ve Firefoxu

### Verze 0.1.9 (13.2.2016)
* Zobrazení náhledu a autorů v našeptávači

### Verze 0.1.8 (12.2.2016)
* Fullscreen aktivuje úplný fullscreen prohlížečky
* Schování/zobrazení panelu s náhedy a metadaty zvlášť

### Verze 0.1.7 (10.2.2016)
* Články a vnitřní části
  - Pokud dokument obsahuje články, tak se v prohlížečce u panelu s náhledy zobrazí tab články, pod kterým je seznam názvů článku. Po rozkliku se prohlížečka omezí jen na stránky vybraného článku
  - To stejné pro vnitřní části (v klientovi pojmenovány kapitoly)
* Možnost přepínat mezi jednostránkovým a dvoustránkovým zobrazením
* Výběr textu z dvoustrany
  - Zatím nelze přes obě strany zároveň, buď jen z pravé nebo jen z levé
* Tlačítka pro přechod na předchozí/další stránku jen pokud je předchozí/další stránka dostupná
* Přidání rozsahu, měřítka a souřadnic do metadat

### Verze 0.1.6 (6.2.2016)
* Dvoustránkové zobrazení

### Verze 0.1.5 (6.1.2016)
* Fit-to-screen vycentrování/zoomování obrázku v prohlížečce
* Jemné zoomování kolečkem myši
* Podpora periodik bez čísel
  - Pro ročníky periodik, které pod sebou mají rovnou stránky
  - Stránky pro takovýto ročník jsou sbaleny do uměle vytvořeného čísla
  - Pokud ročník obsahuje čísla i stránky, pak se čísla zobrazí klacicky a pro stránky je vytvořeno nové číslo
* Další knihovny (celkem 21 knihoven)

### Verze 0.1.4 (13.9.2015)
* Nový systém procházení
  - Řazení abecedně nebo podle výskytu
  - Filtr podle dostupnosti
  - Zobrazení v mřížce nebo seznamem
  - Rychlá změna kategorie procházení
  - Nekonečný seznam
* Zpráva v seznamu sbírek pokud digitální knihovna žádnou neobsahuje
* Zobrazení jen unikátních výsledků v našeptávači

### Verze 0.1.3 (11.9.2015)
* Možnost použití virtuální sbírky jako zdroje dat
* Oprava fulltextového hledání s uvozovkama
* Všechny typy stran

### Verze 0.1.2 (8.9.2015)
* Zobrazení maximálně dvou autorů a jednoho vydavatele v metadatech. Možnost zobrazit vše v dialogu s podrobnostmi o autorech/vydavatelích
* Rychlejší načítání a lepší zobrazení kontextu fulltextového hledání v periodikách. Nyní se kontext zobrazí i u neveřejných dokumentů
* Podpora monographunit
* Přidání abstraktu a obsahu do metadat
* Oprava chybného zobrazení dlouhých textu v dialozích
* Oprava chybného zobrazení dlouhých čísel stránek v náhledech

### Verze 0.1.1 (28.8.2015)
* Fulltextové vyhledávnání jako součást výsledků hledání
* Použité filtry ve vyhledávání - možnost zrušit vše nebo každý zvlášť

### Verze 0.1.0 (24.8.2015)
* Nový systém vyhledávání
* Postupné dočítání ročníků a čísel periodika
* Postupné dočítání náhledů stránek v prohlížečce
* Optimalizace vykreslování

### Verze 0.0.9 (30.7.2015)
* Oprava chybného označení aktivní položky v menu při přímem načtení stránky
* Novinky v aplikaci na vlastní stránce (pravě se na ní nacházíte)
* Zabalování a rozbalování dlouhých názvů a podnázvů v metadatech
* Klikatelná ikona lupy u vyhledávání - slouží jako tlačítko vyhledat
* Oprava špatného zobrazení čísla stránky v náhledu, pokud je uloženo jako pole

### Verze 0.0.8 (28.7.2015)
* Číslo a typ stránky u náhledů v prohlížečce
* Rozšíření panelu s metadaty v prohlížečce
  - Číslo a typ stránky
  - Ročník a číslo periodika
  - Navigace v periodiku
* Po zrušení hledání v dokumentu zůstane vybraná aktuální stránka
* Zobrazení vastního textu v obrazovce Informace (nastavitelné)
* Oprava našeptávače u hledání v dokumunetu
* Označení PDF dokumentu na kartách

### Verze 0.0.7 (1.7.2015)
* Nový hudební přehrávač
* Export do PDF
* Nový způsob zobrazení kontrolních prvků v prohlížečce
* Jiný vzhled talčítek pro přechod na předchozí/další stránku
* Nahlašování chyb
  - Bude fungovat až pro Krameria v5.1.2
* Dialog s informacemi pro nepřístupný dokument
* Stažení JPEG obrázku
* Více infomací o autorech
* Dialog s podrobnostmi o autorech a nakladatelských údajích
* Změna page title podle lokace v aplikaci
* Odstranění seznamu thumbnailů u pdf dokumentu
* Rozlišení typu dokumentu na kartě přes barevný tag
* Změna vzhledu aplikace
* Odstranění výběru světlého/tmavého tématu aplikace

### Verze 0.0.6 (24.5.2015)
* Lepší navigace v aplikaci
  - V prohlížečce se tlačítkem zpět v prohlížeči přechází správně na předchozí otevřené stránky
  - Klik na název 'Digitální knihovna' odkudkoli vede na hlavní stranku
  - Tlačítkem zpět vlevo nahoře se přejde o úroveň výš
* Navigace v ročnících periodika
  - Na obrazovce seznamu čísel ročníku periodika jsou v metadatech údaje o otevřeném ročníku a tlačítka pro přechod na předchozí/následující ročník a na seznam ročníků.
* Cachování
* Optimalizace responzivního vykreslování karet
* Zobrazení počtu zobrazených/nalezených výsledků u hledáni/sbírek/procházení
* Přihlášení uživatele
  - V této verzi nedostupné
  - Zpřístupnění pro testovací účely na požádání
* Ovládací prvky v prohlížečce
  - Přesunuto dospod obrazovky.
  - Defaultně viditelné.
  - Možnost panel schovat
  - volba se zapamatuje
  - panel se znovu zobrazí po najetí kurzorem na spodní okraj obrazovky.
* Lepší zobrazení tlačítek pro přechod na předchozí/následující stránku
* Uložení stavu přepínače 'Pouze veřejné'

### Verze 0.0.5 (8.5.2015)
* Vybraná knihovna součástá url.
  - Možnost odkazování na libovolný dokument libovolné knihovny.
* Anglická lokalizace
* Výběr jazyka
* Oprava zobrazovacích chyb na kartách periodika.

### Verze 0.0.4 (3.4.2015)
* Zobrazení JPEG a DjVu obrázků v OpenLayers prohlížečce.
  - Podpora zoomování.
  - Ovládací prvky (zoom, rotace, vyrovnání, zámeček)
  - Zvýraznění hledaného textu.
* Textový přepis celé stránky.
* Textový přepis vybrané části stránky.
* Našptávač u vyhledávání uvnitř dokumentu.
* Animace zoomu a rotace v prohlížečce.
* Místo uložení v metadatech (mapování sigly na názvy institucí).

### Verze 0.0.3 (25.3.2015)
* Vyhledávání podle názvu, autora, klíčových slov, identifikátorů.
* Autocomplete u hledání podle všeho, názvu, autora, klíčových slov, identifikátorů.
* Procházení podle jazyka, autora a klíčových slov.
* Oprava načítání PDF dokumentů.
* Stránka s informacemi o aplikaci.
* Seznam jazyků (namapovaných na české názvy) v metadatech.
* Varovná hlášení u chybějících nebo veřejně nepřístupných obrázků a pdf dokumentů.
* Oprava chyb.
