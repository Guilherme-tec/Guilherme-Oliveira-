Ampliando o sistema da Papelaria Ponto Certo

def mostrar_menu():
    print("=== MENU ===")
    print("1 - ver mensagem")
    print("0 - Sair")

def mostrar_mensagem():
    print("Bem-vindo!")

mostrar_menu()

opcao = input("Escolha: ")

if opcao == "1":
    mostrar_mensagem()

if opcao == "0":
    print("Programa encerrado!")

if opcao != "1" and opcao != "0":
    print("opcao inválido ")