README


  npm install -save-dev webpack 
  npm install -save-dev react


Vamos a agregar una librería de Hot Reload

  npm install --save-dev hjs-webpack

Instalamos dependencias:
  
  npm i --save autoprefixer babel babel-loader css-loader json-loader postcss-loader react react-hot-loader style-loader stylus-loader url-loader webpack-dev-server yeticss

Configuramos...




=== SCRIPT ========

<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Hello React!</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/react/0.13.3/react.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.23/browser.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
  </head>
  <body>
    <div id="example"></div>
    <script type="text/babel">
      React.render(
        <div>Hola Mundo!</div>,
        document.getElementById('example')
      );
      React.render(
        React.createElement("h1", null, "Hola Mundo!"), 
        document.getElementById('example')
      );
    </script>
  </body>
</html>


