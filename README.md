<p align="center">
  <img width="100%" src="/.github/thumb.png" />
</p>

<p align="center">
    <strong>Aplicativo mobile de gerenciamento de atividades físicas desenvolvido na trilha do ignite da Rocketseat.</strong>
</p>

<p align="center">
  <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/bandeirapk/ignite-gym">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/bandeirapk/ignite-gym">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/bandeirapk/ignite-gym?style=social">
</p>

<h4 align="center"> 
	🚧  Projeto concluído 🚀 🚧
</h4>

## 💻 Sobre o Projeto

O Ignite Gym é um aplicativo mobile de gerenciamento de atividades físicas desenvolvido na trilha do ignite da Rocketseat. O aplicativo permite que o usuário insira tarefas, altere sua imagem de perfil com o uso da câmera e altere o estado da tarefa, marcando as atividades feitas que são exibidas em um histórico de atividades.

<div align="center">
  <img src="./.github/app.gif" alt="gif da aplicação em execução" width="369px" height="659px">
</div>

<br>

## 🔨 Funcionalidades do projeto

- [x] Registrar exercícios
  - [x] Registra as atividades que são providas da própria aplicação
  - [x] Histórico das atividades realizadas que são vindas do async storage
- [x] Alterar perfil
  - [x] Mudar a imagem de perfil com imagens do dispositivo ou tirando uma foto
  - [x] Alterar senha
  - [x] Validação feita nos próprios inputs
  - [x] Refletidas em tempo real na interface
- [x] Criação de conta
  - [x] Login com email e senha
  - [x] Cadastro de conta com email, senha e nome
  - [x] Informações cadastradas no async storage enquanto o usuário está logado
- [x] Logout da conta
- [x] Token e Refresh Token

## ✔️ Tecnologias utilizadas

- `Expo`
- `React Native`
- `Typescript`
- `NodeJS 18.16.0`
- `NPM 9.5.1`
- `Async Storage`
- `React Navigation`
- `Native Base`
- `Hooks`
- `Contexts`
- `Axios`
- `SQLite`

## 🛠️ Instalação e uso

Você pode baixar o projeto e rodar em seu computador seguindo os passos abaixo:

[IgniteGym](https://github.com/bandeirapk/ignite-gym/archive/refs/heads/main.zip) - Baixar o projeto

```bash
# Clone este repositório
git clone https://github.com/bandeirapk/ignite-gym.git

# Configurações da API
cd api/
npm install

# Rode a API
npm run dev

# Acesse a pasta mobile do projeto
cd mobile/

# Instale as dependências
npm install

# Rode o projeto
npx expo start

# Deixe a API rodando e em seguida rode o projeto para poder ter acesso a todas as funcionalidades do projeto.

# Em seguida, abra o emulador ou conecte seu dispositivo e rode o projeto.
```

Feito com ❤️ por [Bandeira Magalhães](https://github.com/bandeirapk)
