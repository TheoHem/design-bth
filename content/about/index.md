---
Title: Om
Description: Om tekniker
---

Om de olika teknikerna som används på sidan
==================
<h4>Pico</h4>
Sidan är byggd på PHP-baserade ramverket <a href="http://picocms.org/" target="_blank">pico</a>.

<h4>SASS</h4>

Under shared-mappen finns tre .scss-filer:<br>
 - base.scss
 - layout.scss
 - variables.scss<br><br>

I layout.scss finns all kod som beskriver det grundläggande upplägget som jag vill att alla mina teman ska ha gemensamt. I variables.scss finns alla mina variabler som avänds i resten ac .scss-filerna. I base.scss importeras alla dessa filer så det lätt ska gå att importera dom in i mina teman.<br><br>

I style.css under mitt "theo"-tema ligger all SASS-kod som är specifik för det temat. Här används en det SASS tekniker som variabler, arv och nästlade regler. Det importeras även typsnitt och ikoner från Font Awsome och Google Fonts. Alla filer från shared importeras genom base.scss.
