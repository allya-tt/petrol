# petrol
Project-developer: Raspopova A.

volume_g=float(input("Введите объем бензина в галлонах:"))
volume_lit=volume_g*3.78541
barr=volume_g/19.5
co2=20*volume_g
term=115000*volume_g
etan=term/75700
price=3*volume_g
print(volume_lit, "литров", barr, "баррелей", co2, "фунтов углекислого газа", etan, "галлонов этанола", price, "долларов")
a=28050000
b=250000
print("В Новосибирске расход бензина составляет:", b," литров в день")
print("В стране расход бензина составляет:", a," литров в год")

