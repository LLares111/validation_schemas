# Schematy walidacyjne

**Repozytorium [https://gitlabplatom.cti.p.lodz.pl/tjaworski/validation_schemas](https://gitlabplatom.cti.p.lodz.pl/tjaworski/validation_schemas) jest jedynym oficjalnym źródłem schematów, dokumentacji schematów oraz przykładów.**
**Schematy znajdujące się w prywatnych zasobach nie będą aktualizowane.**

Repozytorium przechowuje **schematy walidacyjne** oraz **przykłady komunikatów** dla tych schematów, wykorzystywane w komunikacji sieciowej systemu **Platom**.

Opis komunikacji oraz dokumentacja schematów dostępna jest w formie PDF [tutaj](https://gitlabplatom.cti.p.lodz.pl/tjaworski/validation_schemas/tree/master/dokumentacja). Jeżeli jesteś członiem projekt Platom i chcesz wprowadzić poprawki do dokumentacji - napisz maila.
Udostępnie wersję edytowalną online (Google Docs).

Wszelkie uwagi i pytania w zakresie schematów, komunikatów, komunikacji należy zgłaszać do Tomasza Jaworskiego <[tjaworski@iis.p.lodz.pl](mailto:tjaworski@iis.p.lodz.pl)>.

## Struktura repozytorium

 * Zawartość repozytorium podzielona jest na katalogi, odpowiadające schematom walidacyjnym.
    *  Dodając nowy schemat należy zachować zasadę **1 schemat = 1 katalog**. 
    *  Bezpośrednio w katalogu musi być **jeden schemat** i może być **dowolnie wiele komunikatów** przykładowych, które **muszą** poprawnie przechodzić proces walidacji.
*  Każdy schemat powinien być wyposażony w dokumentację, opisującą:
    * cel istnienia schematu,
    * urządzenie pomiarowe/wykonawcze wykorzystujące daną komunikację
    * nazwę schematu, kanału komunikacyjnego i usługi,
    * interpretację danych w polach komunikatów (usługi pomiarowe),
    * wpływ danych na infrastrukturę projektu (usługi wykonawcze),
    * interpretacje danych wejściowych i wyjściowych (usługi przetwarzające).
 * Pliki schematów i komunikatów muszą mieć rozszerzenie `*.json`.
 * Nazwy plików mogą być dowolne; monitor sieciowy i walidator analizują struktury plików `.json` niezależnie od ich nazwy.

## Dodawanie schematów i komunikatów
 * Zarządzanie zwartością repozytorium wymaga narzędzia GIT i z jego poziomu jest zarządzane.
 * Aby móc **dodawać schematy i przykłady komunikatów** do repozytorium, należy zgłosić się do właściciela repozytorium (Tomasz Jaworski) po uprawnienia zapisu (tylko dla członków projektu Platom).
 