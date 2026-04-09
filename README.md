<h1>Detekcja choroby Wilsona</h1>

<h2>soft_set_isWilsondisease_classification – Analiza danych i klasyfikacja</h2>
Zawiera preprocessing zbioru danych – normalizację oraz usunięcie cech o niskim wpływie na wynik. 

Na przygotowanych danych zaimplementowany jest algorytm klasyfikacyjny oparty na teorii zbiorów miękkich, wykorzystujący średnią i medianę. Model jest trenowany na zbiorze treningowym i ewaluowany na zbiorze testowym z wyznaczeniem wskaźnika accuracy.


<h2>genetic_algorithm – Optymalizacja wag algorytmem genetycznym</h2>
Zawiera implementację algorytmu genetycznego z selekcją ruletkową, którego celem jest wyznaczenie optymalnych wag poprawiających accuracy klasyfikatora. Ze względów wydajnościowych obliczenia wag wykonywane są na reprezentatywnej części zbioru danych.

</br>

<b>Najwyższe uzyskane accuracy: 99,97%</b>
