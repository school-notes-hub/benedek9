# Benedek tanulóoldala

A nyilvános tanulóoldal helye és hibabejelentő felülete. A tanulóoldal címe: **https://school-notes-hub.github.io/benedek9/**.

[Hibát találtál vagy kérdésed van?](https://github.com/school-notes-hub/benedek9/issues/new?template=bejelentes.yml) Tartalmi, megjelenítési, hozzáférhetőségi és szerzői jogi kérdést is jelezhetsz. A bejelentés nyilvános, és GitHub-bejelentkezést igényel: személyes adatot, füzetfotót vagy nem nyilvános tanári anyagot ne tölts fel.

A nyers források és a családi munkafeljegyzések a különálló privát tárhelyen maradnak. A jegyzetek hibajelzéseit ellenőrizzük; ez az űrlap nem jelent automatikus javítást vagy garantált válaszidőt.

## Kiadás

A tananyag külön privát Git-repóban marad. Ide kizárólag ellenőrzött, nyilvános HTML, képek, kereső és témaköri PDF-ek kerülnek, Release-csomagként; nagy generált fájlokat nem tárolunk a Git-előzményben.

A `Publish reviewed study site` workflow kézi indításakor a kész Release címkéjét kell megadni. A munkafolyamat rögzített Git-verzióból veszi a közös ellenőrző programot, ellenőrzi a csomag hash-eit, a fájllistát és a céloldalt, majd GitHub Pages-artifactot telepít. A ténylegesen kiadott verzió a weboldal `release.json` fájljában ellenőrizhető. Korábbi, ellenőrzött Release megadásával vissza lehet állni rá; a privát tananyagot ez nem írja át.
