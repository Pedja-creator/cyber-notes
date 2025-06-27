# Linux – SSH Hardening

## 📌 Zašto zaštititi SSH?

SSH koristiš za udaljeni pristup serverima — ako nije zaštićen, napadači mogu upasti.

## ✅ Mere zaštite:

1. **Promeni podrazumevani port (22)**  
   `/etc/ssh/sshd_config` → `Port 2222`

2. **Onemogući root login**  
   `PermitRootLogin no`

3. **Dozvoli samo određene korisnike**  
   `AllowUsers tvoj_korisnik`

4. **Koristi SSH ključeve umesto lozinki**  
   `ssh-keygen` za generisanje ključeva

5. **Fail2ban** – automatski blokira IP adrese koje više puta pogreše lozinku

## 🧪 Testiranje:
```bash
sudo systemctl restart ssh
ssh -p 2222 korisnik@ip-adresa
