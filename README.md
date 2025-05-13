# Gabriela Myszkowiak - 120669
# NTPD5


## Zadanie 1: Przygotowanie lokalnego środowiska
Uruchomienie aplikacji za pomocą render.com
![image](https://github.com/user-attachments/assets/10f24097-5915-494c-a6ec-ce358836d2b3)

## Zadanie 3B: Wdrożenie aplikacji Render
Utworzyłam nowy Web Service i skonfigurowałam projekt, podając link do repozytorium na GitHub.


Testowanie endpointów:
![image](https://github.com/user-attachments/assets/9b966d90-4294-4da2-8b8a-29af570ef458)

![image](https://github.com/user-attachments/assets/d18e3adf-0d63-497d-9d35-89be646114c8)


Test endpointu /predict w Postman:
![image](https://github.com/user-attachments/assets/8dbd1937-c34e-4e34-b980-88eec8af404e)


## Zadanie 4: Porównanie zalet i wad wdrożeń serverless vs własny serwer

Przeprowadzane podczas laboratoriów ćwiczenia oraz drobny research na temat tego zagadnienia nasunęły mi konkrentne wnioski:
* korzystając z usług oferujących wdrożenia serverless możemy pozwolić sobie na pewne ułatwienia kosztem odchudzenia portfela. Przykładem jest skalowanie w górę i w dół, które może w wybranych płatnych planach odbywać się automatycznie. Na lokalnej maszynie musimy zadbać o to we własnym zakresie
* kolejna różnica wciąż dotyczy naszych finansów. Korzystanie z płatnych planów wdrożeniowych znacząco zwiększa koszt utrzymania środowiska względem takiego na maszynie lokalnej
* przygotowanie aplikacji do uruchomienia w obu przypadkach jest bardzo podobne i nie powinno sprawiać problemów jeśli np. wcześniej uruchamialiśmy środowisko lokalnie a teraz próbujemy metody serverless
* oczywistą różnicą jest swoboda konfiguracji - na własnej maszynie jest ona dla nas wyższa

## Zadanie 5: Konfiguracja środowiska i obsługa zmiennych konfiguracyjnych w Google Cloud Run / Render

Dodanie zmiennej w *Render*
![image](https://github.com/user-attachments/assets/e09e8908-abd8-4555-97c6-d768ece7d316)


Jak wygląda endpoint w kodzie:
![image](https://github.com/user-attachments/assets/698ffd33-0366-46bf-9383-ce6c59cf886c)


Test endpointu korzystającego ze zmiennej środowiskowej:

![image](https://github.com/user-attachments/assets/f4064467-5965-43a2-acdc-9b80acdbc6cf)

(pokarało mnie za to, że skusiłam się na użycie literki ś)
