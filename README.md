# test-1

age = int(input("quel age avez vous ?"))
print (age)
if age < 18:
    print("7€")
    prix = 7
else:
    print("12€")
    prix = 12
pop_corn = input("Voulez vous du pop corn ? (oui, non)")
if pop_corn == "oui":
    prix = prix + 5

print(prix)
