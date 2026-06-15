# HeritageTraveler – Hotel-Kooperationen

Interaktive Liste zur Verwaltung von Hotel-Kooperationsanfragen.

**Stack:** Vanilla JS + Tailwind (CDN) + Supabase (Auth + Row-Level Security) + Cloudflare Turnstile.

- Login per E-Mail-Einmalcode (kein Passwort nötig).
- Die Hoteldaten liegen in Supabase und sind durch RLS geschützt — nur der eingeloggte Eigentümer sieht seine Daten.
- Dieses Repo enthält nur das Frontend (öffentliche Keys), keine Hotel-Daten.
