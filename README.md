# Zadanie rekrutacyjne dla programisty front-endu

TL;DR: Stwórz prosty kreator CV z opcją eksportu danych w JSONie.

## Wymagania biznesowe

- Kreator powinien umożliwiać dodanie/edycję/usuwanie w CV poniższych rubryk:
  - Pełne imię oraz nazwisko
  - Zdjęcie
  - Email
  - Numer telefonu
  - Historia zatrudnienia (najnowsze na górze)
    - Nazwa firmy (tekst)
    - Pozycja w firmie (tekst)
    - Adres strony (tekst)
    - Data rozpoczęcia zatrudnienia (data)
    - Data zakończenia zatrudnienia (z opcją że kandydat wciąż tam pracuje) (data)
    - Opis (highlights) tego co kandydat w danej pracy robił - dowolnej długości (tekst)
  - Historia edukacji (najnowsze na górze)
    - Nazwa instytucji (tekst)
    - Kierunek studiow (tekst)
    - Poziom studiow (tekst)
    - Data rozpoczęcia (data)
    - Data zakończenia (z opcją że wciąż studiuje) (data)
  - Umiejętnosci
    - Nazwa skilla (tekst)
    - Poziom - od 1 do 3 gwiazek (integer)  
- Rzeczy wpisane do kreatora powinny być zapisywane gdzieś (lokalnie, chmura, firebase) po to aby przy następnym uruchomieniu nie trzeba bylo ich wpisywać od nowa

## Wymagania techniczne

- Rozwiązanie powinno zostać dostarczone jako kompletny projekt repozytorium git możliwego do sklonowania (odeślij mi adres repo na githubie)
- Rozwiązanie powinno zostać wykonane w technologii na jaką aplikowano w ogłoszeniu o pracę
- Rozwiązanie powinno eksportować poprawny plik wg. formatu [JSON RESUME](https://jsonresume.org/schema/)
