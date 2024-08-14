# Simple-Calculator-using-Python

## hELLO gUYS

<img src="https://i.pinimg.com/736x/ff/8a/50/ff8a500045d4aa2774c1e03a86a1be2c.jpg" width="500" align="left">


<p>Today I was doing some exercises of while loops on Python, and decided to begin my first ever project....... A CALCULATOOOOOR.
Yeah I know... simple and easy, but since I'm a begginner I decided to do it, not using a single tutorial, only my knowleage of if statements and while loops (I didn't even add the while loops yet hahah). It's still pretty simple but I'm gonna start adding more operations (multiplication, division and maybe even some fancy things).</p>

<p>Here's the code for it:</p>

```
operacao = input('Escolha entre (+) para SOMA e (-) para SUBTRAÇÃO: ')

if operacao == '':
  print('Você não digitou nada')
    
elif operacao == '-':
  print('Você escolheu SUBTRAÇÃO')


elif operacao == '+':
  print('Você escolheu SOMA')

else:
  print('Escolha um dos sinais (-) ou (+)')

if operacao == '-' or operacao == '+':
  numero_1 = input('Digite um número: ')
  numero_2 = input('Digite outro número: ')

  numero_1 = int(numero_1)
  numero_2 = int(numero_2)

  soma = numero_1 + numero_2
  subtracao = numero_1 - numero_2

  if operacao == '+':
    print(f'{numero_1} + {numero_2} = {soma}')

  elif operacao == '-':
    print(f'{numero_1} - {numero_2} = {subtracao}')

```

# Here's the new and better version of my calculator!!!

<p>Here's the code for it:</p>

```
''' Calculadora com Python '''

while True:

  numero_1 = input('Digite um número: ')
  numero_2 = input('Digite outro número: ')
  operador = input('Escolha um operador [+], [-], [/] ou [*]: ')

  num_1_float = float(numero_1)
  num_2_float = float(numero_2)

  if operador == '+':
    soma = num_1_float + num_2_float
    print(f'{numero_1} + {numero_2} = {soma:.0f}')

  if operador == '-':
    subtracao = num_1_float - num_2_float
    print(f'{numero_1} - {numero_2} = {subtracao:.0f}')

  if operador == '/':
    divisao = num_1_float / num_2_float
    print(f'{numero_1} / {numero_2} = {divisao:.0f}')

  if operador == '*':
    multiplicacao = num_1_float * num_2_float
    print(f'{numero_1} * {numero_2} = {multiplicacao:.0f}')

  sair = input('Você deseja [s]air?: ').lower().startswith('s')

  if sair:
    print('Você saiu')
    break

```

<img>![Screenshot 2024-08-14 193421](https://github.com/user-attachments/assets/8eb98680-753e-44d0-9bec-a67e9a0a93c6)


