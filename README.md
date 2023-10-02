import math

#Ejercicio 1 

def imprimir_un_verso(): 
 print("asdasfas \n odihasld \njasoijsd\n ajsdoasjid")

def raizDe2(): 
 print(round(2**(0.5), 4)) 

def factorialDeDos(): 
  res = 2 * (2-1)
  print(res)

def perimetro (): 
 print(2 * math.pi)


#Ejercicio 2 

def imprimirSaludo(nombre: str):
 print("Hola " + nombre)

#imprimirSaludo(str("Jose")) 

def raizCuadradaDe(num: int):
 print(num**(0.5))

#raizCuadradaDe(int(round(9,0)))

def fahrenheitACelsius (t: float): 
 print(((t - 32) * 5)/9)

#fahrenheitACelsius(36)

def imprimirDosVeces(estribillo: str): 
 print( estribillo * 2)

#imprimirDosVeces("Holy ")

def esMultiploDe(n:int,m:int)-> bool:
 if math.fmod (n,m) == 0 : 
  return True 
 else: 
  return False

#esMultiploDe(8,2)


def esPar(num:int): 
 if(esMultiploDe(num,2) == True): 
  print(True)
 else:
  print(False)

#sPar(1)

def cantidadDePizzas (comensales:int, minCant: int):
 x = comensales * minCant/8
 print(math.ceil(x))

#cantidadDePizzas(3,6)


#Ejercicio 3 

def algunoEs0 (num1:float, num2:float) -> bool:
 res: bool 
 res = True 
 res = False 
 res = (num1 == 0 or num2== 0)
 return res 

#print(algunoEs0(0,2))


def ambosSon0 (num1:float, num2:float) -> bool:
 res: bool 
 res = True 
 res = False 
 res = (num1 == 0 and num2== 0)
 return res 

#print(ambosSon0(0,2))
#print(ambosSon0(0,0))


def problemeEsNombrelargo(nombre: str)-> bool:
 res: bool 
 res = True 
 res = False 
 res = len(nombre) >= 3 and len(nombre) <= 8
 return res

#print(problemeEsNombrelargo("jo"))

def esBisiesto(año:int)-> bool:
 res: bool 
 res = True 
 res = False 
 res = esMultiploDe(año,400) == True or (esMultiploDe(año,4) == True and esMultiploDe(año, 100) == False)
 return res 

#print(esBisiesto(2020)) 
#print(esBisiesto(2021)) 
#print(esBisiesto(2022)) 
#print(esBisiesto(2023)) 
#print(esBisiesto(2024)) 


#Ejercicio 4 

def pesoPino(cm:int)-> bool: 
 
 if (min(300, cm) == cm):
  return(cm * 3)
 else: 
  return(300 * 3 + ((cm-300) * 2))


#print (pesoPino(800))

def esPesoUtil(kg:int)-> bool:

 if(min(kg,1000) == kg and max(kg,400) == kg):
  return True 
 else: 
  return False

#print(esPesoUtil(1100))

def sirvePino(a:int):
 x = esPesoUtil(pesoPino(a))
 return x 

#print(sirvePino(300))
#print(sirvePino(350))

#Ejercicio 5 

 

