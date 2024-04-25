# spbu_machine_learning_spring_2024
Практики по курсу "Машинное обучение" для программы "большие данные и распределенная цифровая платформа" ПМ-ПУ СПбГУ
## Введение
Проклятие размерности, выбор признаков

## Особенности линейной регрессии
Рассмотрены различные особенности днных, а также следующие положения линейной регрессии:
* Линейность: взаимосвязь между зависимыми и независимыми переменными линейна.
* Гомоскедастичность: дисперсия ошибок постоянна на всех уровнях независимых переменных.
* Нормальность: ошибки подчиняются нормальному распределению.
* Нет мультиколлинеарности: независимые переменные не сильно коррелируют друг с другом.
* Нет эндогенности: между ошибками и независимыми переменными нет связи.
## Регуляризация
Рассмотрены L1, L2, Elastic-Net-регуляризация
## KDE
Разобран метод оценки распределения выборочной СВ с помощью ядер. 

## LOESS
Рассмотрены локальная регрессия с помощью LOESS (LOWESS).
Обзор: https://rafalab.dfci.harvard.edu/pages/754/section-03.pdf
Тред по интерпретации/оценке значимости: https://stats.stackexchange.com/questions/557381/how-do-i-interpret-or-explain-loess-plot

Статьи: 

William S. Cleveland: "Robust locally weighted regression and smoothing
scatterplots", Journal of the American Statistical Association, December 1979,
volume 74, number 368, pp. 829-836.

William S. Cleveland and Susan J. Devlin: "Locally weighted regression: An
approach to regression analysis by local fitting", Journal of the American
Statistical Association, September 1988, volume 83, number 403, pp. 596-610.

## STL
Статья:
Robert P. Cleveland: "STL: A Seasonal-Trend decomposition procedure based on LOESS"
https://www.wessa.net/download/stl.pdf
