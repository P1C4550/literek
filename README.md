# Literek

___literek___ - Urządzenie edukacyjne wspierające naukę poprzez zabawę z fiszkami. Działanie programu polega na losowym usuwaniu jednej litery ze słów pobranych z bazy danych i wyświetlaniu ich ze znakiem `_` w miejscu luki. Zadaniem użytkownika jest pokazanie odpowiedniej fiszki z literą do kamery urządzenia. Program analizuje obraz, rozpoznaje literę i weryfikuje poprawność odpowiedzi – w razie sukcesu przechodzi do kolejnego hasła, a w przypadku błędu pozwala na ponowną próbę. W przypadku kilku niepoprawnych odpowiedzi pokazuje poprawną odpowiedź.


## Uruchamianie

Zalecamy używać [uv](https://docs.astral.sh/uv/), który automatycznie tworzy wirtualne środowisko i pobiera biblioteki.

`uv run main.py`

Inaczej należy zainstalować biblioteki zdefiniowane w `pyproject.toml`


## Dostosowywanie

Program można dostosować do własnych potrzeb, zmieniając słowa, model i różne parametry.

Wszystkie możliwe opcje można zobaczyć uruchamiając program z argumentem `--help`

## Dane
Wypakowane pliki z teachable machine idą do `./model_data/`

w `labels.txt` klasa z tłem bez liter musi mieć nazwę `-`

Pliki ze słowami idą do `./word_data/`
