<h3 align="center">AngularJS</h3>

---

**AngularJS #1 -** Introdução e Hello World

AngularJS é uma framework para o desenvolvimento de aplicações web utilizando a linguagem JavaScript! <br>
Estrutura a arquitetura da aplicação em camadas bem definidas. <br>
Permite a criação de componentes reusáveis e modulares. <br>
Fornece a infraestrutura necessária para integrar com o back-end. <br>
Facilita a automação de testes.

Misko e Hevery e Adams Abrons criaram o projeto em 2009. <br>
Facilitar a criação de aplicações web!

Produtividade <br>
Totalmente escrito em JavaScript <br>
Separação de Responsabilidades

Controller - Responsável pelo o que a View consome <br>
Scope - Faz a mediação entre View e Controller <br>
View (DOM) - É o que o cliente vê

[AngularJS](https://angularjs.org/) <br>
Download AngularJS - ZIP

---

**AngularJS #2 e #3 -** Usando Diretivas

Diretivas são extensões da linguagem HTML que permitem a implementação de novos compartamentos, de forma declarativa.

**ngApp** <br>
Definindo as fronteiras da aplicação

**ngController** <br>
Vinculando um elemento da View ao Controller

**ngModel** <br>
Vinculando uma propriedade ao $scope

**ngClick** <br>
Atribuindo um comportamento ao evento

**ngDisabled** <br>
Desabilitando um elemento dinamicamente

**ngOptions** <br>
Renderiza as opções de um select

**ngClass e ngStyle** <br>
Aplicando classes CSS e estilos dinamicamente

**ngShow, ngHide e ngIf** <br>
Exibindo um elemento condicionalmente

**ngInclude** <br>
Incluir conteúdo dinamicamente

---

**AngularJS #4 -** Validando Formulários

**ngRequired** <br>
Define um determinado campo como obrigatório

**$valid e $invalid** <br>
Consultando a validade de um campo ou formulário

**$pristine e $dirty** <br>
Verificando se um formulário ou campo já foi utilizado alguma vez

**ngMinlength e ngMaxlength** <br>
Define o tamanho mínimo e máximo permitido

**$error** <br>
Consultando os erros de um campo ou formulário

**ngPattern** <br>
Define uma RegExp para validar o campo

---

**AngularJS #5 -** Aplicando Filtros

Filtros <br>
Transformam o resultado de uma expressão, realizando operações como a formatação de data, a conversão de moeda e a ordenação de Array.

**uppercase**
Transforma uma String em letra maiúscula

**lowercase**
Transforma uma String em letra minúscula

**date**
Formata uma data usando uma máscara

**filter**
Filtra um Array com base em um critério

```js
$filter("uppercase")("Lucas")
uppercaseFilter("Lucas")
```

**orderBy**
Ordena um Array com base em um critério

**currency**
Converte um número para moeda

**number**
Formata um número

**limitTo**
Limita um Array ou uma String

---