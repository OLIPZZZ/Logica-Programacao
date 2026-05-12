if __name__ == "__main__":
    nome_cliente = input("Digite o nome do cliente: ")
    valor_pedido = float(input("Digite o valor do pedido: "))
    tem_fidelidade = int(input("Possui cartão fidelidade? (1-SIM, 0-NÃO): "))
    if tem_fidelidade == 1:
        valor_pedido = valor_pedido * 0.90
        print("Desconto de 10% aplicado!")
    else:
        print("Sem desconto aplicado.")
    if valor_pedido < 50:
        valor_pedido = valor_pedido + 5
        print("Taxa de entrega de R$ 5,00 adicionada.")
    else:
        print("Frete grátis!")
    print(f"Cliente: {nome_cliente}")
    print(f"Valor final a pagar: R$ {valor_pedido:.2f}")
