# Script-Python
estudo e scripts envolvendo python

    while True:  
    try:
        idade = int(input("Digite sua idade: "))
        
        # aqui entra o IF/ELSE
        if idade > 0 and idade <= 150:
            break   # idade válida → sai do laço
        else:
            print("Idade inválida, tente de novo.")

    except ValueError:
        print("Você precisa digitar um número inteiro.")

    print("Sua idade é :",idade)

