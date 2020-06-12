## Vector
Реализация динамического массива.

* Размер структуры не превышает `max(void*, T)`;
* В реализации используется small-object и copy-on-write оптимизации;
* Все функции обеспечивают максимальную степень exception guarantee, которую возможно.
