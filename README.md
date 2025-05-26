<h1 align="center"> Projeto API - 5  º Semestre </h1>

<p align="center">
     <a href ="#objetivo">Objetivo</a>  |
     <a href ="#requisitos">Requisitos</a>  |
     <a href ="#cronograma">Cronograma</a>  |
     <a href ="#tecnologias">Tecnologias</a>  |
     <a href ="#backlog">Backlog</a>  |
     <a href ="#mvp">MVP</a>  |
     <a href =#prototipo>Protótipo<a/> |
     <a href =#modelagem-bd>Modelagem BD<a/> |
     <a href =#instalação>Instalação<a/> |
     <a href =#videos-entregas>Vídeos<a/> |
     <a href ="#equipe">Equipe</a>  
   </p>

<span id="objetivo">
  
## 🎯 Objetivo
Desenvolver um aplicativo móvel para o lançamento de reembolso de despesas, garantindo praticidade e precisão no registro das informações.

<span id="requisitos">
  
## 📍 Requisitos funcionais
- Permitir o registro de despesas informando: 
    - Tipo de despesa
    - Data da despesa
    - Valor ou quantidade
- Permitir o anexo de comprovantes de despesa
- Permitir a inserção de uma descrição para a despesa
- Exibir alerta caso o valor da despesa esteja a cima do limite permitido
- Permitir o acompanhamento do status de aprovação das solicitações de reembolso
- Integrar com o sistema corporativo para fornecer e receber os seguintes dados:
    - Informações do solicitante (Nome, Centro de Custo, Projeto)
    - Detalhes da despesa (Data, Valor, Quantidade, Descrição, Anexo)

## 📍 Requisitos não-funcionais
- Manual do Usuário
- Documentação API - Application Programming Interface
- Modelagem de Banco de Dados

<span id="cronograma">  
   
## ⏳ Cronograma    

| Kick-off | 25 fev 2025
| --- | --- |
| Sprint 1 | 10/mar - 30/mar |
| Planning | 31/mar - 04/abr |
| Sprint 2 | 07/abr - 27/abr |
| Planning | 28/abr - 02/mai |
| Sprint 3 | 05/mai - 25/mai |
| Review   | 26/mai - 28/mai |

<span id="tecnologias">
  
## ⚙️ Ferramentas e Tecnologias Utilizadas

