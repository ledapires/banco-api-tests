# 📌 banco-api-tests

Este repositório contém uma suíte de **automação de testes de API REST** desenvolvida em **JavaScript**, utilizando as bibliotecas **Mocha**, **Chai**, **Supertest** e **Mochawesome**. O projeto realiza testes automatizados na API REST do repositório [banco-api](https://github.com/ledapires/banco-api).

## 🚀 Objetivo

Validar os endpoints da API REST de forma automatizada, contribuíndo que estejam funcionando corretamente e de acordo com os requisitos.

## ⚙️ Stack utilizada

* **Linguagem:** JavaScript (Node.js)
* **Framework de Testes:** [Mocha](https://mochajs.org/)
* **Biblioteca de Asserções:** [Chai](https://www.chaijs.com/)
* **Cliente HTTP:** [Supertest](https://github.com/ladjs/supertest)
* **Relatórios:** [Mochawesome](https://www.npmjs.com/package/mochawesome)

## 📁 Estrutura de diretórios

```
├── tests/           # Contém os testes automatizados
│   ├── login.test.js
│   ├── transferencia.test.js
├── mochawesome/     # Diretório gerado com os relatórios em HTML
├── node_modules/    # Dependências do projeto
├── .env             # Variáveis de ambiente (não versionado)
├── package.json     # Dependências e scripts do projeto
```

## 🔑 Formato do arquivo `.env`

Antes de rodaros testes, crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:

```
BASE_URL=http://localhost:3000
```

Substitua o valor pela URL base onde a API está hospedada.

## 🏃‍♀️ Como executar os testes

1️⃣ Instale as dependências:

```bash
npm install
```

2️⃣ Execute os testes:

```bash
npm test
```

3️⃣ Gere o relatório com o **Mochawesome**:

Após a execução, o Mochawesome cria o diretório `mochawesome/` com um relatório em HTML.

Para abrir o relatório, localize o arquivo `mochawesome-report/mochawesome.html` e abra-o em seu navegador.

## 📚 Documentação das dependências principais

* [Mocha](https://mochajs.org/)
* [Chai](https://www.chaijs.com/)
* [Supertest](https://github.com/ladjs/supertest)
* [Mochawesome](https://www.npmjs.com/package/mochawesome)

---

💡 **Autor:** [Leda Pires](https://github.com/ledapires)

Contribuições, sugestões e melhorias são bem-vindas! 🚀✨
