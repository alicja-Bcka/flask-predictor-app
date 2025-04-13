# Flask Predictor App

##
Prosta aplikacja Flask udostępniająca endpoint API `/api/v1.0/predict`. Przyjmuje dwie liczby jako parametry (`liczba1`, `liczba2`) i zwraca predykcję 0 lub 1 w zależności od ich sumy:

- `prediction = 1`, jeśli suma > 5.8
- `prediction = 0`, w przeciwnym razie

Brak podanych liczb traktowany jest jako wartość domyślna `0`.
