# Feladatok
**A 05-number-and-math mappán belül kell dolgoznod!**  
**A HTML fájlokat ne módosítsd!**   
**Az export utasításokat hagyd a file-ok végén!**  
**Az `npm run test:number` parancs futtatásával tudod futtatni a teszteket!**  

1. Írj egy függvényt `summarize` néven, ami a paraméterként kapott tetszőleges darabszámú, tetszőlegesen méretű egész számot összead, és  visszatér az összeadás végeredményével! Vizsgáld is a paraméterként kapott számokat, hogy tényleg integerek-e!
Amennyiben valamelyik paraméter nem integer, egyszerűen hagyd ki a számításból!  
Amennyiben bármelyik paraméter értéke, vagy a részeredmény meghaladja a biztonságos tartomány (safeInteger), automatikusan konvertáljad `BigInt`be, és természetesen a visszatérési érték is `BigInt` legyen!

1. Írj egy függvényt `numericConverter` néven, ami a paraméterként megadott tízes számrendszerbeli számot átkonvertálja kettes, nyolcas, és tizenhatos számrendszerbe is! Ezeket az értékeket pedig egy objectbe adja vissza! A property-k neve legyen: `binary`, `octal`, `hexa`.