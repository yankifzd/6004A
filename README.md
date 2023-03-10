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
-------------------------------------------------------------------------------------

fun main() {
    
}
//exercicio 2 - faça um programa que indique no console se um numero
//verificado e positivo ou negativo
/*
var minecraft = -1 


 if(minecraft > 0){
    println("O $minecraft e um numero positivo")
 }else if(minecraft < 0){
    println("O $minecraft e um numero positivo")
 }else{
   println("O $minecraft nao e nem postivo e nem negativo ")
 }
 */
 
 
//Operades logicos
//
// sao usados para comparar mais de um valor na mesma posiçao
//
// && --> e (shift + 7) -->
// || --> ou (shift + A barrinha invertida ao dele)(PIPELE)
//
// TABELA VERDADE
// e... para que o resultado seja verdadeiro todas as condiçoes =precisam ser verdadeiras
// W
// VF
// FV
// FF 
//
// W - v
// VR - f
// FV - f
// FF - f
// ou... para que o resultado seja verdadeiro pelo menos uma condiçao deve ser veradeira
// W - v
// VF - v
// FV - v
// FF - f
//
//
//
//
//
/*
var coracoes = 0
var vidas = 0
if(vidas <= 00 && coracoes <= 0){
}else{
    println("------ o jogo sera reinicado-------")
*/
// when - quando...
// quando  um determinado valor for verdadeiro uma determinada açao
// sera executada
//
// Estrutura do When
//
// when(var a ser comprado)
// valor -> {açao}
// valor -> {açao}
// valor -> {açao}
// else -> {açao}
// }
/*
var mes = 12
when(mes){
    1 -> {println("janeiro")}
    2 -> {println("fevereiro")}
    3 -> {println("março")}
    4 -> {println("abril")}
    5 -> {println("maio")}
    6 -> {println("junho")}
    7 -> {println("julho")}
    8 -> {println("agosto")}
    9 -> {println("setembro")}
    10 -> {println("outubro")}
    11 -> {println("novembro")}
    12 -> {println("dezembro")}
    else -> {println(mes invalido)}
    */
    // laços de repetiçao
    //
    // do..while - faça... enquanto
    // whiçe - enquanto
    // for - para
    // repeat - re´pita
    //
    //while --> enquanto uma condiçao verdadeira uma determinada açao e executada ate que nao seja mais verdadeira
    //
    var bolo = 500
    

    while(bolo <= 520){
        println(bolo)
        bolo++
    }
    
    
    //do.. while -> ele vai executar uma determinada açao enquato uma condiçao for verdadeira
    println("")
    do{
        println(bolo)
        bolo++
   {while(bolo <= 520)    
