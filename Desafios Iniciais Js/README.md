<h1 align="center">Desafio de Código</h1>
<h2 align="center">Desafios Iniciais Js - Santander Fullstack Develpoer</h2>

</br>

<p align="center">
 • <a href="#Objetivo">Objetivo</a>
 • <a href="#Preparação">Preparação</a> 
 • <a href="#Tecnologias">Tecnologias</a>
 • <a href="#Quadrado-de-pares">Quadrado de pares</a>
 • <a href="#Resto-2">Resto 2</a>
 • <a href="#Tomadas">Tomadas</a>
</p>

## Objetivo 
Colocar em pratica conseitos aprendido sobre JavaScrip resolvendo problemas lógicos.

</br>

## Preparação

Será necessário ter instalado uma IDE, como por exemplo o [Visual Studio Code](https://code.visualstudio.com/).

</br>

## Tecnologias

Foram utilizadas as seguintes tecnologias:

- <b>JavaScript</b>

</br>

---

</br>

## **Quadrado de pares**

Leia um valor inteiro N. Apresente o quadrado de cada um dos valores pares, de 1 até N, inclusive N, se for o caso.

### **Entrada**

A entrada contém um valor inteiro N (5 < N < 2000).

### **Saída**

Imprima o quadrado de cada um dos valores pares, de 1 até N, conforme o exemplo abaixo.

Tome cuidado! Algumas linguagens tem por padrão apresentarem como saída 1e+006 ao invés de 1000000 o que ocasionará resposta errada. Neste caso, configure a precisão adequadamente para que isso não ocorra.

</br>

|Exemplo de Entrada | Exemplo de Saída |
|-------------------|----------------- |
| 6                 | 2^2 = 4          |
|                   | 4^2 = 16         | 
|                   | 6^2 = 36         | 

</br>

---

</br>

## **Resto 2**

 Leia um valor inteiro N. Apresente todos os números entre 1 e 10000 que divididos por N dão resto igual a 2.

### **Entrada**

A entrada contém um valor inteiro N (N < 10000).

### **Saída**

Imprima todos valores que quando divididos por N dão resto = 2, um por linha.

</br>
 
|Exemplo de Entrada | Exemplo de Saída |
|-------------------|----------------- |
| 13                | 2                |
|                   | 15               | 
|                   | 28               | 
|                   | 41               | 
|                   | ...              | 

</br>

---

</br>

## **Tomadas**

Finalmente, o time da Universidade conseguiu a classificação para a Final Nacional da Maratona de Programação da SBC. Os três membros do time e o técnico estão ansiosos para bem representar a Universidade, e além de treinar muito, preparam com todos os detalhes a sua viagem a São Paulo, onde será realizada a Final Nacional.

Eles planejam levar na viagem todos os seus vários equipamentos eletrônicos: celular, tablet, notebook, ponto de acesso wifi, câmeras, etc, e sabem que necessitarão de várias tomadas de energia para conectar todos esses equipamentos. Eles foram informados de que ficarão os quatro no mesmo quarto de hotel, mas já foram alertados de que em cada quarto há apenas uma tomada de energia disponível.

Precavidos, os três membros do time e o técnico compraram cada um uma régua de tomadas, permitindo assim ligar vários aparelhos na única tomada do quarto de hotel; eles também podem ligar uma régua em outra para aumentar ainda mais o número de tomadas disponíveis. No entanto, como as réguas têm muitas tomadas, eles pediram para você escrever um programa que, dado o número de tomadas em cada régua, determine o número máximo de aparelhos que podem ser conectados à energia num mesmo instante.

### **Entrada**

A entrada consiste de uma linha com quatro números inteiros T1, T2, T3, T4, indicando o número de tomadas de cada uma das quatro réguas (2 ≤ Ti ≤ 6).

### **Saída**

Seu programa deve produzir uma única linha contendo um único número inteiro, indicando o número máximo de aparelhos que podem ser conectados à energia num mesmo instante.



</br>
 
|Exemplo de Entrada | Exemplo de Saída |
|-------------------|----------------- |
| 2 4 3 2           | 8                |
| 6 6 6 6           | 21               | 
| 2 2 2 2           | 5                | 
