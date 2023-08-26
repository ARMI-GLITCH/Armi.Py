# Armi.Py
#Phyton Tutorials...

#Pruebas desordenadas

print('-Hola como estas Armando Pasten Martinez-' * 5 )
my_tupla = (6,7,8,9)
print(type(my_tupla))
print(my_tupla)

my_tupla = tuple(my_tupla)
print(type(my_tupla))

print(not(6 == 6)and(8 > 7)or(6 < 5))
print(6 < 1 or 8 > 9)
print(7 == 7 and 8 == 7)

my_list = ['Hola',89]
print(type(my_list))
print(my_list)

a = 1
b = 3
c = a + b
print(c)

mi_numeros = 34

mi_palabra = 'Favorito es :'

print('Mi numero',mi_palabra ,mi_numeros)

print(len('Hola') > len('Rolas'))
print('Hola' + '-Armi-')
    
def Suma_Numeros(numero_1 , numero_2):
    print(numero_1 * numero_2)
    return numero_1 * numero_2

result = Suma_Numeros(6,6)
Suma_Numeros(9999,7777)
Suma_Numeros(999,1010)

print(result)

def Menos_Numeros(Nameros_1 , Nameros_2):
    print(Nameros_1 / Nameros_2)
    return Nameros_1 / Nameros_2

result = Menos_Numeros(5,5)
Menos_Numeros(7,7)
Menos_Numeros(8,72)

print(result)

print(1 + 2 ** 3 / 4 * 5)
print(1 + 2 ** 3 / 4)
print( 9 / 4 )

x = 2
if x < 2:
    print('small')
elif x > 10:
    print('Medium')
else :
    print('Large')  
    print('ALL DONE')

#Prueba

astr = 'Hello bob'
try:
    istr = int(astr)
except:
    istr = 2

print('Hola')

astr = '123'
try:
    istr = int(astr)
except:
    istr = -1

print('Hola')

algo = 'bob'
try:
    print('hello')
    als = int(algo)
    print('Xd')
except:
    als = -1

print('Algo esta mal')

def fred():
    print('Zap')
def jane():
    print('ABC')

jane()
fred()
jane()

n = 5
if n > 0:
    print(n)
    n = n - 1
    print('Blastoff')
    print(n)

p = 2
while True:
    if p == 5:
        break
    print(p)
    p = p + 1

armi = 0
for thing in [5 , 10 , 15]:
    armi = armi + thing
    print(thing , armi)

found = True
print('Before', found)
for value in [53, 38, 20, 84, 10, 78] :
    if value == 84 :
        found = False
    print(found, value)
print('After', found)
        
str3 = '164'

x = int(str3) + 4
print(x)#Conviertes un string en entero

name = input('Enter: ')
Enter = 'Armando'
print(name)#Esto es como un script de bash 

apple = input('Enter: ')
apple = int(apple)
x = apple - 10
print(x)#Conviertes un string en entero 

fruit = 'banana'
letter = fruit[4]
print(letter)

x = 3
f = fruit[x - 2]
print(f)

fruta = 'banana'
prueba = len(fruit)
print(prueba)

#Cuenta las letras y imprime el numero de letras
frutas = 'banana'
index = 0
while index < len(frutas):
    better = frutas[index]
    print(index ,better)
    index = index + 1

#imprime banana en lineas de arriba hacia abajo
xd = 'banana'
for rotter in xd:
    print(rotter)
    
#Cuenta las letras y indicas hasta donde quieres que llegue
s = 'Armando Pasten'
l = len(s)
o = s[0:7]
print(l)
print(o)

i = 'Hello'
p = i + ' ' + 'There'
print(p)

Platano = 'Banana'
u = 'm' in Platano
print(u)

gray = 'Hello Bob'
rst = gray.replace('Bob', 'Lara')
print(rst)

Dia = 'Que tengas un buen dia'
Noche = Dia.startswith('Que')
print(Noche)

datos = 'ArmandoPastenMartinez@ gmail.com'
info = datos.find(' ')
print(info)

works = 'Banana'
k = works.find('na')
print(k)

#Sintaxis Basica 

print('-Sintaxis Basica-')
print('Hola como estas')
a = 7

b = 7

c = a + b

print(c)

mi_numero = 18

print('Mi numero favorito es :', mi_numero)

mi_palabra = 'Hola como estas'

mi_nombre = 'Armando'

print(f'Esto es una variable {mi_numero} Hola gato')

print(mi_palabra ,mi_nombre)

a , b , c , d = 'Hola'

print(a)
print(b)
print(c)
print(d)

print(mi_palabra.upper())#Tod con mayusculas
print(mi_palabra.capitalize())#Solo mayuscula al principio
print(mi_palabra.lower())#Todo con minusculas
print(len(mi_palabra))#Cuenta las palabras
print(mi_palabra.find('o'))#Busca con cuantas letras se posiciona la letra o
print(mi_palabra.count('o'))#Cuenta cuantas -o- hay valaga la redondancia

print(type('Hola'))#Esto es un String
print(type(1))# Esto es un Entero
print(type(1.5))#Esto es un Flot

#Operadores aritmeticos
print('-Operadores aritmeticos-')
print( 5 + 6 )
print( 6 / 7 )
print( 6 * 9 )

print( 'Hola' * 6)
print( 'Hola' + 'Hola')
print( 'hola' + str(6))

