# lista-21-03

*atividade 1*
const alunos1 = ['evandro', 'camila', 'mariana']
const alunos2 = ['luzia', 'cathia', 'paloma']

const salasunidas = alunos1.concat(alunos2)
console.log(salasunidas)

*atividade 2*
const numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
const parteNumeros = numeros.slice(3, 7)
console.log(parteNumeros)

*atividade 3*
const frutas = ['Maçã', 'Banana', 'Laranja', 'Limão', 'Abacaxi']
frutas.splice(2, 2, 'Kiwi', 'pessêgo')
console.log(frutas)

*atividade 4*
const menuPrincipal = ['macarrão', 'risoto', 'feijoada']
const menuDeSobremesas= ['bolo', 'torta', 'sorvete']
const menuCompleto = menuPrincipal.concat(menuDeSobremesas)
console.log(menuCompleto)
