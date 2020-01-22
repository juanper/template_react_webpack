# template_react_webpack
Template mínimo para aplicação web com React, Babel e Webpack

## requisito
```
nodejs >= 12.4
```

### para compilar e baixar pacotes de dependências
```
npm install
```
### para debug do projeto (acesso http://localhost:8080)
```
npm run dev-server
```
### para deploy (saida em /public)
```
npm run build 
```

### para deploy debug (saida em /public)
```
npm run start
```

## iniciar projeto um projeto novo do zero
```
npm init -y
npm i react react-dom
```

### uso de webpack
```
npm i -D webpack webpack-cli webpack-dev-server
npm i -D @babel/core @babel/preset-env @babel/preset-react babel-loader
npm i -D html-webpack-plugin html-loader file-loader svg-url-loader css-loader style-loader
```
