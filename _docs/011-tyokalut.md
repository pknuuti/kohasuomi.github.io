---
title: 'Kohan ohje suomeksi'
permalink: /dokumentaatio/tyokalut/
redirect_from:
  - /theme-setup/
toc: true
---

# 10. Työkalut

Kohan Työkalut-osiossa on monenlaisia toimintoja, joilla voi mm. muokata
ja poistaa niteitä tai tietueita, tulostaa tarroja, tuoda
luettelointitietoja Tätistä, lähettää laskuja, käyttää siirtokokoelmia
jne. Käyttäjän oikeuksista riippuu, mitä työkaluja hänelle on näkyvissä.
Osa työkaluista ei ole käyttökelpoisia tai tarpeellisia Suomen
toimintaympäristössä.

<img src="/assets/files/docs/Tyokalut/tyokalut.png" title="Kuvakaappaus Työkalut-osion aloitusivusta. Työkalujen nimien perään on laitettu eri värisiä palloja niiden käyttökelpoisuuden perusteella" alt="Kuvakaappaus Työkalut-osion aloitusivusta. Työkalujen nimien perään on laitettu eri värisiä palloja niiden käyttökelpoisuuden perusteella" />

- Punaisella pallolla merkityt eivät ole käyttökelpoisia tai
  tarpeellisia.
- Keltaisella pallolla merkityt toimivat, mutta eivät ole
  pääsääntöisesti tarpeellisia (enää).

## 10.1 Asiakaslistat

Asiakaslistat-työkalulla voi luoda asiakkaista listoja, joita voi sitten
hyödyntää mm. asiakastietojen erämuokkauksessa.

Etusivulla listataan olemassa olevat asiakaslistat. Uuden asiakaslistan
voi tehdä _Uusi asiakaslista_ -nappia painamalla.  
<img src="/assets/files/docs/Tyokalut/asiakaslistat.png" alt="" style="width:40.0%" />

Anna listalle nimi ja tallenna se.  
<img src="/assets/files/docs/Tyokalut/asiakaslistat1.png" alt="" style="width:25.0%" />

Tämän jälkeen listalle voi lisätä asiakkaita klikkaamalla
_Toiminnot_-nappia ja valitsemalla _Lisää asiakkaita_.  
<img src="/assets/files/docs/Tyokalut/asiakaslistat2.png" alt="" style="width:40.0%" />

Siitä aukeaa sivu, jolla pystyt hakemaan asiakkaita esim. nimellä.
Valitse hiirellä tarjottu asiakastieto, jolloin se listautuu hakukentän
alapuolelle. Voit hakea useamman asiakkaan tiedot ennen kuin lisäät
heidät listalle.  
<img src="/assets/files/docs/Tyokalut/asiakaslistat3.png" alt="" style="width:40.0%" />

<img src="/assets/files/docs/Tyokalut/asiakaslistat4.png" alt="" style="width:25.0%" />

Nyt pääset tarkastelemaan listalla olevia asiakkaita. Voit myös poistaa
heitä listalta valitsemalla heidän tiedot ja klikkaamalla _Poista
valitut asiakkaat_. Ohjelma kysyy varmistuksen “Poistetaanko asiakas”.
Huom! Asiakastietoja ei poisteta rekisteristä, vain listalta.  
<img src="/assets/files/docs/Tyokalut/asiakaslistat5.png" alt="" style="width:60.0%" />

Asiakkaita voi lisätä listalle myös asiakashaun kautta valitsemalla
ensin halutut asiakkaat ja valitsemalla sitten _Lisää valitut asiakkaat_
-valikosta haluamasi lista.  
<img src="/assets/files/docs/Tyokalut/asiakaslistat6.png" alt="" style="width:40.0%" />

---

## 10.2 Ilmoitukset ja kuitit

Ilmoituksia ja kuitteja ylläpitää pääsääntöisesti kimppojen
pääkäyttäjät, mutta tässä voi olla kimppakohtaisia eroja.

Ilmoitukset ja kuitit -työkalun etusivulla on lista olemassa olevista
pohjista. Ilmoitukset voivat olla joko kaikkia kirjastoja koskevia tai
kirjastokohtaisia. Kirjastokohtaiset pohjat ovat listan lopussa.

<img src="/assets/files/docs/Tyokalut/ilmoitukset.png" alt="" style="width:90.0%" />

- Uusi pohjia voi tehdä _Uusi ilmoitus_ -napilla
- Pohjan voi kopioida toiselle kirjastolle _Kopioi_-napilla
- Pohjaa voi muokata _Muokkaa_-napilla
- Pohjan voi poistaa _Poista_-napilla

### Ilmoituksen muokkaaminen

Ilmoituksen/kuitin voi tehdä samoille kielille kuin mitä Kohaan on
asennettu käyttökieliksi. Lisäksi on olemassa Oletus-pohja, jota
käytetään silloin, kun asiakkaalle ei ole valittuna asiointikieltä.
Ilmoituksen voi määrittää eri viestityypeille: sähköposti, puhelin
(vaatii TalkingTechItivaPhone-tuen), tuloste ja tekstiviesti. Muutokset
tallennetaan _OK_-napista.

<img src="/assets/files/docs/Tyokalut/ilmoitukset1.png" alt="" style="width:50.0%" />

Ilmoitukseen/kuittiin voi lisätä tekstiä sekä tägejä, joilla viestiin
lisätään tietokannasta tietoja. Tägejä voi lisätä vasemman reunan
valikosta tai kirjoittaa sen itse. _Viestin aihe_ -kenttään kirjoitetaan
sähköpostiviestin aihe. Myös viestin aiheessa voi käyttää
tietokanta-tägejä. Jos viesti on html-muotoinen, laitetaan rasti kohtaan
_HTML-viesti_, jolloin viesti osataan käsitellä oikein.  
<img src="/assets/files/docs/Tyokalut/ilmoitukset2.png" alt="" style="width:60.0%" />

### Eräpäivä kuitille ilman kellonaikaa

Eräpäivän saa tulostumaan kuitille ilman kellonaikaa dateonly-määreellä
näin:

Eräpäivä: &lt;&lt;issues.date_due \| dateonly &gt;&gt;

---

## 10.3 Myöhästymisilmoitusten määrittely

Myöhästymisilmoitusten eli palautuskehotusten aikataulu määritetään
Myöhästymisilmoitusten määrittely -työkalulla. Määrittelyt voivat olla
joko kaikkia tai yksittäisiä kirjastoja koskevia. Ilmoituksia voi
lähettää kolme, mutta kaikkia tai mitään ei tarvitse lähettää.

**Huomioi**, että jos oletussääntö on määritetty, ei yksittäiselle
kirjastolle pysty tekemään sääntöä, että ilmoituksia ei lähetetä
ollenkaan.  
{: .notice--warning}

<img src="/assets/files/docs/Tyokalut/myohastymis.png" alt="" style="width:90.0%" />

- Taulukossa listataan ne asiakastyypit, joille on määritetty
  asiakastyyppien ylläpidossa, että myöhästymisilmoituksia lähetetään.
