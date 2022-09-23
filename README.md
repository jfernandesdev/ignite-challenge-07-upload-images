# Upload Images
Desafio 07 - Jornada Ignite by Rocketseat - Trilha ReactJS - Tema: "Upload Images" 📤

## Descrição

Esta é uma aplicação de upload de imagens no ImgBB (serviço de hospedagem de imagens)

- [x] Infinite Queries (listagem que adiciona mais dados ao clicar em um botão de carregamento) e Mutations (utilizada nessa aplicação para o cadastro de uma nova imagem no banco) com React Query;
- [x] Envio de formulário com React Hook Form;
- [x] Exibição de Modal e Toast com Chakra UI.

###  Rodando a aplicação localmente:

#### ImgBB:
Para o armazenamento das imagens foi utilizar uma solução de hospedagem de arquivos gratuita e de fácil utilização chamada ImgBB (não é a melhor solução para esse tipo de hospedagem). Então primeiro é preciso criar uma conta no ImgBB, criar a uma chave da API e copiar e colar o valor no .env.local `NEXT_PUBLIC_IMGBB_API_KEY=VALOR_DA_CHAVE_COPIADA`

#### FaunaDB:
Para o armazenamento das informações das imagens (url, título e descrição), foi utilizado o FaunaDB. Tudo que você precisa fazer é criar um banco no FaunaDB com um nome de sua preferência que **precisa** ter uma coleção chamada `images`. Com o banco e coleção criados, basta você criar e copiar a chave do banco no seu arquivo `.env.local` da seguinte forma: `FAUNA_API_KEY=VALOR_DA_CHAVE_COPIADA`


Depois instale as depedências e rode a aplicação:
```sh
$ yarn install
```
```sh
$ yarn dev 
```

## Layout 🤩

### Desktop (screenshot):

| Home | Modal nova imagem | 
| --- | --- |
| <img src="https://github.com/jfernandesdev/ignite-challenge-07-upload-images/blob/f02c1e7ffa0c62f8aecca879939afdf4bcfd29e7/public/desktop-1.png" /> |  <img src="https://github.com/jfernandesdev/ignite-challenge-07-upload-images/blob/f02c1e7ffa0c62f8aecca879939afdf4bcfd29e7/public/desktop-2.png" /> |
