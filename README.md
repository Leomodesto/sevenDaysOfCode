<h1>Desafio Seven days of code</h1>

<h2>Dia 1</h2>

A sua tarefa de hoje é reescrever o código abaixo de maneira que ele imprima as informações de maneira correta, que faça sentido e sem erros:

<p>let numeroUm = 1</p>
<p>let stringUm = '1'</p>
<p>let numeroTrinta = 30</p>
<p>let stringTrinta = '30'</p>
<p>let numeroDez = 10</p>
<p>let stringDez = '10'</p>

if (COMPARAR O numeroUm e a stringUm) {
  console.log('As variáveis numeroUm e stringUm tem o mesmo valor, mas tipos diferentes')
} else {
  console.log('As variáveis numeroUm e stringUm não tem o mesmo valor')
}

if (COMPARAR O numeroTrinta e a stringTrinta) {
  console.log('As variáveis numeroTrinta e stringTrinta tem o mesmo valor e mesmo tipo')
} else {
  console.log('As variáveis numeroTrinta e stringTrinta não tem o mesmo tipo')
}

if (COMPARAR O numeroDez e a stringDez) {
  console.log('As variáveis numeroDez e stringDez tem o mesmo valor, mas tipos diferentes')
} else {
  console.log('As variáveis numeroDez e stringDez não tem o mesmo valor')
}


<h3> Resposta: </h3>
```
if (stringUm == numeroUm && typeof stringUm != typeof numeroUm){console.log("As variaveis tem o mesmo valor mas tipos diferentes")}
else{
    console.log("as variaveis nao tem o mesmo valor")
}
```

<h2>Dia 2</h2>

Por isso, hoje, eu vou te ensinar a desenvolver um programa simulando um desses sites. Ele deve pedir para o usuário responder 3 perguntas:

- Qual o seu nome?
- Quantos anos você tem?
- Qual linguagem de programação você está estudando?

À medida que as perguntas forem sendo feitas, a pessoa que estiver usando o programa deve responder cada uma delas.

No final, o sistema vai exibir a mensagem:

"Olá [nome], você tem [idade] anos e já está aprendendo [linguagem]!"

Note que cada informação entre [ ] é uma das respostas dadas pela pessoa.
EXERCÍCIO OPCIONAL
Se você quiser se aprofundar no assunto de hoje, eu tenho mais um exercício para você.

Mas ele é 100% opcional.

Você vai complementar o código para que, depois de exibir a mensagem anterior, o programa pergunte:

Você gosta de estudar [linguagem]? Responda com o número 1 para SIM ou 2 para NÃO.

E aí, dependendo da resposta, ele deve mostrar uma das seguintes mensagens:

1 > Muito bom! Continue estudando e você terá muito sucesso.
2 > Ahh que pena... Já tentou aprender outras linguagens?


<h3> Resposta: </h3>

```
function bemVindo(){
    const nome = prompt("Qual seu nome?")
    const idade = prompt("Qual sua idade?")
    const linguagem = prompt("Qual lingagem de programação você está estudando?")

    alert("Olá " + nome + ", você tem " + idade + " anos e está aprendendo " + linguagem + ".");

    const escolha = prompt("Você gosta de estudar " + linguagem + "? Responda com o numero 1 para sim e 2 para não");

    if(escolha == 1 ){
        alert("Muito bom! Continue estudando e você terá muito sucesso")
    }
    else {
        alert ("Ahh que pena... Já tentou aprender outras linguagens?") 
    }
    
}

BemVindo()
```
