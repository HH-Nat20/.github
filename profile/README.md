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
- back-end: Kotlin, Spring Boot (Maven)
- mobiilisovellus: React Native, TypeScript
- tietokanta: PostgreSQL
- julkaisu: ?

Tutustu myös projektin repositorioihin:
- back-end: https://github.com/HH-Nat20/kamppis-server
- mobiilisovellus: https://github.com/HH-Nat20/kamppis-app

<img src="https://github.com/HH-Nat20/.github/blob/main/Nat20%20K%C3%A4mppis-sovelluksen%20arkkitehtuuri.png" alt="Kämppis-sovelluksen arkkitehtuuri" style="width:60%; height:auto;">

## Käyttäjätarinat

### Feature Epic

Title | Description
--- | ---
Kämppis-sovellus yhdistää kämppistä etsivät käyttäjät | “Kimppa-asumisesta kiinnostuneena **käyttäjänä** haluan alustan, jolla voin helposti ja turvallisesti löytää ja tutustua potentiaalisiin kämppäkavereihin.”

### Välttämättömät vaatimukset

_Näiden käyttäjätarinoiden toteutus muodostaa tuotteen demoversion._

Title | Description | Acceptance Criteria
--- | --- | ---
1. Käyttäjäprofiilin luominen ja omien tietojen syöttäminen | **Käyttäjänä** haluan luoda henkilökohtaisen profiilin, jotta muut käyttäjät näkevät, millainen olen. Profiiliin pitää voida liittää kuvia. | Käyttäjän tulee voida syöttää tietoja itsestään lomakkeeseen, kuten esimerkiksi<br>- puhelinnumero (unique)<br>- ikä<br>- sukupuoli<br>- opiskelut<br>- elämäntyyli, esim: siisteys,	vuorokausirytmi, juhliminen, tupakointi<br>- kiinnostuksen kohteet<br>- kämpän haluttu sijainti<br>- mahdolliset lemmikit tai allergiat<br>- kuvat

Title | Description | Acceptance Criteria | Resources
--- | --- | --- | ---
2. Kriteerien mukainen kämppis-profiilien haku | **Käyttäjänä** haluan asettaa hakukriteereitä (esim. sukupuoli, sijainti, elämäntyyli, lemmikit), jotta näen vain profiilit, jotka vastaavat tarpeitani. Jos vastaavia tarpeita on paljon, profiili erottuu muista (esim. ”Supersopiva” tms. tagi). | Sovellus tarjoaa käyttäjälle helppokäyttöisen hakutoiminnon, jossa voidaan asettaa suodattimia vastakämppikselle, kuten:<br>- sukupuoli<br>- ikähaarukka<br>- elämäntyyli<br>- kämpän sijainti<br>- kipuraja omalle osuudelle kämpän vuokrasta<br>- kämppisten määrä | [Tähän mockup-kuva]

Title | Description | Acceptance Criteria | Resources
--- | --- | --- | ---
3. Profiilien selaaminen | **Käyttäjänä** haluan helposti selata muiden käyttäjien profiilien tärkeimpiä tietoja, jotta voin nopeasti arvioida, sopisimmeko kämppiksiksi. | Ensinäkymä profiilista näyttää kuvan ja tärkeimmät tiedot, kuten<br>- nimi<br>- ikä<br>- sijainti<br>- lyhyt teaser-teksti itsestään | [Tähän mockup-kuva]

Title | Description | Acceptance Criteria | Resources
--- | --- | --- | ---
4. Profiilin tarkempi kuvaus | **Käyttäjänä** haluan nähdä valitun käyttäjän koko profiilin, jotta voin arvioida, sopisimmeko kämppiksiksi. | Profiilin näkymä on selkeä ja sisältää olennaiset tiedot (esim. nimi, ikä, elämäntyyli, sijainti). | [Tähän mockup-kuva]

Title | Description | Acceptance Criteria | Resources
--- | --- | --- | ---
5. Kiinnostuksen ilmaiseminen | **Käyttäjänä** haluan ilmaista kiinnostukseni tiettyä profiilikorttia kohtaan, jotta voin saada mahdollisuuden tutustua tarkemmin. | Käyttäjä voi pyyhkäistä profiilikorttia oikealle tai vasemmalle. Jos molemmat osapuolet ovat pyyhkäisseet toistensa kortteja oikealle, luo sovellus yhteyden. Jos jompikumpi on pyyhkäissyt vasemmalle, sovellus ei luo yhteyttä. | [Tähän mockup-kuva]

