<a id="readme-alku"></a>

<div align="center">
<img src="../kamppis-app-icon.png" alt="Kämppis-sovelluksen logo" width="120px" height="120px">
<h1><i>Kämppis</i></h1>
</div>

<br>
<details>
<summary><b>Sisällysluetto</b></summary>
  <ol>
    <li>
        <a href="#mikä-kämppis">Mikä <i>Kämppis</i>?</a>
    </li>
    <li>
        <a href="#miksi-kämppis">Miksi <i>Kämppis</i>?</a>
    </li>
    <li>
        <a href="#miten-kämppis-toimii">Miten <i>Kämppis</i> toimii?</a>
    </li>
    <li>
        <a href="#roadmap">Roadmap</a>
    </li>
    <li>
        <a href="#teknologiat">Teknologiat</a>
    </li>
    <li>
        <a href="#sovelluksen-arkkitehtuuri">Sovelluksen arkkitehtuuri</a>
    </li>
    <li>
        <a href="#käyttäjätarinat-ja-vaatimukset">Käyttäjätarinat ja vaatimukset</a>
    </li>
    <li>
        <a href="#käyttöehdot-ja-tietoturva">Käyttöehdot ja tietoturva</a>
    </li>
    <li>
        <a href="#lisenssi">Lisenssi</a>
    </li>
    <li>
        <a href="#ota-yhteyttä">Ota yhteyttä</a>
    </li>
  </ol>
</details><br>

## Mikä _Kämppis_?
_Kämppis_ on mobiilisovellus, joka yhdistää kämppiksiä ja kimppakämppähuoneita etsivät ihmiset toistensa kanssa.

