# calculadora
#Tutorial: How to make a calculator in python.
operacao = ""
calculo = 0
decisao = 1
while decisao !=0:
    print("Soma -> + ")
    print("Subtração -> - ")
    print("Divisão -> / ")
    print("Multiplicação -> * ")
    operacao = input("Escolha uma operação que deseja fazer: ")
    print("Você escolheu -> "+operacao)
    x = int(input("Informe um número:"))
    y = int(input("Informe outro número:"))
    if operacao == "+":
        calculo = x + y
        print("A soma de " + str(x) + " e " + str(y) + " é -> " + str(calculo))
    if operacao == "-":
        calculo = x - y
        print("A subtração de " + str(x) + " e " + str(y) + " é -> " + str(calculo))
    if operacao == "/":
        calculo = x/y
        print("A divisão de " + str(x) + " e " + str(y) + " é -> " + str(calculo))
    if operacao == "*":
        calculo = x*y
        print("A multiplicação de " + str(x) + " e " + str(y) + " é -> " + str(calculo))
    else:
        print("Você digitou algum dado inválido")
    decisao = int(input("Para sair digite 0 para fazer mais uma operação digite 1: "))