- _Viive_-kenttään määritetään, montako päivää eräpäivän jälkeen
  myöhästyisilmoitus lähetetään.
- _Kirje_-sarakkeessa valitaan, mitä ilmoituspohjaa käytetään viestiä
  lähetettäessä. Ks. Ilmoituksen ja kuitit -kohta.
- _Rajoita_-kohtaan laitetaan rasti, jos halutaan asiakkaan menevän
  lainakieltoon viestin lähdettyä.
- _Maksu_-kohtaan määritetään ilmoituksesta perittävän maksun määrä.
- _Sähköposti, Puhelin, Tuloste ja Tekstiviesti_ -kohdista valitaan
  halutut vaihtoehdot.
- Määrittelyt tallennetaan _Tallenna muutokset_ -nappulalla.

---

## 10.4 Lähetä laskuja

Koha-Suomessa kehitetty versio laskutuksesta.

Ohjeet

- Valitse kirjasto, taulukko näyttää nykyisen kirjaston niteet. Jos
  haluat käsitellä useamman kuin yhden kirjaston niteitä, lisää
  asetusryhmä, jonka nimessä on “LASKU” ja valitse se haluamillesi
  kirjastoille.
- Kirjastolle pitää valita laskutusryhmä kirjastojen asetuksissa. Nyt
  valittavana on kaksi vaihtoehtoa: SAPERP ja PDFBILL. SAPERP lähettää
  laskut KuntaErpiin ja PDFBILL luo tulostettavia PDF-tiedostoja
- Niteet voidaan valita tai poistaa valinta klikkaamalla ‘Valitse
  kaikki’, tai valitsemalla niteet yksitellen. Niteen korvaushintaa
  voi muokata ja kaikki esimääritetyt lisämaksut lisätään
  automaattisesti. Valitse laskutettavat niteet alapuoliselta listalta
  ja klikkaa ‘Luo laskut’ -nappia.
- Korvaushintaan tehdyt muutokset nollataan laskun luomisen jälkeen,
  mutta hinta näkyy oikein laskulla.  
  Kun laskut luodaan onnistuneesti, tallennetaan tietokantaan kyseisen
  päivän aikaleima ja se näytetään taulun “last bill
  created”-sarakkeessa.
- Jos asiakas on lapsi, näytetään huoltaja ja lasku luodaan hänelle.
- Järjestelmäasetuksissa voi määritellä, mitkä maksut poistuvat
  asiakkaan tiedoista palautuksen yhteydessä: RemoveFinesOnReturn

---

## 10.5 Asiakkaiden poisto/lainatietojen poisto eräajona

Asiakkaita ja lainatietoja voi poistaa eräajona seuraavien ehtojen
mukaisesti:  
<img src="/assets/files/docs/Tyokalut/asiakkaidenpoisto.png" title="Kuvakaappaus asiakkaiden ja lainatietojen poisto eräajona -sivulta" alt="Kuvakaappaus asiakkaiden ja lainatietojen poisto eräajona -sivulta" style="width:70.0%" />

- ylimmäisenä, otsikon yläpuolella, on Valitse kirjasto -vaihtoehto,
  eli voit määrittää koskeeko ajo kaikkia kirjastoja vai vain tiettyä
  kirjastoa
- jotka eivät ole lainanneet määritetyn päivämäärän jälkeen
- joiden tili on vanhentunut ennen määritettyä päivämäärää
- jotka eivät ole olleet yhteydessä (kirjautuneet verkkokirjastoon)
  määritetyn päivämäärän jälkeen
- joiden asiakastyyppi on alasvetovalikosta valitun mukainen
- jotka ovat asiakaslistalla, jonka voi valita alasvetovalikosta

Kaikkia vaihtoehtoja voi yhdistellä keskenään asiakastietoja
poistettaessa.

### 10.5.1 Asiakkaiden poisto

Valitse haluamasi vaihtoehto/vaihtoehdot ja laita rasti
Vahvista-ruutuun. Klikkaa sitten Seuraava-nappulaa.

Seuraavaksi kerrotaan, kuinka monta asiakasta ollaan poistamassa ja mitä
niille halutaan tehdä.  
<img src="/assets/files/docs/Tyokalut/asiakkaidenpoisto1.png" title="Kuvakaappaus, jossa kerrotaan kuinka monta asiakasta ollaan poistamassa ja kysytään, mitä asiakastiedoille halutaan tehdä" alt="Kuvakaappaus, jossa kerrotaan kuinka monta asiakasta ollaan poistamassa ja kysytään, mitä asiakastiedoille halutaan tehdä" style="width:45.0%" />

- Poistetaanko näiden asiakkaiden tiedot pysyvästi
  - **Huom!** Tämä vaihtoehto poistaa asiakastiedot täysin
    järjestelmästä, eikä niitä viedä deletedborrower-tauluun. Käytä
    vain, jos haluat poistaa asiakastiedot täysin järjestelmästä ja
    tilastoista.
- Siirrä näiden asiakkaiden tiedot roskakoriin
  - tämä vaihtoehto siirtää asiakastiedot deletedborrowers-tauluun.
    Tätä vaihtoehtoa kannattaa käyttää pääsääntöisesti.
- Älä poista asiakastietoja (testiajo)

Valitse haluamasi vaihtoehto ja klikkaa Valmis-nappulaa.

Tämän jälkeen järjestelmä kertoo, kuinka monta asiakasta poistettiin tai
siirrettiin roskakoriin (deletedborrowers-tauluun).  
<img src="/assets/files/docs/Tyokalut/asiakkaidenpoisto2.png" title="Kuvakaappaus, jossa kerrotaan että 2 asiakasta on siirretty roskakoriin" alt="Kuvakaappaus, jossa kerrotaan että 2 asiakasta on siirretty roskakoriin" style="width:40.0%" />

### 10.5.2 Lainahistorian anonymisointi

Poista asiakkaita -toiminnon alapuolella on lainahistorian anonymisointi
-toiminto. Ihan ylimmäisenä, ennen asiakkaiden poistoa ja otsikon
yläpuolella on Valitse kirjasto -vaihtoehto, josta voit valita, koskeeko
anonymisointi kaikkia kirjastoja vai vain tiettyä kirjastoa.

- Laita rasti kohtaan _Vahvista: Haluat anonymisoida asiakkaiden
  lainahistorian_.
- Valitse päivämäärä, mitä vanhemmat asiakkaiden lainahistoriat
  poistetaan.
- Klikkaa Seuraava

Saat tiedon, kuinka monen asiakkaan lainahistoria anonymisoidaan.

<img src="/assets/files/docs/Tyokalut/asiakkaidenpoisto4.png" title="Kuvakaappaus, jossa varoitetaan, että 454 asiakkaan lainahistoria anonymisoidaan" alt="Kuvakaappaus, jossa varoitetaan, että 454 asiakkaan lainahistoria anonymisoidaan" style="width:30.0%" />

- Valitse _Valmis_

