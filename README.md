# Przekształcanie artykułów na HTML z OpenAI API

## Opis

Aplikacja umożliwia automatyczne przekształcanie tekstu artykułu na format HTML, z zachowaniem odpowiednich tagów dla nagłówków, akapitów, obrazów i podpisów. Aplikacja korzysta z modelu OpenAI GPT-3.5 do generowania kodu HTML na podstawie dostarczonego artykułu. Dodatkowo, wygenerowany HTML jest zapisywany do pliku w formacie `.html`, gotowego do użycia na stronie internetowej.

### Funkcje aplikacji:

- Wczytuje tekst artykułu z pliku tekstowego.
- Generuje kod HTML, używając OpenAI API.
- Zapisuje wygenerowany kod HTML do pliku `.html`.

## Wymagania

1. **Python 3.x** – Aby uruchomić aplikację, musisz mieć zainstalowaną wersję Pythona 3.
2. **Zainstalowane biblioteki**:
    - `openai` (do komunikacji z API OpenAI)
    - `os` (do operacji na plikach)

## Instrukcja uruchomienia

### 1. Instalacja wymaganych bibliotek

Upewnij się, że masz zainstalowaną bibliotekę `openai`. Możesz to zrobić za pomocą poniższego polecenia:

```bash
pip install openai
```bash

### 2. Pobranie klucza API OpenAI
Aby móc korzystać z OpenAI API, musisz posiadać klucz API. Zarejestruj się na stronie OpenAI i wygeneruj klucz API w sekcji API Keys.

Po uzyskaniu klucza API, wklej go w odpowiednie miejsce w skrypcie:

```bash
openai.api_key = 'wstaw_swoj_klucz_API_tutaj'

### 3. Przygotowanie artykułu
Przygotuj artykuł w formacie tekstowym .txt. Możesz użyć dowolnego edytora tekstu do stworzenia tego pliku. Pamiętaj, aby plik był zapisany w formacie UTF-8, aby uniknąć problemów z kodowaniem.

4. Uruchamianie aplikacji w Jupyter Notebooku
Aby uruchomić aplikację, otwórz Jupyter Notebook i wykonaj następujące kroki:

Otwórz nowy notebook lub załaduj istniejący plik .ipynb.
Skopiuj kod aplikacji (zawierający funkcje do wczytywania artykułu, generowania HTML i zapisywania do pliku) do komórek notebooka.
Upewnij się, że zmienna file_path wskazuje na prawidłową lokalizację pliku artykułu na Twoim systemie.
Uruchom komórki kodu.
5. Rezultat
Po uruchomieniu aplikacji, wygenerowany plik HTML zostanie zapisany w tym samym katalogu, w którym znajduje się notebook, pod nazwą artykul.html. Możesz go otworzyć w przeglądarce, aby zobaczyć wynik.
