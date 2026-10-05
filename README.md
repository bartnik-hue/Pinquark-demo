# Pinquark WMS — Interaktywna Prezentacja Multimedialna & Symulator AI

Nowoczesna, w pełni interaktywna prezentacja internetowa systemu **Pinquark WMS** firmy **Meritus S.A.**, łącząca technologie chmurowe, silnik optymalizacji tras AI, pozycjonowanie w czasie rzeczywistym Ultra-Wideband (RTLS) oraz moduł Pinquark Terminal (YMS).

🔗 **Live Demo:** [Otwórz index.html w przeglądarce](index.html)

---

## 🚀 Kluczowe Funkcjonalności

- **Dwa tryby odtwarzania:**
  - 🎬 **Auto-Animacja:** Samodzielny pokaz multimedialny ze zsynchronizowanym lektorem audio (ElevenLabs), paskiem postępu i automatycznym przejściem między slajdami.
  - 🎙️ **Tryb Prezentacyjny:** Samodzielna interakcja ze slajdami, sterowanie klawiaturą, możliwość wejścia w szczegóły techniczne (Deep Dive).
- **Zintegrowany Lektor Audio (ElevenLabs):**
  - Pełna narracja lektorska podzielona na 10 dedykowanych plików audio (`assets/audio/slide_1.mp3` do `slide_10.mp3`).
  - Przycisk włączania / wyciszania lektora w górnym pasku sterowania (`Klawisz M`).
  - Inteligentne wstrzymywanie lektora przy otwarciu okna szczegółów (Deep Dive) i automatyczne wznawianie po zamknięciu.
- **Auto-ukrywanie górnego paska nawigacji:**
  - Pasek sterowania chowa się u góry ekranu, zapewniając 100% immersyjną prezentację.
  - Płynne wysuwanie po zbliżeniu kursora myszy do górnej krawędzi lub najechaniu na uchwyt `▲ STEROWANIE & NAWIGACJA ▼`.
- **Kaskadowe animacje wejścia (Staggered Animations):**
  - Efektowne, sekwencyjne pojawianie się tytułów, kart, zdjęć i parametrów technicznych przy każdej zmianie slajdu.
- **Interaktywny Symulator Magazynu AI (Canvas 2D):**
  - Symulacja na żywo porównująca tradycyjną zbiórkę z algorytmem Pinquark AI (graf czasoprzestrzenny, TSP, omijanie przeszkód z zachowaniem skrajni BHP >2m od regałów).
- **Kalkulator ROI na żywo:**
  - Interaktywne suwaki pracowników i wynagrodzeń wyliczające miesięczne oszczędności i czysty zysk firmy (przy abonamencie 249 PLN/użytkownik).
- **Dwupoziomowa architektura wiedzy (Deep Dive Modal):**
  - Poziom 1: Skrótowa, atrakcyjna wizualnie treść na slajdach.
  - Poziom 2 (`Klawisz D`): Pełna specyfikacja techniczna, hardware, tabele parametrów i zdjęcia w oknie modalnym.

---

## 📑 Struktura Slajdów (10 Rozdziałów)

1. **Wprowadzenie:** Hook, 30 lat doświadczenia Meritus S.A., start w 24h.
2. **3 Filary Platformy:** Stwórz (5 min drag & drop), Zoptymalizuj (silnik AI), Napędzaj (SaaS).
3. **Kreator Low-Code & Mobilność PWA:** Edytor ekranów, aplikacja na terminale Zebra/Honeywell/smartfony, tryb offline.
4. **AI w Akcji — Symulator Magazynu:** Dynamiczna antykolizja, bezpieczna skrajnia korytarzy, -25% długości tras.
5. **Pinquark Navigator:** Wewnętrzny GPS dla magazynu, nawigacja turn-by-turn na terminalu, wdrożenie pracownika w 0 minut.
6. **Inteligentne Czujniki Pinquark UWB:** Hardware RTLS, układy DecaWave DWM1001C, akcelerometr LIS2DH12, TOF 3D <50 cm, heatmaps.
7. **Pinquark Terminal (YMS):** Zarządzanie bramami, kamery OCR tablic i kontenerów, samoobsługowe info-kioski w 30s, wykres Gantta okien czasowych.
8. **Architektura Procesów WMS & Otwarte API REST:** Przyjęcie, składowanie ABC, kompletacja multi-order, wydanie, integracje ERP (SAP, Comarch, Subiekt, Baselinker).
9. **Fakty, Liczby i Case Studies:** Wyniki wdrożeń w H2 Dystrybucja i Laude Smart Intermodal, liderzy branży.
10. **Kalkulator ROI & Podsumowanie:** Subskrypcja 249 PLN/mc, banner wskaźników, darmowe demo.

---

## ⌨️ Skróty Klawiszowe

- `➔` / `Page Down`: Następny slajd
- `←` / `Page Up`: Poprzedni slajd
- `Spacja`: Play / Pauza (Auto-Animacja)
- `M`: Włącz / Wycisz lektora
- `D`: Otwórz / Zamknij szczegóły techniczne (Deep Dive)
- `Esc`: Zamknij okno szczegółów
- `F11`: Pełny ekran

---

## 🛠️ Uruchomienie

Prezentacja nie wymaga instalacji żadnych serwerów ani bibliotek zewnętrznych — wystarczy otworzyć plik `index.html` w dowolnej nowoczesnej przeglądarce (Chrome, Edge, Firefox, Safari).
