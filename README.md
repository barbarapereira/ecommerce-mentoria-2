# Ecommerce

<a alt="Nx logo" href="https://nx.dev" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/nrwl/nx/master/images/nx-logo.png" width="45"></a>

✨ **Este workspace foi gerado por: [Nx, Smart Monorepos · Fast CI.](https://nx.dev)** ✨

## Introdução

Uma aplicação de Ecommerce é um sistema que permite a venda de produtos ou serviços pela internet. A especificação desse tipo de aplicação é fundamental para garantir que todas as funcionalidades necessárias estejam presentes e que a experiência do usuário seja satisfatória.

## Funcionalidades

### Catálogo de produtos

A aplicação precisa ser capaz de exibir os produtos disponíveis para venda, com informações detalhadas sobre cada um deles, como preço, imagem, descrição, entre outros. O catálogo deve ser facilmente navegável e permitir a busca e filtragem de produtos.

### Carrinho de compras

A aplicação deve permitir que o usuário adicione produtos ao seu carrinho de compras, que possa ser facilmente acessado e gerenciado. O carrinho deve exibir informações como quantidade, preço total e opções de pagamento.

### Processo de checkout

A aplicação deve permitir que o usuário finalize sua compra com facilidade, seguindo um processo de checkout simples e intuitivo. O processo de checkout deve incluir informações sobre o frete e opções de pagamento.

### Gerenciamento de pedidos

A aplicação deve permitir que o administrador gerencie os pedidos realizados pelos usuários, com informações detalhadas sobre cada um deles, como status, data de entrega e informações do cliente.

## Requisitos não funcionais

### Segurança

A aplicação deve garantir a segurança dos dados dos usuários e do sistema como um todo, utilizando técnicas de criptografia e proteção contra ataques de hackers.

### Performance

A aplicação deve ter um desempenho satisfatório, carregando rapidamente as páginas e processando as transações com agilidade.

### Usabilidade

A aplicação deve ser fácil de usar e intuitiva, com uma interface de usuário clara e bem organizada.

### Acessibilidade

A aplicação deve ser navegável através do teclado e possuir conteúdo inclusivo para todos os usuários

## Configurações recomendadas:
- Node V20 (utilizar o Node Version Manager - NVM)
- VSCode
- Extensões:
  - [Nx Console](https://marketplace.visualstudio.com/items?itemName=nrwl.angular-console)
  - [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  - [Angular Language Service](https://marketplace.visualstudio.com/items?itemName=Angular.ng-template)
  - [Jest Runner](https://marketplace.visualstudio.com/items?itemName=firsttris.vscode-jest-runner)
  - #### Opcionais
    - [Codeium](https://codeium.com/)
    - [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
    - [Auto Barrel](https://marketplace.visualstudio.com/items?itemName=mikehanson.auto-barrel)
    - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    - [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)

## Clonando o projeto
```
git clone https://github.com/barbarapereira/ecommerce-mentoria-2.git
cd ecommerce-mentoria-2
npm install
```

## Servir o projeto localmente
```
npm run start
```
OU
```
npx nx serve
```

O projeto será servido por padrão em http://localhost:4200/.

## Executar tarefas independentes

```
npx nx <NOME_DA_TAREFA> <NOME_DO_MODULO>
```

Exemplos:

```
npx nx test ecommerce
npx nx lint modules-layout
```

## Visualizar Dependency Graph

```
npx nx graph
```


## Executar tarefas somente do que foi afetado

```
npx nx affected:<NOME_DA_TAREFA>
```

Exemplos:

```
npx nx affected:test
npx nx affected:graph
```
