# Лабораторная работа № 2
Google Colab: https://colab.research.google.com/drive/1Ewr9-L0cEZ8jbr7ZRhteEKhpC2xzbcx4#scrollTo=SkBrB5nCJyLW
## Контрольные вопросы
### 1. Что такое анонимная функция Python, как она работает
Функция «лямбда» используется для создания двух анонимных функций, которые извлекают только дату и время из объекта «datetime» соответственно. 
### 2. Что возвращает функция speedtest ()? Какой код используется для просмотра результатов функции speedtest ()?
Функция speedtest() создана для возврата результатов команды speedtest-cli.
print(speedtest())
### 3. Каким образом выполняется переименование столбцов датафрейма?
df_compact.rename(columns={'Measure A':'Ping (ms)', 
                           'Measure B': 'Download (Mbit/s)',
                           'Measure C': 'Upload (Mbit/s)'}, inplace=True)
### 4. Для чего в лабораторной работе импортируется библиотека NumPy?
Она не используется 🤨
### 5. Как выглядит код удаления столбца Datetime?
df_compact.drop(['Datetime'], axis=1, inplace=True)