<img src="/assets/files/docs/Tyokalut/asiakkaidenpoisto5.png" title="Kuvakaappaus, jossa kerrotaan, että on anonymisoitu 5493 lainaa, jotka ovat vanhempia kuin 31.12.2015" alt="Kuvakaappaus, jossa kerrotaan, että on anonymisoitu 5493 lainaa, jotka ovat vanhempia kuin 31.12.2015" style="width:40.0%" />

---

## 10.6 Asiakkaiden muokkaus eräajona

Asiakkaiden tietoja voi muokata eräajona eli tehdä sama muutos isommalle
joukolle kerralla.

<img src="/assets/files/docs/Tyokalut/asiakkaidenmuokkaus.png" alt="" style="width:35.0%" />  
Muokattavat asiakkaat voi valita kolmella tavalla

- tiedostosta
- asiakaslistalta
- lisäämällä heidän kirjastokortin numeron tekstikenttään, yksi per
  rivi

Sen jälkeen valitaan _Seuraava_

<img src="/assets/files/docs/Tyokalut/asiakkaidenmuokkaus1.png" alt="" style="width:45.0%" />

Asiakkaille voi joko lisätä tai poistaa tietoja. Poistaminen tapahtuu
laittamalla rasti kentän viereen. Lopuksi valitaan _Tallenna_.

---

## 10.7 Niteiden poisto eräajona

Niteiden poistossa eräajona pystyy poistamaan ison joukon niteitä
kerralla.

Valitse ensin poistettavat niteet.  
<img src="/assets/files/docs/Tyokalut/erapoisto.png" alt="" style="width:30.0%" />

- Voit tuoda niteet tiedostosta, joka sisältää joko viivakoodeja tai
  nidenumeroita (itemnumber).
  - Vinkki: Viivakoodi-tiedoston pystyy luomaan esim. Nidehaulla tai
    lukemalla/lisäämällä ne tekstitiedostoon.
- Tai lukea poistettavien niteiden viivakoodit tekstikenttään.

Valitse sitten _Jatka_.

Poistettavat niteet listautuvat avautuvalle sivulle.  
<img src="/assets/files/docs/Tyokalut/erapoisto1.png" alt="" style="width:70.0%" />

- Voit valita, mitä sarakkeita niteistä näytetään.
- Voit vielä tässä vaiheessa ottaa pois rastin sellaisen niteen
  kohdalta, jota ei tarvikaan poistaa.
- Suositus: Kannattaa laittaa rasti kohtaan _Poista tietueet, jos
  kaikki niteet poistettu_, jotta tietokantaan ei jää “roikkumaan”
  niteettömiä nimekkeitä. Huomioi kuitenkin kimppakohtaiset käytännöt.

Valitse lopuksi _Poista valitut_ -painike.

Saat yhteenvedon poistetuista niteistä ja tietueista:

<img src="/assets/files/docs/Tyokalut/erapoisto2.png" alt="" style="width:45.0%" />

Voit palata eräpoiston etusivulle _Palaa niteiden poiston eräajoon_
-napista tai linkistä.

Huomaa, että päädyt niteiden eräpoistoon myös silloin, jos valitset
tietueesta useamman niteen ja sitten valitset taulukon yläpuolelta
_Poista valitut_  
<img src="/assets/files/docs/Tyokalut/erapoisto3.png" alt="" style="width:45.0%" />

---

## 10.8 Niteiden muokkaus eräajona

Niteiden muokkaus eräajona tietueesta käsin on ohjeistettu
\[\[/3_Luettelointi\#3222-Niteiden-erämuokkaus\|Niteiden
erämuokkaus\]\]-osiossa.

Työkaluista käsin liikkeelle lähdettäessä valitaan ensin, mitä niteitä
muokataan.  
<img src="/assets/files/docs/Tyokalut/eramuokkaus1.png" alt="" style="width:35.0%" />  
Niteet voi tuoda

- Viivakooditiedostosta, joka on tehty esim. keräämällä viivakoodeja
  muistioon tai tallentamalla nidehaku viivakooditiedostoksi.
- Nidenumerotiedostosta, joka on tehty esim. raportit-osiossa
  sql-kyselyllä tietokannasta
- Lukemalla niteet yksi kerrallaan tekstilaatikkoon

Niteille voi halutessaan lisätä oletuspohjan arvot laittamalla rastin
kohtaan _Täytä kentät oletusarvoilla, oletuspohjasta_. Huomioi, että
tämä ei välttämättä tuo mitään arvoja niteille, jos
oletusluettelointipohjaan ei ole määritetty oletusarvoja 952-kenttään.

Valitse _Jatka_ muokataksesi niteitä.

Erämuokkauksessa voit  
<img src="/assets/files/docs/Tyokalut/eramuokkaus2.png" alt="" style="width:70.0%" />

- valita, mitä niteitä muokataan
- poistaa niteiltä lainassa-tilan (käytä harkiten)
- säätää, mitä tietoja niteistä näytetään muokkauksessa

Niteiden muokkaus  
<img src="/assets/files/docs/Tyokalut/eramuokkaus3.png" alt="" style="width:60.0%" />

- Pakolliseksi merkittyjä tietoja ei pysty poistamaan niteiltä, mutta
  ne voi vaihtaa toiseksi tiedoksi.
- Tiedon pystyy poistamaan laittamalla rastin halutun kentän viereen.
  Esim. kokoelmakoodin saa poistettua laittamalla rastin
  Kokoelma-kentän viereen.
- Tiedon pystyy lisäämään joko valitsemalla alasvetovalikosta
  vaihtoehdon tai kirjoittamalla kenttään haluttu tieto. Riippuu
  kentästä, kumpi vaihtoehto on mahdollista. Esim. kirjasto- ja
  hyllypaikkatieto valitaan alasvetovalikosta, mutta
  huomautus-kenttiin kirjoitetaan haluttu tieto.

Muutokset tehdään valitsemalla _Tallenna_. Jos et haluakaan tehdä
muutoksia, valitse _Peruuta_ tai sulje ikkuna/välilehti, jolloin
muutoksia ei tehdä.

---

## 10.9 Tietueiden poisto eräajona

Tietueita pystyy poistamaan eräajona. Samaan näkymään voi päästä kahta
kautta.

### 10.9.1 Tietueen poisto korin kautta

Vie haluamasi tietueet koriin ja avaa se.

<img src="/assets/files/docs/Tyokalut/tietueidenpoisto2.png" alt="" style="width:40.0%" />

- Valitse poistettavat tietueet ja klikkaa sitten _Eräpoisto_

### Tietueen poisto työkaluista käsin

Mene työkaluihin ja valitse _Tietueiden poisto eräajona_

<img src="/assets/files/docs/Tyokalut/tietueidenpoisto.png" alt="" style="width:30.0%" />

- Valitse ensin, poistatko bibliografisia tietueita (nimekkeitä) vai
  auktoritettitietueita (esim. kirjailijoita, asiasanoja).
- Voit tuoda poistettavat tietueet joko
  - tiedostona, joka sisältää poistettavien tietueiden tietuenumerot
    (biblionumber). Tällaisen listan voi luoda esimerkiksi
    sql-kyselyllä Raportointi-osiossa tai keräämällä tietuenumeroita
    Muistioon.
  - lisäämällä tietuenumerot tekstikenttään yksi per rivi.

