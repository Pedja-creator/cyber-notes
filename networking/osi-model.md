# OSI Model – 7 slojeva mrežnog modela

## 📌 Slojevi OSI modela (od donjeg ka gornjem)

1. **Physical** – kablovi, konektori, električni signali
2. **Data Link** – MAC adresa, switch, Ethernet
3. **Network** – IP adrese, router, ICMP
4. **Transport** – TCP/UDP portovi, pouzdanost
5. **Session** – uspostavljanje i prekid sesije
6. **Presentation** – enkripcija, konverzija podataka (npr. ASCII → JPEG)
7. **Application** – HTTP, FTP, DNS, email klijenti

## 🧠 Ključni pojmovi

- **TCP/IP** koristi 4 sloja, ali je zasnovan na OSI
- Važno za razumevanje kako podaci "putuju" kroz mrežu
- Mnogi napadi se dešavaju na Layer 3–7

## 🛠 Primer

- Kad surfuješ webom (npr. ideš na google.com):
  - DNS (Layer 7) prevodi adresu
  - TCP port 443 (Layer 4) šalje zahtev
  - IP (Layer 3) vodi do servera
  - Ethernet (Layer 2) nosi paket
  - Kabl (Layer 1) prenosi signal
