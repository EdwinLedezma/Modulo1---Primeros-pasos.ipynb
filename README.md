# Modulo1---Primeros-pasos.ipynb
Python
Python 3.10.2 (tags/v3.10.2:a58ebcc, Jan 17 2022, 14:12:15) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> # program.py
>>> sum = 1 + 2
>>> print(sum)
3
>>> python3 program.py
  File "<stdin>", line 1
    python3 program.py
            ^^^^^^^
SyntaxError: invalid syntax
>>> print (Hola desde la consola)
  File "<stdin>", line 1
    print (Hola desde la consola)
           ^^^^^^^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> print ("Hola desde la consola")
Hola desde la consola
>>> sum = 1+2 #3
>>> product = sum * 2
>>> print(product)
6
>>> planetas_en_el_sistema_solar = 8 # int, pluton era considerado un planeta pero ya es muy pequeño distancia_a_alfa_centauri = 4.367 # float, años luz
>>> puede_despegar = True
>>> transbordador_que_aterrizo_en_la_luna = "Apollo 11" #string
>>> type(distancia_a_alfa_centauri
...
... distancia_a_alfa_centauri =4.367
  File "<stdin>", line 1
    type(distancia_a_alfa_centauri
         ^^^^^^^^^^^^^^^^^^^^^^^^
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> distancia_a_alfa_centauri = 4.367 # Parece un decimal flotante
>>> from datetime import date
>>> date.today
<built-in method today of type object at 0x00007FF82DED0BA0>
>>> print(date.today())
2022-02-22
>>> print("Today's date is: " + str (date.today()))
Today's date is: 2022-02-22
>>> print "Bienvenido al programa de bienvenida"
  File "<stdin>", line 1
    print "Bienvenido al programa de bienvenida"
    ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
SyntaxError: Missing parentheses in call to 'print'. Did you mean print(...)?
>>> print("Bienvenido al programa de bienvenida")
Bienvenido al programa de bienvenida
>>> name = input("Introduzca su nombre")
Introduzca su nombreEdwin
>>> print ("Saludos: " + name)
Saludos: Edwin
>>> print("Calculadora")
Calculadora
>>> first_number = input("Primer numero: ")
Primer numero: 5
>>> second_number = input("Segundo numero: ")
Segundo numero: 5
>>> print(first_number + second_number)
55
>>> print(int(first_number)+int(second_number))
10
>>>
