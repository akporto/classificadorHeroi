# Classificador de Nível de Herói

Este é um projeto simples em JavaScript para classificar o nível de um herói com base na sua quantidade de experiência (XP). O sistema atribui um nível ao herói com base em uma série de faixas de XP, variando de "Ferro" a "Radiante".

## 🛠️ Funcionalidades

- Classificação do herói em diferentes níveis com base em sua quantidade de XP.
- Atribui uma mensagem personalizada mostrando o nome do herói e seu nível.

## 🚀 Como Usar

1. Clone o repositório ou baixe os arquivos no seu computador.
2. Abra o arquivo `.js` no seu editor de código favorito.
3. No código, você verá duas variáveis principais:
   - `nomeHeroi`: que armazena o nome do herói.
   - `experiencia`: que armazena a quantidade de XP do herói.
4. Modifique essas variáveis conforme desejado para testar diferentes heróis e valores de XP.
5. Execute o código para ver o resultado no console, que será uma mensagem indicando o nome e o nível do herói.

## 🔄 Exemplo de Uso

let nomeHeroi = "Thor";
let experiencia = 7500;

Ao executar o código acima, a saída será:

O Herói de nome Thor está no nível de Platina

## 🔢 Lógica de Classificação
Se XP for menor do que 1.000 = Ferro
Se XP for entre 1.001 e 2.000 = Bronze
Se XP for entre 2.001 e 5.000 = Prata
Se XP for entre 5.001 e 7.000 = Ouro
Se XP for entre 7.001 e 8.000 = Platina
Se XP for entre 8.001 e 9.000 = Ascendente
Se XP for entre 9.001 e 10.000 = Imortal
Se XP for maior ou igual a 10.001 = Radiante

## 🧑‍💻 Tecnologias Utilizadas
JavaScript: A linguagem principal utilizada para lógica do programa.
