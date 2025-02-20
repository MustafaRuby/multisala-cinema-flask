# 🎬 Cinema Multisala - Sistema di Prenotazione

![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

> Un moderno sistema di prenotazione posti per multisala cinematografica sviluppato con Flask 🚀

## 📝 Descrizione

Gestisci facilmente le prenotazioni dei posti nelle tue sale cinematografiche con un'interfaccia intuitiva e un backend robusto. 

Il sistema supporta 8 sale da 56 posti ciascuna, con gestione di utenti normali e amministratori, offrendo un'esperienza personalizzata per ogni ruolo.

## ✨ Funzionalità Principali

### 👥 Per gli Utenti
- 📝 Registrazione semplice e veloce
- 🔐 Sistema di login sicuro
- 🎯 Selezione della sala desiderata
- 🎬 Visualizzazione interattiva dei posti per ogni sala
- 🎟️ Prenotazione con un click
- ❌ Gestione delle proprie prenotazioni

### 👑 Per gli Amministratori
- 🔑 Pannello admin dedicato
- 👥 Gestione degli amministratori
- 🎫 Controllo totale sulle prenotazioni di tutte le sale
- 🔄 Override delle prenotazioni esistenti

## 🏗️ Struttura delle Sale

- **🎭 Numero Sale**: 8 sale indipendenti
- **💺 Posti per Sala**: 56 posti (7 file (da A a G) × 8 colonne (da 1 a 8))
- **🎯 Layout**: Layout ottimizzato con corridoio centrale
- **🔍 Identificazione**: Posti identificati da lettera (fila) e numero (colonna)

## 🛠️ Tecnologie Utilizzate

- **🐍 Backend**: Python + Flask
- **💾 Database**: SQLite3
- **🎨 Frontend**: HTML5 + CSS3
- **🔒 Sicurezza**: Flask-Session + Secrets

## 🚀 Come Iniziare

1. **Clona il repository**
```bash
git clone https://github.com/MustafaRuby/multisala-cinema-flask.git
cd multisala-cinema-flask
```

2. **Installa le dipendenze**
```bash
pip install -r requirements.txt
```

3. **Avvia l'applicazione**
```bash
python app.py
```

4. **Accedi all'applicazione**
Apri il browser e vai su `http://localhost:3000`

## 📂 Struttura del Progetto

```
multisala-oz/
│
├── app.py           # Entry point dell'applicazione
├── db_manager.py    # Gestione database
├── db.sql          # Schema database
│
├── templates/       # Template HTML
│   ├── adminLog.html
│   ├── adminReg.html
│   ├── arena.html     # Selezione sala
│   ├── error.html
│   ├── login.html
│   ├── register.html
│   └── sala.html      # Visualizzazione posti
│
└── README.md
```

## 🔐 Sicurezza

- ✅ Sessioni utente protette
- ✅ Validazione input
- ✅ Route admin protette
- ✅ Token di sicurezza

## 🚧 Limitazioni Note

- La sala ha un layout predefinito
- Non supporta prenotazioni simultanee
- Le password sono memorizzate in chiaro (da migliorare in produzione)

## 🤝 Come Contribuire

1. Fai un fork del progetto
2. Crea un branch per la tua feature (`git checkout -b feature/AmazingFeature`)
3. Committa i tuoi cambiamenti (`git commit -m 'Add some AmazingFeature'`)
4. Pusha sul branch (`git push origin feature/AmazingFeature`)
5. Apri una Pull Request

## 📄 Licenza

Distribuito sotto licenza MIT. Vedi `LICENSE` per maggiori informazioni.

## 📧 Contatti

Mostafa Abou Elkhir - [abouelkhirmostaffa@email.com](mailto:abouelkhirmostaffa@email.com)

Link Progetto: [https://github.com/MustafaRuby/multisala-cinema-flask.git](https://github.com/MustafaRuby/multisala-cinema-flask.git)

---
⭐️ Se ti piace questo progetto, metti una stella! ⭐️