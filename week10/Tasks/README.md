# Седмица 10 - Указатели и псевдоними

Задача 1:
=
Да се декларират променливи a и b от целочислен, и c и d от реален тип. Да се изведат адресите на клетките от паметта, където компилаторът е разположил променливите.

Задача 2:
=
Да се декларират променливата a от целочислен тип и p указател на а. Да се използва указателя, за да се промени стойноста на а с 5.

Задача 3:
=
Да се изведат елементите на масив по три начина:
- с индексирана променлива
- с указател - името на масива
- с указател - помощна променлива

Задача 4:
=
Да се напише програма, която въвежда масив от цели числа и го извежда в обратен ред. Намира броя на четните, както и на нечетните елементи и извежда:
- 1 ако четните са повече
- 2 ако нечетните са повече
- 0 при равен брой

**Задачата да се реши с указател**

Задача 5:
=
Напишете функция с прототип(int arr[], int size),която принтира масив.

Задача 6:
=
Напишете функция с прототип(int matrix[][3], int row_size),която принтира матрица с 3 колони.

Задача 7:
=
Напишете следната функция с прототип void change(int* a, int* b), която
приема като аргументи две цели числа и добавя към техните стойности 4.
```
Вход: 
a = 4;
b = 1;

Изход: 
a = 8
b = 5

```

Задача 8:
=
Напишете следната функция с прототип void change(int& a, int& b), която
приема като аргументи две цели числа и добавя към техните стойности 4.
```
Вход: 
a = 4;
b = 1;

Изход: 
a = 8
b = 5

```

Задача 9:
=
Напишете функция с прототип void max(int arr[], unsigned size , int& max) , коятo по подаден масив от цели числа намира най-голямото число и го попълва като изходен параметър.
```
Вход: 
{3,5,23,14,6,13,21,1}

Изход: 
max = 23

```

Задача 10:
=
Напишете функция с прототип void replace(int x[], int size, int replaceWhat, int replaceWith), която заменя всяко срещане на replaceWhat в масива x с replaceWith.
```
Вход: 
{3,5,2,4,6,3,2,1}
replaceWhat = 2
replaceWith = 11

Изход: 
{3,5,6,4,6,3,6,1}
```
