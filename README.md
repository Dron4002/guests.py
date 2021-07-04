# guests.py
here i will create an invitation for each guest 

guests = ["Дедушка", "Веня", "Мама"]
print(guests)
for guest in guests:
    print(f"{guest} приглашаю тебя сегодня в 18:00")
guest1 = "Дедушка"
print(f"{guest1} прийти сегодня не сможет")
guests[0] = "Папа"
print(guests)
for guest in guests:
    print(f"{guest} приглашаю тебя сегодня в 18:00")
new_guest1 = guests.insert(0, "Сестра")
print(guests)
print(f"{guests[0]} наш новый гость")
new_guest2 = guests.insert(2, "Дядя")
print(guests)
print(f"{guests[2]} наш новый гость")
new_guest3 = guests.append("Тетя Аня, Дядя Антон")
print(guests)
print(f"{guests[5]} наши новые гости")
for guest in guests:
    if guest == guests[5]:
        print(f"{guests[5]} приглашаю вас сегодня в 18:00")
    else:
        print(f"{guest} приглашаю тебя сегодня в 18:00")
