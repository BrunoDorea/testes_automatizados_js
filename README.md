<h1 align="center">
  Testes Automatizados em JavaScript | Erick Wendel
</h1>

<h2 align="center">
  <img src="./assets/imagem.jpeg" width="250px">
</h2>

<p align="center">
  <a href="https://wakatime.com/badge/user/68660678-6b86-4b78-98df-f5f41a37e1bc/project/278902a3-108a-4ba0-a294-4059c2cc6acd"><img src="https://wakatime.com/badge/user/68660678-6b86-4b78-98df-f5f41a37e1bc/project/278902a3-108a-4ba0-a294-4059c2cc6acd.svg" alt="wakatime"></a>
</p>

<p align="center">
  <a href="#-projeto">🖥️ Projetos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">🚀 Tecnologias</a>
</p>

## 💻 Projeto

Projeto criado para a aula de Testes Automatizados em JavaScript com Erick Wendel

## 🚀 Tecnologias

<p align="center">
    <img src="https://img.shields.io/static/v1?style=for-the-badge&message=JavaScript&color=222222&logo=JavaScript&logoColor=F7DF1E&label=">
</p>

---

Você precisará usar o Node.js na versão 20 (ou superior) para executar os testes

```sh
node -v
# v20.5.0
```

## Rodando

Restaure as dependencias e execute o projeto:
```sh
npm ci --silent
npm start
```

Seu programa estará rodando em [http://localhost:3000](http://localhost:3000)

Depois que a API estiver rodando você pode executar o script que vai disparar requests, obter o token e exibir a resposta da API.

Para isso execute
```sh
./run-api-requests.sh
```
A resposta deve parecer-se com:

```sh
Token capturado: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjoiZXJpY2t3ZW5kZWwiLCJtZXNzYWdlIjoiaGV5IGR1dXVkZSEiLCJpYXQiOjE2OTE2OTM4MjF9.VmPc9yY4tTXYQaILbY6JXK8IrmKKK0Z4hveVgRUIV9Y

Resposta da rota privada: {"result":"Hey welcome!"}
```