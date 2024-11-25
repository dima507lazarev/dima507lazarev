item1 = input("Введите название предиета: ")
item2 = int(input("Веведите прочность предмета: "))
item3 = float(input("Введите эффективность: "))

print(f"Название = {item1}\n"
      f"Прочность = {item2}\n"
      f"Эффективность = {item3}\n"
      f"ТипДанных: {type(item1)}\n"
      f"ТипДанных: {type(item2)}\n"
      f"ТипДанных: {type(item3)}")
      x = 25.656345235
print(round(x, 2))
print(int(x))
Операторы арифметические:
+  - сложение 2 +2 =4
 - - вычитание 4 -2 = 2
 *  - умножение 4 * 2 =8
 /   - деление 3 / 2 = 1,5
// - Цепочное деление  3 // 2 = 1
** - Возведение в степень 3 ** 3 = 27
% - остаток от деления 11 % 3 = 2
принты
 print("Nothing\n"
      "will work\n"
      "unless you do\n")

print("Anyone who\n"
      "\tstops\n"
      "\t\t learning os old,\n"
      "\t\t\t whether at twenty or eighty\n")



kd=float(input("Введите курс доллара "))
k=float(input("Введите курс евро "))
kk=float(input("Введите курс юани "))
print("1) Перевести из рублей в доллары и евро и юфни\n2)Перевести из доллара и евро и юани в рубли\n")
vibor=int(input("Выберите ваше действиве\n"))
if vibor==1:
    ryb=float(input("Ведите количество рублей "))
    s1=ryb/kd
    s2=ryb/k
    s3=ryb/kk
    print ("Сумма вашего перевода из рублей в долоры = ",'{:.2f}'.format(s1))
    print("Сумма вашего перевода из рублей в евро = ", '{:.2f}'.format(s2))
    print("Сумма вашего перевода из рублей в юани = ", '{:.2f}'.format(s3))
elif vibor==2:
    kold=float(input("Введите количество долларов"))
    kol = float(input("Введите количество евро"))
    ko = float(input("Введите количество юани"))
    s1=kold*kd
    s2=kol*k
    s3=ko*kk
    print("Сумма вашего перевода из доллра в рубли = ",' {:.2f}'.format (s1))
    print("Сумма вашего перевода из евро в рубли = ", ' {:.2f}'.format(s2))
    print("Сумма вашего перевода из юани в рубли = ", ' {:.2f}'.format(s3))
else:
    print("Ошибка!Введите пожалуйста только 1 или 2")
    exit(0)


    

a = int(input("Введите число:")) 
print(f"Четное: {number} * 2 = {number * 2}") 
 
if number % 2 == 0: 
    print(number * 2) 
else: 
    print(number / 4)



    print(f"Регистрация") 
regLogin = input(f"Введите логин") 
regPassword = input(f"Введите пароль") 
Reg = False 
 
if len(regLogin) >=5 and len(regPassword) >= 8: 
    print("красава") 
    Reg = True 
else: 
    print("заново") 
 
if Reg: 
 authLogin = input("Введите логин:  ") 
authPassword = input("Введите пароль:  ") 
 
if not Reg: 
     print("Верно") 
 
else: 
 print("иди *****")



a = int(input("Введите время в секундах от 0 до 84600"))
b = input(f"Выберете действие S , M , H")
s = 84600 - a
H = s // 3600
S = 3600 // H
M = s // 60
S = 60 * M
if b == "H":
    print(H, 'H', end = '')
if b == "M":
    print(M, 'M', end = '')
if b == "S":
    print(S, 'S', end = '')
   
    
    
a = int(input("Введите диаметр окружности"))
b = input("Выберите действие P , S")
P = 2 * 3.1415 * a
S = 3.1415 * a**2
if b == "P":
    print(P, 'P', end = '')
if b == "S":
    print(S, 'S', end = '')

P = int(input("Введите стоимость приставки"))
A = int(input("Введите количество приставок"))
S = int(input("Введите скидку"))
x = int(input("Чтобы узнать общую сумму введите 1.\n Чтобы узнать стоимость одной приставки нажмите 2.\n"))
t = (P * A)-(P*A*S/100)
o = P - (P*S/100)
if x == 1:
    print("Общая сумма составит", t)
else:
    print("Стоимость одной приставки составит", o)

    c = bit // s
b = s // 60
a = b // 3600
if x == 1:
    print ("За часов", a )
elif x == 2:
    print ("За минут", b )
else:
    print ("За секунд", c )
    S = int(input("Введите размер файла"))
