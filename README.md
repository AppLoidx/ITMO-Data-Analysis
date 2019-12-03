# Data Analysis Laboratory Works

* Tasks as [pdf](tasks.pdf)
* Task's files [here](Files)
* Some Theory: [here](Theory.md)

Выполнение:
* [Анализ данных с помощью сценариев **ЧТО-ЕСЛИ**](task-1) - **100%**
* [Расчет характеристик марковских процессов](task-2) - **50%**
* [Линейная оптимизация](task-3) - **100%**
* [Распределение случайных величин](task-4) - **75%**
* [Генерация случайных чисел и анализ выборки данных ](task-5) - **100%**
* [Анализ временных рядов](task-6) - **90%** (функция `РОСТ`)
* [Регрессионный анализ](task-7) - **100%**
* [Сводные таблицы](task-8) - **80%** (мастер сводных таблиц)
<hr>

### Контрольные вопросы
#### Расчет характеристик марковских процессов
1. Объясните назначение и принцип работы средства MS Excel Подбор
параметра.
2. Какой процесс можно считать марковским?

3. Как можно определить установившиеся значения вероятностей
состояний системы?


4. Сформулируйте правило, по которому составляется система
уравнений для определения вероятностей состояний системы.
<hr>

#### Линейная оптимизация
1. Объясните назначение и принцип работы средства MS Excel Поиск
решения.
2. Какие элементы включает в себя задача оптимизации?
3. Что такое целевая функция?
4. В каком случае модель является оптимизационной?
5. Из каких соображений формулируются ограничения?
<hr>

#### Распределение случайных величин
1. Сформулируйте определение понятия “закон распределения
    случайной величины”.

2. Приведите примеры применения экспоненциального закона
    распределения для описания случайных событий.

3. Покажите порядок ввода формул в Excel.

4. Перечислите параметры нормального распределения.

5. Какие случайные события можно описать с помощью нормального
    закона распределения?

6. Что такое дисперсия?

7. Раскройте понятие квантиля.

8. Каким образом определяется степень свободы?

9. Перечислите действия при применении критерия согласия.

   <hr>

   

#### Генерация случайных чисел и анализ выборки данных 

1. Сформулируйте определение понятия “закон распределения случайной величины”. 
2. Приведите примеры применения нормального закона распределения для описания случайных событий. 
3. Что показывают показатели асимметрии и эксцесса? 
4. Перечислите этапы процесса построения гистограммы. 
5. В чем отличие систематической выборки от случайной? 

####  Анализ временных рядов 

1. Дать определение временного ряда. Привести примеры. 
2. Перечислить задачи, решаемые при изучении временных рядов.
3. На какие части можно разделить модель временного ряда? 
4. Что такое тренд? Какими моделями он может быть описан?
5. Какими способами можно выделить тренд?
6. Раскрыть принцип скользящего среднего. 

####  Регрессионный анализ 

1. Что называется регрессионной моделью? 
2. Привести общий вид регрессионной модели.
3. Каким образом можно проверить значимость коэффициента регрессии?
4. Какой метод обычно используется при определении коэффициентов регрессионной модели? 

####  Работа со сводными таблицами 

1. Перечислите основные задачи, решаемые с помощью сводных таблиц.
2. Какую роль играют при построении сводных таблиц срезы?
3. Каким образом можно добавить новое поле в сводную таблицу?
4. Каким образом можно добавить вычисляемый элемент в сводную таблицу?
5. Какие методы обычно используются при анализе данных в сводной таблице? 

<h2 align=center><img src="https://i.pinimg.com/originals/1f/e0/a5/1fe0a5a6c70e32b454727f6417dae87c.webp" /></h2>
#### Расчет характеристик марковских процессов
1. Объясните назначение и принцип работы средства MS Excel Подбор
параметра.
>«Подбор параметра» - ограниченный по функционалу вариант надстройки «Поиск решения». Это часть блока задач инструмента «Анализ «Что-Если»».

