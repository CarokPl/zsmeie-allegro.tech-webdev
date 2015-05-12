# WYMAGANIA
* nodejs, npm
* gruntjs

# INSTALACJA
1. klonujemy projekt: 
```
git clone https://github.com/krzysztofem/ZSMEiE.git
```
2. instalujemy potrzebne narzędzia (plik package.json): 
```
npm install
```

# STRUKTURA KATALOGÓW
* cssy edytujemy w: /css/source. Zmiany wprowadzamy jedynie w plikach z rozszerzeniem .less
* pliki z rozszerzeniem .css generowane są z plików .less

# PRACA NAD PROJEKTEM
1. uruchamiamy taska gruntowego:
```
grunt watch
```
Teraz, po każdej zmianie w plikach .less, wygenerowane zostaną nasze cssy (pliki .css)
2. uruchamiamy lokalny serwer:
```
python -m SimpleHTTPServer
```
3. w przeglądarce wpisujemy adres: http://localhost:8000/views/
4. Gotowe!
