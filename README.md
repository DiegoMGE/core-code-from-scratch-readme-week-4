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
