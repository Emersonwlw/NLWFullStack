
<h1 align="center">
   NLW Spacetime - Cápsula do Tempo
</h1>

<p align="center">
  
  <img alt="Made by Emerson Willian" src="https://img.shields.io/badge/made%20by-Emerson Willian-%20?color=6c4ad0">
  <img alt="Project top programing language" src="https://img.shields.io/github/languages/top/emersonwlw/NLWFullStack?color=6c4ad0">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/emersonwlw/NLWFullStack?color=6c4ad0">
</p>

<p align="center">
  <a href="#information_source-como-executar">ℹ️ Como Executar?</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#rocket-tecnologias">🚀 Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-autores">💻 Autores</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<p align="center">
  O <b>NLW Spacetime - Cápsula do Tempo</b> é o projeto desenvolvido durante a <b>NLW Spacetime da Rocketseat</b>, utilizando <b>NodeJS</b> com <b>Fastify</b> e <b>React</b> com <b>NextJS 13</b>.
</p>

<p align="center">
  <table>
    <tr>
      <td>
        <img alt="Demonstration" src="https://github.com/tavareshenrique/nlw-spacetime/blob/main/previews/NLW-Spacetime.gif?raw=true" width="800px" />
      </td>
    </tr>
  </table>
</p>

---

> 🧪 Essa aplicação não possuirá **Testes Unitários**, **Integração** e **E2E** por não ser o foco do estudo, mas está pronta para ser executada. 🧪

# :information_source: Como Executar?

> Clone o Repositório:

```bash
git clone https://github.com/Emersonwlw/NLWFullStack.git
```

## Server

> Acesse o Server

```bash
cd server
```

> Instale as dependências:

```bash
npm install
```

> Informe as variáveis de ambiente
```bash
cp .env.example .env
```

```bash
GITHUB_CLIENT_ID=""
GITHUB_CLIENT_SECRET=""
```

> Execute o Prisma para criar as tabelas

```bash
npx prisma migrate dev
```

> Inicie o Serviço:

```bash
npm dev
```

## Web

> Com o Server Iniciado, acesse o projeto Web:

```bash
cd .. && cd web
```

> Instale as dependências:

```bash
npm install
```

> Informe a variável de ambiente
```bash
cp .env.example .env
```

```bash
NEXT_PUBLIC_GITHUB_CLIENT_ID=
```

> Inicie o Projeto:

```bash
npm dev
```

> ➡️ Acesse [http://localhost:3000](http://localhost:3000) para acessar a aplicação web.


# :rocket: Tecnologias

- [React](https://reactjs.org/)
- [NodeJS](https://nodejs.org/en/)
- [Typescript](https://www.typescriptlang.org/)
- [Axios](https://axios-http.com/ptbr/docs/intro)
- [Fastify](https://www.fastify.io/)
- [Prisma](https://www.prisma.io/)
- [Zod](https://zod.dev/)
- [NextJS](https://nextjs.org/)
- [TailwindCSS](https://tailwindcss.com/)
- [DayJS](https://day.js.org/)
- [JS Cookie](https://github.com/js-cookie/js-cookie)
- [JWT Decode](https://github.com/auth0/jwt-decode#readme)

# :computer: Autores

<table>
  <tr>
    <td align="center">
      <a href="http://github.com/emersonwlw/">
        <img src="https://avatars.githubusercontent.com/u/60038829?s=96&v=4" width="100px;" alt="Emerson Willian"/>
        <br />
        <sub>
          <b>Emerson Willian</b>
        </sub>
       </a>
       <br />
       <a href="https://www.linkedin.com/in/emerson-willian-486914197/" title="Linkedin">@emersonwlw</a>
       <br />
       <a>💻</a>
    </td>
    <td align="center">
      <a href="http://github.com/rocketseat/">
        <img src="https://avatars.githubusercontent.com/u/28929274?s=200&v=4" width="100px;" alt="Logo da Rocketseat"/>
        <br />
        <sub>
          <b>Rocketseat</b>
        </sub>
       </a>
       <br />
       <a href="http://github.com/rocketseat/" title="Linkedin">@rocketseat</a>
       <br />
       <a>🚀</a>
    </td>
  </tr>
</table>
