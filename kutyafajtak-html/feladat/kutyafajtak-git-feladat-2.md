---
title: Kutyafajták GIT 2-es csapattag
author:
- Rostagni Csaba
---

A következő feladat elvégzéséhez csapatban kell dolgozni. Ön a 2-es számú csapattag.

1. Az 1-es számú csapattag éppen most készíti el a repositoryt. Ne felejtse megosztani számára a felhasználónevét és/vagy e-mail címét, hogy meg tudja osztani önnel a repositoryt.

1. Amint elkészült a repository klónozza leg (`git clone`), majd hozza létre benne, közvetlen a gyökerében az `img` mappát, majd másolja bele a képeket az alábi mappaszerkezet szerint:

    ```text
    |-- img
    |   |-- background
    |   |   |-- keith-misner-h0Vxgz5tyXA-unsplash.jpg
    |   |-- dogs
    |       |-- german-shepherd
    |       |   |-- anna-dudkova-Ce2FZDbx2T0-unsplash.jpg
    |       |   |-- anna-dudkova-bNXn0gKd454-unsplash.jpg
    |       |   |-- jana-ohajdova-IqF8B95ZFfs-unsplash.jpg
    |       |   |-- katelyn-macmillan-bvMUtFN0mIE-unsplash.jpg
    |       |   |-- reba-spike-mGlycNv80Uk-unsplash.jpg
    |       |   |-- vitamina-poleznova-2lVDdshknXI-unsplash.jpg
    |       |-- golden-retriever
    |       |   |-- david-moynihan-BT_QM4CpnNE-unsplash.jpg
    |       |   |-- hugo-lamacq-mXa-47dLsrA-unsplash.jpg
    |       |   |-- mitchell-luo-f0Y_FDt0xJo-unsplash.jpg
    |       |   |-- olga-andreyanova-XeOO8ir_YHs-unsplash.jpg
    |       |   |-- shayna-douglas-rFao8fcvTdY-unsplash.jpg
    |       |-- husky
    |           |-- chris-ensminger-VwAiY1FCII8-unsplash.jpg
    |           |-- gabe-rebra-NzdjuGxj_18-unsplash.jpg
    |           |-- jack-millard-mtMFJz071Cs-unsplash.jpg
    |           |-- wesley-sanchez-cyimMEASu3A-unsplash.jpg
    ```

1. Ahhoz, hogy  a csapat többi tagja is elérje a fájlokat először adja hozzá staging area-hoz (`git add .`) készítsen pillanatképet `kepek hozzaadva` üzenettel (`git commit -m "kepek hozzaadva"`) a projekt jelenlegi állapotáról, majd érje el, hogy a távoli repository-ban is elérhető legyen (`git push`).

    - Előfordulhat, hogy a csapat egy másik tagja már frissítette a távoli kódtárat, így nem engedi a `push` műveletet. Ilyenkor célszerű biztosítani, hogy a helyi tárolóban minden módosítás legyen véglegesítve, majd frissíteni, hogy tartalmazza a távoli repository módosításait (`git pull`).

1. A feladat korábban említette, hogy a stílusokat egy css fájlban kell majd elhelyezni. Ehhez hozzon létre egy mappát `css` néven, benne egy közös styluslapot `style.css` néven.

1. Mivel a stíluslap közös, így az itt megadott beállítások az összes odlalon elérhetőek lesznek. Készítsen el néhány alap beállítást:

    - Az oldal háttérképe legyen az `img/background` mappában található kép.
    - A szövegszín legyen `brown` színű.
    - Típuskijelölő segítségével állítsa be, hogy a A Címsor 1 legyen középre igazítva.
    - A linkek színe minden állapotban legyen `darkslategrey`.

1. Készítsen pillanatképet `stilus létrehozva` üzenettel, majd érje el, hogy a távoli repository-ban is elérhető legyen.

1. Hozza létre `golden-retriever.html` a projektmappában.

