# Reissaaja - Matkakumppani

**Reissaaja** on moderni, selaimessa toimiva sovellus, joka auttaa käyttäjää tutkimaan ympäristöään hyödyntämällä useita eri avoimia rajapintoja (API). Sovellus yhdistää paikkatietoja, interaktiivisen kartan ja Wikipedia-artikkelit yhdeksi saumattomaksi kokemukseksi.



---

## 🚀 Ominaisuudet

- **Reaaliaikainen paikannus:** Hyödyntää selaimen Geolocation API:a käyttäjän tarkan sijainnin löytämiseen.
- **Interaktiivinen kartta:** Käyttää Leaflet.js-kirjastoa ja OpenStreetMap-dataa sijainnin ja kohteiden visualisointiin.
- **Kohdehaku (POI):** Hakee lähellä olevia ravintoloita, kauppoja, nähtävyyksiä ja palveluita Overpass API:n avulla.
- **Paikallinen historia:** Listaa Wikipedia-artikkeleita, jotka liittyvät maantieteellisesti käyttäjän sijaintiin.
- **Responsiivinen Dark Mode:** Tyylikäs käyttöliittymä, joka mukautuu laitteen kokoon ja tukee tummaa teemaa.

---

## 🛠️ Tekninen toteutus

Projekti on toteutettu ilman ulkoisia palvelinratkaisuja (Serverless), hyödyntäen puhtaasti modernia JavaScriptiä (ES6+) ja selainten tarjoamia ominaisuuksia.

### Käytetyt rajapinnat (APIs - Kaikki ilmaisia!) 

1.  **Geolocation API:** Käyttäjän koordinaattien haku.
2.  **Overpass API (OpenStreetMap):** Paikkatietokantaan kohdistuvat kyselyt.
3.  **MediaWiki API:** Wikipedian paikkatietohaku.
4.  **Leaflet.js:** Karttakomponentin hallinta.



---

## 📦 Asennus ja käyttö

Projekti ei vaadi erillistä asennusta tai API-avaimia.

Avaa index.html selaimessasi.

Salli sijaintitietojen käyttö pyydettäessä.

Ulkoasu ja UI/UX
Sovelluksessa on panostettu käyttäjäystävällisyyteen:

Glassmorphism: Käyttöliittymässä on hyödynnetty läpinäkyviä ja sumentavia tasoja (backdrop-filter).

Mobile First: Sovellus on täysin responsiivinen ja optimoitu yhdellä kädellä käytettäväksi mobiililaitteilla.

Teeman hallinta: Teeman vaihto on sijoitettu helposti saataville, mutta se ei häiritse päätoimintoja.