>В упрощенном виде его назначение можно сформулировать так: найти значения, которые нужно ввести в одиночную формулу, чтобы получить желаемый (известный) результат.

>Функция «Подбор параметра» идеально подходит для решения уравнений с одним неизвестным

2. Какой процесс можно считать марковским?
>Пусть имеется некоторая система S, состояние которой меняется с течением времени (под системой S может пониматься техническое устройство, производственный процесс, вычислительная машина, информационная сеть и т. д.). Если состояние системы S меняется во времени случайным, заранее непредсказуемым образом, говорят, что в системе протекает случайный процесс.
>Случайный процесс, протекающий в системе S, называется марковским (или “процессом без последействия”), если он обладает следующим свойством: для каждого момента времени t0 вероятность любого состояния системы в будущем (при t>t0) зависит только от ее состояния в настоящем (при t= t0) и не зависит от того, когда и каким образом система пришла в это состояние (т. е. как развивался процесс в прошлом).
3. Как можно определить установившиеся значения вероятностей
состояний системы?
>События называются состояниями системы, а испытания – изменениями состояний системы
4. Сформулируйте правило, по которому составляется система
уравнений для определения вероятностей состояний системы.
>Уравнение Колмогорова-Чепмена относится к классу рекуррентных соотношений, позволяющих вычислить вероятность состояний марковского случайного процесса на любом шаге (этапе) при наличии информации о предшествующих состояниях
Чаще всего этот термин используется в теории однородных марковских случайных процессов, где ![](https://wikimedia.org/api/rest_v1/media/math/render/svg/9fad655e50cd9c580b3469fb54014b61f6afbed3) — оператор, преобразующий распределение вероятностей в начальный момент времени в распределение вероятности в момент времени t ![](https://wikimedia.org/api/rest_v1/media/math/render/svg/779a95be1122a71184a6815648f16396cfd5e1fe)
<hr>

#### Линейная оптимизация
1. Объясните назначение и принцип работы средства MS Excel Поиск
решения.
>Процедура «Поиск решения» (MS EXCEL) представляет собой мощный инструмент для выполнения сложных вычислений. Она позволяет находить значения переменных, удовлетворяющих указанным критериям оптимальности, при условии выполнения заданных ограничений. Наилучшие результаты она позволяет получить для задач выпуклого программирования. Такие результаты оптимизации оформляются в виде отчетов трёх типов: результаты, устойчивость и пределы.
2. Какие элементы включает в себя задача оптимизации?
> переменные x1, x2…xn (в средстве Поиск решения ячейки,
содержащие значения этих переменных, называются изменяемыми
ячейками);

> целевая функция (ячейка, содержащая значение этой функции
называется целевой ячейкой);

> ограничения (для применения средства Поиск решения
ограничения могут быть записаны на рабочем листе и затем
указаны в диалоговом окне либо заданы непосредственно в этом
окне без записи на рабочем листе). При задании ограничений
отдельно указываются функции ограничений gj(X) и вектор правых
частей ограничений bj
3. Что такое целевая функция?
> Задача оптимизации – поиск экстремума, то есть, максимального или минимального значения определенной функции, которую называют целевой функцией, например, это может быть функция прибыли – выручка минус затраты
4. В каком случае модель является оптимизационной?
5. Из каких соображений формулируются ограничения?
<hr>

#### Распределение случайных величин
1. Сформулируйте определение понятия “закон распределения
случайной величины”.
> Каждая случайная величина подчиняется определенному закону
распределения, т.е. правилу, по которому задается соответствие между
значением случайной величины и вероятностью ее появления. Закон
распределения может быть задан таблично или в виде функции распределения
2. Приведите примеры применения экспоненциального закона
распределения для описания случайных событий.
> применяют в теории надежности при
описании режима нормальной эксплуатации техники. Экспоненциальное распределение играет важную роль в задачах телекоммуникации, так как позволяет моделировать интервалы времени между наступлением событий.
3. Покажите порядок ввода формул в Excel.
> шо?
4. Перечислите параметры нормального распределения.
> Значение, для которого рассчитывается вероятность

> Среднее значение

> Стандартное отклонение

> Интегральная

5. Какие случайные события можно описать с помощью нормального
закона распределения?
>когда возможные значения лежат вокруг некого среднего значения, например, при
стрельбе по мишени, измерении какого-либо параметра и т.д.
6. Что такое дисперсия?
> Диспе́рсия случа́йной величины́ — мера разброса значений случайной величины относительно её математического ожидания.
7. Раскройте понятие квантиля.
> Кванти́ль в математической статистике — значение, которое заданная случайная величина не превышает с фиксированной вероятностью.
8. Каким образом определяется степень свободы?
> Количество степеней свободы — это количество значений в итоговом вычислении статистики, способных варьироваться. Иными словами, количество степеней свободы показывает размерность вектора из случайных величин, количество «свободных» величин, необходимых для того, чтобы полностью определить вектор.

> Количество случайных величин, каждая из которых имеет нормальное распределение
9. Перечислите действия при применении критерия согласия.
> Найти вероятность через =ХИ2РАСП(), а потом значение вероятности =ХИ2ОБР
10. В чем причина отличия результатов решения задач из пунктов 2.3 и
2.4?
> Входные данные другие :)))



