# Python
q = [26, True, 7.6, [1, 2], "abs"]
for i in range(len(q)):
    print("Тип переменной в списке:", type(q[i]))
    
    
    
    
    
    
    l = input("Введите элементы списка: ").split()
l[:-1:2], l[1::2] = l[1::2], l[:-1:2]
print(l)





num = int(input('Введите месяц в виде целого числа от 1 до 12: '))
if num==12 or num==1 or num ==2:
    print('Зима')
elif num==3 or num==4 or num==5:
    print('Весна')
elif num == 6 or num == 7 or num == 8:
    print('Лето')
elif num == 9 or num == 10 or num == 11:
    print('Осень')
else:
    print('Вы ввели неверное число')
    
    
    
    a = input().split()

for ind, i in enumerate(a,1):
    print(ind, i[0:10])
    
    
    
    
    
    
    my_list = [7, 5, 3, 3, 2]
a = int(input("Новый элемент рейтинга: "))
if a > 0:
    my_list.append(a)
    my_list.sort(reverse = True)
    print(f"Новый рейтинг: {my_list}")
else:
    print("Ошибка")







products = []
names = []
prices = []
counts = []
measures = []
q = int(input('Введите количества'))
q = q+1
for i in range(1, q):

    print('товар' ,i)
    name = input("Название: ")
    price = int(input("Цена: "))
    count = int(input("Количество: "))
    measure =input("Единица измерения: ")
    products.append((i, {'название': name, 'цена': price, 'количество': count, 'eд': measure}))

for i in products:
    names.append(i[1].get('название'))
    prices.append(i[1].get('цена'))
    counts.append(i[1].get('количество'))
    measures.append(i[1].get('eд'))

print("список товаров:", products)
    
