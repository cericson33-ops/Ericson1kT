# Ericson-1000

Träningskonceptet för Ericson Fotboll & Konsults spelare i åldrarna 6–10 år — byggt som en React PWA.

## Testa lokalt

```bash
npm install
npm run dev
```

Öppna sedan länken som visas i terminalen (oftast http://localhost:5173).

## Lägg upp på GitHub

1. Skapa ett nytt, tomt repo på github.com (t.ex. `ericson-1000`) — **kryssa inte i** "Add a README" eftersom den redan finns här.
2. Kör i mappen:

```bash
git init
git add .
git commit -m "Första versionen av Ericson-1000"
git branch -M main
git remote add origin https://github.com/DITT-ANVANDARNAMN/ericson-1000.git
git push -u origin main
```

## Deploya på Vercel

1. Gå till [vercel.com](https://vercel.com) och logga in (kan göras direkt med ditt GitHub-konto).
2. Klicka **Add New → Project**.
3. Välj GitHub-repot `ericson-1000` — Vercel känner automatiskt igen att det är ett Vite-projekt och fyller i rätt inställningar (build command `npm run build`, output-mapp `dist`).
4. Klicka **Deploy**. Efter någon minut får du en live-länk (t.ex. `ericson-1000.vercel.app`).

Varje gång du sedan pushar ändringar till `main` på GitHub byggs och publiceras appen om automatiskt.

## Egen domän (valfritt)

Under projektets inställningar på Vercel → **Domains** kan du koppla en egen domän, t.ex. `app.ericsonfotboll.se`, om du har en domän att peka dit.
