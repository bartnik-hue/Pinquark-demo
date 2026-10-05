# Instrukcja obsługi: Prezentacja Interaktywna Pinquark WMS

## 🚀 Jak uruchomić prezentację?

Wystarczy **dwukrotnie kliknąć plik `index.html`** znajdujący się w tym katalogu:
`d:\PRACA\SMOCZNY\pinquark prezenetacja\index.html`

Otworzy się on natychmiast w Twojej domyślnej przeglądarce internetowej (Google Chrome, Microsoft Edge, Firefox, Safari itp.). **Działa w 100% offline**, bez potrzeby instalowania jakichkolwiek serwerów czy programów.

---

## 🎙️ Skrypt dla lektora

W pliku [skrypt_lektora.txt](file:///d:/PRACA/SMOCZNY/pinquark%20prezenetacja/skrypt_lektora.txt) znajduje się kompletny tekst do nagrania lektorskiego lub wygenerowania mowy przez AI (np. ElevenLabs):
* Podzielony precyzyjnie na każdy z 8 slajdów,
* Czas trwania dopasowany do trybu auto-animacji (ok. 12–15 sekund na slajd),
* Łączny czas całego pokazu: ok. 1 min 50 s.

---

## 🎮 Dwa tryby odtwarzania

W górnym pasku sterowania znajduje się przełącznik trybów:

### 1. 🎬 Tryb Automatyczny (Auto-Animacja / Kiosk)
* Działa jak **dynamiczne wideo / animowany showcase**.
* Samodzielnie przenosi widza przez kolejne etapy prezentacji (pasek postępu u góry odlicza czas slajdu).
* Na slajdzie symulatora automatycznie odpala demonstrację algorytmu AI.
* **Klawisz Spacja:** W dowolnym momencie możesz zapauzować animację, aby skomentować slajd, i wznowić kolejnym naciśnięciem.

### 2. 🎙️ Tryb Prezentacyjny (Spotkanie z Klientem / Ręczny)
* Pełna kontrola w Twoich rękach.
* Przełączanie slajdów:
  * Strzałkami na klawiaturze: `[ ← ]` oraz `[ → ]` (lub `PageUp` / `PageDown`),
  * Klikaniem w kropki nawigacyjne na dole ekranu,
  * Klikaniem w strzałki `◀` `▶` w prawym dolnym rogu.
* W tym trybie możesz wchodzić w pełną interakcję z modułami na żywo:
  * **Slajd 4 (Symulator AI w magazynie):**
    * Przyciski: *„Tradycyjny (Chaos + Zator)”* oraz *„Pinquark AI + UWB”*.
    * Rzeczywisty rzut magazynu: ścieżki prowadzą **wyłącznie korytarzami roboczymi** (żadna linia nie przechodzi przez regały).
    * Widoczne przeszkody: zator (odstawiona paleta w alejce) oraz 2 ruchome wózki widłowe w korytarzach poprzecznych.
    * W trybie tradycyjnym magazynier trafia na zablokowaną alejkę, cofa się i wjeżdża na kurs kolizyjny z wózkiem widłowym. W trybie AI algorytm omija zator i bezpiecznie mija wózki.
  * **Slajd 8 (Kalkulator ROI):** Przesuwaj suwaki liczby magazynierów i pensji, by wyliczyć oszczędności bezpośrednio pod magazyn klienta.

---

## 🔍 Poziom 2: Przycisk „Deep Dive” (Pełne dane techniczne)

Prezentacja wykorzystuje **pełną szerokość ekranu** z elegancką, technologiczną ramką.
Jeśli klient na spotkaniu zada szczegółowe pytanie techniczne:
* Kliknij przycisk **„🔍 Pokaż szczegóły (Deep Dive)”** lub wciśnij klawisz **`[ D ]`**.
* Na środku ekranu pojawi się wyśrodkowane okno modalne ze szklanym tłem zawierające pełną specyfikację (modele matematyczne 4D PRM, Dijkstra, Redis, parametry czujników UWB, 12 procesów magazynowych, opisy wdrożeń).
* Klawisz **`[ Esc ]`** lub kliknięcie w tło natychmiast zamyka okno.

---

## ⌨️ Skróty klawiszowe

| Klawisz | Akcja |
| :--- | :--- |
| `→` / `PageDown` | Następny slajd |
| `←` / `PageUp` | Poprzedni slajd |
| `Spacja` | Start / Pauza animacji automatycznej |
| `M` | Włącz / Wycisz lektora (Mute Audio) |
| `D` | Otwórz / Zamknij szczegóły (Deep Dive) |
| `Esc` | Zamknij okno szczegółów |
| `F11` (lub ikona ⛶) | Pełny ekran (rekomendowany na spotkaniach) |

---

## 🔊 Zintegrowany Lektor (Audio Voiceover)
W prezentacji zaimplementowano pełne wsparcie dla profesjonalnego lektora:
* Plik audio został precyzyjnie podzielony na 8 plików odpowiadających każdemu ze slajdów i umieszczony w katalogu `assets/audio/`.
* W górnym pasku sterowania znajduje się dedykowany przycisk **`🔊 Lektor: WŁ / 🔇 WYŁ`** (skrót `[M]`).
* W trybie **Auto-Animacja** slajdy automatycznie synchronizują czas trwania z tempem czytania lektora – po zakończeniu kwestii lektora prezentacja płynnie przechodzi do kolejnego slajdu.
* W trybie **Prezentacyjnym** lektor może czytać treść każdego slajdu lub zostać wyciszony jednym kliknięciem podczas Twojego własnego wystąpienia na żywo.
