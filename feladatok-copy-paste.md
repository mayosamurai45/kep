Néhány gyakorlófeladat

Néhány feladat az alapok gyakorlásához. Ha egy lépés után túlzottan zajos eredményt kapott, végezzen szűrést az eredmények javításához. Nem ZH mintafeladatok. A dolgozatban bármi szerepelhet, ami az órai ismeretek alapján megoldható. 


A kép mentéséhez az imwrite(fájlnév, mentendő_kép); függvényt használhatja. 

F1.

    Olvassa be gombokat tartalmazó képet.
    [Konvertálja a képet HSV színtérbe.]  
    Másolja át a zöld gombokat egy másik, azonos méretű, fekete képre. 
    Jelenítse meg az eredményt egy akármi nevű ablakban.

F2.

    Olvassa be gombokat tartalmazó képet.
    [Konvertálja a képet HSV színtérbe.] 
    Őrizze meg a zöld gombokat a képen, a kép többi pontját pedig állítsa pirosra. 
    Jelenítse meg az eredményt egy XXX nevű ablakban.

F3:

    Olvassa be valamelyik gombot tartalmazó képet.
    Küszöbölje a képet úgy, hogy az eredménykép fekete-fehér legyen. A gomb legyen az előtér. A küszöbértéket konstans értékkel adja meg.
    Mentse el az eredményt result.png néven.

F4:

    Olvassa be valamelyik gombot tartalmazó képet.
    Küszöbölje a képet automatikus eljárással úgy, hogy az eredménykép fekete-fehér legyen és a gomb legyen fehér az eredmény téren. 
    Mentse el az eredményt valami.jpg néven.

F5:

    Olvassa be valamelyik gombot tartalmazó képet szürkeskálában.
    Méretezze át a képet az eredeti méretének duplájára. 
    Alkalmazzon speciális küszöbölést, mely megőrzi az előteret, a háttérpontokat viszont kinullázza ("törli").
    Jelenítse meg az eredményt.

F6. 

    Olvassa be a két képet, ami egy-egy gombot tartalmaz. 
    Mossa el mindkét gombot egy 7x7-es mediánszűrővel.
    Konvertálja a képeket valóssá.
    Váltsa át mindkét képet Lab színtérbe.
    Számítsa ki, hogy mennyi a két kép középpontjai között a teljes színkülönbség. Az eredményt (egy valós szám) a standard outputra írja ki.

Segítség: Az at függvénnyel kérje le a két lab kép középső pixelét. Figyeljen arra, hogy a konvertálás miatt ez Vec3f típusú. 

F7.  

    Olvassa be a zászlót (usa_flag) tartalmazó képet.
    A zászlót őrizze meg. A hátteret törölje. A zászlórúd törléséről vagy megőrzéséről szabadon dönthet. 
    Jelenítse meg az eredményképet. 

    Segítség: összetett feltételre/több maszk használatára is szüksége lehet.

F8.

    Olvassa be a gombokat tartalmazó képet.
    Küszöbölje a képet. (A fehér gombok elveszhetnek.)
    Határozza meg a képen a többi gomb külső kontúrját.
    Rajzolja ki a kontúrokat eltérő színnel a gombokat tartalmazó képre.

F9.

    Olvassa be az egyik gombot tartalmazó képet.
    Küszöbölje a képet. 
    Határozza meg a képen a gomb külső kontúrját.
    Jelenítse meg a konzolon a kontúr területe és a fehér pontok száma közti különbséget. 

F10_K.

    Olvassa be az egyik gombot tartalmazó képet.
    Küszöbölje a képet. 
    Határozza meg a képen a gomb összes kontúrját.
    Rajzolja ki különböző színnel a gomblyukakat.
    Jelenítse meg a képet.

F11_K.

    Olvassa be a gombokat tartalmazó képet.
    Küszöbölje a képet (a fehér gombok elveszhetnek)
    Határozza meg a képen a gombok minden kontúrját.
    Számolja össze, hogy hány gomblyuk van a képen és jelenítse meg az eredményt a standard outputon.

F10.

    Olvassa be az egyik gombot tartalmazó képet.
    Küszöbölje. 
    Írja ki a konzolra, hogy hány pixelből áll a gomb. 
    Morfológiai művelettel határozza meg a gomb körvonalát.
    Jelenítse meg a körvonalakat tartalmazó képet.

F12.

    Olvassa be a gombokat tartalmazó képet.
    Küszöbölje a képet  (a fehér gombok elveszhetnek)
    Dilatálja a képet 7x7-es, ellipszis alakú struktúraelemmel. 
    Jelenítse meg a kapott eredményt.

F13.

    Olvassa be a gombokat tartalmazó képet.
    Küszöbölje a képet  (a fehér gombok elveszhetnek)
    Végezzen morfológiai zárást a képen 7x7-es, ellipszis alakú struktúraelemmel. 
    Jelenítse meg a kapott eredményt.

14.

    Olvassa be a gombokat tartalmazó képet.
    Küszöbölje a képet  (a fehér gombok elveszhetnek)
    Határozza meg a gombok külső kontúrját.
    Határozza meg az egyes gombok magasságát és szélességét a befoglaló téglalapjuk alapján.
    Az értékeket a standard outputra írja ki vagy írja rá a képre. 

