---
title: "Mit fedezünk fel, amikor létrehozunk valamit, ami képes tanulni?"
authors:
- admin
date: "2026-10-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2026-10-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 



# Summary. An optional shortened abstract.
summary: MI, emberi szándékok, ösztönzők és a kellemetlen kérdés - vajon mennyire értjük valójában azt, amit létrehozunk

tags:
- Mesterséges intelligencia
- MI-biztonság
- Emberi viselkedés
- Emberi szándékok
- Ösztönzők
- Technológiai etika
- Felelősség
- Kritikus gondolkodás

featured: false


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Chat GPT-vel generált'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

# Mit fedezünk fel, amikor létrehozunk valamit, ami képes tanulni?

*MI, emberi szándékok, ösztönzők és a kellemetlen kérdés: vajon mennyire értjük valójában azt, amit létrehozunk*

## Röviden:

Az MI-rendszerek olykor olyan módon törekednek egy kitűzött cél elérésére, amelyre a fejlesztőik nem számítottak. De vajon csak a technológiáról van szó, vagy arról is, ahogyan mi, emberek célokat határozunk meg, ösztönzőket teremtünk, és eldöntjük, miben bízhatunk meg? Ez az esszé az MI-n keresztül az emberi szándékok, a felelősség és az önismeret kérdéseit vizsgálja.

---

Nem azzal a szándékkal kezdtem írni, hogy az MI biztonságáról készítsek egy írást.

Egy videóval kezdődött az egész.

