total_geral = 0.0
ativo = True

while ativo:
    print("\n=== SISTEMA DE LOJA ===")
    print("1 - Comprar produto")
    print("2 - Ver total")
    print("3 - Sair")

    opcao = int(input("Escolha uma opção: "))

    if opcao == 1:
        produto = input("Nome do produto: ")
        preco = float(input("Preço: "))
        quantidade = int(input("Quantidade: "))

        if preco < 0 or quantidade < 0:
            print("Valores inválidos!")
        else:
            total = preco * quantidade
            total_geral += total
            print(f"Compra realizada! Total: R${total:.2f}")

    elif opcao == 2:
        print(f"Total geral: R${total_geral:.2f}")

    elif opcao == 3:
        print("Encerrando sistema...")
        ativo = False

    else:
        print("Opção inválida!")
