[ANGULAR__BADGE]: https://img.shields.io/badge/Angular-red?style=for-the-badge&logo=angular
[TYPESCRIPT__BADGE]: https://img.shields.io/badge/typescript-D4FAFF?style=for-the-badge&logo=typescript

<h1 align="center" style="font-weight: bold;">Projeto Buzzfeed 💻</h1>

![angular][ANGULAR__BADGE] ![typescript][TYPESCRIPT__BADGE]

<p align="center">
  <a href="#about">Sobre</a> • 
  <a href="#started">Começando</a> • 
  <a href="#Building">Building</a> • 
  <a href="#recursos">Recursos Adicionais</a>
</p>

<p align="center">
    <img src="/src/assets/imgs/image.png" alt="Image Example" width="400px">
</p>

<h2 id="started">📌 Sobre </h2>


Este projeto foi gerado usando [Angular CLI](https://github.com/angular/angular-cli) version 19.2.3. Tratasse de uma BuzzFeed com perguntas e respostas para descobrir de uma pessoa seria Héroi ou Vilão.  Feito no Bootcamp DecolaTech2025 da Avanade.

<h2 id="started">🚀 Começando</h2>

<h3>Pré-requisitos</h3>

Aqui você lista todos os pré-requisitos necessários para executar seu projeto. Por exemplo:

- Node 22.14.0
- Angular CLI 19.2.3
- Git 

<h3>Clonando</h3>

```bash
git clone https://github.com/MarcioCosta013/DecolaTech2025-Angular-BuzzFeed.git
```

<h3>Começando</h3>

No terminal, execute o seguente script:

```bash
cd buzzfeed
ng serve
```

Depois que o servidor estiver em execução, abra seu navegador e navegue até http://localhost:4200/ . O aplicativo será recarregado automaticamente sempre que você modificar qualquer um dos arquivos de origem.


<h3 id="Building"> Building </h3>

Para construir o projeto, execute:

```bash
ng build
```

Isso compilará seu projeto e armazenará os artefatos de build no `dist/` diretório. Por padrão, o build de produção otimiza seu aplicativo para desempenho e velocidade.


<h3 id="recursos">Recursos Adicionais</h3>

Caso o programa não consiga ler o arquivo `quizz_questions.json` verifique de no arquivo `tsconfig.json` se tem os seguintes comandos:

```bash
"resolveJsonModule": true, //Config para resolver e entender arquivos JSON
"allowSyntheticDefaultImports": true, //Config para entender e importar arquivos arquivos que não são TS, como um arquivo JSON
```

Para obter mais informações sobre como usar o Angular CLI, incluindo referências detalhadas de comandos, visite a página [Visão geral e referência de comandos do Angular CLI](https://angular.dev/tools/cli).
