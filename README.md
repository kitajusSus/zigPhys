# ZigPhys - Architektura i specyfikacja
ZigPhys to środowisko obliczeniowe dla fizyków napisane w języku Zig. Łączy w sobie funkcjonalność podobną do GNU Octave/MATLAB, ale z dodatkowymi bibliotekami i narzędziami zaprojektowanymi specyficznie dla zastosowań fizycznych.
# 2. Główne komponenty interfejsu użytkownik
## 2.1. Konsola interaktywna (REPL)

- Interaktywna konsola z historią poleceń
- Kolorowanie składni
- Autouzupełnianie typów fizycznych, jednostek i funkcji
- Bezpośredni dostęp do pomocy kontekstowej
- Wsparcie dla wielu wątków obliczeń

## 2.2. Edytor skryptów

- Edytor z kartami do zarządzania wieloma plikami
- Kolorowanie składni Zig z dodatkowymi elementami specyficznymi dla fizyki
- Debugger z wizualizacją zmiennych
- Automatyczne formatowanie kodu

## 2.3. System wizualizacji

- Wykresy 2D i 3D
- Wykresy wektorowe i pól
- Wizualizacje układów fizycznych
- Animacje procesów dynamicznych
- Eksport do różnych formatów (PNG, SVG, GIF, MP4)

## 2.4. Menedżer projektów

- Organizacja pracy w projekty
- Moduły do różnych dziedzin fizyki
- Zapisywanie i wczytywanie stanu obliczeń
- Zarządzanie zależnościami

## 2.5. Panel informacyjny
- informacje o błędach.
Lista aktywnych zmiennych
Informacje o typach i jednostkach
Podgląd wyników i metadanych
Monitor wykorzystania zasobów
