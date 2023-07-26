# Exercicio090.py

aluno = dict()
aluno['Nome'] = str(input('nome:'))
aluno['Media'] = float(input(f'A media de {aluno["Nome"]}:'))
if aluno['Media'] >= 7:
    print('Aprovado')
elif 5 <= aluno['Media'] < 7:
    print('Recuperação')
else:
    aluno['Situação'] = 'reprovado'
print('=-'*30)
for k, v in aluno.items():
    print(f'  - {k} é igual a {v}')
