![banner](https://raw.githubusercontent.com/lucianesantcs/origamid-vue/master/public/mockup.png)

# Origamid Vue

Contém dois projetos, Techno Store e Techno Cursos, desenvolvidos no curso de VueJS completo na Origamid.<br>

**Techno Store** <br>
Foi desenvolvido sem a instalação do Vue, apenas importando o arquivo `vue.min.js`<br>

**Techno Cursos** <br>
Foi criado com a instalação do Vue, usando `vue create`, contém toda a estrutura de um projeto na linguagem.

### Previews

Screens das telas encontram-se na pasta `./design` de cada projeto.

## Como usar

Faça um clone deste repositório:

```sh
  $ git clone https://github.com/lucianesantcs/origamid-vue.git
```

### Techno Cursos

Entre na pasta do projeto com `cd techno-cursos` e instale as dependências:

```sh
  # com npm
  $ npm install

  # com yarn
  $ yarn install
```

Inicie o projeto com o comando:

```sh
  # com npm
  $ npm run serve

  # com yarn
  $ yarn run serve
```

Acesse o projeto em `http://localhost:8080/`

**API**

É necessário instalar o <a href="https://github.com/typicode/json-server">json server</a> para usar a api.
Entre na pasta api com `cd api` e use o comando:

```sh
  $ json-server --watch api.json
```

Você consegue acessar a api em `http://localhost:3000/`

### Techno Store

Entre na pasta do projeto com `cd techno-store` para ver os arquivos. <br>
Vocẽ irá precisar de um servidor para visualizar o projeto, como Live Server no VSCode.

## Author

**Luciane Santos**

- Email: lucianesantcs@gmail.com
- GitHub: [@lucianesantcs](https://github.com/lucianesantcs)
- LinkedIn: [@lucianesantcs](https://linkedin.com/in/lucianesantcs)

## License

Copyright © 2020 Luciane Santos / Origamid
