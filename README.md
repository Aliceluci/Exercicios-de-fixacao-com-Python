# Exercicios-de-fixacao-com-Python
Operadores e Variaveis

#001 Qual é o montade que alguém pode economizar sabendo apenas o seu salário e gastos mensais?

salario_mensal = input('Digite o seu salário:')
salario_mensal = float(salario_mensal)

gasto_mensal = input('Digite o valor do seu salário mensal:')
gasto_mensal = float(gasto_mensal)

salario_total = salario_mensal * 12
gasto_total = gasto_mensal * 12
montante_economizado = salario_total - gasto_total

print('O montante que pod ser economizado no fim do anoé de:', montante_economizado)
