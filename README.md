
```bash
mkdir webpack-react-tutorial && cd $_
mkdir -p src
yarn init .

#change yarn source
yarn config get registry
yarn config set registry 'https://registry.npm.taobao.org'

#add webpack support
yarn add webpack --dev
yarn add webpack-cli --dev

#add babel support
yarn add @babel/core babel-loader @babel/preset-env @babel/preset-react --dev

yarn add react react-dom --dev

mkdir -p src/js/components/{container,presentational}

yarn add prop-types --dev

```