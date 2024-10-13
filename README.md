# 1C
Отбор на кафедру 1С

Понимание правил игры:
1. За раз можно переложить лишь одну карту (а не как в пауке все упорядоченные).
2. Карту меньшего номинала можно переложить на карту ЛЮБОГО большего номинала.

Идеи:
1. Пасьянс не сходится, если есть "барьер". Под барьером подразумевается ряд одинаковых по номиналу карт (не обязательно на одном уровне) таких, что над ними лежат только карты меньшего номинала. В таком случае, чтобы не происходило на "поверхности", это не даст возможности переместить "барьерные" карты. Исключением будет такой расклад, при котором под одной из барьерных карт лежит уже упорядоченный набор и только он. То есть если барьерной картой является дама, то под ней первым на столе лежит туз, далее король, потом эта дама.
2. Задача напоминает Ханойские башни, но с хаотично разбросанными в начале кольцами (большое кольцо -- большой номинал, маленькое -- маленький).
3. Хочется решать задачу с помощью графов и переходов между состояниями. Тогда сходимость пасьянса будет равносильна наличию пути из начального расположения карт в выигрышное. Но состояний слишком много.
