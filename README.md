# 📅 Aplicatie Android - Rezervare Evenimente (Event Booker)

Această aplicație Android oferă o soluție simplă și eficientă pentru rezervarea de servicii foto-video pentru evenimente precum nunți, botezuri sau majorate. Este o aplicație complet locală, creată pentru proiect academic / portofoliu.

---

## 🚀 Funcționalități

- ✅ **Autentificare și înregistrare cont**
  - Salvare date în `SharedPreferences`
  - Verificare validitate câmpuri

- ✅ **Rezervare eveniment**
  - Selectare tip eveniment (nuntă, botez, majorat)
  - Introducere număr invitați
  - Alegere servicii (foto+video, doar foto, doar video)
  - Opțiune album personalizat (dacă este cazul)
  - Selectare dată (cu verificare pentru indisponibilitate)
  - Calcul cost total + reduceri automate
  - Salvare rezervare în `SharedPreferences`

- ✅ **Vizualizare cont și rezervări**
  - Acces la datele contului doar după autentificare cu parolă
  - Vizualizare rezervări anterioare

- ✅ **Navigare facilă**
  - Buton de tip „hamburger” pentru acces rapid la funcții

---

## ⚙️ Tehnologii folosite

- 💻 **Android Studio**
- 📱 **Limbaj:** Java
- 📦 **Stocare locală:** `SharedPreferences`
- 🗓️ **UI Components:** Spinner, EditText, CheckBox, DatePicker, ImageButton

---

## ⚠️ Limitări și îmbunătățiri posibile

- 🔐 **Securitate:** Datele sunt salvate local, fără criptare sau protecție avansată.
- 🎨 **Design UI:** Interfața poate fi îmbunătățită vizual pentru o experiență mai modernă și profesională.

---

## ▶️ Cum rulezi aplicația

1. Clonează repository-ul:
   ```bash
   git clone https://github.com/USERNAME/rezervare-evenimente-android.git
