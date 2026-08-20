# Mail LT

Android el. pašto klientas be reklamų.

## Funkcijos
- Kelios IMAP/SMTP paskyros ir bendras Inbox
- SSL/TLS IMAP ir SMTP
- Laiškų sąrašas, peržiūra ir paieška
- Naujas laiškas ir Reply
- Failų prisegimas siunčiant
- Tekstinis parašas kiekvienai paskyrai
- Gmail, savi domenai ir kiti standartiniai IMAP/SMTP serveriai
- Slaptažodžiai saugomi tik įrenginyje programėlės `SharedPreferences`

## Prisijungimas
Gmail paskyrai naudok Google App Password (reikia 2FA), nes paprastas paskyros slaptažodis IMAP/SMTP paprastai nepriimamas. Microsoft 365 / Outlook paskyroms, kuriose uždraustas Basic Auth, reikalingas OAuth2 — tam būtina atskira Microsoft programėlės registracija.

## APK
GitHub Actions workflow `Build MailLT APK` sukuria `MailLT-debug-apk` artefaktą.
