<link rel="stylesheet" href="//cdnjs.cloudflare.com/ajax/libs/highlight.js/9.2.0/styles/default.min.css">
<script src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/9.2.0/highlight.min.js"></script>
# Just Digital Code Style

1. Configure o seu editor

  Certifique-se de utilizar identação de 2 espaços
  
  Não esqueça de salvar arquivos em utf-8

2. Seja cuidado com a sua nomenclatura


	var gato -> é uma variável

	var gatos -> é um array

4. Faça bons comentários. Não caia na armadilha de "tudo óbvio", quanto mais informações melhor

3. Não confie apenas nos comentários, escreva tudo com nomes descritivos

## Variáveis
```Javascript
// Sempre declare variáveis no topo do escopo que estiver trabalhando
var foo = "";
var bar = 0;
```

## Nomenclaturas
```Javascript
var fruta = 'tomate'; // recebe uma string;
var frutas = ['tomate', 'abacaxi', 'banana']; // recebe um array
```
## Condições
Espaços em branco podem ajudar na leitura

```javascript
// Bom
if (true) {
  // instruções
  } else {
  // instruções
}

// Ruim
if(true){
 ...
 }esle{
  ...
}
```
## Funções

```Javascript
// Bom (CamelCase e espaços em branco para facilitar a leitura
function myTestFunction(x, y) {

}

teste(foo, bar);

// Ruim (sem CamelCase e sem espaços para facilitar a leitura
function My_test_function(foo,bar){

}

My_test_function(foo,bar);
