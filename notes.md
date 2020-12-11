# Odpowiedzi 11.12.20

## Intro

- Zmienić "cel pracy" na "cel i zakres pracy"
- Zmienić zawartość na "projekt architektury systemu obszarów (...) na potrzeby/realizowany w ramach koła naukowego" (to jest cel)
- Następnie, zakres pracy to: 
    - zdefiniowanie wymagań
    - architektura
    - zaprojektowanie testów
    - przeprowadzenie testów
    - sposób uruchamiania testów i ich wpływ na wdrażanie "dodatkowo w ramach pracy przedstawione są elementy zarządzania projektem" (tutaj CI/CD)

## Geneza pracy

Pierwszy akapit zrzucić niżej. Wpleść CI/CD do wstępu, uzasadnić jego wykorzystanie, że to jest kluczowe dla dobrego rozwoju systemu/produktu
Przetrenowane -> ponownie wytrenowane/wytrenowane na nowych danych

## Wdrażanie systemu
może zamiast tego implementacja potoku CI/CD?

## Testy systemu

Powiedzieć o podziale testów na integracyjne, komponentów, integracyjne, w terenie.
Opis tego jakie rzeczy były testowane. Ile było testów na komponent (xd).

- Testy jednostkowe - bardziej konkretny opis procesu testowania. Co zdefiniowano, jakie rzeczy są sprawdzane.

- OPIS KROKÓW WSZĘDZIE, nazwać test, co robi, jaki jest cel, jak się weryfikuje, dodać UID testu (?)

- Zamiast wczesnych testów w terenie, testy systemowe, jako osobna sekcja
- Na końcu testy w terenie

## Podsumowanie

- W ramach projektu stworzono (...)

**POPRAWIĆ LABELKI W SZABLONIE**
**RYSUNEK PODPISUJEMY POD RYSUNKIEM, TABELĘ NAD TABELĄ, LISTING NAD**

# PYTANIA NA 10.12.20

- Czy okej jest "w poniższym rozdziale", 2 i 3
    > lepiej "w niniejszym"

- Czy trzeba robić \ref do każdego listingu/diagramu, nawet jak to jest oczywiste?
    Przykładowo listingi i diagramy w rozdziale o protobufie
    >  tak

- Mam \cite w obrazku, przez co przesuwają się wszystkie przypisy (diagram sitl). Co teraz?
    > przerzucić listę diagramów na dół

- Mówić rysunek jak coś jest diagramem/zdjęciem?
    > można mówić wedle woli, tak jak jest styknie

# Tutorial tikz

`https://www.bu.edu/math/files/2013/08/tikzpgfmanual.pdf`

# Pytania

- Jak opisywać pracę ludzi z klubu?

Opisywać, powiedzieć czemu i co we wstępie, podlinkować stronę
i czym się zajmują - i że to prowadzi do napisania tego systemu

- W jakiej kolejności opisać proces decydowania o architekturze

Ma z siebie wynikać, od ogółu do szczegółu

- Listingi kodu - głównie testy i skrypty?

# UWAGI:

`--` zamiast `-`

Pierwszy akapit zamienić na bezosobową.
"Akademicki klub lotniczy zajmuje się tym i tym"

"Rolą autora pracy było X, Y, Z"

Zakres pracy - dodać informacje o projektowaniu testów

*Pomysł*: zakres i struktura pracy. Ożenić cel i zakres, w strukturze opowiedzieć
o spisie treści, bardziej opisowo.

Cel systemu: high levelowy opis tego na co system ma pozwalać

Wymagania funkcjonalne: high levelowy opis tego, do czego system będzie używany


Architektura systemu obejmuje komponenty opisane na rysunku \ref

Zrobić turbo high levelowy schemat na górze przeglądu, zrobić przegląd i wybór 
technologii, na końcu dodać szczegółową tabelę

Dodać do celu projektu -- wykorzystanie dobrych praktyk zarządzania, uzasadnić
CI/CD, powiedzieć że jest o zarządzaniu.

# Nowy plan xDDDD

Celem pracy jest stworzenie projektu systemu wraz z opracowaniem cyklu rozwoju, testowania
i wdrażania, opartym o cykl CI/CD

Zredefiniować system - to nie jest gotowy projekt, tylko zestaw 

Projekt systemu drona - high level
Implementacja systemu zarządzania - CI/CD
Testy z wykorzystaniem CI/CD


## Cel pracy

Prototyp systemu monitorującego -> system inspekcji obszarów, zgadza się z
tematem pracy, rozpisać na czym polega inspekcja

## Zakres pracy -> zakres pracy i struktura pracy

## Przegląd literatury do genezy pracy

Wracać do tematu pracy w treści, jak Haidt

## Architektura, technologie

- Wstęp WSTĘP WSTĘP
- Rozbudować diagram, żeby każdy element na diagramie był opisany jako rozdział/podrozdział i odwrotnie
- Osobny rozdział poświęcony wdrażaniu

## Wdrażanie

Pokazać kontekst CI/CD

