---
Title: Kmom02
Description: Part 2
---

Kursmoment 2
==================

<h4>SASS, Node och npm</h4>
Jag hade lite svårt för att försåt hur allt hängde ihop först, men när det väl föll på plats så tycker jag att SASS är ganska trevligt att jobba med. 
Node och npm är helt nytt för mig, när det väl var installerat tycker jag att det gick smidigt att använda. 
Det tog lite tid att vänja sig vid att köra ett kommando varje gång jag vill uppdatera min style snarare än att bara spara .css-filen. 
Var också lite osäker på hur jag skulle strukturera min kod, men verkar som att koden kompilerade nästan hur jag än lade upp strukturen på .scss-filerna så länge allt importerades till style.scss.<br><br>

<h4>Tema och kod</h4>
Mitt tema har en ganska simpel design som jag tycker är lätt att använda och lätt att jobba med. Sidan är ganska responsiv och jag tycker att den fungerar bra oavsett skärmstorlek.<br><br>

Min SASS-kod är uppdelad i samma filer som skapades i övningen då det jag inte ville göra det allt för komplicerat medan jag fortfarande lär mig hur det fungerar. I layout.scss finns all kod som beskriver det grundläggande upplägget som jag vill att alla mina teman ska ha gemensamt. I variables.scss finns alla mina variabler som avänds i resten ac .scss-filerna. I base.scss importeras alla dessa filer så det lätt ska gå att importera dom in i mina teman.
I style.css under mitt "theo"-tema ligger all SASS-kod som är specifik för det temat. Här används en det SASS tekniker som variabler, arv och nästlade regler. Det importeras även typsnitt och ikoner från Font Awsome och Google Fonts. Alla filer från shared importeras genom base.scss.

<h4>TIL</h4>
Hur man använder SASS och importerar fonter/ikoner.
