# Arrays

Exercício 1
const nomes = ['flávia','rafael','maria']
const objetos = ['mesa','cadeira','óculos']
const juntos = nomes.concat(objetos)
console.log(juntos)

Exercício 2
const numeros =[1,2,3,4,5,6,7,8,9,10]
const parteNumeros = numeros.slice(3, 7)
console.log(parteNumeros)

Exercício 3
const frutas =['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi']
frutas.splice(2, 2, 'kiwi', 'pessêgo')
console.log(frutas)

Exercício 4
const menuPrincipal = ['empada','feijoada','macarronada','parmegiana']
const menuDeSobremesas = ['sorvete','pudim','bolo']
const menuCompleto = menuPrincipal.concat(menuDeSobremesas)
console.log(menuCompleto)
