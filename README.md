<h1 align=center>
<img src="linkimage" />
</h1>

<div align="center">

![BADGE_LICENSE] ![BADGE_NODE_VERSION] ![BADGE_NPM_VERSION] ![BADGE_WEB_REACT] ![BADGE_MOBILE_REACT_NATIVE] ![BADGE_SERVER_NODEJS] ![BADGE_TYPESCRIPT] ![BADGE_OPEN_SOURCE] ![BADGE_OPEN_ISSUES] ![BADGE_CLOSED_ISSUES] ![BADGE_STARS] ![BADGE_FORKS]

</div>

<h3 align="center">

Ecoleta é um projeto desenvolvido na semana Next Level Week (1.0) da rocketseat utilizando as tecnologias TypeScript, Node, React e React Native.

</h3>

![Banner]()

## OBJETIVO

O projeto tem como finalidade conectar empresas e/ou entidades que coletam resíduos (orgânicos e inorgânicos) às pessoas e/ou entidades que necessitam constantemente descartar esses resíduos. Solucionando o problema de descarte de lixo.

## TECNOLOGIAS


#### **Website** ([React][react] + [TypeScript][typescript])

  - **[React Router Dom][react_router_dom]**
  - **[React Icons][react_icons]**
  - **[Axios][axios]**
  - **[Leaflet][leaflet]**
  - **[React Leaflet][react_leaflet]**
  - **[React Dropzone][react_dropzone]**

#### **Server** ([NodeJS][node] + [TypeScript][typescript])

  - **[Express][express]**
  - **[CORS][cors]**
  - **[KnexJS][knex]**
  - **[SQLite][sqlite3]**
  - **[ts-node][tsnode]**
  - **[dotENV][dotenv]**
  - **[Multer][multer]**
  - **[Celebrate][celebrate]**
  - **[Joi][joi]**

#### **Mobile** ([React Native][react_native] + [TypeScript][typescript])

  - **[Expo][expo]**
  - **[Expo Google Fonts][expo_google_fonts]**
  - **[React Navigation][react_navigation]**
  - **[React Native Maps][react_native_maps]**
  - **[Expo Constants][expo_constants]**
  - **[React Native SVG][react_native_svg]**
  - **[Axios][axios]**
  - **[Expo Location][expo_location]**
  - **[Expo Mail Composer][expo_mail_composer]**

#### **Utilitários**

- Protótipo: **[Figma](https://www.figma.com/)** &rarr; **<kbd>[Protótipo (Ecoleta)](https://www.figma.com/file/1SxgOMojOB2zYT0Mdk28lB/Ecoleta)</kbd>**
- API: **[IBGE API][ibge_api]** &rarr; **<kbd>[API de UFs][ibge_api_ufs]</kbd>**, **<kbd>[API de Municípios][ibge_api_municipios]</kbd>** 
- Maps: **[Leaflet][leaflet]**
- Editor: **[Visual Studio Code][vscode]** &rarr; Extensions: **<kbd>[SQLite][vscode_sqlite_extension]</kbd>**
- Commit Conventional: **[Commitlint][commitlint]**
- Teste de API: **[Insomnia][insomnia]**
- Ícones: **[Feather Icons][feather_icons]**, **[Font Awesome][font_awesome]**
- Fontes: **[Ubuntu][font_ubuntu]**, **[Roboto][font_roboto]**


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