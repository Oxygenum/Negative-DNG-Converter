# Negative DNG Converter

**Negative DNG Converter** to desktopowa aplikacja dla fotografów analogowych, służąca do wywoływania cyfrowych skanów negatywów zapisanych w formacie DNG. Program działa na Windows i oferuje pełny 16‑bitowy pipeline obróbki, w tym automatyczne usuwanie maski filmu oraz prosty HDR z trzech ekspozycji.

## Najważniejsze funkcje

- Konwersja negatywów DNG do JPG (8‑bit) oraz 16‑bit TIFF z pełną 16‑bitową obróbką (inwersja, korekcje, wyostrzanie).
- Automatyczne wykrywanie i usuwanie kolorowej maski filmu (pomarańcz, żółty, niebieski itd.) z możliwością ręcznej regulacji składowych BLUE/GREEN/RED.
- Regulacja ekspozycji, kontrastu, gęstości/jasności i nasycenia, zaprojektowana z myślą o negatywach.
- Auto balans bieli na podstawie środkowego obszaru kadru oraz opcjonalne auto‑crop usuwające czarne/puste brzegi skanu.
- Regulacja kolorów CMY (Cyan/Magenta/Yellow) przez bezpośrednią kontrolę kanałów RGB.
- Tryb „AI‑cast removal” – automatyczne usuwanie globalnego zafarbienia.
- Kilka poziomów wyostrzania (Brak, Niskie, Średnie, Wysokie) z maską wyostrzającą w 16‑bitach i ochroną świateł przed zafarbem.
- Prosty HDR 16‑bit z trzech plików DNG (‑2 / 0 / +2 EV) z wyrównaniem rozmiaru i fuzją ekspozycji.
- System presetów: zapis i odczyt ustawień do/z plików JSON, wygodny przy seryjnej obróbce rolek.

## Wersje programu

- **Wersja testowa (Trial)** – pełna funkcjonalność, ale każdy eksport JPG/TIFF zawiera półprzezroczysty watermark „Negative DNG Converter” na całym kadrze.
- **Wersja pełna** – brak watermarka, licencja 1 użytkownik / 2 komputery, możliwość komercyjnego użycia programu zgodnie z EULA.

Linki do pobrania wersji trial i zakupu pełnej wersji znajdziesz na stronie projektu (GitHub Pages) oraz w sekcji Releases.

## Wymagania systemowe

- System: Windows 10 / 11 (64‑bit).
- RAM: minimum 8 GB, zalecane 16 GB dla dużych plików DNG.
- Wymagane aktualne sterowniki GPU oraz biblioteki MSVC / .NET, jeśli instalator o to poprosi.

## Jak używać

1. Zainstaluj program z przygotowanego instalatora (EXE).
2. Uruchom **Negative DNG Converter** z menu Start lub skrótu na pulpicie.
3. Wybierz **Otwórz plik DNG** lub **Wywołaj HDR (3xDNG)** z menu „Plik”.
4. Skorzystaj z suwaków ekspozycji, kontrastu, gęstości, nasycenia, sekcji CMY oraz narzędzi maski i wyostrzania, aby dopasować obraz.
5. Zapisz swoje ustawienia jako preset (JSON), aby szybko odtworzyć je przy kolejnych rolkach.
6. Wyeksportuj finalny obraz do JPG lub 16‑bit TIFF.

## Licencja

Kod źródłowy w tym repozytorium służy głównie do prezentacji działania programu i nie jest udostępniany na licencji open‑source.  
Korzystanie z programu (trial / pełna wersja) regulują osobne pliki EULA dołączone do instalatora (EULA_Trial, EULA_Full).
