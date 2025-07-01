# Codelab - TechBlog

### Links

- Site URL: [Site ativo](https://lucassalles-git.github.io/tech-blog/)

### Construído com

- Marcação semântica HTML5
- Propriedades personalizadas CSS
- Flexbox
- Grid CSS
- Fluxo de trabalho mobile-first
- [Sass](https://sass-lang.com/) - Para estilos

### O que eu aprendi

```scss
h3, p {
      width: clamp(18.188rem, 39.33vw, 21.1rem);
      display: -webkit-box; /*cria uma caixa com limite de linhas*/
      -webkit-line-clamp: 2; /*quantas linhas quero que mostre na caixa*/
      line-clamp: 2;
      -webkit-box-orient: vertical; /*faz a caixa crescer verticalmente*/

      overflow: hidden; /*esconde o que passar do limite de linhas*/
      text-overflow: ellipsis; /*coloca ... se o texto passar do limite*/
    }
```

## Autor

- GitHub - [lucassalles-git](https://github.com/lucassalles-git)

