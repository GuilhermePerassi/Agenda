# Agenda

# ALGORITMO

var
	DADO : Conjunto[1..10,1..5] de cadeia
	I, J : inteiro
	x : cadeia

inicio 

	(Rotina de entrada)

	para I de 1 até 10 passo 1 faça
		escreva "Nome: " 	leia DADO[I,1]
		escreva "Endereço: " 	leia DADO[I,2]
		escreva "Código Postal: " leia DADO[I,3]
		escreva "Bairro: " 	leia DADO[I,4]
		escreva "Telefone: " 	leia DADO[I,5]
	fim_para

	( Rotina de saida )
	
	para I de 1 até 10 passso 1 faça
		para J de 1 até 5 passo 1 faça 
			escreva DADO[I,1]
		fim_para
	fim_para
  
fim

# FLUXOGRAMA

![Fluxograma Agenda](https://github.com/GuilhermePerassi/Agenda/blob/274d6fe136d989ddf4d7920835e6e4ba4d5378f6/agendap1.png)
![Fluxograma Agenda](https://github.com/GuilhermePerassi/Agenda/blob/bbd93e89129f14bd07d2a06f15185fc2a739daee/agendap2.png)
