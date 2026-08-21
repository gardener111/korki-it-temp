# Korepetycje Informatyka
Notatki, zagadnienia do korepetycji z informatyki - Kl. 2L

---

## Zakres

Materiał obejmuje zagadnienia z dwóch arkuszy:

1. Budowa komputera i urządzenia zewnętrzne
2. Systemy operacyjne
3. Sieci komputerowe
4. Drzewo folderów i operacje na plikach
5. Witryna WWW / HTML
6. Edycja tekstu
7. Równania matematyczne w edytorze tekstu

---

# 1. Budowa komputera i urządzenia zewnętrzne

## 1.1. BIOS

### Definicja

**BIOS** (Basic Input/Output System) to podstawowe oprogramowanie znajdujące się na płycie głównej komputera, które uruchamia się jako jedno z pierwszych po włączeniu komputera.

### Po ludzku

Po naciśnięciu przycisku zasilania komputer musi najpierw sprawdzić podstawowe elementy sprzętu, np. RAM, procesor i dyski, a następnie znaleźć system operacyjny. Za początkowy etap odpowiada BIOS lub jego współczesny następca — **UEFI**.

BIOS nie jest systemem operacyjnym.

Schemat:

**BIOS/UEFI → uruchamia i przygotowuje komputer → Windows/Linux → przejmuje komputer**

### Przykład

Po włączeniu komputera można nacisnąć np. `Delete`, `F2`, `F10`, `F12` lub `Esc`, aby wejść do ustawień BIOS/UEFI. Można tam np. ustawić kolejność urządzeń, z których komputer próbuje się uruchomić.

---

## 1.2. RAM

### Definicja

**RAM** (Random Access Memory) to pamięć operacyjna komputera, która przechowuje dane potrzebne aktualnie uruchomionym programom.

### Po ludzku

RAM można porównać do **biurka**:

- dysk → szafa,
- RAM → biurko,
- procesor → człowiek pracujący przy biurku.

Im większe biurko, tym więcej rzeczy można mieć jednocześnie pod ręką.

### Przykład

Komputer ma 16 GB RAM i uruchomione są jednocześnie Chrome, Spotify, Discord i Word. Każdy program wykorzystuje część pamięci RAM.

### Ważne

RAM jest pamięcią **ulotną**.

Po wyłączeniu komputera zawartość RAM zostaje utracona.

---

## 1.3. ROM

### Definicja

**ROM** (Read Only Memory) to pamięć przeznaczona do przechowywania danych, które nie powinny być normalnie zmieniane podczas zwykłej pracy komputera.

### Po ludzku

Można wyobrazić ją sobie jako instrukcję zapisaną na stałe.

Współczesne komputery stosują różne rodzaje pamięci flash do przechowywania firmware'u, np. UEFI.

### Do zapamiętania

- **RAM** → pamięć robocza, szybka, zawartość znika po wyłączeniu.
- **ROM** → pamięć przeznaczona do trwałego przechowywania określonych danych/oprogramowania.

---

## 1.4. Pamięć operacyjna

Najprościej:

**pamięć operacyjna = RAM**

Przykłady:

- 4 GB RAM
- 8 GB RAM
- 16 GB RAM
- 32 GB RAM

Nie należy jej mylić z SSD, HDD ani pendrivem.

| Element | Do czego służy? |
|---|---|
| RAM | Tymczasowa praca programów |
| SSD/HDD | Długotrwałe przechowywanie plików |
| CPU | Wykonywanie obliczeń |
| GPU | Przetwarzanie grafiki |
| BIOS/UEFI | Uruchomienie i konfiguracja sprzętu |

---

## 1.5. Urządzenia zewnętrzne

### Urządzenia wejścia

Urządzenia wejścia służą do **wprowadzania informacji do komputera**.

Czyli:

**człowiek → komputer**

Przykłady:

- klawiatura,
- mysz,
- mikrofon,
- skaner,
- kamera internetowa,
- tablet graficzny.

### Urządzenia wyjścia

Urządzenia wyjścia przekazują informacje **z komputera do użytkownika**.

Czyli:

**komputer → człowiek**

Przykłady:

- monitor,
- drukarka,
- głośniki,
- słuchawki,
- projektor.

