# curso-webpack-react

Primero instalamos iniciamos npm e instalamos react y react-dom
```
npm init -y
npm install react react-dom
```

Instalamos babel
```
npm install @babel/core @babel/preset-env @babel/preset-react babel-loader -D
```

Creamos .babelrc y agregamos los presets:
```
{
  "presets": [
    "@babel/preset-env",
    "@babel/preset-react"
  ]
}
```

Instalamos las sigueintes librerías
```
npm install webpack webpack-cli webpack-dev-server -D
npm install html-loader html-webpack-plugin -D
```