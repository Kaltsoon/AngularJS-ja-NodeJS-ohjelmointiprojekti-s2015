# Syksyn 2015 Angular.js- ja Node.js ohjelmointiprojektit

Tämä on kurssisivu syksyn 2015 Angular.js- ja Node.js-ohjelmointiprojekteille. Kurssit voi suorittaa joko **erikseen** tai **samanaikaisesti** toteuttamalla vapaavalintaisen sovelluksen, joka käyttää joko toista tai molempia teknologioista. Projekti(t) on mahdollista toteuttaa myös ryhmässä.

Kummastakin projektista voi saada **1-3 opintopistettä** niin, että **n. 20 työtuntia vastaa aina yhtä opintopistettä**. Työtunnit tulee olla kirjattuna erilliseen tuntikirjanpitoon, josta kerrotaan lisää projektikohtaisessa ohjeessa. Ryhmässä toteutussa projektissa jokaisella ryhmäläisellä tulee olla erillinen tuntikirjanpito. **Ilman tuntikirjanpitoa opintopisteitä ei voi saada!** Projekteista **ei saa arvosanaa**, vaan ne arvostellaan hyväksytty-hylätty-asteikolla.

Kurssin ainoana esitiona on JavaScript-kielen kohtalainen hallinta. Kurssilla **ei ole erilistä materiaalia**, vaan opiskelu on pääosin itsenäistä. Pajaohjausta järjestetään kuitenkin kolme kertaa viikossa, jonka aikana saa ohjausta oman sovelluksen toteuttamisen kanssa. 

:exclamation: **Molempien projektien deadline on 12.11 klo 23:59. Samalla viikolla järjestetään demotilaisuudet, jossa projektit esitellään muille.**

#Ajankohtaista

* :bulb: Kurssi alkaa vapaaehtoisella introlla maanantaina klo 14:00. Introssa fiilistellään lyhyesti Nodea ja Angularia sekä käydään läpi kurssiin liittyviä asioita. **Jos sinulle on jo kaikki selvää, ei introon tarvitse tulla.**

#Ohjaus

Molemmille **projekteille on yhteiset pajaohjausajat**, joiden aikana ohjaajalta saa kysyä molempiin projekteihin liittyviä kysymyksiä. 

* Ohjaajana toimii Kalle Ilves (email: kalle.ilves[at]helsinki.fi, IRC-nick: kaltsoon)
* Pajaohjaus (26.10 - 8.11):
  * Maanantaisin klo 12-14 luokassa BK107
  * Keskiviikkoisin klo 14-16 luokassa BK107
  * Perjantaisin klo 12-14 luokassa BK107
* IRC-kanavana toimii **#angular-node-2015**, josta voi kysyä neuvoa ohjaajalta ja muilta opiskelijoilta

## Angular.js ohjelmointiprojektin ohjeistus

