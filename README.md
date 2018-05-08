![](https://github.com/alxmamaev/image-storage/blob/master/dota2/2018-05-08_15-49-47.png)
# AI-Academy - Dota2Competition
*AI-Academy* - спецпроект Сбербанка, направленный на популяризацию образования в сфере искусственного интеллекта среди школьников. В рамках проекта проходил хакатон, в рамаах которого участникам предлагалось решить задачу предсказания результата матча игры Dota 2.

Здесь представлено мое решение, которое на отборочном и финальном этапе заняло первое место.

## Задача
![](https://github.com/alxmamaev/image-storage/blob/master/dota2/2018-05-08_16-00-17.png)

### Данные
Скачать данные: [тык](https://ai-academy.datasouls.com/public/dota2_data_final.zip)
* train_matches.jsonl, test_matches.jsonl - полные описания матчей ("сырые" данные);
* train_features.csv, test_features.csv - таблицы с признаками от организаторов;
* train_targets.csv - таблица с исходами матчей из обучающей выборки, в частности указание победителя;
* sample_submission.csv - пример файла с решением.


## Решение
* Solution.ipynb - решение задачи с онлайн этапа
* Data-Preprocessing.ipynb - ноутбучек по извлечению фич на финальном этапе
* Catboost-01-Copy1.ipynb - ноутбучек с обучением модельки для финального этапа

## Видео ML-тренировки
Помимо этого, на пятом датафесте, на секции ML-тренировок я подробно разобрал это решение.


[![Watch video](https://img.youtube.com/vi/YSQqHlQwQDY/0.jpg)](https://www.youtube.com/watch?v=YSQqHlQwQDY)
