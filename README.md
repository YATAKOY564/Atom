# Atom

Закаряев Шамиль

Блокчейн - выстроенная по определённым правилам непрерывная последовательная цепочка блоков, содержащих информацию. 
Связь между блоками обеспечивается не только нумерацией, но и тем, что каждый блок содержит свою собственную хеш-сумму и хеш-сумму предыдущего блока. 
Изменение любой информации в блоке изменит его хеш-сумму. Чтобы соответствовать правилам построения цепочки, изменения хеш-суммы нужно будет записать в следующий блок, что вызовет изменения уже его собственной хеш-суммы. 
При этом предыдущие блоки не затрагиваются. Если изменяемый блок последний в цепочке, то внесение изменений может не потребовать существенных усилий. 
Но если после изменяемого блока уже сформировано продолжение, то изменение может оказаться крайне трудоёмким процессом. 
Дело в том, что обычно копии цепочек блоков хранятся на множестве разных компьютеров независимо друг от друга. 
Впервые термин появился как название полностью реплицированной распределённой базы данных, реализованной в системе «Биткойн», из-за чего блокчейн часто отождествляют с реестром транзакций в различных криптовалютах. 
Однако технология цепочек блоков может быть распространена на любые взаимосвязанные информационные блоки. 
Появившаяся в октябре 2008 года система Биткойн стала первым применением технологии блокчейн. 
В настоящее время блокчейн-технологии находят применение в таких областях, как финансовые операции, идентификация пользователей или создание технологий кибербезопасности, а также актуальны для банковских учреждений и государственных организаций. 
Являясь технологией построения массово-распределённых баз данных, блокчейн испытывает ряд специфических проблем, которые затрудняют его использование. 
Среди этих проблем можно назвать следующие:

1) Постоянный рост размера файлов блокчейна
2) Передача данных блокчейн происходит необратимо. В связи с этим отсутствует возможность отмены операции, даже если она была осуществлена ошибочно
3) Общее ограничение производительности блокчейна, связанное со спецификой работы алгоритмов консенсуса.


Окунев Данил

Криптография — это наука о способах преобразования информации с целью ее защиты от незаконных пользователей.
Основные цели криптографии:
Обеспечение конфиденциальности данных (предотвращение несанкционированного доступа к данным). Это одна из основных задач криптографии, для ее решения применяется шифрование данных, т.е. такое их преобразование, при котором прочитать их могут только законные пользователи, обладающие соответствующим ключом.
Обеспечение целостности данных — гарантии того, что при передаче или хранении данные не были модифицированы пользователем, не имеющим на это права. Под модификацией понимается вставка, удаление или подмена информации, а также повторная пересылка перехваченного ранее текста.
Обеспечение аутентификации. Под аутентификацией понимается проверка подлинности субъектов (сторон при обмене данными, автора документов, и т.д.) или подлинности самой информации. Частным случаем аутентификации является идентификация — процедура доказательства субъектом того, что он действительно является именно тем, за кого себя выдает. Во многих случаях субъект X должен не просто доказать свои права, но сделать это так, чтобы проверяющий субъект (Y) не смог впоследствии сам использовать полученную информацию для того, чтобы выдать себя за X. Подобные доказательства называются «доказательствами с нулевым разглашением».
Обеспечение невозможности отказа от авторства — предотвращение возможности отказа субъектов от совершенных ими действий (обычно — невозможности отказа от подписи под документом). Эта задача неотделима от двойственной — обеспечение невозможности приписывания авторства. Наиболее яркий пример ситуации, в которой стоит такая задача — подписание договора двумя или большим количеством лиц, не доверяющих друг другу. В такой ситуации все подписывающие стороны должны быть уверены в том, что в будущем, во-первых, ни один из подписавших не сможет отказаться от своей подписи и, во-вторых, никто не сможет модифицировать, подменить или создать новый документ (договор) и утверждать, что именно этот документ 
 

