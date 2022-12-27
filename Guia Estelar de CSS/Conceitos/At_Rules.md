### At Rules  

* Está relacionado ao comportamento do CSS
* começa com o sinal de `@` seguido do indentificador e valor   

## Exemplos comuns 

- @import serve para incluir um CSS externo.
- @media são regras condicionais para vários dispositivos.
- @font-face é para colocar fontes externas.
- @keyframes serve para as animations do CSS.

```css
@import "http://local.com./styles.css"

@media(min-width: 500px){
    /*rules here */
}

@font-face{
    /*rules here */
}

@keyframes name_of_animation{
    /*rules here */
}
```