Valitse sitten _Jatka_.

Tietueiden poistossa listataan poistoon valitut tietueet.

<img src="/assets/files/docs/Tyokalut/tietueidenpoisto3.png" alt="" style="width:50.0%" />

- jos tietueeseen liittyy lainassa olevia niteitä, ei sitä pysty
  poistamaan.
- voit vielä tässä vaiheessa ottaa rastin pois niiltä tietueilta,
  joita et halua poistaa.
- **Huomioi**: tietueiden eräpoisto poistaa myös tietueeseen liittyvät
  lehtitilaukset, niteet ja varaukset **<span
  class="lehtitilauksia Kohassa tarkoittaa oikeasti se kun "tilaukset", virheellisesti käännetty on subscriptions käännösvirhe, on Kuvassa"></span>**
  - tämä voi olla kätevää esim. kun teos ei ilmesty ja siihen on
    paljon varauksia, jolloin sitä ei pysty poistamaan tietueesta
    käsin poistamatta ensin varauksia.

Valitse lopuksi _Poista valitut tietueet_. Jos et haluakaan poistaa,
valitse _Peruuta_ tai sulje ikkuna/välilehti, jolloin poistoa ei tehdä.

Poiston jälkeen saat kuittauksen poistetuista tietueista  
<img src="/assets/files/docs/Tyokalut/tietueidenpoisto4.png" alt="" style="width:30.0%" />

---

## 10.10 Tietueiden muokkaus eräajona

Tietueiden muokkauksessa eräajona voi lisätä/muokata tai poistaa
MARC-kenttiä. Valituille tietueille voi esimerkiksi lisätä kielikoodin
tai huomautuksen.

Erämuokkauksessa on rajoituksia

- jos tietueessa on jo olemassa muokattavaksi valittu MARC-kenttä,
  päivittää työkalu sen. Se ei lisää uuttaa toistumaan kentästä.
- kiinteämittaisia kenttiä ei pysty muokkaamaan/poistamaan

Ennen kuin tietueita voi muokata, pitää määrittää käytettävä
\[\[11_Työkalut\#1113-MARC-muokkauksen-pohjat\|MARC-muokkauksen
pohja\]\].

Tietueiden erämuokkaukseen pääse kahta kautta.

**Korista**  
<img src="/assets/files/docs/Tyokalut/tietueidenmuokkaus1.png" alt="" style="width:40.0%" />

- Vie muokattavat tietueet koriin ja valitse kaikki (tai halutut) ja
  valitse sitten _Erämuokkaus_.

**Työkaluista**  
<img src="/assets/files/docs/Tyokalut/tietueidenmuokkaus.png" alt="" style="width:30.0%" />

- Valitse ensin, muokataanko bibliografisia tietueita (nimekkeitä) vai
  auktoriteettitietueita (esim. kirjailija, asiasana).
- Seuraavaksi valitaan muokattavat tietueet joko
  - tuomalla ne tiedostosta, jossa on lista tietuenumeroista
    (biblionumber). Tällaisen voi luoda esim. sql-kyselyllä
    Raportointi-osiossa tai keräämällä tietuenumeroita Muistioon.
  - listaamalla tietuenumerot tekstikenttään yksi per rivi
- Viimeiseksi valitaan, mitä muokkauspohjaa käytetään eli mitä
  muutoksia tietueille tehdään.

Valitse sitten _Jatka_.

<img src="/assets/files/docs/Tyokalut/tietueidenmuokkaus2.png" alt="" style="width:30.0%" />

- Voit vielä vaihtaa muokkauspohjan tai tullessasi korista käsin,
  valitse se nyt.
- Voit tarkistaa muokkausen tuloksen valitsemalla _Näytä MARC_,
  jolloin avautuu MARC-tietueen esikatselu ja mukana on myös haluttu
  muutos:

<img src="/assets/files/docs/Tyokalut/tietueidenmuokkaus3.png" alt="" style="width:60.0%" />

Kun kaikki on kuten pitääkin, valitse _Muokkaa valittuja tietueita_.

Saat kuittauksen, onnistuiko muokkaus:

<img src="/assets/files/docs/Tyokalut/tietueidenmuokkaus4.png" alt="" style="width:30.0%" />

---

## 10.11 Automaattinen niteen muokkaus iän mukaan

Niteitä voi muokata automaattisesti iän mukaan. Työkalulla luodaan
säännöt, joiden mukaan niteitä käsitellään automaattisesti. Sääntöjen
lisäksi järjestelmänkehittäjän pitää ajastaa yöllinen ajo
(_misc/cronjobs/automatic_item_modification_by_age.pl_), joka
varsinaisesti sitten tekee sääntöjen mukaiset muutokset.

Olemassa olevat säännöt näkyvät työkalun etusivulla. Sitä muokkaamaan ja
uusia sääntöjä luomaan pääsee valitsemalla _Muokkaa sääntöjä_  
<img src="/assets/files/docs/Tyokalut/ianmukaan.png" alt="" style="width:30.0%" />  
Voit nyt joko muokata olemassa olevaa tai tehdä uuden säännön
valitsemalla _Lisää sääntö_  
<img src="/assets/files/docs/Tyokalut/ianmukaan2.png" alt="" style="width:40.0%" />

Uudelle säännölle määritetään seuraavat:

<img src="/assets/files/docs/Tyokalut/ianmukaan3.png" alt="" style="width:40.0%" />

- **Ikä päivinä**. Ikä lasketaan niteen hankintapäivä-kentän mukaan.
- **Ehdot**, jotka pitää täyttyä ennen kuin nidettä muokataan. Voit
  lisätä useamman ehdon valitsemalla _Lisää ehto_ kentän vierestä.
- **Korvaajat**, eli mikä tieto niteeseen lisätään/muokataan. Voit
  lisätä useamman korvaajan valitsemalla _Lisää korvaaja_ kentän
  vierestä.

Kun sääntö on valmis, valitse _Tallenna_-painike, joka “kelluu” sivun
yläreunassa sivua vieritettäessä.

Säännön voi poistaa valitsemalla _Poista tämä sääntö_.

---

## 10.12 Tarratulostin

### Ohje käyttäjälle

Ennen tulostamista valitaan vasemmasta reunasta ensin, mitä tarrapohjaa
käytetään, jos niitä on useampi. Koska tulostimia ja pdf-ohjelmia on
erilaisia, saattaa tarrojen sijoittumista arkille joutua säätämään. Se
onnistuu tekstilaatikon alapuolella olevilla marginaali-asetuksilla.
Niissä voi käyttää sekä plus että miinusmerkkisiä arvoja sen mukaan,
mihin suuntaan arkkia pitää asemoida. Käytännössä voi säätää vasemman ja
ylämarginaalin alkukohtaa. Testit kannattaa tehdä normaalille
kopiopaperille ja verrata asetteluja esim. valoa vasten varsinaiseen
tarra-arkkiin, jolloin ei kulu turhaan varsinaisia tarra-arkkeja.

