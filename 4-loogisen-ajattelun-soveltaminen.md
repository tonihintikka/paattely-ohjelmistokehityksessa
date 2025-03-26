# Loogisen ja ohjelmallisen ajattelun soveltaminen

[← Takaisin sisällysluetteloon](README.md) | [← Edellinen: Verbaalinen päättely](3-verbaalinen-paattely.md) | [Seuraava: Kriittinen ajattelu →](5-kriittinen-ajattelu.md)

## Sisältö
- [Johdanto loogisen ajattelun soveltamiseen](#johdanto-loogisen-ajattelun-soveltamiseen)
- [Algoritmisen ajattelun perusteet](#algoritmisen-ajattelun-perusteet)
- [Ongelmanratkaisun vaiheet](#ongelmanratkaisun-vaiheet)
- [Loogisten operaatioiden soveltaminen](#loogisten-operaatioiden-soveltaminen)
- [Ohjelmoinnillinen ajattelu käytännössä](#ohjelmoinnillinen-ajattelu-käytännössä)
- [Esimerkkejä ja harjoituksia](#esimerkkejä-ja-harjoituksia)

## Johdanto loogisen ajattelun soveltamiseen

Looginen ajattelu on monimutkaisten ongelmien ratkaisun perusta. Sitä voidaan soveltaa arkipäivän tilanteista aina tieteellisiin ja teknologisiin haasteisiin. Loogisen ajattelun soveltaminen yhdistää määrätietoisesti useita ajattelun taitoja, kuten:

- Analyyttistä ajattelua (ongelman osiin pilkkominen)
- Deduktiivista ja induktiivista päättelyä
- Systemaattista lähestymistapaa
- Syy-seuraussuhteiden tunnistamista
- Algoritmista ajattelua

Looginen ajattelu on erityisen tärkeää digitaalisessa maailmassa, jossa tietojenkäsittely, teknologia ja ohjelmointi perustuvat loogisille rakenteille. Ohjelmoinnillinen ajattelu (computational thinking) on loogisen ajattelun muoto, joka keskittyy ongelmien ratkaisemiseen tietojenkäsittelyn näkökulmasta.

## Algoritmisen ajattelun perusteet

**Algoritmi** on yksityiskohtainen, vaiheittainen ohje tehtävän suorittamiseksi. Algoritminen ajattelu tarkoittaa kykyä:

1. Pilkkoa ongelma selkeisiin, ratkaistaviin osiin
2. Tunnistaa kaavoja ja säännönmukaisuuksia
3. Määrittää ratkaisuprosessin vaiheet loogisessa järjestyksessä
4. Automatisoida ratkaisuprosessi

### Algoritmien keskeiset ominaisuudet

- **Determinismi**: Samoilla lähtöarvoilla algoritmi tuottaa aina saman tuloksen
- **Äärellisyys**: Algoritmi päättyy äärellisessä ajassa
- **Yksiselitteisyys**: Jokainen vaihe on tarkasti määritelty
- **Yleisyys**: Algoritmi ratkaisee ongelman kaikki tapaukset, ei vain yksittäistapauksia

### Esimerkki yksinkertaisesta algoritmista: kahden luvun suurimman yhteisen tekijän löytäminen (Eukleideen algoritmi)

```
1. Olkoon a ja b positiivisia kokonaislukuja
2. Jos b = 0, lopeta: suurin yhteinen tekijä on a
3. Laske a jaettuna b:llä ja ota jakojäännös r
4. Aseta a = b ja b = r
5. Palaa vaiheeseen 2
```

## Ongelmanratkaisun vaiheet

Looginen ongelmanratkaisu etenee tyypillisesti seuraavien vaiheiden kautta:

### 1. Ongelman määrittely ja ymmärtäminen

- Mikä on ratkaistava ongelma?
- Mitkä ovat lähtötiedot ja haluttu lopputulos?
- Mitkä ovat mahdolliset rajoitteet?

### 2. Ongelman jakaminen osiin (dekompositio)

- Jaetaan monimutkainen ongelma pienempiin, helpommin ratkaistaviin osiin
- Tunnistetaan osaongelmien väliset riippuvuudet

### 3. Ratkaisustrategian suunnittelu

- Kehitetään looginen etenemissuunnitelma
- Tunnistetaan tarvittavat työkalut ja menetelmät
- Hahmotetaan algoritmi tai toimintamalli

### 4. Ratkaisun toteuttaminen

- Sovelletaan suunniteltua strategiaa vaihe vaiheelta
- Seurataan algoritmia tai prosessia järjestelmällisesti

### 5. Testaus ja arviointi

- Tarkistetaan saadun ratkaisun oikeellisuus
- Arvioidaan ratkaisun tehokkuus
- Tunnistetaan mahdolliset parannuskohteet

### 6. Abstrahointi ja yleistäminen

- Tunnistetaan mitä opittiin ja miten opittua voidaan soveltaa laajemmin
- Yleistetään ratkaisu vastaavien ongelmien ratkaisemiseksi

## Loogisten operaatioiden soveltaminen

Loogisia operaatioita (JA, TAI, EI, JOS-NIIN) voidaan soveltaa käytännön ongelmanratkaisussa monin tavoin.

### Ehtolauseiden käyttö päätöksenteossa

Ehtolauseet ovat keskeinen osa loogista päättelyä ja algoritmista ajattelua. Ne toimivat muodossa "JOS ehto, NIIN toiminto, MUUTEN toinen toiminto".

Esimerkki arkielämän ehtolauseesta:
```
JOS ulkona sataa
    ota sateenvarjo mukaan
MUUTEN JOS on aurinkoista
    ota aurinkolasit mukaan
MUUTEN
    tarkista sääennuste uudelleen
```

### Loogisten porttien soveltaminen

Loogisia portteja (JA, TAI, EI) käytetään digitaalisissa järjestelmissä, mutta niitä voidaan soveltaa myös arkipäivän päätöksenteossa:

- **JA-operaatio**: Molemmat ehdot täytyy täyttyä
  - "Menen elokuviin, JOS minulla on vapaata JA elokuva on kiinnostava"

- **TAI-operaatio**: Vähintään toisen ehdoista täytyy täyttyä
  - "Tarvitsen kulkuvälineen, jos matka on pitkä TAI sää on huono"

- **EI-operaatio**: Ehdon kieltäminen
  - "Menen ulos, JOS EI sada"

## Ohjelmoinnillinen ajattelu käytännössä

Ohjelmoinnillinen ajattelu (computational thinking) on ongelmanratkaisutapa, joka hyödyntää tietojenkäsittelyn periaatteita. Sen keskeisiä elementtejä ovat:

### 1. Dekompositio
Ongelman pilkkominen pienempiin osiin, esimerkiksi:
- Ruoanlaitto: ostoslistan laatiminen, ainesten hankinta, esivalmistelu, varsinainen valmistus, tarjoilu

### 2. Kaavojen tunnistaminen
Säännönmukaisuuksien havaitseminen, esimerkiksi:
- Liikennevalojen vaihtumisrytmi
- Vuodenaikojen kierto
- Viikkorutiinit

### 3. Abstrahointi
Olennaisen tiedon tunnistaminen ja epäolennaisen sivuuttaminen, esimerkiksi:
- Kartta (abstraktio maastosta, joka sisältää vain olennaiset tiedot)
- Aikataulut (abstraktio päivän tapahtumista)

### 4. Algoritminen ajattelu
Askel askeleelta etenevien ohjeiden laatiminen, esimerkiksi:
- Ruokaresepti
- Kodin elektroniikan käyttöohjeet
- Reittisuunnitelma

### Ohjelmoinnillisen ajattelun arkikäyttö

Ohjelmoinnillista ajattelua voidaan soveltaa monissa ei-teknologisissa tilanteissa:

- **Projektisuunnittelu**: Tehtävien jako, riippuvuuksien tunnistaminen, resurssien kohdentaminen
- **Aikataulutus**: Optimaalisen reitin tai järjestyksen suunnittelu (esim. kauppaostokset, asiointi)
- **Opettaminen**: Monimutkaisten asioiden selittäminen yksinkertaisemmin, vaiheittain
- **Päätöksenteko**: Vaihtoehtojen systemaattinen arviointi, päätöspuiden käyttö

## Esimerkkejä ja harjoituksia

### Esimerkki 1: Arkipäivän algoritmi - kahvin keittäminen

Kahvin keittäminen voidaan esittää algoritmina:

```
1. Tarkista, onko kahvinpuruja ja vettä saatavilla
   JOS ei, hanki puuttuvat aineet
2. Mittaa vesi ja kaada se kahvinkeittimeen
3. Aseta suodatin kahvinkeittimeen
4. Mittaa kahvinpurut ja aseta ne suodattimeen
5. Kytke kahvinkeitin päälle
6. Odota, kunnes kahvi on valmista
7. Kaada kahvi kuppiin
```

### Esimerkki 2: Päätöspuu ruokapaikan valinnassa

Päätöspuu on visuaalinen tapa esittää loogista päätöksentekoprosessia:

```
Onko aikaa paljon?
|
+-- Kyllä --> Onko rahaa paljon?
|             |
|             +-- Kyllä --> Ravintolaillallinen
|             |
|             +-- Ei -----> Piknik puistossa
|
+-- Ei -----> Onko nälkä suuri?
              |
              +-- Kyllä --> Pikaruokaravintola
              |
              +-- Ei -----> Välipala kahvilassa
```

### Harjoitustehtävät

#### Harjoitus 1: Algoritmin suunnittelu

Suunnittele algoritmi reitin löytämiseksi kodistasi lähimpään kirjastoon. Kirjoita vaiheet selkeässä järjestyksessä ja huomioi mahdolliset ehtolauseet (esim. "JOS sataa, valitse reitti, jossa on katoksia").

#### Harjoitus 2: Loogisten operaatioiden soveltaminen

Muotoile seuraavat tilanteet käyttäen loogisia operaatioita (JA, TAI, EI, JOS-NIIN):

a) Milloin päätät pyöräillä töihin?
b) Millä perusteella valitset elokuvan katsottavaksi?
c) Miten päätät, mitä vaatteita puet päällesi aamulla?

#### Harjoitus 3: Ohjelmoinnillisen ajattelun soveltaminen

Valitse jokin arkipäivän tehtävä (esim. siivoaminen, harrastukseen valmistautuminen) ja sovella ohjelmoinnillisen ajattelun neljää vaihetta:
1. Dekompositio (jaa tehtävä osiin)
2. Kaavojen tunnistaminen (tunnista toistuvat elementit)
3. Abstrahointi (poimi olennaiset tekijät)
4. Algoritminen ajattelu (luo vaiheittainen prosessi)

---

## Seuraava aihe: [Kriittinen ajattelu](5-kriittinen-ajattelu.md)
