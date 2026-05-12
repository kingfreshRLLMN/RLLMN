# RLLMN Website

Een strakke statische website voor het streamer merchandise merk RLLMN.

## Lokaal bekijken

Open `index.html` direct in je browser, of start een simpele server:

```powershell
python -m http.server 4173
```

Ga daarna naar `http://localhost:4173`.

## Deploy naar Vercel

1. Zet deze map in een GitHub repository.
2. Importeer de repository in Vercel.
3. Zet de Root Directory op de map waar `index.html` staat.
4. Framework preset: `Other`.
5. Build command leeg laten.
6. Output directory leeg laten of `.` gebruiken.

De site gebruikt alleen HTML, CSS, JavaScript en een lokale hero-afbeelding.
