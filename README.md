

# Globo-Fishing

## Conceito do projeto
No cerne deste projeto encontra-se a concepção de um website com enfoque no desenvolvimento de conscientização e segurança digital.
A proposta central é proporcionar aos usuários uma experiência educativa e prática, visando ampliar a compreensão sobre os métodos utilizados por agentes maliciosos na internet, com ênfase especial em ataques de phishing.
Para isso foi criado do zero um website que simula o globo.com, mas que na realidade seria um site malicioso que rouba as informações dos usuarios desavisados

Link para o site criado: https://globo-fishing.vercel.app/
  
## Pré-requisitos e recursos utilizados
No Front-end foi utilizado HTML, CSS e javascript, alem da hospedagem gratuita da Vercel 
No Back-end foi utilizado Node.js, MongoDB além de bibliotecas como cors, express, joi, entre outras. Sua hospedagem foi feita gratuitamente com o Render

## Passo a passo
1. Estudei o site da Globo
2. Construi o HTML e CSS separando por seções
3. Construi um Back simples e com banco de dados para poder quardar os logins
4. Após vários testes fiz o deploy


## Instalação
O projeto já possui um deploy, mas caso queira instalá-lo em sua máquina aqui vai o passo a passo

Para o Front basta ter uma copia do projeto e arrastar o arquivo HTML para o seu navegador

Para o Back-end é necessário ter o MongoDB em sua máquina

1. Crie um arquivo .env e o complete-o como no arquivo .envExample
2.
  ```
  Execute o comando npm install no terminal, dentro da pasta do projeto
  ```
3.
  ```
  Execute o comando npm install no terminal, dentro da pasta do projeto
  ```

## Execução


![Imagem](https://github.com/Vinicius-Terra/Globo-Fishing/blob/main/Screenshot%20from%202023-08-16%2017-42-44.png)

Você pode começar explorando a aplicação pela página de início do Front-end. Lá, existe um botão escondido que, ao ser clicado, envia discretamente todas as informações já coletadas pelo site para o seu navegador. Para fazer isso, basta clicar no anúncio de pescaria (que é um botão secreto), em seguida, usar o botão direito do mouse, clique em "Inspecionar". Procure pela seção "Console"; assim, você terá acesso às informações.

![Imagem](https://github.com/Vinicius-Terra/Globo-Fishing/blob/main/Screenshot%20from%202023-08-16%2018-02-56.png)


Para adicionar novas informações ao banco de dados, basta agir como um usuário comum que deseja fazer login na conta da Globo.

![Imagem](https://github.com/Vinicius-Terra/Globo-Fishing/blob/main/Screenshot%20from%202023-08-16%2018-03-29.png)

![Imagem](https://github.com/Vinicius-Terra/Globo-Fishing/blob/main/Screenshot%20from%202023-08-16%2018-04-33.png)


## Bugs/problemas conhecidos
O site esta hospedado em servisos gratuitos, então existe uma lentidão para a resposta do servidor, é preciso ser paciente.

## Autores
* Vinícius Fernandes Terra Silva


