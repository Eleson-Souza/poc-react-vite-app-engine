Essa é uma POC para realizar deploy de uma aplicação React com Vite simples no Google Cloud Platform __App Engine__

## Deploy

1. Clone o repositório: `git clone https://github.com/eleson-souza/poc-react-vite-app-engine.git`
2. Navegue até o diretório: `cd poc-react-vite-app-engine`
3. Instale as dependências: `npm install`
4. Gere a build da aplicação: `npm run build`
5. Crie uma pasta no shell do GCP e faça o upload apenas do app.yaml e dist para ela. O app.yml contém configurações de runtime e outras pertinentes e o dist é a build/estáticos da aplicação.
6. Após configurado o App Engine com o runtime Node.js, rode o seguinte comando na pasta criada: `gcloud app deploy`
7. Pronto, será retornado a URL para acesso à aplicação online :)
