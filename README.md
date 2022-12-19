# Diego Orellana - CoreCode Bootcamp 🚀
## Week 4
## Monday Challenges
- [Average sales and commission](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-4/blob/main/README.md#average-sales-and-commission)
- [Even or odd](https://github.com/DiegoMGE/core-code-from-scratch-readme-week-4/blob/main/README.md#even-or-odd)

### Average sales and commission
```python
Algoritmo averageSalesAndCommission
	Definir valueSales Como Real
	valueSales = 0
	Imprimir 'Write the total number of sales to enter:'
	Leer totalSales
	
	Para sale = 1 Hasta totalSales Con Paso 1 Hacer
		Imprimir 'Write the value of the sale number: ' sale
		Leer valueSale
		valueSales = valueSales + valueSale
	FinPara
	
	average = (valueSales / totalSales)
	Imprimir 'The average sales is: ' average
	
	Si totalSales < 5 Entonces
		Imprimir 'The commission received by the seller is (10%): ' valueSales * 0.10
	SiNo
		Imprimir 'The commission received by the seller is (15%): ' valueSales * 0.15
	FinSi
FinAlgoritmo
```

### Even or odd
```python
Algoritmo evenOrOdd
	maxNumber = 50
	
	Repetir
		Imprimir 'Write a number between 1 and 50'
		Leer number
		Si number > 50 Entonces
			Imprimir 'Invalid number'
		FinSi
	Mientras Que number > maxNumber
	
	par = number % 2 == 0
	impar = number % 2 == 1
	
	Imprimir 'par: ' par
	Imprimir 'impar: ' impar
	
	Para value = 1 Hasta number Con Paso 1 Hacer
		Si (value % 2 == 0) & par Entonces
			Imprimir 'Even: ' value
		FinSi
		Si (value % 2 == 1) & impar Entonces
			Imprimir 'Odd: ' value
		FinSi
	FinPara
	
FinAlgoritmo
```

## Tuesday Challenges
- [Full name]()

### Full name
```python
Algoritmo fullName
	Imprimir 'Your first name'
	Leer firstName
	Imprimir 'Your last name'
	Leer lastName
	
	ccFirstName = Mayusculas(Subcadena(firstName, 0, 0)) + Minusculas(Subcadena(firstName, 1, Longitud(firstName) - 1))
	ccLastName = Mayusculas(Subcadena(lastName, 0, 0)) + Minusculas(Subcadena(lastName, 1, Longitud(lastName) - 1))
	
	Imprimir ccFirstName + ' ' + ccLastName
FinAlgoritmo
```
