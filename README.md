# TransferPy — dokumentacija

**TransferPy** je radni alat za pripremu i proveru podataka, obračuna i obrazloženja u studijama transfernih cena. Povezuje klijente, studije, transakcije, izvore, stručni pregled i radni izvoz.

Početna dokumentacija prilagođena je GitHub Pages-u i koristi statični HTML/CSS u folderu `docs`, slično ARPy dokumentaciji. Trenutni status aplikacije: **razvojni kandidat 0.1.0**.

## Sadržaj

- [Početna stranica](docs/index.html): namena, funkcionalnosti, tok rada, desktop i kontakt.
- CUP i višestavčni CUP, TNMM sa jednogodišnjim i višegodišnjim podacima.
- Finansije, uporediva društva, analize kamata i Excel radni papiri.
- Narativ, izvori, prilozi i radni Word/PDF/ZIP izvoz.
- Korisničke uloge, stručne potvrde i desktop aktivacija.

Ekspert potvrđuje konačan izbor metode, uporedivost i zaključak. Preporuka metode je opciona i koristi privremena pravila. Izvoz radnog dokumenta ne potvrđuje niti zaključava studiju.

## GitHub Pages

U podešavanjima ovog repozitorijuma izabrati:

1. **Settings → Pages**.
2. Source: **Deploy from a branch**.
3. Branch: **main**, folder: **/docs**.
4. Kliknuti **Save** i sačekati završetak objave.

Planirana adresa posle uključivanja Pages-a:

https://keymaster75.github.io/TransferPy-Documentation/

Fajlovi su pripremljeni; ovo uputstvo ne znači da je Pages već uključen. Za lokalni pregled otvoriti `docs/index.html` u browseru. Za izmene teksta koristiti PHPStorm ili drugi editor; nije potreban frontend build.

## Održavanje

Glavni tekst je u `docs/index.html`, stilovi u `docs/css/style.css`. Dodavati javne primere bez podataka stvarnih klijenata. README i korisnička dokumentacija treba da odgovaraju stvarno dostupnim funkcijama.

Kasnije su planirani detaljnija uputstva, istorija verzija i `latest.json` za proveru ažuriranja. Update metadata objaviti tek uz stvarni installer, tačan link, verziju i SHA256 kontrolni zbir; provera ažuriranja još nije deo aplikacije.

Repozitorijum je namenjen javnoj dokumentaciji. Privatni ključevi, izdate licence, lokalne konfiguracije, baze i stvarne studije ne pripadaju ovom repozitorijumu.

## Kontakt

Aleksandar Aleksić — [aleksica@gmail.com](mailto:aleksica@gmail.com)
