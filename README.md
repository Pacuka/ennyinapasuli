# 🎒 Ennyi Nap a Suli

**[ennyinapasuli.hu](https://ennyinapasuli.hu/)**

Egy teljesen komolytalan weboldal, ami megpróbálja megmondani, hogy **hány nap van még hátra a suliból**.

Ennyi.

Illetve... van benne egy titkos `67` mód is. 💀

## ✨ Mit tud?

* 📅 Tanév-visszaszámláló
* 🎓 Következő érettségi visszaszámláló
* 📤 Oldal megosztása
* 📸 Sztori-kép generálása
* 🗿 Aura rendszer
* 👀 Saját látogatásszámláló `localStorage` segítségével
* 🔑 e-Kréta gyorslink
* ✨ Titkos Chaos Mode
* 67
* még több 67
* indokolatlan mennyiségű brainrot

## 💀 Chaos Mode

Ha begépeled:

```text
67
```

vagy megnyomod a jobb alsó sarokban lévő ✨ gombot, bekapcsol a **Chaos Mode**.

Ilyenkor az oldal többek között:

* random brainrot szövegeket dobál,
* e-Kréta panaszokat generál,
* sulis igazságokat mond,
* `67`-eket dobál a háttérben,
* és általánosságban elveszíti a maradék komolyságát.

## 🧑‍💻 Technológia

Az egész oldal egyetlen HTML fájlból áll:

* HTML
* CSS
* vanilla JavaScript
* `localStorage`
* Canvas API

Nincs backend, nincs adatbázis, nincs framework, nincs React, nincs 14 darab npm package egy visszaszámlálóhoz.

**Pont így jó.**

## 🤖 AI / vibe coding

Ez a projekt részben **AI segítségével, vibe coding módszerrel** készült.

Nem célja, hogy bemutassa a tökéletes szoftverarchitektúrát, és nem is akar úgy tenni, mintha az lenne.

A cél egyszerűen ennyi volt:

> „Legyen egy hülye oldal, ami megmondja, hány nap van még a suliból.”

A kód ezért helyenként valószínűleg nem úgy néz ki, ahogy egy production-grade projektben kellene.

**És ez teljesen szándékos.**

Ez egy fun projekt, nem egy NASA-misszió.

## 📁 Fájlstruktúra

```text
.
└── index.html
```

Igen.

**Egy fájl.**

## 🚀 Futtatás

Nem kell hozzá build rendszer.

Egyszerűen nyisd meg az `index.html` fájlt böngészőben, vagy tedd fel bármilyen statikus webtárhelyre.

Például:

* GitHub Pages
* Cloudflare Pages
* saját szerver
* bármilyen egyszerű static hosting

## ⚠️ Fontos

A visszaszámláló a JavaScriptben beállított dátumból számol:

```js
const schoolEnd = new Date("2027-06-19T00:00:00");
```

Az oldal jelenlegi számlálója **naptári napokat** számol, nem egy teljesen hivatalos, munkanap/iskolai szünet alapján kalkulált tanítási nap-számot.

## 📜 Licenc

Ez egy kis személyes/fun projekt.

Ha valamiért fel akarod használni vagy átalakítani, nyugodtan nézd meg a forrást, de ne várj tőlem enterprise supportot. xd

---

Made by **Pacuka** 🗿

**67**