### Urządzenia wejścia-wyjścia

Mogą zarówno odbierać, jak i wysyłać informacje.

Przykład: **ekran dotykowy**.

- dotyk → człowiek → komputer,
- obraz → komputer → człowiek.

Inne przykłady:

- karta sieciowa,
- modem,
- urządzenie wielofunkcyjne.

### Jednostki pamięci

Służą do przechowywania danych:

- SSD,
- HDD,
- pendrive,
- karta pamięci,
- zewnętrzny dysk.

### Jednostki pojemności

**bit → bajt → KB → MB → GB → TB**

Najważniejsze:

**1 bajt = 8 bitów**

---

## 1.6. Kompatybilność

### Definicja

**Kompatybilność** oznacza możliwość prawidłowej współpracy dwóch elementów.

### Po ludzku

Jeśli program jest kompatybilny z komputerem, oznacza to, że można go na nim uruchomić i działa prawidłowo.

### Przykład

Program wymaga:

- Windows 11,
- procesora x64,
- 8 GB RAM.

Komputer ma:

- Windows 11,
- procesor x64,
- 16 GB RAM.

Program jest kompatybilny.

---

## 1.7. Multimedia

### Definicja

**Multimedia** oznaczają wykorzystanie wielu rodzajów informacji jednocześnie.

Np.:

- tekst,
- obraz,
- dźwięk,
- animacja,
- film.

### Przykład

YouTube wykorzystuje multimedia: obraz, dźwięk, tekst i animacje.

---

# 2. Systemy operacyjne

## 2.1. System operacyjny

### Definicja

**System operacyjny (OS — Operating System)** to podstawowe oprogramowanie zarządzające komputerem i umożliwiające użytkownikowi korzystanie ze sprzętu oraz uruchamianie programów.

### Przykłady

- Windows
- Linux
- macOS
- Android
- iOS

### Po ludzku

System operacyjny jest **pośrednikiem między użytkownikiem, programami i sprzętem**.

Przykład:

Klikasz ikonę Chrome. Chrome potrzebuje procesora, RAM-u, dysku, karty sieciowej i ekranu. System operacyjny pomaga programowi korzystać z tych urządzeń.

---

## 2.2. System jednozadaniowy

### Definicja

System jednozadaniowy pozwala na wykonywanie **jednego zadania w danym momencie**.

Schemat:

**zadanie A → zadanie B → zadanie C**

---

## 2.3. System wielozadaniowy

### Definicja

System wielozadaniowy pozwala na wykonywanie wielu programów/zadań w tym samym czasie.

Przykład:

- Spotify,
- Word,
- Chrome,
- Discord,
- pobieranie pliku

mogą działać jednocześnie.

System szybko przełącza procesor między zadaniami, dzięki czemu użytkownik ma wrażenie równoczesnej pracy.

---

## 2.4. System wielodostępowy

### Definicja

System wielodostępowy pozwala wielu użytkownikom korzystać z tego samego systemu komputerowego, często jednocześnie.

Przykład:

Jeden serwer Linux może mieć konta użytkowników:

- Jan,
- Adam,
- Kasia.

Każdy może mieć własne pliki, konto i uprawnienia.

---

## 2.5. System czasu rzeczywistego

### Definicja

**System czasu rzeczywistego** to system, w którym bardzo ważne jest wykonanie określonej operacji w wymaganym czasie.

Nie chodzi tylko o to, żeby odpowiedź była szybka. Odpowiedź musi nastąpić w odpowiednim czasie.

### Przykłady

- system ABS samochodu,
- system sterowania samolotem,
- robot przemysłowy,
- aparatura medyczna.

---

# 3. Sieci komputerowe

## 3.1. Sieć komputerowa

### Definicja

**Sieć komputerowa** to połączone ze sobą urządzenia, które mogą wymieniać dane i korzystać ze wspólnych zasobów.

### Przykład

W domu komputer, telefon, telewizor i drukarka mogą być podłączone do tego samego routera.

---

## 3.2. Rodzaje sieci

### PAN

**Personal Area Network** — sieć osobista.

Przykład:

telefon ↔ smartwatch przez Bluetooth.

### LAN

