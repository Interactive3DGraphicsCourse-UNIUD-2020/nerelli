# Creazione sito
Ho creato un sito usando HTML e Bootstrap e <a href="https://getbootstrap.com/docs/4.0/examples/album/">seguendo l'esempio "album"</a> di Bootstrap.
# Scelta del modello
Ho scelto di usare <a href="https://sketchfab.com/3d-models/free-1995-fiat-punto-gt-48db6facb4b64e99b60f36b8c01185e1">questo</a> modello. L'ho scaricato e lo implemento usando un loader gltf.
# Complicazioni modello
Le texture del modello sono eccessivamente pesanti. Le ho compresse molto usando Photoshop riducendole in scala per raggiungere 12MB di texture. Il modello è inoltre molto complesso, ha 9 geometrie differenti, alle quali sono applicate più d'una texture ognuna.
# Scelta nuovo modello
Ho deciso di cambiare modello ad uno più semplice, ed ho optato per <a href="https://sketchfab.com/3d-models/cat-statue-4f32fb314d5246babd75994e5894796e">questo</a>.
Ho usato lo shader BRDF spiegato a lezione che varia la mipmap al variare della roughness per aggiungere due materiali metallici (oro e rame) con riflessi PBR usando i corrispettivi cspec.
# Aggiunta ulteriori envMap
Ho aggiunto delle envMap scattate da me sfruttando l'applicazione Google Street View che permette di generare latlong maps dal proprio telefono e altre prese da <a href="https://hdrmaps.com/">hdrmaps</a>.
# Generazione irradianceMaps
Ho generato le irradianceMaps usando <a href="https://github.com/dariomanesku/cmftStudio">cmftStudio</a>: un software Open Source che genera delle irradianceMaps.