# 1. Básico: imprime todos los números enteros del 0 al 100.
print("Ejercicio 1: Números del 0 al 100")
for i in range(101):
    print(i)

# ------------------------------------------
# 2. Múltiples de 2: imprime todos los números múltiplos de 2 entre 2 y 500.
print("\nEjercicio 2: Múltiplos de 2 entre 2 y 500")
for i in range(2, 501, 2):
    print(i)

# ------------------------------------------
# 3. Contando Vanilla Ice: imprime los números enteros del 1 al 100. Si es divisible por 5 imprime "ice ice" en vez del número. Si es divisible por 10, imprime "baby".
print("\nEjercicio 3: Contando Vanilla Ice")
for i in range(1, 101):
    if i % 10 == 0:
        print("baby")
    elif i % 5 == 0:
        print("ice ice")
    else:
        print(i)

# ------------------------------------------
# 4. Wow. Número gigante a la vista: suma los números pares del 0 al 500000 e imprime la suma total.
print("\nEjercicio 4: Suma de números pares del 0 al 500000")
suma_total = 0
for i in range(0, 500001, 2):
    suma_total += i
print("Suma total:", suma_total)

# ------------------------------------------
# 5. Regrésame al 3: imprime los números positivos comenzando desde 2024, en cuenta regresiva de 3 en 3.
print("\nEjercicio 5: Cuenta regresiva de 3 en 3 desde 2024")
for i in range(2024, 0, -3):
    print(i)

# ------------------------------------------
# 6. Contador dinámico: establece tres variables: numInicial, numFinal y multiplo. Comenzando en numInicial y pasando por numFinal, imprime los números enteros que sean múltiplos de multiplo.
print("\nEjercicio 6: Contador dinámico")
numInicial = 5
numFinal = 50
multiplo = 7
for i in range(numInicial, numFinal + 1):
    if i % multiplo == 0:
        print(i)
