# Repozytorium z wykorzystanym kodem oraz najważniejszymi wynikami

## Zawartość plików: 
### Pliki zawierające napisany kod
- `wszystkie_dufy.ipynb` zawiera kod pozwalający na przygotowanie pliku `all_duf_names.csv`
- `100_duf_lengths.ipynb` zawiera kod pozwalający na:
  -  wybranie 100 losowych domen o znanej i nieznanej funkcji
  -  wyznaczenie granic domen z użyciem Chainsaw
  -  wycięcie domeny z całego białka na podstawie informacji o granicach domeny
- `100_duf_plddt.ipynb` zawiera kod pozwalający na ocenę średniego pLDDT na zbiorze plików pdb
- `100_duf_only_deepfri.ipynb` zawiera kod pozwalający na użycie DeepFRI na zbiorze plików pdb (plik `100_duf_deepfri_with_figures.zip` zawiera dwie wersje pliku który rzeczywiście został wykorzystany przy używaniu narzędzia DeepFRI - zawierają one dodatkowe wykresy z różnymi sposobami agregowania anotacji przewidzianych przez DeepFRI)
- `100_duf_summary.ipynb` zawiera kod pozwalający na przedstawienie rezultatów dla anotacji przewidzianych w obrębie danego białka (pliki potrzebne do jego uruchomienia znajdują się w tym repozytorium)


### Dodatkowe pliki
- `GO_information_content_swiss-model.txt` to plik otrzymany z Sano zawierający informacje o obliczonym Information Content dla GO termów
- `all_duf_names.csv` to plik z informacjami o wszystkich domenach białkowych o nieznanej funkcji w Pfam, których nazwa jest jak wyrażenie "duf[0-9]+" (nie uwzględniając wielkości znaków)
- `accessions_random_100_known_function.csv` to plik z informacjami o białkowych reprezentantach 100 losowo wybranych domen białkowych o znanej funkcji, zawiera też informacje o granicach domen z Pfam
- `accessions_random_100_unknown_function.csv` to plik z informacjami o białkowych reprezentantach 100 losowo wybranych domen białkowych o nieznanej funkcji, zawiera też informacje o granicach domen z Pfam
- `known_100_lengths.csv` to plik z informacjami o białkowych reprezentantach 100 losowo wybranych domen białkowych o znanej funkcji, dla których Chainsaw wykryło domenę odpowiadającą domenie z Pfam, zawiera też informacje o długości domeny z Pfam, długości domeny z Chainsaw, długości części wspólnej obu domen, procent pokrycia względem Pfam i procent pokrycia względem Chainsaw
- `unknown_100_lengths.csv` to plik z informacjami o białkowych reprezentantach 100 losowo wybranych domen białkowych o nieznanej funkcji, dla których Chainsaw wykryło domenę odpowiadającą domenie z Pfam, zawiera też informacje o długości domeny z Pfam, długości domeny z Chainsaw, długości części wspólnej obu domen, procent pokrycia względem Pfam i procent pokrycia względem Chainsaw
- `summary_results.zip` plik zawierający skompresowany folder z podsumowaniem wszystkich wyników tworzonym przez plik `100_duf_summary.ipynb` oraz jego wcześniejsze wersje
- `known_raw_deepfri_results.zip` i `unknown_raw_deepfri_results.zip` zawiera foldery z surowymi wynikami DeepFRI dla reprezentantów 100 losowo wybranych domen o znanej i nieznanej funkcji z Chainsaw i Pfam
- `pvalue_tables.ods` plik zawierający arkusze z kolejnymi liczonymi porówananiami rezultatów między grupami


