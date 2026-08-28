# HYROX plan — GitHub Pages

Pliki:
- `index-light-github.html` — aplikacja
- `one_month_prior_start_gdansk_2026.json` — źródło danych

## Publikacja
1. Umieść oba pliki w tym samym katalogu repozytorium.
2. Włącz GitHub Pages dla repozytorium.
3. Otwórz stronę przez adres GitHub Pages.

## Zapisywanie zmian
Przycisk **Edytuj dzień → Zapisz do GitHub** używa GitHub Contents API.

Przy pierwszym zapisie w danej sesji strona poprosi o:
- GitHub Personal Access Token,
- owner/nazwę użytkownika,
- nazwę repozytorium,
- branch.

Token jest używany wyłącznie w pamięci bieżącej strony — nie jest zapisywany do `localStorage` ani do pliku.

Token musi pozwalać na odczyt/zapis zawartości repozytorium. Dla fine-grained PAT wybierz właściwe repozytorium i uprawnienie **Contents: Read and write**.

Uwaga: GitHub Pages jest statyczne, więc bezpośredni zapis do repozytorium wymaga autoryzacji GitHub API. Nie umieszczaj stałego tokenu w kodzie strony.
