# Produkttext AI

> Researchad affärsmöjlighet från Nexar Academy. Den fullständiga marknadsresearchen
> ligger i skillen **affärsplan** — kör `/affarsplan` för att läsa den.

## Vad vi bygger
Generera SEO-optimerade produktbeskrivningar på svenska – på sekunder, inte dagar.. Produkttext AI är en självbetjänings-SaaS som hjälper svenska e-handlare att automatiskt skapa SEO-optimerade produktbeskrivningar i stor skala. Ladda upp din produktkatalog, välj ton och stil, och få färdiga texter direkt i ditt e-handelssystem – utan att behöva anlita en byrå. Byggt från grunden för den svenska marknaden med djupa integrationer mot Shopify, WooCommerce och Centra.

## Stack (ändra inte utan att fråga)
- Next.js + Tailwind (frontend)
- Supabase (databas + auth)
- Vercel (deploy)
- Claude API där appen behöver AI

## Kommandon
- `npm run dev` — kör lokalt
- `npm run build` — bygg + felkoll (kör efter varje ändring)
- `npm run lint` — lint

## Så jobbar vi (viktigt)
- Bygg i **små steg** — kör `npm run build` efter varje ändring och visa resultatet.
- **Fråga vid större vägval** (tech, datamodell, pris) i stället för att gissa.
- Lägg **aldrig** hemligheter/nycklar i koden — bara i `.env.local`.
- Håll det **enkelt** — en MVP som bevisar värdet, inte en färdig produkt.

## Projektminne (DU ansvarar för det — användaren ska aldrig behöva be)
- Efter varje avklarat steg: uppdatera `docs/FRAMSTEG.md` (byggt + nästa steg).
- Vid varje vägval: logga en rad i `docs/BESLUT.md` (datum + 1 mening om varför).
- Bocka av i `docs/UPPGIFTER.md` allt eftersom.
- **Vid sessionsstart: läs `docs/FRAMSTEG.md` FÖRST** och sammanfatta "var vi var".
- Använd din inbyggda auto-memory för build-kommandon och buggfixar.

## Kom igång
**Kör `/start` först** — den frågar om din nivå och guidar dig hela vägen: förklarar varje verktyg (Supabase, Vercel m.m.), hjälper dig installera, och bygger appen steg för steg. Är du redan van kan du i stället be mig läsa `/affarsplan` och föreslå en MVP-plan direkt.

<!-- nexar:opportunity slug=produkttext-ai -->
