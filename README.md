# Opiekun Zwierzaka

## Opis
**Opiekun Zwierzaka** to prosty program w języku Python, który symuluje opiekę nad wirtualnym zwierzakiem. Użytkownik nadaje imię swojemu zwierzakowi i może wchodzić z nim w interakcje, takie jak słuchanie, karmienie lub zabawa. Zwierzak ma dwa główne atrybuty: poziom głodu (`hunger`) i znudzenia (`boredom`), które wpływają na jego nastrój. Program działa w konsoli i oferuje prosty interfejs tekstowy.

## Funkcjonalności
- **Tworzenie zwierzaka**: Użytkownik nadaje imię zwierzakowi.
- **Interakcje**:
  - Słuchanie zwierzaka (`talk`): Zwierzak mówi, jak się czuje (nastrój: szczęśliwy, zadowolony, podenerwowany, wściekły).
  - Karmienie zwierzaka (`eat`): Zmniejsza poziom głodu.
  - Zabawa ze zwierzakiem (`play`): Zmniejsza poziom znudzenia.
- **Mechanika czasu**: Każda interakcja zwiększa głód i znudzenie zwierzaka.
- **Prosty interfejs**: Menu tekstowe do wyboru akcji.

## Wymagania
- Python 3.x

## Jak uruchomić
1. Sklonuj repozytorium lub pobierz plik `Opiekun_zwierzaka.py`.
2. Upewnij się, że masz zainstalowanego Pythona 3.x.
3. Uruchom program w terminalu lub konsoli poleceniem:
   ```bash
   python Opiekun_zwierzaka.py
