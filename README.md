## Репозиторий проектов из курса "Специалист по Data Science" Яндекс.Практикум
### Мои учебные проекты:

#### [1. Исследование: Музыка больших городов]()
__Задача:__ выдвинуты гипотезы:  
Музыку в двух городах — Москве и Санкт-Петербурге — слушают в разном режиме;   
Списки десяти самых популярных жанров утром в понедельник и вечером в пятницу имеют небольшие отличия;  
Население двух городов предпочитает разные музыкальные жанры.  
__Выполнено:__ Данные очищены от дубликатов и пропусков. Проведена аналитика сгруппированных данных.  
__Инструменты:__ `pandas`.  

#### [2. Исследование надежности заёмщиков.]()
__Задача:__  Оценка влияния различных характеристик заемщиков на факт погашения кредита в срок.  
__Выполнено:__ Данные очищены от выбросов, дубликатов и пропусков, проведена лемматизация. Проведена аналитика важности признаков для определения категорий клиентов, клиенты разбиты на категории. Составлен портрет идеального заемщика.  
__Инструменты:__ `pandas, pymystem3, nltk.stem, collections`.  

#### [3. Исследование объявлений о продаже квартир.]()
__Задача:__  Анализ признаков влияющих на стоимость квартир в регионе.  
__Выполнено:__ Данные сохранены, пропуски заполнены, в том числе с применением случайных величин в диапазоне нормального распределения признаков. По совокупности признаков определены самые близкие к центру квартиры, а также районы с самыми высокими и низкими ценами. Найдена средняя скорость продажи для разных типов недвижимости. Выявлена динамика повышения цен.  
__Инструменты:__ `pandas, pyplot, seaborn`.  

#### [4. Определение перспективного тарифа для телеком компании.]()
__Задача:__  Анализ статистики использования услуг мобильного оператора клиентами с целью определения приоритетного тарифа для фирмы.  
__Выполнено:__ Рассмотрены два тарифных плана нижней и верхней ценовой категории. На основании статистического анализа, выявлены характерные особенности поведения клиентов: затраты, продолжительность использования тарифа, лояльность, стабильность. Проверены гипотезы о поведении клиентов на разных тарифах. Определен и статистически подтвержден наиболее выгодный для оператора тариф.  
__Инструменты:__ `pandas, seaborn, pyplot, numpy, stats, reduce`.  

#### [5. Прогноз продаж в интернет-магазине.]()
__Задача:__  Исследование продаж компьютерных игр в различных регионах и определение стратегии рекламной компании.  
__Выполнено:__ Проведен анализ данных о продажах игр по всему миру. Определены пики популярности и периоды жизни игровых консолей. Проведен анализ корреляции мнения критиков, журналистов и пользователей с реальными продажами. Составлены портреты клиентов по странам с предпочтениями к платформам, жанрам, конкретным продуктам. Проверены гипотезы о самых популярных жанрах и платформах.  
__Инструменты:__ `pandas, seaborn, pyplot, numpy, stats, statistics`.  

#### [6. Модель рекомендаций тарифных планов.]()
__Задача:__  Модель рекомендаций пользователям альтернативных тарифных планов.  
__Выполнено:__ На основании использования клиентами услуг действующего тарифного плана, настроена модель рекомендации. Использовались RandomForestClassifier, DecisionTreeClassifier, LogisticRegression. Проверка модели на адекватность используя DummyClassifier.  
__Инструменты:__ `pandas, sklearn, numpy, seaborn, matplotlib, accuracy_score, train_test_split`.

#### [7. Отток банковских клиентов.]()
__Задача:__  Модель для предсказания оттока банковских клиентов.  
__Выполнено:__ Датасет очищен, признаки кодированы с помощью StandardScaler, использованы DecisionTreeClassifier, RandomForestClassifier, LogisticRegression. Гиперпараметры подобраны кроссвалидацией, применен апсемплинг для устранения дисбаланса классов, для оценки моделей использовалась ROC кривая, F1, accuracy.  
__Инструменты:__ `pandas, sklearn, numpy, seaborn, matplotlib, accuracy_score, precision_score, recall_score, roc_auc_score, roc_curve, f1_score, StandardScaler, shuffle`.  

#### [8. Предсказание прибыли нефтедобывающей компании.](https://github.com/supercurlyman/praktikum.yandex/blob/master/oil_wells.ipynb)
__Задача:__  Модель предсказаний прибыли компании и выбор прибыльных регионов для разработки нефти.  
__Выполнено:__ В избранном регионе собраны характеристики для скважин: качество нефти и объём её запасов. Построена модель для предсказания объёма запасов в новых скважинах, использована LinearRegression с метрикой RMSE. Определены скважины с самыми высокими оценками значений добычи. Рассчитаны точки безубыточности, риски убытков, выбран регион с максимальной суммарной прибылью отобранных скважин.  
__Инструменты:__ `pandas, sklearn, numpy, matplotlib, mean_squared_error, StandardScaler`.  

