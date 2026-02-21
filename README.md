# Projeto Costs

O **Costs** é uma aplicação de gestão de projetos desenvolvida para ajudar no controlo de custos e serviços de diferentes empreendimentos. A aplicação permite criar projetos, definir orçamentos e gerir os serviços associados a cada um.

## 🚀 Funcionalidades

* **Criação de Projetos**: Definição de nome, orçamento e categoria do projeto.
* **Gestão de Serviços**: Adição e remoção de serviços com atualização automática do orçamento disponível.
* **Visualização de Projetos**: Lista completa de projetos com opções de edição e exclusão.
* **Controle de Orçamento**: Validação para garantir que o custo dos serviços não excede o orçamento do projeto.

## 🛠️ Tecnologias Utilizadas

* **React**: Biblioteca principal para a interface.
* **React Router Dom**: Gestão de rotas da aplicação.
* **JSON Server**: Utilizado para simular uma API REST de backend.
* **React Icons**: Biblioteca de ícones.
* **CSS Modules**: Estilização isolada por componente.
* **UUID**: Geração de IDs únicos para os serviços.

## 🏁 Como Executar o Projeto

### Pré-requisitos

* Node.js instalado.
* Gestor de pacotes npm.

### Instalação

1. Clone o repositório.
2. Instale as dependências:
```bash
npm install

```

### Execução

Para rodar a aplicação corretamente, precisa de iniciar tanto o frontend como o backend (simulado pelo JSON Server):

1. **Iniciar rota Backend**:

* [Backend](https://projeto-api-cost.onrender.com)
2. **Iniciar o Frontend**:
```bash
npm start

```


A aplicação abrirá em [http://localhost:3000](https://www.google.com/search?q=http://localhost:3000).

## 🌐 Web 

* Link do [Github Pages](https://hectorsalg.github.io/projeto-costs/)

## 📜 Scripts Disponíveis

* `npm start`: Inicia o servidor de desenvolvimento do React.
* `npm run backend`: Inicia o `json-server` para monitorizar o ficheiro `db.json` na porta 5000.
* `npm run build`: Cria a versão de produção na pasta `build`.
* `npm run deploy`: Realiza o deploy automático para o GitHub Pages.