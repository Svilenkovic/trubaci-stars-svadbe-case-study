<a href="https://trubaci-trubacizasvadbe.rs/"><img src="media/cover.jpg" alt="Trubači Stars Beograd, naslovna strana na laptopu i telefonu" width="100%"></a>

# Trubači Stars Beograd

Beogradski sajt orkestra Trubači Stars, napravljen iz početka na zapuštenom drugom domenu, sa stranom za svaku od 15 opština.

**[trubaci-trubacizasvadbe.rs](https://trubaci-trubacizasvadbe.rs/)** · [Studija slučaja](https://svilenkovic.rs/radovi/trubaci-stars-svadbe) · [English](README.md)

> [!NOTE]
> Klijentski projekat. Izvorni kod pripada klijentu i čuva se u privatnom repozitorijumu. Ova stranica opisuje šta sam uradio i kako.

<table>
  <tr><td><b>Klijent</b></td><td>Trubači Stars</td></tr>
  <tr><td><b>Delatnost</b></td><td>Trubački orkestar za svadbe i proslave</td></tr>
  <tr><td><b>Lokacija</b></td><td>Beograd</td></tr>
  <tr><td><b>Vrsta</b></td><td>Sajt sa više strana</td></tr>
  <tr><td><b>Moj deo posla</b></td><td>Redizajn, izrada, selidba, hosting i održavanje</td></tr>
  <tr><td><b>Tehnologije</b></td><td>PHP 8.3, nginx, vanilla JS, AVIF/WebP, JSON-LD</td></tr>
</table>

## O projektu

Orkestar je već imao dva domena koja su se otimala o iste pretrage, a klijent je tražio treći. Podaci iz Search Console-a i logova za četrnaest dana pokazali su da domen namenjen svadbama ima dvadesetak organskih klikova. Za svadbene upite Google je rangirao drugi sajt, jer je šezdeset gradskih strana na oba domena imalo isti H1. Umesto trećeg domena, ispraznio sam ovaj i napravio ga iz početka kao sajt samo za Beograd, a ostatak Srbije i sve druge prilike ostali su sestrinskom sajtu.

Petnaest opštinskih strana koje se razlikuju samo po imenu Google vidi kao jednu stranu ponovljenu petnaest puta, pa svaka navodi svoja naselja i ono što treba znati o dolasku: parking u bloku na Novom Beogradu nije isti problem kao sokak u Grockoj. Kad sam ih napisao, izmerio sam preklapanje po nizovima od pet reči: u proseku oko devet odsto, najviše četrnaest. Šezdesetak gradskih strana sa starog sajta prešlo je na sestrinski sajt kroz mapu preusmerenja 301. Pre toga sam uklonio pet starijih preusmerenja u suprotnom smeru, jer bi napravila petlju.

## Šta sam uradio

- 28 strana, među njima glavna strana za Beograd, 15 opštinskih strana, svadbeni protokol, cenovnik i dva vodiča za izbor i cenu
- Zajednički delovi i tri pomoćne funkcije, a FAQ oznake se prave iz istog niza kao i pitanja na strani
- Jedan CSS fajl od oko 26 KB i jedna skripta od oko 7 KB, sa ikonama u ugrađenom SVG sprajtu umesto fonta sa ikonama
- Zlatna linija koju skrol iscrtava samo pomoću CSS-a, a stoji mirno gde pregledač to ne podržava
- Ulazne animacije samo za elemente ispod prvog ekrana, pa naslov cenovnika više ne čeka odloženu skriptu
- Brojač klikova na broj telefona koji upisuje po jedan red u rotirajući log, bez kolačića i bez tuđeg alata

## Merenja

| | Performanse | Pristupačnost | Dobre prakse | SEO |
| :-- | :-: | :-: | :-: | :-: |
| Telefon | 99 | 100 | 100 | 100 |
| Desktop | 99 | 100 | 100 | 100 |

PageSpeed Insights, laboratorijsko merenje živog sajta, septembar 2026. Sigurnosna zaglavlja: 6 od 6. HTML validator: bez grešaka. axe provera pristupačnosti: bez prekršaja. Strukturisani podaci: `FAQPage`, `MusicGroup`, `Service`.

## Snimci ekrana

<table>
  <tr>
    <td width="68%" valign="top"><img src="media/desktop.webp" alt="Trubači Stars Beograd, naslovna strana na ekranu širine 1440 px"></td>
    <td width="32%" valign="top"><img src="media/mobile.webp" alt="Trubači Stars Beograd, naslovna strana na telefonu"></td>
  </tr>
</table>

<img src="media/inner-1.webp" alt="Svadbe, slave, krštenja i rođendani: svadba ostaje ovde, ostale prilike vode na sestrinski sajt">
<sub>Svadbe, slave, krštenja i rođendani: svadba ostaje ovde, ostale prilike vode na sestrinski sajt</sub>

<img src="media/inner-2.webp" alt="Cena se zna pre poziva: deo zbog kog je cenovnik i pisan">
<sub>Cena se zna pre poziva: deo zbog kog je cenovnik i pisan</sub>

---

<sub>Izrada: [D. Svilenković](https://svilenkovic.rs).</sub>
