###  Passos para Executar o Web_SistemaReembolso
    
#### 1. Abrindo um Novo Terminal
* Abra um novo terminal no VSCode para configurar o projeto web.

#### 2. Configuração e Execução
* Navegue até a pasta web:
  ```bash
  cd .\Web_SistemaReembolso\web
  ```
* Instale as dependências:
  ```bash
  npm install
  ```

* Configurar o arquivo de API
  * Acesse o arquivo [api.ts](./web/src/services/api.ts)
  * Substitua ```<ip-da-sua-maquina>``` pelo IP correto da sua máquina.

* Inicie o projeto web com o comando:
  ```bash
  npx expo start --web
  ```
