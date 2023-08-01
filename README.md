# 11-projetos-em-Python
Pequenos programas em Pyhton

# 11 Projetos em Python para Praticar

## 1. Contador de Palavras

print("Diga em uma frase algo em que voce pensou hoje!")

frase = (input("Escreva aqui: "))
contador = len(frase.split())

print("Legal! Voce acabou de me dizer no que pensou usando " + str(contador) + " palavras.")

## 2. Jogo Mad Libs

cor = input("Qual sua cor favorita: ")
nome_plural = input("Escreva um nome plural: ")
celebridade = input("Escreva o nome de uma celebridade: ")

print(("Rosas são " + cor))
print(nome_plural + " são azuis")
print("Eu amo " + celebridade)

## 3.Par ou Impar

print("Olá, bem vindo!")

while True:
    numero = int(input("Por favor, insira um número de 1 a 1000: "))
    
    if numero == 10:
        break
    if numero % 2 == 0:
        print("o número é par!")
        print("Se deseja encerrar a aplicação escreva o número 10!")
        print("Obrigado")
    else:
        print("o número é ímpar!")
        print("Se deseja encerrar a aplicação escreva o número 10!")
        print("Obrigado!")