F15.

    Olvassa be a gombokat tartalmazó képet.
    Küszöbölje a képet  (a fehér gombok elveszhetnek)
    Határozza meg a gombok külső kontúrját.
    Járja be a kontúr vektort:
        Határozza meg a kontúr befoglaló téglalapját
        Vágja ki a téglalap által megadott részt az eredeti képről
        A kapott képeket jelenítse meg és várakoztasson 20 ms-ig.


F16.

    Olvassa be a palota.jpg képet színesben. 
    Hisztogramtranszformáció segítségével javítson a képen. 
    Mentse el lathato_palota.png néven.


F17.

    Olvassa be az egy gombot tartalmazó képet szürkeskálában. 
    Végezzen Gauss szűrést 5x5-ös maszkkal, 0.6 szigma paraméterrel. 
    Emelje ki az éleket a Sobel operátor használatával.  
    Jelenítse meg a képet. 

F18.

    Olvassa be az ablakot tartalmazó képet.
    Végezzen egy enyhe, általános szűrést. (pl.  5x5-ös Gauss-szűrő, 0.6 szigma paraméterrel.)
    Határozza meg a vízszintes irányú* gradienserősséget minden pontban.
    Jelenítse meg az eredményt.

*segítség: a gradiens iránya merőleges az él irányára, tehát függőeleges irányú éleket kell látnia a képen. 

F19.

    Olvassa be az ablakot tartalmazó képet.
    Küszöbölje úgy, hogy a "világító" ablakok előtérré váljanak. 
    A későbbiekben meg akarjuk határozni az ablakok számát, ezért el kell érnie, hogy egy-egy ablak egyetlen egységgé olvadjon össze. (A kereteket el kell törölnie.)  
    Jelenítse meg az eredményt.

F20. 

    Nyissa meg a snow.avi videót. 
    Olvassa be a jerry_monent képet. 
    Minden egyes képkockára hajtsa végre az alábbi műveleteket:
        másolja rá Jerry-t (természetesen a háttér nélkül). Jele a videó jobb oldalára. 
        várakoztasson 20 milliszekundumot. 
    Az utolsó képkocka bezárása előtt várakozzon addig, amíg a felhasználó le nem üt egy billentyűt. 
    
    
További feladatok

AF1.: Olvassa be a pinguen_colony2.png képet és határozza meg, hogy hány pingvin van a képen. Jelöljön meg minden pingvint körrel vagy más jelölővel, hogy ránézésre is ellenőrizni lehessen a program helyességét. 

AF2.: Írjon programot, mely beolvassa az ablakok.jpg képet és megszámolja, hogy hány ablakból árad ki a fény. Ügyeljen rá, hogy a keretek miatt ne számoljon egy ablakot többször. Rajzolja is körbe a világosnak vélt ablakokat, hogy az eredményt ránézésre is ellenőrizni lehessen. 

AF3.: Becsülje meg a napozó rozmárok számát az agyarak száma alapján. 

    Olvassa be a walrus_jeff_foot.png képet. 
    Küszöbölje a kék csatorna alapján (ne sajnálja az időt a megfelelő küszöbérték megkeresésére)
    A külső körvonalakat gyűjtse össze a küszöbölt képen.
    Minden körvonalra:
        határozza meg a minimális befoglaló téglalapot az alábbi függvény segítségével:
        cv::RotatedRect minAreaRect(cv::InputArray points);
        ha a kapott téglalap hosszabbik oldala legalább kétszer olyan hosszú, mint a rövidebb oldal, akkor az adott kontúrt tekintse rozmáragyarnak, növeljen egy számlálót és rajzolja ki zölddel a kontúrt.  Egyébként rajzolja ki kékkel a kontúrt az eredeti képre. 
        Megj.: Szükség esetén (pl.: ha a küszöbölése nem az igazi) a kontúr területe/kerülete alapján is kidobhat kontúrokat ennél a lépésnél. 
    Írja ki a rozmárok becsült számát (normál esetben egy rozmár 2 agyarral bír).
    /A "becsült" szó arra utal, hogy ennél a feladatnál elfogadhatóak hibák: nem minden rozmárnál látható a két agyar, a küszöbölés során is elveszhet egy-egy barnásabb agyar, és bejöhet egy-két fehérnek látszó terület, bár ezeket szűri majd valamennyire. A detektált agyarak száma alapján csak alsó becslés adható. /

AF4. : Találja meg a képen a kókuszos fánkokat a fank.jpg, majd rajzolja őket körbe 3 pixel vastag fekete vonallal. Jelenítse meg az eredményt. (Megj. Nem elvárt a fekete vonal precíz illeszkedése. )

AF5.: Találja meg az összes fánkot a fank.jpg képen, majd egyesével mentse le a fánkokat tartalmazó képrészleteket (befoglaló téglalap által megadott rész) egy mappába. 

AF6.: Másolja oda a lekicsinyített Jerry-t (természetesen a zöld háttértől mentesen) a snow.avi minden képkockájának felső sarkába. Az eredményképet jelenítse meg, elmentenie nem kell. 
