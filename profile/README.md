# Kämppis

## Mikä _Kämppis_?
_Kämppis_ on mobiilisovellus, joka yhdistää kämppiksiä etsivät ihmiset toistensa kanssa.

## Miksi _Kämppis_?
_Kämppis_ pyrkii vaikuttamaan positiivisesti käyttäjiensä elämään.

Suomen punaisen ristin teettämän [yksinäisyysbarometrin](https://www.punainenristi.fi/uutiset/2023/yksinaisyys-koskettaa-yha-useampaa-suomessa/) mukaan kolmannes 15–24-vuotiaista nuorista tuntee itsensä yksinäiseksi kuukausittain. Lisäksi inflaatio, asuinkustannusten nousu sekä hallituksen kaavailemat muutokset opiskelijoiden asumistukeen tekevät kimppa-asumisesta myös taloudellisesti houkuttelevan vaihtoehdon.

_Kämppis_ vastaa tähän haasteeseen tarjoamalla kimppa-asumista harkitseville alustan löytää toisensa.

## Miten _Kämppis_ toimii?
Kimppa-asumisesta kiinnosunut käyttä luo profiilin _Kämppikseen_. Käyttäjä pääsee selaamaan muiden rekisteröityneiden käyttäjien profiileja ja halutessaan asettaa kriteerejä, joiden mukaan _Kämppis_ etsii ja näyttää käyttäjälle muiden käyttäjien profiileja. Kriteereinä voi olla esim. kämppäkaverin toivottu sukupuoli, elämäntyyli, kimppakämpän sijainti, lemmikit jne. Käyttäjä voi ilmaista, mikäli haluaa saada tietää jostakin käyttäjästä enemmän. Mikäli kaksi käyttäjää haluaa tutustua toisiinsa mahdollisina tulevina kämppäkavereina, avaa _Kämppis_ heille chat-mahdollisuuden.

_Kämppis_ tarjoaa kimppa-asumisesta kiinnostuneille käyttäjille vain mahdollisuuden löytää toisiaan ja tutustua toisiinsa. _Kämppis_ ei sisällä ominaisuuksia esimerkiksi kimppa-asunnon etsimiseen tai muihin asumiseen liittyviin käytännön seikkoihin.

## Teknologiat
_Kämppis_ on rakennettu käyttämällä seuraavia teknologioita:
- back-end: Kotlin, Spring Boot (Gradle)
- mobiilisovellus: React Native, TypeScript
- tietokanta: PostgreSQL
- julkaisu: ?

Tutustu myös projektin repositorioihin:
- back-end: https://github.com/HH-Nat20/kamppis-server
- mobiilisovellus: https://github.com/HH-Nat20/kamppis-app

## Sovelluksen arkkitehtuuri
<details>
 <summary>Klikkaa avataksesi sovelluksen arkkitehtuurikuvan</summary>
 <img src="https://github.com/HH-Nat20/.github/blob/main/Nat20%20K%C3%A4mppis-sovelluksen%20arkkitehtuuri.png" alt="Kämppis-sovelluksen arkkitehtuuri" style="width:60%; height:auto;">
</details>

## Käyttäjätarinat ja vaatimukset

### Feature Epic
**Title**: Kämppis-sovellus yhdistää kämppistä etsivät käyttäjät<br>
**Description**: “Kimppa-asumisesta kiinnostuneena _käyttäjänä_ haluan alustan, jolla voin helposti ja turvallisesti löytää ja tutustua potentiaalisiin kämppäkavereihin.”

### Välttämättömät vaatimukset
_Näiden käyttäjätarinoiden toteutus muodostaa tuotteen demoversion._

<details>
<summary><b>Title</b>: 1. Käyttäjäprofiilin luominen ja omien tietojen syöttäminen</summary>
<b>Description:</b>	Käyttäjänä haluan luoda henkilökohtaisen profiilin, jotta muut käyttäjät näkevät, millainen olen. Profiiliin pitää voida liittää kuvia.<br>
<b>Acceptance Criteria</b>:	Käyttäjän tulee voida syöttää tietoja itsestään lomakkeeseen, kuten esimerkiksi<br>
- puhelinnumero (unique)<br>
- ikä<br>
- sukupuoli<br>
- opiskelut<br>
- elämäntyyli, esim: siisteys, vuorokausirytmi, juhliminen, tupakointi<br>
- kiinnostuksen kohteet<br>
- kämpän haluttu sijainti<br>
- mahdolliset lemmikit tai allergiat<br>
- kuvat<br>
</details>

<details>
<summary><b>Title</b>:	2. Kriteerien mukainen kämppis-profiilien haku</summary>
<b>Description</b>:	Käyttäjänä haluan asettaa hakukriteereitä (esim. sukupuoli, sijainti, elämäntyyli, lemmikit), jotta näen vain profiilit, jotka vastaavat tarpeitani. Jos vastaavia tarpeita on paljon, profiili erottuu muista (esim. ”Supersopiva” tms. tagi).<br>
<b>Acceptance Criteria</b>:	Sovellus tarjoaa käyttäjälle helppokäyttöisen hakutoiminnon, jossa voidaan asettaa suodattimia vastakämppikselle, kuten:<br>
- sukupuoli<br>
- ikähaarukka<br>
- elämäntyyli<br>
- kämpän sijainti<br>
- kipuraja omalle osuudelle kämpän vuokrasta<br>
- kämppisten määrä<br>
<b>Resources</b>:	[Tähän mockup-kuva]
</details>

<details>
<summary><b>Title</b>: 3. Profiilien selaaminen</summary>
<b>Description</b>: Käyttäjänä haluan helposti selata muiden käyttäjien profiilien tärkeimpiä tietoja, jotta voin nopeasti arvioida, sopisimmeko kämppiksiksi.<br>
<b>Acceptance Criteria</b>: Ensinäkymä profiilista näyttää kuvan ja tärkeimmät tiedot, kuten<br>
- nimi<br>
- ikä<br>
- sijainti<br>
- lyhyt teaser-teksti itsestään<br>
<b>Resources</b>: [Tähän mockup-kuva]
</details>

<details>
<summary><b>Title</b>:	4. Profiilin tarkempi kuvaus</summary>
<b>Description</b>:	Käyttäjänä haluan nähdä valitun käyttäjän koko profiilin, jotta voin arvioida, sopisimmeko kämppiksiksi.<br>
<b>Acceptance Criteria</b>	Profiilin näkymä on selkeä ja sisältää olennaiset tiedot (esim. nimi, ikä, elämäntyyli, sijainti).<br>
<b>Resources</b>: [Tähän mockup-kuva]
</details>

<details>
<summary><b>Title</b>:	5. Kiinnostuksen ilmaiseminen</summary>
<b>Description</b>:	Käyttäjänä haluan ilmaista kiinnostukseni tiettyä profiilikorttia kohtaan, jotta voin saada mahdollisuuden tutustua tarkemmin.<br>
<b>Acceptance Criteria</b>:	Käyttäjä voi pyyhkäistä profiilikorttia oikealle tai vasemmalle. Jos molemmat osapuolet ovat pyyhkäisseet toistensa kortteja oikealle, luo sovellus yhteyden. Jos jompikumpi on pyyhkäissyt vasemmalle, sovellus ei luo yhteyttä.<br>
<b>Resources</b>: [Tähän mockup-kuva]
</details>

<details>
<summary><b>Title</b>:	6. Chat-ominaisuus</summary>
<b>Description</b>	Käyttäjänä haluan chatata potentiaalisen kämppäkaverin kanssa, jotta voimme keskustella tarkemmin ja selvittää, sopisimmeko yhteen. Kumpi tahansa osapuoli voi lopettaa chatin kesken milloin tahansa.<br>
<b>Acceptance Criteria</b>:	Chat avautuu vain, jos molemmat käyttäjät ovat ilmaisseet kiinnostuksensa toisiinsa. Chattiin voi syöttää tekstiä, emojeita ja GIF-animaatioita.<br>
<b>Resources</b>: [Tähän mockup-kuva]
</details>

### Hyödylliset vaatimukset
_Näiden käyttäjätarinoiden sekä välttämättömien käyttäjätarinoiden toteutus muodostaa tuotteen valmiin version._

<details>
<summary><b>Title</b>:	7. Sisäänkirjautuminen</summary>
<b>Description</b>:	Käyttäjänä haluan kirjautua sisään olemassa olevalle profiilille.<br>
<b>Acceptance Criteria</b>:	Käyttäjä voi kirjautua takaisin olemassa olevalle tilille OAuthin avulla. Käyttäjä ei voi kirjautua muulle kuin omalle profiililleen. Käyttäjää ei kirjata automaattisesti sisään, jos hän on aiemmin kirjautunut ulos.<br>
</details>

<details>
<summary><b>Title</b>:	8. Käyttäjäprofiilin omien tietojen muokkaaminen</summary>
<b>Description</b>:	Käyttäjänä haluan muokata henkilökohtaisen profiilini tietoja, jotta omat tietoni ovat ajan tasalla ja muut käyttäjät saavat minusta realistisen kuvan.<br>
<b>Acceptance Criteria</b>:	Käyttäjän tulee voida muokata omia tietojaan oman profiilinsa kautta sekä tallentaa muokatut tiedot.<br>
</details>

<details>
<summary><b>Title</b>: 9. Kopio omista tiedoista</summary>
<b>Description</b>: Käyttäjänä haluan pyytää kopiota omista tiedoistani käyttäjäprofiilissani, jotta minulle selviää, mitä tietoja minusta varastoidaan.<br>
<b>Acceptance Criteria</b>: Käyttäjäprofiilissa on ”Kopio omista tiedoista”-painike. Sitä painettaessa käyttäjä saa ilmoituksen pyynnön onnistumisesta sekä kopion tiedoistaan ilmoittamaansa sähköpostiosoitteeseen.<br>
</details>

<details>
<summary><b>Title</b>:	10. Käyttäjäprofiilin poistaminen</summary>
<b>Description</b>:	Käyttäjänä haluan poistaa oman profiilini, mikäli en halua enää jatkaa sovelluksen käyttöä.<br>
<b>Acceptance Criteria</b>:	Käyttäjän tulee voida poistaa oma profiilinsa ja kaikki omat tietonsa sovelluksesta tietosuojakäytäntöjen (GDPR) mukaisesti.
</details>

<details>
<summary><b>Title</b>: 11. Ilmoitukset</summary>
<b>Description</b>: Käyttäjänä haluan saada ilmoituksia, kun joku ilmaisee kiinnostuksensa profiiliani kohtaan, jotta tiedän, milloin on tarpeen tarkistaa sovellus.<br>
<b>Acceptance Criteria</b>: Ilmoitukset ovat reaaliaikaisia ja sisältävät tarpeeksi tietoa, jotta käyttäjä tietää, mitä tapahtui.<br>
<b>Resources</b>: [Tähän mockup-kuva]
</details>

<details>
<summary><b>Title</b>: 12. Käyttäjän tietojen yksityisyys</summary>
<b>Description</b>: Käyttäjänä haluan, että vain valitsemani tiedot ovat näkyvillä sovelluksen käyttäjille, jotta voin käyttää sovellusta turvallisesti.<br>
<b>Acceptance Criteria</b>: Profiilin asetuksissa käyttäjä voi hallita, mitä tietoja jaetaan. Käyttäjä voi myös piilottaa profiilini näkyvistä muilta käyttäjiltä. Käyttäjän tulee myös hyväksyä sovelluksen palveluehdot ennen kuin voi käyttää sovellusta.<br>
</details>

<details>
<summary><b>Title</b>:	13. Toisen käyttäjän ilmiantaminen</summary>
<b>Description</b>:	Käyttäjänä haluan pystyä ilmiantamaan asiattoman viestin tai profiilin, jotta voin suojella itseäni ja muita häiritsevältä käytökseltä.<br>
<b>Acceptance Criteria</b>:	Käyttäjä voi painaa "Ilmianna" viestin tai profiilin kohdalla, ja ilmianto lähetetään tarkistettavaksi.<br>
</details>

<details>
<summary><b>Title</b>: 14. Käyttäjäpalautteen antaminen</summary>
<b>Description</b>: Käyttäjänä haluan antaa palautetta sovelluksen käytöstä ja toiminnasta.<br>
<b>Acceptance Criteria</b>: Sovelluksessa on yksinkertainen palautteenantotoiminto.<br>
</details>

<details>
<summary><b>Title</b>:	15. Kämppä</summary>
<b>Description</b>:	Käyttäjänä haluan ilmoittaa, minkälaista kämppää haen, tai jos minulla on kämppä, syöttää sen tiedot.<br>
<b>Acceptance Criteria</b>:	Käyttäjä voi ilmoittaa profiilissaan, hakeeko hän kämppää vai kämppistä. Kämpän tai halutun kämpän ominaisuudet löytyvät profiilista.<br>
</details>

### Valinnaiset vaatimukset
_Näiden käyttäjätarinoiden toteutus on ylimääräistä extraa tuotteeseen._

<details>
<summary><b>Title</b>: 16. Premium-toiminnot</summary>
<b>Description</b>: Käyttäjänä haluan ostaa Premium-version sovelluksesta, jotta saan käyttööni lisätoimintoja.<br>
<b>Acceptance Criteria</b>: Sovelluksessa on mahdollisuus ostaa Premium-versio. Premium-käyttäjä voi nähdä omasta profiilista kiinnostuneet käyttäjät ilman chat-yhteyden luontia. Voin myös peruuttaa viimeisimmän pyyhkäisyn, jos tein virheen. Asunnon haltijana toimivana käyttäjä voin myös valita profiilistani AutoLike-ominaisuuden, jonka avulla mätsään automaattisesti kaikkien niiden profiilien kanssa, jotka tykkäävät profiilistani. Voin käyttää tekoälyä kirjoittamaan biostani lyhennettyjä "prompteja", jotka näkyvät profiilikorttini yhteydessä.<br>
</details>

<details>
<summary><b>Title</b>: 17. Ohjeet turvalliseen kanssakäymiseen sovelluksessa ja sen ulkopuolella</summary>
<b>Description</b>: Käyttäjänä haluan saada ohjeita siitä, miten toimia sovelluksessa ja sen ulkopuolella muiden käyttäjien kanssa turvallisesti ja vastuullisesti.<br>
<b>Acceptance Criteria</b>: Sovellus antaa sopivassa kohdassa käyttäjälle luettavaksi lyhyen ohjeen siitä, miten kommunikoida ja tavata turvallisesti muiden käyttäjien kanssa.<br>
</details>

<details>
<summary><b>Title</b>: 18. Käyttäjän shadowbannaaminen</summary>
<b>Description</b>: Adminina haluan pystyä estämään häiritsevien käyttäjien näkyvyyden muille käyttäjille ilman, että he huomaavat sitä, jotta voin suojella yhteisöä ja estää väärinkäytöksiä tehokkaasti.<br>
<b>Acceptance Criteria</b>:<br>
- Shadowbannattu käyttäjä voi edelleen kirjautua, selata profiileja ja "swaipata", mutta hänen profiiliaan ei näytetä muille käyttäjille, eikä hän saa yhteyksiä tai mätsäyksiä.<br>
- Admin voi asettaa shadowbannauksen manuaalisesti tai automaattisesti raporttien ja algoritmien perusteella.<br>
- Shadowbannaus ei näy käyttäjälle, eikä järjestelmä anna siitä mitään ilmoitusta.<br>
</details>

<details>
<summary><b>Title</b>: 19. Ilmiantamisen automaattinen tarkastus</summary>
<b>Description</b>: Adminina haluan, että järjestelmä merkitsee automaattisesti ilmiannetut viestit asiattomiksi tai ei-asiattomiksi, jotta voin priorisoida tarkistettavat tapaukset.<br>
<b>Acceptance Criteria</b>:<br>
- Järjestelmä analysoi ilmiannot automaattisesti, esimerkiksi syöttämällä ilmiannettu viesti tai profiili AI:lle.<br>
- Jos järjestelmä tunnistaa viestin asiattomaksi, sen lähettäjä asetetaan väliaikaiseen banniin, jolloin hän ei voi käyttää sovellusta ennen ylläpitäjän tarkistusta.<br>
- Väliaikaisen bannin aikana käyttäjälle näytetään viesti, jossa kerrotaan, että hänen viestinsä on ilmoitettu asiattomaksi.<br>
- Admin tarkistaa tapauksen mahdollisimman pian.<br>
- Jos admin toteaa viestin olleen asiattoman, bannaus pysyy voimassa ja käyttäjälle ilmoitetaan tuomion syy.<br>
- Jos viesti osoittautuu vääräksi hälytykseksi, bannaus poistetaan ja käyttäjälle ilmoitetaan päätöksestä.v
</details>

<details>
<summary><b>Title</b>: 20. Sokkomätsi-toiminto</summary>
<b>Description</b>: Käyttäjänä haluan yrittää löytää kämppiksen ilman rajoitteita tai hakukriteereitä ja antaa sattuman ratkaista.<br>
<b>Acceptance Criteria</b>:<br>
- Sokkomätsi-toiminto on valittavissa erillisenä ominaisuutena sovelluksen sisällä.<br>
- Käyttäjä voi painaa "Sokkomätsi"-painiketta ja odottaa, että järjestelmä yhdistää hänet satunnaiseen toiseen käyttäjään, joka on myös käyttänyt sokkomätsiä.<br>
- Sokkomätsi ei huomioi hakukriteerejä tai käyttäjien profiilissa ilmoitettuja toiveita.<br>
<b>Kun sokkomätsi onnistuu:</b><br>
- Molemmat käyttäjät saavat ilmoituksen ja pääsevät keskustelemaan toistensa kanssa chatin välityksellä.<br>
- Molemmille näytetään perustiedot toisesta käyttäjästä (esim. nimi, ikä ja sijainti, jos käyttäjä on sallinut niiden jaon).<br>
- Jos sokkomätsi ei löydä paria kohtuullisessa ajassa (esim. 1 minuutti), käyttäjälle ilmoitetaan, ettei muita sokkomätsi-käyttäjiä ole juuri nyt saatavilla.<br>
</details>

<details>
<summary><b>Title</b>: 21. Käyttäjätuen ominaisuus</summary>
<b>Description</b>: Käyttäjänä haluan ottaa yhteyttä asiakastukeen, jos kohtaan ongelmia sovelluksessa, jotta saan apua nopeasti.<br>
<b>Acceptance Criteria</b>: Sovelluksessa on yksinkertainen tukipyyntötoiminto.<br>
</details>

## Käyttöehdot & tietoturva
[Tähän osio, jossa tietoturva, tietosuoja, GDPR, tietokannan suojaus]

## Ota yhteyttä
