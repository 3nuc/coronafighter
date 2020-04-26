Projekt 5 - Top-down Shooter

Opierając się na załączonych materiałach (kod źródłowy oraz zasoby graficzne), napisać grę zręcznościową typu top-down shooter - CoronaFighter. Gra ma polegać na sterowaniu, swego rodzaju "nano-myśliwcem" poruszającym się wewnątrz ludzkiego ciała (np. żyły/tętnicy) i strzelaniu do koronawirusów. Dostarczony kod źródłowy implementuje już animację tła, nadlatujące koronawirusy oraz proste sterowanie nano-maśliwcem (przeciąganie palcem). Kod oprócz standardowych komponentów react-native wykorzystuje biblioteki react-native-game-engine do implementacji pętli logiki oraz rn-sprite-sheet do implementacji animowanych duszków (sprites) w oparciu o szablony. UWAGA! Aplikacja jest dostosowana do ekranów 1080x1920 420dpi i była testowana wyłącznie w emulatorze Android API 28 (Pie Android 9.0). Twoje zadania:

1. Stwórz nowy projekt react-native i skopiuj załączone pliki źródłowe (wraz z katalogiem
    images) do katalogu głównego projektu **(0 pkt.)**
2. Zainstaluj bibliotekę  react-native-game-engine **(0 pkt.)**  
    `npm install --save react-native-game-engine`
3. Zainstaluj bibliotekę rn-sprite-sheet **(0 pkt.)**  
    `npm install --save rn-sprite-sheet`
4. Funkcjonalności podstawowe **(1pkt)**
    * Zaimplementuj funkcjonalność strzelania do koronawirusów.  
    * Mozesz stworzyć do tego celu specjalny przycisk np. w postaci celownika wyświetlanego przed myśliwcem.  
    * Koronawirusy po trafieniu mają     wybuchać a licznik punktów powinien być odpowiednio zwiększany. 
    * Kontakt wirusa ze statkiem ma również skutkować anihilacją wirusa, jednak liczba żyć gracza powinna być zmniejszana.  
    * Przykładowe zasoby graficzne obrazujące pociski    znajdziesz w pliku  Muzzle_flashes.psd (możesz też skorzystać z własnych). 
    * Licznik punktów i żyć umieść w górnej części ekranu. (1 pkt.)
5.    Zaimplementuj sterowanie w oparciu o akcelerometr, w taki sposób by wychylanie smartfona w lewo/prawo powodowało przesuwanie statku w tych samych kierunkach. (0.5 pkt.)
6.    Dodaj funkcjonalność zbierania "znajdziek" np. w postaci witamin lub mikroelementów podwyższających, licznik żyć. (0.5 pkt.)
7.     Zadanie dla chętnych - dodaj inne funkcjonalności wedle własnego pomysłu np. elementy interfejsu (ekran startowy, punktacja - highscores), efekt paralaksy ruchu w postaci dodatkowej animowanej warstwy tła, inne rodzaje "znajdziek": dopalacze, spowalniacze, osłony, rakiety, a także obiekty, których trafienie powoduje odejmowanie puntów np. krwinki czerwone (0-1 pkt.)

