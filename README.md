# progect_5
Работа по проекту 5 -компьютер говорит НЕТ.
Удалось: обработать данные, сформировать submission, протестировать перультаты на kaggle.
Итоговые результате - ROC AUC на data_train - 0.743. На data_test 0.7386.
Результат есть в итоговом списке на kaggle. 
ник - Nazhiya Imuh 
Сделана попытка найти границу отсечения, чтобы разносить итоговые данные на 0 и 1 и
построить матрицу читать confusion_matrix и посчитать f1_score и accuracy_score.
Оптимальная граница отсечения 0,17. При ней f1_score = 0.35, accuracy_score = 0.76.
Найдены гиперпараметры:
Лучший penalty: l2 
Лучшее C: 2.7825594022071245
