# Repositório Final do Projeto da UC de Projeto Mobile

## Para testar a aplicação, algumas configurações devem serem feitas

- O Back End do projeto foi construído em cima de uma API local, Node. Para conseguir utilizar integralmente a aplicação, deverá baixar o repositório mobile_api em: https://github.com/Adriel21/mobile_api

- Após baixar o repositório, dê um `npm install`

- Pegue o banco de dados `mobile (4).sql` que está no repositório Fala-no-Mic-Final, na pasta `bd`

- Crie um banco de dados no PHPMYADMIN com o nome mobile e, importe o arquivo do passo a cima

- Inicie a API node, com o comando `node index.js`

- Mude o endereço ip dos arquivos em que está sendo consumida a api no projeto, nos arquivos: home.js, cadastro.js, detalhes.js, perfilpublico.js, perfil.js, publicar.js, editarRedeSocial.js

- Inicie o projeto com npm start e utilize o expo go ou android studio para emular o projeto
