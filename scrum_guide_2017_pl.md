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