1. Az oldal nyelve legyen *magyar*, míg a karakterkódolás `utf-8`.
1. Az oldal címe legyen: *"Arany retriever"*
1. A `nyers-golden-retriever.txt` fájl tartalmát helyezze el egy `kutyaoldal` azonosítójú `main` elembe.
1. A `kutyaoldal` azonosítójú elem legelejére egy *bekezdésben* hozzon létre egy hivatkozást az `index.html` oldalra, a kattintható szöveg legyen: *"Vissza a kutyafajtákhoz"*. A link a munkamappa gyökerében található `index.html`-re mutasson.
1. Az olda főcímére: *"Arany retriever"* alkalmazzon Címsor 1-es kiemelést.
1. Az alcímeket *"A fajtáról"*, *"Előnyei"*, *"Osztályozás"* és *"Képek"* lássa el Címsor 2-es kiemeléssel.
1. Az *"Előnyei"* címsor után található sorok legyenek számozatlan formázással kialakítva.
1. Az oldalon található további szöveget (a táblázat kivételével) bekezdésekként állítsa be.
1. A főcím alatt közvetlen illessze be a `img/dogs/golden-retriever` mappában található `david-moynihan-BT_QM4CpnNE-unsplash.jpg` képet.
    - A képre alkalamzza a `minikep` osztálykijelölőt
    - Amennyiben a kép nem jelenne meg, úgy a *"Egy arany retriever fekszik a széken"* helyettesítő szöeg jelenjen meg.
    - Amennyiben a felhasználó az egeret a kép fölé viszi, úgy a *"Arany retriever"* szöveg jelenjen meg.
1. Az *"Osztályozás"* részben alakítson ki egy 3 soros, 2 oszlopos táblázatot a mintának megfelelően.
1. Az `./img/dogs/golden-retriever/` mappában található képeket szúrja be az oldal aljára egy `kepek` osztályú keretbe: 
    - `hugo-lamacq-mXa-47dLsrA-unsplash.jpg`
    - `mitchell-luo-f0Y_FDt0xJo-unsplash.jpg`
    - `olga-andreyanova-XeOO8ir_YHs-unsplash.jpg`
    - `shayna-douglas-rFao8fcvTdY-unsplash.jpg`
1. Az előző feladatban beszúrt 4 képre alkalmazza a `kep` osztálykijelölőt.

A következő formázásokat a `style.css` fájlban végezze.


1. A bekezdések sormagassága legyen másfeles, továbbá az első sorra állítson be `1cm` behúzást.

1. Készítsen pillanatképet `bekezdések megformázva` üzenettel, de még **ne** juttasa el a távoli repositoryba.

1. Formázza meg a stíluslapon `kepek` osztályú elem(ek)et a következőképp:
    - A szöveg igazítását állítsa középre
    - Törölje a lebegtetést bármelyik oldalra is lett kiadva

1. Formázza meg a stíluslapon az összes `kep` osztályú elemet a következőképp:
    - A szélessége legyen `280` képpont
    - A `vertial-align` tulajdonság értékét állítsa `middle`-re
    - A háttérszínt állítsa fehérre.
    - A belső kitöltése legyen `10` képpont
    - Állítsa a margót `5` képpontra.
    - Állítson be 1 képpont vastag folyamatos szegélyt `#4d0808` színnel.
    - Állítson be doboz árnyékot `3`-`3` képpont eltolással az x és az y tengelyen, az elhomályosítás sugara legyen `10` képpont, a színe pedig `#4d0808`.

1. Készítsen pillanatképet `képek megformázva` üzenettel, majd érje el, hogy a távoli repository-ban is **elérhető legyen**.

Módosítások

1. Hozzon létre egy `dogs` nevű mappát közvetlen a gyökérmappában, majd helyezze bele a `golden-retriver.html` fájlt.

1. Módosítsa úgy az `index.html` oldalt, hogy a korábban létrehozott hivatkozás most már a `dogs` mappába lévő fájlra mutasson.

1. Ellenőrizze a CSS fájl és a képek hivatkozásait, hogy a jelenlegi mappaszerkezet esetében is helyesen működjenek.

1. Készítsen pillanatképet `arany retriever áthelyezve` üzenettel, majd érje el, hogy a távoli repository-ban is **elérhető legyen**.