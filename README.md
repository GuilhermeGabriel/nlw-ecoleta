<h1 align=center>
<img src="https://raw.githubusercontent.com/GuilhermeGabriel/nlw-ecoleta/master/Images/ecoleta.png" />
</h1>

<div align="center">

</div>

<h3 align="center">

Ecoleta é um projeto desenvolvido na semana Next Level Week (1.0) da rocketseat utilizando as tecnologias TypeScript, Node, React e React Native.

</h3>

![Banner]()

## OBJETIVO

O projeto tem como finalidade conectar empresas e/ou entidades que coletam resíduos (orgânicos e inorgânicos) às pessoas e/ou entidades que necessitam constantemente descartar esses resíduos. Solucionando o problema de descarte de lixo.

## TECNOLOGIAS


#### **Website** (React + TypeScript)

  - **React Router Dom**
  - **React Icons**
  - **Axios**
  - **Leaflet**
  - **React Leaflet**
  - **React Dropzone**

#### **Server** (NodeJS + TypeScript)

  - **Express**
  - **CORS**
  - **KnexJS**
  - **SQLite**
  - **ts-node**
  - **dotENV]**
  - **Multer**

#### **Mobile** (React Native + TypeScript)

  - **Expo**
  - **Expo Google Fonts**
  - **React Navigation**
  - **React Native Maps**
  - **Expo Constants**
  - **React Native SVG**
  - **Axios**
  - **Expo Location**
  - **Expo Mail Composer**

#### **Utilitários**

- Protótipo: **Figma**
- API: **IBGE API API de Municípios** 
- Maps: **Leaflet**
- Editor: **Visual Studio Code**
- Commit Conventional: **Commitlint**
- Teste de API: **Insomnia**
- Ícones: **Feather Icons**
- Fontes: **Ubuntu**


## COMO UTILIZAR

### Configurações Iniciais

Primeiro, você precisa ter o nodejs instalado na sua máquina. 

Após ter o Node instalado, instale as dependências do React e React Native (Expo) de forma global, utilizando os comandos:

```sh
# React:
$ npm install create-react-app -g

# Expo (React Native):
$ npm install -g expo-cli 
```

Você precisa modificar o arquivo `.env` e inserir as informações que condizem com o seu **host**:

Instale as dependências contidas nos arquivos `package.json`:

```sh
$ npm install

# ou
$ yarn
```

### Utilizando o Server

```sh
# Executando a aplicação em modo de desenvolvimento:
$ npm run dev

# Instanciando o banco de dados:
$ npm run knex:migrate

# Povoando o banco de dados (seeds):
$ npm run knex:seed
```

### Utilizando o Website

```sh
# Executando o website no modo de desenvolvimento:
$ npm run start
```

### Utilizando o Mobile

Instale o aplicativo Expo no seu celular.

```sh
# Executando o mobile no modo de desenvolvimento:
$ npm run start
```
