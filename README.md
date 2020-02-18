# html-fundamental

## [1.hodina](./1.hodina) - praca s textom

a(anchor) - klikatelny odkaz
blockquote - odsek
b(bold) - tucne pismo
br(break) - odriadkovanie
del alebo s - preskrtnutie pisma
em (emphasized text) - zdoraznenie textu
h1-h6 - nadpisy
hr(horizontal row) - ciara cez obrazovku
i(italic) - sikme pismo
p(paragraph) - odstavec (hl.text)
pre(preformatted text) - text ostane ako ho piseme
q(quotation) - uvodzovky,citacia
small - male pismo
sub(subscripted text) - dolny index(dole pismo)
sup(superscripted text) - horny index (horne pismo)
strong - tucne pismo
u(underline) alebo ins - podciarknuty text

div(division) - BLOKOVY ELEMENT - def.sekciu dokumentu
span - INLINE ELEMENT - def.sekciu dok.v riadku

## [2.hodina](./2.hodina) - zoznamy,tabulky,obrazok

ul(unordered list) - necislovany(neusporiadany) zoznam (komb. s tag li)
li(list item) - polozka zoznamu
ol(ordered list) - cislovany(usporiadany) zoznam

table - tabulka (komb. s tagmi tr,th,td)
tr(table row) - riadok tabulky,co chcem dat vsetko do riadku(komb. s th,td)
th(table heading) - hlavicka tabulky
td(table data/cell) - info v tabulke (v bunke tabulky)

img(image) - obrazok (na klikatelny obrazok s popisom:(<a href=""title=""><img src="" alt=""></a>)

## [3.hodina](./3.hodina) - linky,layout

### linky

a(anchor) - klikatelny odkaz, s atributom href(URL,mailto:,tel:,), target(_blank-otvori na novom okne)

-prekliknutie mozeme urobit pomocou id: <tag id:"bla"></tag>
-ciel oznacime napr: <div><a href="#bla"></a></div>

### layout

header-hlavicka
nav- navigacia linkov (ul-li-a href="#")
section-def. sekciu v dokumente
article-clanok o ktorom piseme
aside- bocne info na stranke
footer- pata
iframe- pouziva sa na vlozenie ineho dokumentu do aktualneho dokumentu -nejde 

### form, input

form - formular (tabulka) (atribut: action=/action_page.php)
input - vstupne udaje (type="submit"-potvrdit)

## [4.hodina](./4.hodina) - forms

textarea- element def. viacriadkove vstupne pole ( cols-Atribút urcuje viditelnú sírku textovej oblasti, rows-Atribút urcuje viditelny pocet riadkov v textovej oblasti)
select- def. rozbalovaci zoznam (<option> - def.moznost,ktoru mozeme vybrat, atribut selected vyberie ako prvu nasu zvolenu moznost)

6.hodina
border: solid, dotted, dashed, double
padding: 6px(hore+dole),12px(lavo+pravo)
cursor:pointer; -ukaze klikajuci prst 
text-align - plati iba pre inline elementy {ktore su v block lvl elem.}
inline elementy- neda sa menit velkost(akceptuju margin lavy a pravy,horny a spodny nie) display:inline-block ->dokazeme s nim menit vysku a sirku v inlinelementoch
pridavanie farby pomocou: #,alebo nazvu, alebo rgb + rgba( pridame alfa kanal= priesvitnost, od 0-1, stare prehliadace to nezobrazia, tak piseme rgb aj rgba (255, 45, 32, 0.5); ) coloradobe.com

google fonts (sk/cz latin)
tag:hover {color:#fff}; = kurzor nad elementom -> zmeni farbu
font-weight: (100-900);
text-transform: (uppercase-velke pismo, lowercase-male pismo, capitalize- kazde zaciatocne pismeno velke)
font-style:
font-variant: small-caps; - velke pismena vo velkosti malych pismen
text-indent: - na odsadenie textu
text-decoration:
letter/word-spacing:
text-shadow: 3px 2px 0px #fff   tien pod pismom+farba
text-align

.class > h3 -> pouzije priameho potomka 
..-ist von z adresara