Title | Description | Acceptance Criteria | Resources
--- | --- | --- | ---
6. Chat-ominaisuus | **Käyttäjänä** haluan chatata potentiaalisen kämppäkaverin kanssa, jotta voimme keskustella tarkemmin ja selvittää, sopisimmeko yhteen. Kumpi tahansa osapuoli voi lopettaa chatin kesken milloin tahansa. | Chat avautuu vain, jos molemmat käyttäjät ovat ilmaisseet kiinnostuksensa toisiinsa. Chattiin voi syöttää tekstiä, emojeita ja GIF-animaatioita. | [Tähän mockup-kuva]

### Hyödylliset vaatimukset

_Näiden käyttäjätarinoiden sekä välttämättömien käyttäjätarinoiden toteutus muodostaa tuotteen valmiin version._

Title | Description | Acceptance Criteria
--- | --- | ---
7. Sisäänkirjautuminen | **Käyttäjänä** haluan kirjautua sisään olemassa olevalle profiilille. | Käyttäjä voi kirjautua takaisin olemassa olevalle tilille OAuthin avulla. Käyttäjä ei voi kirjautua muulle kuin omalle profiililleen. Käyttäjää ei kirjata automaattisesti sisään, jos hän on aiemmin kirjautunut ulos.

Title | Description | Acceptance Criteria
--- | --- | ---
8. Käyttäjäprofiilin omien tietojen muokkaaminen | **Käyttäjänä** haluan muokata henkilökohtaisen profiilini tietoja, jotta omat tietoni ovat ajan tasalla ja muut käyttäjät saavat minusta realistisen kuvan. | Käyttäjän tulee voida muokata omia tietojaan oman profiilinsa kautta sekä tallentaa muokatut tiedot.

Title | Description | Acceptance Criteria
--- | --- | ---
9. Kopio omista tiedoista | **Käyttäjänä** haluan pyytää kopiota omista tiedoistani käyttäjäprofiilissani, jotta minulle selviää, mitä tietoja minusta varastoidaan. | Käyttäjäprofiilissa on ”Kopio omista tiedoista”-painike. Sitä painettaessa käyttäjä saa ilmoituksen pyynnön onnistumisesta sekä kopion tiedoistaan ilmoittamaansa sähköpostiosoitteeseen.

Title | Description | Acceptance Criteria
--- | --- | ---
10. Käyttäjäprofiilin poistaminen | **Käyttäjänä** haluan poistaa oman profiilini, mikäli en halua enää jatkaa sovelluksen käyttöä. | Käyttäjän tulee voida poistaa oma profiilinsa ja kaikki omat tietonsa sovelluksesta tietosuojakäytäntöjen (GDPR) mukaisesti.

Title | Description | Acceptance Criteria | Resources
--- | --- | --- | ---
11. Ilmoitukset | **Käyttäjänä** haluan saada ilmoituksia, kun joku ilmaisee kiinnostuksensa profiiliani kohtaan, jotta tiedän, milloin on tarpeen tarkistaa sovellus. | Ilmoitukset ovat reaaliaikaisia ja sisältävät tarpeeksi tietoa, jotta käyttäjä tietää, mitä tapahtui. | [Tähän mockup-kuva]

Title | Description | Acceptance Criteria
--- | --- | ---
12. Käyttäjän tietojen yksityisyys | **Käyttäjänä** haluan, että vain valitsemani tiedot ovat näkyvillä sovelluksen käyttäjille, jotta voin käyttää sovellusta turvallisesti. | Profiilin asetuksissa käyttäjä voi hallita, mitä tietoja jaetaan. Voin myös piilottaa profiilini näkyvistä muilta käyttäjiltä. Käyttäjän tulee myös hyväksyä sovelluksen palveluehdot ennen kuin voi käyttää sovellusta.

Title | Description | Acceptance Criteria
--- | --- | ---
13. Toisen käyttäjän ilmiantaminen | **Käyttäjänä** haluan pystyä ilmiantamaan asiattoman viestin tai profiilin, jotta voin suojella itseäni ja muita häiritsevältä käytökseltä. | Käyttäjä voi painaa "Ilmianna" viestin tai profiilin kohdalla, ja ilmianto lähetetään tarkistettavaksi.

Title | Description | Acceptance Criteria
--- | --- | ---
14. Käyttäjäpalautteen antaminen | **Käyttäjänä** haluan antaa palautetta sovelluksen käytöstä ja toiminnasta. | Sovelluksessa on yksinkertainen palautteenantotoiminto.

### Valinnaiset vaatimukset

_Näiden käyttäjätarinoiden toteutus on ylimääräistä extraa tuotteeseen._

Title | Description | Acceptance Criteria
--- | --- | ---
15. Premium-toiminnot | **Käyttäjänä** haluan ostaa Premium-version sovelluksesta, jotta saan käyttööni lisätoimintoja. | Sovelluksessa on mahdollisuus ostaa Premium-versio. Premium-käyttäjä voi nähdä omasta profiilista kiinnostuneet käyttäjät ilman chat-yhteyden luontia. Voin myös peruuttaa viimeisimmän pyyhkäisyn, jos tein virheen.

