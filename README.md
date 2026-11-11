# Super Tris (PWA)
Sito statico: `index.html` + `sw.js` + manifest + icone. Nessuna build necessaria.
Backend: Supabase (progetto SuperTris, regione eu-central-1): tabelle rooms/room_seats/games/feedback con RLS e Edge Function `game` (valida ogni mossa lato server).
La chiave nel file è la chiave pubblica (anon): non contiene segreti.
Deploy: carica questi file in un repository GitHub e importalo su vercel.com (Framework: Other, nessun comando di build).
