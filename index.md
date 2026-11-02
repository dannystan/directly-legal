# Polityka prywatności aplikacji DireCTLy

*Data wejścia w życie: 2 listopada 2026 r.*

DireCTLy to bezpłatna, niekomercyjna aplikacja na system iOS, udostępniająca rozkłady jazdy oraz komunikaty komunikacji miejskiej w gminach Chrzanów, Trzebinia i Libiąż oraz w okolicznych miejscowościach. Aplikacja jest projektem niezależnym, tworzonym przez osobę prywatną w czasie wolnym, i nie jest powiązana z żadnym oficjalnym przewoźnikiem ani z organizatorem komunikacji publicznej w obsługiwanym regionie.

Administratorem danych osobowych w rozumieniu RODO jest **Daniel Stankowski**, osoba prywatna tworząca aplikację. Kontakt w sprawach dotyczących aplikacji oraz danych osobowych jest możliwy pod adresem: **hellodirectly@gmail.com**.

## 1. Zasada ogólna

Aplikacja nie wymaga konta, logowania ani rejestracji. Nie zbiera danych analitycznych, nie zawiera narzędzi do raportowania błędów ani zewnętrznych zestawów SDK służących do reklam, analityki lub śledzenia. Za pośrednictwem aplikacji autor otrzymuje dane o Tobie tylko wtedy, gdy włączysz powiadomienia o komunikatach (punkt 5) lub wyślesz wiadomość e-mail (punkt 6).

## 2. Połączenia z serwerami zewnętrznymi

Do działania aplikacja łączy się z serwerami wymienionymi poniżej. Przy każdym połączeniu odbiorca otrzymuje adres IP, z którego korzysta telefon, oraz podstawowe informacje techniczne żądania. Aplikacja nie dołącza do tych połączeń Twoich współrzędnych ani danych identyfikujących użytkownika, z wyjątkiem tokenu opisanego w punkcie 5.

Operator serwisu kiedyprzyjedzie.pl (zkkm.kiedyprzyjedzie.pl) dostarcza dane na żywo o odjazdach i pojazdach. Otrzymuje również identyfikator przystanku lub kursu, którego dotyczy żądanie, na przykład oglądanego przystanku lub przystanku zapisanego w ulubionych.

Związek Komunalny „Komunikacja Międzygminna” w Chrzanowie (ZKKM, zkkm.pl) udostępnia komunikaty oraz oficjalne rozkłady jazdy, których aktualność sprawdza aplikacja. Gdy włączone są powiadomienia o komunikatach, aplikacja może łączyć się z tym serwisem również w tle.

GitHub Pages, usługa firmy GitHub, udostępnia aktualizacje rozkładu jazdy przygotowane przez autora oraz informację o stanie usługi.

Apple obsługuje sprawdzanie nowej wersji aplikacji w App Store, wyświetlanie map oraz wyszukiwanie adresów opisane w punkcie 4. Przy wyświetlaniu map Apple może otrzymywać informację o oglądanym obszarze.

Cloudflare obsługuje serwer powiadomień autora. Aplikacja łączy się z nim wyłącznie w związku z powiadomieniami o komunikatach (punkt 5). Serwer nie zapisuje adresów IP w swojej bazie danych.

Operator serwisu kiedyprzyjedzie.pl, ZKKM, GitHub i Apple przetwarzają te dane na własnych zasadach, a autor nie otrzymuje od nich adresów IP użytkowników aplikacji. GitHub, Apple i Cloudflare mogą przetwarzać dane poza Europejskim Obszarem Gospodarczym.

Linki otwierane w aplikacji (na przykład artykuły z komunikatami i strony na ekranie Licencje) prowadzą do stron zewnętrznych, które przetwarzają dane na własnych zasadach. Aplikacja nie ma dostępu do tego, co na nich robisz.

## 3. Dane na urządzeniu i kopie zapasowe

Ulubione przystanki, ostatnio wyszukiwane przystanki, adresy i trasy, przypomnienia o odjazdach, ustawienia, pobrany rozkład jazdy oraz zapisane odpowiedzi serwerów (pamięć podręczna) są przechowywane na urządzeniu. Aplikacja nie przesyła ich autorowi.

Kopia zapasowa w iCloud lub na komputerze może zawierać te dane, zgodnie z ustawieniami Twojego urządzenia i konta. Autor nie ma dostępu do tych kopii. Odinstalowanie aplikacji usuwa jej dane z urządzenia, ale kopie zapasowe mogą nadal je zawierać, a przywrócenie kopii może je odtworzyć. Kopiami zarządzasz w Ustawieniach iOS lub na komputerze.

## 4. Lokalizacja i mapy

Po wyrażeniu zgody w systemowym oknie iOS aplikacja korzysta z lokalizacji, aby wskazać pobliskie przystanki oraz planować trasy z miejsca, w którym jesteś, lub do tego miejsca. Współrzędne nie są wysyłane autorowi. Zgodę można w dowolnej chwili cofnąć w Ustawieniach iOS.

Podczas wyszukiwania adresów w aplikacji wpisywane zapytania są przekazywane do usług map firmy Apple, które zwracają podpowiedzi i lokalizację wybranego adresu. Apple przetwarza te zapytania zgodnie ze swoją polityką prywatności. Zapytania nie są wysyłane autorowi.

