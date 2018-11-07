Scrum Guide™
============

Ta wersja Przewodnika Scrum w formacie Markdown i HTML jest konwersją polskiego tłumaczenia wersji PDF z Listopada 2017 [dostępnej w serwisie www.scrumguides.org](http://www.scrumguides.org/docs/scrumguide/v2017/2017-Scrum-Guide-US.pdf).


Przewodnik po Scrumie: Reguły gry
---------------------------------

Listopad 2017


*Przygotowany i utrzymywany przez twórców Scruma: Kena Schwabera i Jeffa Sutherlanda*

**WERSJA JĘZYKOWA POLSKA/ POLISH**


Cel przewodnika
---------------

Scrum to ramy postępowania przydatne w procesach wytwarzania, dostarczania i
utrzymywania złożonych produktów. Ten Przewodnik zawiera definicję Scruma, na którą
składają się: role, wydarzenia, artefakty i zestaw reguł, które łączą te elementy w jedną całość.
Scrum został stworzony przez Kena Schwabera i Jeffa Sutherlanda. To oni są autorami tego
przewodnika i razem wspierają zawarte w nim przesłanie.


Definicja Scruma
----------------

Scrum (rzecz.): ramy postępowania (ang. *framework*), dzięki którym ludzie mogą adaptacyjnie rozwiązywać złożone problemy tak, by w produktywny i kreatywny sposób wytwarzać produkty o najwyższej możliwej wartości.

Scrum jest:

  * lekki,
  * łatwy do zrozumienia,
  * trudny do opanowania.

Scrum to ramy postępowania, które są wykorzystywane w zarządzaniu wytwarzaniem złożonych produktów od początku lat dziewięćdziesiątych. Scrum nie jest procesem czy techniką wytwórczą, czy też wyczerpującym opisem sposobu działania. Definiuje jedynie ogólne reguły postępowania, w obrębie których możliwe jest stosowanie różnego rodzaju procesów i technik. Scrum obnaża względną skuteczność wykorzystywanych metod zarządzania produktem i sposobów wykonywania pracy tak, by można było w sposób ciągły doskonalić produkt, zespół oraz środowisko pracy.

Na Scruma składają się: Zespoły Scrumowe (ang. *Scrum Teams*) oraz związane z nimi role,
wydarzenia, artefakty (ang. *artifacts*) i reguły. Każdy z elementów służy konkretnym celom i każdy jest niezbędny do osiągnięcia sukcesu w stosowaniu Scruma.

Reguły Scruma łączą ze sobą wydarzenia, role i artefakty, definiując powiązania i relacje
pomiędzy nimi. Zostały one opisane w tym dokumencie.

Poszczególne zastosowania Scruma mogą się między sobą różnić i z tego względu wykraczają
poza zakres tego przewodnika.


Zastosowanie Scruma
-------------------

Początkowo Scrum został stworzony w celu zarządzania i wytwarzania produktów.

Począwszy od wczesnych lat dziewięćdziesiątych był wykorzystywany powszechnie, na całym
świecie, do:

  1. odkrywania i identyfikowania rentowności rynków, technologii i potencjału
  produktów,
  2. tworzenia i rozbudowy produktów,
  3. wprowadzania na rynek produktów i ich rozszerzeń, nawet wielokrotnie każdego
  dnia,
  4. rozwijania i utrzymywania środowisk typu cloud (online, bezpiecznych, dostępnych
  na żądanie) oraz innych środowisk operacyjnych do zastosowań produktowych,
  5. utrzymywania i modernizacji produktów.

Scrum był stosowany do rozwijania oprogramowania, sprzętu, oprogramowania
wbudowanego (ang. *embedded*), sieci zintegrowanych usług i autonomicznych pojazdów.
Znalazł swoje zastosowanie w szkolnictwie, administracji publicznej, marketingu, zarządzaniu operacjami w organizacjach – praktycznie każdej sferze codziennego życia.

Każdego dnia Scrum udowadnia swoją przydatność w obliczu gwałtownie rosnącej złożoności
technologii, zmian rynkowych, środowiska i zachodzących pomiędzy nimi interakcji.

Scrum dowiódł swojej skuteczności w iteracyjnym i przyrostowym transferze wiedzy.
Obecnie znajduje szerokie zastosowanie w rozwoju produktów, usług i w zarządzaniu
organizacjami.

Istotą Scruma jest niewielki zespół. Niezależny zespół jest wysoce elastyczny i potrafi
sprawnie się dostosowywać. Te atuty sprawdzają się zarówno w przypadku pojedynczych
zespołów, kilku współpracujących zespołów, wielu zespołów oraz sieci powiązanych ze sobą
zespołów, które wykonują pracę, rozwijają, wydają na rynek i utrzymują efekty pracy tysięcy
osób. Współpracują one i współdziałają ze sobą wykorzystując wyrafinowane środowiska i
architektury systemowe.

Słowa „rozwijać” (ang. *develop*) i „rozwijanie” (ang. *development*) są używanie w tym
przewodniku w odniesieniu do złożonej pracy, której przykłady wymieniono powyżej.


Teoria Scruma
-------------

Scrum został osadzony w teorii empirycznej kontroli procesu, lub — krócej — w teorii
empiryzmu. Empiryzm reprezentuje pogląd, iż wiedza wynika z *doświadczania i
podejmowania decyzji* w oparciu o to, co zostało poznane. Scrum wykorzystuje podejście
iteracyjne i przyrostowe w celu zwiększenia przewidywalności i lepszej kontroli ryzyka.

Empiryczna kontrola procesu opiera się na trzech filarach: przejrzystości, inspekcji i adaptacji.

### Przejrzystość

Wszystkie istotne aspekty procesu muszą być widoczne dla osób odpowiedzialnych za
osiągane rezultaty. Reguła przejrzystości wymaga, by aspekty te były opisane wspólnymi dla
osób zaangażowanych standardami, tak by wszyscy obserwatorzy tak samo rozumieli to, co
obserwują.

Przykładowo:

  * uczestnicy danego procesu muszą posługiwać się wspólnym nazewnictwem elementów tego procesu,
  * osoby wykonujące pracę i osoby akceptujące wyniki tej pracy muszą posługiwać się
  wspólną definicją „Ukończonej” (ang. *"Done"*) pracy.

### Inspekcja

Osoby wykorzystujące Scruma muszą poddawać częstej inspekcji artefakty scrumowe oraz postępy w realizacji Celu Sprintu (ang. *Sprint Goal*), celem wykrycia niepożądanych rozbieżności. Inspekcja nie powinna jednak być zbyt częsta, by nie stanowiła przeszkody w wykonywaniu pracy. Inspekcje przynoszą najwięcej korzyści, gdy są sumiennie przeprowadzane przez wykwalifikowanych inspektorów bezpośrednio w miejscu, w którym wykonywana jest praca.

### Adaptacja

Jeżeli osoba dokonująca inspekcji ustali, że jeden lub więcej aspektów procesu wykracza poza
przyjęte limity oraz że wytwarzany w ten sposób produkt nie będzie akceptowalny, proces lub
przetwarzany materiał muszą zostać skorygowane. Korekta musi być wykonana jak najszybciej, by ograniczyć dalsze odstępstwa.

Scrum przewiduje cztery formalne punkty przeprowadzania inspekcji i okazje do dokonania
adaptacji (korekty). Wszystkie te punkty zostały opisane w sekcji Wydarzenia w Scrumie:

  * Planowanie Sprintu (ang. *Sprint Planning*)
  * Codzienny Scrum (ang. *Daily Scrum*)
  * Przegląd Sprintu (ang. *Sprint Review*)
  * Retrospektywa Sprintu (ang. *Sprint Retrospective*)


Wartości Scruma
---------------

Zespół Scrumowy przyjmując wartości zaangażowania, odwagi, skupienia, otwartości i poszanowania i postępując zgodnie z nimi, powołuje do życia filary Scruma – przejrzystość, inspekcja i adaptacja, tworząc atmosferę zaufania pomiędzy wszystkimi współpracującymi osobami. Członkowie Zespołu Scrumowego odkrywają te wartości i uczą się ich, pracując z wydarzeniami, rolami i artefaktami Scruma.

Powodzenie w wykorzystaniu Scruma zależy od biegłości w postępowaniu zgodnie z tymi pięcioma wartościami. Wszyscy osobiście zobowiązują się osiągać cele Zespołu Scrumowego. Członkowie Zespołu Scrumowego mają odwagę postępować właściwie i przezwyciężać trudności. Wszyscy skupiają się na pracy w Sprincie i celach Zespołu Scrumowego. Zespół Scrumowy i jego interesariusze zgadzają się pozostawać otwartymi na wszystkie aspekty wykonywanej pracy i związane z nią wyzwania. Członkowie Zespołu Scrumowego wzajemnie respektują swoje prawo do bycia niezależnymi, kompetentnymi ludźmi.


Zespół Scrumowy
---------------

W skład Zespołu Scrumowego wchodzą: Właściciel Produktu (ang. *Product Owner*), Zespół Deweloperski (ang. *Development Team*) oraz Scrum Master. Zespoły Scrumowe są samoorganizujące się i międzyfunkcjonalne (ang. *cross-functional*). Samoorganizujące się zespoły samodzielnie decydują, w jaki sposób najlepiej wykonywać pracę, nie będąc przy tym kierowanymi przez osoby spoza zespołu. Zespoły międzyfunkcjonalne posiadają wszelkie kompetencje niezbędne do ukończenia pracy, nie będąc zależnymi od osób nienależących do zespołu. Model zespołu proponowany w Scrumie został zaprojektowany tak, aby zoptymalizować elastyczność, kreatywność i produktywność. Taki model Zespołu Scrumowego dowiódł swojej rosnącej skuteczności w wymienionych uprzednio przypadkach oraz każdym innym rodzaju złożonej pracy.

Zespoły Scrumowe dostarczają produkty iteracyjnie i przyrostowo, zwiększając szanse na
uzyskanie informacji zwrotnej. Przyrostowe dostarczanie „Ukończonego” produktu zapewnia
nieprzerwaną dostępność jego działającej, potencjalnie użytecznej wersji.


Właściciel Produktu
-------------------

Właściciel Produktu jest odpowiedzialny za maksymalizację wartości produktu i pracy Zespołu Deweloperskiego. Sposoby osiągania tego celu mogą się znacznie różnić pomiędzy organizacjami, Zespołami Scrumowymi i poszczególnymi osobami.

Właściciel Produktu jest jedyną osobą odpowiedzialną za zarządzanie Backlogiem Produktu
(ang. *Product Backlog*). Pojęcie zarządzania Backlogiem Produktu mieści w sobie:

  * jasne artykułowanie elementów Backlogu Produktu,
  * porządkowanie kolejności elementów Backlogu Produktu w sposób pozwalający jak najlepiej osiągać założone cele i misje,
  * optymalizowanie wartości pracy wykonywanej przez Zespół Deweloperski,
  * zapewnianie, że Backlog Produktu jest dostępny, przejrzysty i jasny dla wszystkich, a także opisuje to, czym Zespół Scrumowy będzie się zajmował w dalszej kolejności,
  * zapewnianie, że Zespół Deweloperski rozumie elementy Backlogu Produktu w wymaganym stopniu.

Właściciel Produktu może wykonywać powyższe zadania samodzielnie lub zlecać je Zespołowi Deweloperskiemu, jednak to Właściciel Produktu pozostaje za nie odpowiedzialny. Właściciel Produktu to pojedyncza osoba, nie komitet.

Właściciel Produktu może reprezentować interesy grupy osób, lecz osoby chcące zmienić priorytet elementu Backlogu Produktu, muszą zwrócić się do Właściciela Produktu.

Aby Właściciel Produktu mógł odnieść sukces, cała organizacja musi respektować jego decyzje. Decyzje te są odzwierciedlone w treści i kolejności elementów Backlogu Produktu. Nikt nie może nakazać Zespołowi Deweloperskiemu, aby pracował z innym zestawem wymagań.


Zespół Deweloperski
-------------------

Zespół Deweloperski złożony jest z profesjonalistów, których zadaniem jest dostarczenie, na zakończenie każdego Sprintu, „Ukończonego” i gotowego do potencjalnego wydania Przyrostu (ang. *Increment*) produktu. „Ukończony” Przyrost jest wymagany podczas Przeglądu Sprintu (ang. *Sprint Review*). Tylko członkowie Zespołu Deweloperskiego tworzą Przyrost.

Zespoły Deweloperskie są ustanowione i uprawnione przez organizację do samodzielnego organizowania własnej pracy i zarządzania nią. Synergia będąca rezultatem takiego postępowania zwiększa ogólną wydajność i efektywność Zespołu Deweloperskiego.

Charakterystyka Zespołów Deweloperskich jest następująca:

  * Są samoorganizujące się. Nikt (nawet Scrum Master) nie może mówić Zespołowi Deweloperskiemu, jak przekształcać elementy Backlogu Produktu w Przyrosty gotowej do potencjalnego wydania funkcjonalności.
  * Zespoły Deweloperskie są międzyfunkcjonalne, w swoim składzie posiadają wszystkie umiejętności niezbędne do wytworzenia Przyrostu produktu.
  * Scrum nie wyróżnia nazw ról członków Zespołu Deweloperskiego, bez względu na charakter wykonywanej przez nich pracy.
  * Scrum nie wyróżnia podzespołów w Zespole Deweloperskim, niezależnie od rodzaju wykonywanych zadań — na przykład testowania, tworzenia architektury, operacji czy analizy biznesowej.
  * Mimo, iż pojedynczy członkowie Zespołu Deweloperskiego mogą posiadać wyspecjalizowane umiejętności i mogą skupiać się na konkretnych dziedzinach, odpowiedzialność za wykonywaną pracę ponosi cały Zespół Deweloperski.


### Wielkość Zespołu Deweloperskiego

Zespół Deweloperski powinien być na tyle mały, by pozostał zwinnym i jednocześnie wystarczająco liczny, żeby mógł wykonać znaczącą pracę w ramach Sprintu. Mniej niż troje członków oznacza mniejszy stopień interakcji i niższy wzrost produktywności. Mniejsze Zespoły Deweloperskie mogą napotykać w trakcie Sprintu braki kompetencji uniemożliwiające im dostarczanie Przyrostu gotowego do potencjalnego wydania. Więcej niż dziewięcioro członków wymaga zbyt dużych nakładów na koordynację. W dużych Zespołach Deweloperskich poziom złożoności jest tak wysoki, że stosowanie procesu empirycznego przestaje być użyteczne. Osoby Właściciela Produktu i Scrum Mastera nie są wliczane w podane wyżej wartości, chyba że wykonują one jednocześnie pracę wynikającą z Backlogu Sprintu (ang. *Sprint Backlog*).


Scrum Master
------------

Scrum Master jest odpowiedzialny za promowanie i wspieranie stosowania Scruma tak, jak został on zdefiniowany w tym Przewodniku. Scrum Masterzy osiągają to poprzez pomaganie wszystkim w zrozumieniu teorii Scruma, jego praktyk, reguł i wartości.

Scrum Master jest przywódcą służebnym (ang. *servant leader*) Zespołu Scrumowego. Scrum Master pomaga również osobom spoza Zespołu Scrumowego zrozumieć, które z ich interakcji z Zespołem Scrumowym są pomocne, a które nie. Scrum Master pomaga zmieniać te zachowania, aby maksymalizować wartość wytwarzaną przez Zespół Scrumowy.

### Jak Scrum Master wspiera Właściciela Produktu?

Scrum Master służy pomocą Właścicielowi Produktu w wielu aspektach, na przykład:

  * zapewniając, że cele, zakres i domena produktowa są zrozumiałe dla wszystkich w Zespole Scrumowym, tak dobrze jak to tylko możliwe,
  * znajdując techniki efektywnego zarządzania Backlogiem Produktu,
  * pomagając Zespołowi Scrumowemu zrozumieć potrzebę formułowania jasnych i zwięzłych elementów Backlogu Produktu,
  * w rozumieniu zasad planowania produktu w środowisku empirycznym,
  * zapewniając, że Właściciel Produktu wie, jak porządkować Backlog Produktu, aby maksymalizować wartość,
  * w rozumieniu i praktykowaniu zwinności (ang. *agility*),
  * wspomagając przebieg wydarzeń scrumowych, kiedy jest to konieczne lub kiedy jest o to proszony.

### Jak Scrum Master wspiera Zespół Deweloperski?

Scrum Master służy pomocą Zespołowi Deweloperskiemu na kilka sposobów, na przykład:

  * coachując Zespół Deweloperski w zakresie wykorzystania zasad samoorganizacji i międzyfunkcyjności,
  * pomagając Zespołowi Deweloperskiemu tworzyć produkty wysokiej wartości,
  * usuwając przeszkody ograniczające postępy Zespołu Deweloperskiego,
  * wspomagając przebieg wydarzeń scrumowych, kiedy jest to konieczne lub kiedy jest o to proszony,
  * coachując Zespół Deweloperski w zakresie sposobu wykonywania pracy w organizacjach, w których Scrum nie jest jeszcze w pełni przyjęty i rozumiany.

### Jak Scrum Master wspiera organizację?

Scrum Master służy pomocą całej organizacji na kilka sposobów, na przykład:

  * przewodząc procesom wdrażania Scruma oraz prowadząc coaching osób w ten proces zaangażowanych,
  * planując wykorzystanie Scruma wewnątrz organizacji,
  * wspierając pracowników i interesariuszy w zrozumieniu i stosowaniu Scruma oraz empirycznego podejścia do rozwoju produktu,
  * powodując zmiany prowadzące do zwiększania produktywności Zespołu Scrumowego,
  * współpracując z innymi Scrum Masterami w celu zwiększenia efektywności wykorzystania Scruma w organizacji.


Wydarzenia w Scrumie
--------------------

Wydarzenia (ang. *events*) opisane w Scrumie są używane do wprowadzenia regularności i ograniczenia potrzeby organizowania innych, nieujętych w Scrumie spotkań. Wszystkie wydarzenia w Scrumie są ograniczone czasowo (ang. timebox), co oznacza, że mają ustalony maksymalny czas trwania. Po rozpoczęciu Sprintu jego czas trwania jest stały – nie może być skracany ani wydłużany. Pozostałe wydarzenia mogą zakończyć się, kiedy ich cel zostanie osiągnięty, co zapewnia właściwe wykorzystanie czasu i zapobiega wkradaniu się marnotrawstwa w proces.

Poza Sprintem, który zawiera w sobie pozostałe wydarzenia, każde ze wydarzeń w Scrumie jest formalną okazją do przeprowadzenia celowej inspekcji i dokonania adaptacji. Wydarzenia w Scrumie są specjalnie zaprojektowane w taki sposób, aby zapewnić niezbędną przejrzystość i umożliwić inspekcję. Nieuwzględnienie któregokolwiek z nich redukuje przejrzystość i jest utraconą szansą na dokonanie inspekcji i adaptacji.

### Sprint

Sercem Scruma jest Sprint — ograniczony czasowo do maksymalnie jednego miesiąca, podczas którego wytwarzany jest „Ukończony”, gotowy do użycia i potencjalnego wydania Przyrost produktu. Sprinty zachowują możliwie stały czas trwania przez cały okres realizowania prac. Nowy Sprint rozpoczyna się bezpośrednio po zakończeniu poprzedniego.

Sprinty zawierają i składają się z Planowania Sprintu, Codziennych Scrumów, pracy wytwórczej, Przeglądu Sprintu i Retrospektywy Sprintu.

Podczas Sprintu:

  * nie są wprowadzane zmiany stanowiące zagrożenie dla realizacji Celu Sprintu,
  * cele jakościowe nie są obniżane,
  * zakres prac, wraz ze zdobywaniem nowych informacji, może być wyjaśniany i renegocjowany pomiędzy Właścicielem Produktu a Zespołem Deweloperskim.

Każdy Sprint może być postrzegany jako projekt sięgający nie dalej niż miesiąc w przód. Jak każdy projekt, Sprint używany jest do osiągnięcia jakiegoś celu. Z każdym Sprintem związany jest opis tego, co należy zbudować, projekt oraz elastyczny plan wykonywania prac prowadzących do powstania oczekiwanego przyrostu produktu.

Czas trwania Sprintu jest ograniczony do jednego miesiąca kalendarzowego. Jeśli horyzont zakończenia Sprintu jest zbyt odległy, może zmienić się definicja tego, co ma zostać zbudowane, może zwiększyć się złożoność oraz wzrosnąć ryzyko. Sprinty wprowadzają przewidywalność, zapewniając, że proces inspekcji i adaptacji w kierunku osiągnięcia Celu Sprintu będzie zachodził przynajmniej co miesiąc. Ponadto Sprinty ograniczają ryzyko do kosztu jednego miesiąca kalendarzowego.

#### Przerywanie Sprintu
Sprint może zostać przerwany przed upływem ograniczenia czasowego. Tylko Właściciel Produktu ma prawo przerwać Sprint, jednak może podjąć taką decyzję pod wpływem opinii interesariuszy, Zespołu Deweloperskiego lub Scrum Mastera.

Sprint może zostać przerwany, jeśli Cel Sprintu się zdezaktualizuje. Może tak się stać, gdy firma zmieni kierunek rozwoju lub gdy zmienią się uwarunkowania rynkowe lub technologiczne. Ogólnie rzecz ujmując Sprint powinien zostać przerwany, jeśli kontynuowanie prac nie ma sensu w zaistniałych okolicznościach. Jednak ze względu na krótki czas trwania Sprintów ich przerywanie rzadko jest sensowne.

Kiedy Sprint jest przerywany, wszystkie wykonane i „Ukończone” elementy Backlogu Produktu są przeglądane. Jeśli część tej pracy nadaje się do potencjalnego wydania, Właściciel Produktu zwykle ją zatwierdza. Wszystkie nieukończone elementy Backlogu Produktu są ponownie szacowane i zwracane do Backlogu Produktu. Praca na nich wykonana szybko się dewaluuje i z tego względu musi być regularnie powtórnie szacowana.

Przerwanie Sprintu zużywa zasoby, ponieważ wszyscy muszą się przegrupować podczas kolejnego Planowania Sprintu, aby móc rozpocząć nowy Sprint. Przerwania Sprintów są zwykle traumatyczne dla Zespołu Scrumowego i zachodzą bardzo rzadko.

### Planowanie Sprintu

Praca przeznaczona do wykonania w Sprincie jest planowana podczas Planowania Sprintu. Plan ten powstaje w efekcie wspólnej pracy członków Zespołu Scrumowego.

Planowanie Sprintu jest wydarzeniem ograniczonym do ośmiu godzin w przypadku miesięcznego Sprintu. Dla krótszych Sprintów jest ono zwykle krótsze. Rolą Scrum Mastera jest zapewnienie, że Planowanie Sprintu się odbywa i jego uczestnicy rozumieją cel tego wydarzenia. Scrum Master uczy Zespół Scrumowy utrzymywać je w wyznaczonych ramach czasowych.

Planowanie Sprintu daje odpowiedź na następujące pytania:

  * Co może zostać dostarczone w ramach Przyrostu mającego być rezultatem nadchodzącego Sprintu?
  * W jaki sposób praca, niezbędna do dostarczenia Przyrostu, będzie wykonana?

#### Temat pierwszy: Co może zostać zrobione w Sprincie?
Zespół Deweloperski prognozuje zakres prac, który zostanie zrealizowany w trakcie Sprintu. Właściciel Produktu omawia założenia Sprintu i te elementy Backlogu Produktu, których realizacja w trakcie Sprintu pozwoli na osiągnięcie Celu Sprintu. Cały Zespół Scrumowy wspólnie pracuje nad zrozumieniem pracy będącej zakresem Sprintu.

Planowanie Sprintu oparte jest na Backlogu Produktu, ostatnim Przyroście produktu, przewidywanych możliwościach Zespołu Deweloperskiego w Sprincie oraz poprzednich rezultatach Zespołu Deweloperskiego. Decyzja o liczbie elementów Backlogu Produktu pobranych do Sprintu należy tylko i wyłącznie do Zespołu Deweloperskiego. Tylko Zespół Deweloperski może ocenić, co jest w stanie osiągnąć w nadchodzącym Sprincie.

W trakcie planowania Sprintu Zespół Scrumowy tworzy także Cel Sprintu. Jest to zamierzenie, które zostanie osiągnięte w ramach Sprintu poprzez implementację wybranych elementów Backlogu Produktu. Cel Sprintu pomaga Zespołowi Deweloperskiemu zrozumieć, w jakim celu będzie on tworzyć Przyrost.

#### Temat drugi: W jaki sposób praca zostanie wykonana?
Po określeniu Celu Sprintu oraz wybraniu elementów Backlogu Produktu do Sprintu Zespół Deweloperski decyduje, w jaki sposób zostaną one podczas Sprintu przekształcone w „Ukończony” Przyrost produktu. Wybrane elementy Backlogu Produktu wraz z planem ich dostarczenia nazywane są Backlogiem Sprintu.

Zespół Deweloperski zwykle rozpoczyna od projektowania systemu i zarysowania prac niezbędnych do przekształcenia elementów Backlogu Produktu w działający Przyrost produktu. Praca może ostatecznie odbiegać od planu pod względem ilości lub szacowanej pracochłonności. Niemniej podczas Planowania Sprintu Zespół Deweloperski rozplanowuje swoje działania w stopniu dającym mu możliwość prognozowania, co może zostać zrealizowane w nadchodzącym Sprincie. W trakcie tego spotkania praca planowana na pierwsze dni Sprintu jest rozpisywana na mniejsze porcje, często nie większe niż jeden dzień roboczy. Zespół Deweloperski samodzielnie organizuje się pod kątem wykonania pracy wynikającej z Backlogu Sprintu, zarówno podczas Planowania Sprintu, jak i zgodnie z potrzebami w trakcie Sprintu.

Właściciel Produktu może pomóc wyjaśniać wybrane elementy Backlogu Produktu i osiągać kompromisy. Jeśli Zespół Deweloperski ustali, że ma za dużo lub za mało pracy, może renegocjować wybrane elementy Backlogu Produktu z Właścicielem Produktu. Zespół Deweloperski może także zaprosić na to spotkanie inne osoby, aby wsparły Zespół wiedzą techniczną lub domenową.

Zanim Planowanie Sprintu dobiegnie końca, Zespół Deweloperski powinien być w stanie wytłumaczyć Właścicielowi Produktu i Scrum Masterowi, w jaki sposób ma zamiar pracować, organizując się samodzielnie, by osiągnąć Cel Sprintu i wytworzyć oczekiwany Przyrost.

### Cel Sprintu

Cel Sprintu to założenie, które ma zostać spełnione w ramach Sprintu poprzez implementację wybranych elementów Backlogu Produktu. Dostarcza on Zespołowi Deweloperskiemu wskazówek w jakim celu tworzony jest Przyrost. Jest on definiowany podczas Planowania Sprintu. Cel Sprintu daje Zespołowi Deweloperskiemu pewną swobodę co do sposobu, w jaki dana funkcjonalność zostanie zaimplementowana. Zazwyczaj wybrane elementy Backlogu Sprintu stanowią spójną funkcję systemu, która może stać się Celem Sprintu. Celem Sprintu może także być cokolwiek, co zapewni spójność i spowoduje, że członkowie Zespołu Deweloperskiego będą pracowali razem, a nie nad odrębnymi inicjatywami.

W trakcie Sprintu Zespół Deweloperski pamięta o Celu Sprintu. Aby go osiągnąć, wprowadza nowe funkcjonalności i wdraża nowe technologie. Jeśli podczas Sprintu charakter prac okazuje się inny niż oczekiwał Zespół Deweloperski, Zespół Deweloperski podejmuje współpracę z Właścicielem Produktu, aby renegocjować zakres Backlogu Sprintu.

### Codzienny Scrum

Codzienny Scrum jest wydarzeniem dla Zespołu Deweloperskiego, ograniczonym czasowo do piętnastu minut. Codzienny Scrum organizowany jest każdego dnia Sprintu. W jego trakcie Zespół Deweloperski planuje pracę na najbliższe dwadzieścia cztery godziny. W ten sposób, poprzez inspekcję pracy wykonanej od poprzedniego Codziennego Scruma, zespół optymalizuje współpracę i efektywność oraz prognozuje nadchodzącą pracę w Sprincie. W celu zredukowania złożoności Codzienny Scrum odbywa się codziennie w stałym miejscu i o stałej porze.

Zespół Deweloperski używa Codziennych Scrumów do oceny postępów prac nad realizacją Celu Sprintu i trendu względem ukończenia pracy opisanej w Backlogu Sprintu. Codzienny Scrum zwiększa szanse osiągnięcia przez Zespół Deweloperski Celu Sprintu. Każdego dnia Sprintu samoorganizujący się Zespół Deweloperski powinien wiedzieć jak będzie przebiegała dalsza współpraca by możliwe było osiągnięcie Celu Sprintu i stworzenie przed końcem Sprintu oczekiwanego Przyrostu.

Przebieg spotkania jest ustalany przez Zespół Deweloperski. Może ono być przeprowadzane na wiele sposobów, jeśli tylko pozostaje poświęcone postępom prac w kierunku osiągnięcia Celu Sprintu. Niektóre Zespoły Deweloperskie wykorzystują pytania, inne prowadzą dyskusje.
Oto przykład pytań, które mogą być wykorzystywane podczas tego spotkania:

  * Co zrobiłem wczoraj, co pomogło Zespołowi Deweloperskiemu przybliżyć się do osiągnięcia Celu Sprintu?
  * Co zrobię dzisiaj, co pomoże Zespołowi Deweloperskiemu przybliżyć się do osiągnięcia Celu Sprintu?
  * Czy widzę jakiekolwiek przeszkody mogące uniemożliwić mi lub Zespołowi Deweloperskiemu osiągnięcie Celu Sprintu?

Cały Zespół Deweloperski lub poszczególni jego członkowie często spotykają się bezpośrednio po Codziennym Scrumie, aby szczegółowo przedyskutować wybrane zagadnienia, dostosować lub zredefiniować plan prac na pozostałą część Sprintu.

Scrum Master zapewnia, że Zespół Deweloperski spotyka się w ramach Codziennego Scruma, jednak to Zespół Deweloperski jest odpowiedzialny za przeprowadzenie tego spotkania. Scrum Master uczy Zespół Deweloperski, jak utrzymać piętnastominutowe ograniczenie czasowe Codziennego Scruma.

Codzienny Scrum jest wewnętrznym spotkaniem Zespołu Deweloperskiego. Jeśli inne osoby są obecne, Scrum Master upewnia się, że nie zaburzają one jego przebiegu.

Codzienne Scrumy poprawiają komunikację, eliminują inne spotkania, identyfikują i usuwają przeszkody, sprzyjają szybkiemu podejmowaniu decyzji i podnoszą poziom wiedzy Zespołu Deweloperskiego. Jest to spotkanie kluczowe dla procesu inspekcji i adaptacji.
