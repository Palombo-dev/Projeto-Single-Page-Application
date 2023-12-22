# Projeto SPA (Single Page Application)

O foco dessa aplicação de página única (SPA) tem o objetivo principal o aprendizado do Gulp para autimatizar várias tarefas de desenvolvimento

## Recursos

- **Gulp**: Utilizamos o Gulp para automatizar a criação da pasta de build, concatenar arquivos, minificar JS, HTML e SASS, e muito mais.
- **Servidor Web JS**: Criamos um servidor web JS com o Gulp para observar qualquer mudança no código de desenvolvimento.

## Como usar

1. **Instalação**: Primeiro, instale todas as dependências do projeto com `npm install`.
2. **Desenvolvimento**: Para iniciar o servidor de desenvolvimento, use `gulp`. Isso iniciará o servidor, observará as mudanças no código e executará todas as tarefas novamente, enviando para produção e recarregando o servidor automaticamente.
3. **Build**: Para criar uma versão de produção do seu projeto, use `gulp build`. Isso criará uma pasta de build com todos os seus códigos de desenvolvimento prontos para produção.

## Tarefas do Gulp

Aqui estão algumas das tarefas do Gulp que utilizamos:

- `gulp.series()`: Usamos isso para executar tarefas em série.
- `gulp.parallel()`: Usamos isso para executar tarefas em paralelo.
- `gulp.watch()`: Usamos isso para observar as mudanças nos arquivos e executar tarefas automaticamente.

## Contribuição

Contribuições são bem-vindas! Por favor, leia o guia de contribuição antes de fazer qualquer alteração.

## Licença

Este projeto está licenciado sob a licença MIT.
