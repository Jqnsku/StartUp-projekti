# StartUp-projekti

# Projektisuunnitelma

Projektisuunnitelmasta käy ilmi projektin tärkeimmät tiedot, kuten tavoite, kohderyhmä, vaatimukset ja toimintatavat.

Voitte käyttää tätä tiedostoa pohjana suunnitelmallenne tai luoda uuden tiedoston.

# Suunnitelman rakenne

## Projektin kuvaus
Kertoo perustiedot projektista

* Projektin nimi
* Yleiskuvaus projektista ja sen tavoitteista
* Projektin kohderyhmä

## Laajuus
Kertoo kuinka laajaa projektia ollaan tekemässä

* Listaus toiminnallisuuksista joita projektissa on
    * Erottele minimitoiminnallisuudet (ne jotka on pakko olla jotta projekti toimiii) ja "kiva olla" toiminnallisuudet (tehdään jos jää aikaa)

### Esimerkki TODO app (web)

Minimitoiminnallisuudet:
* Käyttäjätilien luonti ja kirjautuminen
* Tehtävien lisääminen, muokkaus ja poisto
* Tehtävien tilan seuranta (kesken/valmis)

Tehdään jos on aikaa:
* Mobiilisovellus
* Reaaliaikainen yhteistyö
* Integraatiot muihin palveluihin

## Vaatimukset
Kertoo vaatimukset lopulliselle tuotteelle

* Toiminnalliset vaatimukset
* Ei Toiminnalliset vaatimukset

### Esimerkki TODO app (web)
Toiminnalliset vaatimukset:

* Käyttäjä voi rekisteröityä ja kirjautua
* Käyttäjä voi lisätä tehtävän (otsikko + kuvaus)
* Käyttäjä voi merkitä tehtävän valmiiksi

Ei-toiminnalliset vaatimukset:

* Sivun latausaika alle 2 sekuntia
* Responsiivinen käyttöliittymä myös mobiililaitteilla
* Perustason tietoturva (salasanan cryptaus)

## Tekninen suunnittelu
Kertoo mitä teknologioita käytetään projektin kehityksessä

* Frontend
* Backend
* Tietokanta
* Arkkitehtuuri

### Esimerkki
Frontend:
* React,
* Tailwind CSS

Backend:
* Node.js
* Express
* Socket.io

Tietokanta:
* PostgreSQL
* Hostaus Supabasessa

Arkkitehtuuri:
* REST API frontendin ja backendin välillä
* Websocketeilla reaaliaikaisuus, jos aika riittää

## Resurssit
Kertoo tiimin roolit ja käytettävät työkalut

* Roolit
* Työkalut

### Esimerkki
Roolit: 
* Frontend kehittäjä - Oppilas A
* Backend kehittäjä - Oppilas B
* UI designer - Oppilas C
* Projektijohtaja - Oppilas D

Työkalut:
* Github (versionhallinta)
* Figma (suunnittelu)
* Jira (projektinhallinta)
* Discord (kommunikointi ja etäpalaverit)

## Kommunikointisuunnitelma
Kertoo mitä väyliä pitkin kommunikoidaan ja miten toimitaan kommunikointia tarvittavissa tilanteissa

* Pääsääntöiset kommunikointikanavat
* Toimintatavat etänä
* Kokousten tiheys
* Kommunikointi rahoittajan/asiakkaan suuntaan
* Suunnitelma sairastumisten/poissaolojen varalle

### Esimerkki

Pääsääntöinen kommunikointi etänä ja etäpalaverit tapahtuvat discordin kautta.
Paikan päällä keskustelu tapahtuu kasvotusten.

Palaveri pidetään sprintin alussa sekä lopussa, joiden lisäksi on myös päivittäinen daily palaveri, jossa käymme päivän tärkeimmät asiat läpi.

Kommunikointi asiakkaan suuntaan tapahtuu sähköpostilla sekä Teams palavereilla. 

Poissaollessa tiimin jäsen ilmoittaa mahdollisimman nopeasti koko tiimille ja kertoo hänen tärkeimmät tehtävät työnalla.
Tiiminjäsenet puskevat työnsä versionhallintaan, jotta akuutin ongelman ollessa toinen tiiminjäsen voi jatkaa poissaolevan työtä.
Myös versionhallinan branchit pidetään lyhytikäisinä, jolla helpotetaan tilannetta, jos toisen täytyy jatkaa poissaolevan työtä. 

# Seuranta ja raportointi
Miten projektin edistymistä seurataan ja kuinka raportoidaan rahoittajan/asiakkaan suuntaan
* Seurantapalaverit
* Projektinhallinnan työkalut
* Kuinka usein ja miten raportoidaan

### Esimerkki

Projektin edistymistä seurataan daily palaveissa sekä sprintin lopetus palavereissa. Yksittäinen sprintti kestää 2-3 päivää
Projektinhallintaan käytetään Jira taulua, johon jokainen päivittää työnsä tilan.
Projektijohtaja raportoi rahoittajalle/asiakkaalle jokaisen sprintin päädyttyä projektin tilanteen.
