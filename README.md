# Wymagania
* nodejs, npm
* gruntjs

# Instalacja
* klonujemy projekt: 
```
git clone https://github.com/krzysztofem/ZSMEiE.git
```
* instalujemy potrzebne narzędzia (plik package.json): 
```
npm install
```

# Struktura katalogów
* cssy edytujemy w: /css/source. Zmiany wprowadzamy jedynie w plikach z rozszerzeniem .less
* pliki z rozszerzeniem .css generowane są z plików .less

# Praca nad projektem
* uruchamiamy taska gruntowego:
```
grunt watch
```
Teraz, po każdej zmianie w plikach .less, wygenerowane zostaną nasze cssy (pliki .css)
* uruchamiamy lokalny serwer:
```
python -m SimpleHTTPServer
```
* w przeglądarce wpisujemy adres: http://localhost:8000/views/
* Gotowe!
