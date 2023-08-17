# media_aritmetica
bim1 = int(input("Nota bimestre 1: "))
bim2 = int(input("Nota bimestre 2: "))
bim3 = int(input("Nota bimestre 3: "))
bim4 = int(input("Nota bimestre 4: "))

media = float(bim1 + bim2 + bim3 + bim4)/4
print ("Média: ",media)

if media >=9:
   print ("Aprovado")
elif media >= 7:
    print ("Aprovado com louvor")
elif media < 7:
     print("Reprovado")
