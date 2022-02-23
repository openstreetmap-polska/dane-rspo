# dane-rspo
Dane z rejestru szkół i placówek oświatowych przygotowane do integracji z OpenStreetMap

Projekt ich mapowania opisany na stronie https://wiki.openstreetmap.org/wiki/Organised_Editing/Activities/Updating_and_mapping_schools_in_Poland

## Struktura plików
Pliki geojson dla każdej gminy pogrupowane są w katalogach województwo / powiat.
Na początku nazwy każdego katalogu i pliku znajduje się numer TERYT danej jednostki. W przypadku plików, na końcu dodane jest określenie rodzaju jednostki (Miejska / Wiejska / Miejsko-Wiejska / DZielnica, DElegatura). Nie dzielono gmin miejsko-wiejskich na miasta i obszary wiejskie.

## Struktura danych w plikach
W przypadku gdy w RSPO kilka placówek miało te same współrzędne (zespoły szkół), w plikach znajdujących się tutaj, punkty te zostały nieco rozsunięte po szerokości geograficznej, aby nie nakładały się na siebie (znajdują się jeden pod drugim).
Pliki zawierają propozycje tagów. Tag "note" zawiera informacje o placówkach podrzędnych lub placówce nadrzędnej (zespoły szkół).
W przypadku wątpliwości co do tagowania, w tagu "fixme" znajduje się opis propozycji.

Informacje o danej jednostce mozna podejrzeć bezpoeśrednio w rejestrze RSPO pod adresem https://rspo.gov.pl/rspo/123364 - podstawiając na końcu adresu interesujący nas nr RSPO (ref:rspo).
