# Zákon o kybernetické bezpečnosti a informační systémy zpravodajských služeb

Cílem této práce je velmi důkladně se seznámit s historickým vývojem a
aktuálním stavem problematiky právního rámce Zákona o kybernetické
bezpečnosti specificky ve vztahu ke zpravodajským službám ČR a jejich
informačním a komunikačním systémům.

## Obsah
* [Úvod](#Uvod)
* [Zpravodajské služby](#Zpravodajske sluzby)
* [Informační systémy ZS](#Informacni systemy ZS)
  * [Informační systémy ZS typu I - obsahující utajované informace](#IS typu I)
  * [Informační systémy ZS typu II - neobsahující utajované informace](#IS typu II)
* [Předmět úpravy Zákona o kybernetické bezpečnosti](#Predmet upravy)
* [Kontrolní činnost](#Kontrolni cinnost)
* [Závěr](#Zaver)
  

<div id='Uvod'/>
## Úvod

[Zákon o kybernetické bezpečnosti](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=82522&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#local-content)
(plným jménem Zákon o kybernetické bezpečnosti a o změně souvisejících
předpisů; zákon č. 181/2014 Sb., dále jen *ZKB* - někteří autoři
používají zkratku *ZoKB*) byl ve Sbírce zákonů vydán dne 29. srpna
2014, čímž nabyl platnosti. Účinnosti nabyl dne 1. ledna 2015 (viz
[§38](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=2&idBiblio=82522&recShow=32&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)). Jeho
prvopočátky je však možné datovat již do roku 2011, kdy vláda svým
[usnesením č. 781](https://www.nbu.cz/cs/aktuality/994-informace-k-usneseni-vlady-ceske-republiky-ze-dne-19-rijna-2011-c-781/)
z 19. října tohoto roku jmenovala
[Národní bezpečnostní úřad](https://www.nbu.cz/) (dále jen *NBÚ*)
gestorem oblasti kybernetické bezpečnosti, zřídila Radu pro
kybernetickou bezpečnost apod. Mimo jiné bylo ministrům vnitra a
obrany a řediteli Bezpečnostní informační služby uloženo spolupracovat
na návrhu ZKB.

Tedy již od samého počátku příprav ZKB jej velmi pečlivě sledovaly i
české zpravodajské služby (dále jen *ZS*). Jejich informační (a
samozřejmě i komunikační) systémy pracující s utajovanými informacemi
spadají pod
[Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=60504&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=412~2F2005&rpp=15#local-content)
(zákon č. 412/2005 Sb.). Zájem ZS o ZKB byl tedy již od počátku
motivován snahou minimalizovat jeho dopady a případně pouze získat
nějaké výhody z něj plynoucí. To se jim nakonec (podle autorova
názoru) podařilo, jak ostatně bude ukázáno ve zbytky této práce.


<div id='Zpravodajske sluzby'/>
## Zpravodajské služby

V České republice jsou
[Zákonem o zpravodajských službách](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=42079&nr=153~2F1994&rpp=15#local-content) (zákon č. 153/1994 Sb.)
definovány 3 zpravodajské služby:

* [Bezpečnostní informační služba](http://www.bis.cz/) (dále jen
  *BIS*)
* [Úřad pro zahraniční styky a informace](http://www.uzsi.cz/) (dále
  jen *ÚZSI*)
* [Vojenské zpravodajství](http://www.vzcr.cz/) (dále jen *VZ*)

BIS je zřízena
[Zákonem o Bezpečnostní informační službě](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=42080&nr=154~2F1994&rpp=15#local-content)
(zákon č. 154/1994 Sb.). VZ je zřízeno
[Zákonem o Vojenském zpravodajství](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=60279&nr=289~2F2005&rpp=15#local-content)
(zákon č. 289/2005 Sb.). ÚZSI v&nbsp;současné době nemá svůj vlastní
zřizovací zákon (v&nbsp;zákoně č. 153/1994 Sb. má svoji specifickou část -
[Zvláštní ustanovení o Úřadu pro zahraniční styky a informace](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=0&idBiblio=42079&recShow=13&nr=153~2F1994&rpp=15#parCnt)).

Výkony činnosti obou civilních ZS jsou pak prvkem kritické
infrastruktury v rámci odvětví Veřejná správa podle
[Zákona o krizovém řízení](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=0&idBiblio=49557&name=krizov~C3~A9m~20~C5~99~C3~ADzen~C3~AD&rpp=15#local-content)
 (zákon č. 240/2000 Sb.) a
[Nařízení vlády o kritériích pro určení prvku kritické infrastruktury](https://portal.gov.cz/app/zakony/zakonInfo.jsp?idBiblio=83169&nr=315~2F2014&rpp=15#local-content).


<div id='Informacni systemy ZS'/>
## Informační systémy ZS

Hlavním úkolem ZS je *zabezpečování informací*
([§5](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=0&idBiblio=42079&recShow=4&name=z~C3~A1kon~20o~20zpravodajsk~C3~BDch~20slu~C5~BEb~C3~A1ch&rpp=15#parCnt)
[Zákona o zpravodajských službách](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=42079&nr=153~2F1994&rpp=15#local-content))
v oblasti jejich působnosti (pro účely této práce není rozdílná
oblastní působnost ZS podstatná). K plnění tohoto úkolu samozřejmě
používají i informační a komunikační systémy. Pro účely této práce
rozdělíme informační systémy (dále jen IS) ZS podle toho, zda
nakládají s utajovanými informacemi na dva typy:

* IS ZS typ I - obsahují resp. nakládají s utajovanými informacemi
* IS ZS typ II - neobsahují resp. nenakládají s utajovanými informacemi

Toto rozdělení je pro ZS velmi důležité, neboť jim v minulosti (tedy
před účinností ZKB) určovalo i nyní určuje podmínky, za kterých tyto
IS provozují.

<div id='IS typu I'/>
### IS typu I - obsahující utajované informace

IS typu I (tedy obsahující resp. nakládající s utajovanými
informacemi) jsou z pohledu ZS důležitější (kritičtější), neboť v
minulosti musely (a stále musí) splňovat požadavky definované ve
[Vyhlášce o bezpečnosti informačních a komunikačních systémů a dalších elektronických zařízení nakládajících s utajovanými informacemi a o certifikaci stínicích komor](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=60721&nr=523~2F2005&rpp=15#local-content)
(vyhláška č. 523/2005 Sb., ve znění vyhlášky č. 453/2011 Sb.). Jednou
z mnoha původně zvažovaných variant právní úpravy kybernetické
bezpečnosti byla dokonce i pouze ochrana IS typu I (viz
[Věcný záměr zákona](http://www.govcert.cz/download/nodeid-1044/) i
[Důvodová zpráva](http://www.govcert.cz/download/nodeid-732/) k návrhu zákona).

<div id='IS typu II'/>
### IS typu II - neobsahující utajované informace

U IS typu II byly požadavky již benevolentnější a ZS si je definovaly
samy v rámci své činnosti (jedná se o různé podpůrné a provozní
systémy, které s utajovanými skutečnostmi nenakládají, nicméně činnost
dané ZS podporují - např. informační systém veřejné webové prezentace
úřadu apod.). Naprostá většina IS typu II však nenaplňuje podmínky pro
určení kritické informační infrastruktury.


<div id='Predmet upravy'/>
## Předmět úpravy Zákona o kybernetické bezpečnosti

V úvodním paragrafu ZKB je specifikován předmět zákonné úpravy (v
dalším textu práce budu citovat pouze pro obsah práce důležité části
zákonů a to zejména z důvodu přehlednosti a ucelenosti textu práce):

> **§1 Předmět úpravy**  
> (1) Tento zákon upravuje práva a povinnosti osob a působnost a
> pravomoci orgánů veřejné moci v&nbsp;oblasti kybernetické bezpečnosti.

Pokud by tento paragraf nebyl modifikován následujícím odstavcem,
vztahoval by se tak celý ZKB i na výše definované IS ZS typu I (tedy
na IS ZS nakládající s utajovanými informacemi). Proto již v
[prvotním návrhu zákona](http://www.govcert.cz/download/nodeid-622/)
z 15. dubna 2013 je obsažen odstavec 2:

> (2) Tento zákon se nevztahuje na informační nebo komunikační
>     systémy, které nakládají s utajovanými informacemi.

Tento pro ZS velmi důležitý odstavec vznikl v rámci Meziresortní
pracovní skupiny (členy pracovní skupiny byla ministerstva vnitra a
obrany, obě civilní ZS, Český telekomunikační úřadu a Generální
ředitelství hasičského záchranného sboru) zabývající se vytvořením
paragrafového znění zákona na základě
[Věcného záměru zákona](http://www.govcert.cz/download/nodeid-1044/)
připraveného NBÚ a schváleného vládou
([nařízením vlády č. 382](https://www.govcert.cz/download/nodeid-551/
) ze dne 30. května 2012) a byl tak součástí zákona ihned od jeho
prvního návrhu.

[Věcný záměr zákona](http://www.govcert.cz/download/nodeid-1044/)
totiž jako jednu z možných variant řešení problematiky kybernetické
bezpečnosti zvažoval i pouze právní regulaci IS typu I, avšak velmi
přesně upozornil na skutečnost, že kybernetická bezpečnost IS typu I
je již *v současné době kvalitně řešena specifickou právní úpravou*
(citace z
[Věcného záměru zákona](http://www.govcert.cz/download/nodeid-1044/)). Specifický
zákon upravující problematiku kybernetické bezpečnosti IS typu I tak
dostal přednost před generickým zákonem o kybernetické bezpečnosti a
odstavec 2 tak nepřímo odkazuje na již existující specifickou úpravu, tedy na
[Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=60504&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=412~2F2005&rpp=15#local-content)
(zákon č. 412/2005 Sb.) a jeho prováděcí předpisy.

**ZKB se tedy vůbec nevztahuje na IS typu I, neboť tyto systémy již mají
svůj právní regulační rámec a mimo jiné podléhají i certifikaci.**

ZS však kromě IS určených pro nakládání s utajovanými informacemi
disponují i ostatními IS, které činnost ZS podporují. Mezi názorné
příklady je možné zařadit např. IS, které akumulují informace z
tzv. *otevřených zdrojů* (OSINT, Open Source Intelligence) a poskytují
je oprávněným osobám nebo informační systémy veřejné webové prezentace
úřadu apod. Takové systémy ze své podstaty neobsahují utajované
informace a tedy nespadají pod
[Zákon o ochraně utajovaných informací a o bezpečnostní způsobilosti](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=60504&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=412~2F2005&rpp=15#local-content). Pro
činnost ZS jsou ale velmi významné. Jejich důležitost musí posoudit
jejich provozovatel resp. správce.

Pokud by takový IS podmínky určení kritické informační infrastruktury
splňoval, vztahuje se na něj ZKB v&nbsp;omezené míře dané
[§33](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=2&idBiblio=82522&recShow=32&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
ZKB:

> **§33 Společná ustanovení**  
> (1) Tento zákon se vztahuje pouze na takové informační nebo
> komunikační systémy zpravodajských služeb, které splňují podmínky
> pro určení kritické informační infrastruktury, a to v rozsahu § 12 a
> 16; ustanovení § 4 se na tyto systémy použije přiměřeně a Úřad je
> jako prvky kritické infrastruktury podle § 22 odst. 2 písm. m)
> nenavrhuje.

I toto ustanovení v původním záměru NBÚ nefigurovalo a vzniklo až v
rámci Meziresortní pracovní skupiny.

První odstavec
[§33](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=2&idBiblio=82522&recShow=32&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
tedy hovoří o dvou ustanoveních:

1. ze ZKB je na takové IS aplikován pouze
   [§12](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=0&idBiblio=82522&recShow=11&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
   a
   [§16](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=1&idBiblio=82522&recShow=15&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
   plně a
   [§4](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=0&idBiblio=82522&recShow=3&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
   přiměřeně.

   V
   [§12](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=0&idBiblio=82522&recShow=11&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
   je specifikováno vydání *varování* NBÚ o hrozbě v oblasti
   kybernetické bezpečnosti (odstavec 1) a jeho zveřejnění na webových
   stránkách NBÚ a poskytnutí předaným kontaktům (odstavec 2). V tomto
   paragrafu tedy není pro ZS specifikována žádná zásadní
   povinnost. Možnost získání informací z vydaného varování je jistě
   příjemná a pro správce IS ZS jistě zajímavá. Na druhou stranu ale
   zveřejněné varování a obecně jakékoli informace na webových
   stránkách NBÚ jsou jistě otevřeným zdrojem, se kterým by
   zpravodajská služba již před vydáním zákona měla pracovat a
   informace by se tak odpovědným pracovníkům ZS měla dostat (na
   základě konceptu *Need to know*) i bez předání kontaktních údajů
   oprávněné osoby.

   [§16](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=1&idBiblio=82522&recShow=15&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
   ZKB definuje *kontaktní údaje* a jejich poskytnutí:

   - o orgánu veřejné moci (název ZS, adresa sídla apod.)
   - o fyzické osobě, která je za orgán oprávněna jednat ve věcech
     upravených ZKB (jméno, příjmení, telefonní číslo a adresu
     elektronické pošty)

   Poskytnutí kontaktních údajů na odpovědné pracovníky je tak novou
   povinností vztahující se i na ZS. Protože se však na ZS neuplatňují
   přechodná ustanovení ZKB
   ([§29-§31](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=1&idBiblio=82522&recShow=26&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt))
   specifikující lhůtu pro poskytnutí těchto kontaktních údajů, je to
   povinnost pouze hypotetická. Zde jsem v rámci přípravy práce
   položil dotaz na NCKB/NBÚ, abych si tento názor potvrdil a ověřil
   si i přístup ZS k této povinnosti (ZS se obecně snaží uchovávat v
   tajnosti nejen metody, prostředky a výsledky své práce, ale i své
   pracovníky a spolupracovníky a jejich kontaktní údaje). Ani jedna
   ZS však své kontaktní informace na základě této povinnosti
   do 5. ledna 2016 neposkytla (informace ředitele NKCB, pana
   Vladimíra Rohela). Ostatně žádná ZS nyní nemá určen některý svůj IS
   jako součást kritické informační infrastruktury, a proto ani není
   definován počátek 30denní lhůty pro poskytnutí kontaktních údajů
   ([§29, odst. 1](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=1&idBiblio=82522&recShow=26&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)). NBU
   však již nyní kontaktními údaji na jednotlivé ZS disponuje, neboť
   se ZS spolupracuje na činnostech podle jiných zákonů a dokonce
   spolu velmi úzce spolupracovali již na přípravě tohoto zákona.

   [§4](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=0&idBiblio=82522&recShow=3&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
   definuje pojem *bezpečnostní opatření* a povinnost orgánů a osob
   zavést, provádět a dokumentovat je. Tento paragraf je tedy jediný,
   který stanovuje pro ZS novou povinnost, kterou musí na některé své
   IS typu II aplikovat přiměřeně.

2. i pokud by IS ZS splňoval podmínky pro určení kritické informační
   infrastruktury, NBÚ jej přesto nebude Ministerstvu vnitra navrhovat
   jako prvek kritické infrastruktury v odvětví komunikační a
   informační systémy v oblasti kybernetické bezpečnosti, jejichž
   provozovatelem je organizační složka státu (podle krizového
   zákona) a tedy je vláda ani jako takové neurčí.

   I tento odstavec je tedy vůči ZS benevolentní, neboť určení
   daného IS by ZS přinášelo další povinnosti podle krizového zákona.

Velmi zajímavým se zde ve výčtu paragrafů rozsahu platnosti ZKB na IS
ZS typu II jeví chybějící
[§11 Opatření](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=0&idBiblio=82522&recShow=10&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
a
[§24 Nápravná opatření](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=1&idBiblio=82522&recShow=22&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
(a jak bude uvedeno níže i
[§23 Kontrola](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=1&idBiblio=82522&recShow=21&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)). Zejména
pak ve vztahu ke změně
[§146](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=1&idBiblio=60504&recShow=153&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=412~2F2005&rpp=100#parCnt)
odst. 1
[Zákona o ochraně utajovaných informací a o bezpečnostní způsobilosti](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=60504&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=412~2F2005&rpp=15#local-content)
v
[§34 odst. 2](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=1&idBiblio=82522&recShow=28&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt). Zákonodárce
zde hovoří o možnosti požádání o vysvětlení kontrolním orgánem (tedy
NBÚ) v rámci řízení o vydání opatření podle ZKB v případě, že je
rozhodovací činnost ZS stižena vadami. Protože se ale oba paragrafy
podle výše uvedeného na ZS vůbec nevztahují, nemůže být ani žádné
takové řízení zahájeno.

**Z
[§33](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=2&idBiblio=82522&recShow=32&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
tedy také plyne, že na IS ZS typu II, které nesplňují podmínky pro
určení kritické informační infrastruktury, se zákon nevztahuje
vůbec.**

<div id='Kontrolni cinnost'/>
## Kontrolní činnost

Kontrolní činnosti v rámci ZKB se věnují
[§23](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=1&idBiblio=82522&recShow=21&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
a
[§24](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=1&idBiblio=82522&recShow=22&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)
zákona. Kontrolu vykonává NBÚ. V rámci kontrolní činnosti může ukládat
nápravná opatření
([§24 odst. 1](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=1&idBiblio=82522&recShow=22&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt))
a v nejzávažnějších případech i zákázat používaní daného IS nebo
některé jeho části
([§24 odst. 2](https://portal.gov.cz/app/zakony/zakonStruct.jsp?page=1&idBiblio=82522&recShow=22&fulltext=kybernetick~C3~A9~20bezpe~C4~8Dnosti&nr=181~2F2014&rpp=15#parCnt)). Zejména
druhé oprávnění je velmi silné a závažné. Jeho aplikace na jiný úřad
bude velmi jistě důkladně zvažována a také zdůvodněna.

Kontrola zpravodajských služeb je ale řešena zejména
[Zákonem o zpravodajských službách](https://portal.gov.cz/app/zakony/zakonPar.jsp?idBiblio=42079&nr=153~2F1994&rpp=15#local-content),
který pamatuje i na ostatní zákony a kontrolní činnost nad ZS
neponechává v rukou těchto zákonů (výjimku tvoří např. kontrola
dodržování rozpočtových pravidel). (Podrobněji se kontrolní činnosti
nad ZS věnuje i dokument ředitele Centra bezpečnostních studií CEVRO
Institutu Jaroslava Salivara nazvaný
[Kontrola zpravodajských služeb a la chytrá horákyně aneb pravomoci opět rostou, kontrola zůstává bezzubá](http://www.cevroinstitut.cz/data/2015-08-28-kontrola-zpravodajskych-sluzeb.pdf).)

Relevantní části zákona o zpravodajských službách zde uvádím v plném
znění, jejich rozbor následuje.

> **Kontrola zpravodajských služeb**  
> § 12  
> (1) Činnost zpravodajských služeb podléhá kontrole vlády a
>     Parlamentu. Rozsah a způsob kontroly zpravodajských služeb
>     Parlamentem stanoví zvláštní zákon.  

> § 13  
> Působnost státních orgánů ke kontrole plnění úkolů hospodaření se
> státním majetkem a plnění státního rozpočtu podle zvláštních
> právních předpisů není ustanoveními tohoto zákona dotčena.  

> § 13a  
> (1) Jiná zvláštním zákonem stanovená kontrola než podle § 12 a 13
>     může být v zařízeních zpravodajské služby vykonána jen se
>     souhlasem jejího ředitele.

>  (2) Nebude-li souhlas podle odstavce 1 udělen, zajistí zpravodajská
>  služba výkon kontroly ve své působnosti a podá do 60 dnů ode dne
>  odmítnutí udělení souhlasu zprávu o výsledku vykonané kontroly
>  kontrolnímu orgánu, který o souhlas požádal, nestanoví-li tento
>  kontrolní orgán lhůtu delší.

> (3) Není-li zpravodajská služba schopna zajistit výkon kontroly ve
> své působnosti, je povinna umožnit výkon kontroly kontrolnímu
> orgánu. Může si však vyhradit zvláštní podmínky způsobu výkonu
> takové kontroly.

Tyto paragrafy velmi přesně definují, za jakých podmínek se může
kontrola kontrolního orgánu v ZS uskutečnit. Specificky v případě
kontroly NBÚ v rámci ZKB k tomu může dojít pouze se souhlasem ředitele
ZS. Jeho vydání je však velmi nepravděpodobné z důvodů již výše
zmíněných (snaha utajit metody i nástroje, ale také z&nbsp;důvodů uvedených
dále v odstavci 3, kdy si kontrolovaný subjekt může stanovit podmínky
kontroly). Zákon však pamatuje i na takové případy. ZS pak provede
kontrolu sama a zprávu o výsledku kontroly NBÚ poskytne v definovaném
čase. Tento způsob kontroly ze strany ZS by byl (podmiňovací způsob je
zde použit zcela záměrně) zřejmě preferován. Nicméně je možné, že v
určitých specifických a izolovaných případech by ZS mohla preferovat
plnou nezávislou kontrolu experty NBÚ za stanovených podmínek
(odstavec 3).

Vše výše uvedené však platí pouze za předpokladu, že by se na IS ZS
(typu II) vztahovaly paragrafy o kontrole a nápravných opatřeních ZKB,
což ale
[Společná ustanovení](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=2&idBiblio=82522&recShow=32&name=kybernetick~C3~A9~20bezpe~C4~8Dnosti&rpp=15#parCnt)
zákona neuvádí a aplikace těchto paragrafů na ZS je tedy sporná. Ve
stejné situaci se budeme nacházet při analýze možností aplikace
správních deliktů a sankcí ([§25](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=0&idBiblio=82522&recShow=24&nr=181~2F2014&rpp=50#parCnt)) resp. stavu kybernetického nebezpečí ([§21](https://portal.gov.cz/app/zakony/zakonPar.jsp?page=0&idBiblio=82522&recShow=20&nr=181~2F2014&rpp=50#parCnt)) na ZS.


<div id='Zaver'/>
## Závěr

Z výše uvedeného tedy plyne, že Zákon o kybernetické bezpečnosti se na
informační systémy zpravodajských služeb vztahuje pouze velmi okrajově
a to pouze v singulárních případech informačních systémů nenakládající
s utajovanými informacemi splňujících podmínky pro určení kritické
informační infrastruktury.

Pro takové informační a komunikační systémy pak zpravodajská služba:

- poskytne (resp. může poskytnout) kontaktní údaje (bez lhůty pro
  jejich poskytnutí)
- přiměřeně aplikuje bezpečnostní opatření (zavádí, provádí a
  dokumentuje)

- efektivně nepodléhá kontrole NBÚ (resp. může se jí nesouhlasem
  vlastního ředitele úspěšně bránit), nápravným opatřením ani sankcím
  ze ZKB plynoucím.
