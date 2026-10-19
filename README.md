# Mazhi Panel

## Cel aplikacji

Własny panel integracyjny rozwijany na potrzeby obsługi
danych i ustawień sprzedaży własnego konta Allegro.

Repozytorium zawiera wyłącznie publiczną dokumentację
aplikacji. Nie zawiera kodu źródłowego panelu,
danych dostępowych ani tokenów OAuth.

## Środowiska

### Sandbox

Środowisko służące do testowania integracji.

Zarejestrowana aplikacja: Mazhi Panel Sandbox v2.

### Produkcja

Przygotowywana integracja z własnym kontem produkcyjnym.
Na obecnym etapie dostęp ograniczony jest do odczytu:
- danych konta w celu identyfikacji połączenia;
- ustawień sprzedaży: warunków zwrotów, gwarancji,
  reklamacji oraz cenników dostaw.

Operacje zmieniające dane w Allegro są blokowane
przez backend panelu.

Zarejestrowana aplikacja: [dokładna nazwa aplikacji produkcyjnej].

## Autoryzacja

Panel wykorzystuje OAuth 2.0 Authorization Code.

Zakresy używane przez obecną integrację:
- allegro:api:profile:read
- allegro:api:sale:settings:read

## Opiekun i kontakt


Projekt utrzymuje: Mazzhi
Kontakt: Mazzhi
