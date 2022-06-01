# Desafio | Front End

Olá! Seja bem vindo ao teste para a vaga de Frontend Developer para o time da Creatus.

Escolhemos um teste que abordará seus conhecimentos em HTML, CSS e Javascript. Você será encaixado na vaga de acordo com seu resultado.


## Sobre o Desafio

O desafio consiste no desenvolvimento do layout de uma landing page com uma grade de produtos e um formulário de newsletter. Seu principal objetivo é transformar este layout em uma página funcional.

**Link do layout:** https://xd.adobe.com/spec/4025e242-a495-4594-71d2-5fd89d774b57-3614

**Endpoint da API:** https://frontend-intern-challenge-api.iurykrieger.now.sh/products?page=1


### Layout

Você terá que implementar o layout de acordo com esse mock. O mock contém a estrutura do layout e todo o estilo da página.

É importante se ater aos detalhes de tamanho e espaçamento entre os elementos da página, construindo o HTML mais semântico possível utilizando-se das tags do HTML5.

### Comportamento

Para preencher a página com as informações dos produtos, você terá que consultar esta [**API**](https://frontend-intern-challenge-api.iurykrieger.now.sh/products?page=1) de forma paginada, sendo que cada página consultada retornará as informações de 8 produtos e um link para a próxima página.

Assim que obter os dados, você deverá implementar os seguintes pontos:
* Para cada produto retornado pela API, um card de produto com as respectivas informações deve ser criado na grade de produtos;
* Ao clicar no botão Ainda mais produtos aqui! a próxima página da API deve ser consultada, gerando mais 8 produtos na grade existente, abaixo dos produtos * já carregados pela primeira requisição;
* Os formulários devem ter seus campos de input validados de acordo com o conteúdo (ex: O campo de email deve conter um email válido);

## Instruções
* Crie um repositório no seu github que irá conter o desenvolvimento do seu desafio.
* Faça commits ao longo do seu desenvolvimento, isso nos ajudará a entender sua linha de raciocínio ;)
* Faça README.md que contenha as informações de setup e a descrição do seu projeto;
* Suba um live preview do seu desafio em um dos provedores a seguir, isso nos ajudará a testar sua implementação:
  * Now
  * Heroku
  * Netifly
  * Qualquer outro semelhante

Assim que concluir o seu desafio, nos envie o link do seu repositório contendo o resultado do seu desafio e o link do live preview para que possamos testá-lo.

<br/>

###### _Créditos: https://github.com/chaordic/frontend-developer-challenge_
