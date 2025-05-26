###  Passos para Executar o Frontend_SistemaReembolso
    
#### 1. Abrindo um Novo Terminal
* Abra um novo terminal no VSCode para configurar o frontend.

#### 2. Configuração e Execução
* Navegue até a pasta do frontend:
  ```bash
  cd .\Frontend_SistemaReembolso\app
  ```
* Instale as dependências:
  ```bash
  npm install
  ```
* Configurar o arquivo de API
  * Acesse o arquivo [api.ts](./app/src/services/api.ts)
  * Substitua ```<ip-da-sua-maquina>``` pelo IP correto da sua máquina.

* Inicie o frontend com o comando:
  ```bash
  npx expo start
  ```
