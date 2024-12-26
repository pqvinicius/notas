## verificar media e total de notas ##

num_notas = int(input("Digite o total de notas (quantas notas serão contabilizadas):"))
cont = 1 
notas = []
while cont <= num_notas:
    nota_atual = float(input("Digite a nota:"))
    cont+=1
    notas.append(nota_atual)
notas
media = sum(notas) / len (notas)

print(f"As notas foram:{notas}")
print(f"A média das notas foi de {media}")

if media > 5:
    print("O aluno foi aprovado!")
else:
    print("Aluno de recuperação")
    # TODO: write code...

while True:
    resposta = input("Deseja adicionar novas notas? (sim/não): ").strip().lower()
    if resposta == "sim":
        nova_nota = float(input("Digite a nova nota: "))
        notas.append(nova_nota)
        media = sum(notas) / len (notas)
        print(f"As notas foram:{notas}")
        print(f"A média das notas foi de {media}")
    elif resposta == "não":
        print("Processo encerrado.")
        break
    else:
        print("Resposta inválida! Por favor, digite 'sim' ou 'não'.")