**Huomioi**, että pdf-ohjelman tulostusasetuksista kannattaa aina
valita, ettei skaalata tai soviteta arkin kokoon. Jos käytetään
skaalausta, se muuttaa tarrojen asemointia myös suhteessa toisiinsa,
jolloin ne eivät enää osu oikeaan kohtaan arkkia (esim. liian lähelle
tai kauas ylempänä olevasta tarrasta).

<img src="/assets/files/docs/Tyokalut/tarratulostin.png" alt="" style="width:30.0%" />

#### Niteiden lisääminen tulostettavaksi

Niteet voi lisätä kahdella tavalla tulostettavaksi. Joko lisäämällä
tulostettavien niteiden viivakoodit tekstikenttään tai lisäämällä ne
niteen muokkauksen kautta tarratulostulistalle.

Laita niteen muokkauksessa rasti kohtaan _Lisää tulostuslistalle_ ja
valitse sitten yläpuolelta _Tallenna_  
<img src="/assets/files/docs/Tyokalut/tarratulostin5.png" alt="" style="width:25.0%" />  
Nide siirtyy _labels printing_ -nimiselle Kohan listalle. Jos listaa ei
ollut ennestään olemassa, luodaan sellainen.  
<img src="/assets/files/docs/Tyokalut/tarratulostin6.png" alt="" style="width:40.0%" />  
Listalla olevat niteet näkyvät nyt tarratulostimen tekstikentässä.
Listan voi tyhjentää valitsemalla _Tyhjennä lista_. Huomioi, että nappi
ei tyhjennä tekstikentästä niitä viivakoodeja, jotka siihen on lisätty
itse manuaalisesti.

<img src="/assets/files/docs/Tyokalut/tarratulostin7.png" alt="" style="width:30.0%" />  
Tyhjennyksestä tulee popup-kuittaus:

![](/assets/files/docs/Tyokalut/tarratulostin8.png)  
Ja Kohan labels printing -lista on sen jälkeen tyhjä:  
<img src="/assets/files/docs/Tyokalut/tarratulostin9.png" alt="" style="width:30.0%" />

#### Tulostaminen

Säädä tarvittaessa marginaaleja ja valitse sitten _Tulosta_. Voit
ohittaa tarroja arkilta laittamalla tekstikenttään tyhjän rivin.
Esimerkiksi kaksi tyhjää riviä ohittaa kaksi ensimmäistä tarraa ja
aloittaa tulostamisen vasta kolmannesta.  
<img src="/assets/files/docs/Tyokalut/tarratulostin1.png" alt="" style="width:30.0%" />  
Valitse _Tulosta_, jonka jälkeen tulee popup, joka kysyy mitä
tiedostolle tehdään. Avataanko tiedosto pdf-ohjelmalla vai
tallennetaanko se. Tiedosto kannattaa avata.  
<img src="/assets/files/docs/Tyokalut/tarratulostin2.png" alt="" style="width:30.0%" />  
Tiedosto avataan tietokoneellesi asennetulla pdf-tiedostojen
oletusohjelmalla, josta voit sen sitten tulostaa ohjelman
tulostustoimintoja käyttäen. Tarra-arkki näytetään sellaisena kuin se
tulostuu. Alla pari erilaista esimerkkiä asetteluista.  
<img src="/assets/files/docs/Tyokalut/tarratulostin3.png" alt="" style="width:50.0%" />  
<img src="/assets/files/docs/Tyokalut/tarratulostin4.png" alt="" style="width:45.0%" />

---

### Ohje tarrapohjan muokkaajalle

Ohje tarrapohjan muokkaajalle löytyy Teknisen dokumentaation puolelta:
\[\[/Tarrapohjien_muokkaus\|Tarrapohjan muokkaaminen\]\]

---

## 10.13 MARC-muokkauksen pohjat

Kohassa pystyy muokkaamaan tietueita eräajona ja sitä varten tarvitaan
säännöt, minkä pohjalta muokkausta tehdään. MARC-muokkauksen pohjat ovat
tätä varten.

<img src="/assets/files/docs/Tyokalut/marcpohja.png" alt="" style="width:30.0%" />

### Uuden muokkauspohjan tekeminen

Uuden pohjan voi tehdä valitsemalla _Uusi pohja_  
<img src="/assets/files/docs/Tyokalut/marcpohja1.png" title="Kuvakaappaus, jossa on ympyröity punaisella laatikolla Uusi pohja -niminen nappula" alt="Kuvakaappaus, jossa on ympyröity punaisella laatikolla Uusi pohja -niminen nappula" style="width:30.0%" />

Anna pohjalle kuvaava nimi. Voit myös kopioida malliksi jonkin jo
olemassa olevan pohjan.  
<img src="/assets/files/docs/Tyokalut/marcpohja2.png" title="Kuvakaappaus uuden pohjan luonnista. Kuvassa on tekstikenttä Nimi ja alasvetovalikko, josta voi valita kopioitavan mallin. Nimi-kenttä on pakollinen." alt="Kuvakaappaus uuden pohjan luonnista. Kuvassa on tekstikenttä Nimi ja alasvetovalikko, josta voi valita kopioitavan mallin. Nimi-kenttä on pakollinen." style="width:30.0%" />

Sen jälkeen pohjalle pitää lisätä toiminnot eli mitä muokkauksia
tietueille halutaan tehdä. Valitse _Uusi toiminto_  
<img src="/assets/files/docs/Tyokalut/marcpohja3.png" title="Kuvakaappaus, jossa näkyy kaksi nappulaa: uusi pohja sekä uusi toiminto. Jälkimmäinen on ympyröity punaisella laatikolla." alt="Kuvakaappaus, jossa näkyy kaksi nappulaa: uusi pohja sekä uusi toiminto. Jälkimmäinen on ympyröity punaisella laatikolla." style="width:25.0%" />

Valitse ensimmäisestä valikosta, haluatko poistaa, lisätä/päivittää,
siirtää, kopioida vai kopioida ja korvata.  
<img src="/assets/files/docs/Tyokalut/marcpohja4.png" title="Kuvakaappaus, jossa on avattuna alasvetovalikko, jossa on vaihtoehdot poista, lisää/päivitä, siirry, kopio, kopioi ja korvaa" alt="Kuvakaappaus, jossa on avattuna alasvetovalikko, jossa on vaihtoehdot poista, lisää/päivitä, siirry, kopio, kopioi ja korvaa" style="width:30.0%" />

Sitten valitaan, koskeeko toiminto kaikkia määritettyjä kenttiä vai 1.
vastaan tulevaa kenttää, joka täyttää kenttä-määrityksen.  
<img src="/assets/files/docs/Tyokalut/marcpohja5.png" title="Kuvakaappaus, jossa on avattuna alasvetovalikko, josta voi valita vaihtoehdot kaikki tai 1." alt="Kuvakaappaus, jossa on avattuna alasvetovalikko, josta voi valita vaihtoehdot kaikki tai 1." style="width:30.0%" />