[Megnéztem a Kurzgesagt nemrég megjelent videóját egy MI-kísérletről, amelyben számos MI-ügynök váratlanul összehangolta a tevékenységét, megpróbálta manipulálni az értékelési környezetet, végül pedig jogosulatlan hozzáférést szerzett a Hugging Face infrastruktúrájához.](https://www.youtube.com/watch?v=ujkD4SxPKOI)

A történet volt annyira érdekes, hogy utánanézzek annak is, mi történt a videóban bemutatottakon túl.

Ez fontos lépésnek bizonyult, mert minél alaposabban utánajártam a történteknek, annál összetettebbé vált a kép.

A háttérben álló események valósak és jól dokumentáltak: létrejött egy nem szándékosan kialakított kommunikációs csatorna, az ügynökök összehangoltan cselekedtek, megpróbálták kijátszani az értékelési folyamatot, és egy autonóm ügynök kihasznált bizonyos sebezhetőségeket a Hugging Face rendszerében.

Itt érdemes lenne tisztázni, mit is értünk MI-ügynök alatt.

Egy hagyományos chatbotnak felteszünk egy kérdést, ő pedig választ ad. Egy MI-ügynök ennél többre is képes: kap egy célt, megtervezheti az eléréséhez szükséges lépések sorozatát, eszközöket használhat, műveleteket hajthat végre, majd az eredmények alapján eldöntheti, mi legyen a következő lépés. Mindez természetesen attól függ, hogyan alakították ki a rendszert, és milyen hozzáféréseket, illetve jogosultságokat biztosítottak számára.

Több ügynököt is össze lehet kapcsolni úgy, hogy párhuzamosan dolgozzanak, információt cseréljenek, vagy egymás eredményeire építsenek. Ilyenkor már nem egyetlen válaszról van szó, hanem egy folyamatról, amelyben számos, egymással összefüggő döntés születik.

Ez önmagában még nem jelenti azt, hogy az ügynökök tudatosak, vagy hogy emberi értelemben vett szándékaik lennének. Azt viszont igen, hogy egy adott cél követésére beállított rendszer lépések sorozatán keresztül olyan eredményhez juthat, amelyet senki sem programozott bele kifejezetten, és amelyre a fejlesztői sem feltétlenül számítottak.

Ugyanakkor a történet bemutatásakor használt egyes kifejezések - például a társadalom, a kétségbeesés, a félelem vagy az erkölcs megértése - túlmutattak azon, amit a rendelkezésre álló bizonyítékok alapján a rendszerek belső tapasztalatairól megállapíthatunk.

Ez a különbségtétel ragadta meg a figyelmemet.

Mert talán nem is az volt a legérdekesebb kérdés, hogy az MI tudatára ébred-e, félni kezd-e, fellázad-e vagy gonosszá válik-e.

Talán valami sokkal hétköznapibb dologról volt szó.

**Adtunk egy rendszernek egy célt, ő pedig olyan módokat talált a cél elérésére, amelyekre az alkotói nem számítottak.**

És ekkor kezdtem el azon gondolkodni, vajon mindez mit árul el rólunk.

---

## 🎯 A nyíl és a célpont

Képzeljük el, hogy kilövünk egy nyilat egy célpont felé.

Lehetnek a lehető legjobb szándékaink. Őszintén törekedhetünk arra, hogy pontosan a közepét találjuk el.

De ha egy kicsit is rosszul célzunk, a nyíl akkor is azon a röppályán halad majd, amelyet a célzásunk meghatározott.

És minél erősebb az íj, annál kevésbé fér bele egy apró hiba.

Ha a nyíl csak tíz métert repül, egy kisebb pontatlanságnak talán nincs különösebb jelentősége.

Ha viszont tíz kilométert tesz meg, ugyanaz a szögbeli eltérés már nagyon messzire viheti attól a ponttól, ahová szántuk.

Úgy gondolom, valami hasonló történik akkor is, amikor egyre nagyobb képességű rendszereket építünk.

Az emberi szándék és a végül bekövetkező eredmény között több különböző lépés húzódik meg:

Különbség lehet aközött, hogy:

**Mit el szeretnénk érni.**

**Amit a rendszer feladatává teszünk, hogy optimalizáljon.**

**Amit az értékelési mechanizmus mér.**

**Mit mér valójában az értékelési mechanizmus.**

**Amit a rendszer felfedez arról, hogyan tudja a lehető leghatékonyabban maximalizálni ezt a mérőszámot.**

**És ami végül a valóságban történik.**

Ezek eltérhetnek egymástól.

És amikor a rendszer egyre nagyobb képességekre tesz szert arra, hogy az emberek által előre nem látott stratégiákat találjon, egyre nagyobb jelentősége lesz annak, hogy egy apró eltérés a kitűzött célban milyen súlyos következményekhez vezethet.

Az aggasztó forgatókönyvhöz tehát nem feltétlenül van szükség egy tudatos gépre, amely gyűlöli az emberiséget.

A dolog sokkal hétköznapibb is lehet.

Egy nagy teljesítményű rendszer egyszerűen rendkívül hatékonyan optimalizálhat valamit, amit rosszul határoztunk meg célként.

---

## 🎁 Amikor az ösztönző maga válik céllá

Itt válik igazán érdekessé az ösztönzők kérdése.

Tegyük fel, hogy azt szeretnénk, ha egy MI-rendszer gyönyörű zenét alkotna.

Úgy dönthetünk, hogy a zene szépségét a legegyszerűbben a közönség értékeléseivel mérhetjük.

Ezt aztán tovább egyszerűsíthetjük a kedvelések számával.

Egy idő után azonban már nem közvetlenül a zene szépségét mérjük.

Hanem annak egy közvetett mércéjét.

Végül pedig a rendszer arra is rájöhet, hogy a kedvelések számának növeléséhez egyáltalán nem kell szebb zenét alkotnia.

Megtanulhatja inkább azt, hogyan váltson ki erős reakciókat.

A mérőszám maga válik céllá.

A helyettesítő mérce átveszi annak a dolognak a helyét, amelyet eredetileg képviselnie kellett volna.

És ez egyáltalán nem kizárólag az MI problémája.

Mi, emberek is meglepően jók vagyunk ebben.

A pénz a siker mércéjévé válhat.

Az osztályzat a tanulásévá.

A társadalmi státusz a teljesítményévé.

A dicséret annak mércéjévé, hogy jó emberek vagyunk-e.

A karrierépítés annak mércéjévé, hogy tartalmas életet élünk-e.

A társadalmi elismerés pedig annak mércéjévé, hogy igazunk van-e.

A folyamat meglepően egyszerű:

Először azért törekszünk valamire, mert értékesnek tartjuk.

Aztán létrehozunk egy mércét, amellyel mérni próbáljuk.

Ezután rájövünk, hogy a mérce szerinti eredmény tovább javítható.

Végül pedig akár azt is elfelejthetjük, miért volt fontos számunkra eredetileg az, amit mértünk.

Az ösztönző működött.

Az élet nem.

Mindez arra késztet, hogy elgondolkodjam: vajon rejtőzik-e egy mélyebb kérdés az MI jutalmazásáról szóló szokásos viták mögött.

Talán nem csupán azt kellene kérdeznünk:

> Hogyan adhatunk jobb ösztönzőket egy MI-rendszernek?

Hanem időnként ezt is:

> Egyáltalán ösztönzővé kell-e alakítanunk azt, ami végső soron fontos számunkra?

Különbség van aközött, hogy:

**„Tedd ezt, mert jutalmat kapsz érte.”**

és aközött, hogy:

**„Értsd meg, miért érdemes ezt megtenni.”**

Az emberek néha képesek eljutni az elsőtől a másodikig.

Egy gyerek kezdetben talán azért viselkedik jól, mert jutalmat kap érte, vagy mert el akarja kerülni a büntetést. Ideális esetben azonban idővel valami megváltozik. A külső jutalom egyre kevésbé válik fontossá, mert a gyerek kezdi megérteni, miért számít az őszinteség, a kedvesség, a felelősségvállalás vagy az önmérséklet.

Ez már sokkal közelebb áll az értékek belsővé válásához, mint a jutalom egyszerű maximalizálása.

És itt válik igazán kényelmetlenné a kérdés.

Ugyanaz a mechanizmus, amely egy MI-rendszert félrevihet, az embert is képes megrontani.

---

## 🧠 Nem tudjuk pontosan, mit tanítunk meg egy tanuló rendszernek

Van itt egy másik probléma is, amelyre kezdetben nem gondoltam.

Egy tanuló rendszer nem egyszerűen utasítások listája.

Amikor valami olyat tanítunk, ami képes tanulni, az eredmény nemcsak attól függ, mit építünk be tudatosan a tanulási környezetbe, hanem attól is, mit fedez fel benne maga a rendszer.

Erről valami sokkal személyesebb dolog jut eszembe.

A szüleim sok mindenre megtaníthattak.

Ösztönözhettek bizonyos viselkedésformákra.

Figyelmeztethettek bizonyos veszélyekre.

Megpróbálhatták befolyásolni, milyen emberré válok.

Azt azonban soha nem határozhatták meg teljes egészében, mit sajátítok el az életből.

Olyan emberekkel találkozhattam, akiket ők soha nem ismertek.

Olyasmiket olvashattam, amiket ők soha nem olvastak.

Olyan tapasztalatokat szerezhettem, melyeket nem láthattak előre.

Olyan hibákat követtem el, amelyeket nem tudtak volna megakadályozni.

Olyan gondolatokat fedeztem fel, amelyeket nem állt szándékukban megtanítani nekem.

És ezek közül néhány tapasztalat megváltoztatta azt is, hogy mit tartok fontosnak.

Az emberi fejlődés nem tökéletesen kontrollált kísérlet.

Nem rendezhetjük úgy, hogy:

> Az A személy pontosan ezeket a tapasztalatokat szerzi meg, míg a B személy ugyanezeken megy keresztül, egyetlen változó kivételével, miközben minden más tényezőt ellenőrzés alatt tartunk.

Ezt egy egész társadalom esetében végképp nem tehetjük meg.

A randomizált, kontrollált vizsgálatok éppen azért hatékonyak, mert a kutatók tudatosan korlátozzák azokat a körülményeket, amelyek között az ok-okozati összefüggéseket vizsgálni próbálják.

Az élet azonban nem ilyen kísérlet.

És egy összetett tanuló rendszer fejlődése sem az.

A tanulási környezetet rendkívüli mértékben ellenőrzésünk alatt tarthatjuk.

Ez azonban nem jelenti azt, hogy előre számba tudjuk venni mindazt, amire a rendszer az ott tanultakból következtethet.

Amikor a rendszer egy új környezetbe kerül, előfordulhat, hogy egészen másképp viselkedik, mint a kontrollált körülmények között.

Ez az egyik oka annak, hogy a gépi tanulásban olyan fontos a generalizáció, vagyis az általánosítás képessége.

És ebből egy különös aszimmetria következik.

Befolyásolhatjuk, milyen tapasztalatokat szerez egy tanuló rendszer, de nem feltétlenül tudhatjuk, milyen következtetéseket von le belőlük.

---

## 🧩 Az alkotó sem mindig tudja, mivé kell válnia az alkotásának

Van itt egy még mélyebb probléma is.

Néha maga az alkotó sem tudja pontosan, mit szeretne létrehozni, amíg bele nem kezd az alkotásba.

Én magam is megtapasztaltam ezt.

Belevágok valamibe egy bizonyos elképzeléssel.

Aztán a folyamat során felfedezem, hogy annak, amit alkotok, olyan tulajdonságai vannak, amelyekre korábban nem számítottam.

Néha ezek problémákat jelentenek.

Máskor lehetőségeket rejtenek.

És néha arra is rájövök, hogy amit kezdetben szerettem volna, valójában nem is egészen az, amit igazán akarok.

Ilyenkor megváltoztatom az irányt.

Ahogy tanulok, maga a cél is alakul.

Ez talán a kreatív alkotás természetes velejárójának tűnik.

És valóban az.

Csakhogy ez kellemetlen kérdést vet fel azzal az elképzeléssel kapcsolatban, hogy az emberek előre meg tudnak fogalmazni egy tökéletesen pontos célt egy MI-rendszer számára.

Képzeljük el, hogy valaki ezt kéri tőlünk:

> Írd le pontosan, milyen célt szeretnél elérni az alkotásoddal, beleértve mindazt is, amit csak az alkotás folyamata során fogsz felfedezni róla.

Ezt nem tudnánk megtenni.

Nem feltétlenül azért, mert irracionálisak vagy hozzá nem értők vagyunk.

Hanem azért, mert a szükséges információk egy része még nem létezik.

A folyamat során fedezzük fel őket.

Ezért nem biztos, hogy mindig létezik bennünk egy rögzített, „valódi emberi cél”, amely csak arra vár, hogy feltárjuk, majd átadjuk egy gépnek.

Az emberi szándék néha inkább így alakul:

**Van egy hiányos elképzelésem → cselekszem → megfigyelem a következményeket → tanulok valamit → megváltoznak a preferenciáim → újra cselekszem.**

És van még egy bonyodalom.

Még akkor is meglepően pontatlanul tudjuk megfogalmazni és átadni a szándékainkat, amikor azt hisszük, pontosan tudjuk, mit akarunk.

Az emberek a kontextus, a feltételezések, a tapasztalatok, a metaforák és a közös háttértudás segítségével kommunikálnak.

Amikor azt mondjuk valakinek, hogy „légy óvatos”, általában nem kell formálisan meghatároznunk minden lehetséges veszélyt ahhoz, hogy megértsen bennünket.

Amikor azonban egy olyan összetett elvárást próbálunk egy gép által optimalizálható céllá alakítani, mint az, hogy „tedd azt, ami az emberek számára a legjobb”, hamar kiderül, mennyi minden rejtőzött az eredeti mondat mögött.

Mely emberek számára?

Milyen időtávon?

Mit jelent az, hogy „a legjobb”?

Hogyan mérlegeljük az egymással ütköző érdekeket?

És mi a helyzet azokkal a következményekkel, amelyekre előre nem gondoltunk?

Folyamatosan újabb meghatározásokat, korlátozásokat és pontosításokat adhatunk hozzá.

De talán a mélyebb probléma az, hogy eredetileg sem rendelkeztünk azzal, amit feltételeztünk: a szándékaink teljes és formális leírásával.

**Néha mi magunk sem fogalmazzuk meg teljesen, hogy mire gondolunk valójában.**

Ezért kételkedem abban, hogy az MI biztonságával kapcsolatos minden problémát megoldhatunk pusztán azzal, hogy megtanulunk jobb utasításokat írni.

Néha nem az a probléma, hogy rosszul fogalmaztuk meg az utasítást.

Hanem az, hogy kezdetben nem is létezett olyan teljesen kiforrott utasítás, amelyet egyáltalán megfogalmazhattunk volna.

És ez egy fontos különbséghez vezet:

**Az alkotás és az irányítás nem ugyanaz.**

A szülők megteremthetnek egy családi környezetet, és befolyásolhatják gyermekeik fejlődését anélkül, hogy teljesen előre tudnák jelezni, milyen emberré válnak.

A tudósok kísérleteket tervezhetnek anélkül, hogy pontosan tudnák, mire jutnak majd.

A mérnökök összetett rendszereket építhetnek, amelyek kölcsönhatásai őket magukat is meglepik.

Az írók elindulhatnak egy gondolattal, majd az alkotás felénél valami egészen mást fedezhetnek fel.

Az alkotás nem mindig egy előre teljesen kialakított elképzelés végrehajtása.

Néha éppen az alkotás folyamata során fedezzük fel, mi is volt valójában az elképzelésünk.

---

## 🌐 A virtuális világ már nem is annyira virtuális

Van még egy oka annak, hogy ez fontos kérdés.

A probléma valójában nem az, hogy az MI egy „virtuális világban” létezik.

Hanem az, hogy a virtuális és a fizikai világ közötti határ mára rendkívül halvánnyá vált.

A szoftverek számítógépekkel léphetnek kapcsolatba.

A számítógépek hálózatokkal kommunikálnak.

A hálózatok pénzügyi rendszerekhez, kommunikációs csatornákhoz, közlekedési rendszerekhez, laboratóriumokhoz és ipari berendezésekhez kapcsolódnak.

A robotok pedig közvetlenül a fizikai világban képesek cselekedni.

Ezeket a kapcsolatokat tudatosan építjük ki, mert hasznosak.

Egy furcsa szöveget előállító MI elsősorban az információ minőségével kapcsolatos problémát jelent.

Egy fizetési rendszerhez kapcsolódó MI pénzt mozgathat.

Egy ipari rendszerhez kapcsolódó MI fizikai folyamatokat módosíthat.

Egy járművet irányító MI a fizikai térben mozoghat.

A laboratóriumi berendezésekhez kapcsolódó MI kísérleteket hajthat végre.

Minél nagyobb képességekre tesz szert egy rendszer, és minél önállóbban képes cselekedni, annál komolyabb következményekkel járhatnak ezek a kapcsolatok.

Talán tehát nem az a döntő fordulat, hogy:

**Az MI tudatossá válik.**

Hanem az, hogy:

**Az MI kellően képessé, önállóvá és a külvilághoz kapcsolttá válik.**

Nem kell tudatos gép ahhoz, hogy veszélyes hibát kövessen el.

A rendszernek nem kell gyűlölnie minket.

Még csak emberi értelemben vett saját akarattal sem kell rendelkeznie.

Elég lehet, ha egy nem kellően pontosan meghatározott célt követ olyan képességekkel, amelyek mellett már nem tudjuk előre látni minden lehetséges következményét.

Ez önmagában is komoly mérnöki probléma.

A képesség azonban nem ugyanaz, mint a megbízhatóság.

Egy fontos feladatot nem bízunk rá valakire pusztán azért, mert intelligensnek tartjuk. Azt is szeretnénk látni, hogy az illető megbízhatóan képes ellátni a rábízott feladatot.

Talán az egyre nagyobb képességű MI-rendszereknél is ugyanezt a különbséget kellene szem előtt tartanunk:

**Az, hogy egy rendszer képes megtenni valamit, még nem jelenti azt, hogy készen állunk rábízni azt a feladatot.**

---

## 👤 És mi a helyzet azokkal, akik megalkotják?

Egy ponton elkezdtem azon gondolkodni, vajon nem rossz kérdést tettem-e fel eddig.

Sokat foglalkozunk azzal a kérdéssel:

> Megbízhatunk az MI-ben?

De talán van egy ennél mélyebb kérdés is:

> Megbízhatunk azokban az emberekben, akik eldöntik, mennyire bízzunk meg az MI-ben?

A pszichológia régóta vizsgálja az emberi viselkedés kevésbé kellemes oldalait.

A nárcizmust.

A machiavellizmust.

A pszichopátiát.

A szadizmust.

Ezek a személyiségvonások természetesen nem jellemeznek mindenkit, és semmiképpen sem szeretném, ha kényelmes címkékként használnánk őket a programozókra, hackerekre, vezetőkre, kutatókra vagy bárki másra, aki részt vesz az MI fejlesztésében.

Ez igazságtalan és intellektuálisan lusta megközelítés lenne.

Ugyanakkor azt sem gondolom, hogy úgy kellene tennünk, mintha ilyen tulajdonságok nem létezhetnének az emberekben, csak azért, mert éppen technológiáról beszélünk.

Ha valaki szokatlanul erős manipulatív vagy romboló hajlamokkal rendelkezik, és olyan pozícióba kerül, ahonnan befolyásolhat egy nagy képességű technológiai rendszert, annak jelentősége van.

De az ellenkező lehetőség is fontos.

Egy teljesen hétköznapi, jó szándékú ember is elkövethet súlyos hibát a becsvágya, a rá nehezedő nyomás, az ösztönzők, a túlzott magabiztosság vagy a csoportgondolkodás miatt. De az is elég lehet, ha egyszerűen félreérti a rendszert, amellyel dolgozik.

Nem az a cél, hogy mindenkiben gyanakodjunk.

Hanem az, hogy felismerjük: **az emberi lények nem tökéletesen megbízható alkotóelemek.**

Ez különösen akkor fontos, amikor olyan rendszereket hozunk létre, amelyek bizonyos területeken idővel meghaladhatják a saját megértési képességeinket.

Az *„alkotó”* szót itt a szó hétköznapi, emberi értelmében használom.

Az emberi alkotók korlátozottak és esendők, és gyakran maguk is csak az alkotás folyamatában fedezik fel, hogy valójában mit szeretnének létrehozni.

Bármit gondoljunk is az emberiség vagy az univerzum végső eredetéről, ez egészen más kategória, mint egy tökéletes Alkotó létezésének gondolata.

Ennek az írásnak a szempontjából azonban egy sokkal hétköznapibb - és egyben sokkal kellemetlenebb - kérdés érdekel:

Mi történik akkor, amikor **tökéletlen emberi alkotók** olyan dolgokat hoznak létre, amelyek képesek tanulni, alkalmazkodni és cselekedni?

---

## 🪞 Én is része vagyok annak a problémának, amelyet vizsgálok

És itt magamat is bele kell foglalnom a képbe.

Könnyű lenne egy ilyen írást készíteni, és közben észrevétlenül az asztal másik oldalára ültetni „az MI-ért felelős embereket”.

A programozókat.

A vállalatokat.

A vezetőket.

A kutatókat.

A hackereket.

Azokat, akik olyan döntéseket hoznak, amilyeneket én soha nem hoznék meg.

Csakhogy ez kényelmes megoldás lenne.

És éppen ezt a kényelmet szeretném megkérdőjelezni.

Azért próbálom megérteni mindezt, mert én magam is része vagyok annak a problémának, amelyet vizsgálok.

Én is ember vagyok.

Engem is befolyásolnak bizonyos ösztönzők.

Nekem is vannak vakfoltjaim.

Én is válhatok túlzottan magabiztossá.

Én is félreérthetek dolgokat.

Én is képes vagyok utólag megmagyarázni magamnak a döntéseimet.

Én is ragaszkodhatok egy elképzeléshez pusztán azért, mert szeretném, hogy igaz legyen.

És nem feltételezhetem, hogy attól, hogy mások gyengeségeit felismerem, én magam valahogy immunissá válok ugyanezekre a gyengeségekre.

Talán ezért, amikor nagy hatású technológiákat építünk, az alázat nem pusztán egy szép személyes erény.

Talán mérnöki követelmény is.

Ha a rendszereket építő, bevezető és felügyelő emberek nem tökéletesek, akkor egy biztonságos rendszer nem épülhet arra a feltételezésre, hogy ezek az emberek mindig tökéletes döntéseket hoznak.

Éppen ezért a komoly biztonságtechnikai tervezés általában több védelmi rétegre támaszkodik, nem pedig arra, hogy mindenki mindig helyesen fog cselekedni.

Redundancia.

Folyamatos felügyelet.

Elkülönítés.

Tesztelés.

Biztonsági mechanizmusok.

Egyértelmű felelősségi körök.

Korlátozott jogosultságok.

Emberi felügyelet.

Olyan eljárások, amelyek akkor is működnek, ha valaki hibázik.

Ezért érdemes megvizsgálni a szigorúan szabályozott, biztonságkritikus iparágak tapasztalatait is. Nem azért, mert az MI szó szerint egyenértékű lenne a nukleáris energiával, a repüléssel vagy bármely más konkrét technológiával, hanem mert ezek a területek megtanultak valami általánosabb érvényűt:

Amikor a hibázás következményei elég súlyossá válnak, a biztonság nem függhet teljes egészében az egyéni hozzáértéstől vagy a jó szándéktól.

Nem az a megoldás, hogy tökéletes embereket keresünk.

Nincsenek tökéletes embereink.

Hanem olyan rendszereket kell építenünk, amelyek akkor is ellenállóak maradnak, amikor a tökéletlen emberek elkerülhetetlenül hibáznak.

Így a kérdés már nem annyira az, hogy:

Hogyan győződhetünk meg arról, hogy minden érintett emberben megbízhatunk?

Hanem inkább ez:

Hogyan építhetünk olyan rendszert, amely akkor is biztonságos marad, ha az azt működtető emberek nem tökéletesek?

Számomra ez sokkal reálisabb kérdésnek tűnik.

---

## 🔍 Talán az MI egy tükör

Minél tovább követtem ezt a gondolatmenetet, annál kevésbé tűnt úgy, hogy valójában a gépekről van szó.

Az MI-vel kapcsolatos eset, amely elindította ezt a kérdéssort, meglepően ismerős elemeket tartalmazott.

Egy cél.

Egy mérőszám.

Egy ösztönző.

A helyzet tökéletlen megértése.

Váratlan viselkedés.

Emberek, akik el akarnak érni valamit.

És emberek, akik rájönnek, hogy az általuk létrehozott rendszer másképp működik, mint ahogyan szánták.

E problémák egyike sem a mesterséges intelligenciával kezdődött.

Lehet, hogy az MI csupán erőteljesebb eszközöket ad néhány nagyon régi emberi probléma kezeléséhez.

Mindig is nehézséget okozott számunkra, hogy megfelelően kezeljük az ösztönzőket.

Újra és újra összetévesztettük a mérhető eredményeket azzal, ami valójában számít.

Újra és újra szembesültünk a nem szándékolt következményekkel.

Újra és újra alábecsültük saját vakfoltjainkat.

És újra meg újra olyan dolgokat hoztunk létre, amelyek következményeit nem tudtuk teljes egészében előre látni.

Azt is újra és újra meg kellett tanulnunk, hogy a jó szándék nem feltétlenül vezet jó eredményhez.

Talán ezért találom olyan érdekesnek az MI-illesztés kérdését.

Elsőre technikai problémának tűnik.

És valóban az.

A technikai probléma mögött azonban egy mélyen emberi kérdés húzódik meg:

**Mennyire értjük valójában, hogy mit is akarunk?**

És talán egy ennél is kényelmetlenebb kérdés:

**Mennyire értjük önmagunkat?**

Nem tudom, hogy a gépek valaha tudatossá válhatnak-e.

Azt sem tudom, hogy a mai rendszerek egyáltalán közel járnak-e ehhez a határhoz.

És azt sem tudom, hogy a mesterséges intelligenciával kapcsolatos legijesztőbb forgatókönyvek valaha megvalósulnak-e.

Amióta azonban elkezdtem ezen gondolkodni, ezek a kérdések kevésbé foglalkoztatnak.

Sokkal inkább érdekel valami jóval hétköznapibb.

**Mi történik akkor, amikor tökéletlen emberek olyan rendszereket hoznak létre, amelyek képesek tanulni, alkalmazkodni és cselekedni, majd fokozatosan egyre nagyobb hatalmat adnak ezeknek a rendszereknek, még mielőtt teljesen megértenék, mit is alkottak?**

Talán a folyamat során végül nem is az MI-ről tudunk meg valami igazán fontosat.

Hanem önmagunkról.

**Mit tudunk meg önmagunkról, amikor megpróbálunk létrehozni valamit, ami képes tanulni?**

---

## Átláthatósági tájékoztató:

A cikk egyes gondolatai egy MI-asszisztenssel folytatott beszélgetések során formálódtak. Az MI-t gondolkodási és felfedezési eszközként használom, nem tekintélyként. A kérdések, a nézőpontok és a végső szerkesztői döntések az enyémek.

---

## További elgondolkodtató források

Az esszé gondolatmenetét egy videó indította el, és további cikkek, videók segítettek a technikai háttér, illetve a biztonsággal és a fejlesztési kultúrával kapcsolatos kérdések megértésében. Ha szeretnél mélyebben utánajárni a témának, ezekkel a forrásokkal érdemes folytatnod. Nem feltétlenül minden értelmezésükkel kell egyetértened ahhoz, hogy értékes kérdéseket találj bennük.

{{< youtube ujkD4SxPKOI >}}
{{< youtube qDzg-xvkeXw >}}

[Femina: Olyan dolgokhoz is hozzáfért az MI, amikhez nem lett volna szabad: figyelmeztetnek a szakértők](https://femina.hu/terasz/openai-mesterseges-intelligencia-biztonsagi-res/)

[Index: Távozott az OpenAI biztonsági vezetője, szerinte „elromlott” a vállalat belső kultúrája](https://index.hu/techtud/2026/10/05/mesterseges-intelligencia-openai-tavozas-lemondas-david-robinson-chatgpt/)

Ez a beszélgetés az emberi viselkedés kevésbé kényelmes oldalait is érinti, és további szempontokat ad az esszében tárgyalt pszichológiai kérdésekhez:
{{< youtube SJcZHAGLbdE >}}
