# Adicionando um Estilo ao nosso HTML

* Inline
    ```css
      <h1 style="color: blue;">Título
	    <strong style="color: red;">alo</strong>
      </h1>
    ´´´
* No Head do HTML
    ```css
     <!DOCTYPE html>
         <html lang="en">
            <head>
                <meta charset="UTF-8">
                <meta http-equiv="X-UA-Compatible" content="IE=edge">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <title>Document</title>
	            <style>
	                h1 {
			            color: blue;
			        }
	                strong {
			                color: red;
			        }
	            </style>
            </head>
        ´´´
    * Com o Link geralmente no Head do HTML
    ```css
    <link rel="stylesheet" href="style.css">
    ´´´
    *  @import
        - Usada dentro do CSS
        ```css
             @import 'https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap'
        ´´´
        - Não é recomendado seu uso, pois leva um pouco mais de tempo do que através da tag link, fazendo a página ficar menos responsiva, demorando mais para o carregamento da mesma.