Seuraavaksi kirjoitetaan, mitä MARC-osakenttää halutaan muokata.  
<img src="/assets/files/docs/Tyokalut/marcpohja6.png" title="Kuvakaappaus, jossa on ympyröity punaisella laatikolla kaksi kirjoituskenttää. Toisessa on marc-kentän numero 500 ja toisessa marc-osakentän kirjain a" alt="Kuvakaappaus, jossa on ympyröity punaisella laatikolla kaksi kirjoituskenttää. Toisessa on marc-kentän numero 500 ja toisessa marc-osakentän kirjain a" style="width:30.0%" />

Voit määrittää myös, pitääkö täyttyä jokin ehto ennen kuin muutos
tehdään. Valittavissa on jos/paitsi-vaihtoehdot. Tämä ei ole
pakollinen.  
<img src="/assets/files/docs/Tyokalut/marcpohja61.png" title="Kuvakaappaus, jossa on avattuna alasvetovalikko, jossa on vaihtoehdot jos ja paitsi" alt="Kuvakaappaus, jossa on avattuna alasvetovalikko, jossa on vaihtoehdot jos ja paitsi" style="width:20.0%" />

Määrittele ehdon vaatima kenttä sekä missä tapauksessa se otetaan
huomioon.  
<img src="/assets/files/docs/Tyokalut/marcpohja7.png" title="Kuvakaappauksessa on kaksi kirjoituskenttää sek avattu alasvetovalikko. Kentiin on kirjoitettu 100 ja a. Alasvetovalikossa on vaihtoehdot &quot;on jo olemassa&quot;, &quot;ei ole olemassa&quot;, osumat ja &quot;ei osumaa&quot;" alt="Kuvakaappauksessa on kaksi kirjoituskenttää sek avattu alasvetovalikko. Kentiin on kirjoitettu 100 ja a. Alasvetovalikossa on vaihtoehdot &quot;on jo olemassa&quot;, &quot;ei ole olemassa&quot;, osumat ja &quot;ei osumaa&quot;" style="width:30.0%" />

Voit myös käyttää ehdossa RegEx-sääntöä halutessasi. Kuvaus-kenttään
voit kuvailla, mitä toiminto tekee. Toiminto tallennetaan valitsemalla
_Lisää toiminto_.  
<img src="/assets/files/docs/Tyokalut/marcpohja8.png" title="Kuvakaappaus valmiiksi määritetystä toiminnosta. Punaisella on ympyröity kohdat RegEx, Kuvaus sekä Lisää toiminto -nappula. Kuvaus-kenttään on kirjoitettu Tällä säännöllä voi poistaa Aku Ankoista 500a-kentän." alt="Kuvakaappaus valmiiksi määritetystä toiminnosta. Punaisella on ympyröity kohdat RegEx, Kuvaus sekä Lisää toiminto -nappula. Kuvaus-kenttään on kirjoitettu Tällä säännöllä voi poistaa Aku Ankoista 500a-kentän." style="width:40.0%" />

Toimintoja voi lisätä useamman samaan pohjaan ja niiden
suoritusjärjestystä voi muuttaa ensimmäisen sarakkeen nuolilla.  
<img src="/assets/files/docs/Tyokalut/marcpohja9.png" title="Kuvakaappaus, jossa näkyy valmiina juuri tehty sääntö taulukkona. Ensimmäissä sarakkeessa lukee Muuta järjestystä, toisessa sarakkeessa lukee tilaus, kolmannessa sarakkeessa lukee Toiminto, neljännessä sarakkeessa lukee Kuvaus, viidennessä sarakkeessa on muokkaa-nappula, kuudennessa sarakkeessa on poista-nappula." alt="Kuvakaappaus, jossa näkyy valmiina juuri tehty sääntö taulukkona. Ensimmäissä sarakkeessa lukee Muuta järjestystä, toisessa sarakkeessa lukee tilaus, kolmannessa sarakkeessa lukee Toiminto, neljännessä sarakkeessa lukee Kuvaus, viidennessä sarakkeessa on muokkaa-nappula, kuudennessa sarakkeessa on poista-nappula." style="width:50.0%" />

---

## 10.14 Kalenteri

Kalenteri-työkalulla voi määrittää kirjaston aukiolo- ja sulkupäivät.
Jos päivä on merkitty kalenterissa suljetuksi, ei sille tule eräpäiviä
eikä varausten viimeisiä noutopäiviä. Kalenterit määritetään erikseen
jokaiselle kirjastolle.

Kun sivulle menee, avautuu näkyville käyttäjän kirjautumiskirjaston
kalenteri. Oikealla on vinkkejä ja listoja määritetyistä
kiinniolopäivistä.  
<img src="/assets/files/docs/Tyokalut/kalenteri1.png" title="Kuvakaappaus kalenteri-työkalun näkymästä. Esillä on vasemmalla Oulun kaupungin pääkirjaston kalenteri heinäkuulta 2020. Oikealla on vinkkejä ja listoja kiinniolopäivistä" alt="Kuvakaappaus kalenteri-työkalun näkymästä. Esillä on vasemmalla Oulun kaupungin pääkirjaston kalenteri heinäkuulta 2020. Oikealla on vinkkejä ja listoja kiinniolopäivistä" style="width:80.0%" />

### 10.14.1 Kiinniolon lisääminen

Kiinniolo lisätään valitsemalla kalenterista haluttu päivämäärä tai
päivämäärävälin ensimmäinen päivä.

<img src="/assets/files/docs/Tyokalut/kalenteri2.png" title="Kuvakaappaus, jossa näkyy valittavissa olevat vaihtoehdot. Tarkempi kuvaus varsinaisessa tekstissä" alt="Kuvakaappaus, jossa näkyy valittavissa olevat vaihtoehdot. Tarkempi kuvaus varsinaisessa tekstissä" style="width:50.0%" />

Kun klikkaat aloituspäivämäärää, avautuu valikko, josta voi valita
päivämäärävälin. Nimeke-kenttään voi kirjoittaa haluamansa nimen
kiinniolopäivälle/aikavälille, esim. Suljettu tai Pääsiäinen.
Kuvaus-kenttään voi kuvata tarkemmin sulkutietoa. Sitten voi valita
koskeeko valinta

- Kiinni vain tänä päivänä
  - yksittäinen kiinniolopäivä
- Kiinni joka viikko tänä päivänä
  - tällä voi määrittää helposti esim. kaikki sunnuntait
    kiinnioleviksi
- Kiinni joka vuosi samana päivänä
  - tällä voi määrittää joka vuosi samana kalenteripäivänä toistuvat
    juhlapyhät kiinnioleviksi, esim. jouluaatto
- Kiinni aikavälillä
  - tämä pitää valita, jotta Päivästä-päivään valinta ylempänä
    toimii
- Kiinni aikavälillä joka vuosi
  - toimii kuten kiinni joka vuosi samana päivänä, mutta
    määritetäänkin aikaväli, esim. joulunpyhät
- Kopioi kaikkiin kirjastoihin
  - jos tähän laittaa rastin, kopioidaan määritys kaikkiin
    kirjastoihin. Kätevä toiminto silloin, kun pitää saada tehtyä
    järjestelmänlaajuisia määrityksiä. Esim. kaikki kirjastot
    suljettu järjestelmäpäivityksen vuoksi tai kaikkia koskeva
    juhlapyhä.

