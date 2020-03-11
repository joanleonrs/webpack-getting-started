**Install dependencies**

npm init

git init

npm i webpack --save-dev --save-exact

npm i webpack-cli --save-dev --save-exact


**Create a bundle file on dev mode**

npx webpack --entry ./index.js --output ./bundle.js --mode development


**Create a webpack config file**

touch webpack-config.js


**Manejo de Assets con Loaders**

npm i --save-dev --save-exact css-loader

npm i --save-dev --save-exact style-loader

**Añadir webpack-dev-server para contar con el live/reload automático**

npm i -D --save-exact webpack-dev-server

