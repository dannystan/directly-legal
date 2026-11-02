# Polityka prywatności aplikacji DireCTLy

DireCTLy to bezpłatna, niekomercyjna aplikacja na iOS, która udostępnia rozkłady jazdy oraz komunikaty dotyczące komunikacji miejskiej w gminach Chrzanów, Trzebinia i Libiąż oraz w okolicznych miejscowościach. Jest niezależnym projektem tworzonym przez osobę prywatną w czasie wolnym. Aplikacja nie jest powiązana z żadnym przewoźnikiem ani organizatorem komunikacji publicznej w obsługiwanym regionie.

Administratorem danych osobowych w rozumieniu RODO jest Daniel Stankowski, autor aplikacji. W sprawach dotyczących aplikacji oraz ochrony danych osobowych możesz skontaktować się z nim pod adresem [hellodirectly@gmail.com](mailto:hellodirectly@gmail.com).

## 1. Połączenia z serwerami

Aplikacja korzysta z serwerów wymienionych poniżej podmiotów. Każdy z tych serwerów otrzymuje adres IP Twojego urządzenia oraz podstawowe informacje techniczne o połączeniu.

* Operator serwisu kiedyprzyjedzie.pl dostarcza dane w czasie rzeczywistym o odjazdach i pojazdach. Otrzymuje również identyfikator przystanku lub kursu, którego dotyczy zapytanie aplikacji.
* Związek Komunalny „Komunikacja Międzygminna” w Chrzanowie (ZKKM, zkkm.pl) udostępnia komunikaty i aktualne rozkłady jazdy.
* GitHub udostępnia aktualizacje rozkładu jazdy oraz informację o dostępności danych w czasie rzeczywistym.
* Apple obsługuje mapy, wyszukiwanie adresów i sprawdzanie dostępności nowej wersji aplikacji. Może otrzymywać informacje o wyświetlanym obszarze mapy, a podczas wyszukiwania otrzymuje wpisywane zapytania.
* Cloudflare obsługuje serwer powiadomień autora, z którym aplikacja łączy się wyłącznie w związku z powiadomieniami o komunikatach opisanymi w punkcie 3.

Podstawą prawną przekazywania przez aplikację opisanych w tym punkcie danych jest prawnie uzasadniony interes autora, polegający na zapewnieniu działania aplikacji (art. 6 ust. 1 lit. f RODO).

Autor nie otrzymuje adresów IP od operatora serwisu kiedyprzyjedzie.pl, ZKKM, GitHuba ani Apple. Nie zapisuje ich również w bazie danych serwera powiadomień. Cloudflare przetwarza adresy IP związane z połączeniami z serwerem powiadomień w swoich rejestrach (logach) przez czas niezbędny do świadczenia usługi.

## 2. Lokalizacja

Jeżeli wyrazisz zgodę w systemowym oknie iOS, aplikacja korzysta z Twojej lokalizacji, aby wyświetlać Twoje położenie na mapie i odległość do przystanku, wskazywać pobliskie przystanki oraz planować trasy z Twojej bieżącej lokalizacji lub do niej. Współrzędne Twojej lokalizacji nie są przekazywane autorowi.

Podstawą prawną przetwarzania danych o lokalizacji jest Twoja zgoda (art. 6 ust. 1 lit. a RODO). Możesz ją cofnąć w dowolnym momencie w ustawieniach iOS. Cofnięcie zgody nie wpływa na zgodność z prawem przetwarzania dokonanego na jej podstawie przed jej cofnięciem.

Jeżeli poprosisz o wyznaczenie trasy pieszej, współrzędne trasy zostaną przekazane do aplikacji Apple Maps albo do Google Maps, jeśli ta druga została wybrana i jest zainstalowana na urządzeniu. Podstawą prawną tego przekazania jest prawnie uzasadniony interes autora opisany w punkcie 1 (art. 6 ust. 1 lit. f RODO).

## 3. Powiadomienia o komunikatach

Jeżeli włączysz powiadomienia o komunikatach, aplikacja prześle na serwer autora token urządzenia, czyli uzyskany od Apple identyfikator umożliwiający dostarczanie powiadomień.

Serwer przechowuje token wraz z oznaczeniem systemu i rodzaju wersji aplikacji oraz datami pierwszej rejestracji i ostatniego otwarcia aplikacji. Token jest wykorzystywany wyłącznie do wysyłania tych powiadomień. Jego odbiorcami są Cloudflare i Apple.

