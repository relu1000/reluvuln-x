# 🇷🇴 ReluVuln-X

**Scanner CVE open-source cu fingerprinting, ML ranking și pluginuri extensibile.**  
Creat cu mândrie românească, umor tehnic și ambiție globală.


## 🔧 Funcționalități

- 🧬 Fingerprinting automat al țintei (IP/URL)
- 🔥 CVE ranking cu ML și scoruri colorate
- 🔌 Pluginuri dinamice activabile/dezactivabile
- 📊 Dashboard web cu interfață elegantă
- 📤 Integrare cu HackerOne pentru raportare automată
- 🧠 API REST complet (FastAPI)

- ## 📦 Instalare 

```bash
git clone git@github.com:relu1000/reluvuln-x.git
cd reluvuln-x
source reluvuln-env/bin/activate
python3 -m venv reluvuln-env
source reluvuln-env/bin/activate
pip install -r requirements.txt


---

### 4. ▶️ Pornire

```markdown
## ▶️ Pornire

### API:
```bash
uvicorn api:app --reload
uvicorn dashboard:app --reload --port 8001

---

### 5. 📥 Endpointuri API

```markdown
## 📥 Endpointuri API

- `GET /scan?target=` – Scanează ținta
- `GET /plugins` – Listează pluginuri
- `POST /report` – Trimite vulnerabilitate în HackerOne
## 🧠 Stil și identitate

ReluVuln-X nu e doar un scanner.  
E un manifest tehnic cu suflet românesc, culoare în CLI și eleganță în dashboard.

> „Nu doar detectăm vulnerabilități. Le înțelegem, le clasificăm și le raportăm cu stil.”
## 🤝 Contribuții

Pull request-uri, idei și pluginuri noi sunt binevenite.  
Respectă stilul modular și extensibil. Fii creativ, dar clar.
## 📜 Licență

MIT – folosește, modifică, distribuie.  
Dar nu uita să menționezi ReluVuln-X dacă te ajută.