s = int(input("Введите скорость интернета в Мегабайтах в секундах"))
x = int(input("Чтобы узнать за сколько часов скачается фаил выберите 1.\n Чтобы узнать за сколько минут нажмите 2.\n Чтобы узнать за сколько секунд нажмите 3.\n "))

Mbait = S * 1024
a = Mbait // s
b = s // 60
c = s // 3600
if x == 1:
    print("За секунд ", a)
if x == 2:
    print("За минут ", b)
if x == 3:
    print("За часов ", c)


s = int(input("Введите количество часов"))
if s < 0 or s > 23: print('Ошибка')
elif s <= 7: print("Good night")
elif s <= 12: print("Good Morning")
elif s <= 18: print("Good Day")
else:
    print("Good Evening")


numder = int(input("Введите номер 1 - 7 "))
if numder < 0 or numder > 7: print('Ошибка')
elif numder <= 1: print("Понедельник")
elif numder <= 2: print("Вторник")
elif numder <= 3: print("Среда")
elif numder <= 4: print("Четверг")
elif numder <= 5: print("Пятница")
elif numder <= 6: print("Суббота")
elif numder <= 7: print("Воскресенье")



numder = int(input("Введите номер 1 - 12 "))
if numder < 0 or numder > 12: print('Ошибка')
elif numder <= 1: print("Январь")
elif numder <= 2: print("Февраль")
elif numder <= 3: print("Март")
elif numder <= 4: print("Апрель")
elif numder <= 5: print("Май")
elif numder <= 6: print("Июнь")
elif numder <= 7: print("Июль")
elif numder <= 8: print("Август")
elif numder <= 9: print("Сентябрь")
elif numder <= 10: print("Октябрь")
elif numder <= 11: print("Ноябрь")
elif numder <= 12: print("Декабрь")


number = int(input("Введите число"))
if number > 0: 
    print("Numder is positive")
elif number < 0: 
    print("Numder is negative")
else:
    print("Numder is equal to zero")


num = int(input("Введите число"))
if not num%5:
    print("Число чётное и кратное 5")
if num%2 and num%5:
    print("Число не четное и не кратное 5")
elif not num%2:
    print("Число четное и не кратное 5")


    kol= int(input("Введите количество литров"))
ctom = int(input("Введите стоимость за литр"))
rast = int(input("Введите пройденое растояние"))
pas = kol * ctom
rsa = kol / rast * 100
print(f"Потрачено на топливо: {rsa}\nРасход топлива на 100 км: {pas}")







dox = int(input("Введите ваш доход"))
if dox < 10000:
    nal  = 0.05
if dox > 50000:
    nal = 0.15
if 10000 <= dox and dox <= 50000:
    nal = 0.1
sum = nal * dox
print(sum)




r = float(input("Введите рост"))
v = int(input("Введите вес"))
bmi = v / r ** 2
if bmi < 18.5:
    print("Недостаточный вес")
if 18.5 <= bmi <= 24.9:
    print("Норма")
if 24.9 <= bmi <= 29.9:
    print("Избыток")
if 29.9 <= bmi <= 31:
    print("Ожирение")


a = int(input("введите 1 число"))
b = int(input("введите 2 число"))
c = int(input("введите 3 число"))
d = int(input("Выберите действие 1 если умножить \n 2 если сложить"))
if d == 1:
    print("умножение=", a*b*c)
if d == 2:
    print("сложение=", a+b+c)
    
    
    
x = int(input("Введите первое число"))
z = int(input("Введите второе число"))
c = int(input("Введите третье число"))
o = int(input("Выберите действие\n 1 найти максимум\n 2 найти минимум\n 3 найти среднеарифметическое"))
if o ==  1:
    max_num = max(x, z, c)
    print("Максимальное", max_num)
elif o == 2:
    min_num = min(x, z, c)
    print("Минимальное", min_num)
elif o == 3:
    average = (x + z + c) / 3
    print("Среднеарифметическо", average)





metr = int(input("Введите количество метров"))
o = int(input("Выберете действие: нажмите 1 чтоб перевести в мили\n 2 чтоб перевести дюймы \n 3 чтоб перевести в ядры "))
m = metr * 0.000621371
d = metr * 39.3701
if o == 1:
    miles = metr * 0.000621371
    print("количество миль", miles)
elif o == 2:
    daim = metr * 39.3701
    print("количество дюймов", daim)
elif o == 3:
    idr = meters * 1.09361
    print("количество ядров", idr)


count = 0
while count < 10:
    count += 1
    print(count, end="" )




begin = int(input("begin >> "))
end = int(input("end >> "))



