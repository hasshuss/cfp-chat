# CFP Chat — Assistant commercial clôtures aluminium

Interface web de chat connectée à l'agent IA CFP Distribution.

## Stack
- **Astro** (SSG, zéro JS côté serveur)
- Vanilla JS client-side
- CSS mobile-first

## Lancer en local
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

## API
Appels vers `https://back.poktools.com/api/agent/chat`  
`POST { sessionId, message }` → `{ reply, sessionId }`

La session est persistée dans le `localStorage` du navigateur.
