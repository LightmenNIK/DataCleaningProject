Пример работы Marcdown

Marcdow. Что это такое?

<strong> Marcdown </strong> - простой язык разметки 

*Наклон этой записи*, _И этой_

**Выделение полужирным**. __И это__

# <center> 1. Это первый заголовок </center>

## 1.1. Подзаголовок первого заголовка

## 1.2. Второй подзаголовк первого заголовка

# 2. Второй заголовок
* Элемент 1
* Элемент 2
  * Элемент 2.1

[Яндкс Музыка](https://music.yandex.ru/home)

![Картинка](https://w.forfun.com/fetch/e4/e42780ae40f4800557b01690975a4f95.jpeg)

<center> <img src=Funny-cat-sunglasses_2560x1920-1.jpg width=500 height=400> </center>

```python
vaccine_combinations = covid_df['vaccines'].value_counts()[:10]
fig = plt.figure(figsize=(5, 5))
axes = fig.add_axes([0, 0, 1, 1])
axes.pie(
    vaccine_combinations,
    labels=vaccine_combinations.index,
    autopct='%.1f%%',
    explode = [0.1, 0.09, 0, 0, 0, 0, 0, 0, 0, 0]
);
```

> Это цитата

# Формулы 

$$ a = d + c$$

$ a = 30$

Initialized empty Git repository in D:\Програмирование\Програмирование\Задачи_SkillFactory\Bonus_Marckdown