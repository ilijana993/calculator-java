# calculator-java
simple calculator written in Java; supports addition, subtraction, multiplication and division

Fajl – broj linije koda – zapažanje (pomoću Sonar Lint-a)

Calculator- 1 – neimenovan paket, code smell=minimalan
Calculator – 4 – Korisne klase ne bi trebalo da imaju javne konstruktore. Code smell=maksimalno značajan
Calculator - 18 - Imena metoda treba da budu u skladu sa konvencijom o imenovanju ( umesto „ToString“ treba da piše „toString“). Code smell=minimalan
Calculator – 24 - Imena metoda treba da budu u skladu sa konvencijom o imenovanju ( umesto „Run“ treba da piše „run“). Code smell=minimalan
Calculator – 70 - Lokalne promenljive ne treba deklarisati, a zatim ih odmah vratiti ili izbaciti (treba da piše „return Float.toString(finalResult)“) . Code smell=minimalan
Calculator – 73 - Imena metoda treba da budu u skladu sa konvencijom o imenovanju ( umesto „Calculate“ treba da piše „calculate“). Code smell=minimalan
Calculator – 182 – suvišna naredba („return“)

Start – 1 – neimenovan paket, code smell=milimalan
Start – 6 - Imena metoda i lokalnih promenljivih treba da budu u skladu sa konvencijom o imenovanju ( umesto „Expression“ treba da piše „expression“). Code smell=minimalan
Start – 8 - Standardni izlazi ne bi trebalo da se koriste direktno za evidentiranje bilo čega. Umesto „System.out.println“ treba da stoji „logger.log“. Code smell=maksimalno značajan
Start – 19 - Standardni izlazi ne bi trebalo da se koriste direktno za evidentiranje bilo čega. Umesto „System.out.println“ treba da stoji „logger.log“. Code smell=maksimalno značajan
