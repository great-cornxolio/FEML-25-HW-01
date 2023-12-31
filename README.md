# Домашнее задание «Классификация: Логистическая регрессия и SVM»
Нетология. Курс: Feature Engineering (FEML-25). Программа: "Data Scientist: с нуля до middle"
___

Цель: изучить применение модели логистической регрессии и метода опорных векторов в задаче бинарной классификации.

### Описание задания:
В домашнем задании нужно решить задачу классификации физических лиц по уровню дохода. Данные для обучения модели хранятся в файле [adult.csv](https://github.com/great-cornxolio/FEML-25-HW-01/blob/main/adult.csv).
Целевая переменная – уровень дохода income, который принимает два значения <=50K и >50K, поэтому классификация бинарная. Остальные признаки описывают персональную информацию – возраст, образование, семейное положение и т.д. Подробное описание признаков и их возможные значения можно получить самостоятельно, используя функции Python3 для анализа датасета (describe, unique и т.д) или прочитать информацию по [ссылке](https://www.cs.toronto.edu/~delve/data/adult/adultDetail.html).
Задачу классификации нужно решить при помощи обучения модели логистической регрессии и модели опорных векторов.

### Этапы работы:
1. Получите данные и загрузите их в рабочую среду.
2. Проведите первичный анализ.
Проверьте данные на пропуски. Удалите в случае обнаружения.
3. Постройте 1-2 графика на выбор. Визуализация должна быть основана на исследуемых данных и быть полезной (из графика можно сделать вывод об особенностях датасета/класса/признака).
4. Преобразуйте категориальные признаки.
5. Разделите выборку на обучающее и тестовое подмножество. 80% данных оставить на обучающее множество, 20% на тестовое.
6. Обучите модели логистической регрессии и опорных векторов на обучающем множестве.
7. Для тестового множества предскажите уровень дохода и сравните с истинным значением, посчитав точность предсказания моделей. Для этого используйте встроенную функцию score.
8. Сформулируйте выводы по проделанной работе.
Кратко опишите какие преобразования были сделаны с данными.
Сравните точность двух моделей.
Напишите свое мнение, в полной ли мере модели справились с поставленной задачей.

### [Решение](https://github.com/great-cornxolio/FEML-25-HW-01/blob/main/FEML_25_HW_01.ipynb)
