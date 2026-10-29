# Mapa electoral · Santa Coloma de Gramenet · Generals 2023 per secció censal

Mapa interactiu d'accés restringit de les 88 seccions censals de Santa Coloma de Gramenet.
Les dades (`dades/*.bin`) estan xifrades amb AES-256-GCM i només es poden llegir des de la pàgina introduint la contrasenya.

- `index.html`: la pàgina (Leaflet 1.9.4).
- `dades/seccions_2023.bin`: seccions censals (ICGC/Idescat, 1-1-2024) amb resultats, renda (INE ADRH 2023) i índex de prioritat, xifrades.
- `dades/limits.bin`: límit municipal i límits de districte, xifrats.

Intervals calculats amb la distribució de les seccions de Santa Coloma (quintils i terciles locals).

Fonts: resultats electorals per secció; límits de seccions censals de l'ICGC i l'Idescat; renda de l'INE. Mapa base © ICGC (CC BY 4.0) i © OpenStreetMap.
