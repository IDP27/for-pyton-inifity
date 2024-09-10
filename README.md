# for-pyton-inifity
prova de for/modulo logica da programacao
ini = int(input('Digite um numero inteiro: '))
fim = int(input('Digite outro numero inteiro: '))
soma_pares = 0
for numero in range(ini, fim + 1):
    if numero % 2 == 0:
        soma_pares += numero
if soma_pares == 0:
    print('Não há números pares no intervalo.')
else:
    print(f"A soma dos números pares no intervalo é: {soma_pares}")     
