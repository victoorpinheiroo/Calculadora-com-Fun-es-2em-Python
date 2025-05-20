# Essa é uma calculadora com operações de soma, subtração, multiplicação e raiz quadrada
def soma(numeroA , numeroB):
    resultado = numeroA + numeroB
    print(f"O resultado da soma é: {resultado}")
    
def subtracao(numeroA , numeroB):
    resultado = numeroA - numeroB
    print(f"O resultado da soma é: {resultado}")

def multiplicacao (numeroA , numeroB):
    resultado = numeroA * numeroB
    print(f"O resultado da soma é: {resultado}")
    
def raizQuadrada (numeroA):
    resultado = numeroA ** 0.5
    print(f"O resultado da raiz quadrada é: {resultado}")

opcao = int(input("MENU: \n 1. SOMA\n 2. SUBTRAÇÂO \n 3. MULTIPLICAÇÂO \n 4. RAIZ QUADRADA \n"))

if (opcao == 1):
    numeroA = float(input("digite o primeiro numero: "))
    numeroB = float(input("Digite o segundo número: "))
    soma(numeroA, numeroB)
    
elif (opcao == 2):
    numeroA = float(input("digite o primeiro numero: "))
    numeroB = float(input("Digite o segundo número: "))
    subtracao(numeroA, numeroB)
    
elif (opcao == 3):
    numeroA = float(input("digite o primeiro numero: "))
    numeroB = float(input("Digite o segundo número: "))
    multiplicacao(numeroA, numeroB)
 
    
elif (opcao == 4):
    numeroA = float(input("Digite o numero: "))
    raizQuadrada(numeroA)
    
else:
    print("Você não selecionou nenhuma das opções")
