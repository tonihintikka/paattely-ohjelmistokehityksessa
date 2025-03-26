# Loogisen päättelyn periaatteet

[← Takaisin sisällysluetteloon](README.md) | [← Edellinen: Numeraalinen päättely](1-numeraalinen-paattely.md) | [Seuraava: Verbaalinen päättely →](3-verbaalinen-paattely.md)

## Sisältö
- [Johdanto loogiseen päättelyyn](#johdanto-loogiseen-päättelyyn)
- [Formaalin logiikan perusteet](#formaalin-logiikan-perusteet)
- [Deduktiivinen päättely](#deduktiivinen-päättely)
- [Logiikan kieli ja symbolit](#logiikan-kieli-ja-symbolit)
- [Argumenttien rakenne ja pätevyys](#argumenttien-rakenne-ja-pätevyys)
- [Päättelyvirheet](#päättelyvirheet)
- [Esimerkkejä ja harjoituksia](#esimerkkejä-ja-harjoituksia)

## Johdanto loogiseen päättelyyn

Logiikka on tieteen ja filosofian haara, joka tutkii päättelyn periaatteita, argumentaation pätevyyttä ja totuudenmukaisuuden rakenteita. Se keskittyy erityisesti siihen, miten väitteet ja väitelauseet liittyvät toisiinsa ja millä perusteilla voimme katsoa jonkin väitteen seuraavan toisista väitteistä.

Looginen päättely on johdonmukaista ajattelua, jossa yhdestä tai useammasta alkuoletuksesta eli premissistä johdetaan loogisia seurauksia. Se on ajattelun taito, joka mahdollistaa:

- Monimutkaisten ongelmien pilkkomisen osiin
- Johdonmukaisten päätelmien tekemisen
- Virheellisten argumenttien tunnistamisen
- Tiedon kriittisen arvioinnin

## Formaalin logiikan perusteet

Formaali logiikka on logiikan osa-alue, joka keskittyy pätevän päättelyn muodollisiin rakenteisiin. Siinä käytetään erityisiä symboleja ja merkintätapoja, jotka mahdollistavat päättelyrakenteiden tarkan analyysin.

Formaalin logiikan keskeisiä käsitteitä ovat:

### Lause (Propositio)
- Väite, joka voi olla joko tosi tai epätosi
- Esimerkki: "Helsinki on Suomen pääkaupunki" (tosi lause)
- Esimerkki: "2+2=5" (epätosi lause)

### Totuusarvo
- Lauseen ominaisuus olla joko tosi (T) tai epätosi (F)
- Klassisessa logiikassa ei ole "osittain tosia" lauseita

### Konnektiivit
Loogiset operaattorit, jotka yhdistävät lauseita:
- Negaatio (¬): "ei"
- Konjunktio (∧): "ja"
- Disjunktio (∨): "tai"
- Implikaatio (→): "jos-niin"
- Ekvivalenssi (↔): "jos ja vain jos"

### Tautologia
- Lause, joka on tosi kaikissa mahdollisissa tilanteissa
- Esimerkki: "Joko sataa tai ei sada"

### Ristiriita (Kontradiktio)
- Lause, joka on epätosi kaikissa mahdollisissa tilanteissa
- Esimerkki: "Sataa ja ei sada"

## Deduktiivinen päättely

Deduktiivinen päättely on loogisen päättelyn keskeinen muoto, jossa johtopäätös seuraa välttämättä premisseistä. Jos premissit ovat tosia ja päättely on muodollisesti pätevää, myös johtopäätöksen täytyy olla tosi.

Klassinen esimerkki deduktiivisesta päättelystä on syllogismi:

```
Premissi 1: Kaikki ihmiset ovat kuolevaisia.
Premissi 2: Sokrates on ihminen.
Johtopäätös: Sokrates on kuolevainen.
```

Deduktiivisen päättelyn erityispiirteitä:
- Johtopäätös sisältyy implisiittisesti premisseihin
- Johtopäätös ei sisällä uutta tietoa, jota ei olisi jo premisseissä
- Pätevä deduktiivinen päättely säilyttää totuuden premisseistä johtopäätökseen
- Se etenee yleisestä yksityiseen

## Logiikan kieli ja symbolit

Formaalin logiikan kieli koostuu symboleista, jotka mahdollistavat loogisten rakenteiden täsmällisen ilmaisun.

### Propositiologiikan symbolit

- Propositioita merkitään usein kirjaimilla p, q, r, ...
- Konnektiivit:
  - Negaatio: ¬p ("ei p")
  - Konjunktio: p ∧ q ("p ja q")
  - Disjunktio: p ∨ q ("p tai q")
  - Implikaatio: p → q ("jos p, niin q")
  - Ekvivalenssi: p ↔ q ("p jos ja vain jos q")

### Predikaattilogiikan symbolit

- Kvanttorit:
  - Universaalikvanttori: ∀x ("kaikille x")
  - Eksistenssikvanttori: ∃x ("on olemassa x")
- Predikaatit: P(x) ("x:llä on ominaisuus P")
- Relaatiot: R(x,y) ("x on relaatiossa R y:hyn")

## Argumenttien rakenne ja pätevyys

Loogisessa päättelyssä argumentti koostuu premisseistä ja johtopäätöksestä. Argumentin muodollista pätevyyttä voidaan analysoida seuraavien käsitteiden avulla:

### Pätevyys (Validiteetti)

Argumentti on pätevä, jos johtopäätös seuraa loogisesti premisseistä. Tämä tarkoittaa, että jos kaikki premissit olisivat tosia, myös johtopäätöksen olisi oltava tosi.

Esimerkki pätevästä argumentista:
```
Premissi 1: Jos sataa, tie on märkä.
Premissi 2: Sataa.
Johtopäätös: Tie on märkä.
```

Esimerkki epäpätevästä argumentista:
```
Premissi 1: Jos sataa, tie on märkä.
Premissi 2: Tie on märkä.
Johtopäätös: Sataa.
```
(Tämä on virheellinen, koska tie voi olla märkä muistakin syistä.)

### Totuudenmukaisuus (Perusteltavuus)

Argumentti on totuudenmukainen, jos sen premissit ovat tosia. On huomattava, että pätevä argumentti voi perustua epätosiin premisseihin.

### Pitävyys (Kestävyys)

Argumentti on pitävä, jos se on sekä pätevä että totuudenmukainen (premissit ovat tosia). Pitävä argumentti johtaa väistämättä tosiin johtopäätöksiin.

## Päättelyvirheet

Päättelyvirheet ovat loogisia virheitä argumentaatiossa. Ne voivat näyttää pinnallisesti vakuuttavilta, mutta eivät noudata pätevän päättelyn sääntöjä.

### Formaalit päättelyvirheet

1. **Seurauksen vahvistaminen (Affirming the Consequent)**
   ```
   Jos p, niin q.
   q.
   Siis p.
   ```
   Virhe: Tie voi olla märkä muistakin syistä kuin sateesta.

2. **Edeltäjän kieltäminen (Denying the Antecedent)**
   ```
   Jos p, niin q.
   Ei p.
   Siis ei q.
   ```
   Virhe: Vaikka ei sataisikaan, tie voi silti olla märkä muista syistä.

### Informaalit päättelyvirheet

1. **Ad Hominem (Henkilöön kohdistuva)**: Argumentin sijaan hyökätään sen esittäjää vastaan.
2. **Olkinukke (Straw Man)**: Vastustajan näkemyksen vääristely heikommaksi versioksi.
3. **Auktoriteettiin vetoaminen (Appeal to Authority)**: Väitteen perusteleminen pelkästään auktoriteetin näkemyksellä.
4. **Väärä dilemma (False Dilemma)**: Vaihtoehtojen keinotekoinen rajoittaminen kahteen.
5. **Kaltevan pinnan argumentti (Slippery Slope)**: Väite, että ensimmäinen askel johtaa väistämättä ääripäähän.

## Esimerkkejä ja harjoituksia

### Esimerkki: Pätevän argumentin analysointi

Tarkastellaan argumenttia:
```
Premissi 1: Kaikki planeetat ovat taivaankappaleita.
Premissi 2: Maa on planeetta.
Johtopäätös: Maa on taivaankappale.
```

Tämä voidaan formalisoida:
```
∀x(Planeetta(x) → Taivaankappale(x))
Planeetta(Maa)
∴ Taivaankappale(Maa)
```

Argumentti on pätevä, koska johtopäätös seuraa loogisesti premisseistä. Se on myös pitävä, koska premissit ovat tosia.

### Harjoitustehtävät

1. Arvioi argumentin pätevyys:
   ```
   Jos opiskelet ahkerasti, menestyt kokeessa.
   Et menestynyt kokeessa.
   Siis et opiskellut ahkerasti.
   ```

2. Tunnista seuraavassa päättelyvirhe:
   "Emme voi hyväksyä hänen näkemystään ilmastonmuutoksesta, koska hän ei ole ilmastotieteilijä."

3. Muodosta pätevä deduktiivinen argumentti käyttäen premissejä:
   - Kaikki nisäkkäät ovat selkärankaisia
   - Kaikki ihmiset ovat nisäkkäitä

---

## Seuraava aihe: [Verbaalinen päättely](3-verbaalinen-paattely.md)
