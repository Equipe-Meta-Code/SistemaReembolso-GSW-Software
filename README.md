<h1 align="center"> Projeto API - 5  º Semestre </h1>

<p align="center">
     <a href ="#objetivo">Objetivo</a>  |
     <a href ="#requisitos">Requisitos</a>  |
     <a href ="#tecnologias">Tecnologias</a>  |
     <a href ="#backlog">Backlog</a>  |
      <a href ="#mvp">MVP</a>  |
     <a href ="#equipe">Equipe</a>  |
     <a href =#prototipo>Protótipo<a/> |
     <a href =#videos-entregas>Vídeos<a/>
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

<span id="tecnologias">
  
## ⚙️ Ferramentas e Tecnologias Utilizadas

| ![TypeScript](https://img.shields.io/badge/-TypeScript-0D1117?style=for-the-badge&logo=typescript) | ![JavaScript](https://img.shields.io/badge/-JavaScript-0D1117?style=for-the-badge&logo=javascript) | ![REACT](https://img.shields.io/badge/-React-0D1117?style=for-the-badge&logo=react) | ![React Native](https://img.shields.io/badge/-React%20Native-0D1117?style=for-the-badge&logo=react) |
| --- | --- | --- | --- |
| ![Android](https://img.shields.io/badge/-Android-0D1117?style=for-the-badge&logo=android) | ![Expo](https://img.shields.io/badge/-Expo-0D1117?style=for-the-badge&logo=expo) | ![MySQL](https://img.shields.io/badge/-MySQL-0D1117?style=for-the-badge&logo=mysql) | ![MongoDB](https://img.shields.io/badge/-MongoDB-0D1117?style=for-the-badge&logo=mongodb) |
| ![VS Code](https://img.shields.io/badge/-VS%20Code-0D1117?style=for-the-badge&logo=visualstudiocode) | ![FIGMA](https://img.shields.io/badge/Figma-0D1117?style=for-the-badge&logo=figma) | ![JIRA](https://img.shields.io/badge/-JIRA-0D1117?style=for-the-badge&logo=jira) | ![Microsoft](https://img.shields.io/badge/Microsoft_Office-0D1117?style=for-the-badge&logo=microsoft-office) | 

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
| 5 | Média | Eu, como usuário, quero anexar comprovantes e adicionar descrições às minhas despesas para facilitar a validação. | 13 | 2 | RF2, RF3 | O usuário deve conseguir anexar imagens de comprovantes (JPEG, PNG, PDF) e inserir uma descrição detalhada da despesa. O sistema deve garantir que as despesas com comprovantes anexados e descrições salvas fiquem disponíveis para análise. |
| 6 | Média | Eu, como funcionário, quero visualizar o status de aprovação das minhas solicitações de reembolso, para acompanhar o andamento do processo. | 10 | 2 | RF5 | Permitir o acompanhamento do status de aprovação das solicitações de reembolso. |
| 7 | Média | Eu, como usuário, quero visualizar os limites de reembolso para cada categoria de despesa nos projetos, garantindo um melhor controle financeiro. | 8 | 2 | RF4 | O sistema deve exibir o limite de reembolso disponível para cada projeto e o usuário deve conseguir visualizar o valor total do limite e quanto já foi utilizado. |
| 8 | Média | Eu, como usuário, quero que o sistema calcule automaticamente o valor total das minhas despesas com base nos valores e quantidades informados, para visualizar com precisão os meus gastos. | 6 | 2 | RF1, RF4, RF6 | O sistema deve calcular automaticamente o total das despesas por solicitante e por projeto, considerando os valores e quantidades de cada item no registro de despesas. O total deve ser atualizado em tempo real conforme o usuário altera os valores ou quantidades. |
| 9 | Média | Eu, como usuário, quero que meus dados sejam autenticados ao acessar minha conta, garantindo segurança no aplicativo. | 10 | 3 | RF6 | Exigir autenticação de usuário para acessar a conta. Os dados de login devem ser validados antes de permitir o acesso ao aplicativo. |
| 10 | Média | Eu, como usuário, quero um aplicativo com interface amigável, para melhorar a experiência de uso. | 20 | 2 | RF4 | O aplicativo deve possuir uma interface intuitiva. Os elementos visuais devem seguir um design padronizado, com botões, ícones e cores que facilitem a usabilidade. O sistema deve fornecer confirmações e alertas para ações do usuário. |
| 11 | Baixa | Eu, como usuário, quero acessar o histórico das minhas solicitações de reembolso para acompanhar o status e analisar registros anteriores. | 9 | 1 | RF1 | O usuário deve conseguir visualizar uma lista com todas as solicitações de reembolso feitas e as solicitações devem exibir informações relevantes, como data, valor, status (pendente, aprovado, recusado) e descrição. |
| 12 | Baixa | Eu, como usuário, quero ser alertado quando minhas despesas ultrapassarem o limite da empresa, para evitar solicitações fora das regras. | 6 | 2 | RF4 | Exibir o valor limite definido para cada categoria de despesa e alertar o usuário de forma clara e intuitiva caso o valor da despesa ultrapasse o limite estabelecido. |
| 13 | Baixa | Eu, como usuário, quero ter acesso ao manual do usuário, para entender o funcionamento do aplicativo. | 9 | 3 | RNF1 | Destinado ao usuário final, explica como utilizar um sistema ou produto (Apresentação do sistema; instalação ou acesso; interface e funcionalidades; passo a passo de uso; perguntas frequentes e resolução de erros comuns; contato e suporte.). |

</details>

<div style="display: flex;">
  <img src="https://github.com/user-attachments/assets/3b29d1eb-0e25-4469-a901-6769ca6238f6" width="450"/>
  <img src="https://github.com/user-attachments/assets/87acea7f-00a7-43dc-aa09-25d32aa2f576" width="450"/>
</div>

<span id="mvp">
  
## MVP - Mínimo Produto Viável
<div style="display: flex;">
  <img src="https://github.com/user-attachments/assets/f4e5c81a-07e6-44e9-b172-cc7efe9c8aae" width="450">
</div>


<span id="prototipo">
     
## 📲 Protótipo Figma
* [Clique aqui](https://www.figma.com/design/ggjMhKZe8I1IaFGjzGx4V0/APP---RefundGo?node-id=0-1&p=f&t=VD4qXCwoVmp0CVLB-0) para acessar o protótipo!

<!-- 
<span id="modelagem-bd">
## 📂 Modelagem de Banco de Dados



<span id="instalação">
## 📥 Guia de Instalação -->
<span id="videos-entregas">
     
## 📽️ Vídeos de Entrega das Sprints

<details >
     
<summary>Sprint 1</summary>

https://github.com/user-attachments/assets/fd2b5b8f-8bc0-4117-948f-7c332a74f33a

</details>

<span id="equipe">

## 👥 Equipe

<br>

|Nome|Função|GitHub|
| -------- |-------- |-------- |
|**Ana Luisa Andrade**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/LuisaAndrade28)|
|**Dianne Faria**|Developer Team| [![](https://bit.ly/3f9Xo0P)](https://github.com/DianneFaria)|
|**Gustavo Sena**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/gustavosenamp)|
|**Julia Gonzalez**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/juliagonzalezmoreira)|
|**Maria Luiza Guedes**|Product Owner|[![](https://bit.ly/3f9Xo0P)](https://github.com/mluizaguedes)|
|**Pedro Henrique Ribeiro**|Developer Team|[![](https://bit.ly/3f9Xo0P)](https://github.com/pedrohenribeiro)|
|**Sofia Lessa**|Scrum Master|[![](https://bit.ly/3f9Xo0P)](https://github.com/sofialessaa)|
