# De uma linha

""
De várias linhas
""

# Exemplo de input e print
aluna = input("Qual seu nome?")
print("Olá, ", aluna)

nome = input("Digite seu nome: ") 
cidade = input("Digite sua cidade: ")
print(nome + " mora em " + cidade)

altura = float(input("Digite sua altura: "))
print(" Sua altura é " , altura , "m")

# Exemplo de variavel inteira (int)
idade = 25
print(idade) # Saída: 25

# Exemplo de variavel de ponto flutuante (float)
altura = 1.75
print(altura) # Saída: 1.75

# Exemplo de formatação de números (:.nf)
numero = 3.14159
print(f"Com duas casas: {numero:.2f}") # 3.14
print(f"Com três casas: {numero:.3f}") # 3.142
print(f"Sem casas decimais: {numero:.0f}") # 3

# Exemplo de :.2f
numero = flot(input("Digite um número))
print(f"O número digitado foi {numero:.2f})

# Solicita ao usuario um numero decimal
numero = float(input("Digite um numero: "))

# Exibe o numero formatado com duas casas decimais
print(f"O número digitado foi {numero:.2f}")

# Exemplo de variavel string (str)
nome = " João"
print("Olá, " + nome) # Saída: João

# Exemplo com F-String
nome = input("Digite seu nome ")
print(f"Olá, {nome}!")

# Exemplo sem F-String
idade = input("Digite sua idade ") 
print("Você tem " + idade + " anos!")

# Exemplo de listas (list)
numeros = [1, 2, 3, 4, 5]
print(numeros) # Saída: [1, 2, 3, 4, 5]

# Exemplo de tuplas (tuple)
coordenadas = (10, 20)
print(coordenadas) # Saída: (10, 20)

# Exemplo de dicionário (dict)
pessoa = {
    "nome": "Maria",
    "idade": 30,
    "cidade": "São Paulo"
}
print(pessoa) # Saída: {'nome': 'Maria', 'idade': 30, 'cidade': 'São Paulo'}
