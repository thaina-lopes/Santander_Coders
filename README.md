<!DOCTYPE HTML5>
<h1><div align = "center"> Santander Coders 2023.2 | Front-End :computer:</div></h1>
</br>
<h2><b><div align = "center">Objetivo</align></b></h2>
<p>Esse repositório irá guardar os conceitos e conhecimentos adquiridos com o curso de Front-End fornecido pela Ada Tech.</p>
</br></br>

<h2><b><div align = "center">Sequência cronológica</div></b></h2>
</br>
:dart: Github </br>
:dart: JavaScript </br>
</br></br>

<h1><b><div align = "center">Git e Github</div></b></h1>
</br>
<h3><b><div align = "center">Comandos para subir o projeto para o Github a partir do terminal:</div></b></h3>
</br>
<p><b>git init</b> Inicia um repositório Git em um diretório específico</br>
<b>git add .</b> Adiciona todas as alterações feitas nos arquivos do diretório atual ao "staging area" do Git </br>
<b>git status</b> Exibe informações sobre quais arquivos foram modificados, quais estão no "staging area" prontos para serem commitados, e se há diferenças entre a cópia local e o repositório remoto.</br>
<b>git commit -m exemplo</b> (nome do commit) Usado para criar a primeira versão do repositório Git</br>
<b>git branch -M main</b> Usado para renomear a branch padrão do Git de 'master' para 'main'. O -M é usado para forçar a mudança de nome da branch principal.</br>
<b>git remote http://...</b> (link do repositório do github) Usado após o primeiro commit, quando você decide conectar o seu repositório local a um repositório remoto existente ou ao criar um novo repositório remoto.</br>
<b>git push -u origin main</b> Usado para enviar commits locais para um repositório remoto chamado "origin" </p>
</br>

<h3><b><div align = "center">Comandos para fazer um commit:</div></b></h3>
</br>
<p><b>git status</b></br>
<b>git add .</b></br>
<b>git status</b></br>
<b>git commit -m exemplo</b> (descrição da alteração feita no projeto)</br>
<b>git push origin main</b></br>
</br>

</br></br>
<h1><b><div align = "center">JavaScript</div></b></h1>
</br>
<h2><b><div align = "center">Variáveis e tipos de dados</div></b></h2>
<p><b>Number:</b> Números</br><b>String:</b> Texto</br><b>Booleano:</b> Verdadeiro ou falso </br> <b>Array:</b> Armazena uma coleção de valores</br><b>Object:</b> Conjunto de atributos aninhados a uma variável</br><b>Functions:</b> É possivel declarar uma variável como uma função, podendo fazer operações e retornando o valor para a variável de declaração </p>
<p>No <b>JavaScript</b>, as variáveis podem ser declaradas de duas maneiras, sendo elas:</p>
<p><b>const:</b> Usado para declarar variáveis que não podem ser reatribuídas.</br><b>let:</b> Usado para declarar variáveis que podem ser reatribuídas.</p>
<p>Exemplo de como elas podem ser chamadas:</p>

```javascript
const primeiroExemplo;
let segundoExemplo;
```
</br></br>
<h2><b><div align = "center">Operadores Booleanos</div></b></h2>
<p><b>Igualdade:</b> == (ou ===)</br><b>Desigualdade:</b> != (ou !==)</br><b>Maior que:</b> > </br><b>Menor que:</b> < </br><b>Maior ou igual:</b> >= </br><b>Menor ou igual:</b> <= </br> </p>

</br></br>
<h2><b><div align = "center">Conjunções lógicas</div></b></h2>
<p><b>END:</b> &&</br><b>OR:</b> ||</br><b>NOT:</b> ! </p>

</br></br>
<h2><b><div align = "center">Funções</div></b></h2>
<p>A função nada mais é do que um bloco de cógido que podemos invocar diversas vezes, ela pode ou não retornar um valor. Seu comando de escrita é o <b>function</b> e sua estrutura é basicamente como representado abaixo:</p>

```javascript
function nomeDaFuncao (value){
  return value;
}
```

</br></br>
<h2><b><div align = "center">Condicionais</div></b></h2>
<p>O uso de comandos condicionais, determinam como o código deve se comportar de acordo com cada condição programada. Ele poderá ter 1, 2, 3 ou mais situações condicionais, e seus comandos são: <b>if</b>,<b> else</b> e/ou <b>else if.</b></p>
<p>Exemplo de como usar:</p>

```javascript
if(condição){
  //condição se for verdadeiro
}
else{
  //condição se for falso
}
```

</br></br>
<h2><b><div align = "center">Loops</div></b></h2>
<p>Em <b>JavaScript</b>, os 'loops' são usados para fazer um programa executar uma mesma ação várias vezes. Esses loops podem ter ou não um número específico de repetições, dependendo do comando utilizado.</p>
<p>Quando sabemos exatamente quantas vezes queremos que o programa repita uma ação, podemos usar o comando <b>for</b>. Isso acontece quando temos um intervalo pré-definido, o que nos permite determinar quando o ciclo começa e termina. O <b>for</b> é útil nessas situações porque controlamos exatamente o número de vezes que a ação será repetida.</p>
<p>Segue um exemplo do modelo de escrita:</p>

```javascript
for(início; condição; modificador){
  //código que será executado em cada repetição
}
```

<p>Ao contrário do <b>for</b>, o <b>while</b> é útil quando não temos um número específico de repetições em mente, mas queremos continuar executando um bloco de código enquanto uma condição permanecer verdadeira.</p>
<p>Segue um exemplo:</p>

```javascript
while(condição){
  //rotina
}
```

</br></br>
<h2><b><div align = "center">Arrays</div></b></h2>
<p>Um <b>Array</b> nos permite armazenar uma coleção de dados ordenados.</br>Sua estrutura é representada por dois colchetes '[ ]' que indicam respectivamente o início e o fim de um array. Para separar os valores dentro dele, utilizamos a vírgula ','.</br>Dentro de um array, podemos ter diversos tipos de dados, podem ser string, number, boolean e entre outros. Os arrays são acessados por meio de um índice numérico, começando geralmente do zero.</p>
<p>Segue um exemplo da estrutura de um array:</p>

```javascript
let arrayNomes = ['Ana', 'Camila', 'Marcela'];
console.log("O nome que está nessa posição é: "+arrayNomes[2]); //O nome que está nessa posição é: Marcela
```
