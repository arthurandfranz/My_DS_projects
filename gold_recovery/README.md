# Прогнозированию доли востановления золота по параметрам исходного сырья
## Цель
На этапе процесса обработки золотосодержащей руды прогнозировать итоговую долю золота в сырье
## Задача 
В нашем распоряжении данные собранные на разных этапах процесса выделения золота из исходного сырья:  
- Параметры исходного cырья  
- Параметры сырья на разных этапах обработки  
- Параеметры технологического процесса  
- Параметры "хвостов" на разных этапах  

Мы хотим построить модель которая будет предсказывать долю востановления золота из руды лучше чем константная модель.  
Для создания модели использовали библиотеку CatBoost, для подбора гиперпараметров GridSearch и кросс-валидацию.  
## Результат:
Модель sMAPE 6.99 
Константная модель 7.77

## Библиотеки
CatBoost  
Scikit-learn
