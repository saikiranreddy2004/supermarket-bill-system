# supermarket-bill-system
  #python program on supermarket billing system
a=0
b=0
sum=0
while True:
    item=input('Item: ')
    unit=input('Enter the Unit: ')
    a=int(unit)
    price=input('Enter the Price: ')
    b=int(price)
    sum +=a*b
    next_item=input('is there another item ? ')
    if next_item !='yes':
        print('please choose betwee Yes or No')
    if next_item =='no':
        break
print('Total Items purchased : ',sum)
