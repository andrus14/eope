### 1. Mis poolest erinevad HTML elemendi atribuudid **id** ja **class**?
    **id** peab olema HTML dokumendi ulatuses unikaalne.  
    **class** määrab ära elemendi tüübi, ühte tüüpi elemente võib oll dokumendi ulatuses rohkem.

### 2. Videos kasutati "margin" ja "padding", sellest tekkis küsimus millal tuleks kasutada "padding" ja millal "margin"?
    (https://www.youtube.com/watch?v=NZEz4yNITd8)
    Selles videos selgitakse, millal üht või teist kasutada ja lisaks sellele veel räägitakse erinevatest viisidest, kuidas kumbagi kasutada erinevate külgede puhul või kõigi või mõnede külgede puhul eraldi.
    
### 3. Videos kasutati "height: 100vh;" kas see on sama mis "height: 100%;", või see on hoopis midagi muud?
    [Mis on viewport?](https://www.youtube.com/watch?v=QY3lTBZnJmE)
    [vh on viewport height](https://medium.com/@madhum86/css-font-sizing-pixels-vs-em-vs-rem-vs-percent-vs-viewport-units-b1485716afe7)
    See ei ole sama. HTML document võib olla mõõtudelt palju suurem kui viewport. height: 100%; on parent elemendi kõrgus ja 100vh on viewporti kõrgus.

### 4. Miks videos kasutati "justify-content: flex-start;" kuid mitte lihtsalt "justify-content: start;"?
    Saab kasutada mõlemat. Kui kasutada flex-direction: row-reverse või column-reverse, siis käituvad nad erinevalt. Aga ainult Chromes.

1. Mis on main-axis ja mis on cross-axis?
1. Kas "justify-content" ja "align-items" ainuke vahe on selles et üks on horisontaalne ja teine vertikaalne?
    axis - telg; main-axis - põhitelg; cross-axis - risttelg
    Teljed saab omavahel ära vahetada flex-direction atribuudiga.
    flex-direction: row; - main-axis on horisontaaltelg ja cross-axis on vertikaaltelg.
    flex-direction column; - main-axis on vertikaaltelg ja cross-axis on horisontaaltelg.

    justify-content kasutatakse sisu paigutamiseks peateljel (main-axis) ja align-items sisu paigutamiseks ristteljel (cross-axis), mis sõltub flex-directionist ja ei tähenda, et justify-content on alati horisontaalselt.
    Selgitav video - https://www.youtube.com/watch?v=lUp-liFRboU

1. Kui palju kasutatakse flexboxi päris lehekülgedel? Tekib küsimus kas/millal üldse on mõtet seda mitte kasutada?
    History of CSS layouts - http://grid-layout.com/history.html
    Flexbox vs CSS Grid - https://www.youtube.com/watch?v=hs3piaN4b5I




    Milleks kasjutatakse ordering, tahaks täpsustust saada
    Küsimus siuke, kui kasutan  flex-wrap:wrap; ja align-content:flex-start;  ja panen div sisse <br> Miks siis 1-2 kast muutuvad? https://gyazo.com/0667e380c41d2f8c94a639967e101cd5 (pilt sellest)
    Sain teada, et flex-grow kasutades, saata muuta ühe div suuremaks, kui teised
    https://gyazo.com/4fc1d2f70bf48e84fa2dfa2c199bdf10 Ta kasutas videos * mida see täpsemalt teeb, ei saanud aru?


* sain teada et itemeid saab orederida 'order: number'
* sain teada et 'align-items: baseline' seab kõik erineva suurusega kastid milles on tekst, õigele kõrgusele et text oleks ka õigel kõrgusel.
* tuli meelde et kui teed näiteks divi ja määrad sellele klassi, siis saab sinna samasse panna ka teise klassi et näiteks ühesugustest kastidest just mingit teatud kasti muuta jne. Ise kasutasin ainult ühte klassi koguaeg.

1. Mis vahe on ID'l, classil? Millal kasutada ühte ja millal teist? Googeldasin, sain teada, et ID on unikaalne ja saab kasutada ainult ühe korra, aga class võib korduda.
2. Tal hakkab lehekülje content lehekülje äärtest, aga minul jätab väikse vahe sisse enne kui content algab. Googleist leitsin et algselt html paneb natukene marginit.
4. Kuidas kiiresti koodi välja commentida? Googleist leitsin Ctrl+K+C.