![Angular.js](https://raw.githubusercontent.com/Kaltsoon/AngularJS-ja-NodeJS-ohjelmointiprojekti-s2015/master/images/AngularJS-large.png)  

AngularJS on suuren suosion saavuttanut JavaScript sovelluskehys skaalautuvien web-sovellusten kehittämiseen.
Angularia ei voi rajata pelkäksi MVC-sovelluskehykseksi (vaikkakin niin usein tehdään), vaan tarkempi termi onkin "Model View Whatever" (MVW). Se siis esittää mallia näkymässä ja välittää näkymässä tehtyjä muutoksia takaisin malliin. Mitä mallin ja näkymän rajapinnassa tapahtuu, on ohjelmoijan itsensä päätettävissä. 

### Projektin aihe

Projektin aiheen saa itse valita. Tärkeintä on vain, että siinä käytetään Angularia. Angularin lisäksi voit käyttää kaikkia haluamiasi kirjastoja ja työkaluja. Hyvä aihe voisi olla esimerkiksi keskustelualue-sovellus, joka käyttää sovelluksen datan tallentamiseen [Firebasea](https://www.firebase.com/).

:thumbsup: **Voit forkata [tämän](https://github.com/Kaltsoon/Angular-boilerplate) repon projektisi pohjaksi tai käyttää vaikkapa [tätä](https://github.com/yeoman/generator-angular) Yeoman generaattoria.**

:question: **Jos sinulla on vaikeuksia aiheen keksimisen kanssa, tule kysymään siitä ohjauksessa tai lähetä viestiä irkissä!**

### Projektin vaatimukset

:exclamation: **Projektin deadline on 12.11 klo 23:59!**

* Linkki sovellukseen repositorion kotisivukenttään, README:hen ja tuntikirjanpitoon sähköpostina osoitteeseen kalle.ilves[at]helsinki.fi deadlineen mennessä. **Ilmoita viestissä opiskelijanumerosi ja suorittamasi projektit**.
* Tuntikirjanpitoon
 * Päivittäiset työtunnit, jossa ilmenee päiväämärä, lyhyt kuvaus tehdystä työstä ja käytetyt tunnit
 * Käytetyt tunnit yhteensä
 * :exclamation: **Jos teet samalla Node.js-projektin jaa tuntikirjanpito kahteen osaan: Node.js- ja Angular-projektin tuntikirjanpitoon!**
 * :exclamation: **Jos toteutat projektia ryhmässä, jokaisella ryhmäläisellä tulee olla oma tuntikirjanpito!**
* README:hen
 * Aihekuvaus, joka sisältää alustava selitys projektin ideasta
 * Linkki itse sovellukseen ([täällä](https://github.com/tuhoojabotti/AngularJS-ohjelmointiprojekti-k2014/blob/master/material/starting.md#hostaus) vaihtoehtoja hostaukseen)
 * Muuta mukavaa (CI-palvelin linkki, ymv. mahtavuutta)

### Hyviä linkkejä :thumbsup:

* **[Ville Lahdenvuon kevään 2014 materiaali](https://github.com/tuhoojabotti/AngularJS-ohjelmointiprojekti-k2014#materiaali)**
 * Tutustu etenkin linkkiin "Alkuun pääseminen" 
* [Web-selainohjelmointi kurssin materiaalin Angular-osiot (kappaleesta 12 eteenpäin)](http://web-selainohjelmointi.github.io/#12-Sovelluksen-rakenteen-hallinta:-AngularJS)
* [Angular.js-sovelluskehyksen kotisivu](https://angularjs.org)

## Node.js ohjelmointiprojektin ohjeistus

![Node.js](https://raw.githubusercontent.com/Kaltsoon/AngularJS-ja-NodeJS-ohjelmointiprojekti-s2015/master/images/nodejs-logo.png)

Node.js mahdollistaa JavaScriptin käytön selainpuolen sovellusten ulkopuolella. Sen avulla pystyt mm. toteuttamaan web-palvelin sovelluksia, jotka välittävät dataa tietokannasta selainpuolen sovelluksille.

### Projektin aihe

Projektin aiheena on vapaavalintaine Node.js sovellus. Voit käyttää vapaasti haluamiasi Node-kirjastoja ja työkaluja. Hyvä aihe voisi olla esimerkiksi [Stackoverflow](http://stackoverflow.com/)-kopio [Sails](http://sailsjs.org/) MVC-sovelluskehyksellä.

:question: **Jos sinulla on vaikeuksia aiheen keksimisen kanssa, tule kysymään siitä ohjauksessa tai lähetä viestiä irkissä!**

### Projektin vaatimukset

:exclamation: **Projektin deadline on 12.11 klo 23:59!**

* Linkki sovellukseen repositorion kotisivukenttään, README:hen ja tuntikirjanpitoon sähköpostina osoitteeseen kalle.ilves[at]helsinki.fi deadlineen mennessä. **Ilmoita viestissä opiskelijanumerosi ja suorittamasi projektit**.
* Tuntikirjanpitoon
 * Päivittäiset työtunnit, jossa ilmenee päiväämärä, lyhyt kuvaus tehdystä työstä ja käytetyt tunnit
 * Käytetyt tunnit yhteensä
 * :exclamation: **Jos teet samalla Angular.js-projektin jaa tuntikirjanpito kahteen osaan: Node.js- ja Angular-projektin tuntikirjanpitoon!**
 * :exclamation: **Jos toteutat projektia ryhmässä, jokaisella ryhmäläisellä tulee olla oma tuntikirjanpito!**
* README:hen
 * Aihekuvaus, joka sisältää alustava selitys projektin ideasta
 * Linkki sovellukseen (jos kyseessä ei ole web-sovellus, lisää tarkat asennus- ja käyttöohjeet)
 * Muuta mukavaa (CI-palvelin linkki, ymv. mahtavuutta)

### Hyviä linkkejä :thumbsup:

* **[Ville Lahdenvuon kevään 2014 materiaali](https://github.com/tuhoojabotti/NodeJS-ohjelmointiprojekti-k2014#materiaali)**
 * Tutustu etenkin linkkiin "Alkuun pääseminen" 
* [Node.js kotisivu](https://nodejs.org/en/)
* [Express](http://expressjs.com/) web-palvelinohjelmoinnista kiinnostuneille
 * [Web-selainohjelmointi kurssin viimeisellä viikolla](http://web-selainohjelmointi.github.io/#21-Palvelinohjelmointia-JavaScriptill%C3%A4---Node.js-ja-Express) toteutetaan pieni Express-sovellus
* [Sails](http://sailsjs.org/) MVC-sovelluskehys 
