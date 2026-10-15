# TAQWASTEPS — Web App

**Walk With Faith · Each Step Toward Allah**

🌐 **Live app:** https://webapp.taqwasteps.in
🏠 **Main website:** https://www.taqwasteps.in

TAQWASTEPS is a free Islamic habit tracker that helps you stay consistent with your Salah, Dhikr, Quran and Tahajjud — one honest step at a time.

---

## ✨ Features

- 🕌 **Salah tracker** — log each of the 5 daily prayers (with Jamaat, alone, Qaza, or not yet)
- ⏰ **Prayer times** — auto-detected by location or city, with Hanafi / Shafi Asr options
- 🕋 **Masjid times** — enter your local masjid's Azan & Iqamah times and get reminders on that schedule
- 🔔 **Salah reminders** — notifications 5–20 minutes before Azan, per prayer
- 📿 **Dhikr counter** — tasbih counter with streaks and custom dhikr
- 📖 **Quran goal** — set a daily page goal (out of 604 pages) and build a reading streak
- 🌅 **Morning & night routines** — Ayat al-Kursi, the 3 Quls, Al-Mulk, last 2 ayahs of Al-Baqarah
- 🕌 **Friday specials** — Surah Al-Kahf reminder, and As-Sajdah & Al-Insan for Friday Fajr
- 🌙 **Tahajjud log** — daily check-in and history
- 📅 **Salah history from age 7** — mark past prayers, as the Prophet ﷺ commanded
- 💭 **Prayer mood** — reflect on how your heart felt in each Salah
- 🔐 **Accounts** — email or Google sign-in, with full account deletion

---

## 📁 Project Structure

```
├── index.html      # The web app
├── auth.js         # Sign-in / sign-up logic (Firebase Auth)
├── sw.js           # Service worker — notifications & offline support
├── manifest.json   # PWA settings (install to home screen)
├── logo.png        # App logo
└── CNAME           # Custom domain: webapp.taqwasteps.in
```

---

## 🚀 Deployment

This app is hosted on **GitHub Pages** with the custom domain `webapp.taqwasteps.in`.

- Every push to the `main` branch is deployed automatically.
- DNS: `CNAME` record `webapp` → `taqwasteps-dev.github.io`
- HTTPS is enforced in **Settings → Pages**.

> When changing `sw.js`, bump the cache version so users receive the update.

---

## 📱 Install as an App

- **Android (Chrome):** open the app → menu ⋮ → **Add to Home screen**
- **iPhone (Safari):** open the app → Share → **Add to Home Screen**
- **Android APK:** available on [taqwasteps.in](https://www.taqwasteps.in)

---

## 🔒 Privacy & Terms

- [Privacy Policy](https://www.taqwasteps.in/privacy.html)
- [Terms of Use](https://www.taqwasteps.in/terms.html)

---

## 🤲 Note

> *"Only mark what you have truly prayed. Every honest step is recorded by Allah."*

Made with 🤍 by the TAQWASTEPS team.
