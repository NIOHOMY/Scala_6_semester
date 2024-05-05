<h2 align="center">Scala_6_semester</h2>

<h3 align="center">Лаболаторные работы </h3>
<h2 align="center">1</h2>

<h3 align="center">
  Работа с файлом.
</h3>

Создать текстовый файл в качестве имени файла использовать свою фамилию. <br/>
Файл содержит текст на английском языке набор слов, из них.


* обязательно есть повторяющиеся и пустые строки.

Над файлом произвести следующие действия:<br/>

1. найти заданное слово
2. посчитать количество вхождений заданного слова;
3. разбить текст на слова и удалить пустые строки.
4. Создать наборы RDD на основе массивов (целочисленных ассоциативных) и применить к ним Transformation reduce и map.

<div align="center">
  <a href="https://github.com/NIOHOMY/Scala_6_semester/blob/main/labs/1/lab1.txt">Перейти к лабораторной 1</a>
</div>

##

<h2 align="center">2</h2>

<h3 align="center">
  Работа с DataFrame
</h3>

По данным, приведенным ниже — нужно составить отчет по успеваемости, ответив на вопросы

```sql
Класс Имя Возраст Пол Предмет Оценка
12 Ivanov 25 old man сhinese 50
12 Ivanov 25 old man mathematics 60
12 Ivanov 25 old man еnglish 70
12 Petrov 20 old man сhinese 50
12 Petrov 20 old man mathematics 50
12 Petrov 20 old man еnglish 50
12 Sidorova 19 old women сhinese 70
12 Sidorova 19 old women mathematics 70
12 Sidorova 19 old women еnglish 70
12 Lunin 25 old man сhinese 50
12 Lunin 25 old man mathematics, 60.
12 Lunin 25 old man еnglish 70
13 Yakovlev 25 old man сhinese 60 лет
13 Yakovlev 25 old man mathematics, 60 .
13 Yakovlev 25 old man еnglish 70
13 Volkov 20 old man сhinese 50
13 Volkov 20 old man mathematics 60
13 Volkov 20 old man еnglish 50
13 Zaitseva 19 old women сhinese 70
13 Zaitseva 19 old women mathematics 80
13 Zaitseva 19 old women еnglish 70
13 Lisitsin 20 old man сhinese 30
13 Lisitsin 20 old man мужской mathematics 60
13 Lisitsin 20 old man еnglish 50
13 Sorokina 18 old women сhinese 70
13 Sorokina 18 old women mathematics 80
13 Sorokina 18 old women еnglish 70
```

Нужно ответить на следующие вопросы:

1. Сколько человек сдало тест? <br/>
1.1 Сколько человек в возрасте до 20 лет сдают тест? <br/>
1.2 Сколько человек, которым исполнилось 20 лет, сдают экзамен? <br/>
1.3 Сколько человек старше 20 лет сдают экзамен? <br/>
2. Всего несколько мальчиков сдают экзамен? <br/>
2.1 Сколько девушек сдают экзамен? <br/>
3. Сколько человек сдают экзамен в 12 классе? <br/>
3.1 Сколько человек в 13 классе сдают экзамен? <br/>
4. Каков средний балл по языковым предметам? <br/>
4.1 Какова средняя оценка предметов по математике? <br/>
4.2 Какова средняя оценка предметов по английскому языку? <br/>
5. Каков средний балл одного человека? <br/>
6. Каков средний балл 12 класса? <br/>
6.1 Какова средняя общая оценка для мальчиков в 12 классе? <br/>
6.2 Каков средний общий балл 12 девушек? <br/>
6.3 Точно так же ищите соответствующие результаты класса 13 <br/>
7. Какова самая высокая оценка китайского языка во всей школе? <br/>
7.1 Какой минимальный балл для 12 класса по китайскому языку? <br/>
7.2 Какой самый высокий класс математики в 13 классе? <br/>
8. Сколько девочек в 12 классах с общим баллом более 150? <br/>
9. Каков средний балл учащегося с общим баллом, превышающим 150 баллов, по математике, превышающей или равной 70, и возрастом, превышающим или равным 20 годам? <br/>

<div align="center">
  <a href="https://github.com/NIOHOMY/Scala_6_semester/blob/main/labs/2/lab2.txt">Перейти к лабораторной 2</a>
</div>

##
