# 🤖 Robô Educa 
### 🤓 Aprenda Programação e Inteligência Artificial construindo seu próprio robô.

<hr>

## Módulo FrontEnd básico para login na plataforma

Este módulo FrontEND do projeto tem a função de identificar e logar o usuário na plataforma, permitindo que a iteração com o mesmo seja personalizada conforme seu perfil e histórico. 

### Tecnologias utilizadas

- ![Node.js Version](https://img.shields.io/badge/Node.js-v20-green)
- ![HTML](https://img.shields.io/badge/HTML-5-orange)

### Como Usar 

1. Clone o repositório.
```
$ git clone https://github.com/Robo-Educa/front_basic.git 
```
2. Instale as dependências.
```
$ cd front-basic
$ npm install
```
3. Execute o projeto.
```
$ node index.js
```
4. Teste no Navegador
```
http://localhost:8080/
```

### Como publicar no Google Cloud Run
* Na console do GCP Cloud SDK Shell :
```
$ cd front-basic
$ gcloud components update
$ gcloud init
$ gcloud run deploy --source .
```

### Como criar um projeto em NODE.js do zero - Passo a passo (Windows): 

* Crie uma pasta para seu projeto e em seguida mova-se para dentro dela.
```
$ md\nome_do_projeto
$ cd\nome_do_projeto
```

* Inicie um projeto Node.JS informando nome, versão, autor, etc:
```
$ npm init
```

* Instale eventuais bibliotecas/dependências relativas ao projeto. Exemplo:
```
$ npm install express
```

* Criar arquivo básico do projeto (Ex.: index.js)

* Criar arquivo .ENV contendo variáveis de ambiente do sistema (se necessário)

* Criar pasta `/public` contendo arquivos estáticos do projeto. Ex: Html, CSS, imagens, etc.

* Para executar sua aplicação digite no terminal:
```
$ node index.js
```
* Em seguida digite no seu navegador:
```
http://localhost:3000/
```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request.

## Licença

Este projeto está licenciado sob a [Apache 2.0 License](LICENSE). Observe também os Termos de Serviço.

