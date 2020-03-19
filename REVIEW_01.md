- ### Mille poolest erinevad HTML elemendi atribuudid **id** ja **class**?

    **ID** peab olema HTML dokumendi ulatuses unikaalne. Seda kasutad siis, kui sul on vaja dokumendist üles leida üks konkreetne element. Näiteks JS EventListener külge panna.

    **class** kasutatkse sama tüüpi ja ühise stiiliga elementide puhul. Näiteks kui tahad ära määrata hulga nuppude stiili.

    Lisaks on elemndi **class** atribuudis ära määrata mitu klassi, eraldades nad tühikutega.  
    Näiteks nii `<p class="nav-item active">`.

- ### Videos kasutati **margin** ja **padding**, sellest tekkis küsimus millal tuleks kasutada üht ja millal teist?

    [Selgitav video](https://www.youtube.com/watch?v=NZEz4yNITd8)  

    Selles videos selgitakse, millal üht või teist kasutada ja lisaks sellele veel räägitakse erinevatest viisidest, kuidas kumbagi kasutada erinevate külgede puhul või kõigi või mõnede külgede puhul eraldi.
    
- ### Videos kasutati `height: 100vh;` kas see on sama mis `height: 100%;`, või see on hoopis midagi muud?
  
    [Mis on viewport?](https://www.youtube.com/watch?v=QY3lTBZnJmE)  
    [vh tähendab viewport height](https://medium.com/@madhum86/css-font-sizing-pixels-vs-em-vs-rem-vs-percent-vs-viewport-units-b1485716afe7)  

    See ei ole sama. HTML document võib olla mõõtudelt palju suurem kui *viewport*. `height: 100%;` on ülemise elemendi kõrgus ja `height: 100vh;` on *viewport*i kõrgus.

- ### Miks videos kasutati `justify-content: flex-start;`, kuid mitte lihtsalt `justify-content: start;`?
  
    Saab kasutada mõlemat. Kui kasutada `flex-direction: row-reverse;` või `flex-direction: column-reverse;`, siis käituvad nad erinevalt. Aga Chrome seda ei toeta ja testida on võimalik seda näiteks Firefoxiga. Proovi järgi.

- ### Mis on **main-axis** ja mis on **cross-axis**?
  
    **axis** - telg  
    **main-axis** - põhitelg  
    **cross-axis** - risttelg

    Teljed saab omavahel ära vahetada **flex-direction** *property* abil. See tähendab, et **main-axis** ei ole alati horisontaaltelg.

    `flex-direction: row;` - **main-axis** on horisontaaltelg ja **cross-axis** on vertikaaltelg.  
    `flex-direction column;` - **cross-axis** on horisontaaltelg ja **main-axis** on vertikaaltelg.

- ### Kas **justify-content** ja **align-items** ainuke vahe on selles, et üks on horisontaalne ja teine vertikaalne?

    **justify-content** - kasutatakse sisu paigutamiseks peateljel (main-axis)  
    **align-items** - kasutatakse sisu paigutamiseks ristteljel (cross-axis)

    milline on pea- ja milline risttelg sõltub **flex-directionist** ja ei tähenda, et **justify-content** on alati horisontaalselt.

    [Selgitav video](https://www.youtube.com/watch?v=lUp-liFRboU)

- ### Kui palju kasutatakse flexboxi päris lehekülgedel? Tekib küsimus kas/millal üldse on mõtet seda mitte kasutada?
  
    [History of CSS layouts](http://grid-layout.com/history.html)  
    [Flexbox vs CSS Grid](https://www.youtube.com/watch?v=hs3piaN4b5I)

- ### Mis on **order** *property* ja milleks seda kasutatakse?

    Kui tavaliselt ilmuvad elemendid flex konteinerisse nende kirjutamise järjekorras, siis **order** abil on võimalik seda järjekorda muuta.

    Kasutatkse näiteks *responsive design*i puhul, kus desktop- ja mobiilivaates võib elementide järjekord erineda.

    Kasutatkase näiteks siis, kui elementide järjekord HTML struktuuris visuaalses paigutuses võiks erineda.

    Näiteks nägemispuudega inimestele, kes kasutavad ekraanilugereid või otsimootoritele saab esitada tähtsama info HTML struktuuris eespool, visuaalselt võib see olla esile toodud ka nii, et asukoha mõttes asub järjekorras taga pool, aga on suurem või rõhutatud.

- ### Mis on **baseline**?
- ### Miks mul on lehe servas valge serv, aga tal ei ole?
- ### Mis on **CSS Normalize** või **Reset Stylesheet**?
- ### VS Code klaviatuurikäsud ja nende muutmine. Toggle comment line.
- ### CSS selectorid `.plan > *`
