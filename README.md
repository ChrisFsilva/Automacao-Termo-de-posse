<h1 align="center">Termo de posse</h1>			
<br>
<h4 align="center"> 🚀 Concluído 🚀 </h4>
	

Tabela de conteúdos
=================
<!--ts-->
   * [Sobre o projeto](#-sobre-o-projeto)
   * [Layout](#-layout)
   * [Como executar o projeto](#-como-executar-o-projeto)
     * [Pré-requisitos](#pré-requisitos)
     * [Funcionalidades](#Funcionalidades)
   * [Tecnologias](#-tecnologias)
   * [Autor](#-autor)
   * [Licença](#-licença)
<!--te-->


## 💻 Sobre o projeto

Descrição:
Este projeto visa automatizar a emissão de termos de posse de equipamentos de TI para colaboradores da empresa usando Power Automate. O fluxo automatizado gerencia tarefas como a geração dos documentos de posse, envio para assinatura via Microsoft Approval e armazenamento dos termos assinados. O modelo do documento é criado usando HTML e CSS para garantir um layout profissional e personalizável.

Tecnologias Utilizadas:
 -Power Automate: Para a criação e gerenciamento dos fluxos automatizados.
 -Microsoft 365: Integração com Outlook, SharePoint e outros serviços da Microsoft.
 -SharePoint: Armazenamento e gerenciamento dos termos de posse.
 -Microsoft Approval: Gerenciamento do processo de assinatura dos termos de posse.
 -HTML e CSS: Criação do modelo de documento.
 
---

## 🎨 Layout

O layout da aplicação está disponível no LinkedIn:

O layout da aplicação está disponível no pinteres:
<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="Termo de posse By Christopher Silva" title="#Posse-automacao" src="https://i.pinimg.com/1200x/c4/75/c8/c475c8aa0c4215ebfde64d9837f2f0da.jpg" />
</p>

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="Termo de posse By Christopher Silva" title="#Posse-automacao" src="https://i.pinimg.com/1200x/81/ae/a3/81aea39d3eec4d0747feb14111d1a674.jpg" />
</p>
Componentes Principais:
 -GenerateTermsFlow: Fluxo para criação dos termos de posse de equipamentos de TI.
 -SendForApprovalFlow: Fluxo para envio dos termos de posse para assinatura via Microsoft Approval.
 -StoreSignedTermsFlow: Fluxo para armazenamento dos termos de posse assinados no SharePoint.
 -NotifyStatusFlow: Fluxo para envio de notificações por e-mail sobre o status da assinatura.
 -term_template.html: Modelo de documento em HTML.
 -term_style.css: Estilos do documento em CSS.
 -TermsLibrary: Biblioteca de documentos no SharePoint para armazenamento dos termos de posse.

---

## 🚀 Como executar o projeto

### Pré-requisitos

 -Conta Microsoft 365 com permissões de administrador.
 -Licença Power Automate.
 -Configuração do SharePoint.
 -Configuração do Microsoft Approval.

Instalação:
 -Certifique-se de que sua conta Microsoft 365 tem permissões de administrador.
 -Crie uma biblioteca de documentos no SharePoint para armazenar os termos de posse.
 -No Power Automate, crie um novo fluxo e configure os gatilhos e ações conforme descrito nas funcionalidades.

#### Funcionalidades
```bash

 -Geração de Termos de Posse: Cria automaticamente termos de posse de equipamentos de TI para novos colaboradores usando um modelo de documento em HTML e CSS.
 -Envio para Assinatura: Envia os termos de posse para assinatura via Microsoft Approval.
 -Armazenamento no SharePoint: Armazena os termos de posse assinados na biblioteca de documentos do SharePoint.
 -Notificação por E-mail: Envia notificações por e-mail para os colaboradores sobre o status da assinatura.
Guia do Usuário:
 -Geração de Termos: O fluxo de Power Automate é iniciado para gerar automaticamente os termos de posse para novos colaboradores, utilizando o modelo HTML e CSS.
 -Envio para Assinatura: Os termos de posse são enviados para o colaborador via Microsoft Approval para assinatura.
 -Armazenamento dos Termos: Após a assinatura, os termos são automaticamente armazenados na biblioteca de documentos do SharePoint.
 -Notificação: O colaborador e os responsáveis são notificados por e-mail sobre o status da assinatura.

```



## 🛠 Tecnologias

As seguintes tecnologias foram usadas na construção do projeto:

-   **[HTML/CSS](https://developer.mozilla.org/pt-BR/docs/Web/HTML)** 
-   **[Microsoft Aprovações](https://support.microsoft.com/pt-br/office/o-que-s%C3%A3o-aprova%C3%A7%C3%B5es-a9a01c95-e0bf-4d20-9ada-f7be3fc283d3)** 
-   **[Power Automate](https://www.microsoft.com/pt-br/power-platform/products/power-automate)**
-   **[SharePoint](https://www.microsoft.com/pt-br/microsoft-365/sharepoint/collaboration)**
---

## 🦸🏻‍♂️ Autor

 <br>
  <sub><b><p>Christopher Silva</p></b></sub></a>
 <br />

[![Linkedin Badge](https://img.shields.io/badge/-Christopher%20Silva-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/chris-f-silva//)](https://www.linkedin.com/in/chris-f-silva/) 
[![Gmail Badge](https://img.shields.io/badge/-chrisspfc.silva@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:daniel.rodrigues.soarees@gmail.com)](mailto:chrisspfc.silva@gmail.com)

---

## 📝 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.. [MIT](./LICENSE)

Feito por: Christopher Silva
