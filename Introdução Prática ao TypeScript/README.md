<h1 align="center">Desafio de Projeto</h1>
<h2 align="center">Introdução Prática ao TypeScript - Santander Fullstack Develpoer</h2>

</br>

<p align="center">
 • <a href="#Objetivo">Objetivo</a>
 • <a href="#Preparação">Preparação</a> 
 • <a href="#Tecnologias">Tecnologias</a>
 • <a href="#Exercício-1">Exercício 1</a>
 • <a href="#Exercício-2">Exercício 2</a>
 • <a href="#Exercício-3">Exercício 3</a>
</p>

## Objetivo 
Colocar em pratica conseitos aprendido sobre TypeScrip resolvendo problemas lógicos.

</br>

## Preparação

Será necessário ter instalado uma IDE, como por exemplo o [Visual Studio Code](https://code.visualstudio.com/).

</br>

## Tecnologias

Foram utilizadas as seguintes tecnologias:

- <b>TypeScript</b>


</br>

---

</br>

## **Exercício 1**

Como podemos rodar isso em um arquivo .ts sem causar erros? 

</br>

~~~typescript
let employee = {};
employee.code = 10;
employee.name = "John";
~~~

---

</br>

## **Exercício 2**

Como podemos melhorar o esse código usando TS?

</br>

~~~typescript
let pessoa1 = {};
pessoa1.nome = "maria";
pessoa1.idade = 29;
pessoa1.profissao = "atriz"

let pessoa2 = {}
pessoa2.nome = "roberto";
pessoa2.idade = 19;
pessoa2.profissao = "Padeiro";

let pessoa3 = {
    nome: "laura",
    idade: "32",
    profissao: "Atriz"
};

let pessoa4 = {
    nome = "carlos",
    idade = 19,
    profissao = "padeiro"
}
~~~

---

</br>

## **Exercício 3**

O código abaixo tem alguns erros e não funciona como deveria. Você pode identificar quais são e corrigi-los em um arquivo TS?

</br>

~~~typescript
let botaoAtualizar = document.getElementById('atualizar-saldo');
let botaoLimpar = document.getElementById('limpar-saldo');
let soma = document.getElementById('soma');
let campoSaldo = document.getElementById('campo-saldo');

campoSaldo.innerHTML = 0

function somarAoSaldo(soma) {
    campoSaldo.innerHTML += soma;
}

function limparSaldo() {
    campoSaldo.innerHTML = '';
}

botaoAtualizar.addEventListener('click', function () {
    somarAoSaldo(soma.value);
});

botaoLimpar.addEventListener('click', function () {
    limparSaldo();
});

/**
    <h4>Valor a ser adicionado: <input id="soma"> </h4>
    <button id="atualizar-saldo">Atualizar saldo</button>
    <button id="limpar-saldo">Limpar seu saldo</button>
    <h1>"Seu saldo é: " <span id="campo-saldo"></span></h1>
 */
~~~