**Local Area Network** — sieć lokalna.

Przykład: sieć w domu, szkole lub biurze.

### MAN

**Metropolitan Area Network** — sieć obejmująca większy obszar, np. część lub całe miasto.

### WAN

**Wide Area Network** — sieć rozległa.

Przykład: Internet.

### Do zapamiętania

**PAN → osobista**

**LAN → lokalna**

**MAN → miejska**

**WAN → rozległa**

---

## 3.3. Topologia fizyczna sieci

### Definicja

**Topologia sieci** opisuje sposób połączenia urządzeń w sieci.

Najważniejsze:

- magistrala,
- gwiazda,
- pierścień,
- siatka,
- drzewo.

### Magistrala

Wszystkie urządzenia są podłączone do jednego wspólnego przewodu.

```text
PC ─── PC ─── PC ─── PC
```

Awaria głównego przewodu może wpłynąć na całą sieć.

### Gwiazda

Wszystkie urządzenia są podłączone do centralnego urządzenia.

```text
       PC
        |
PC ── SWITCH ── PC
        |
       PC
```

Jest bardzo popularna we współczesnych sieciach.

### Pierścień

Urządzenia tworzą zamknięty obwód.

```text
PC ─ PC
|     |
PC ─ PC
```

### Siatka

Urządzenia mają wiele połączeń między sobą.

Zaletą jest możliwość znalezienia innej drogi, gdy jedno połączenie przestanie działać.

### Drzewo

Połączenia mają strukturę hierarchiczną.

```text
        SWITCH
        /    \
    SWITCH   SWITCH
    /   \     /   \
   PC   PC   PC   PC
```

---

## 3.4. Wady i zalety sieci

### Zalety

- udostępnianie plików,
- udostępnianie drukarki,
- wspólne połączenie internetowe,
- komunikacja,
- współpraca.

### Wady

- ryzyko problemów z bezpieczeństwem,
- awaria sieci może odciąć wiele urządzeń,
- możliwość rozprzestrzeniania malware,
- koszty sprzętu i utrzymania.

---

## 3.5. Sieć peer-to-peer

### Definicja

**Peer-to-peer (P2P)** to sieć, w której komputery mogą bezpośrednio udostępniać sobie zasoby. Nie ma jednego centralnego serwera odpowiedzialnego za wszystko.

```text
PC A ←→ PC B
 ↕       ↕
PC C ←→ PC D
```

### Zalety

- prostota,
- niski koszt,
- brak konieczności posiadania centralnego serwera.

### Wady

- trudniejsze zarządzanie przy dużej liczbie komputerów,
- problemy z bezpieczeństwem,
- trudniejsze tworzenie kopii zapasowych.

---

## 3.6. Sieć z wydzielonym serwerem

### Definicja

Istnieje **serwer**, który udostępnia usługi innym komputerom — klientom.

```text
        SERWER
       /  |  \
      /   |   \
    PC    PC    PC
```

Serwer może przechowywać:

- pliki,
- konta użytkowników,
- strony WWW,
- bazy danych,
- kopie zapasowe.

### Zaleta

Centralne zarządzanie.

---

# 4. Drzewo folderów

## 4.1. Plik

### Definicja

**Plik** to zbiór danych zapisanych pod określoną nazwą w pamięci komputera.

Przykłady:

```text
zdjecie.jpg
praca.docx
muzyka.mp3
film.mp4
notatki.txt
strona.html
```

---

## 4.2. Folder

### Definicja

**Folder** to miejsce służące do organizowania plików i innych folderów.

Przykład:

```text
Dokumenty
├── Szkoła
│   ├── Matematyka
│   ├── Polski
│   └── Informatyka
└── Prywatne
    ├── Zdjęcia
    └── Dokumenty
```

---

## 4.3. Podfolder

### Definicja

**Podfolder** to folder znajdujący się wewnątrz innego folderu.

Przykład:

```text
Szkoła
└── Informatyka
```

`Informatyka` jest podfolderem `Szkoła`.

---

## 4.4. Ścieżka dostępu

### Definicja

**Ścieżka dostępu** określa, gdzie znajduje się konkretny plik lub folder.

### Windows

