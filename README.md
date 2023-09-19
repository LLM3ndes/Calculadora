# Calculadora

# Função para adição
def add(x, y):
    return x + y

# Função para subtração
def subtract(x, y):
    return x - y

# Função para multiplicação
def multiply(x, y):
    return x * y

# Função para divisão
def divide(x, y):
    if y == 0:
        return "Erro! Divisão por zero."
    return x / y

# Exibição do menu
print("Selecione a operação:")
print("1. Adição")
print("2. Subtração")
print("3. Multiplicação")
print("4. Divisão")

# Solicita ao usuário a escolha da operação
escolha = input("Digite a opção (1/2/3/4): ")

# Solicita ao usuário os números de entrada
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

# Realiza a operação com base na escolha do usuário
if escolha == '1':
    print("Resultado:", add(num1, num2))
elif escolha == '2':
    print("Resultado:", subtract(num1, num2))
elif escolha == '3':
    print("Resultado:", multiply(num1, num2))
elif escolha == '4':
    print("Resultado:", divide(num1, num2))
else:
    print("Opção inválida")


import math  # Importa o módulo math para usar a função sqrt (raiz quadrada)

# Função para calcular a raiz quadrada
def square_root(x):
    if x < 0:
        return "Erro! Não é possível calcular a raiz quadrada de um número negativo."
    return math.sqrt(x)

# ... (Código anterior da calculadora)

# Exibição do menu
print("Selecione a operação:")
print("1. Adição")
print("2. Subtração")
print("3. Multiplicação")
print("4. Divisão")
print("5. Raiz Quadrada")  # Adiciona a opção para calcular raiz quadrada

# Solicita ao usuário a escolha da operação
escolha = input("Digite a opção (1/2/3/4/5): ")

# ... (Código anterior da calculadora)

# Adiciona um bloco para a opção 5 - Raiz Quadrada
elif escolha == '5':
    print("Resultado:", square_root(num1))
import math  # Importa o módulo math para usar a função sqrt (raiz quadrada)

# Função para calcular a raiz quadrada
def square_root(x):
    if x < 0:
        return "Erro! Não é possível calcular a raiz quadrada de um número negativo."
    return math.sqrt(x)

# Função para calcular a potência de um número
def power(x, y):
    return x ** y

# ... (Código anterior da calculadora)

# Exibição do menu
print("Selecione a operação:")
print("1. Adição")
print("2. Subtração")
print("3. Multiplicação")
print("4. Divisão")
print("5. Raiz Quadrada")
print("6. Potência")  # Adiciona a opção para calcular potências

# Solicita ao usuário a escolha da operação
escolha = input("Digite a opção (1/2/3/4/5/6): ")

# ... (Código anterior da calculadora)

# Adiciona um bloco para a opção 6 - Potência
elif escolha == '6':
    num3 = float(input("Digite o expoente: "))
    print("Resultado:", power(num1, num3))
