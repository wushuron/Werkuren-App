# 🕐 Uren Tracker CAO

Werkuren-tracker met CAO Kleinmetaal berekeningen. Werkt offline en installeerbaar als app op je telefoon.

## Functies

✅ Uren per opdracht bijhouden  
✅ Automatische CAO Kleinmetaal berekeningen  
✅ Werkt offline (Service Worker)  
✅ Installeerbaar op Android/iOS als app  
✅ LocalStorage voor data-persistentie  

## Hoe naar GitHub en Netlify

### Stap 1: Repository op GitHub aanmaken

1. Ga naar https://github.com
2. Log in of maak een account aan
3. Klik rechtsboven op **"New repository"**
4. Naam: `uren-tracker` (of wat jij wilt)
5. Beschrijving: "Werkuren tracker met CAO berekeningen"
6. Klik **"Create repository"**

### Stap 2: Bestanden uploaden

Op je GitHub repository pagina:
1. Klik **"Add file"** → **"Upload files"**
2. Sleep alle 3 bestanden hierheen:
   - `index.html`
   - `manifest.json`
   - `sw.js`
3. Klik **"Commit changes"**

### Stap 3: Netlify connecteren

1. Ga naar https://netlify.com
2. Klik **"New site from Git"**
3. Kies **GitHub**
4. Selecteer je `uren-tracker` repository
5. Klik **"Deploy"**

**Done!** Netlify deployt je app automatisch.

## Op je telefoon gebruiken

### Android:
1. Open je app-link in Chrome
2. Tik het menu (3 puntjes)
3. Kies **"Install app"** of **"Add to Home Screen"**

### iPhone:
1. Open in Safari
2. Tik het deelknop (⬆️)
3. Kies **"Add to Home Screen"**

## Bestanden

| Bestand | Functie |
|---------|---------|
| `index.html` | Je app (HTML, CSS, JavaScript) |
| `manifest.json` | PWA instellingen (installatie) |
| `sw.js` | Service Worker (offline support) |

## Data

Je data wordt opgeslagen in **localStorage** op je telefoon. Niet gedeeld met servers.

## Vragen?

Bewerk `index.html` direct als je iets wilt veranderen, push naar GitHub, en Netlify update automatisch.

---

**Genoten van het maken van deze app? Veel sterkte met je CNC werk!** 🚀