Иcтория криптографии
Криптография наcчитывает около 4 тыcяч лет. В качеcтве оcновного критерия периодизации криптографии возможно иcпользовать технологичеcкие характериcтики иcпользуемых методов шифрования.
Первый период (приблизительно c 3-го тыcячелетия до н. э.) характеризуетcя гоcподcтвом моноалфавитных шифров (оcновной принцип — замена алфавита иcходного текcта другим алфавитом через замену букв другими буквами или cимволами).
Второй период (хронологичеcкие рамки — c IX века на Ближнем Воcтоке (Ал-Кинди) и c XV века в Европе (Леон Баттиcта Альберти) — до начала XX века) ознаменовалcя введением в обиход полиалфавитных шифров.
Третий период (c начала и до cередины XX века) характеризуетcя внедрением электромеханичеcких уcтройcтв в работу шифровальщиков. При этом продолжалоcь иcпользование полиалфавитных шифров.
Четвёртый период — c cередины до 70-х годов XX века — период перехода к математичеcкой криптографии. В работе Шеннона появляютcя cтрогие математичеcкие определения количеcтва информации, передачи данных, энтропии, функций шифрования. Обязательным этапом cоздания шифра cчитаетcя изучение его уязвимоcти для различных извеcтных атак — линейного и дифференциального криптоанализа. Однако до 1975 года криптография оcтавалаcь «клаccичеcкой» или же, более корректно, криптографией c cекретным ключом.
Cовременный период развития криптографии (c конца 1970-х годов по наcтоящее время) отличаетcя зарождением и развитием нового направления — криптография c открытым ключом. Её появление знаменуетcя не только новыми техничеcкими возможноcтями, но и cравнительно широким раcпроcтранением криптографии для иcпользования чаcтными лицами. Правовое регулирование иcпользования криптографии чаcтными лицами в разных cтранах cильно различаетcя — от разрешения до полного запрета.
Примеры шифрования
1.	Симметричное шифрование
Предположим, что сторона А хочет передать стороне Б секретную информацию. Стоп. А, Б — это всё некрасиво и неудобно. Именно поэтому в криптографии принято называть стороны обмена информацией именами Алиса (Alice) и Боб (Bob).
Итак, как Алиса может передать сообщение, чтобы никто, кроме Боба, не смог прочесть его? Необходимо как-то изменить эти данные по заранее согласованному с Бобом алгоритму. Простейшим способом реализации такой задачи является подстановочный шифр — алгоритм, при котором каждая буква сообщения заменяется на другую букву. Например, вместо первой буквы алфавита («А») Боб c Алисой будут использовать третью («В»), вместо второй («Б») — четвертую («Г») и так далее.
В этом случае алгоритмом шифрования является сдвиг букв алфавита, а ключом — цифра 2 (сдвиг на две позиции). Любой, кто знает алгоритм и ключ, сможет расшифровать сообщение Алисы.
2.	Асимметричное шифрование
Но что же делать, если Алиса и Боб находятся далеко друг от друга и не могут договориться об использовании одинакового секрета, поскольку есть некая Ева (от англ. eavesdropper — подслушивающий), которая так и хочет узнать тайны Алисы и Боба? В этом случае Боб может отправить Алисе замок, ключ от которого есть только у него. Алиса положит письмо в коробку и запрёт её на этот замок. Теперь ни Алиса, ни Ева не смогут открыть коробку и прочесть письмо.
Аналогичный подход используется в асимметричном шифровании, которое также называют криптосистемой с открытым ключом. В примере с Алисой и Бобом секретным ключом Боба будет ключ от замка, а публичным ключом условно можно назвать сам замок. Отправка Алисе замка — это алгоритм согласования ключей.
Наиболее популярным алгоритмом шифрования с открытым ключом является RSA. Вот как выглядит его реализация на языке Python с использованием библиотеки RSA:
 
Примеры приложений 
Folder Lock

Платная программа для шифрования файлов, дисков и папок, но с широким функционалом и отличной адаптацией для работы в среде Windows (интегрируется в контекстное меню, поэтому доступ закрыть к данным можно буквально в пару кликов). Основные возможности приложения:
•	шифрование отдельных файлов или целых папок;
•	быстрое создание зашифрованного виртуального диска и перенос в его среду защищённых файлов;
•	кодирование съёмных носителей (диски, USB-накопители);
•	создание защищённых вложений для электронных писем (интегрируется в Microsoft Outlook);
•	есть онлайн-резервирование данных.
Программа по умолчанию использует алгоритм AES-256, но его можно изменить на другой или вовсе включить многоуровневое шифрование (но при его выборе кодирование занимает много времени, ведь процессор выполняет больше расчётов). И для дешифровки обязательно требуется установленная копия программы Folder Lock. Без неё файл открыть не получится.
WinRAR

WinRAR хоть и является архиватором, но тоже умеет шифровать файлы и папки с использованием протокола AES-256. Также поддерживается 256-разрядное хеширование BLAKE2sp. Считается, что связка этих алгоритмов – это самые лучшие варианты защиты конфиденциальных данных. Без пароля получить доступ к файлам не получится.
Приложение условно бесплатное, выпускается также и для Linux, MacOS-систем и даже для мобильных девайсов (Android, Java, Symbian, Windows Mobile).

Мачнев Иван

Разработка веб-сайтов: проекты и примеры кода для разработки 
веб-сайтов и веб-приложений на разных языках программирования и фреймворках.

Веб-разработка — процесс создания веб-сайта или веб-приложения. 
Основными этапами процесса являются веб-дизайн, вёрстка страниц, программирование на стороне клиента и сервера,
а также конфигурирование веб-сервера.

Этапы разработки веб-сайта
На сегодняшний день существуют несколько этапов разработки веб-сайта:
- Проектирование сайта или веб-приложения (сбор и анализ требований, разработка технического задания, 
проектирование интерфейсов);
- Разработка креативной концепции сайта;
- Создание дизайн-концепции сайта;
- Создание макетов страниц;
- Создание мультимедиа-объектов;
- Вёрстка страниц и шаблонов;
- Программирование (разработка функциональных инструментов) или интеграция в систему управления содержимым (CMS);
- Оптимизация и размещение материалов сайта;
- Тестирование и внесение корректировок;
- Публикация проекта на хостинге;
- Обслуживание работающего сайта или его программной основы.

Создание технического задания
1. Цели и назначение сайта.
2. Аудитория сайта.
3. Технические характеристики.
4. Содержание сайта (структура сайта с подробным описанием элементов и функций каждой страницы).
5. Интерактивные элементы и сервисы (формы обратной связи, поиск на сайте, форум на сайте).
6. Формы (отправки на почту, подписки на рассылку, обратной связи).
7. Система управления содержимым (контентом).
8. Требования к материалам.
9. Перенос на хостинг.

HTML-верстка
Утверждённый дизайн передаётся HTML-верстальщику, который «нарезает» графическую картинку на отдельные рисунки,
из которых впоследствии складывает HTML-страницу. В результате создаётся код, который можно просматривать с помощью браузера.
А типовые страницы впоследствии будут использоваться как шаблоны.
