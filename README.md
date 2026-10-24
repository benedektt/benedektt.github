# Tahi-Tóth Benedek – személyes szakmai weboldal

Magyar és angol, statikus szakmai bemutatkozó oldal. Fókusz: ingatlanstratégia, piaci lehetőségek, fejlesztési koncepció és pozicionálás, a szakmai tapasztalat és a tanulmányok bemutatásával.

Tervezett cím közzététel után: https://benedektt.github.io/

## Megtekintés a saját gépeden

1. Csomagold ki a ZIP-fájlt.
2. Nyisd meg a kicsomagolt `index.html` fájlt a böngésződben.
3. Az EN hivatkozás az angol oldalra vezet. A fájlok és a mappák maradjanak együtt.

Az oldal használatához nincs szükség telepítésre vagy fordításra.

## Közzététel GitHub Pagesen

1. A `benedektt` fiókban hozz létre egy új, **Public** repositoryt pontosan `benedektt.github.io` néven. Az Add README lehet bekapcsolva.
2. A repositoryban válaszd az **Add file → Upload files** lehetőséget.
3. A ZIP **kicsomagolt tartalmát** töltsd fel a repository gyökerébe. Az `index.html` közvetlenül a gyökérben legyen; az `en` és `assets` mappák szerkezete maradjon meg. A ZIP-et és az azt körülvevő mappát nem kell feltölteni.
4. Mentsd a fájlokat a **Commit changes** gombbal a `main` ágra.
5. Nyisd meg a **Settings → Pages** oldalt.
6. A **Build and deployment → Source** mezőben válaszd a **Deploy from a branch** beállítást.
7. A Branch legyen **main**, a mappa **/(root)**; kattints a **Save** gombra.
8. A közzététel eltarthat néhány percig, a GitHub dokumentációja szerint akár 10 percig. A Pages beállításainál megjelenő **Visit site** hivatkozáson ellenőrizhető az éles oldal.

Ha már létezik `benedektt.github.io` repository vagy rajta korábbi weboldal, előbb tekintsd át a tartalmát. Ez a csomag teljes kezdőoldalt és kapcsolódó fájlokat tartalmaz.

Hivatalos útmutató: https://docs.github.com/en/pages/quickstart

## Tartalom és módosítás

| Fájl | Szerep |
| --- | --- |
| `index.html` | Magyar bemutatkozó oldal és a hozzá tartozó metaadatok. |
| `en/index.html` | Angol bemutatkozó oldal és a hozzá tartozó metaadatok. |
| `styles.css` | Közös megjelenés és mobilnézet. |
| `assets/favicon.svg` | Böngészőikon. |
| `assets/social-card.png` | Megosztási kép, 1200 × 630 px. |
| `robots.txt` | Feltérképezési beállítás és sitemap-hivatkozás. |
| `sitemap.xml` | A két nyelvi oldal címe és kapcsolata. |
| `404.html` | Nem található oldal. |
| `.nojekyll` | Egyszerű statikus kiszolgálás. |

A képzési megnevezések és szakmai szerepkörök a tulajdonos által megadott LinkedIn-szövegre épülnek. A két 2026-ban indult programnál a kezdés szerepel, teljesítési állítás nélkül. A bemutatkozás tartós szakmai fókuszt ír le; nem használ várható végzést vagy automatikusan változó munkaviszony-hosszt.

A két nyelvi oldal külön szerkeszthető; tartalmi változtatáskor mindkettőt érdemes frissíteni. Jelentős módosításkor a sitemap `lastmod` dátuma az adott oldal tényleges frissítésének dátumára cserélhető.

A kész oldal HTML- és CSS-fájlokból áll, saját tárhelyen tárolt képpel és külső betűkészlet-letöltés nélkül. Nem tartalmaz analitikát, követőkódot vagy kapcsolatfelvételi űrlapot.

## SEO-beállítások

- Külön magyar és angol oldalcím és leírás.
- Nyelvenként saját canonical URL, kölcsönös `hreflang` hivatkozásokkal.
- ProfilePage, Person és WebSite strukturált adatok.
- A személyhez tartozó szakmai profilok `sameAs` hivatkozásai.
- Open Graph- és megosztási metaadatok.
- Sitemap és indexelhető, valódi HTML-tartalom.

A közzététel után a Search Console-ban URL-előtag típusú tulajdonként felvehető a `https://benedektt.github.io/` cím. A Google által adott ellenőrző HTML-fájlt külön kell feltölteni; ez a csomag nem tartalmaz fiktív ellenőrző azonosítót.

A technikai előkészítés nem garantál indexelést vagy keresőhelyezést. Saját domain későbbi használatakor az oldalcímeket a két HTML-fájl metaadataiban és strukturált adataiban, továbbá a robots.txt és sitemap.xml fájlokban is az új domainhez kell igazítani.

Elkészítve: 2026. október 24.

Frissítés: következetes külső nézőpont magyarul és angolul; meleg törtfehér, kő-, homok- és szénszürke paletta; a meglévő oldalszerkezet és az építészeti illusztráció megtartásával.
