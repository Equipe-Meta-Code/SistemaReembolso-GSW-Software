###  Passos para Executar o Backend_SistemaReembolso
    
#### 1. Abrindo um Novo Terminal
* Abra um novo terminal no VSCode para configurar o backend.

#### 2. Configuração e Execução
* Navegue até a pasta do backend:
  ```bash
  cd .\Backend_SistemaReembolso\
  ```
* Instale as dependências:
  ```bash
  npm install
  ```
* Configurar informações
  * Acesse o arquivo [.env.example](./.env.example)
  * Renomeie este arquivo para `.env`;
  * Preencha os campos com suas informações reais.

* Configurar informações do banco de dados MySQL
  * Acesse o arquivo [database.ts](./src/config/database.ts)
  * Adicione a senha do banco de dados
  
* Inicie o backend com o comando:
  ```bash
  npm run dev
  ```
