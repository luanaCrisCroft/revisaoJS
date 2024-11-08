# revisaoJS
Acesse o site do Minecraft Code e realize o cadastro e em seguida o login.
Inicialmente ele pede para vocês selecionarem o idioma e pode ser o Português.
Se você já fez o Aventureiro pode escolher outro. O importante é vocês fazerem porque farei referência em nossas aulas.
Qualquer dúvida coloquem aqui nos comentários porque pode ser a dúvida do seu colega.

Minecraft | Code.org
https://code.org/minecraft

## Cria um mapa mental para resolver o problema abaixo:
1. Calculando sua média com 3 notas em 2 disciplinas.
2. Passar num concurso.
3. Construir um aplicação.

## Tente transformar em flowgorithm a solução acima.
Abra o Power Point Lógica de Programação e adicione no Flowgorithm (http://www.flowgorithm.org/download/).
Depois adicione a foto ou o que você salvou no formato .frpg

## Faça em Portugol ou no Visual Studio Code
1. Desenvolva um algoritmo para somar dois valores inteiros 
2. Desenvolva um algoritmo que receba dois números inteiros, encontre a soma destes e a exiba na tela.
3. Desenvolva um algoritmo que receba o primeiro e o segundo nome do usuário e que exiba as 2 palavras concatenadas.
4. Desenvolva um algoritmo que recebe três notas e retorne a sua média aritmética simples.
5. Desenvolva um algoritmo que calcule o volume de uma esfera de raio R, fornecido pelo usuário. 
(V =4/3πR^3)
6.Escrever um algoritmo para determinar o consumo médio de um automóvel sendo fornecida a distância total percorrida pelo automóvel e o total de combustível gasto "90% do sucesso se baseia em simplesmente não desistir!" - Woody Allen

### Bonus
7.Faça um algoritmo que receba dois números e ao final most re a soma, subtração, multiplicação e a divisão dos números lidos
8.Escrever um algoritmo que leia o nome de um vendedor, o seu salário fixo e o total de vendas efetuadas por ele no mês (em dinheiro). Sabendo que este vendedor ganha 15% de comissão sobre suas vendas efetuadas, informar o seu nome, o salár io fixo e salário no final do mês.
Fonte: https://ooffoo.wordpress.com/portugol-ide/listaoexercicios-portugol/

## Faça no Visual Studio usando JavaScript: 
Você vai ter uma festa e só pode entrar com essas condições:
1. se for maior que 18 e passou em todas as matérias o aluno pode entrar.
2. se for menor que 18 e estiver com a mãe ou o pai e tiver passado ele pode
entrar.
3. Se o aluno não passou por média mas frequentou 75% as aulas e é maior 18 pode
entrar.
Observação: Adicione uma condição default para retornar que ele não vai entrar caso não atenda a essas condições.

## Git e GitHub
https://www.alura.com.br/artigos/o-que-e-git-github

Fazendo analogia com o pendrive que usamos diariamente:
git init (adiciona a pasta .git) = seria quando a gente define qual pendrive usar e insere ele no computador
git add . (adiciona todos os arquivos da nossa pasta) = seria quando a gente seleciona todos os arquivos que desejamos copiar da nossa máquina.
git commit -m "adicionando nossos arquivos" = seria quando a gente dar o ctrl + c para copiar todos os arquivos que desejamos copiar
git branch -M main (definimos a branch que iremos adicionar os arquivos) = seria quando a gente cria uma nova pasta no nosso pendrive para receber os nossos arquivos copiados.
git remote add origin https://github.com/luanaCristina/testeAulaMod1.git (o nome do nosso repositório que irá ser colocado nossos arquivos) = aqui seria quando a gente dar o nome para nossa pasta. Aqui a gente já sabe o nome.
git push -u origin main 
(transfere todos os arquivos dselecionados para 

 dentro do repositõrio do GitHub.)  = aqui a gente utiliza o ctrl + v para colar os nossos arquivos selecionados dentro do nosso pendrive.

## lógica com javascript
### variáveis
var nome = "Luana"
let idade = 18
const pi = 3.14
//tipo da variáveis defiinida em tempo de execucação

console.log(nome + " " + idade + " " + pi)


var nota1 = 4
var nota2 = 5
var nota3 = "4"
var soma = nota1 + nota2
console.log(soma)
var resto = soma%2
console.log(resto)

nota1 == nota2
nota1 === nota3
nota1 > nota2
nota1 >= nota2

if(soma >=7){
    console.log("aluno aprovado")
}

### array

var sorvete = "tamarindo"
console.log(sorvete)
//variável evoluída - do pichu para pikashu (ARRAY)

//index = primeiro elemento começa com 0
var saboresSorv = ["coco", "chocolate", "morango", "limao"] 
console.log(saboresSorv)

saboresSorv.push("menta")
console.log(saboresSorv)

saboresSorv.pop()
console.log(saboresSorv)

saboresSorv[0] = "cajá"
console.log(saboresSorv)

console.log(saboresSorv.length);

saboresSorv.splice(1,0, "jaca", "tamarindo", "delícia de abacaxi")
console.log(saboresSorv)

### for sintaxe
for(let banana = 0; banana >= 100; banana ++){
    console.log(banana)
}

//impares 200 elementos
for(let numero = 0; numero <=200; numero++){
    if(numero % 2 === 0){
        console.log(numero)
    }
}
    console.log("=======================")
    console.log("ímpares")
    console.log("========================")

  for(let numero = 0; numero <=200; numero++){
        if(numero % 2 !== 0){
            console.log(numero)
        }
    }

### function
//função é um bloco de instruçõa que vai executado quando eu chamar.
//funcao pode ter ou nao parametros
//A gente precisa chamar a função senão ela não executa.

function media(nota1, nota2, nota3, nota4){
    var soma = (nota1+nota2+nota3+nota4)/4
    if(soma>=6){
        console.log("O aluno foi aprovado")
    }else{
        console.log("O aluno foi reprovado")
    }
}
media(10, 9, 7, 6)
media(4,3,2,1)
media(2,4,6)

//função com return e sem parâmetro
function olaGente(){
    return "Olá pessoaaaallllllll"
}

//função chamando função
function escrevaOlaGente(nomeAluno){
    console.log(`${olaGente()} O aluno ${nomeAluno} foi reprovado`)
}

escrevaOlaGente("Dayvison")

### object
let pessoa = {
    nome: "Luana",
    matricula: "20234567",
    cpf: "000000000",
    dataNascimento: "12/12/2012",
    etinia: "parda",
    cadastroAtualizado: true,
    pet: ["Luna", "Negão", "Branquinho", "Branquinha"]
}


console.log(pessoa.cpf)

let pet = {
    nome: "Luna",
    raca: "vira-lata",
    cor: "preta com branco",
    tamanho: "pequeno porte",
    fala: function(){
        return "au au au"
    }
}

console.log(pet.fala())

### object com new
let bolo = {
    ingredientes: ["trigo", "ovo", "fermento", "açúcar"],
    forma: "redonda"
}

function Pets(nome, raca, cor, tamanho, tipoAnimal, castrado, sexo){
    this.nome = nome;
    this.raca = raca;
    this.cor = cor;
    this.tamanho = tamanho;
    this.tipoAnimal = tipoAnimal;
    this.castrado = castrado;
    this.sexo = sexo;
    this.fala = function(fala){return fala}
}
let branquinho = new Pets("Branquinho", "vira-lata", "branco com amarelo",
    "pequeno porte", "gato", true, "macho")
console.log(branquinho);
console.log(branquinho.fala("miau miau miau"))


  
