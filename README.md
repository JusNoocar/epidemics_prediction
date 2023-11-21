Прогнозирование распространения эпидемий на примере COVID-19  

Суть нашего сервиса: 
Прогнозирование распространения различных эпидемий 
Помощь работникам мед учреждений в более чётком понимании ситуации в стране, возможность подготовки к новым волнам заболеваний.  

Что можем предложить: 

Понятный и интуитивный интерфейс  
Использование библиотек Scikit-learn, NumPy, Pandas, Arima для обучения ИИ 
Хорошая точность прогнозирования(среднее MAE по регионам = 14 человек)  

Будущие обновления 

Увеличение списка болезней которые мы сможем прогнозировать 
Использование более точных моделей или нейронных сетей 

Использованные данные:  

Данные, использованные для обучения модели   
https://data.humdata.org/dataset/ca5f6ac0-035b-47eb-b118-7a0a3357e71a 
Таблица, в которой указано количество заболевших коронавирусом, регион и дата наблюдений 
Данные взяты в промежуток 26-03-2020 по 04-02-2021, по 85 регионам России(для модели были использованы 83 региона) 

Используемая модель: 

Авто-регрессия ARIMA с гиперпараметрами:  
p(порядок авторегрессии) = 5 
d(порядок интегрирования) =1 
q(порядок скользящего среднего) = 0 

Для модели были использованы следующие метрики: 

Mean absolute error, mean absolute percentage error 

Дополнительно:  

сайт, где можно выбрать 
регион, дату,  
заболевание и узнать  
прогноз модели 
на эту дату
