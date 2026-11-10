# Oleoducto Beta · simulador 3D + constructor de ductos

Sitio estático (sin build). Se publica tal cual en Vercel, Cloudflare Pages o cualquier hosting.

- `index.html` — simulador Oleoducto Beta (vista 3D, sala de control, desafío, SCADA).
- `constructor.html` — constructor de ductos a medida: trazado sobre mapa, altimetría real
  (Copernicus GLO-90 vía Open-Meteo), caño (NPS, schedule, grado API 5L, clase ANSI, MAOP),
  estaciones, bombas, boosters, medición, trampas de pig, válvulas, destino (refinería, parque de
  tanques o puerto) y revisión con el motor hidráulico.
- `index.html?ducto=ID` — simula un ducto guardado en el navegador.

Los ductos se guardan en el navegador (localStorage) y se exportan/importan como `.json`.
Simulación de entrenamiento con valores estimados: no reemplaza un estudio hidráulico.
