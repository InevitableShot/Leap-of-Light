# Leap of Light
## Projekt gry na przedmiot "Projekt C++"
"Leap of Light" będzie grą platformową nawiązującą do kultowej gry "Icy Tower", jednakże będzie ona w zupełnie innym settingu, a także będą dodatkowe mechaniki utrudniające wspinanie się. Gracz będzie miał za zadanie pokonać jak największą ilość stopni. Przeszkodą w osiągnięciu tego celu będzie wszechobecna ciemność. Jedynymi źródłami światła oświetlającymi przestrzeń wokół bohatera będzie jego maska, która zapewniać będzie poświatę wokół postaci oraz latarka, przy pomocy której gracz będzie mógł oświetlić część mapy i zaplanować dalszą drogę. Dodatkowo oprócz ciemności, przeszkodą do pokonania będą latające nietoperze, które uciekają przed światłem latarki. Gra będzie dość zręcznościowa, gdyż oprócz opanowania samego poruszania się i skakania, gracz będzie musiał skupić się również na sterowaniu światłem za pomocą myszy. Gracz przegrywa w momencie spadnięcia na sam dół lub dotknięciu przez nietoperza.

## Wykorzystywane technologie
* SFML (mechanika gry oraz wygląd)
* Box2D (silnik fizyczny)

## Terminy raportów oraz wstępne rozplanowanie pracy
1. Raport I (09.11.2021)
  * Poruszanie się postaci
  * Wykrywanie kolizji gracza ze ścianami oraz platformami
  * Testowy poziom, gdzie można wypróbować kolizje
  * Początkowy zarys tego jak gra będzie wyglądać graficznie (jeśli nie znajdę pasujących grafik do zamysłu gry to wykonam je samodzielnie, dlatego na początku mogą zostać użyte placeholdery)
2. Raport II (23.11.2021)
  * Dodanie nietoperzy, generowanie ich w przestrzeni oraz ich ruch
  * Generowanie kolejnych platform i przesuwanie się poziomu do góry
3. Raport III (7.12.2021)
  * Wstępne zaimplementowanie mechaniki światła 
  * Dodanie dodatkowych platform, które będą reagować na światło
4. Raport IV (21.12)
  * Reagowanie nietoperzy na światło
  * Mechanika nietoperzy polegająca na próbie "ataku" gracza
  * Licznik zdobytych punktów 
  * Menu gry
