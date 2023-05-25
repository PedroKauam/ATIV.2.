# ATIV.2.
Atividade de lógica de programação
Algoritmo "venda de carrus :)"
//  
//  
// Descrição   : Aqui você descreve o que o programa faz! (função)
// Autor(a)    : Nome do(a) aluno(a)
// Data atual  : 4/5/2023
Var
Informadologin, login,caract: caracter
Senha, informadosenha,Op: inteiro
//declaraçao de variaveis para cadastro de veiculos
OBJETO1,OBJETO2,OBJETO3,OBJETO4,OBJETO5,OBJETO6,OBJETO7,OBJETO8,OBJETO9,OBJETO10:caracter
//final de declaracoes
//var globais
acesso,acesso2: inteiro
//fim var
//VAR p cadastro pelo operador
veiculo,venda,ano:inteiro
valor: real
// fim var
Inicio
Login <- "LCC"
Senha<- 2535
Repita
Escreval("Login")
Leia(informadologin)
Escreval("Senha")
Leia(informadosenha)
Se (informadologin="LCC") e (senha=2535) entao
Fimse
Ate (informadologin="LCC") e (informadosenha=senha)
//FIM DO LOGIN
//INICIO COMPRAS E VENDAS DE CARROS
 Escreval("Seja bem vindo")
OBJETO3 <-("1 HILUX ANO 2022,CABINE DUPLA, COR: PRETA, VALOR R$230.000,00")
OBJETO4 <-("2 HILUX ANO 2023,CABINE ESTENDIDA, COR: PRETA, VALOR R$330.000,00")
OBJETO5 <-("3 HILUX ANO 2023,CABINE DUPLA, COR: PRETA, VALOR R$340.000,00")
OBJETO6 <-("5 HILUX ANO 2022,CABINE DUPLA, COR: VERMELHA, VALOR R$300.000,00")
OBJETO7 <-("6 COROLLA ANO 2022,BLINDADO, COR: VERMELHA, VALOR R$120.000,00")
OBJETO8 <-("7 COROLLA ANO 2023,HIBRIDO, COR: VERMELHA, VALOR R$300.000,00")
OBJETO9 <-("8 COROLLA ANO 2018,SERIE ADVENTURE, COR: VERMELHA, VALOR R$80.000,00")
OBJETO10 <-("9 COROLLA,ANO 2020, COR: VERMELHA, VALOR R$100.000,00")
// FIM DE CADASTRO DE VEICULOS
//inicio op do sistem
Repita
Escreval("digite 1 para ver veiculos")
Escreval("digite 2 para cadastrar veiculos")
Escreval("digite 3 para vender veiculos")
Escreval("digite 00 para sair")
Leia (acesso)
    SE ACESSO = 1 ENTAO
escreval(Objeto3)
Escreval("========")
escreval(Objeto4)
escreval("========")
Escreval(Objeto5)
Escreval("========")
escreval(Objeto6)
Escreval("========")
escreval(Objeto7)
escreval("========")
escreval(objeto8)
escreval("========")
escreval(Objeto9)
escreval("========")
escreval(Objeto10)
SENAO
    SE ACESSO = 2 entao
    SENAO
Se acesso = 3  entao
FIMSE
FIMSE
FIMSE
ATE ACESSO = 00
 
fimalgoritmo
