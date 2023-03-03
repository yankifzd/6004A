# 6004A
ejhhwssyvwywgywvvyvgyuwevedbwwy
/**
 * You can edit, run, and share this code.
 * play.kotlinlang.org
 */
fun main() {
    println("Hello, world!!!")
}

//variaveis
//
//var - mutavel - seu valor pode ser alterado
//val - nao mutavel - nao e possivel alterar seu valor
//
//Tipos de variaveis
//
//BooLean - verdadeiro ou falso
//Sting - qualquer texte de qualquer tamanho dentro de ""  --> ex: "pizza"	
//Char - Apenas um caractere dentro de ''  --> ex: 'a'
//Int - Numeros inteiros
//Double - numeros decimais (de forma longa arredondada)  --> 71.23
//long - numeros reais (de forma longa) --> Ex:5000000000000000
//Float - numeros decimais (de forma definitiva) --> ex:71.31231371831
//
//Estrutura de uma variavel
//
//var nomeDela = "valor"
//var nimeDela s
//
//Concatenaçao
var messiGoldenBall = 7  


println()
-------------------------------------------------------------------
fun main() {
    println("Hello, world!!!")
// Operadores Relaconais
// 
//  sao sinais que auxiliam em comparaçoes entre valores
//  
// = -> para definir valores
// == -> comparaçao de igualdade
// != -> diferença
// > -> maior que...
// < -> menor que...
// 
// Operadores matematicos
// + ->adiçao
// - -> subtraçao
// * -> multiplicaçao
// / -> divisao
// % -> modulo - resto de uma divisao
// ++ -> adiciona 1 a um valor
// -- -> subtrai 1 de um valor
// 
// Condiçoes 
// if..else -> se..senao
// 
// Estrutura do if..else simples
// 
// if (codiçao){
// açao a ser executada
// }
//
/*
var classificado = "Real Madrid"

if (classificado == "Real Madrid"){
    println("Real Madrid classificado para a final hala Madrid!!")
}else{
    println("barcelona classificado para a final infelizmente")
}
*/
// if..else composto
// 
// estrutura:
// if (condiçao){
// açao
// }else if(condiçao){
// açao
// }else{
// açao
// }


var vidas = 1
    
if(vidas >= 5){
    println("voce esta excelete!! que vida boa")
}else if(vidas == 4){
     println("voce ta muito bem!! pode comer miojo :)")
}else if(vidas == 3){
      println("voce ta ok mais pode melhorar")
}else if(vidas == 2){
    println("ta tudo bem ai??")
}else if(vidas == 1){
    println("se ta morrendo!! se cuida cara")
}else{
    println("voce nn existe")
}    
}


//exercicico 1 - faça um programa que verifique dois numeros e indique
//no console o maior entre eles

//exercicio 2 - faça um programa que indique no console se um numero
//verificado e positivo ou negativo
//
//.Nos exercicios devem ser utilizadas pelo menos 1 variavel
//.Os exercicios devem ser feitos com if..else
//.Divirtam-se 
//
// exercicio 1:

var sorvete = 3
var chocolate = 7

if(sorvete > chocolate){
    println("o numero $sorvete e maior que $chocolate")
}else{
    println("o numero $chocolate e maior que $sorvete")
}
}