#### Генерация случайных чисел и анализ выборки данных 

1. Сформулируйте определение понятия “закон распределения случайной величины”. 

   > Каждый закон распределения – это некоторая функция, полностью описывающая случайную величину с вероятностной точки зрения. 

2. Приведите примеры применения нормального закона распределения для описания случайных событий. 

   >Нормальное распределение часто встречается в природе. Например, следующие случайные величины хорошо моделируются нормальным распределением:
   >
   >**отклонение при стрельбе**;
   >
   >**[погрешности измерений](https://ru.wikipedia.org/wiki/Погрешность_измерения)** (однако погрешности некоторых измерительных приборов имеют иное распределение);
   >
   >**некоторые характеристики живых организмов в популяции**.

   > Такое широкое распространение этого распределения связано с тем, что оно является [бесконечно делимым](https://ru.wikipedia.org/wiki/Бесконечно_делимое_распределение) непрерывным распределением с конечной дисперсией. Поэтому к нему в пределе приближаются некоторые другие, например [биномиальное](https://ru.wikipedia.org/wiki/Биномиальное_распределение) и [пуассоновское](https://ru.wikipedia.org/wiki/Распределение_Пуассона). Этим распределением моделируются многие недетерминированные физические процессы

   

3. Что показывают показатели асимметрии и эксцесса? 

   > Показатели асимметрии – характеризуют симметрию распределения данных около своего центра: коэффициент асимметрии, эксцесс 

4. Перечислите этапы процесса построения гистограммы. 

   1. Анализ данных -> Гистограмма
   2.  
      1. **Входной интервал** – вводится диапазон ячеек, содержащих анализируемые данные.
      2. В поле **Интервал карманов** вводится диапазон ячеек, содержащих значения границ интервалов (параметр является необязательным, в этом случае набор интервалов создается автоматически).
      3. **Параметры вывода** – указывается место, где будет указана таблица частот.
      4. Для вывода гистограммы следует установить флажок опции **Вывод графика**. Флажки опций Парето (отсортированная гистограмма) и Интегральный процент (накопленные) частоты следует оставить сброшенными.  

5. В чем отличие систематической выборки от случайной? 

   > **Случайная выборка** строится таким образом, чтобы каждый объект генеральной совокупности имел одинаковую вероятность быть выбранным, и при этом объекты отбираются независимо друг от друга. 

   > Для получения **систематической выборки** в генеральной совокупности определяют случайную начальную точку и отбирают элементы, начиная с этой точки через постоянный интервал (с постоянным шагом отбора). Для того чтобы из совокупности N получить систематическую выборку размером n, необходимо выбирать элементы с шагом N / n. Данный метод используется в том случае, когда есть предварительно пронумерованные списки, платежные поручения, приходные и расходные чеки и т.д., в подобных случаях он быстрее и проще, чем метод простой случайной выборки. 



####  Анализ временных рядов 

1. Дать определение временного ряда. Привести примеры. 

   > **Временной ряд** представляет собой последовательность данных, описывающих объект в последовательные моменты времени. 

   > Примеры временных рядов: 
   >
   > в экономике – курсы акций, валют, объемы продаж, объем производства; 
   >
   > в метеорологии – температура, интенсивность осадков, сила ветра, давление, 	влажность и т.д.; 
   >
   > в гидрологии – уровни воды в водоемах; 
   >
   > в технике – параметры сигналов. 

2. Перечислить задачи, решаемые при изучении временных рядов.

   >  Выявление структуры временного ряда необходимо для того, чтобы построить [математическую модель](https://ru.wikipedia.org/wiki/Математическая_модель) того явления, которое является источником анализируемого временного ряда. Прогноз будущих значений временного ряда используется для эффективного принятия решений. 

3. На какие части можно разделить модель временного ряда? 

   > Детерминированную (неслучайную) и случайную

   > **Детерминированная** (закономерная) часть – это составляющая временного ряда, элементы которой вычисляются по определенному правилу как функция от времени 

   > **Случайный** компонент временного ряда придает хаотичность и непредсказуемость. Для описания и анализа данного компонента используют понятия и методы теории вероятностей и математической статистики. 

4. Что такое тренд? Какими моделями он может быть описан?

   > **Трендом** (trend – тенденция, направление) временного ряда называют изменяющийся, нециклический компонент, описывающий влияние долговременных факторов, эффект которых сказывается постепенно. К таким факторам относятся изменение демографических характеристик, рост потребления, технологическое и экономическое развитие. 

   

5. Какими способами можно выделить тренд?

   > Метод аналитического выравнивания (диаграмма)

   > Использование статических функций (функции)

   не уверен, на самом деле...

6. Раскрыть принцип скользящего среднего. 

   >  Метод формирует значения, которые в каждой точке определения равны среднему значению исходной функции за предыдущий период 

   > Скользящие средние обычно используются с данными временных рядов для сглаживания краткосрочных колебаний и выделения основных тенденций или циклов. Наиболее часто используются простое скользящее среднее (среднее арифметическое), экспоненциальное скользящее среднее и взвешенное скользящее среднее 

   



####  Регрессионный анализ 

1. Что называется регрессионной моделью? 

   > Походу, это все таблички в 7-ом задании. Например, линейная регрессия

2. Привести общий вид регрессионной модели.

   > y = b0 + b1 * x - линейная регрессия
   >
   > y = b0 + b1 * x1 + ... + bm * xm - множественная

3. Каким образом можно проверить значимость коэффициента регрессии?

   > F – расчетное значение F-критерия Фишера, определяемое как отношение факторной дисперсии к остаточной. Значимость F – значение уровня значимости, соответствующее вычисленному значению F 

   > Рассчитанный уровень значимости Значимость F = 0,002 меньший 0,05 подтверждает значимость величины коэффициента детерминации. 

4. Какой метод обычно используется при определении коэффициентов регрессионной модели? 

   > Функция регрессия???



####  Работа со сводными таблицами 

1. Перечислите основные задачи, решаемые с помощью сводных таблиц.
2. Какую роль играют при построении сводных таблиц срезы?
3. Каким образом можно добавить новое поле в сводную таблицу?
4. Каким образом можно добавить вычисляемый элемент в сводную таблицу?
5. Какие методы обычно используются при анализе данных в сводной таблице? 