Podstawą prawną przetwarzania tych danych jest Twoja zgoda (art. 6 ust. 1 lit. a RODO). Możesz ją cofnąć w dowolnym momencie, wyłączając powiadomienia w aplikacji. Cofnięcie zgody nie wpływa na zgodność z prawem przetwarzania dokonanego na jej podstawie przed jej cofnięciem.

Token jest przechowywany, dopóki powiadomienia są włączone w aplikacji. Po ich wyłączeniu zostaje usunięty, gdy do serwera dotrze wysłane przez aplikację żądanie usunięcia.

Po odinstalowaniu aplikacji token zostaje usunięty dopiero wtedy, gdy Apple poinformuje przy próbie wysłania powiadomienia, że token nie jest już aktywny.

## 4. Wiadomości e-mail i zgłoszenia problemów

Jeżeli napiszesz do autora, otrzyma on Twój adres e-mail, nazwę nadawcy (jeżeli jest ustawiona) oraz temat i treść wiadomości. Wiadomość wysłana z aplikacji zawiera również informacje o wersji aplikacji i systemu iOS, a zgłoszenie problemu także dane wskazanego przystanku lub trasy: nazwy, identyfikatory, linie, kierunek i godziny.

Dane te są wykorzystywane wyłącznie do udzielenia odpowiedzi oraz sprawdzenia i rozwiązania zgłoszonego problemu. Podstawą prawną ich przetwarzania jest prawnie uzasadniony interes autora, polegający na obsłudze korespondencji i poprawianiu danych w aplikacji (art. 6 ust. 1 lit. f RODO).

Wiadomości są przechowywane nie dłużej niż przez 12 miesięcy od ich otrzymania. Odbiorcą danych jest Google, który obsługuje skrzynkę pocztową autora w usłudze Gmail.

## 5. Przekazywanie danych poza Europejski Obszar Gospodarczy

GitHub, Apple, Cloudflare i Google mogą przetwarzać dane poza Europejskim Obszarem Gospodarczym (EOG), w tym w Stanach Zjednoczonych.

Podstawą przekazywania danych jest decyzja Komisji Europejskiej stwierdzająca odpowiedni stopień ochrony lub standardowe klauzule umowne. Decyzja dotycząca EU–US Data Privacy Framework ma zastosowanie do podmiotów w USA objętych tym programem.

Treść standardowych klauzul umownych jest dostępna na [stronie Komisji Europejskiej](https://commission.europa.eu/publications/publications-standard-contractual-clauses-sccs_en).

ZKKM i operator serwisu kiedyprzyjedzie.pl podlegają RODO, tak jak autor, a GitHub, Apple, Cloudflare i Google zapewniają równoważną ochronę danych na podstawach opisanych powyżej.

## 6. Czy podanie danych jest obowiązkowe

Podanie danych jest dobrowolne, jednak niektóre z nich są niezbędne do korzystania z określonych funkcji aplikacji.

Bez połączeń z serwerami nie będą działać funkcje opisane w punkcie 1. Bez zgody na dostęp do lokalizacji nie będą dostępne funkcje wykorzystujące Twoje położenie, opisane w punkcie 2. Bez tokenu urządzenia nie będzie możliwe otrzymywanie powiadomień o komunikatach, a bez adresu e-mail autor nie będzie mógł odpowiedzieć na Twoją wiadomość.

## 7. Twoje prawa

W odniesieniu do danych przetwarzanych przez autora, w tym adresu IP przy połączeniu z serwerem powiadomień, tokenu urządzenia i danych zawartych w wiadomościach e-mail, przysługują Ci, w zakresie określonym w RODO, prawa dostępu do danych, ich sprostowania, usunięcia oraz ograniczenia przetwarzania. W odniesieniu do tokenu urządzenia przysługuje Ci również prawo do przenoszenia danych.

Masz prawo w dowolnym momencie wnieść sprzeciw, z przyczyn związanych z Twoją szczególną sytuacją, wobec przetwarzania danych opartego na prawnie uzasadnionym interesie autora (art. 21 RODO).

W sprawach dotyczących przetwarzania danych osobowych i korzystania z tych praw możesz skontaktować się z autorem pod adresem [hellodirectly@gmail.com](mailto:hellodirectly@gmail.com).

Przysługuje Ci także prawo wniesienia skargi do Prezesa Urzędu Ochrony Danych Osobowych.
