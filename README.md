## 1. Kiedy Git wykona fast-forward, a kiedy powstaje merge commit?

 - Fast-forward jest możliwy wtedy, gdy branch docelowy nie ma nowych commitów
od momentu utworzenia drugiej gałęzi. Wtedy Git tylko przesuwa wskaźnik brancha.
Merge commit powstaje wtedy, gdy obie gałęzie mają własne nowe commity
i historia rozeszła się na dwie linie.

## 2. Czym w praktyce różni się merge od rebase?

 - Merge łączy dwie historie i zachowuje informację o rozgałęzieniu.
Rebase przepisuje commity jednej gałęzi tak, jakby zostały utworzone
na końcu drugiej gałęzi, dzięki czemu historia jest bardziej liniowa.

## 3. W jaki sposób został rozwiązany konflikt w Twoim repozytorium?

 - Konflikt został wywołany przez zmianę tego samego fragmentu kodu
na branchu main i feature-conflict. Został rozwiązany ręcznie
przez edycję konfliktującej linii, usunięcie markerów konfliktu
i pozostawienie końcowej wersji, która zachowuje poprawne działanie programu.