# XML Račun → PDF Konverter

**Jednostavna aplikacija za pretvaranje XML eRačuna u PDF format**

Download link: https://github.com/zaja/UBL-XML-u-PDF-RACUN/archive/refs/heads/main.zip
---
![Model](https://github.com/zaja/UBL-XML-u-PDF-RACUN/blob/main/image.png?raw=true)
## O aplikaciji

Ova aplikacija namijenjena je svima koji zaprime **eRačun u XML formatu bez PDF privitka**. Omogućuje jednostavno pretvaranje XML fakture u pregledni PDF dokument koji se može:

- 📄 **Ispisati** za arhivu ili evidenciju
- 📧 **Proslijediti u knjigovodstvo** u čitljivom formatu
- 💾 **Arhivirati** zajedno s originalnim XML-om

### Zašto ova aplikacija?

Mnogi dobavljači šalju eRačune isključivo u UBL XML formatu koji nije čitljiv bez specijaliziranih alata. Ova aplikacija omogućuje brzo i jednostavno generiranje PDF verzije računa s svim potrebnim podacima.

---

## Pokretanje

1. **Dvostruki klik** na `XML-Racun-PDF.exe`
2. Kliknite **"Odaberi..."** i pronađite XML datoteku računa
3. PDF putanja će se automatski generirati (možete je promijeniti)
4. Kliknite **"Konvertiraj u PDF"**
5. Otvorite generirani PDF klikom na **"Otvori PDF"**

---

## Značajke

### Podržani podaci iz XML računa

| Sekcija | Podaci |
|---------|--------|
| **Zaglavlje** | Broj računa, datum izdavanja, datum dospijeća, razdoblje |
| **Dobavljač** | Naziv, adresa, OIB, PDV ID, kontakt podaci |
| **Kupac** | Naziv, adresa, OIB, PDV ID, kontakt podaci |
| **Isporuka** | Adresa isporuke (ako postoji) |
| **Stavke** | Šifra, naziv, količina, jedinična cijena, rabat, PDV, ukupno |
| **Ukupno** | Osnovica, PDV, ukupan iznos za plaćanje |
| **Plaćanje** | IBAN, banka, način plaćanja |
| **Napomene** | Sve napomene iz računa |

### Prednosti

- ✅ **Bez instalacije** - standalone .exe datoteka
- ✅ **Hrvatski znakovi** - potpuna podrška za č, ć, š, ž, đ
- ✅ **Pregled prije konverzije** - vidite ključne podatke računa
- ✅ **Profesionalan izgled** - čist i pregledan PDF format
- ✅ **UBL 2.1 kompatibilnost** - podržava hrvatski eRačun standard

---

## Podržani formati

Aplikacija podržava **UBL 2.1 XML** fakture prema hrvatskom standardu za eRačun, uključujući:

- Fiskalizirane račune
- B2B račune
- Račune s više stavki i različitim stopama PDV-a

---

## Česta pitanja

### Windows prikazuje sigurnosno upozorenje?

Budući da aplikacija nije digitalno potpisana, Windows može prikazati upozorenje pri prvom pokretanju. Kliknite **"Više informacija"** → **"Svejedno pokreni"**.

### PDF se ne generira ispravno?

Provjerite je li XML datoteka valjana UBL 2.1 faktura. Aplikacija ne podržava druge XML formate.

### Gdje se sprema PDF?

Po defaultu u isti direktorij kao XML datoteka, s istim imenom ali .pdf ekstenzijom. Možete promijeniti lokaciju prije konverzije.

---

## Tehnički podaci

- **Format:** Windows executable (.exe)
- **Veličina:** ~30 MB (uključuje sve potrebne biblioteke)
- **Zahtjevi:** Windows 10/11 (64-bit)
- **Jezik sučelja:** Hrvatski

---

## Autor

**Goran Zajec**  
📧 Email: [da@svejedobro.hr](mailto:da@svejedobro.hr)

Za pitanja, prijedloge ili prijavu grešaka slobodno se obratite.

---

## Licenca

Aplikacija je besplatna za osobnu i poslovnu upotrebu.

---

*Verzija 1.0 | Siječanj 2026*
