# programa-que-faz-sorteio
Um programa em python básico que sorteia os alunos para apagar a lousa foi usado a biblioteca random.

import random
a1 = str(input('primeiro aluno: '))
a2 = str(input('segundo aluno: '))
a3 = str(input('terceiro aluno: '))
a4 = str(input('quarto aluno: '))
lista = [a1, a2, a3, a4]
escolido = random.choice(lista)
print('O aluno escolido foi {}'.format(escolido))


esse programa alem de sortear ele tambem mostra a sequencia do sorteado

a1 = str(input('primeiro lugar:'))
a2 = str(input('segundo lugar:'))
a3 = str(input("terceiro lugar:"))
a4 = str(input('quarto lugar:'))
lista = [a1, a2, a3, a4]
random.shuffle(lista)
print('A ordem de apresentação será')
print(lista)
