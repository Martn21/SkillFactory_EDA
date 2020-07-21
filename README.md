# SkillFactory_EDA
Разведывательный анализ данных
Анализируем данные об успеваемости учащихся (файл stud_math.xls)
Ноутбук содержит комментарии к каждому шагу, здесь только выводы
Собственно числовых данных в наборе только 3 столбца: Возраст(age), Количество пропусков(absences)  и итоговая оценка(scores)
Имеется слабая отрицательная корреляция между возрастом и успеваемостью, -0.16. Очень слабая положительная корреляция (0.10) между успеваемостью и пропусками занятий - довольно неожиданно. Вероятно на уровне погрешности.
С помощью теста Стьюдента проаналлизирована значимость категориальных факторов для конечной оценки
Найдены статистически значимые различия для колонки address - вероятно есть "неблагоприятные" районы, влияющие на успеваемость
Найдены статистически значимые различия для колонки Medu - подчеркивает роль матери в процессе воспитания
Найдены статистически значимые различия для колонки Mjob - подчеркивает роль матери в процессе воспитания
Найдены статистически значимые различия для колонки failures ? непонятно, что такое failures
Найдены статистически значимые различия для колонки higher - логично: кто хочет учиться дальше, готовится к экзаменам лучше
Найдены статистически значимые различия для колонки romantic - похоже романтические отношения мешают успеваемости
