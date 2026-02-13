GIT HUB:
Aggiunta File:
git pull

Se faccio modifiche:
git add .
git commit -m "Descrizione"
git push

# 🏥 Sistema di Prenotazione Ospedaliera

Progetto universitario che simula un **sistema di prenotazione delle visite ospedaliere**, simile al funzionamento di un CUD, sviluppato interamente da zero.

Il sistema permette la gestione delle prenotazioni settimanali delle visite mediche, organizzate per **giorni e fasce orarie**, con diversi **ruoli utente** e **reparti ospedalieri**.

---

## 🎯 Obiettivi del progetto

Simulare un sistema reale di prenotazione ospedaliera
Gestire ruoli con permessi differenti
Visualizzare disponibilità settimanali (lun–ven, 9:00–17:00)
Applicare un’architettura client-server moderna

---

## 🧑‍⚕️ Reparti disponibili

Cardiologia  
Pediatria  
Ortopedia  
Oculistica  
Medicina Generale  

---

## 👥 Ruoli e permessi

| Ruolo        | Permessi |
|--------------|----------|
| **Utente**   | CRUD prenotazioni |
| **Medico**   | Visualizzazione delle proprie visite |
| **Segreteria** | Visualizzazione completa delle prenotazioni |
| **Admin**    | Gestione completa del sistema |

---

## 📅 Organizzazione delle visite

Orari: **09:00 – 17:00**
Giorni: **Lunedì – Venerdì**
Prenotazioni organizzate in **slot orari**
Evidenziazione slot **liberi** e **occupati**

---

## 🛠️ Tecnologie utilizzate

### Backend
Node.js
Express
REST API

### Frontend
Angular
TypeScript
HTML / CSS

### Versionamento
Git
GitHub

---

## 📁 Struttura del progetto
