# CIA Triad – Osnova sajber bezbednosti

## 🧠 Šta znači CIA?

1. **Confidentiality (Poverljivost)**
   - Ograničava pristup informacijama
   - Primer: lozinke, enkripcija, autentifikacija

2. **Integrity (Integritet)**
   - Informacije su tačne i nisu neovlašćeno menjane
   - Primer: hash funkcije, digitalni potpisi

3. **Availability (Dostupnost)**
   - Sistem i podaci dostupni ovlašćenim korisnicima kada su im potrebni
   - Primer: backup sistemi, DDoS zaštita

## 🛠 Realni primer:

- Online banka:
  - Korisnik koristi 2FA → **Confidentiality**
  - Transakcija se verifikuje hash-om → **Integrity**
  - Server uvek aktivan → **Availability**
