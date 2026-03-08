# Saiph CRM 4.0

## Deploy su Vercel (2 minuti)

1. Vai su **vercel.com** → Sign up / Login con GitHub
2. Clicca **"Add New Project"**
3. Trascina questa cartella `saiph-deploy` oppure clicca **"Import"** se l'hai caricata su GitHub
4. Lascia tutto di default → clicca **"Deploy"**
5. In ~60 secondi hai il link tipo `saiph-crm.vercel.app`

---

## In alternativa: gira in locale

Assicurati di avere Node.js installato (node -v per verificare), poi:

```bash
npm install
npm run dev
```

Si apre su http://localhost:5173

---

## Struttura

```
saiph-deploy/
├── index.html
├── package.json
├── vite.config.js
├── vercel.json
└── src/
    ├── main.jsx
    └── App.jsx   ← tutto il CRM è qui
```
