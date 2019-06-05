# Zarovizsga-tetelek-2019

Tudományos adatanalitika és modellezés specializáció [záróvizsga tételsor 2019](https://physics.elte.hu/content/fizikus-msc-zarovizsga-informaciok.t.2998?m=1515&fbclid=IwAR1KUiIbuPZiUw67nuoKrVk551MCUSsgpzI6yMt1ao7H331aCvSdKQxeUyw).

# Munkamenet:

1. Minden tétel külön mappában lesz, külön tex forrással és képekkel. Mindenki csak a saját mappájában dolgozzon. Tehát ha a 3-as tételt dolgozod ki, akkor a 3-as mappa a tied, hogy ne legyen merge conflict.

2. Győzödj meg róla, hogy lefordul a latex forrásod, ne rakj ki olyan forrást, ami hibaüzenetet dob!

3. Ha ez megvan, akkor a gyökér mappából `git add .` aztán `git commit -m "valami message"`, majd `git push`. Ha valamiért ez nem megy, akkor valószínű, más is hozzáadott valamiket, ezért `git pull` majd újra `git commit -m "Message"` és `git push`.

4. Ha kérdésed van, nyiss egy issue-t, hogy mindenki lássa.

5. Ha nem jelennek meg a hivatkozások, referenciák, próbálkozz ezzel:
```
cd <mappa, ahol a tex file van>
pdflatex <tex_file_kiterjesztes_nelkul> && bibtex <tex_file_kiterjesztes_nelkul> && pdflatex <tex_file_kiterjesztes_nelkul> && pdflatex <tex_file_kiterjesztes_nelkul>
```
# Sablon:
Itt található egy sablon, amiben vannak hasznos megoldások, példák: [sablon pdf](https://github.com/nbulatovic/Zarovizsga-tetelek-2019/blob/master/template/template.pdf)
[sablon tex](https://github.com/nbulatovic/Zarovizsga-tetelek-2019/blob/master/template/template.tex)

# Beosztás

Berekméri Evelin 1, 11

  

Biricz András 12, 16

  

Bulatovic Nikola 9, 14

  

Furuglyás Kristóf 5

  

Horváth Benedek 7, 10

  

Kaszás Bálint 6, 3

  

Kruppa Zoltán 13

  

Mezősi Máté 15, 8

  

Nagy Dániel 2

  

Olar Alex 4

  

Prósz Aurél 17

  

# Tételsor

  

1) Mérési adatok és a mérési hiba – Hibák és zajok, ezek forrásai. A statisztikus és a szisztematikus hiba. A hiba sztochasztikus modellezése. Adatmodellezés – A függvényillesztés alapproblémája. Magfüggvényes becslések.

  

2) Bootstrap módszerek. A maximum likelihood módszer. Hipotézis tesztelés. Extrém statisztikák. Post hoc analízis. Regresszió. Függetlenségvizsgálat. Egzakt tesztek.

  

3) Véletlen számok generálása, numerikus integrálás, Newton-típusú formulák, Gauss-formulák. Monte-Carlo módszer, Markov-lánc Monte-Carlo, hierarchikus bayes-i hálózatok.

  

4) Termodinamikai rendszerek szimulációja, Ising-model, Metropolis-algoritmus.

  

5) Fraktáldimenzió, önhasonló matematikai fraktálok, természetben előforduló fraktálok, sejtautomaták.

  

6) Differenciálegyenletek numerikus vizsgálata, Euler-módszer, Runge-Kutta módszer, stabilitás, parciális differenciálegyenletek. Dinamikai rendszerek, kaotikus viselkedés (Complex and Adaptive Dynamical Systems alapján).

  

7) Molekuláris dinamika, Verlet- és sebesség-Verlet-algoritmus, termodinamikai mennyiségek meghatározása és relaxáció.

  

8) Jelfeldolgozás és idősor-analízis – Fourier-módszerek, FFT, a spektrum és a spektrogram, az átviteli és ablakfüggvények, Wiener-szűrő. Korrelációs függvények, a Wiener–Hincsin-tétel és a teljesítményspektrum. Konvolúció és dekonvolúció. Szűrők analóg és digitális megvalósítása, RLC-körök, FIR- és IIR-szűrők.

  

9) Képfeldolgozás – Képek digitális reprezentációja, színmodellek. Interpolációs, konvolúciós és dekonvolúciós módszerek, homomorf szűrés. Élek, sarkok és foltok detektálása. Morfológiai analízis, jellemzők kinyerése. Perspektívakorrekció, zajszűrési módszerek.

  

10) AD és DA konverterek – Digitális-analóg konverzió, AD-konverzió szukcesszív approximációval. A kvantálási zaj és a mintavételi törvény. Digitális jelek tömörítési módszerei: delta-moduláció és delta-szigma moduláció. Digitális számábrázolás és műveletvégzés.

  

11) Számítógépes tanulás – Predikciós és klasszifikációs módszerek. Felügyelt és felügyelet nélküli tanítás. A tanítóhalmaz, a validáció és a túlfittelés. K-means, Support Vector Machine, Random Forest, k-NN-módszer.

  

12) Neurális hálók - teljesen összekötött neurális hálók, konvolúciós neurális hálók, backpropagation, optimizerek (SGD, Adam), batch normalisation, autoencoderek, word2ve

  

13) Dimenzióredukciós módszerek – Magas dimenziós adatok statisztikus tulajdonságai. A főkomponens-analízis és alkalmazásai, t-SNE.

  

14) Számítógépes hálózatok – A hálózati adatátvitel fizikai rétege, ethernet, az optikai adatátvitel módszerei. Vezeték nélküli hálózatok. IP hálózatok, végpontok, kapcsolók, útválasztók, tűzfalak, IP cím, TCP, UDP, DNS, NAT. Sávszélesség, sorban állás, torlódás. Hálózati topológiák. Adattitkosítás.

  

15) Relációs adatbázisok – a relációs adatmodell, logikai és fizikai operátorok (seek, scan és a joinok változatai, aggregálás), adattárolási modellek (row store, column store), indexek (klaszterezett index, nem klaszterezett index), a B-fa, kulcsok és kényszerek, tranzakciók. Lekérdezésoptimalizálás. Az adatbetöltés menete.

  

16) Többdimenziós adatok – Geográfiai és térbeli adatok reprezentálása, pontfelhők. Keresési alapproblémák: intervallum-keresés, térbeli keresés, legközelebbi szomszédok. Térbeli indexek, térkitöltő görbék (Z-index, Peano–Hilbert-index), kD-fa, R-fa, a bitkódolás szerepe. Tércellázási módszerek: Delaunay-háromszögelés, Voronoi-cellázás. A gömb indexelése, Quad-tree, HEALPix, HTM.

  

17) Vizualizáció – Tudományos adatok két és háromdimenziós megjelenítésének technikái, skalár-, vektor- és tenzorértékű adatok ábrázolása. Színek. Térbeli adatok megjelenítése, volometrikus és szintfelületes ábrázolás. Háromdimenziós renderelési technikák, ray casting, ray tracing. A sztereoszkópius megjelenítés technológiái. Számítógépes geometria.