# React via CDNJS

Existe duas formas de trabalhar com react JSX, instalando os requisitos e rodando na própria máquina, ou adicionando [CDNs](https://www.hostinger.com.br/tutoriais/o-que-e-cdn?ppc_campaign=google_search_generic_hosting_all&bidkw=defaultkeyword&lo=9100789&gad_source=1&gclid=Cj0KCQjwncWvBhD_ARIsAEb2HW8tIpynv76cdYFs2SOYSYXKiGojL2bS6MUo7Ige7MP6nqG3wI-0lKQaAjvUEALw_wcB). O uso das CDNs facilita a agilidade, criação e espaço de armazenamento na máquina, pois o projeto não fica no computador.

CDNs utilizados no projeto Link e CDNs:

[react](https://cdnjs.com/libraries/react):

```text
<script src="https://cdnjs.cloudflare.com/ajax/libs/react/18.2.0/umd/react.production.min.js" integrity="sha512-8Q6Y9XnTbOE+JNvjBQwJ2H8S+UV4uA6hiRykhdtIyDYZ2TprdNmWOUaKdGzOhyr4dCyk287OejbPvwl7lrfqrQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```

[react-dom](https://cdnjs.com/libraries/react-dom): Tecnologia do React que serve para permitir a conexão do nosso código JavaScript com o DOM a árvore de elementos do HTML, que se refere a tudo que vai mostrar na nossa tela.

```text
<script src="https://cdnjs.cloudflare.com/ajax/libs/react-dom/18.2.0/umd/react-dom.production.min.js" integrity="sha512-MOCpqoRoisCTwJ8vQQiciZv0qcpROCidek3GTFS6KTk2+y7munJIlKCVkFCYY+p3ErYFXCjmFjnfTTRSC1OHWQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```

[babel-standalone](https://cdnjs.com/libraries/babel-standalone): O Babel é uma **ferramenta de compilação de códigos JavaScript** que podem estar em uma versão mais moderna, mas que o navegador não a suporte. Ele faz essa compilação, como se fosse uma tradução, para conseguirmos acessar aplicações mais novas em qualquer navegador.

```text
<script src="https://cdnjs.cloudflare.com/ajax/libs/babel-standalone/7.24.0/babel.min.js" integrity="sha512-2nvFgDDkDQZAO7x0iuupGiKpK+/qm7+bjzIEZBCn3o7v60+ZaPoe5x4sb21xahHfI7RCC9emLVY1k4kvap9RyQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
```

## Sobre o Babel

O Babel é um compilador JavaScript, ou seja, um programa que lê o seu código fonte e gera um novo código como resultado. No CodeConnect estamos usando especificamente a versão babel-standalone, uma versão que pode ser usada em ambientes que não são o Node.js, como navegadores e outros sistemas.

```javascript

```

 **Qual é o argumento que deve ser passado para o método `ReactDOM.createRoot`?**

Resp.: Um elemento que representa onde o seu aplicativo será renderizado.

"Você pode obter esse elemento usando o método document.getElementById, que recebe o id do elemento e retorna o elemento correspondente. Por exemplo, se você tem um elemento HTML com o id root, você pode passar document.getElementById('root') como argumento para o método ReactDOM.createRoot"

**createRoot**: Cria uma raiz do React, que é um ponto de entrada para o seu aplicativo React no DOM.

**render**: renderiza um elemento React no DOM, usando a raiz do React criada pelo método createRoot.