Title | Description | Acceptance Criteria
--- | --- | ---
16. Ohjeet turvalliseen kanssakäymiseen sovelluksessa ja sen ulkopuolella | **Käyttäjänä** haluan saada ohjeita siitä, miten toimia sovelluksessa ja sen ulkopuolella muiden käyttäjien kanssa turvallisesti ja vastuullisesti. | Sovellus antaa sopivassa kohdassa käyttäjälle luettavaksi lyhyen ohjeen siitä, miten kommunikoida ja tavata turvallisesti muiden käyttäjien kanssa.

Title | Description | Acceptance Criteria
--- | --- | ---
17. Käyttäjän shadowbannaaminen | **Adminina** haluan pystyä estämään häiritsevien käyttäjien näkyvyyden muille käyttäjille ilman, että he huomaavat sitä, jotta voin suojella yhteisöä ja estää väärinkäytöksiä tehokkaasti. | <br>- Shadowbannattu käyttäjä voi edelleen kirjautua, selata profiileja ja "swaipata", mutta hänen profiiliaan ei näytetä muille käyttäjille, eikä hän saa yhteyksiä tai mätsäyksiä.<br>- Admin voi asettaa shadowbannauksen manuaalisesti tai automaattisesti raporttien ja algoritmien perusteella.<br>- Shadowbannaus ei näy käyttäjälle, eikä järjestelmä anna siitä mitään ilmoitusta.

Title | Description | Acceptance Criteria
--- | --- | ---
18. Ilmiantamisen automaattinen tarkastus | **Adminina** haluan, että järjestelmä merkitsee automaattisesti ilmiannetut viestit asiattomiksi tai ei-asiattomiksi, jotta voin priorisoida tarkistettavat tapaukset. | <br>- Järjestelmä analysoi ilmiannot automaattisesti, esimerkiksi syöttämällä ilmiannettu viesti tai profiili AI:lle.<br>- Jos järjestelmä tunnistaa viestin asiattomaksi, sen lähettäjä asetetaan väliaikaiseen banniin, jolloin hän ei voi käyttää sovellusta ennen ylläpitäjän tarkistusta.<br>- Väliaikaisen bannin aikana käyttäjälle näytetään viesti, jossa kerrotaan, että hänen viestinsä on ilmoitettu asiattomaksi.<br>- Admin tarkistaa tapauksen mahdollisimman pian. Jos admin toteaa viestin olleen asiattoman, bannaus pysyy voimassa ja käyttäjälle ilmoitetaan tuomion syy. Jos viesti osoittautuu vääräksi hälytykseksi, bannaus poistetaan ja käyttäjälle ilmoitetaan päätöksestä.

Title | Description | Acceptance Criteria
--- | --- | ---
19. Sokkomätsi-toiminto | **Käyttäjänä** haluan yrittää löytää kämppiksen ilman rajoitteita tai hakukriteereitä ja antaa sattuman ratkaista. | <br>- Sokkomätsi-toiminto on valittavissa erillisenä ominaisuutena sovelluksen sisällä.<br>- Käyttäjä voi painaa "Sokkomätsi"-painiketta ja odottaa, että järjestelmä yhdistää hänet satunnaiseen toiseen käyttäjään, joka on myös käyttänyt sokkomätsiä.<br>- Sokkomätsi ei huomioi hakukriteerejä tai käyttäjien profiilissa ilmoitettuja toiveita.<br>- Kun sokkomätsi onnistuu:<br>- Molemmat käyttäjät saavat ilmoituksen ja pääsevät keskustelemaan toistensa kanssa chatin välityksellä.<br>- Molemmille näytetään perustiedot toisesta käyttäjästä (esim. nimi, ikä ja sijainti, jos käyttäjä on sallinut niiden jaon).<br>- Jos sokkomätsi ei löydä paria kohtuullisessa ajassa (esim. 1 minuutti), käyttäjälle ilmoitetaan, ettei muita sokkomätsi-käyttäjiä ole juuri nyt saatavilla.

Title | Description | Acceptance Criteria
--- | --- | ---
20. Käyttäjätuen ominaisuus | **Käyttäjänä** haluan ottaa yhteyttä asiakastukeen, jos kohtaan ongelmia sovelluksessa, jotta saan apua nopeasti. | Sovelluksessa on yksinkertainen tukipyyntötoiminto.

## Vaatimukset

## Käyttöehdot & tietoturva
Tietoturva, tietosuoja, GDPR, tietokannan suojaus 

## Ota yhteyttä

 
