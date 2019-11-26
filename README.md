//matriz

var educacao = [ 'escola', 'faculdade' ];

console.log (educacao.length);

//Acessar em um array 

var first = educacao[first. length -1];

var last = educacao[educacao.length -1];


//LOOP SOBRE UMA MATRIZ

educacao.forEach(function(item, index, array) {
  console.log(item, index);
});

//ADICIONAR AO FINAL DE UMA MATRIZ

var newLength = frutas.push ('Laranja' );

//REMOVA DA FINAL DE UMA MATRIZ

var last = frutas.pop ();

//REMOVA DA FRENTE DE UMA MATRIZ

var primeiro = frutas.shift();

//ADICIOANAR Á FRENTE DE UMA MATRIZ

var newLength = frutas.unshift('Strawberry')

//ENCONTRE O INDICE DE UM ITEM NA MATRIZ

frutas.push('manga');

var pos = frutas.indexOf ('Banana');

//REMOVER UM ITEM PELA POSICAO DO INDICE

var removedItem = frutas.emenda(pos.1);

//REMOVER ITENS DE UMA POSICAO DO INDICE

var vegetables = [ 'Repolho', 'Nabo', 'Rabanete'];
console.log(vegetais);

var pos = 1, n = 2;

var removedItems = vegetais.emenda (pos, n);

console.log(vegetais);

console.log(removedItems);

//COPIAR UMA MATRIZ

var shallowCopy = frutas.fatia();