#Operadores comparativos
print('-Operadores comparativos-')
print( 8 > 9 )#¿8 es mayor que 9?
print( 5 < 6 )#¿5 es menor que 6?
print( 8 == 8 )#¿8 es igual a 8?
print( 4 <= 8 )#¿4 es menor o igual a 8?
print( 4 >= 8 )#¿4 es mayor o igual que 8?
print( 4 != 8 )#'¿4 es diferente a 8?

print(len('Hola') > len('Bolas'))#Cuenta si tiene mas caracteres que la otra
print('a' > 'b')#Cuenta desde el abedecedario A , B , C la letra -a- no es mayor que -b-

#Operadores logicos
print('-Operadores logicos-')
print(4 < 6 or 7 > 9)#Si uno es true se volvera true
print(4 < 6 and 7 > 9)#Si uno no es verdadero te dara false
print(not(4 > 6))#Si es verdero lo convierte a falso y viseversa...

#Listas
print('-Listas-')
my_list = ['Phyton',53,False,43,'Hola mundo',53,53]
print(type(my_list))

print(my_list)
#print(my_list[1])

my_list.append('45')#Añade otro elemento
print(my_list)

my_list.insert(3, 'Suscribanse')#El numero indica la posicion donde estara la palabra
print(my_list)

my_list.remove('Hola mundo')#Remueve elementos 
print(my_list)

print(my_list.pop(3))#Remueve desde la posicion y te devuelve el valor que borro
print(my_list)

print(my_list.count(53))#Cuenta los numeros o palabras repetidas
print(my_list)

my_list.reverse()#Pone todo al reves
print(my_list)

my_list.clear()#Borra la lista
print(my_list)

#Tuplas

my_tupla = (53, 'Perro',7.4,True)
print(type(my_tupla))

print(my_tupla[1])
print(my_tupla.count(53))
print(my_tupla.index(True))#Busca elementos desde su posicion

my_tupla = list(my_tupla)#Convierte la Tupla en Lista
print(type(my_tupla))

print(my_tupla.count(53))
print(my_tupla)

#Sets
print('-Sets-')

my_set = {}#Esto es un dict
print(type(my_set))

my_set = {'Phyton','Javascript','C++'}#Esto es un Set
print(type(my_set))

print(my_set)

my_set.add('C++')#No lo agrega porque ya lo tiene
print(my_set)

my_set.add('C#')
print(my_set)

my_set0 = {'Phyton', 'Javascript', 'C++'}

my_set.difference_update(my_set0)#Mustra la diferencia entre sets
print(my_set)

#Diccionarios

my_dict = {'Nombre':'Armando','Apodo':'Armi','Apellido':'Pasten Martinez'}
print(type((my_dict)))
print(my_dict)

print(my_dict['Nombre'])

print(my_dict.keys())#Te muestra las llaves
print(my_dict.values())#Te muestra el valor de las llaves

my_dict = list(my_dict)
print(my_dict)

my_dict = tuple(my_dict)
print(my_dict)

my_dict = set(my_dict)
print(my_dict)

#Condicionales
print('-Condicionales-')

#Este es un tipo de sintaxis

numero = 7

Albion = 'Es un juego complejo...rlinblneilrnbllnfd'

if 3 < 4:
    print('3 es menor que 4')
else:
    print('3 no es mayor que 4')

if len(Albion) > 100:
    print('Es demasiado TEXTO..')
else:
    print('No pues no es tanto..')

#Este es otro tipo de sintaxis
 
if 7 > 6:
    print('7 es mayor que 6')
elif 6 == 6:
    print('6 es igual a 6')
else:
    print('No se cumple estas 2 condiciones') 

#Bucles
print('-Bucles-')
numero = 0
while numero < 200:
    numero += 10
    print(numero)
    if numero < 200:
        print('Es menor que 200')
    if numero == 200:
        print('Llegaste al final rey')
        break

lista = [8,9,10,11,12,13]
for number in lista:
    print(number)

for numeros in range(100):
    print(numeros)
    if numeros == 50:
        print('Hola esto es una prueba de que aprendi')
        
#Funciones
print('-Funciones-')

def Sum_numbers(numero_1, numero_2 = 10):
    print(numero_1 + numero_2)
    return numero_1 + numero_2
    
result = Sum_numbers(45,53)
Sum_numbers(40,11)
Sum_numbers(90,90)

print(result)

#Clases
print('-Clases-')
class unHumanoRaro:
    def __init__(self, Altura, Edad, Peso):
        self.Altura = Altura
        self.Edad = Edad
        self.Peso = Peso

Humano_1 = unHumanoRaro(1.80, 23, 87)

print(f'El humano mide =',Humano_1.Altura)
print(f'El humano tiene =',Humano_1.Edad)
print(f'El humano pesa =',Humano_1.Peso)

#Excepciones
print('-Excepciones-')

try:
    print(5 + '8')
except:
    print('Error')

try:
    print(55 + 78)
except:
    print('Error')
else:
    print('Hola mundo')
finally:
    print('Suscribete')

try:
    print(5 + 9)
except NameError as error:
    print('Error NameError , Haga algo')
    print(error)
except TypeError as error2:
    print('Error TypeError , Haga algo')
    print(error2)

#Modulos
print('-Modulos')

from Funciones import Suma_Numeros, Menos_Numeros

Suma_Numeros(9,9)
Menos_Numeros(9,81)





