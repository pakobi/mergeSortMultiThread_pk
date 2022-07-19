# mergeSortMultiThread_pk
PPR - Labolatorium 
Zad13 - Sortowanie tablicy za pomocą algortmu mergeSort - sortowanie przez scalanie - wersja wielowątkowa

Tablica wejsciowa jest generowana przez funkcje RAND()

Wielkosc tablicy wejsciowej ustalona przez #define TABLE_MAX_LENGTH 1000

Zdefinowana struktura DataS - zawiera dane tablicy do sortowania

Zdefiniowane dwie funkcje typu void: scalaj(int, int, int, int), sortujScalaj(void *arg)

Podział tablicy wykonywany jest przez dwie funkcje wielową

Ustawione i uruchomione zostały dwa watki na podział tablicy obsługujące  sortujScalaj(void *arg) rekurencyjnie.

Ustawiony został wątek w main() który uruchamia sortujScalaj(void *arg) i czeka na wykonanie całego algortmu.