| ![TypeScript](https://img.shields.io/badge/-TypeScript-0D1117?style=for-the-badge&logo=typescript) | ![JavaScript](https://img.shields.io/badge/-JavaScript-0D1117?style=for-the-badge&logo=javascript) | ![REACT](https://img.shields.io/badge/-React-0D1117?style=for-the-badge&logo=react) | ![React Native](https://img.shields.io/badge/-React%20Native-0D1117?style=for-the-badge&logo=react) |
| --- | --- | --- | --- |
| ![Node.js](https://img.shields.io/badge/-Node.js-0D1117?style=for-the-badge&logo=node.js) | ![MongoDB](https://img.shields.io/badge/-MongoDB-0D1117?style=for-the-badge&logo=mongodb) | ![MySQL](https://img.shields.io/badge/-MySQL-0D1117?style=for-the-badge&logo=mysql) | ![Android Studio](https://img.shields.io/badge/-Android%20Studio-0D1117?style=for-the-badge&logo=android-studio) |
| ![Android](https://img.shields.io/badge/-Android-0D1117?style=for-the-badge&logo=android) | ![Expo](https://img.shields.io/badge/-Expo-0D1117?style=for-the-badge&logo=expo) | ![FIGMA](https://img.shields.io/badge/Figma-0D1117?style=for-the-badge&logo=figma) | ![JIRA](https://img.shields.io/badge/-JIRA-0D1117?style=for-the-badge&logo=jira) | 

<span id="backlog">
  
## 📊 Product Backlog

<details>
 <summary>User Story</summary>
   
| Rank | Prioridade | User Story | Estimativa(Horas) | Sprint | Requisito do Parceiro | Critério de aceitação |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | Alta | Eu, como funcionário, quero registrar minhas despesas relacionadas às minhas funções na empresa e solicitar reembolso, para garantir o reembolso adequado. | 12 | 1 | RF1 | Permitir o registro de despesas informando o tipo, a data, o valor ou quantidade e a qual projeto pertence. |
| 2 | Alta | Eu, como funcionário, quero registrar minhas despesas e solicitar reembolso de forma prática pelo meu dispositivo móvel, para facilitar o processo. | 8 | 1 | RF6 | Desenvolver uma aplicação para uma plataforma móvel, como smartphones ou tablets, garantindo praticidade. |
| 3 | Alta | Eu, como gestor, quero acessar as despesas dos projetos e funcionários, bem como suas solicitações de reembolso, para gerenciar os pedidos e monitorar os gastos da empresa. | 10 | 1 | RF6 | Integrar com o sistema corporativo para fornecer e receber informações do solicitante (Nome, Centro de Custo, Projeto) e detalhes da despesa (Data, Valor, Quantidade, Descrição, Anexo). |
| 4 | Alta | Eu, como usuário, quero criar e acessar minha conta no aplicativo, para cadastrar minhas despesas e solicitar os reembolsos. | 8 | 1 | RF6 | O usuário deve conseguir criar uma conta informando dados básicos e deve conseguir fazer login com as credenciais cadastradas. |
| 5 | Média | Eu, como usuário, quero anexar comprovantes e adicionar descrições às minhas despesas para facilitar a validação. | 13 | 3 | RF2, RF3 | O usuário deve conseguir anexar imagens de comprovantes (JPEG, PNG, PDF) e inserir uma descrição detalhada da despesa. O sistema deve garantir que as despesas com comprovantes anexados e descrições salvas fiquem disponíveis para análise. |
| 6 | Média | Eu, como funcionário, quero visualizar o status de aprovação das minhas solicitações de reembolso, para acompanhar o andamento do processo. | 10 | 2 | RF5 | Permitir o acompanhamento do status de aprovação das solicitações de reembolso. |
| 7 | Média | Eu, como usuário, quero visualizar os limites de reembolso para cada categoria de despesa nos projetos, garantindo um melhor controle financeiro. | 8 | 2 | RF4 | O sistema deve exibir o limite de reembolso disponível para cada projeto e o usuário deve conseguir visualizar o valor total do limite e quanto já foi utilizado. |
| 8 | Média | Eu, como usuário, quero que o sistema calcule automaticamente o valor total das minhas despesas com base nos valores e quantidades informados, para visualizar com precisão os meus gastos. | 6 | 2 | RF1, RF4, RF6 | O sistema deve calcular automaticamente o total das despesas por solicitante e por projeto, considerando os valores e quantidades de cada item no registro de despesas. O total deve ser atualizado em tempo real conforme o usuário altera os valores ou quantidades. |
| 9 | Média | Eu, como usuário, quero que meus dados sejam autenticados ao acessar minha conta, garantindo segurança no aplicativo. | 10 | 3 | RF6 | Exigir autenticação de usuário para acessar a conta. Os dados de login devem ser validados antes de permitir o acesso ao aplicativo. |
| 10 | Média | Eu, como usuário, quero um aplicativo com interface amigável, para melhorar a experiência de uso. | 20 | 2 | RF4 | O aplicativo deve possuir uma interface intuitiva. Os elementos visuais devem seguir um design padronizado, com botões, ícones e cores que facilitem a usabilidade. O sistema deve fornecer confirmações e alertas para ações do usuário. |
| 11 | Baixa | Eu, como usuário, quero acessar o histórico das minhas solicitações de reembolso para acompanhar o status e analisar registros anteriores. | 9 | 1 | RF1 | O usuário deve conseguir visualizar uma lista com todas as solicitações de reembolso feitas e as solicitações devem exibir informações relevantes, como data, valor, status (pendente, aprovado, recusado) e descrição. |
| 12 | Baixa | Eu, como usuário, quero ser alertado quando minhas despesas ultrapassarem o limite da empresa, para evitar solicitações fora das regras. | 6 | 2 | RF4 | Exibir o valor limite definido para cada categoria de despesa e alertar o usuário de forma clara e intuitiva caso o valor da despesa ultrapasse o limite estabelecido. |
| 13 | Baixa | Eu, como usuário, quero ter acesso ao manual do usuário, para entender o funcionamento do aplicativo. | 9 | 3 | RNF1 | Destinado ao usuário final, explica como utilizar um sistema ou produto (Apresentação do sistema; instalação ou acesso; interface e funcionalidades; passo a passo de uso; perguntas frequentes e resolução de erros comuns; contato e suporte.). |

</details>

<p align="left">
  <img src="https://github.com/user-attachments/assets/cb70734c-c75b-4044-ad2e-598b14b49708" width="390"/>
  <img src="https://github.com/user-attachments/assets/444dfd41-c4e4-4f8a-951c-10af01183e53" width="390"/>
</p>


<span id="mvp">
  
## MVP - Mínimo Produto Viável
<div style="display: flex;">
  <img src="https://github.com/user-attachments/assets/4d63b371-73cc-4386-9fac-bf6efc369dc9" width="390">
</div>


<span id="prototipo">
     
## Protótipo Figma
📲 [Clique aqui](https://www.figma.com/design/ggjMhKZe8I1IaFGjzGx4V0/APP---RefundGo?node-id=0-1&p=f&t=VD4qXCwoVmp0CVLB-0) para acessar o protótipo! *(Segure `Ctrl` e clique para abrir em nova guia)*

<span id="modelagem-bd">
     
## Modelagem de Banco de Dados
<img src="https://github.com/user-attachments/assets/ccc12f4b-1799-42d0-9bc5-6014579a24f3" width="450"/>


<span id="instalação">
     
## 📥 Guia de Instalação  
  * Acesse para ver o passo a passo do [Frontend](./Guia-de-Instalação/frontend-readme.md)
  * Acesse para ver o passo a passo do [Backend](./Guia-de-Instalação/backend-readme.md)
  * Acesse para ver o passo a passo do [Sistema Corporativo Web](./Guia-de-Instalação/sistema-web-readme.md)

<span id="videos-entregas">
     
## 🎬 Vídeos de Entrega

<details>
     
<summary>Sprint 1</summary>

https://github.com/user-attachments/assets/fd2b5b8f-8bc0-4117-948f-7c332a74f33a

</details>


<details>
     
<summary>Sprint 2</summary>

https://github.com/user-attachments/assets/95df7846-001a-4841-87b1-d7bc0b4af24e

</details>


<span id="equipe">
     
## 👥 Equipe

|Nome|Função|GitHub|
| -------- |-------- |-------- |
|**Ana Luisa Andrade**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/LuisaAndrade28)|
|**Dianne Faria**|Developer Team| [![](https://bit.ly/3f9Xo0P)](https://github.com/DianneFaria)|
|**Gustavo Sena**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/gustavosenamp)|
|**Julia Gonzalez**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/juliagonzalezmoreira)|
|**Maria Luiza Guedes**|Product Owner|[![](https://bit.ly/3f9Xo0P)](https://github.com/mluizaguedes)|
|**Pedro Henrique Ribeiro**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/pedrohenribeiro)|
|**Sofia Lessa**|Scrum Master|[![](https://bit.ly/3f9Xo0P)](https://github.com/sofialessaa)|
