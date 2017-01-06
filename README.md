# Dokumentacja do odtwarzacza Radia Anime24 na androidzie

## Wersja Oprogramowania
## Wstęp 
## Wymagania 
### Wymagania Funkcjonalne
**Wymaganie 1.1 - Odtwarzacz**
> Moduł odtwarzacz musi posiadać takie funcjonalności jak:
- przycisk do stopowania/startowania odtwarzania radia
- w trakcie rozmowy telefonicznej muzyka jest wyciszana do zera
- muzyka jest odtwarzana w czasie rzeczywistym 
- wyświetlanie kto prowadzi audycje 
- wyświetlanie tytułu audycji
- możliwość wyświetlenia ilości słuchaczy na audycji

**Wymaganie 1.2 - Pozdrowienia**
> Moduł pozdrowień posiada:
- pole typu textarea do pozdrowień
* pole pozdrowień posiada walidowanie co do dlugości słów: maksymalna ilość znaków to 999
* pole pozdrowień nie może być puste przed wyłaniem (spacje tez musza być obslużone)
- Pole Nick
* pole Nick posiada walidowanie co do dlugości słów: maksymalna ilość znaków to 100
* pole Nick nie może być puste przed wyłaniem (spacje tez musza być obslużone)
- Przycisk wyślij
* Jeżeli pozdrowienie jest wysłane, przycisk zostaje wyłączony na 10 sekund

**Wymaganie 1.3 - Ramówka**
> Modół ramówka działa następująco:
- pobiera listę audycji, zaraz po uruchomieniu aplikacji
- odświerzanie ramówki jest co 40 minut
- przy przełączeniu na modłu ramówka, ona nie pobiera informacji o audycjach
- (Nowość) możliwość zaznaczenia audycji i właczenie przypomnienia

**Wymaganie 1.4 - Top Lista**
> Moduł top lista posiada:
- listę utworów
- każdy utwór posiada przyciśk, który umożliwia głosowanie
- pole z możliwością dodania piosenki do top listy

**Wymaganie 1.5 - Ustawienia**
>  Moduł Ustawienia posiada takie opcje jak:
- Wybór odświerzania informacji o audycji (możliwe kombinacje to: 1 min, 2 min, 3 min, 5 min, 10 min)
- checkbox liczba słuchaczy
- (Nowość) wybór skórki



### Wymagania niefunkcjonalne 
#### Dostepność
#### Modyfikowalność
#### Bezpieczeństwo
#### Twstowalność
## Architektura i użyte technologie
## Praca przy projekcie
### Wersjonowanie
### Praca z branchami
### Podział obowiązków
### Sposób i analiza pokrycia testami funcjonalności aplikacji

