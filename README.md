# AULA6_PARA_NOME_SOBRENOME
## Sobre estruturas de repetição 

algoritmo "PARA_NOME_E_SOBRENOME"
//Faculdade de Tecnologia de Jahu(FATEC) - GTI - Noturno
//Trabalho "Salva-vidas" - Prof° Tiago Antônio da Silva
//Nicolas Gabriel Garcez Fernandes Pinto
//~31/03/2025

var

   i: inteiro
   nome, sobrenome_um, sobrenome_dois, sobrenome_tres: caractere

inicio

   repita

      para i de 1 ate 3 faça

         escreval("Digite seu primeiro nome: ")
         leia(nome)
         escreval(" ")
         escreval("Digite seu primeiro sobrenome: ")
         leia(sobrenome_um)
         escreval(" ")
         escreval("Digite seu segundo sobrenome: ")
         leia(sobrenome_dois)
         escreval(" ")
         escreval("Digite seu terceiro sobrenome: ")
         leia(sobrenome_tres)

         se (nome = "nicolas") e (sobrenome_um = "gabriel") e (sobrenome_dois = "garcez") e (sobrenome_tres = "fernandes") entao
            limpatela()
            escreval(" ")
            escreval("Acesso liberadíssimo ;)")
            interrompa

         senao
            limpatela()
            escreval(" ")
            escreval("Não é o Nicolas :(")
            escreval(" ")
            escreval("Tentativas", i, " de 3")

            se (i = 3) entao
               escreval ("Acesso barrado :/")
               interrompa

            fimse
         fimse
      fimpara
   ate (nome = "nicolas") e (sobrenome_um = "gabriel") e (sobrenome_dois = "garcez") e (sobrenome_tres = "fernandes")

fimalgoritmo

