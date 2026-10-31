# Szecsői Háztáji – telepíthető app

Telepíthető (PWA) burok a Szecsői Háztáji Nyilvántartó Apps Script webapphoz:
ikon, manifest és service worker, az éles `/exec` telepítés beágyazva.

Megnyitás és telepítés: **https://szecsoi-haztaji-app.pages.dev/** (Cloudflare Pages, a `main` ág minden
feltöltés után automatikusan kikerül).

A régi cím (https://gabeszx.github.io/szecsoi-haztaji-app/) is működik, de onnan ne telepítsd: Androidon a Chrome
az azonos `gabeszx.github.io` webcímen lévő másik appal (Tanulmányi Követő) egynek látta, ezért kapott külön címet.

- **Windows / Chrome:** címsor jobb oldalán a telepítés ikon (vagy ⋮ → Átküldés, mentés és megosztás → Oldal telepítése alkalmazásként).
- **Android / Chrome:** ⋮ → Telepítés / Hozzáadás a kezdőképernyőhöz.

Az ikonok a privát kódrepóban nem érhetők el, ezért élnek itt. Ha az éles telepítés
azonosítója megváltozna, az `index.html`-ben lévő iframe linkjét kell átírni.
