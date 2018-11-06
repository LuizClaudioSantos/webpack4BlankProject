# webpack 4 configuration default

This is based in the article: "A tale of Webpack 4 and how to finally configure it in the right way" by Margarita Obraztsova @riittagirl on Instagram. 
it is a simple blank project to be used as a start point for webpack projects, it will provide you:

1. Transpile you JavaScript code with babel

2. CSS and JavaScript minification

3. CSS and JavaScript hash and preplacement in html code to avoid browsers cache problems

4. Polishment of CSS with PostCSS

5. Clean and fresh builds with in clean-webpack-plugin



```
mkdir webpack-4-tutorial
cd webpack-4-tutorial
npm init
npm install webpack webpack-cli --save-dev
npm install babel-core babel-loader babel-preset-env --save-dev
touch .babelrc
touch  webpack.config.js
npm install style-loader css-loader --save-dev
npm install mini-css-extract-plugin --save-dev
npm install html-webpack-plugin --save-dev
npm install postcss-loader --save-dev
npm i -D autoprefixer
npm install clean-webpack-plugin --save-dev
```

