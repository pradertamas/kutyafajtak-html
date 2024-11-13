---
title: Kutyafajták GIT 1-es csapattag
author:
- Rostagni Csaba
---

A következő feladat elvégzéséhez csapatban kell dolgozni. Ön az 1-es számú csapattag.

A feladat során a mappaszerkezetet tartani kell, illetve a feladat adott pontja szerint aktualizálni kell!

Amennyiben a feladat máshogy nem kéri a stílusbeállításokat a stíluslapon kell elvégezni!

1. Hozzon létre egy repositoryt `kutyafajtak-html` néven, majd ossza meg a csapat többi tagjával.

1. Amint elkészült a repository és meg is osztotta csapattársaival, úgy klónozza le (`git clone`), majd közvetlen a gyökerében hozza létre az `index.html` fájlt.

    - A fájl egy HTML5 oldal alapszerkezetét tartalmazza.
    - Biztosítsa, hogy az oldal nyelve legyen magyar, továbbá a karakterkódolás legyen `utf-8`.
    - Az oldal címe legyen *"Kuytafajták"*. Ezt jelenítse meg az oldalon Címsor 1-es kiemeléssel. A böngészőfülön megjelenő cím is legyen ugyanez.
    - Hozzon létre egy felsorolást, ami egyetlen elemet tartalmazzon. Ez legyen egy link, ami a projektmappában később létrehozandó `german-shepherd.html` fájlra mutasson, a felirat legyen *"Németjuhász"*.

1. Ahhoz, hogy  a csapat többi tagja is elérje a fájlokat először adja hozzá staging area-hoz (`git add .`) készítsen pillanatképet `főoldal létrehozva` üzenettel (`git commit -m "főoldal létrehozva"`) a projekt jelenlegi állapotáról, majd érje el, hogy a távoli repository-ban is elérhető legyen (`git push`).

    - Előfordulhat, hogy a csapat egy másik tagja már frissítette a távoli kódtárat, így nem engedi a `push` műveletet. Ilyenkor célszerű biztosítani, hogy a helyi tárolóban minden módosítás legyen véglegesítve, majd frissíteni, hogy tartalmazza a távoli repository módosításait (`git pull`).

1. Hozza létre a korábban linkelt `german-shepherd.html` a projektmappában.

1. Az oldal nyelve legyen *magyar*, míg a karakterkódolás `utf-8`.
1. Az oldal címe legyen: *"Németjuhász"*
1. A `nyers-nemetjuhasz.txt` fájl tartalmát helyezze el egy `kutyaoldal` azonosítójú `main` elembe.
1. Az olda főcímére: *"Németjuhász"* alkalmazzon címsor 1-es kiemelést.
1. Az alcímeket *"A fajtáról*", *"Osztályozás"* és *"Képek"* lássa el Címsor 2-es kiemeléssel.
1. Az oldalon található további szöveget (a táblázat kivételével) bekezdésekként állítsa be.
1. A főcím alatt közvetlen illessze be az `img/dogs/german-shepherd` mappában található `katelyn-macmillan-bvMUtFN0mIE-unsplash.jpg` képet.
    - A képre alkalamzza a `minikep` osztálykijelölőt
    - Amennyiben a kép nem jelenne meg, úgy a *"Németjuhász"* helyettesítő szöeg jelenjen meg.
    - Amennyiben a felhasználó az egeret a kép fölé viszi, úgy a *"Németjuhász pórázon"* szöveg jelenjen meg.
1. Az "Osztályozás" részben alakítson ki egy 3 soros, 2 oszlopos táblázatot a mintának megfelelően.
1. Az `img/dogs/german-shepherd/` mappában található képeket szúrja be az oldal aljára egy `kepek` osztályú keretbe: 
    - `anna-dudkova-Ce2FZDbx2T0-unsplash.jpg`
    - `jana-ohajdova-IqF8B95ZFfs-unsplash.jpg`
    - `reba-spike-mGlycNv80Uk-unsplash.jpg`
    - `vitamina-poleznova-2lVDdshknXI-unsplash.jpg`
1. Az előző feladatban beszúrt 4 képre alkalmazza a `kep` osztálykijelölőt.

A következő formázásokat a `style.css` fájlban végezze. Ennek a létrehozása a 2-es számú csapattag feladata. Előfordulhat, hogy már elkészítette, csak frissíteni kell a helyi repositoryt (`git pull`). Az ütközések elkerülése végett egyeztessen csapattársával, hogy ő hozza létre a fájlt.

15. A szövegszín korábban hibásan lett megadva, ezt módosítsa `#4d0808` színkódra.

1. Formázza meg a táblázatot:
    - A szegély legyen `1` képont vastag, folytonos, `#aa7777` színű, ahogy a mintán látható
    - A táblázat szegélye legyen összevonva
    - A cellái kapjanak `0.5rem` mértékű belső margót
    - A táblázat legyen vízszintesen középreigazítva

1. Készítsen pillanatképet `táblázat megformázva` üzenettel, de még **ne** juttasa el a távoli repositoryba.

1. Formázza meg a `minikep` osztályú elemeket a következőképp:
    - A kép lebegjen a jobb oldalra
    - A kép szélessége legyen `400` képpont
    - Állítson be `20` képpontnyi bal oldali margót
    - Állítson be `3` képpont vastag folyamatos szegélyt `#4d0808` színnel

1. Készítsen pillanatképet `miniképek megformázva` üzenettel, majd érje el, hogy a távoli repository-ban is **elérhető legyen**.

Módosítások

20. Hozzon létre egy `dogs` nevű mappát közvetlen a gyökérmappában, majd helyezze bele a `german-shepherd.html` fájlt.

1. Módosítsa úgy az `index.html` oldalt, hogy a korábban létrehozott hivatkozás most már a `dogs` mappába lévő fájlra mutasson.

1. Ellenőrizze a CSS fájl és a képek hivatkozásait, hogy a jelenlegi mappaszerkezet esetében is helyesen működjenek.

1. Készítsen pillanatképet `németjuhász áthelyezve` üzenettel, majd érje el, hogy a távoli repository-ban is **elérhető legyen**.

1. Bővítse a felsorolást egy linkkel, ami a `dogs` később létrehozandó `husky.html` fájlra mutasson, a felirat legyen *"Husky"*.

1. Készítsen pillanatképet `főoldal módosítva` üzenettel, majd érje el, hogy a távoli repository-ban is **elérhető legyen**.

1. A `kutyaoldal` azonosítójú elem legelejére egy *bekezdésben* hozzon létre egy hivatkozást az `index.html` oldalra, a kattintható szöveg legyen: *"Vissza a kutyafajtákhoz"*. A link a munkamappa gyökerében található `index.html` fájlra mutasson.

1. Készítsen pillanatképet `link a főoldalra` üzenettel, majd érje el, hogy a távoli repository-ban is **elérhető legyen**.

A feladatot összeállította: Rostagni Csaba