```text
C:\Users\Jan\Documents\Szkoła\Informatyka\zadanie.docx
```

Czytamy:

dysk C → Users → Jan → Documents → Szkoła → Informatyka → zadanie.docx

### Linux

```text
/home/jan/szkola/informatyka/zadanie.txt
```

---

## 4.5. Kopiowanie

### Definicja

**Kopiowanie** tworzy drugą wersję pliku. Oryginał pozostaje na swoim miejscu.

Skróty:

**Ctrl + C** → kopiuj

**Ctrl + V** → wklej

Po skopiowaniu mogą istnieć dwie wersje pliku.

---

## 4.6. Przenoszenie

### Definicja

**Przenoszenie** oznacza zmianę miejsca pliku.

Skróty:

**Ctrl + X** → wytnij

**Ctrl + V** → wklej

### Różnica

**Kopiowanie:** stary + nowy

**Przenoszenie:** stary → nowy

---

# 5. Witryna WWW / HTML

## 5.1. HTML

### Definicja

**HTML (HyperText Markup Language)** to język znaczników służący do tworzenia struktury stron internetowych.

HTML nie jest klasycznym językiem programowania.

Opisuje, co znajduje się na stronie:

- nagłówek,
- tekst,
- obraz,
- link,
- tabela itd.

---

## 5.2. Podstawowa struktura HTML

```html
<!DOCTYPE html>
<html>
<head>
    <title>Moja strona</title>
</head>

<body>
    <h1>Witaj!</h1>
    <p>To jest moja pierwsza strona.</p>
</body>

</html>
```

Schemat:

```text
HTML
├── HEAD
│   └── informacje o stronie
└── BODY
    └── zawartość widoczna na stronie
```

---

## 5.3. `html`

```html
<html>
</html>
```

Określa początek i koniec dokumentu HTML.

---

## 5.4. `head`

```html
<head>
</head>
```

Zawiera informacje dotyczące dokumentu.

---

## 5.5. `title`

```html
<title>Moja strona</title>
```

Określa tytuł strony widoczny np. na karcie przeglądarki.

---

## 5.6. `body`

```html
<body>
</body>
```

Zawiera właściwą treść strony.

---

## 5.7. Znaczniki pojedyncze i podwójne

### Podwójny

Ma otwarcie i zamknięcie:

```html
<p>To jest tekst.</p>
```

### Pojedynczy

Nie wymaga klasycznego zamknięcia:

```html
<br>
```

Przejście do nowej linii.

```html
<img src="kot.jpg">
```

Wstawienie obrazu.

---

## 5.8. Nagłówki

HTML ma nagłówki od `h1` do `h6`.

```html
<h1>Najważniejszy nagłówek</h1>
<h2>Drugi poziom</h2>
<h3>Trzeci poziom</h3>
```

`h1` jest najważniejszym poziomem.

---

## 5.9. Akapit

```html
<p>To jest akapit tekstu.</p>
```

`p` = paragraph.

---

## 5.10. Kolor i tło

W prostych zadaniach szkolnych można spotkać:

```html
<body bgcolor="yellow">
```

albo współcześnie:

```html
<body style="background-color: yellow;">
```

Kolor tekstu:

```html
<p style="color: red;">Czerwony tekst</p>
```

---

## 5.11. Kolor, rozmiar i styl tekstu

```html
<p style="color: blue; font-size: 20px;">
    Niebieski tekst.
</p>
```

- `color` → kolor,
- `font-size` → rozmiar.

Pogrubienie:

```html
font-weight: bold;
```

---

## 5.12. Hiperłącze

### Definicja

**Hiperłącze** to element, który pozwala przejść do innej strony, dokumentu lub miejsca.

Przykład:

```html
<a href="https://www.google.com">Google</a>
```

- `a` = anchor,
- `href` = adres, do którego prowadzi link.

---

## 5.13. Ścieżki dostępu do plików w HTML

Załóżmy:

```text
strona
├── index.html
└── obrazki
    └── kot.jpg
```

W `index.html`:

```html
<img src="obrazki/kot.jpg">
```

Oznacza to:

obecny folder → `obrazki` → `kot.jpg`.

### Ścieżka względna

```html
<img src="obrazki/kot.jpg">
```

