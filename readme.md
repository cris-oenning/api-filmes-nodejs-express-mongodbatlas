# API de filmes em Node.js com Express e MongoDB Atlas

Este é um projeto simples de exemplo de uma API de filmes em Node.js que utiliza o framework Express.js para criar endpoints que se conectam a um banco de dados MongoDB Atlas. Esta API permite realizar operações CRUD (Criar, Ler, Atualizar, Deletar) em uma coleção de filmes.

## Requisitos

Certifique-se de que você tenha as seguintes ferramentas instaladas em sua máquina antes de executar o projeto:

- Node.js - Ambiente de tempo de execução JavaScript.
- Um IDE ou editor de código de sua escolha (Recomendado: Visual Studio Code).

## Configuração

1 - Clone este repositório para a sua máquina local

2 - Instale as dependências necessárias com o comando "npm install"

3 - Configure a conexão com o MongoDB Atlas:

- Abra o arquivo app.js no seu editor de código.
- Substitua "sua string de conexão com o mongoDb Atlas" pela sua própria string de conexão com o MongoDB Atlas. Certifique-se de que sua string de conexão inclui credenciais válidas e o nome do banco de dados.

## Uso

Para iniciar a API, execute o seguinte comando como padrão "node src/index.js" ou configure seu script de start conforme sua necessidade.

A API estará disponível em http://localhost:3000.

## Rotas da API

- GET /: Retorna todos os filmes da coleção.

- POST /: Cria um novo filme na coleção. Envie um JSON no corpo da solicitação com os campos title, description, image_url e trailer_url.

- PUT /:id: Atualiza um filme existente com o ID especificado. Envie um JSON no corpo da solicitação com os campos que você deseja atualizar.

- DELETE /:id: Deleta um filme com o ID especificado.

## Exemplo de Solicitação

### POST / (Criar Filme)

{
"title": "O Poderoso Chefão",
"description": "Um clássico do cinema",
"image_url": "https://example.com/poderoso-chefao.jpg",
"trailer_url": "https://example.com/poderoso-chefao-trailer.mp4"
}

### PUT /:id (Atualizar Filme)

{
"title": "O Poderoso Chefão - Edição Especial",
"description": "Uma versão estendida do clássico",
"image_url": "https://example.com/poderoso-chefao-edicao-especial.jpg",
"trailer_url": "https://example.com/poderoso-chefao-edicao-especial-trailer.mp4"
}

### DELETE /:id (Deletar Filme)

Nenhuma carga útil é necessária. Apenas especifique o ID na URL.

## Contribuindo

Sinta-se à vontade para contribuir para este projeto. Você pode abrir problemas (issues) ou enviar solicitações de pull (pull requests) para melhorar o código ou adicionar recursos adicionais.

## Contatos

• E-mail: crisoenning@gmail.com
• Instagram: instagram.com/cristopher_oenning
• Github: github.com/cris-oenning
