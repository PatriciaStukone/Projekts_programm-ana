lang=input("Выберите язык (ru),choose language (en)")
if lang =="ru":
guests=int(input("Сколько гостей будет присутствовать?"))
rent=float(input("Сколько стоит аренда помещения?(за час, в евро)"))
renttime=float(input("Сколько времени займёт праздник?"))
food=float(input("Сколько всего денег уйдёт на еду?(в евро)"))

rentsum=rent*renttime
allmoney=rentsum+food

print("Всего денег будет потрачено: ",allmoney)
print("Всего гостей будет присутствовать: ",guests)
print("На аренду помещения будет потрачено: ",rentsum)

elif lang =="en":
guests = int(input("How many guasts will be present?"))
rent=float(input("How much is the rental price?(per hour,in euros)"))
renttime=float(input("How long will the holiday take?"))
food=float(input("How much money will you spend on food?(in euros)"))

rentsum=rent*renttime
allmoney=rentsum+food

print("Total money will be spent: ",allmoney)
print("Total guests will be present: ",guests)
print("Rent of premises will be spent: ",rentsum)