Adres jest podany względem miejsca, w którym znajduje się obecny plik HTML.

### Jeden folder wyżej

```text
..
```

Przykład:

```html
<img src="../kot.jpg">
```

`..` oznacza przejście o jeden folder wyżej.

---

# 6. Edycja tekstu

Najczęściej chodzi o Microsoft Word lub LibreOffice Writer.

## 6.1. Marginesy

### Definicja

**Margines** to pusta przestrzeń pomiędzy krawędzią strony a właściwą treścią dokumentu.

W Wordzie:

**Układ → Marginesy**

Można wybrać:

- normalne,
- wąskie,
- szerokie,
- własne.

---

## 6.2. Blokowy układ tekstu

Tekst organizuje się w bloki/akapity.

```text
TYTUŁ

Pierwszy akapit.

Drugi akapit.

Trzeci akapit.
```

W Wordzie:

**Enter** → nowy akapit

**Shift + Enter** → nowa linia w tym samym akapicie

---

## 6.3. Automatyczny numer strony

W Wordzie:

**Wstawianie → Numer strony**

Można umieścić numer np. na górze lub dole strony.

Automatyczna numeracja pozwala Wordowi samodzielnie numerować strony.

---

## 6.4. Automatyczna data i godzina

W Wordzie:

**Wstawianie → Data i godzina**

Można wybrać np.:

`21.08.2026`

albo:

`21 sierpnia 2026`

---

## 6.5. Style tekstu

### Definicja

**Styl** to gotowy zestaw ustawień formatowania tekstu.

Przykład:

**Nagłówek 1**

może automatycznie ustawić większą czcionkę, pogrubienie i odpowiednie odstępy.

Ważne jest używanie stylów zamiast ręcznego formatowania każdego nagłówka.

---

## 6.6. Automatyczny spis treści

Spis treści wykorzystuje style nagłówków.

Przykład struktury:

```text
1. Wstęp
2. Budowa komputera
   2.1 Procesor
   2.2 RAM
3. Sieci
```

Jeśli nagłówki zostaną oznaczone jako:

- `Wstęp` → Nagłówek 1
- `Budowa komputera` → Nagłówek 1
- `Procesor` → Nagłówek 2
- `RAM` → Nagłówek 2
- `Sieci` → Nagłówek 1

Word może automatycznie wygenerować spis treści.

W Wordzie:

**Odwołania → Spis treści → Automatyczny spis treści**

---

## 6.7. Tabulatory

### Definicja

**Tabulator** pozwala ustawić tekst w określonych miejscach w wierszu.

Przykład:

```text
Imię        Nazwisko       Wiek
Jan         Kowalski       16
Adam        Nowak          15
```

Klawisz:

**Tab**

Nie należy wyrównywać kolumn za pomocą dużej liczby spacji.

Do tego służą tabulatory albo tabele.

---

## 6.8. Listy punktowane

Przykład:

- komputer,
- monitor,
- klawiatura,
- mysz.

W Wordzie:

**Narzędzia główne → Punktory**

---

## 6.9. Listy numerowane

Przykład:

1. Włącz komputer.
2. Uruchom Word.
3. Utwórz dokument.
4. Zapisz plik.

W Wordzie:

**Narzędzia główne → Numerowanie**

---

## 6.10. Listy wielopoziomowe

Przykład:

```text
1. Komputer
   1.1 Procesor
   1.2 RAM
       1.2.1 Rodzaje RAM
       1.2.2 Pojemność RAM
2. Sieci
   2.1 LAN
   2.2 WAN
```

W Wordzie:

**Narzędzia główne → Lista wielopoziomowa**

---

## 6.11. Grafika w edytorze tekstu

Można wstawić:

- zdjęcie,
- obraz,
- ikonę,
- kształt,
- wykres,
- SmartArt.

Word:

**Wstawianie → Obrazy**

Po wstawieniu obrazu można zmienić:

- rozmiar,
- położenie,
- oblewanie tekstem.

### Oblewanie tekstem

Obraz może być np.:

- w tekście,
- otoczony tekstem,
- przed tekstem,
- za tekstem.

Warto przećwiczyć zmianę sposobu rozmieszczenia obrazu względem tekstu.

