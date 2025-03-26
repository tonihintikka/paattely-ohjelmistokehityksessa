# Numeraalisen päättelyn periaatteet

[← Takaisin sisällysluetteloon](README.md)

## Sisältö
- [Johdanto numeraaliseen päättelyyn](#johdanto-numeraaliseen-päättelyyn)
- [Numeraalisen päättelyn määritelmä ja keskeiset käsitteet](#numeraalisen-päättelyn-määritelmä-ja-keskeiset-käsitteet)
- [Induktiivinen ja deduktiivinen numeraalinen päättely](#induktiivinen-ja-deduktiivinen-numeraalinen-päättely)
- [Tilastollinen päättely](#tilastollinen-päättely)
- [Todennäköisyydet päättelyssä](#todennäköisyydet-päättelyssä)
- [Korrelaatio ja kausaliteetti](#korrelaatio-ja-kausaliteetti)
- [Esimerkkejä numeraalisesta päättelystä](#esimerkkejä-numeraalisesta-päättelystä)
- [Harjoitustehtävät](#harjoitustehtävät)
- [Seuraava aihe: Looginen päättely](2-looginen-paattely.md)

## Johdanto numeraaliseen päättelyyn

Numeraalinen päättely on tärkeä osa jokapäiväistä elämäämme. Käytämme sitä tehdessämme ostoksia, arvioidessamme aikaa ja etäisyyksiä, analysoidessamme dataa tai tulkitessamme tilastoja. Numeraalinen päättely on kykyä ymmärtää, analysoida ja tehdä johtopäätöksiä numeerisen tiedon pohjalta.

Nykymaailmassa, jossa dataa on saatavilla enemmän kuin koskaan aiemmin, numeraalisen päättelyn taidot ovat entistä tärkeämpiä. Ne auttavat meitä erottamaan olennaisen tiedon epäolennaisesta ja tekemään perusteltuja päätöksiä.

## Numeraalisen päättelyn määritelmä ja keskeiset käsitteet

**Numeraalinen päättely** tarkoittaa prosessia, jossa tehdään johtopäätöksiä ja ratkaisuja numeerisen informaation perusteella. Se sisältää erilaisia ajatteluprosesseja kuten:

- **Laskennallinen ajattelu**: Kyky ratkaista ongelmia käyttäen matemaattisia operaatioita
- **Kvantitatiivinen analyysi**: Numeerisen datan systemaattinen tarkastelu
- **Mallintaminen**: Tosielämän ilmiöiden esittäminen matemaattisessa muodossa
- **Mittasuhteiden ymmärtäminen**: Kyky hahmottaa suuruusluokkia ja mittasuhteita

Keskeisiä käsitteitä numeraalisessa päättelyssä ovat:

- **Data**: Havainnoista tai mittauksista kerätyt numeeriset tiedot
- **Muuttuja**: Suure, joka voi saada erilaisia arvoja
- **Tunnusluvut**: Dataa kuvaavat luvut kuten keskiarvo, mediaani ja keskihajonta
- **Riippuvuus**: Muuttujien välinen suhde tai yhteys

## Induktiivinen ja deduktiivinen numeraalinen päättely

Numeraalinen päättely voi olla luonteeltaan joko induktiivista tai deduktiivista:

### Induktiivinen numeraalinen päättely

Induktiivinen päättely etenee yksittäisistä havainnoista yleistyksiin. Esimerkki:

*Mittaamme 100 eri männyn pituutta metsässä ja havaitsemme keskiarvoksi 23 metriä. Induktiivisesti päättelemme, että kyseisen metsän mäntyjen keskipituus on noin 23 metriä.*

Induktiivinen päättely on tärkeää etenkin:
- Tilastollisessa analyysissa
- Empiirisissä tutkimuksissa
- Trendien tunnistamisessa

### Deduktiivinen numeraalinen päättely

Deduktiivinen päättely lähtee yleisistä säännöistä tai laeista kohti yksittäistapauksia. Esimerkki:

*Tiedämme, että kaikki ympyrät noudattavat kaavaa A = πr². Kun meillä on ympyrä, jonka säde on 5 cm, voimme deduktiivisesti päätellä sen pinta-alan olevan noin 78,5 cm².*

Deduktiivinen päättely on keskeistä:
- Matemaattisessa todistamisessa
- Laskennallisissa sovelluksissa
- Luonnontieteellisten lakien soveltamisessa

## Tilastollinen päättely

Tilastollinen päättely on numeraalisen päättelyn osa-alue, jossa tehdään johtopäätöksiä datasta todennäköisyyslaskennan avulla. Keskeisiä käsitteitä ovat:

- **Otanta**: Tapa, jolla tutkittava aineisto on valittu perusjoukosta
- **Tilastollinen merkitsevyys**: Mitta sille, kuinka todennäköisesti tulos ei ole sattumaa
- **Luottamusväli**: Numeerinen väli, joka tietyllä todennäköisyydellä sisältää todellisen arvon
- **Hypoteesien testaus**: Väitteiden testaaminen tilastollisin menetelmin

Tilastollisessa päättelyssä on tärkeää ymmärtää:

1. **Otantavirhe**: Ero otoksen ja perusjoukon välillä
2. **Edustavuus**: Kuinka hyvin otos edustaa perusjoukkoa
3. **Harhat**: Systemaattiset virheet tilastollisessa päättelyssä

## Todennäköisyydet päättelyssä

Todennäköisyyksien ymmärtäminen on olennainen osa numeraalista päättelyä. Todennäköisyydet auttavat arvioimaan tapahtumien mahdollisuuksia ja riskejä.

Todennäköisyyksien perusteita:

- **Klassinen todennäköisyys**: Suotuisten tapausten määrä jaettuna kaikkien mahdollisten tapausten määrällä
- **Ehdollinen todennäköisyys**: Tapahtuman todennäköisyys, kun tiedetään toisen tapahtuman toteutuneen
- **Bayesin teoreema**: Matemaattinen menetelmä, jolla päivitetään todennäköisyyksiä uuden tiedon valossa

Käytännön esimerkki Bayesin teoreemasta:

*Lääketieteellinen testi tunnistaa sairauden 99% tarkkuudella (herkkyys), mutta antaa myös 2% vääriä positiivisia tuloksia. Jos sairauden esiintyvyys väestössä on 0,1%, mikä on todennäköisyys, että positiivisen testituloksen saanut henkilö todella sairastaa kyseistä sairautta?*

Bayesin kaavan avulla voidaan laskea, että todennäköisyys on vain noin 4,7%, mikä on yllättävän pieni. Tämä osoittaa, kuinka tärkeää on ymmärtää todennäköisyyksien toimintaa erityisesti harvinaisten tapahtumien kohdalla.

## Korrelaatio ja kausaliteetti

Numeraalisessa päättelyssä on erittäin tärkeää ymmärtää ero korrelaation ja kausaliteetin välillä:

- **Korrelaatio**: Muuttujien välinen tilastollinen yhteys, jossa toisen muuttujan arvot vaihtelevat systemaattisesti toisen muuttujan arvojen mukaan
- **Kausaliteetti**: Syy-seuraussuhde, jossa yhden muuttujan muutos aiheuttaa muutoksen toisessa muuttujassa

Klassinen sanonta alalla on: "Korrelaatio ei implikoi kausaliteettia". Esimerkiksi:
- Jäätelön myynti ja hukkumistapaukset korreloivat keskenään kesäisin
- Tämä ei kuitenkaan tarkoita, että jäätelön syönti aiheuttaisi hukkumisia
- Molemmat selittyvät kolmannella tekijällä: lämpimällä säällä

Kausaliteetin osoittamiseksi tarvitaan tyypillisesti:
1. Ajallinen järjestys (syy edeltää seurausta)
2. Korrelaatio muuttujien välillä
3. Vaihtoehtoisten selitysten eliminointi (usein kontrolloiduilla kokeilla)

## Esimerkkejä numeraalisesta päättelystä

### Esimerkki 1: Asuntomarkkinoiden analysointi

Ajattele tilannetta, jossa tarkastellaan asuntojen hintojen kehitystä:

*Datasta havaitaan, että tietyn kaupunginosan asuntojen hinnat ovat nousseet 15% vuodessa viimeisen kolmen vuoden ajan. Onko järkevää päätellä, että hinnat nousevat 15% myös seuraavana vuonna?*

Numeraalinen päättely:
1. Tunnistetaan trendi (15% vuosittainen kasvu)
2. Pohditaan, onko kasvu kestävää pitkällä aikavälillä
3. Arvioidaan muita vaikuttavia tekijöitä (korkotaso, rakentaminen alueella, talouden kehitys)
4. Päädytään tasapainoiseen arvioon tulevasta kehityksestä

### Esimerkki 2: Lääketieteellisen tutkimuksen arviointi

*Uutisissa kerrotaan, että tutkimuksen mukaan kahvin juonti vähentää sydäntautien riskiä 20%. Miten arvioida väitettä?*

Numeraalinen päättely:
1. Tarkistetaan otoskoko (onko riittävä tilastolliseen merkitsevyyteen?)
2. Selvitetään, onko kyseessä korrelaatio vai kausaliteetti
3. Huomioidaan mahdolliset sekoittavat tekijät (esim. kahvia juovien muu elämäntyyli)
4. Vertaillaan tulosta muihin tutkimuksiin

## Harjoitustehtävät

### Tehtävä 1: Todennäköisyyksien laskeminen

Korttipakassa on 52 korttia. Mikä on todennäköisyys, että satunnaisesti nostettu kortti on:
a) Pata?
b) Kuvakortti (J, Q, K)?
c) Musta kuvakortti?

### Tehtävä 2: Korrelaation ja kausaliteetin arviointi

Arvioi seuraavia väitteitä. Osoittavatko ne korrelaatiota, kausaliteettia vai ei kumpaakaan? Perustele.

a) "Juoksuharjoittelun määrän lisääminen paransi juoksijan aikaa 10 km:n matkalla."
b) "Maissa, joissa syödään enemmän suklaata, on enemmän Nobel-palkittuja henkilöitä."
c) "Kaksosten syntyminen lisääntyy hedelmällisyyshoitojen käytön yleistymisen myötä."

### Tehtävä 3: Tilastollinen päättely

Kyselytutkimuksessa 100 opiskelijasta 65 ilmoitti pitävänsä matematiikasta. 95% luottamusväliksi laskettiin 55%-75%. Tulkitse tulosta ja selitä, mitä luottamusväli kertoo.

### Tehtävä 4: Induktiivinen ja deduktiivinen päättely

Tunnista, kumpaa päättelymuotoa seuraavat esimerkit edustavat:

a) "Kaikki havaitut joutsenet ovat olleet valkoisia, joten kaikki joutsenet ovat valkoisia."
b) "Kaikki priimiluvut ovat parittomia lukuun ottamatta lukua 2, joten luku 17 on pariton."
c) "Kaikissa tutkimissamme metalleissa lämpölaajeneminen on ollut suoraan verrannollinen lämpötilan muutokseen, joten lämpölaajeneminen on yleinen metallien ominaisuus."

---

## Seuraava aihe: [Looginen päättely](2-looginen-paattely.md)
