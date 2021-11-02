- 👋 Hi, I’m @coldplay20
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
Algoritmo detarea
	Definir clientes,bola Como Entero
	Definir total,descuento como real
	Escribir "Ingresa el total de clientes"
	leer clientes
	Mientras clientes > 0
		Escribir "Ingresa el total de la compra"
		leer total
		Escribir "Ingresa un numero"
		Escribir "1 = Bola roja"
		Escribir "2 = Bola amarilla"
		Escribir "3 = Bola blanca"
		leer bola
		
		si bola > 0 y bola < 4 Entonces
			si bola == 1 Entonces
				descuento = total * .40
			SiNo
				si bola == 2 Entonces
					descuento = total * .25
				SiNo
					descuento = 0
				FinSi
			FinSi
			Escribir "El total a pagar es: $",total - descuento
			Escribir "El descuento aplicado es: $",descuento	
			clientes = clientes - 1
		SiNo
			Escribir "Ingresa un numero correcto"
		FinSi	
		Escribir ""
	FinMientras	
FinAlgoritmo
<!---
coldplay20/coldplay20 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