---

## 6.12. Przypisy dolne i końcowe

### Przypis dolny

Informacja pojawia się na dole konkretnej strony.

Przykład:

> Informatyka zajmuje się przetwarzaniem informacji.¹

Na dole:

> ¹ Przykładowa definicja.

### Przypis końcowy

Przypisy są umieszczane na końcu dokumentu lub sekcji.

Word:

**Odwołania → Wstaw przypis dolny**

---

## 6.13. Tabele

Tabela składa się z:

- wierszy,
- kolumn,
- komórek.

Przykład:

| Imię | Wiek | Klasa |
|---|---:|---|
| Jan | 16 | 2A |
| Adam | 15 | 2B |

Word:

**Wstawianie → Tabela**

---

## 6.14. Równania matematyczne

Word posiada **edytor równań**.

Skrót:

**Alt + =**

Przykład:

```text
x^2+2x+1=0
```

Można też używać zapisu:

```text
\frac{a}{b}
```

co daje:

\[
\frac{a}{b}
\]

### Potęga

```text
x^2
```

→ x²

### Indeks dolny

```text
x_1
```

→ x₁

### Pierwiastek

```text
\sqrt{x}
```

→ √x

### Ułamek z pierwiastkiem

```text
\frac{\sqrt{x}}{2}
```

→ √x / 2 w zapisie matematycznym.

---

## 6.15. Zapisywanie tekstu w różnych formatach

### `.docx`

Standardowy dokument Microsoft Word. Można go dalej edytować.

### `.pdf`

Format przeznaczony głównie do zachowania wyglądu dokumentu.

### `.txt`

Zwykły tekst bez zaawansowanego formatowania.

### `.odt`

Format dokumentów używany przez LibreOffice Writer.

---

# 7. Format pliku a program

Rozszerzenie pliku mówi systemowi, jakiego rodzaju jest plik.

| Rozszerzenie | Typ |
|---|---|
| `.docx` | dokument Word |
| `.pdf` | dokument PDF |
| `.txt` | zwykły tekst |
| `.jpg` | obraz |
| `.png` | obraz |
| `.mp3` | dźwięk |
| `.mp4` | film |
| `.html` | strona HTML |
| `.zip` | archiwum |

---

# 8. Najważniejsze skróty klawiszowe

| Skrót | Funkcja |
|---|---|
| `Ctrl + C` | Kopiuj |
| `Ctrl + X` | Wytnij |
| `Ctrl + V` | Wklej |
| `Ctrl + Z` | Cofnij |
| `Ctrl + Y` | Ponów |
| `Ctrl + A` | Zaznacz wszystko |
| `Ctrl + S` | Zapisz |
| `Ctrl + P` | Drukuj |
| `Ctrl + F` | Znajdź |
| `Ctrl + H` | Znajdź i zamień |
| `Ctrl + B` | Pogrubienie |
| `Ctrl + I` | Kursywa |
| `Ctrl + U` | Podkreślenie |
| `Enter` | Nowy akapit |
| `Shift + Enter` | Nowa linia |
| `Tab` | Tabulator |
| `Backspace` | Usuń znak przed kursorem |
| `Delete` | Usuń znak za kursorem |
| `Alt + =` | Wstaw równanie w Wordzie |

---

# 9. Jak to tłumaczyć osobie początkującej

Nie warto wymagać od niej wyłącznie wykucia definicji. Najpierw należy zbudować prosty model informatyki.

### Siedem zdań, które porządkują większość materiału

1. **Komputer składa się ze sprzętu i oprogramowania.**
2. **Sprzęt to rzeczy, które można fizycznie dotknąć: procesor, RAM, dysk, monitor, klawiatura.**
3. **Oprogramowanie to programy: Windows, Word, Chrome itd.**
4. **System operacyjny jest pośrednikiem między użytkownikiem, programami i sprzętem.**
5. **Pliki przechowujemy na dyskach, a foldery służą do ich organizowania.**
6. **Jeżeli komputery połączymy ze sobą, powstaje sieć.**
7. **HTML służy do określania struktury stron internetowych, a Word do tworzenia i formatowania dokumentów.**

---

# 10. Ćwiczenia praktyczne

