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
