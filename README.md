# Strona o Emotikonach i ich znaczeniu w komunikacji.

> ### [Link do strony](https://malelus.github.io/Emotikony/)

---

#### Strona została napisana w edytorze Visual Studio Code używając składni SCSS preprocesora SASS do pisania kodu CSS oraz użyto ikon ze strony https://fontawesome.com/.

- czcionki:
  - [Poppins](https://fonts.google.com/specimen/Poppins).

---

### Obowiązkowe:

- układ:

  - nawigacja,
  - zawartość,
  - stopka.

---

### Dodatkowe:

#### Budowa:

- strona została zaprojektowana w sposób responsywny dzięki czemu umożliwia to swobodne i wygodne korzystanie z niej na każdym urządzeniu:

| Smartphone                                                                                                       | Mobile                                                                                          | Desktop                                                                       |
| ---------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- |
| < 699px                                                                                                          | 700px - 999px                                                                                   | > 1000px                                                                      |
| widok przystowany do korzystania na smartphonie, hamburger menu (nawigacja rozwijana) (pierwotny design strony), | widok mobilny, pasek nawigacji na górze, dostosowanie czcionek i animacji do większych ekranów, | widok desktop , dostosowanie czcionek i animacji do komputerów stacjonarnych, |

- użyto znaczników semantycznych,

- użyto znaczników Open Graph (znaczniki wyświetlające podgląd strony w momencie udostępniania),

- linki nawigacji przenoszące do odpowiadającej im sekcji strony,

- okno popup umieszczone w stopce strony, zawiera:

  - skrócone informacje o zawartości strony,
  - link do repozytorium GitHub'a,
  - informacje o autorze,
  - datę wykonania,

  - okno można wyłączyć na 3 sposoby:

    - przycisk Zamknij,
    - kliknięcie poza obszar okna,
    - za pomocą przycisku ESC.

- przycisk na dole strony przenoszący na górę strony.

#### Wygląd:

- animacja przejścia między podstronami wykonana przy pomocy CSS oraz JavaScript,

- linki aktywne oraz znacznik na której stronie aktualnie znajduję się użytkownik,

- zmieniony wygląd scrollbar'a,

- symulowane wysłanie formularza na serwer komunikowany poprzez komunikat, następnie strona zostaje odświeżona.

#### Dodatki:

- informacje w konsoli o statusie animacji oraz o czasach trwania wszystkich animacji znajdujących się na stronie,

- możliwość wyłączenia całkowicie animacji znajdujących się na stronie.

  > (aby wyłączyć animacje: Ustawienia > Ułatwienia dostępu > Wyświetlacz > Pokaż animacje w systemie Windows (Wyłącz)) (Ustawienie znajduje się w pliku \_reset.scss).

---

#### Wykonał: Mateusz Narowski

#### Data: 02.03.2021
