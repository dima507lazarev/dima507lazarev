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

    a = int(input("Введите стоимость приставки "))
b = int(input("Введите количество приставок "))
с = int(input("Введите скидку" ))
d = input("Выберите действие  O (Общая сумма) , M (стоимость одной приставки с учётом скидки) ")
