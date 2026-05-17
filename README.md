import random
import string

numero = int(input('Quantidade de caracteres (8 a 12): '))

if numero < 8 or numero > 12:
    print('Valor inválido.')

else:
    caracteres = string.ascii_letters + string.digits

    senha = ''

    for i in range(numero):
        senha += random.choice(caracteres)

    print(f'Senha gerada: {senha}')

Senha gerada: A8k2Lm91Qa
