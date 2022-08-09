## "Время года"

### Задание

По заданному номеру месяца выведите строку — название времени года, соответствующего данному месяцу.

### Формат входных данных

Дано целое число m, номер месяца. 1 <= m <= 12

### Формат выходных данных

Вывести название времени года. Весна/Зима/Лето/Осень

### Решение задачи

```python
number = int(input('month:'))
if number == 12 or number == 1 or number == 2:
    print('Winter')
elif number == 3 or number == 4 or number == 5:
    print('Spring')
elif number == 6 or number == 7 or number == 8:
    print('Summer')
elif number == 9 or number == 10 or number == 11:
    print('Autumn')
else:
    print('Nothing')
```

---

### Данные для самопроверки

| Дано | Результат |
| :---: | --- |
|    1    | Зима |
|    3    | Весна  |
|    5    | Весна  |
|    6    | Лето  |
|    10    | Осень  |
|    12    | Зима  |
