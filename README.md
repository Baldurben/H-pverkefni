# Keyrsla verkefnis
Til þess að keyra verkefnið þarf að installa dependencies með: `$ npm install`

Svo þarf að compilea .SCSS skrár í .CSS sem er gert með: `$ npm run sass`

Nú ætti verkefnið að vera rétt sett upp.

Ef þú ætlar að gera breytingar er hægt að keyra sass-watch sem að fylgist með breytingum innan .SCSS skrám og compilear jafn óðum í .CSS og skipunin fyrir það er: `$ npm run sass-watch`

Síðan til að 'linta' scss kóðann (athuga að uppsetning sé rétt) þá er hægt að keyra `$ npm run lint-scss` fyrir styles.scss skránna og `$ npm run lint-scss-folder` fyrir allar .scss skrár í scss möppunni.


# Uppsetning verkefnis
Í verkefninu erum við með 5 .SCSS skrár sem eru:

#### config.scss
Í config eru grunn stillingar eins og font og litir. 

#### header.scss og footer.scss
header.scss og footer.scss innihalda scssið fyrir headerinn og footerinn.

#### grid.scss
Meirihluti alls scssins sem við skrifuðum er að finna í grid skjalinu. Við fylgdum BEM merkingum til að gera uppsetningu verkefnisins auðskiljanlega.

#### staff.scss
Staff.scss inniheldur scssið sem þarf til þess að stylea staff síðuna.

Þetta er allt importað í `styles.scss` sem er síðan compileað í `styles.css` og er notað af HTMLinu.


# Höfundar verkefnis
Baldur Benediktsson bab42@hi.is

Rebekka Rut Stefánsdóttir rrs10@hi.is

Sveinn Þórarinsson svt9@hi.is

