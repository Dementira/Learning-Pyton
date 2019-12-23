# Learning-Pyton
Repository with some of python

#Quiero hacer un programa que le sirva a una persona para ver cuanta plata gasto en su negocio de hamburguesas
#I want to make a program that helps a person to see how much money they spend on their hamburger business

#Entrada de datos
#Data input

print('Por favor, ingrese lo solicitado a continuación...')  #Pls, enter the requested below ...

precioCarne = int(input('Ingrese el precio de la carne picada '))
gramosCarne = int(input('Ingrese la cantidad de gramos que compró '))


precioPan = int(input('Ingrese el precio de pan '))
cantidadPanes = int(input('Ingrese cantidad de panes que compró '))


precioChedar = int(input('Ingrese el precio del chedar '))
fetasChedar = int(input('Ingrese la cantidad de fetas que compró '))


precioCebollas = int(input('Ingrese el precio de las cebollas '))
cantidad = int(input('Ingrese la cantidad de cebollas que compró '))

servilletas = int(input('Ingrese el precio de las servilletas '))

#Calculos
totalGastos = (precioCarne+precioPan+precioChedar+precioCebollas+servilletas)
print('La suma de sus gastos es: ', totalGastos)

cantidadHamburguesas = (gramosCarne/80)
print('La cantidad de hamburguesas que hace con ', gramosCarne, 'es ', cantidadHamburguesas)

precioPorHamburguesa = (totalGastos/cantidadHamburguesas)
print('El precio de cada hamburguesa es: ', precioPorHamburguesa)

gananciasTotales = (cantidadHamburguesas*(precioPorHamburguesa*2))
print('Las ganancias totales son: $', gananciasTotales)

gananciaPrivada = (gananciasTotales-totalGastos)
print('Las ganancias personales son: $', gananciaPrivada)
print('La proxima invercion se basa en: ', totalGastos)
