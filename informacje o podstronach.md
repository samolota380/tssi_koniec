Strona główna (index.html) – jest dobra, zostaje taka jak jest
Tutoriale – tam są linki do wszystkich podstron tutorialowych, które będą się znajdowały w folderze /tutoriale
html-podstawy.html – z tego powinieneś się inspirować układem strony, stylem itp.
trzeba do niej tylko dodać na dole przejśćie do następnej strony tutorialowej
styl taki ogólny jest w style.css, nie bój się do niego dopisywać rzeczy

Pisząc css:
nie pisz wszystkiego w jednej linii, pisz to tak aby wyglądało na human written (np bez komentarzy) i było readable.
staraj się outsoucować rzeczy do style.css jeżeli ma to sens aby było to wszystko wspólne i ujednolicone

kolejność tych samouczków ( i tak linki do wszyckich mają być dodatkowo w tutoriale.html w formie tych kafelków co są)

jak piszesz jakiś kod to jeżeli to ma sens to zamieść pod tym ten sam kod ale już nie jako przykład tylko kod do strony aby np. było widać co dany kod z przykładu zrobił i jak wygląda.

1 - Html podstawy: 
definicja, parser, doctype, meta, przegląðarka, walidator, sitryna, zasady znaczników, encje

2 - Podstawowe znaczniki:
meta, wszystkie jej opcje tzn description, keywords, copyright, generator, robots
h1, p, h1-h6, em, strong, znaczniki blokowe i liniowe, cite, q, blockquoute, small, i, b, br, hr, code, pre, sup, sub, ins, del, span

3 - Listy
ul, li, ol, dl, dt, dd

4 - Tabele:
tables, tr, th, td, rowspan, colspan, tabele zagnieżdżone.

5 - Adresowanie w html5
a href do wszystkiego, img src alt, href do id elementów na stronie #, adresiwabue bezwzględne vs względne, mailto

6 - Grafika
atrybut title, img height width

7 - CSS Wprowadzenie
selektor, właściwość, wartość, deklaracja stylu, reguła stylu
3 typy: zewnętrzny, wewnętrzny, lokalny, przykłady.
hierachia stylów, arkusz zerujący meyera definicja.

8 - Czcionki
szeryfowe, bezszeryfowe, wytłumaczenie, wiele przykłady czcionek(serif i sans-seric)
font-family, font-style, text-decoration i wszystko o nim, font-weight

właściwości color, font-weight, letter-spacing,
text-align
font-size, odnościk do jednostek
line-height
nowrap

9 - Jednostki w html (wszystkie), strona o jednostkach jest już zrobiona ale trzeba ją dopracować tzn całkowicie styl wywalić i dopasować do tutejszych potrzeb bo była zaimportowana z jakiejś starej strony

10 - Model pudełkowy w CSS
jakaś grafika, wytłumaczenia, marginesy, paddingi, 
background color, background image, gradient, wszystko o borderach i przykłady
width, height, środkowanie, centrowanie! 

11 Opływanie float i układy stron zrobione przy jego użyciu
left right, nie ma float center

12 Display flex i układy stron zrobione przy jego użyciu
te takie układy przykładowe zafillowane lorem ipsum.

13 Display grid i układy stron zrobione przy jego użyciu
jak się to robi

14 Menu pionowe i poziome
nav, <nav><ul><li><a></....>
klasa, id, odnośnik do wszystkich rodzajów selektórów w html
a:hover visited active link itp.

15 Selektory
wszystkie typy selektorów, jest już plik selektory.html ale on jest w złym stylu, trzeba go totalnie wyciepać i dostosować do naszych potrzeb

16 Mapa odsyłaczy na obrazku
wykorzystaj jakoś mapa.html ale znowu podobna sytuacja co do wcześniejszych ponownie wykorzystywanych plików
usemap
area shape itp.

17 Pozycjonowanie elementów na stronie internetowej
position, static, relative, absolute, fixed, sticky
left-right-top-bottom

18 Cieniowanie
border-collapse, box-shadow, text-shadow, border-radius

19 Pozycjonowanie kontekstowe
overflow, position absolute, position relative, absolute
z-index. Z index nie działa przy position:static! 
scrollbar-color, scrollbar-wight

20 Formularze
form, action, method (post i get, bezpieczeństwo), autocomplete, novalidate
textarea
input type, value
label type text, reset, password
label for, połączone z input type=.. id=..
selektorowanie input[type=submit] w css
required, readonly, disabled,
dostępność: tabindex, acceskey

21 Formularze 2
placeholder, max-lenght, min-lenghth, 
:focus, autofocus, size,
wszystkie type tzn tel passwword email url date datetime-local time week; number min max step, range min max step, color
checkbox, zasady ich name'owania
radio
fieldset i legend
enctype, type file accept=...
type hidden, submit, reset
button, może być 3 typów: submit, reset, button
select name size multiple, option, optgroup

22 Responsywność stron
definicja, picture, source media srcset, img src alt
meta viewport, odniesienie do jednostek
treshholdy, jakieś obrazki
@media css

23 Animacje w html5
transform rotate, scale, translate, transition, opacity
@keyframes, from, to, procenty %
animation:nazwa 4s, animation0iteration-count, animation-direction, delay, timing-function wszystkie,
steps