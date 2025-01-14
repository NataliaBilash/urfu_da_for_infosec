**Polars**

- Считайте датасет из файла [train.csv](https://disk.yandex.ru/i/gSHLosoobj_JsA) (это данные о выживаемости на Титанике) с помощью _polars_  - **1 балл**
- Выведите основную информацию о датасете: информацию о типах данных, число пропусков, средние значения и т.д. - **1 балл**

 - Посчитайте количество пассажиров каждого класса (Pclass) - **1 балл**

- Выведите количество выживших мужчин и женщин на корабле - **1 балл**

- Выведите часть таблицы с пассажирами, возраст которых больше 44 лет - **1 балл**


**Ускорение работы с pandas**

 - Считайте датасет из файла [train.csv](https://disk.yandex.ru/i/gSHLosoobj_JsA) (это данные о выживаемости на Титанике) с помощью _pandas_ 
 - Посчитайте средний возраст пассажиров и его стандартное отклонение  с помощью bottleneck - **1 балл**

 - Для каждого пассажира умножьте значение столбца `Fare` на 1.3, если класс его билета - 1 или 2, и на 1.1, если класс его билета - 3. Сохраните результаты как новый столбец `Fare_new`. (При реализации расчета используйте любые альтернативы методу `iterrows`) - **1 балл**

**Оптимизация типов pandas**

 - Считайте датасет из файла [Housing.csv](https://disk.yandex.ru/d/xZ32QkNqOgyq3A) (это данные о ценах домов) с помощью _pandas_ 
 - Для каждого столбца определите оптимальный с точки зрения потребления памяти тип данных - напишите свои выводы в комментариях  - **2 балла**
 - Поменяйте типы данных столбцов датафрейма на выбранные вами в прошлом пункте и сравните потребление памяти до и после оптимизации - **1 балл**

Для сдачи домашней работы запушьте файлы в ветку **hw_1** в вашем репозитории, создайте pull-request и отправьте на ревью @pacifikus
