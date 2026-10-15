# TAQWASTEPS Web App

Walk with faith, one step at a time.

Live app: https://webapp.taqwasteps.in
Main website: https://www.taqwasteps.in

TAQWASTEPS is a free habit tracker for Muslims. It helps you stay consistent with Salah, Dhikr, Quran and Tahajjud, and keeps an honest record of your progress.

## Features

- **Salah tracker** – log each of the five daily prayers: with Jamaat, alone, late (Qaza), or not yet prayed
- **Prayer times** – based on your location or city, one time per prayer (Shafi'i Asr), with makrooh periods, optional prayers and Suhoor/Iftar times
- **Masjid times** – enter your local masjid's Azan and Iqamah times to see them next to each prayer
- **Dhikr counter** – a tasbih counter with streaks and your own custom dhikr
- **Quran goal** – set a daily page target and build a reading streak
- **Morning and night routines** – Ayat al-Kursi, the three Quls, Surah Al-Mulk and the last two ayahs of Al-Baqarah
- **Friday reminders** – Surah Al-Kahf, plus As-Sajdah and Al-Insan for Friday Fajr
- **Tahajjud log** – a daily check-in and a history of past nights
- **Salah history from age 7** – go back and mark past prayers
- **Prayer mood** – note how you felt during each Salah
- **Accounts** – sign in with email or Google, reset a forgotten password, and delete your account at any time

## Project structure

```
index.html      The web app (sign-in, accounts and data use Supabase)
logo.png        App logo
CNAME           Custom domain (webapp.taqwasteps.in)
```

## Deployment

The app is hosted on GitHub Pages at `webapp.taqwasteps.in`. Anything pushed to the `main` branch goes live automatically.

- DNS: a `CNAME` record for `webapp` pointing to `taqwasteps-dev.github.io`
- HTTPS is enforced under Settings → Pages

The password reset page lives on the main site at `https://taqwasteps.in/reset-password` (file `reset-password.html` in the main site repo).

The web app does not send notifications. Prayer reminders are in the Android app.

## Installing on your phone

- **Android (Chrome):** open the app, tap the menu, then tap *Add to Home screen*
- **iPhone (Safari):** open the app, tap Share, then tap *Add to Home Screen*
- **Android APK:** download it from [taqwasteps.in](https://www.taqwasteps.in)

## Privacy and terms

- [Privacy Policy](https://www.taqwasteps.in/privacy.html)
- [Terms of Use](https://www.taqwasteps.in/terms.html)

---

Only mark what you have truly prayed. Every honest step is seen by Allah.

Made by the TAQWASTEPS team.
