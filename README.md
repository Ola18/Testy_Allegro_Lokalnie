# Testy_Allegro_Lokalnie
Testowanie funkcjonalności Obserwowanie ofert z Allegro Lokalnie.

Testy zostały zaprojektowane tak, aby pokryć wymagania jakie powinna spełniać testowana funkcjnalność. 
Analizy wymagań dokonano na podstawie instrukcji dla użytkownika (https://allegro.pl/pomoc/dla-kupujacych/wyszukiwanie-i-obserwowanie/jak-obserwowac-wybrane-oferty-VEB4ORgOkFl). 
Przetestowano stronę internetową oraz aplikację mobilną pobraną na urządzenie typu smartphone Samsung Galaxy J5 z systemem Android 9.
Przypadki testowe opisano w arkuszu Excel, do większości dołączono zrzut ekranu.

Oprócz błędów, na które wskazują przypadki testowe oznaczone jako niezaliczone, w trakcie testowania zauważono kilka niespójności, które opisano poniżej.

Aplikacja mobilna nie posiada poniższych funkcji:
  1. Filtrowanie według kategorii.
  2. Licznik ofert trwających i zakończonych.
  3. Wyszukiwanie ofert po tytule, nazwy sprzedawcy, notatce.
  4. Ustawienia dot. powiadomienia mailowego.
  5. Opcja Zaznacz wszystkie.
  6. Udostępnianie ofert.

Instrukcja dla użytkownika wskazuje tylko na brak możliwości dodawania notatki w mobilnej wersji Allegro.
  
Testy wykazały również niespójność między ofertami obserwowanymi w aplkacji mobilnej i na stronie internetowej. 
Oferty na stronie internetowej wystawione z opcją kup teraz lub darmowe zawierają informację: do wyczerpania przedmiotów (zrzut ekranu AL_001).
W aplikacji mobilnej przy tego typu ogłoszeniach pojawia się data, której nie ma na stronie oferty (zrzut ekranu AL_002).
