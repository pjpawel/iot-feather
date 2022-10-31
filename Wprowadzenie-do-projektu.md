# Wprowadzenie do projektu
IOT Feather jest projektem stworzonym na potrzeby współpracy 3 grup projektowych z przedmiotu Internet rzeczy. Opiera się na wymienionych w 
[README](https://github.com/utbrott/iot-feather/blob/main/README.md) (sekcja **_Build with_**) elementach hardware oraz sekcji software, której dokladna zawartość pokazana jest w dziale **_File structure_** pliku Readme. Na wiki w sekcjach opisana została część software podzielona, jak same pliki projektu, na sekcje odpowiedzialne za elementy funkcjonlności, które zostały zgrupowane razem w celu ułatwienia odczytu i modyfikacji. Wiki zawiera również opis założeń początkowych samego projektu oraz prac poczynionych przez poszczególne zespoły.

# Założenia projektowe
Założenia projektowe postawione po zapoznaniu się z dostępnym hardware sformułowane zostały w następujący sposób:

**Stacja pogodowa z wykorzystaniem Adafruit Feather**
* wykorzystanie czujnika BME280 do odczytu temperatury, ciśnienia oraz wilgotności pomieszczenia
* wykorzystanie anten do komunikacji poprzez sieć Wi-FI
* zbieranie danych o temperaturze, ciśnieniu i wilgotności za pomocą OpenWeather API
* wyświetlanie danych
* periodyczne odświeżanie danych

# Planowane możliwości