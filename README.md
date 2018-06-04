# Rosbank
Rosbank ML competition.

Здесь приводятся основные элементы обработки данных, дающие 1-е место по первой задаче и 2-е место по второй.

utils.ipynb - обработка изначальных данных, которые должны быть в файлах init_train.csv и init_test.csv

time.ipynb - обработка времени

money.ipynb - обработка денежной информации

mcc.time - обработка времени с учетом МСС-кодов. Пока без комментариев

mcc.money - обработка денег с учетом МСС-кодов. Аналогично без комментариев

файлы "handcrafted_mcc_features.npy" и "mcc_codes.npy" содержат инфу об мсс кодах. Первый словарь получен частично с помощью тематического моделирования, частично вручную. Второй массив - данные с сайта mcc-codes.ru. Это словари. Открывать с помощью np.load(файл).item()