Kysymysmerkistä vaihtoehdon perässä saat tarkemman kuvauksen
vaihtoehdosta.

### 10.14.2 Sulkupäivien värikoodit

Eri tyyppiset sulkupäivät on merkitty eri väreillä.

<img src="/assets/files/docs/Tyokalut/kalenteri4.png" title="Kuvakaappaus kalenterissa käytettyjen värien selitteestä" alt="Kuvakaappaus kalenterissa käytettyjen värien selitteestä" style="width:40.0%" />

- harmaa on työpäivä eli päivälle voi tulla erä- ja noutopäiviä.
- punainen on yksittäinen, ei toistuva kiinniolopäivä. Myös
  aikavälillä suljetuksi merkityt päivät merkitään punaisella.
- keltainen on viikottain toistuva kiinniolopäivä.
- oranssi on vuosittain toistuva kiinniolopäivä.
- sininen on poikkeus määritettyyn kiinnioloon eli käytännössä päivä
  on avoin ja sille voi tulla erä- ja noutopäiviä.

Alla kuvakaappaus, miltä ne näyttävät kalenterissa.  
<img src="/assets/files/docs/Tyokalut/kalenteri3.png" title="Kuvakaappaus kalenterista, jossa on punaisia, sininen, keltaisia ja oranssi merkintä" alt="Kuvakaappaus kalenterista, jossa on punaisia, sininen, keltaisia ja oranssi merkintä" style="width:30.0%" />

Myös kuluva päivä on merkitty kalenteriin kellertävällä värillä, jos
kyseinen päivä on avoinna oleva päivä. Jos päivä on merkitty suljetuksi,
näkyy siinä sulkupäivän tyypin mukainen väri.  
<img src="/assets/files/docs/Tyokalut/kalenteri5.png" title="Kuvakaappaus kalenterista, jossa on ympyröity punaisella laatikolla kuluva päivä" alt="Kuvakaappaus kalenterista, jossa on ympyröity punaisella laatikolla kuluva päivä" style="width:30.0%" />

### 10.14.3 Sulkutiedon poistaminen

Sulkupäiviä voi myös poistaa, jos ne ovat virheellisiä tai tarpeettomia.

Valitse päivä tai aikavälin ensimmäinen päivä.

<img src="/assets/files/docs/Tyokalut/kalenteri6.png" title="Kuvakaappaus, jossa on ympyröity punaisella laatikolla poisto-vaihtoehdot: poista tämä päivä, poista yksittäiset kiinniolot aikavälillä, poista toistuvat kiinniolot aikavälillä, poista poikkeukset aikaväliltä" alt="Kuvakaappaus, jossa on ympyröity punaisella laatikolla poisto-vaihtoehdot: poista tämä päivä, poista yksittäiset kiinniolot aikavälillä, poista toistuvat kiinniolot aikavälillä, poista poikkeukset aikaväliltä" style="width:50.0%" />

Määritä tarvittaessa aikavälin loppupäivä. Valitse haluamasi
poisto-vaihtoehto ja klikkaa Tallenna.

### 10.14.4. Sulkutiedon muokkaaminen

Sulkupäiviä voi muokata valitsemalla halutun päivän tai aikavälin
ensimmäisen päivän. Voit muuttaa esim. Nimekettä ja Kuvausta. Valitse
sitten vaihtoehto _Muokkaa kiinniolopäivää_ ja klikkaa Tallenna-nappia.

<img src="/assets/files/docs/Tyokalut/kalenteri7.png" title="Kuvakaappaus, jossa näkyy muokkaustila ja on ympyröitynä punaisella laatikolla kohdat Nimeke, Kuvaus ja Muokkaa kiinniolopäivää" alt="Kuvakaappaus, jossa näkyy muokkaustila ja on ympyröitynä punaisella laatikolla kohdat Nimeke, Kuvaus ja Muokkaa kiinniolopäivää" style="width:50.0%" />

---

## 10.15 Lokien katselu

Lokien katselu -työkalulla pystyy hakemaan mm. asiakkaisiin, lainoihin,
maksuihin, varauksiin ja luettelointitietueisiin liittyviä muutoksia.
Työkaluun pääsee myös esim. asiakastietojen ja perustiedot-näytön
kautta, jolloin sinne on valmiiksi täytettynä asiakkan tai tietueen
tunnista. Järjestelmäasetuksissa Lokit-osiossa määritetään, mitä tietoja
tallennetaan muutoshistoriaan eli lokitetaan. Tiedot haetaan tietokannan
action_logs-taulusta.

Työkalun käyttö vaatii harjoittelua, jotta osaa tulkita tuloksia. Eri
osioissa ja toiminnoissa kirjataan asiaoita eri tavalla, joten mitään
kaikenkattavaa ohjetta ei pysty tekemään.

<img src="/assets/files/docs/Tyokalut/lokit.png" title="Kuvakaappaus Lokien katselu -sivulta. Ylhäältä alas: Virkailija, osiot, toiminnot, ID-tunnus, tiedot, käyttöliittymä, alkupvm, loppupvm, selaimen näytölle, tiedostoon, nimi" alt="Kuvakaappaus Lokien katselu -sivulta. Ylhäältä alas: Virkailija, osiot, toiminnot, ID-tunnus, tiedot, käyttöliittymä, alkupvm, loppupvm, selaimen näytölle, tiedostoon, nimi" style="width:45.0%" />

Vaihtoehtojen kuvaukset ja sulkeissa valintaa vastaava taulun sarake
action_logs-taulussa:

- **Virkailija** (user): tähän kohtaan voi määrittää, minkä
  käyttäjätunnuksen tekemiä muutoksia haetaan. Kenttään laitetaan
  käyttäjän borrowernumber.
- **Osiot** (module): määrittele, minkä Kohan osion tietoja haluat
  hakea: kaikki, luettelo (luettelointitiedot), auktoriteetit,
  asiakkaat, hankinta, kausijulkaisut, varaukset, lainaus ja palautus,
  kirje, maksut, järjestelmäasetukset, cron jobit, raportit
- **Toiminnot** (action): valitse minkälaisia toimintoja haluat hakea:
  kaikki, lisää (lisäys), poista, muokkaa, lainaus, palautus, uusi,
  luo, poista, keskeytä, jatka, lisää viesti, poista viesti, vaihda
  salasanaa, aja
- **ID-tunnus** (object): tähän määritellään tutkittavan tiedon
  tunniste, mikä riippuu siitä, mitä ollaan tutkimassa: asiakkaan
  borrowernumber, tietueen biblionumber, niteen itemnumber, varauksen
  id
- **Tiedot** (info): Tämän kentän tieto riippuu haettavasta osiosta,
  koska siihen kirjataan tehty muutos. Kirjaustapa vaihtelee eri
  toiminnoissa. Hakuehtona voi käyttää esim. biblionumberia,
  borrowernumberia tai itemnumberia. Kenttää voi kirjoittaa myös ihan
  sanoja, joita arvelee kirjatun muutoksiin, kuten phone.
