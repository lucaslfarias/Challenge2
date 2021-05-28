# Challenge2

Desafio Portugol - Fork este repo, clone em sua máquina, trabalhe na sua branch e crie um programa em portugol para os exercícios a serguir. Ao finalizar, commit para seu repositório e faça um pull request para o repo original.
Data limite. 28/05 até as 12:00 da manhã.

-Escreva um algoritmo para ler um valor (do teclado) e escrever (na tela) o seu antecessor.
Resposta:
Algoritmo "antecessor"
Var
   N, antecessor:real

Inicio
      escreva("o antecessor de:")
      leia (N)
      antecessor<- N-1
      escreva ("e: ", antecessor)
Fimalgoritmo

-Ler um valor e escrever a mensagem É MAIOR QUE 10! se o valor lido for maior que 10, caso contrário escrever NÃO É MAIOR QUE 10!
R= 
Algoritmo "maior-que"
Var
      valor: interio
Inicio
      Escreval ("Informe um numero: ")
      Leia (valor)
      Se valor > 10 entao
      Escreva ("E maior que 10")
      Senao
      Escreva ("Nao e maior que 10")
      fimse
Fimalgoritmo

- Faça um algoritmo que receba dois números e ao final mostre a soma, subtração, multiplicação e a divisão dos números lidos.

R= 
Algoritmo "calculo"
Var
   N1, N2: Real
Inicio
     Escreval ("informe um numero: ")
      Leia (N1)
      Escreval ("informe outro numero: ")
      Leia (N2)
      Escreval ("o resultado da soma e: ", N1+N2)
      Escreval ("o resultado da subtracao e: ", N1-N2)
      Escreval ("o resultado da divisao e: ", N1/N2)
      Escreval ("o resultado da multiplicacao e: ", N1*N2)
Fimalgoritmo

- Escrever um algoritmo para determinar o consumo médio de um automóvel sendo fornecida a distância total percorrida pelo automóvel e o total de combustível gasto.

R=
Algoritmo "combustivel"

Var
   dist, comb, media : real


Inicio
   escreva ("Digite a distância em Km percorrida pelo automóvel: ")
   leia (dist)
   escreva ("Digite o combustível gasto em litros pelo automovel: ")
   leia (comb)
   media <- comb / dist
   escreva ("O consumo médio do automóvel é: ", media, " litros a cada 1 Km")


Fimalgoritmo

- Escreva um Algoritmo que leia 3 notas de um aluno e no final diga se ele passou por media ( acima de 7). Caso ele tire 0 em uma das provas o programa tem que retornar reprovado.

R=

Algoritmo "notas"
Var
   N1, N2, N3, M: Real
Inicio
   Escreva ("Nota 1: ")
   Leia (N1)
   Escreva ("Nota 2: ")
   Leia (N2)
   Escreva ("Nota 3: ")
   Leia (N3)
   M <- (N1 + N2 + N3) / 2
   EscrevaL ("A media do aluno foi: ", M)
   Se (M >= 7) entao
      EScrevaL ("Aluno APROVADO")
   senao
      Se (M >= 5) e (M <7) entao
         Escreval ("Aluno em RECUPERACAO")
      senao
         Escreval("Aluno REPROVADO")
      FimSe
   FimSe
Fimalgoritmo