
1 - Criar uma nova lista com todos os itens da lista abaixo multiplicados por 2
Lista de Números - [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

2 - Criar uma lista de objetos a partir da lista abaixo, cada objeto da lista deve conter uma propriedade chamada "nome" que será o item da posição (Nome da fruta)
Lista de Frutas - ['Maçã', 'Abacaxi', 'Kiwi', 'Figo', 'Noz']

3 - Criar uma lista somente com o id dos usuários a partir da lista abaixo
Lista de usuários = [
  { id: 5887, nome: 'Jonathan do Typescript', idade: 24, admin: true }, 
  { id: 2356, nome: 'Vinicius', idade: 24, admin: false },
  { id: 4158, nome: 'Amanda', idade: 30, admin: true },
  { id: 5678, nome: 'Nathalia', idade: 26, admin: false },
  { id: 5689, nome: 'Flávia', idade: 29, admin: false },
]

4 - Criar uma lista invetendo os valores, a chave agora é valor, e o valor é a chave
Ex:. // { 5887: 'id', Jonathan do Typescript: 'nome', 24: 'idade', true: 'admin' }

Lista de usuários = [
  { id: 5887, nome: 'Jonathan do Typescript', idade: 24, admin: true }, 
  { id: 2356, nome: 'Vinicius', idade: 24, admin: false },
  { id: 4158, nome: 'Amanda', idade: 30, admin: true },
  { id: 5678, nome: 'Nathalia', idade: 26, admin: false },
  { id: 5689, nome: 'Flávia', idade: 29, admin: false },
]

5 - Criar uma lista de objetos onde cada objeto será composto pelas propriedades atuais mais uma nova propriedade chamada "profissao" com o valor "Dev. Front ✌️"

Lista de Usuários = [
  { id: 5887, nome: 'Jonathan do Typescript', idade: 24, admin: true }, 
  { id: 2356, nome: 'Vinicius', idade: 24, admin: false },
  { id: 4158, nome: 'Amanda', idade: 30, admin: true },
  { id: 5678, nome: 'Nathalia', idade: 26, admin: false },
  { id: 5689, nome: 'Flávia', idade: 29, admin: false },
]


6 - No caso abaixo, temos duas listas quase iguais, porém cada uma possuem propriedades diferentes, porém precisamos de apenas uma lista
fazer um "merge" das duas listas (explicar no dia)

Lista 1 = [
  { id: 5887, nome: 'Jonathan do Typescript' },
  { id: 2356, nome: 'Vinicius' },
  { id: 4158, nome: 'Amanda' },
  { id: 5678, nome: 'Nathalia' },
  { id: 5689, nome: 'Flávia' },
]

Lista 2 = [
  { id: 5887, conhecimentos: ['javascript', 'scss', 'vue.js', 'html'], admin: true }, 
  { id: 2356, conhecimentos: ['javascript', 'scss', 'vue.js', 'html'], admin: false },
  { id: 4158, conhecimentos: ['javascript', 'scss', 'vue.js', 'html'], admin: true },
  { id: 5678, conhecimentos: ['javascript', 'scss', 'vue.js', 'html'], admin: false },
  { id: 5689, conhecimentos: ['javascript', 'scss', 'vue.js', 'html'], admin: false }
]

✅ Ex. de um valor correto: { id: 5887 nome: 'Jonathan do Typescript', conhecimentos: ['javascript', 'scss', 'vue.js', 'html'], admin: true }