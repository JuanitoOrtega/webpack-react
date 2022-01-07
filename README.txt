# Instalamos React
npm install react react-dom -S

# Creamos el proyecto
npm init -y

# Instalamos las dependencias de babel
npm install @babel/core @babel/preset-env @babel/preset-react babel-loader -D

# Creamos en nuestra raiz el archivo .babelrc
{
    "presets": [
        "@babel/preset-env",
        "@babel/preset-react"
    ]
}

# Instalamos webpack-cli
npm install webpack webpack-cli webpack-dev-server -D

# Creamos nuestro archivo de configuración
webpack.config.js

# Instalamos dependencias para HTML
npm install html-loader html-webpack-plugin -D

# Editamos nuestro archivo package.json
"scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "webpack serve",
    "build": "webpack --mode production"
},

# CSS
npm install mini-css-extract-plugin css-loader style-loader sass sass-loader -D

# Optimizador
npm install css-minimizer-webpack-plugin terser-webpack-plugin clean-webpack-plugin -D