## Ćwiczenie 1 — foldery

Utwórz:

```text
Zaliczenie
├── Dokumenty
│   ├── Polski
│   ├── Matematyka
│   └── Informatyka
├── Obrazy
└── Kopie
```

Następnie:

1. utwórz plik,
2. skopiuj go,
3. przenieś,
4. usuń,
5. odtwórz z kosza,
6. sprawdź ścieżkę dostępu.

---

## Ćwiczenie 2 — Word

Utwórz dokument zawierający:

- tytuł,
- kilka nagłówków,
- kilka akapitów,
- listę numerowaną,
- listę punktowaną,
- listę wielopoziomową,
- tabelę,
- obraz,
- numerację stron,
- datę,
- przypis dolny,
- równanie.

Na końcu:

- zapisz jako `.docx`,
- eksportuj jako `.pdf`.

---

## Ćwiczenie 3 — spis treści

Utwórz:

```text
1. Komputer
   1.1 Procesor
   1.2 RAM
   1.3 Dysk

2. Sieci komputerowe
   2.1 LAN
   2.2 WAN
```

Użyj stylów:

- Nagłówek 1,
- Nagłówek 2.

Następnie automatycznie wygeneruj spis treści.

---

## Ćwiczenie 4 — HTML

Utwórz folder:

```text
moja-strona
├── index.html
└── obrazek.jpg
```

W `index.html` umieść:

```html
<!DOCTYPE html>
<html>

<head>
    <title>Moja strona</title>
</head>

<body>

<h1>Moja pierwsza strona</h1>

<p>To jest moja pierwsza strona internetowa.</p>

<p style="color: blue;">
    Ten tekst jest niebieski.
</p>

<a href="https://www.google.com">
    Przejdź do Google
</a>

<br>

<img src="obrazek.jpg">

</body>

</html>
```

Następnie otwórz `index.html` w przeglądarce.

---

# 11. Minimum do zapamiętania

## Komputer

- BIOS/UEFI
- RAM
- ROM
- urządzenia wejścia
- urządzenia wyjścia
- urządzenia wejścia-wyjścia
- kompatybilność
- multimedia

## Systemy

- system operacyjny
- jednozadaniowy
- wielozadaniowy
- wielodostępowy
- czasu rzeczywistego

## Sieci

- sieć komputerowa
- LAN
- MAN
- WAN
- topologia
- gwiazda
- magistrala
- pierścień
- siatka
- drzewo
- P2P
- sieć z serwerem
- wady i zalety sieci

## Pliki

- plik
- folder
- podfolder
- ścieżka
- kopiowanie
- przenoszenie

## HTML

- HTML
- `html`
- `head`
- `title`
- `body`
- `h1`
- `p`
- `a`
- `href`
- `img`
- `src`
- ścieżka względna
- `..`
- znaczniki pojedyncze/podwójne

## Word

- marginesy
- akapit
- style
- nagłówki
- spis treści
- tabulatory
- listy punktowane
- listy numerowane
- listy wielopoziomowe
- grafika
- przypis dolny/końcowy
- tabela
- równanie
- formaty `.docx`, `.pdf`, `.txt`, `.odt`

## Skróty

- `Ctrl+C` — kopiuj
- `Ctrl+X` — wytnij
- `Ctrl+V` — wklej
- `Ctrl+Z` — cofnij
- `Ctrl+S` — zapisz
- `Ctrl+A` — zaznacz wszystko
- `Ctrl+B` — pogrubienie
- `Ctrl+I` — kursywa
- `Ctrl+U` — podkreślenie
- `Alt+=` — równanie w Wordzie

---

# 12. Najlepszy sposób nauki

Jeżeli to jest zaliczenie praktyczno-teoretyczne, najlepszy schemat to:

**10–15 minut teorii → 20–30 minut pracy na komputerze → krótkie pytania → powtórka.**

Szczególnie:

- foldery,
- Word,
- HTML

powinny być wykonywane przez ucznia samodzielnie, a nie tylko obserwowane.

Najlepiej, żeby potrafił nie tylko powiedzieć, czym jest np. ścieżka dostępu, ale samodzielnie ją odnaleźć, stworzyć i wykorzystać.

