# Finding-Equilibria-in-the-Traffic-Assignment-Problem-with-Primal-Dual-Gradient-Methods-for-Stable-Dy

Проект 2. Сравнительный анализ различных алгоритма поиска равновесного распределения транспортных потоков по путям в моделях Бэкмана и Стабильной динамики.

План работ. 
Прочитать статью https://arxiv.org/pdf/2008.02418.pdf (если что-то будет не понятно, можно подсмотреть детали тут https://arxiv.org/pdf/2003.12160.pdf) и ознакомиться с питон-кодом к статье (при возникновении вопросов стоит писать Мерузе Кубентаевой kubentayeva-m@yandex.ru). 
Описанная в статье задача и численные алгоритмы на практике многократно используются при изучении вопросов перераспределения транспортных потоков. Проведите исследование, какой из численных методов, описанных в статье более чувствителен к удачному выбору точки старта. Мотивация в такой постановке следующая: часто бывает уже известно равновесие в транспортной сети, но сеть немного поменялась, например, поменялись характеристики части ребер (пропускные способности изменились), нужно найти новое равновесие. Понятно, что если поменялись характеристики небольшого числа ребер, то мы вправе ожидать, что равновесия будут близкими. Разные алгоритмы могут иметь разную чувствительность к выбору точки старата. В данном контексте интересны такие алгоритмы, которые наиболее чувствительны к удачному выбору точки старта. P.S. Наиболее интересны сравнения алгоритмов типа условного градиента и различных двойственных методов для модели Бэкмана.
