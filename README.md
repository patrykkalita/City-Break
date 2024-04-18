## Instrukcja obsługi
- Pobieramy folder z plikami projektu
  - W pliku .env wprowadzamy własny klucz api dla OpenAI
- W terminalu, przechodzimy do lokalizacji w której mamy folder z projektem
- Za pomocą poniższej komendy budujemy obraz Docker
```console
docker build -t cities .
```
- Następnie uruchamiamy zbudowany obraz
```console
docker run -p 8501:8501 cities
```
- W przeglądarce uruchamiamy aplikację pod zdefiniowanym wcześniej portem
- Wyświetla nam się chatbot z którym możemy rozmawiać
