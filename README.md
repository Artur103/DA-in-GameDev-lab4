# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #4 выполнил:
- Хаврак Артур Юрьевич
- ФО-220007

Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

## Цель работы
Изучить работу перцептрона.

## Задание 1
### В проекте Unity реализовать перцептрон, который умеет производить вычисления: OR, AND, NAND, XOR.
1. OR. Работает корректно, обучается за 4 эпохи.
2. AND. Работает корректно, обучается за 7-8 эпох.
3. NAND. Работает корректно, обучается за 4-6 эпох.
4. XOR. Работает некорректно, т.к. XOR - нелинейная функция, перцептрон не может реализовать данную функцию (проблема Мински)

## Задание 2
### Построить графики зависимости количества эпох от ошибки  обучения. Указать от чего зависит необходимое количество эпох обучения.
- Графики: https://docs.google.com/spreadsheets/d/11LlQZhPCQ7QTlVgtikRbnyCtLM6hfgI1rYrjYrQmYE0/edit?usp=sharing
- Необходимое количество эпох зависит, прежде всего, от сложности функции. OR - самая простая, поэтому нужно всего 4 эпохи, чтобы перцептрон обучился.

## Задание 3
### Построить визуальную модель работы перцептрона на сцене Unity.
- Для построения визуальной модели я использовал сферы, компонент Rigidbody, метод OnTriggerEnter и метод OnCollisionEnter.

## Выводы
Я познакомился с перцептронами и реализовал их в Unity.

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
