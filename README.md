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

