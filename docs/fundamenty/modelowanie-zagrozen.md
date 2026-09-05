---
title: Modelowanie zagrożeń
icon: lucide/crosshair
---

# Modelowanie zagrożeń (Threat Modeling)

!!! abstract "Cel artykułu"
    Zdefiniowanie indywidualnego profilu ryzyka operacyjnego. Dokument wprowadza metodologię analizy zagrożeń, pozwalając na racjonalne dobranie narzędzi i procedur do faktycznych potrzeb bezpieczeństwa, bez niepotrzebnej utraty ergonomii pracy.

W inżynierii bezpieczeństwa nie istnieje pojęcie ochrony absolutnej. Każde zabezpieczenie to kompromis pomiędzy bezpieczeństwem a wygodą. Zanim zaczniesz wdrażać rygorystyczne procedury i instalować specjalistyczne oprogramowanie, musisz zrozumieć swoją sytuację wyjściową.

W cyberbezpieczeństwie proces ten nazywa się **modelowaniem zagrożeń**. Zamiast ślepo podążać za każdym nowym trendem, zadaj sobie pięć fundamentalnych pytań, które zdefiniują Twój osobisty plan obrony:

### 1. Identyfikacja aktywów (Co dokładnie chronisz?)
Zdefiniuj swoje krytyczne dane. Czy są to prywatne zdjęcia, dostęp do konta bankowego, poufne maile biznesowe, a może kryptowaluty? Nie wszystkie dane mają taką samą wartość. Hasło do forum wielbicieli kawy wymaga innej ochrony niż główna skrzynka pocztowa, na którą przychodzą linki resetujące.

### 2. Analiza adwersarza (Przed kim to chronisz?)
Kto jest Twoim przeciwnikiem? Zautomatyzowane boty skanujące sieć w poszukiwaniu starych haseł? Brokerzy danych i korporacje reklamowe tworzące Twój profil behawioralny? Złodziej, który wyrwie Ci telefon na ulicy? A może zaawansowane służby państwowe? Twój adwersarz definiuje to, jakiej tarczy musisz użyć.

### 3. Ocena prawdopodobieństwa (Jak realny jest atak?)
Jakie jest faktyczne prawdopodobieństwo wystąpienia danego wektora ataku? Ryzyko, że padniesz ofiarą masowego wycieku haseł z niezabezpieczonego sklepu internetowego, jest ogromne. Ryzyko, że zostaniesz celem dedykowanego ataku za pomocą oprogramowania Pegasus, jest dla przeciętnego obywatela bliskie zeru.

### 4. Skutki kompromitacji (Co się stanie w przypadku przełamania?)
Oceń najgorszy możliwy scenariusz. Jeśli ktoś włamie się na Twoje zapomniane konto na portalu VOD, skutki będą znikome. Jeśli jednak ktoś przejmie Twój numer telefonu (SIM swapping) i uzyska dostęp do banku lub głównej skrzynki mailowej, konsekwencje mogą być katastrofalne finansowo i życiowo.

### 5. Tolerancja na tarcie (Ile wygody jesteś w stanie poświęcić?)
Każda warstwa bezpieczeństwa wprowadza "tarcie" (ang. *friction*), co wymaga czasu, dodatkowych kliknięć oraz nauki nowych nawyków. Jak daleko jesteś w stanie się posunąć? Czy jesteś gotowy nosić przy sobie fizyczny klucz sprzętowy U2F? Zrezygnować z wygody biometrii na rzecz długiego kodu PIN? Zablokować powiadomienia w tle? 

---

!!! success "Inżynieria adekwatności"
    Odpowiadając na te pięć pytań, tworzysz swój unikalny model zagrożeń. Dzięki niemu przestaniesz marnować zasoby na obronę przed wyimaginowanymi atakami i skupisz się na wdrożeniu procedur z tej Bazy Wiedzy tam, gdzie faktycznie zabezpieczą one Twoją cyfrową tożsamość.