Jeżeli poprosisz aplikację o wyznaczenie trasy dojścia do przystanku, otwierana jest zewnętrzna aplikacja map (Apple Maps lub Google Maps, zależnie od Twojego wyboru w ustawieniach), a do wybranego dostawcy przekazywane są współrzędne punktu początkowego i docelowego trasy. Dane te są przetwarzane zgodnie z polityką prywatności odpowiednio Apple lub Google i nie trafiają do autora.

## 5. Powiadomienia o komunikatach oraz token urządzenia

Jeżeli włączysz powiadomienia o nowych komunikatach, aplikacja rejestruje się w usłudze Apple Push Notification service (APNs) i uzyskuje token urządzenia (identyfikator umożliwiający dostarczanie powiadomień). Token ten zostaje przesłany na serwer autora, działający w usłudze Cloudflare Workers. Serwer przechowuje go wraz z oznaczeniem systemu i rodzaju kompilacji aplikacji oraz datami pierwszej i ostatniej rejestracji i wykorzystuje wyłącznie do wysyłania powiadomień o komunikatach.

Podstawą prawną przetwarzania tokenu jest Twoja zgoda (art. 6 ust. 1 lit. a RODO), wyrażona przez włączenie powiadomień. Zgodę możesz wycofać w każdej chwili, wyłączając powiadomienia w aplikacji. Aplikacja prosi wtedy serwer o usunięcie tokenu, a jeżeli prośba nie dotrze, ponawia ją przy kolejnym otwarciu. Wycofanie zgody nie wpływa na zgodność z prawem przetwarzania, którego dokonano przed jej wycofaniem.

Token jest przechowywany, dopóki powiadomienia pozostają włączone w aplikacji. Serwer nie usuwa tokenów z powodu samego upływu czasu. Wyłączenie powiadomień wyłącznie w Ustawieniach iOS zatrzymuje ich wyświetlanie, a token pozostaje na serwerze, dopóki nie wyświetlisz ekranu Ustawienia w aplikacji. Aplikacja wyłącza wtedy powiadomienia i prosi serwer o usunięcie tokenu. Po odinstalowaniu aplikacji token zostaje usunięty dopiero wtedy, gdy usługa APNs zgłosi przy wysyłce powiadomienia, że nie jest on już aktywny.

Token jest udostępniany firmie Cloudflare, dostawcy usługi hostingu (podmiotowi przetwarzającemu), oraz usłudze APNs firmy Apple, która dostarcza powiadomienia na urządzenie. Podmioty te zapewniają odpowiedni poziom ochrony danych. Ponieważ dostawcy ci mogą przetwarzać token poza Europejskim Obszarem Gospodarczym, przekazanie odbywa się na podstawie decyzji Komisji Europejskiej stwierdzającej odpowiedni stopień ochrony (EU-US Data Privacy Framework) lub na podstawie standardowych klauzul umownych.

## 6. Wiadomości e-mail i zgłoszenia problemów

Aplikacja umożliwia kontakt z autorem oraz zgłoszenie problemu z odjazdem, przystankiem lub trasą. W obu przypadkach otwiera przygotowaną wiadomość w Twojej aplikacji pocztowej. Wiadomość zostaje wysłana tylko wtedy, gdy ją wyślesz, a przed wysłaniem możesz sprawdzić i zmienić jej treść.

Autor otrzymuje Twój adres e-mail i nazwę nadawcy, jeżeli jest ustawiona, temat i treść wiadomości oraz dopisane na jej końcu wersje aplikacji i systemu iOS. Zgłoszenie problemu zawiera ponadto dane wskazanego elementu: nazwę i identyfikatory przystanku, linię, kierunek, pokazaną godzinę z informacją, czy pochodzi z danych na żywo, czy z rozkładu, oraz bieżącą godzinę, a w przypadku trasy nazwy punktów początkowego i docelowego, linie oraz godziny odjazdu i przyjazdu.

Dane te służą wyłącznie do udzielenia odpowiedzi oraz sprawdzenia i poprawienia zgłoszonego problemu. Podstawą prawną jest prawnie uzasadniony interes autora, polegający na obsłudze korespondencji i poprawianiu danych w aplikacji (art. 6 ust. 1 lit. f RODO). Wiadomości są przechowywane nie dłużej niż 12 miesięcy od ich otrzymania.

Skrzynkę pocztową autora obsługuje usługa Gmail firmy Google, która przetwarza wiadomości zgodnie ze swoją polityką prywatności i może przetwarzać je poza Europejskim Obszarem Gospodarczym.

## 7. Twoje prawa

W odniesieniu do tokenu oraz wiadomości e-mail wysłanych do autora przysługuje Ci, w zakresie określonym w RODO, prawo dostępu do danych, ich sprostowania, usunięcia, ograniczenia przetwarzania i wniesienia sprzeciwu, a w odniesieniu do tokenu także prawo przenoszenia danych oraz wycofania zgody w sposób opisany w punkcie 5. W tych sprawach możesz skontaktować się z autorem pod adresem **hellodirectly@gmail.com**. Przysługuje Ci także prawo wniesienia skargi do Prezesa Urzędu Ochrony Danych Osobowych ([uodo.gov.pl](https://uodo.gov.pl)).

## 8. Zmiany polityki

Aktualna wersja polityki jest dostępna w aplikacji oraz na tej stronie internetowej. W razie zmian zaktualizowana zostanie data wejścia w życie na początku dokumentu.
