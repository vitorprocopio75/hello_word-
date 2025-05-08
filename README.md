# hello_word-  ...
#1-usuario irá inserir dois valores
#variavel é um espaço reservado na memória que recebe dados
#tipos variaveis ( texto, booleano, número(inteiro e float(flutuante-peso, altura, medida)))

numero1 = int(input('Insira o primeiro número:'))
#print(numero1)

numero2 = float(input('Insira o segundo número que seja flutuante :'))
#print(numero2)



#calculo da soma 
soma = numero1 + numero2
print(" o valor de soma os numeros  declarado é:",soma)

#calculo subritação 
subritração = numero1 - numero2
print("A subritração dos  numeros é :", subritração )

#calculo da multipilcação 
multipilcação = numero1 * numero2
print("A multipilcação dos numeros é:", multipilcação)


#calculo da potencia 
potencia = numero1 -+ numero2 
print("a pontencia do numero1 elevado ao numero2 é:")


#exemplo de boleano 
idade = int(input("Digite a sua idade :"))
if idade >= 18:
    print(True)
else:
    print(False)
