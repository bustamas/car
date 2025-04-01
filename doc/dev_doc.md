# Fejlesztői dokumentáció

## Az alkalmazás célja

Az alkkalmazás adatait töltibe a csv fájlokból, majd azokon programozási tételeket valósit meg.

## Eszközök

Az alkalmazás egy Java nyelven írt program, ami VSCode-dal készült. A Java projekt "No build tools" választássa jött létre.

## Forrrásfájlok

A Forrásfájlok src könyvtárban találhatók egységesen.

## AZ app osztály

Az app osztáyl csak az alkalmazás inditását szogálja.

## Solution osztály 

A Solution osztály szolháltatja a megoldásokat. Minden egyes metódus egy-egy programozási tétel valósitja meg.

Minden metódus kiírja a saját maga által generealt eredményt.

## A Store osztály 

A Store osztály valósitja meg a fáljok beolvasását. Az ipari kód a tryReadCsvFile metódusban van megvalósitva, a readCsvFile metódus csak a hibakezelést valósitja meg. 

## Car osztály 

A Car osztály objektumban tároljuk a egy jármű adatait.