while begin < end:
    begin += 1
    print(begin, end=" ")


   while True:    userChoise = input("Действие: [+][0 - ваыход] >> ")
    
    if userChoise == '+':
        print ('Посчиталась сумма')
        
    elif userChoise == '0':
        print('Всего хорошего')
        break
    else:
        print('Вы выбрали что то не то?')


count = 0
while count < 10:
    count += 1
    if count == 6:
      continue
    print(count, end="" )**


continue = пропуск хода
break = завершить цикл


num = int(input("Введите число"))
mul = 1
while True:
    result = num * mul
    print(f"{num} * {mul} = {result}")
    mul += 1
    if result > 50:
        break



for i in range(1, 50):
    if i % 3 == 0:
        continue
    if i % 7 == 0:
        break
    print(i)



b = 1000
print(f"Остаток в банке: {b}")
c = int(input("Сколько вы хотите снять "))
while b >= 0:
    s = b - c
    print(f"на счету осталось: {s}")
    if s <= 0:
        break


Казино
import random
a = input("Что вы будете ставить")
Casino = [" z ", " zov ", " goida "]
for i in range(1, 4):
    print (random.choice(Casino),random.choice(Casino),random.choice(Casino))



цикл for\ range \ итератор \ laze evaluation
итератор - обьект который позволяет перебирать элементы по 
одному запоминая своё текущее положение
итерация - один шаг цикла
range() - встроенная функция котораягенерирует последовательность цисел 
range(start, stop, step) -> range(1, 10, 3)
- start ( по иумолчанию 0)
- stop конечное число ( не включается в последовательность)
- step (по умолчанию 1) шаг изменения чисел
-------
for
инерируемые обьекты
(1,2,3,4,5) - const (неизменяемый список)
[1.2.3.4.5]
for i in range(start, stop):
   код_для_выполнения
   for i in range(10):
   print(i, end = " ")
   
   string_ = "Hello world"
   for i in string_:
   if i == 'l'
   print(i, end = " ")
---------------
   библиотека и модуль
   random() - это функция модуля random из Python
   необходлимо для возвращения числа в диапазоне:
    от 0.0 до 1.0
    -------
    import random
    
    print(random.random()) - 0.0 -> 1.0
    
     print(random.randint(1, 10)) 1 -> 10 вкл
     
     print(random.uniform(1.5, 10.5))
     
     name = ["Валера", "Марк", "Виктор"]
     print(random.choice(name))-  рандомный выбор из последовательности
     
     cards = [1,2,3,4,5]
     print(random.shuffle(cards)) перемешивание
     
 ----------   


n = input("Введите число")
z = 0
for i in range(1 , n)
z = z + i
print(f"Ввод {a} ---> Вывод:", z + a, end=" ")
print(f"(", end="")
for i in range(1 , n)
z = z + i
print (f"{i}+", end="")
print(f"{a})", end="")





Y = 10
X = 10

for i in range(X):
    for j in range(Y):
        if i == 0:
            print('z', end=" ")
        elif i !=0 and j > 1:
            print(" ", end="")
        if j == 0 and i > 0:
            print('z', end="")
        elif j != 0 and i > 0:
            print(" ", end="")
        if j == 9 and i > 0:
            print('z', end=" ")
        elif j != 9 and i < 0:
            print(" ", end=" ")
        if  i == 9 and j > 0 and j < 9:
            print("z", end=' ')
        else:
            print(" ", end=' ')
    print( )


 a = int(input("Введите первое число"))
b = int(input("Введите второе число"))
s = a + b
print("Сложение: ",s)
v = a - b
print("Вычитание: ",v)
m = a * b
print("Умножение: ",m)
d = a / b
print("Деление: ", d)
x = (a / b) * 100
print("Проценты:", x)



import turtle
import math

t = turtle.Turtle()
t.speed(0)
t.color("red")
turtle.bgcolor("black")

def corazon(n):
    x = 16 * math.sin(n) ** 3
    y = 13 * math.cos(n) - 5 * \
        math.cos(2*n) - 2*math.cos(3*n) - \
        math.cos(4*n)
    return x, y

t.penup()
for i in range(15):
    t.goto(0, 0)
    t.pendown()
    for n in range(0, 100, 2):
        x, y = corazon(n/10)
        t.goto(x*i, y*i)
    t.penup()

t.hideturtle()
turtle.done()



import time

def countdown():
    seconds = int(input("Ваедите количество секунд для обратного отсчта"))
    while seconds > 0:
        mins , secs = divmod(seconds, 60)
        timer = f'{mins:02}:{secs:02}'
        print(timer, end='\r')
        time.sleep(1)
        seconds -= 1
    print("Время вышло")

countdown()
