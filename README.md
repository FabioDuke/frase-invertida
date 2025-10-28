# frase-invertida
def inverter_palavras(frase):
    return ' '.join([palavra[::-1] for palavra in frase.split()])

frase = input("Digite a frase: ")
resultado = inverter_palavras(frase)
print("Frase depois de ser invertida:", resultado)
