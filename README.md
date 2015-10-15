# gulp-docs-pt

## Getting Started

#### 1. Instale o Gulp de maneira Global

```sh
$ npm install --global gulp
```

#### 2. Instale Gulp em sua pasta de dependências:

```sh
$ npm install --save-dev gulp
```

#### 3. Crie um arquivo `gulpfile.js` no diretório root de seu projeto:

```js
var gulp = require('gulp');

gulp.task('default', function() {
  // insira aqui a tarefa padrão a ser executada
});
```

#### 4. Execute o gulp:

```sh
$ gulp
```

A *task* padrão irá ser executada e não irá executar nada por enquanto.

Para executar uma tarefa individual, use `gulp <tarefa> <outratarefa>`.
To run individual tasks, use `gulp <task> <othertask>`.