Projekti on toteutettu osana Haaga-Helia ammattikorkeakoulun [Ohjelmistoprojekti 2](https://opinto-opas.haaga-helia.fi/course_unit/SOF007AS3A) -opintojaksoa.
<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

## Miksi _Kämppis_?
_Kämppis_ pyrkii vaikuttamaan positiivisesti käyttäjiensä elämään.

Suomen punaisen ristin teettämän [yksinäisyysbarometrin](https://www.punainenristi.fi/uutiset/2023/yksinaisyys-koskettaa-yha-useampaa-suomessa/) mukaan kolmannes 15–24-vuotiaista nuorista tuntee itsensä yksinäiseksi kuukausittain. Lisäksi inflaatio, asuinkustannusten nousu sekä hallituksen kaavailemat muutokset opiskelijoiden asumistukeen tekevät kimppa-asumisesta myös taloudellisesti houkuttelevan vaihtoehdon.

_Kämppis_ vastaa tähän haasteeseen tarjoamalla kimppa-asumista harkitseville alustan löytää toisensa.
<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

## Miten _Kämppis_ toimii?
Kimppa-asumisesta kiinnostunut käyttäjä luo profiilin _Kämppikseen_. Käyttäjä voi toistaiseksi kirjautua käyttämällä GitHub-tiliään. Kirjautunut käyttäjä voi sovelluksessa muokata omaa profiiliaan, kämppis- ja huonepreferenssejään sekä valitsemaan, etsiikö hän toista kämppistä uutta kimppakämppää varten, tyhjää huonetta olemassa olevasta kimppakämpässä vai uutta kämppista oman kimppakämppänsä tyhjään huoneeseen.

Käyttäjä pääsee selaamaan muiden rekisteröityneiden käyttäjien profiileja. Käyttäjä näkee toisten käyttäjien tai vapaiden huoneiden profiileja omien preferenssiensä mukaisesti. Preferenssejä voi olla esimerkiksi kämppäkaverin ikä ja sukupuoli tai kimppakämppähuoneen sijainti, kimppakämpän kämppisten lukumäärä ja vuokra. Löytäessään sopivan kämppiksen tai huoneen käyttäjä voi kertoa olevansa kiinnostunut niistä pyyhkäisemällä profiilin oikealle. Mikäli profiili ei kiinnosta käyttäjää, hän voi siirtyä seuraavaan profiiliin pyyhkäisemällä vasemmalle. Mikäli kaksi käyttäjää pyyhkäisee toisiaan oikealle, tai jos käyttäjä pyyhkäisee huonetta, jonka lisääjän pyyhkäisee käyttäjää, avaa _Kämppis_ heille chat-ikkunan. Käyttäjät voivat näin tutustua paremmin.

_Kämppis_ tarjoaa kimppa-asumisesta kiinnostuneille käyttäjille vain mahdollisuuden löytää toisiaan ja tutustua toisiinsa. _Kämppis_ ei sisällä ominaisuuksia esimerkiksi kimppa-asunnon etsimiseen tai muihin asumiseen liittyviin käytännön seikkoihin.
<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

## Roadmap
Kämppiksen versio 1.0 sisältää sovelluksen minimum viable product -version (MVP). Ensimmäinen julkaisuversio sisältää keskeiset ominaisuudet, jotka mahdollistavat käyttäjien profiilien luomisen, sopivan kämppiksen etsimisen ja yhteyden muodostamisen:

- Profiilin luonti: Käyttäjät voivat luoda oman profiilinsa syöttämällä henkilökohtaisia tietoja, kuten iän, sukupuolen, elämäntyylin, kiinnostuksen kohteet, sijainnin ja lemmikit. Profiiliin voi lisätä myös kuvia.
- Käyttäjä voi luoda oman käyttäjäprofiilin lisäksi kämpän, johon voi luoda huoneprofiileja vapaista huoneista, joilla voi etsiä kämppistä omaan vapaaseen kimppakämpän honeeseen. Kimppakämppään voi kutsua jo siellä asuvia kämppiksiä Kämppis-apin käyttäjiksi, jotta kaikki kämpässä asuvat ovat käyttäjän näkyvillä.
- Hakukriteerit: Käyttäjä voi etsiä sopivia kämppisehdokkaita tai kimppakämpän huoneita määrittelemällä omat toiveensa esimerkiksi sukupuolen, iän, elämäntyylin, sijainnin ja vuokraosuuden suhteen.
- Profiilien selaaminen: Käyttäjä näkee selailunäkymässä tiiviin yhteenvedon muista profiileista – mm. kuvan, iän, sijainnin ja lyhyen esittelytekstin.
- Tarkempi profiilinäkymä: Valitsemalla profiilin, käyttäjä näkee kaikki syötetyt tiedot selkeästi esitettynä.
- Kiinnostuksen ilmaisu: Profiilikortteja voi selata pyyhkäisemällä oikealle (kiinnostunut) tai vasemmalle (ei kiinnostunut). Jos molemmat käyttäjät ovat osoittaneet kiinnostuksensa, muodostuu yhteys.
- Chat-toiminto: Kun yhteys on muodostettu, avautuu keskusteluikkuna, jossa käyttäjät voivat vaihtaa viestejä. Keskustelu voi olla useamman kuin kahden käyttäjän välillä, jos yhteys on muodostettu kimppakämpän huoneprofiilin ja sitä etsivän käyttäjän välille. Chatin voi lopettaa koska tahansa.

Seuraaviin versioihin suunniteltuja toiminnallisuuksia ovat
- OAuth-kirjautumisen laajentaminen (esim. Google-tilillä)
- Admin-hallintapaneeli
- Sovelluksen ilmoitukset
- iOS-tuki
- Toiminnallisuudet kohdassa <b>Valinnaiset vaatimukset</b>

Katso tarkka lista suunnitelluista toiminnallisuuksista ja tunnetuista ongelmista:

[![Project issues][project-issues-logo]][project-issues-url]
[![Back-end issues][back-end-issues-logo]][back-end-issues-url]
[![App issues][app-issues-logo]][app-issues-url]
<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

## Teknologiat
_Kämppis_ on rakennettu käyttämällä seuraavia teknologioita:

![Back-end][back-end-logo]<br>
[![Kotlin][kotlin-logo]][kotlin-url]
[![Spring Boot][spring-logo]][spring-url]
[![Gradle][gradle-logo]][gradle-url]

![App][app-logo]<br>
[![TypeScript][typescript-logo]][typescript-url]
[![React Native][react-native-logo]][react-native-url]

![Tietokanta][database-logo]<br>
[![PostgreSQL][postgres-logo]][postgres-url]

![Työkalut][tools-logo]<br>
[![GitHub][github-logo]][github-url]
[![GitHub Actions][github-actions-logo]][github-actions-url]
[![Docker][docker-logo]][docker-url]
[![Expo Go][expo-logo]][expo-url]
[![Android Studio][android-studio-logo]][android-studio-url]
[![Bruno][bruno-logo]][bruno-url]
[![Visual Studio Code][vs-code-logo]][vs-code-url]
[![IntelliJ IDEA][intellij-idea-logo]][intellij-idea-url]

Tutustu myös _Kämppis_-projektin repositorioihin:

[![Back-end repository][back-end-repository-logo]][back-end-repository-url]
[![App repository][app-repository-logo]][app-repository-url]
<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

## Sovelluksen arkkitehtuuri
<details>
 <summary>Klikkaa avataksesi sovelluksen arkkitehtuurikuvan</summary>
 <img src="../Nat20 Kämppis-sovelluksen arkkitehtuuri.png" alt="Kämppis-sovelluksen arkkitehtuuri" style="width:60%; height:auto;">
</details>
<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

## Käyttäjätarinat ja vaatimukset

### Feature Epic
**Title**: Kämppis-sovellus yhdistää kämppistä etsivät käyttäjät<br>
**Description**: “Kimppa-asumisesta kiinnostuneena _käyttäjänä_ haluan alustan, jolla voin helposti ja turvallisesti löytää ja tutustua potentiaalisiin kämppäkavereihin.”

<details>
<summary><b>Välttämättömät vaatimukset</b></summary>
<blockquote>
Näiden käyttäjätarinoiden toteutus muodostaa tuotteen demoversion.

<details>
<summary><b>Title</b>: 1. Käyttäjäprofiilin luominen ja omien tietojen syöttäminen</summary>
<blockquote>
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
</blockquote>
</details>

<details>
<summary><b>Title</b>:	2. Kriteerien mukainen kämppis-profiilien haku</summary>
<blockquote>
<b>Description</b>:	Käyttäjänä haluan asettaa hakukriteereitä (esim. sukupuoli, sijainti, elämäntyyli, lemmikit), jotta näen vain profiilit, jotka vastaavat tarpeitani. Jos vastaavia tarpeita on paljon, profiili erottuu muista (esim. ”Supersopiva” tms. tagi).<br>
<b>Acceptance Criteria</b>:	Sovellus tarjoaa käyttäjälle helppokäyttöisen hakutoiminnon, jossa voidaan asettaa suodattimia vastakämppikselle, kuten:<br>
- sukupuoli<br>
- ikähaarukka<br>
- elämäntyyli<br>
- kämpän sijainti<br>
- kipuraja omalle osuudelle kämpän vuokrasta<br>
- kämppisten määrä<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>: 3. Profiilien selaaminen</summary>
<blockquote>
<b>Description</b>: Käyttäjänä haluan helposti selata muiden käyttäjien profiilien tärkeimpiä tietoja, jotta voin nopeasti arvioida, sopisimmeko kämppiksiksi.<br>
<b>Acceptance Criteria</b>: Ensinäkymä profiilista näyttää kuvan ja tärkeimmät tiedot, kuten<br>
- nimi<br>
- ikä<br>
- sijainti<br>
- lyhyt teaser-teksti itsestään<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>:	4. Profiilin tarkempi kuvaus</summary>
<blockquote>
<b>Description</b>:	Käyttäjänä haluan nähdä valitun käyttäjän koko profiilin, jotta voin arvioida, sopisimmeko kämppiksiksi.<br>
<b>Acceptance Criteria</b>	Profiilin näkymä on selkeä ja sisältää olennaiset tiedot (esim. nimi, ikä, elämäntyyli, sijainti).<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>:	5. Kiinnostuksen ilmaiseminen</summary>
<blockquote>
<b>Description</b>:	Käyttäjänä haluan ilmaista kiinnostukseni tiettyä profiilikorttia kohtaan, jotta voin saada mahdollisuuden tutustua tarkemmin.<br>
<b>Acceptance Criteria</b>:	Käyttäjä voi pyyhkäistä profiilikorttia oikealle tai vasemmalle. Jos molemmat osapuolet ovat pyyhkäisseet toistensa kortteja oikealle, luo sovellus yhteyden. Jos jompikumpi on pyyhkäissyt vasemmalle, sovellus ei luo yhteyttä.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>:	6. Chat-ominaisuus</summary>
<blockquote>
<b>Description</b>	Käyttäjänä haluan chatata potentiaalisen kämppäkaverin kanssa, jotta voimme keskustella tarkemmin ja selvittää, sopisimmeko yhteen. Kumpi tahansa osapuoli voi lopettaa chatin kesken milloin tahansa.<br>
<b>Acceptance Criteria</b>:	Chat avautuu vain, jos molemmat käyttäjät ovat ilmaisseet kiinnostuksensa toisiinsa. Chattiin voi syöttää tekstiä, emojeita ja GIF-animaatioita.<br>
</blockquote>
</details>

</details>

<details>
<summary><b>Hyödylliset vaatimukset</b></summary>
<blockquote>
Näiden käyttäjätarinoiden sekä välttämättömien käyttäjätarinoiden toteutus muodostaa tuotteen valmiin version.

<details>
<summary><b>Title</b>:	7. Sisäänkirjautuminen</summary>
<blockquote>
<b>Description</b>:	Käyttäjänä haluan kirjautua sisään olemassa olevalle profiilille.<br>
<b>Acceptance Criteria</b>:	Käyttäjä voi kirjautua takaisin olemassa olevalle tilille OAuthin avulla. Käyttäjä ei voi kirjautua muulle kuin omalle profiililleen. Käyttäjää ei kirjata automaattisesti sisään, jos hän on aiemmin kirjautunut ulos.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>:	8. Käyttäjäprofiilin omien tietojen muokkaaminen</summary>
<blockquote>
<b>Description</b>:	Käyttäjänä haluan muokata henkilökohtaisen profiilini tietoja, jotta omat tietoni ovat ajan tasalla ja muut käyttäjät saavat minusta realistisen kuvan.<br>
<b>Acceptance Criteria</b>:	Käyttäjän tulee voida muokata omia tietojaan oman profiilinsa kautta sekä tallentaa muokatut tiedot.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>: 9. Kopio omista tiedoista</summary>
<blockquote>
<b>Description</b>: Käyttäjänä haluan pyytää kopiota omista tiedoistani käyttäjäprofiilissani, jotta minulle selviää, mitä tietoja minusta varastoidaan.<br>
<b>Acceptance Criteria</b>: Käyttäjäprofiilissa on ”Kopio omista tiedoista”-painike. Sitä painettaessa käyttäjä saa ilmoituksen pyynnön onnistumisesta sekä kopion tiedoistaan ilmoittamaansa sähköpostiosoitteeseen.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>:	10. Käyttäjäprofiilin poistaminen</summary>
<blockquote>
<b>Description</b>:	Käyttäjänä haluan poistaa oman profiilini, mikäli en halua enää jatkaa sovelluksen käyttöä.<br>
<b>Acceptance Criteria</b>:	Käyttäjän tulee voida poistaa oma profiilinsa ja kaikki omat tietonsa sovelluksesta tietosuojakäytäntöjen (GDPR) mukaisesti.
</blockquote>
</details>

<details>
<summary><b>Title</b>: 11. Ilmoitukset</summary>
<blockquote>
<b>Description</b>: Käyttäjänä haluan saada ilmoituksia, kun joku ilmaisee kiinnostuksensa profiiliani kohtaan, jotta tiedän, milloin on tarpeen tarkistaa sovellus.<br>
<b>Acceptance Criteria</b>: Ilmoitukset ovat reaaliaikaisia ja sisältävät tarpeeksi tietoa, jotta käyttäjä tietää, mitä tapahtui.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>: 12. Käyttäjän tietojen yksityisyys</summary>
<blockquote>
<b>Description</b>: Käyttäjänä haluan, että vain valitsemani tiedot ovat näkyvillä sovelluksen käyttäjille, jotta voin käyttää sovellusta turvallisesti.<br>
<b>Acceptance Criteria</b>: Profiilin asetuksissa käyttäjä voi hallita, mitä tietoja jaetaan. Käyttäjä voi myös piilottaa profiilini näkyvistä muilta käyttäjiltä. Käyttäjän tulee myös hyväksyä sovelluksen palveluehdot ennen kuin voi käyttää sovellusta.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>:	13. Toisen käyttäjän ilmiantaminen</summary>
<blockquote>
<b>Description</b>:	Käyttäjänä haluan pystyä ilmiantamaan asiattoman viestin tai profiilin, jotta voin suojella itseäni ja muita häiritsevältä käytökseltä.<br>
<b>Acceptance Criteria</b>:	Käyttäjä voi painaa "Ilmianna" viestin tai profiilin kohdalla, ja ilmianto lähetetään tarkistettavaksi.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>: 14. Käyttäjäpalautteen antaminen</summary>
<blockquote>
<b>Description</b>: Käyttäjänä haluan antaa palautetta sovelluksen käytöstä ja toiminnasta.<br>
<b>Acceptance Criteria</b>: Sovelluksessa on yksinkertainen palautteenantotoiminto.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>:	15. Kämppä</summary>
<blockquote>
<b>Description</b>:	Käyttäjänä haluan ilmoittaa, minkälaista kämppää haen, tai jos minulla on kämppä, syöttää sen tiedot.<br>
<b>Acceptance Criteria</b>:	Käyttäjä voi ilmoittaa profiilissaan, hakeeko hän kämppää vai kämppistä. Kämpän tai halutun kämpän ominaisuudet löytyvät profiilista.<br>
</blockquote>
</details>

</blockquote>

</details>

<details>
<summary><b>Valinnaiset vaatimukset</b></summary>
<blockquote>
Näiden käyttäjätarinoiden toteutus on ylimääräistä extraa tuotteeseen.

<details>
<summary><b>Title</b>: 16. Premium-toiminnot</summary>
<blockquote>
<b>Description</b>: Käyttäjänä haluan ostaa Premium-version sovelluksesta, jotta saan käyttööni lisätoimintoja.<br>
<b>Acceptance Criteria</b>: Sovelluksessa on mahdollisuus ostaa Premium-versio. Premium-käyttäjä voi nähdä omasta profiilista kiinnostuneet käyttäjät ilman chat-yhteyden luontia. Voin myös peruuttaa viimeisimmän pyyhkäisyn, jos tein virheen. Asunnon haltijana toimivana käyttäjä voin myös valita profiilistani AutoLike-ominaisuuden, jonka avulla mätsään automaattisesti kaikkien niiden profiilien kanssa, jotka tykkäävät profiilistani. Voin käyttää tekoälyä kirjoittamaan biostani lyhennettyjä "prompteja", jotka näkyvät profiilikorttini yhteydessä.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>: 17. Ohjeet turvalliseen kanssakäymiseen sovelluksessa ja sen ulkopuolella</summary>
<blockquote>
<b>Description</b>: Käyttäjänä haluan saada ohjeita siitä, miten toimia sovelluksessa ja sen ulkopuolella muiden käyttäjien kanssa turvallisesti ja vastuullisesti.<br>
<b>Acceptance Criteria</b>: Sovellus antaa sopivassa kohdassa käyttäjälle luettavaksi lyhyen ohjeen siitä, miten kommunikoida ja tavata turvallisesti muiden käyttäjien kanssa.<br>
</details>

<details>
<summary><b>Title</b>: 18. Käyttäjän shadowbannaaminen</summary>
<blockquote>
<b>Description</b>: Adminina haluan pystyä estämään häiritsevien käyttäjien näkyvyyden muille käyttäjille ilman, että he huomaavat sitä, jotta voin suojella yhteisöä ja estää väärinkäytöksiä tehokkaasti.<br>
<b>Acceptance Criteria</b>:<br>
- Shadowbannattu käyttäjä voi edelleen kirjautua, selata profiileja ja "swaipata", mutta hänen profiiliaan ei näytetä muille käyttäjille, eikä hän saa yhteyksiä tai mätsäyksiä.<br>
- Admin voi asettaa shadowbannauksen manuaalisesti tai automaattisesti raporttien ja algoritmien perusteella.<br>
- Shadowbannaus ei näy käyttäjälle, eikä järjestelmä anna siitä mitään ilmoitusta.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>: 19. Ilmiantamisen automaattinen tarkastus</summary>
<blockquote>
<b>Description</b>: Adminina haluan, että järjestelmä merkitsee automaattisesti ilmiannetut viestit asiattomiksi tai ei-asiattomiksi, jotta voin priorisoida tarkistettavat tapaukset.<br>
<b>Acceptance Criteria</b>:<br>
- Järjestelmä analysoi ilmiannot automaattisesti, esimerkiksi syöttämällä ilmiannettu viesti tai profiili AI:lle.<br>
- Jos järjestelmä tunnistaa viestin asiattomaksi, sen lähettäjä asetetaan väliaikaiseen banniin, jolloin hän ei voi käyttää sovellusta ennen ylläpitäjän tarkistusta.<br>
- Väliaikaisen bannin aikana käyttäjälle näytetään viesti, jossa kerrotaan, että hänen viestinsä on ilmoitettu asiattomaksi.<br>
- Admin tarkistaa tapauksen mahdollisimman pian.<br>
- Jos admin toteaa viestin olleen asiattoman, bannaus pysyy voimassa ja käyttäjälle ilmoitetaan tuomion syy.<br>
- Jos viesti osoittautuu vääräksi hälytykseksi, bannaus poistetaan ja käyttäjälle ilmoitetaan päätöksestä.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>: 20. Sokkomätsi-toiminto</summary>
<blockquote>
<b>Description</b>: Käyttäjänä haluan yrittää löytää kämppiksen ilman rajoitteita tai hakukriteereitä ja antaa sattuman ratkaista.<br>
<b>Acceptance Criteria</b>:<br>
- Sokkomätsi-toiminto on valittavissa erillisenä ominaisuutena sovelluksen sisällä.<br>
- Käyttäjä voi painaa "Sokkomätsi"-painiketta ja odottaa, että järjestelmä yhdistää hänet satunnaiseen toiseen käyttäjään, joka on myös käyttänyt sokkomätsiä.<br>
- Sokkomätsi ei huomioi hakukriteerejä tai käyttäjien profiilissa ilmoitettuja toiveita.<br>
<b>Kun sokkomätsi onnistuu:</b><br>
- Molemmat käyttäjät saavat ilmoituksen ja pääsevät keskustelemaan toistensa kanssa chatin välityksellä.<br>
- Molemmille näytetään perustiedot toisesta käyttäjästä (esim. nimi, ikä ja sijainti, jos käyttäjä on sallinut niiden jaon).<br>
- Jos sokkomätsi ei löydä paria kohtuullisessa ajassa (esim. 1 minuutti), käyttäjälle ilmoitetaan, ettei muita sokkomätsi-käyttäjiä ole juuri nyt saatavilla.<br>
</blockquote>
</details>

<details>
<summary><b>Title</b>: 21. Käyttäjätuen ominaisuus</summary>
<blockquote>
<b>Description</b>: Käyttäjänä haluan ottaa yhteyttä asiakastukeen, jos kohtaan ongelmia sovelluksessa, jotta saan apua nopeasti.<br>
<b>Acceptance Criteria</b>: Sovelluksessa on yksinkertainen tukipyyntötoiminto.<br>
</blockquote>
</details>

</blockquote>

</details>
<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

## Tietoturva ja laadunvarmistus
Kämppis-sovellus on kehitetty käyttäjä edellä. Siksi tietoturvasta ja sovelluksen laadunvarmistuksesta on huolehdittu erityisen hyvin.

Kaikki sovelluksen syötteet validoidaan sekä käyttöliittymä- että palvelintasolla. Hibernate huolehtii omalta osaltaan syötteiden sanitaatiosta muuttamalla ne *prepared statement* -muotoon ennen käsittelyä tietokannassa. Sovellus käyttää HTTPS-protokollaa, ja käyttäjän kirjautumisessa on käytössä OAuth vanhenevan JWT-tokenin kera. Tämän lisäksi sovelluksen salaisuuksia ei tallenneta etärepositorioissa.

Myös käyttäjän tietosuojaa on ajateltu. Keräämme käyttäjältä vain välttämättömät tiedot, kuten nimen, sähköpostin ja syntymäajan. Emme säilytä salasanoja lainkaan. Sovelluksen käyttäjä voi nähdä ja muokata tietojaan, mutta myös halutessaan pyytää niistä kopion tai poistaa kaikki tiedot. Tietojen poistamisessa on kyse monimutkaisemmasta toiminnosta kuin pelkkä *soft delete* - kolmenkymmenen päivän jälkeen poistopäätöksestä käyttäjän kaikki tiedot anonymisoidaan. Näin hän ei enää ole tunnistettavissa, mutta tietokanta ei kärsi esim. id-tietojen puuttumisesta.

Olemme myös panostaneet laadunvarmistukseen. Projektin palvelinpuoli on katettu yksikkö- ja integrointitestein, ja siinä on käytetty hyväksi myös CI/CD-putken mahdollistavaa GitHub Actionsia. Lisätietoja kaikista projektiin rakennetuista testeistä löytyy Excel-muodossa [täältä](https://github.com/HH-Nat20/kamppis-server/tree/dev/src/test/resources).

<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

## Lisenssi

<p xmlns:cc="http://creativecommons.org/ns#" ><i>Kämppis</i>-projekti on lisensoitu <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1" alt=""></a></p>

<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

## Ota yhteyttä
Sovelluksen ovat toteuttaneet
- Janne Airaksinen: [devaajanne](https://github.com/devaajanne)
- Paul Carlson: [Phoolis](https://github.com/Phoolis)
- Julia Hämäläinen: [marttyyriroskis](https://github.com/marttyyriroskis)
- Jesse Hellman: [Bminor87](https://github.com/Bminor87)

Kehittäjien yhteystiedot löydät GitHub-profiileista.
  
<a href="https://github.com/HH-Nat20/kamppis-server/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=HH-Nat20/kamppis-server" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-alku">Takaisin alkuun</a>)</p>

<!-- LINKIT JA KUVAT -->

<!-- PROJEKTI JA REPOSITORIOT -->
[back-end-repository-logo]: https://img.shields.io/badge/BackEnd%20Repository-000000?style=for-the-badge
[back-end-repository-url]: https://github.com/HH-Nat20/kamppis-server
[back-end-issues-logo]: https://img.shields.io/badge/BackEnd%20Open%20Issues%20And%20Bugs-000000?style=for-the-badge
[back-end-issues-url]: https://github.com/HH-Nat20/kamppis-server/issues
[app-repository-logo]: https://img.shields.io/badge/App%20Repository-000000?style=for-the-badge
[app-repository-url]: https://github.com/HH-Nat20/kamppis-app
[app-issues-logo]: https://img.shields.io/badge/App%20Open%20Issues%20And%20Bugs-000000?style=for-the-badge
[app-issues-url]: https://github.com/HH-Nat20/kamppis-app/issues
[project-issues-logo]: https://img.shields.io/badge/Project%20Open%20Issues-000000?style=for-the-badge
[project-issues-url]: https://github.com/HH-Nat20/.github/issues

<!-- TEKSTILOGOT -->
[app-logo]: https://img.shields.io/badge/App-000000?style=for-the-badge
[back-end-logo]: https://img.shields.io/badge/BackEnd-000000?style=for-the-badge
[database-logo]: https://img.shields.io/badge/Tietokanta-000000?style=for-the-badge
[tools-logo]: https://img.shields.io/badge/Työkalut-000000?style=for-the-badge

<!-- TEKNOLOGIAT JA TYÖKALUT -->
[kotlin-logo]: https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=Kotlin&logoColor=white
[kotlin-url]: https://kotlinlang.org/
[spring-logo]: https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white
[spring-url]: https://spring.io/
[gradle-logo]: https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white
[gradle-url]: https://gradle.org/
[typescript-logo]: https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white
[typescript-url]: https://www.typescriptlang.org/
[react-native-logo]: https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB
[react-native-url]: https://reactnative.dev/
[postgres-logo]: https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white
[postgres-url]: https://www.postgresql.org/
[github-logo]: https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white&style=for-the-badge
[github-url]: https://github.com/
[github-actions-logo]: https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white
[github-actions-url]: https://github.com/features/actions
[docker-logo]: https://img.shields.io/badge/docker-257bd6?style=for-the-badge&logo=docker&logoColor=white
[docker-url]: https://www.docker.com/
[expo-logo]: https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=fff
[expo-url]: https://expo.dev/go
[android-studio-logo]: https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white
[android-studio-url]: https://developer.android.com/studio
[bruno-logo]: https://img.shields.io/badge/Bruno-FF6C37?style=for-the-badge&logo=Bruno&logoColor=white
[bruno-url]: https://www.usebruno.com/
[vs-code-logo]: https://custom-icon-badges.demolab.com/badge/Visual%20Studio%20Code-0078d7.svg?logo=vsc&logoColor=white&style=for-the-badge
[vs-code-url]: https://code.visualstudio.com/
[intellij-idea-logo]: https://img.shields.io/badge/Intellij%20Idea-000?logo=intellij-idea&style=for-the-badge
[intellij-idea-url]: https://www.jetbrains.com/idea/
