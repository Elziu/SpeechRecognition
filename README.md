
# System Rozpoznawania Mowy

## Instrukcja instalacji

### Krok 1: Sklonowanie repozytorium

1. Otwórz terminal lub wiersz polecenia.
2. Przejdź do katalogu, w którym chcesz sklonować repozytorium.
3. Uruchom poniższe polecenie, aby sklonować repozytorium:
 
    ```bash
    git clone https://github.com/Elziu/SpeechRecognition
    ```
5. Przejdź do katalogu projektu:
 
    ```bash
    cd SpeechRecognition
    ```

### Krok 2: Instalacja zależności

1. Upewnij się, że znajdujesz się w katalogu projektu.
2. Zainstaluj wymagane biblioteki za pomocą poniższego polecenia:
   
    ```bash
    pip install -r requirements.txt
    ```

### Krok 3: Uruchomienie programu

1. Upewnij się, że masz zainstalowane wszystkie wymagane biblioteki.
2. Uruchom główny skrypt:
   
    ```bash
    python speech_recognition_system.py
    ```

### Krok 4: Obsługa programu

1. Po uruchomieniu programu, pojawi się komunikat:
   
    ```
    Nacisnij 'r', aby rozpoczac nagrywanie...
    ```
3. Naciśnij klawisz `r`, aby rozpocząć nagrywanie.
4. Pojawi się komunikat:
   
    ```
    Nacisnij 's', aby zatrzymac nagrywanie...
    ```
6. Naciśnij klawisz `s`, aby zatrzymać nagrywanie.
7. Nagranie zostanie zapisane w folderze `nagrania`, a transkrypcja w folderze `transkrypcje`.
