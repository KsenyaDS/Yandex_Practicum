# Телеком 

**Цель проекта**

Оператор связи «Ниединогоразрыва.ком» хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

**Результат проекта**

На этапе исследовательского анализа данных выявили, что

- у ушедших клиентов ежемесячный платеж больше, по сравнению с остальными клиентами
- пришло много новых клиентов с низким ежемесячным платежем
- на услугу телефонии ежемесячный платеж вырос у постоянных клиентов
  
Отток клиентов связан скорее всего с подорожанием услуги телефонии для постоянных клиентов. Возможно необходимо предложить постоянным клиентам промокоды и специальные условия на услугу телефонии.

На этапе предобработки данных:

- привели данные к нужному типу
- заполненили пропущенные значения
- объединили таблицу
- добавили новые признаки
- удалили ненужные столбцы
- закодировали данные
- масштабировали численные значения
- определили признаки
- разделили данные на выборки
- написали вывод

На этапе построения моделей:

- подбрали параметры для нескольких моделей
- обучили 5 моделей классификации
- проверили качество моделей с помощию метрик accuracy, ROC-AUC
- посчитали время предсказания моделей на тестовой и обучающей выборке
  
В итоге:

- наилучший результат качества предсказания на обеих выборках у модели LGBMClassifier
- наибольшее время предсказания у модели LGBMClassifier
- если важнее время предсказания, то посоветуем выбрать оператору модель CatBoostClassifier
- если важнее качество предсказания, то посоветуем выбрать оператору модель LGBMClassifier
  
**Используемые инструменты**

pandas, numpy, sklearn, matplotlib

**Ссылка на nbviewer**

https://nbviewer.org/github/KsenyaDS/Yandex_Practicum/blob/master/2.%20Credit_Scoring/kredit.ipynb 

