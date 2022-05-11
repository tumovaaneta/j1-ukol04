# Úkol 4 (lekce 6) – Java Collections Framework

Každou část úkolu vytvořte jako samostatný commit (důležité je to spíš pro vás – pokud na to zapoemenete a budete mít vše najednou, není potřeba commity
po částech vyvářet dodatečně). Pokud zjistíte dodatečně v kódu nějakou chybu, nevadí, commitněte opravu jako další commit. Pokud si chcete práci průběžně
zálohovat, po commitu udělejte také push, čímž se všechny neodeslané commity nahrají na GitHub.

Úkolem bude implementovat Sportku – vylosovat 6 čísel a jedno dodatkové číslo ze 49 čísel. 

Implementujte konstruktor a tři metody v třídě `Sportka` podle komentářů `TODO` v konstruktoru/metodě. Při spuštění aplikace dojde k losování dvou tahů Sportky,
ověří se výsledky a tažená čísla se vypíšou do konzole.

Pro implementaci se budou hodit metody na rozhraní [List](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/List.html) a metoda
[Collections.shuffle()](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Collections.html#shuffle(java.util.List)).
