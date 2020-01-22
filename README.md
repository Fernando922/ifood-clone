<p align="center">
  <img src="https://user-images.githubusercontent.com/54908803/72811670-dd7fca80-3c3e-11ea-98b1-1d993903f383.png" width="600" />
</p>

# Ferramentas

<p>Este projeto foi desenvolvido utilizando das seguintes tecnologias:</p>

- [React Native](https://facebook.github.io/react-native/)
- [React Navigation](https://reactnavigation.org/)
- [Expo](https://docs.expo.io/versions/latest/)
- [ESlint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Styled Components](https://styled-components.com/)
- [Axios](https://github.com/axios/axios)
- [Json Server](https://github.com/typicode/json-server)
- [NumeralJs](https://github.com/adamwdraper/Numeral-js)
- [VSCode](https://code.visualstudio.com/)
- [Material Icons](https://material.io/resources/icons/?style=baseline)

# Imagens do projeto

<p align="center">
  <img src="https://user-images.githubusercontent.com/54908803/72817515-aa423900-3c48-11ea-8a2b-a102a8eb39cd.png" />
</p>
<br/>
<p align="center">
  <img src="https://user-images.githubusercontent.com/54908803/72817571-c5ad4400-3c48-11ea-9d10-015db2c6576b.png" />
</p>
<br/>


<p align="center">
<img height="320"  src="https://user-images.githubusercontent.com/54908803/72848367-2eb1ad80-3c83-11ea-8ec4-e47bfd405ad6.gif">
<img height="320"  src="https://user-images.githubusercontent.com/54908803/72848515-88b27300-3c83-11ea-97d1-b4bca80dfc1a.gif">
<img height="320"  src="https://user-images.githubusercontent.com/54908803/72848544-98ca5280-3c83-11ea-9b90-d102e47356d7.gif">
<img height="320"  src="https://user-images.githubusercontent.com/54908803/72848570-a54eab00-3c83-11ea-9016-4cde03fe1364.gif">
</p>

# Como executar o projeto

<p>Executando o projeto:</p>

<p>
A aplicação foi desenvolvida através da utilização do Expo, e isso nos permite executar o projeto em nossos próprios aparelhos
móveis.
</p>

<p>Para execução do projeto, você precisará inicialmente ter em sua máquina um dos gerenciadores de pacote abaixo: </p>

- [NPM](https://www.npmjs.com/)
- [Yarn](https://yarnpkg.com/lang/en/) (recomendado)

<p>
  Inicialmente, você precisa instalar todas as dependências de funcionamento do projeto, para isso, com o terminal aberto na pasta do projeto, execute:
</p>


```
  yarn
  npm install
```


<p>
  Agora você precisa instalar globalmente o Json Server que vai servir como backend da aplicação, você pode instalar através
  de um dos seguintes comandos:
</p>

```
  npm install -g json-server
  yarn add -g json-server
```

<p>
  Agora você precisa baixar o projeto para sua máquina, você pode baixar o ZIP e extrair, ou caso tenha o GIT instalado na sua máquina
  pode clonar o projeto através do seguinte comando:
</p>

```
  git clone https://github.com/leoobarbosa2/ifood-clone.git
```

<p>
  Para iniciar o backend da aplicação, com o seu terminal aberto na pasta do projeto, execute: 
</p>

```
  json-server --host 192.168.11.16 -p 3333 -w server.json
```

<p>
  Observe que 192.168.11.16 é o IP da minha máquina, para que o backend funcione corretamente você precisará utilizar o IP da
  sua máquina para utilização.
</p>

<p>
  Realize a alteração desse IP, para o IP da sua máquina em src/services/api.js mantendo a porta :3333
</p>

<p>
  <img src="https://user-images.githubusercontent.com/54908803/72815451-6d287780-3c45-11ea-96f8-da0ba2338072.png" />
</p>

<p>
  Agora você precisa do aplicativo do EXPO instalado no seu dispositivo móvel, você pode encontrar por ele na Google Play ou App Store:
</p>

- [Expo Android](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=pt_BR)
- [Expo Ios](https://apps.apple.com/br/app/expo-client/id982107779)

<p>
  Continuando, execute o comando para iniciar a aplicação mobile com o expo:
</p>

```
  yarn start
  npm run start
```

<p>
  Após iniciar o projeto, o seu navegador irá abrir uma tela semelhante a essa, basta utilizar o seu leitor de QRCode
  que o Expo irá identificar e sugerir que abra no aplicativo, ou você pode escanear no próprio aplicativo do Expo
</p>

<p>
  <img src="https://user-images.githubusercontent.com/54908803/72814122-4b2df580-3c43-11ea-8860-291214206a31.png" />
</p>

<p>
  Depois disso é só aguardar o expo carregar o aplicativo!
</p>


<p>
  Testado no Android & IOS
</p>

<p>
  <img src="https://user-images.githubusercontent.com/54908803/72819629-56d1ea00-3c4c-11ea-8d6e-ca0d9a15d9c8.png" />
</p>

<p>
  Thank you :)
</p>

