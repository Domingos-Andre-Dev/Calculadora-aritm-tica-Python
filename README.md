# Calculadora-aritmetica-Python
nome = input('digite seu nome : ')

lista = []

for l in range(3):

      lista.append(float(input('digite sua nota : ')))

media = sum(lista) / 3
if media >= 10:
    print(f'{nome} você aprovou com a media {media}')

elif media == 9:
    print(f'{nome} você foi a recurso com a media {media}')

else:
    print(f'{nome} você reprovou com a média {media}')
