# Защита персональных данных клиентов
## Описание
Нужно защитить данные клиентов страховой компании «Хоть потоп». Необходимо разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию.
Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось.
## Цель
Разработать модель для анонимизации персональных данных клиентов страховой компании
## Используемые библиотеки
- `pandas`
- `numpy`
- `sci-kit learn`
## Результаты

В ходе работы было проделано:

1)Загружены и изучены данные.

2)Качество линейной регресии не изменилось от использования исодной матрици и исходной матрицы, умноженную на обратимую.

3)Создан алгоритм преобразования данных.

4)Исследован алгоритм преобразования данных и проверена метрика R2 для данных без преобразования и с ним.

По результатам работы использования матричных операций можно увидеть, что данные очень просто зашифровать от распознования, имея правильную матрицу.
