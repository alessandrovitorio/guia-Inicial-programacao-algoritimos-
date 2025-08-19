# 🌟 Guia Inicial de Tecnologias e Node.js para PA - Programação de Algoritmos

Bem-vindo(a) às aulas de **Programação de Algoritmos**! Aqui você vai encontrar um guia passo a passo para configurar seu ambiente de desenvolvimento e dar os primeiros passos com Node.js e JavaScript. Tudo pensado para iniciantes. 😃

---

## 1. Tecnologias e Ferramentas

### 1.1 Visual Studio Code (VSCode) 🖥️
**O que é:**  
VSCode é um editor de código leve, moderno e muito popular. Ele suporta várias linguagens e tem uma enorme quantidade de extensões que ajudam no desenvolvimento.

**Instalação:**  
- Acesse [VSCode](https://code.visualstudio.com/).  
- Baixe e instale para o seu sistema operacional.  
- Recomendo instalar a extensão **"JavaScript (ES6) code snippets"** para facilitar a programação.

---

### 1.2 Node.js ⚡
**O que é:**  
Node.js é um ambiente que permite rodar JavaScript fora do navegador, como no seu computador. Ele será a base para executar nossos códigos de backend.

**Instalação:**  
- Acesse [Node.js](https://nodejs.org/).  
- Baixe a versão **LTS (Long Term Support)**, que é mais estável.  
- Após instalar, abra o terminal e digite:
```bash
node -v
npm -v
````

Isso vai mostrar a versão instalada do Node.js e do npm (gerenciador de pacotes).

---

### 1.3 readline-sync 📝

**O que é:**
`readline-sync` é um módulo Node.js que permite **ler dados do usuário pelo terminal de forma síncrona** (um passo de cada vez). Usaremos ele para entrada de dados.

**Instalação:**
No terminal do VSCode ou Git Bash:

```bash
npm install readline-sync
```

---

### 1.4 Git Bash / Terminal 🖥️

**O que é:**
Um terminal permite executar comandos no seu computador. Para Windows, o Git Bash é recomendado, pois é mais parecido com o terminal Linux e facilita os exercícios.

**Instalação:**

* Acesse [Git](https://git-scm.com/downloads) e instale.
* Você poderá usar o Git Bash ou o terminal do VSCode para rodar seus códigos.

---

## 2. Primeiros Passos com Node.js

### 2.1 Criando um arquivo JavaScript

1. Abra o VSCode.
2. Crie uma pasta chamada `meu-projeto`.
3. Dentro da pasta, crie um arquivo chamado `index.js`.

---

### 2.2 Entrada de dados com readline-sync

```javascript
 **instalação**
npm i readline-sync

const readline = require('readline-sync');
//lembrando que você pode trocar o nome de readline para input ex:const input = require('readline-sync');
// Solicita um número ao usuário
let numero = readline.question("Digite um número: ");

console.log("Você digitou:", numero);
```

**Explicação:**

* `require('readline-sync')` importa o módulo para usar a função de entrada.
* `readline.question` pede que o usuário digite algo no terminal.
* `console.log` exibe informações no terminal.

---

### 2.3 Saída de dados

* Usamos `console.log()` para mostrar mensagens ou resultados no terminal.

```javascript
console.log("Olá, mundo!");
```

---

## 3. Tipos de Dados em JavaScript

| Tipo      | Exemplo     | Observações                         |
| --------- | ----------- | ----------------------------------- |
| Number    | 10, 3.14    | Números inteiros e decimais         |
| String    | "Olá", 'PA' | Texto entre aspas simples ou duplas |
| Boolean   | true, false | Verdadeiro ou falso                 |
| Undefined | undefined   | Variável declarada, mas sem valor   |
| Null      | null        | Valor intencionalmente vazio        |

**Dica:** Para converter tipos:

```javascript
let texto = "123";
let numero = Number(texto); // Converte string para número
let booleano = Boolean(numero); // Converte número para booleano
```

---

## 4. Operadores em JavaScript

### 4.1 Aritméticos

```javascript
+   // soma
-   // subtração
*   // multiplicação
/   // divisão
%   // resto da divisão
```

### 4.2 Atribuição

```javascript
=   // atribui valor
+=  // soma e atribui
-=  // subtrai e atribui
```

### 4.3 Comparação

```javascript
==  // igual
=== // igual e mesmo tipo
!=  // diferente
!== // diferente ou tipo diferente
>   // maior
<   // menor
>=  // maior ou igual
<=  // menor ou igual
```

### 4.4 Lógicos

```javascript
&&  // e
||  // ou
!   // negação
```

---

## 5. Próximos Passos

* Praticar a entrada e saída com `readline-sync` e `console.log`.
* Experimentar tipos de dados e operadores.
* Tentar criar pequenos algoritmos, como somar dois números ou comparar valores.

---

💡 **Dica Final:**
Sempre teste seu código no terminal. Se der erro, leia a mensagem com atenção — ela vai indicar onde está o problema. A prática constante é o segredo para aprender programação! 🚀

---

**Bom estudo e bons códigos! 😎**
