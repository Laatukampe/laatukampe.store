# Laatukampe Affiliate Store

Tämä kansio sisältää yksinkertaisen staattisen verkkosivuston, joka toimii esimerkkinä **Laatukampe.store** ‑affiliatekaupalle. Sivusto koostuu HTML‑ ja CSS‑tiedostoista ja muutamasta esimerkkituotteesta kotituotteille ja elektroniikalle. Jokaisen tuotteen “Osta nyt” ‑linkki tulee korvata oman affiliate‑verkoston seurantalinkillä.

## Rakenne

* **index.html** – verkkokaupan etusivu. Sisältää kategoriat (kotituotteet ja elektroniikka) ja kolme esimerkkituotekorttia per kategoria.
* **style.css** – tyyli‑ ja asettelutiedosto, joka määrittelee sivun fontit, värit ja ruudukkopohjaisen tuotelistan.
* **images/** – kansio, joka sisältää abstraktit kuvat kotituotteille (`home.png`) ja elektroniikalle (`electronics.png`). Voit korvata nämä omilla tuotekuvillasi.

## Miten muokata

1. **Lisää tuotteita:** kopioi olemassa olevia `.product-card` ‑elementtejä `index.html`‑tiedostossa ja muokkaa otsikkoa, kuvausta, tähtiluokitusta ja `href`‑attribuuttia osoittamaan oikeaan affiliate‑linkkiin.
2. **Vaihtamalla kuvat:** korvaa `images/home.png` ja `images/electronics.png` tiedostoillasi. Kuvien kokoa voi säätää CSS:n kautta.
3. **Sivun tyyli:** muokkaa `style.css` tarvittaessa värejä, fontteja tai asettelua vastaamaan brändiäsi.

## GitHub Pages

Voit julkaista tämän sivuston GitHub Pagesissa seuraavasti:

1. Luo uusi GitHub‑repositorio nimeltä `laatukampe.store` (tai haluamallasi nimellä).
2. Kopioi tämän kansion sisältö repositorion juureen.
3. Lisää, commit ja pushaa muutokset GitHubiin.
4. Aseta repositoriosta **GitHub Pages** ‑asetuksista julkaisu `main`‑haaran juurihakemistosta.

Kun olet tehnyt nämä vaiheet, GitHub luo julkisen URL‑osoitteen, josta käyttäjät voivat löytää kauppasi. Muuta domainasetuksissa oman verkkotunnuksesi (`laatukampe.store`) ohjaamaan GitHub‑sivulle. Lisätietoa GitHub Pagesin käyttöönotosta löydät GitHubin virallisista ohjeista.

## Lisenssi

Tämä projekti on tarkoitettu esimerkkikäyttöön eikä sillä ole virallista lisenssiä. Voit vapaasti muokata ja käyttää sitä omassa liiketoiminnassasi.