# meshRouting

Приводится вариант фиксированной однопутевой маршрутизации для моделирования распределения трафика в Mesh-сети. Разработанная модель позволяет проанализировать работу маршрутизации в различных вариантах сети введенных пользователем. При решении задачи распределения потоков в качестве модели трафика используется самоподобный процесс – фрактальное бруоновское движение (fBM/D/1) характеризующееся коэффициентом Херста.

### Технологии

* Интерфейс: bootstrapp, HTML&CSS, JavaScript.

* Отрисовка узлов и линий связи: JavaScript, JQuery, JCanvas.

* Вычисления: Brython и JavaScript.

###  Links

[mesh routing app (web)](https://julikas.github.io/meshRouting/index.html)

[Иллюстрация - Алгоритм поиска оптимальных путей для каждой пары "источник-адресат"](https://github.com/julikas/meshRouting/blob/master/ccc.pdf)

[Иллюстрация - Алгоритм поиска оптимального маршрута](https://github.com/julikas/meshRouting/blob/master/bbb.pdf)

[Иллюстрация - Алгоритм Дейкстры](https://github.com/julikas/meshRouting/blob/master/deikstra.png)

### Источники

[github.com/bulygin69 - Алгоритм Дейкстры](https://github.com/bulygin69/dijkstra/blob/master/dijkstra2.py)

[brython.info](http://www.brython.info/)

Крылов В.В., Самохвалова С.С. Теория телетрафика и ее приложения. Спб.:  БХВ-Петербург,  2005.

Клейнрок Л. Коммуникационные сети. М.: Наука, 1975.

Информационные процессы, Том 1, No 2, 2001, стр. 103–125, Березко, Вишневский, Левнер, Федотов.

Информационные процессы, Том 8, No 3, 2008, стр. 173–192, Ляхов, Пустогаров, Шпилев.
