<h1 align="center"> Explorer Lab #01 </h1>

<p align="center">
Evento exclusivo e gratuito, promovido pela Rocketseat para ensino de tecnologias WEB.
</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br>

<p align="center">
  <img alt="rocketpay" src=".github/project.png" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- HTML e CSS
- JavaScript e JSON
- [Node e NPM](https://nodejs.org/)
- [Vite](https://vitejs.dev/)
- [iMask](https://imask.js.org)

## 💻 Projeto

O Rocketpay é um componente que simula o formulário de preenchimento de cartão de crédito, onde é possível adicionar máscara aos inputs e atualizar elementos HTML via DOM.

## 🔖 Layout

Você pode visualizar o layout do projeto através [DESSE LINK](https://www.figma.com/file/gpqavL469k0pPUGOmAQEM9/Explorer-Lab-%2301/duplicate). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.

## :memo: Licença

Esse projeto está sob a licença MIT.

---

Feito com ♥ by Rocketseat :wave: [Participe da nossa comunidade!](https://discord.gg/rocketseat)

# Expressão Regular

---

# Expressões Regulares

Regex com JavaScript

---

## Expressões Regulares

Também conhecida como `Regular Expression` ou `Regex` é uma tecnologia usada para buscar padrões dentro de textos e funciona em diversas linguagens

<aside>
💡 Exemplo: Busque por todos os caracteres numéricos dentro de algum texto

</aside>

---

## Como pensar?

Existe uma maneira correta de pensar ao utilizar essa tecnologia para a busca de padrões.

◦ Leitura da esquerda para a direita

◦ Ler um caractere de cada vez, um após o outro

◦ Conhecer os caracteres reservados da tecnologia

---

## Criando regex no JavaScript

```jsx
const re = /foo/; 

const re = new RegExp(/foo/);
```

---

## Funções usadas em Strings

Existem diversas maneiras de usar expressões regulares em uma string no JavaScript. Abaixo, vamos verificar 3

```jsx
// agrupa os padrões em um array
const matches = 'aBC'.match(/[A-Z]/g);
// Output: Array [B, C]

// pesquisa se existe ou não o padrão
const index = 'aBC'.search(/[A-Z]/);
// Output: 1

// substitui os padrões por novo valor
const next = 'aBC'.replace(/a/, 'A');
// Output: ABC
```

---

## Cheatsheet

**Básico**

◦ **`/ expression / flags`**

Exemplo: **`/[A-Z]+/g`**

◦ `\` usar caracteres especiais

Exemplo: **`/ Oi\?\*\\/`** 

◦ **`()`** agrupador

◦ **`|`** OU lógico

◦ **`Fala Dev`** pesquisa exata

◦ `^Fala` o texto inicia com

◦ **`Dev$`** o texto termina com

**Colchetes**

◦ **`[xyz]`** qualquer um x, y, z

◦ **`[J-Z]`** qualquer caracter entre J e Z.

◦ **`[^xyz]`** nenhum x, y, z

**Classes de caracteres**

◦ **`\w`** palavra **`\d`** dígito **`\s`** espaços em branco (tabs, quebras de linha)

◦ **`\W`** NÃO palavra **`\D`** NÃO dígito **`\S`** NÃO espaços em branco

◦ **`\t`** tabs, **`\n`** quebra de linha

◦ **`.`** qualquer caracter (exceto nova linha)

◦ **`mayk|diego`** mayk ou diego

◦ **`?`** zero ou uma ocorrência

◦ **`*`** zero ou múltiplas ocorrências

◦ **`+`** uma ou múltiplas ocorrências

◦ **`{n}`** n ocorrências

◦ **`{min,max}`** mínima/máxima ocorrências

---

## Testando Expressões

Podemos testar de diversas formas, desde diretamente no seu código, ou: 

- Direto no Editor (VSCode)
    
    Search and Replace
    
- Online
    
    [RegExr: Learn, Build, & Test RegEx](https://regexr.com/)
    

---

## Referências

‣ [https://www.youtube.com/watch?v=sa-TUpSx1JA](https://www.youtube.com/watch?v=sa-TUpSx1JA)

‣ [https://fireship.io/lessons/regex-cheat-sheet-js/](https://fireship.io/lessons/regex-cheat-sheet-js/)

‣ [https://www.debuggex.com/cheatsheet/regex/javascript](https://www.debuggex.com/cheatsheet/regex/javascript)