- **Käyttöliittymä** (interface): mitä kautta muutos on tehty: kaikki,
  virkailijaliittymä, verkkokirjasto, SIP (automaatit), komentorivi.
  Näiden lisäksi tuloksissa voi olla myös vaihtoehtoa REST, joka
  tarkoittaa REST-rajapintaa.
- **Alkupvm ja Loppupvm** (timestamp): tähän voi ja kannattaa
  määrittää aikavälin, miltä tietoja hakee. Lokitietoja on paljon,
  joten aikaväli kannattaa määrittää mahdollisimman tarkasti. Lisäksi
  ei ole monestikaan tarkoituksenmukaista esim. tutkia asiakkaan
  täydellistä muutoshistoriaa, jolloin rajaaminen on tarpeen.

Tulostus-otsikon alla

- **Selaimen näytölle**: tulokset näytetään selaimesssa
- **Tiedostoon ja nimi**: tulokset voi viedä CSV-tiedostoksi ja
  nimi-kenttään voi määrittää tiedostolle nimen.

Esimerkki, jossa haettu asiakkaan muutoslokilta kaikki tiedot tietyllä
välillä:

<img src="/assets/files/docs/Tyokalut/lokit2.png" title="Kuvakaappaus lokin hakutuloksista. Taulukko, jossa sarakkeet pvm, virkailija, osio, toiminto, ID-tunnus, tiedot ja käyttöliittymä" alt="Kuvakaappaus lokin hakutuloksista. Taulukko, jossa sarakkeet pvm, virkailija, osio, toiminto, ID-tunnus, tiedot ja käyttöliittymä" style="width:90.0%" />

- Virkailija nro 0 tarkoittaa, että muutoksen on tehnyt jokin
  järjestelmän oma toiminto, ei virkailija.

---

## 10.16 Uutiset

Uutiset-työkalulla voi kirjoittaa uutisia tai tiedotteita
virkailijaliittymään, Kohan verkkokirjastoon ja kuiteille. Uutisia voi
kirjoittaa niillä kielillä, mitä omaan Kohaan on asennettu.

<img src="/assets/files/docs/Tyokalut/uutiset.png" title="Kuvakaappaus Uutiset-työkalun aloitusnäkymästä, jossa on useampi uutinen näkyvissä" alt="Kuvakaappaus Uutiset-työkalun aloitusnäkymästä, jossa on useampi uutinen näkyvissä" style="width:95.0%" />

- **Paikka**: missä uutinen näytetään
- **Kirjasto**: mille kirjastoille (perustuu kirjautumiskirjastoon)
  uutinen näytetään
- **Numero**: monentena näytetään, jos oon useampi uutinen
- **Julkaisuvuosi**: julkaisupäivä
- **Vanhentumispvm**: Vanhentumispäivä, jos sellainen on määritetty
- **Nimeke**: Uutisen otsikko
- **Tekijä**: Uutisen tekijä. Uutisten kirjoittajaksi merkitään sisään
  kirjautunut käyttäjä. _NewsAuthorDisplay_ -järjestelmäasetuksella
  voi määrittää, piilotetaanko tai näytetäänkö uutisen kirjoittajan
  nimi.
- **Uutiset**: Uutisten sisältö
- **Toiminnot**: Muokkaa-napista voi muokata uutista ja Poista-napista
  voi poistaa uutisen

Uutiset näkyvät virkailijaliittymässä etusivun vasemmassa reunassa.

<img src="/assets/files/docs/Tyokalut/uutiset4.png" title="Etusivulta kuvakaappaus, jossa näkyy kaksi uutista ja vähän muita osia sivusta" alt="Etusivulta kuvakaappaus, jossa näkyy kaksi uutista ja vähän muita osia sivusta" style="width:50.0%" />

### 10.16.1 Uuden uutisen luominen

Valitse sivun yläreunasta _Luo uusi_.

<img src="/assets/files/docs/Tyokalut/uutiset2.png" title="Kuvakaappaus uuden uutisen lisäyssivusta" alt="Kuvakaappaus uuden uutisen lisäyssivusta" style="width:70.0%" />

Valitse ja täytä tarvittavat tiedot:

- **Näyttöpaikka**: näytetäänkö uutinen kaikkialla,
  virkailijatyökalussa, kuiteissa vai verkkokirjastossa (voit valita
  erikseen kieliversiot)
- **Kirjasto**: näytetäänkö uutinen kaikille kirjastoille vai vain
  tietylle kirjastolle
- **Nimeke**: Uutisen nimi tai otsikko. Pakollinen tieto.
- **Julkaisupvm**: voi joko jättää tyhjäksi, jolloin uutinen
  julkaistaan heti tai valita tietty julkaisupäivä.
- **Vanhentumispvm**: voi joko jättää tyhjäksi, jolloin uutinen ei
  vanhene tai valita tietty vanhentumispäivä, jolloin uutinen
  piilotetaan käyttäjiltä valittuna päivänä.
- **Näyttöjärjestys**: jos uutisia on useampi, tällä voi määrittää
  niiden keskinäinen järjestys
- **Uutiset**: Tähän kirjoitetaan varsinainen uutinen. Käytettävissä
  on WYSIWYG-muotoilut (what you see is what you get).

Tallenna valitsemalla OK tai peruuta valitsemalla Peruuta.

### 10.16.2 Uutisen poistaminen

Uutisen voi poistaa klikkaamalla halutun uutisen kohdalla Poista-nappia.

<img src="/assets/files/docs/Tyokalut/uutiset3.png" title="Uutiset-sivulta kuvakaappaus, jossa on ympyröitynä punaisella laatikolla Poista-nappula" alt="Uutiset-sivulta kuvakaappaus, jossa on ympyröitynä punaisella laatikolla Poista-nappula" style="width:90.0%" />

**Huom!** Vanhentuneet uutiset poistuvat käyttäjien näkyviltä
vanhentumispäivänä, mutta eivät poistu automaattisesti uutislistasta. Ne
pitää halutessaan poistaa manuaalisesti Poista-napilla.
{: .notice--warning}

---

## 10.17 Työkaluliitännäiset

Koha-Suomella ei ole tällä hetkellä työkalu-liitännäisiä.

<img src="/assets/files/docs/Tyokalut/liitannaiset.png" title="Työkaluliitännäiset-sivulta kuvakaappaus, jossa kerrotaan &quot;Ei työkaluiksi luettavia asennettuja liitännäisiä" alt="Työkaluliitännäiset-sivulta kuvakaappaus, jossa kerrotaan &quot;Ei työkaluiksi luettavia asennettuja liitännäisiä" style="width:70.0%" />

Koha-Suomella on käytössä yksi raporttiliitännäinen, jonka saa esille
klikkaamalla _Katso liitännäisiä luokan mukaan_ -nappia tai menemällä
Raportit-osioon.

<img src="/assets/files/docs/Tyokalut/liitannaiset2.png" title="Kuvakaappaus, jossa näkyy raporttiliitännäisen tiedot" alt="Kuvakaappaus, jossa näkyy raporttiliitännäisen tiedot" style="width:70.0%" />

---

## 10.18 Siirtokokoelmat

Siirtokokoelmat
