# Projeto SPA (Single Page Application)

O foco dessa SPA tem o objetivo principal o aprendizado do Gulp para autimatizar várias tarefas de desenvolvimento

## Recursos

- **Gulp**: Utilizamos o Gulp para automatizar a criação da pasta de build, concatenar arquivos, minificar JS, HTML e SASS, e muito mais.
- **Servidor Web JS**: Criamos um servidor web JS com o Gulp para observar qualquer mudança no código de desenvolvimento.

## Como usar

1. **Instalação**: Primeiro, instale todas as dependências do projeto com `npm install`.
2. **Desenvolvimento**: Para iniciar o servidor de desenvolvimento, use `gulp`. Isso criará uma versão de produção do projeto, iniciará o servidor, observará as mudanças no código e executará todas as tarefas novamente, enviando para produção e recarregando o servidor automaticamente.

## Tarefas do Gulp

Aqui estão só algumas das tarefas do Gulp que serão executadas:

- `htmlmin()`: Usamos isso para minificar o HTML, retirando espaços em brancos, comentarios e renomeando variaveis, deixando tudo em uma unica linha.
- `sass()`: Usamos isso para compilar arquivos SASS em CSS.
- `concat()`: Usamos isso para concatenar vários arquivos.
- `babel()`: Usamos o babel para transformar JavaScript moderno em uma versão que possa ser rodada na maioria dos Browsers atuais.
- `uglify()`: Usamos isso para minificar o JavaScript, retirando espaços em brancos, comentarios e renomeando variaveis, deixando tudo em uma unica linha.
- `uglifycss()`: Usamos isso para minificar o CSS, retirando espaços em brancos, comentarios e renomeando variaveis, deixando tudo em uma unica linha.
- `gulp.src() e gulp.dest()`: Usamos isso para selecionar os arquivos de entrada e de saída para ás tarefas do gulp. 
- `gulp.series()`: Usamos isso para executar tarefas em série.
- `gulp.parallel()`: Usamos isso para executar tarefas em paralelo.
- `gulp.watch()`: Usamos isso para observar as mudanças nos arquivos e executar tarefas automaticamente.

## Licença

Este projeto está licenciado sob a licença MIT.
