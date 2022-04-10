while True:
	print("================")
	print("KALKULATOR MOD")
	print("================")
	
	op1 = int(input("masukan jumlah: "))
	op2 = input("masukan operasi contoh +, -, *, /,: ")
	if op2 not in("+","-","*","/"):
		print("maaf operasi yg anda masukan salah")
		break
		
	op3 = int(input("masukan jumlah: "))
	
	if op2 == "+":
		print("hasil dari",op1,"+",op3,"=",op1+op3)
	elif op2 == "-":
          print("hasil dari",op1,"-",op3,"=",op1-op3)
	elif op2 == "*":
          print("hasil dari",op1,"*",op3,"=",op1*op3)			
	elif op2 == "/":
          print("hasil dari",op1,"/",op3,"=",op1/op3)
          print(" ")
