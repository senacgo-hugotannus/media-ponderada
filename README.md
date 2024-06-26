# EXERCÍCIO: Média Ponderada

Exemplo de como utilizar as linguagens html, css e javascript para criar uma
aplicação web, sem necessitar do uso de um framework.

## Instruções para **clonar** o Repositório

Em um terminal de comando, navegue até a pasta de sua preferência -- como por exemplo a pasta `~/Projetos/` -- e clone este projeto utilizando o comando:

```bash
# Para clonar o repositório usando HTTPS
git clone https://github.com/hugotannus/media-ponderada.git
```

... ou:

```bash
# Para clonar o repositório usando SSH
git clone git@github.com:hugotannus/media-ponderada.git
```

Em seguida, navegue até a pasta do repositório, remova a pasta `.git`, inicie um novo repositório...

```bash
cd media-ponderada

# Ao remover esta pasta, você estará removendo o histórico de alterações do exercício...
rm -rfv .git/

# ... para dar lugar à sua própria resolução do exercício.
git init
```

... e faça um primeiro *commit* no seu repositório local.

```bash
# Prepara todos os arquivos contidos no repositório
git add .

# Ao remover esta pasta, você estará removendo o histórico de alterações do exercício...
git commit -m "Estágio inicial do exercício."
```

Por fim, crie um novo repositório no [GitHub](https://github.com) (**sem adicionar** os arquivos `README.md` e `.gitignore`, e de preferência ***público***), e siga as instruções na tela à seguir para enviar os arquivos ao repositório recém criado na plataforma.

## Execução

A solução não requer instalação prévia, e pode ser executada:

- abrindo o arquivo `index.html` diretamente no navegador;
- criando uma instância local da aplicação com o [http-server](https://www.npmjs.com/package/http-server), ou;
- por meio do uso de extensões do VSCode, como o [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) ou o [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server).

## Testes

Os testes podem ser executados também sem nenhuma instalação prévia. Basta abrir o arquivo `index.html`, localizado no diretório `tests/`.

Caso tenha instanciado um servidor local para a aplicação (na porta `8080`, por exemplo), basta executar os testes pela URL `http://localhost:8080/tests/index.html`.

## Referências

### HTML

- [HTML: Living Standard - Named access on the Window object](https://html.spec.whatwg.org/multipage/nav-history-apis.html#named-access-on-the-window-object)
- [CSS Tricks - *Named Element IDs Can Be Referenced as JavaScript Globals*](https://css-tricks.com/named-element-ids-can-be-referenced-as-javascript-globals/)
- [Stack Overflow - *Do DOM tree elements with IDs become global properties?*](https://stackoverflow.com/questions/3434278/do-dom-tree-elements-with-ids-become-global-properties)

### JavaScript

- [JavaScript Guide - Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)

### Testing

- [Mocha - Simple, flexible, fun](https://mochajs.org/)
- [Chai Assertion Library - Installation](https://www.chaijs.com/guide/installation/#browser)
- [Chai Assertion Library - BDD](https://www.chaijs.com/api/bdd/#method_eql)

### Web App

- [MDN Web Docs - Web app manifests](https://developer.mozilla.org/en-US/docs/Web/Manifest)
- [Apiki - Web App Manifest para personalizar sua Progressive Web App](https://blog.apiki.com/web-app-manifest/)
- [Building a Mobile App using HTML, CSS, and JavaScript](https://medium.com/stackanatomy/building-a-mobile-app-using-html-css-and-javascript-b3a8fd37723d)
