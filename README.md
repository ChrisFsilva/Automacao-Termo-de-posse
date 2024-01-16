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
     * [Rodando a aplicação](#-Rodando-a-aplicação-Web)
   * [Tecnologias](#-tecnologias)
   * [Autor](#-autor)
   * [Licença](#-licença)
<!--te-->


## 💻 Sobre o projeto

  * Situação
- Processo de documentação legal referente aos equipamentos e acessorios fornecidos ao colaborador.
- Processo realizado totalmente de forma manual com base nas ferramentas conhecidas pelo técnico.
  * Problema enfrentado
- Sem padronização do documento.
- Documentos que não cumpriam LGPD.
- Sem precisão na confirmação do material entregua.
- Sem padronização no tipo de arquivo
- Sem padronização no método de entrega
- Erros de português
  * Execução da solução
- Através do Sharepoint é alimentado um banco de dado.
- Quando o técnico define o status como "Gerar termo de posse" aciona uma API do Approvous que envia um e-mail para o colaborador, constando a lista dos equipamentos fornecidos.
- O e-mail possui comando TypeScript cujo o colaborador utilizará para confirmar se as informações de equipamento estão corretas
- Caso ele confirme será uma acinada uma API via JavaScript
- Essa API fornece as informações ao Power automate onde é criado um documento em HTML e outro PDF.
- Esse documento é implementado como TypeScript no corpo do e-mail alem do PDF ser anexo e enviado ao colaborador.
- Caso ele recuse deverá preencher um formulario justificando o motivo da recusa
- Técnico responsavel e gestor receberão um e-mail notificando a recusa com os detalhes adicionado pelo colaborador
- Caso o status seja alterado para "Devolução do equipamento" será enviado um termo utilizando o banco de dados para o e-mail pessoal do colaborador constando todos os itens que ele devolveu, de acordo com os critérios da LGPD.

 
---

## 🎨 Layout

O layout da aplicação está disponível no LinkedIn:

<a href="#">
  <img alt="Automação do Onboard By Christopher Silva" src="https://img.shields.io/badge/Acessar%20Layout%20-aqui-%2304D361?style=flat-square">
</a>

<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="https://www.linkedin.com/in/chris-f-silva/" title="#moments-automacao" src="https://media.licdn.com/dms/image/D4D2DAQFhWADyr73FMA/profile-treasury-image-shrink_1920_1920/0/1704298991106?e=1706036400&v=beta&t=zrYm5i4Sa4wA7v-5fx5w2HYSv32kGRqRlR5zyR3Lc-w" />
</p>
<p align="center" style="display: flex; align-items: flex-start; justify-content: center;">
  <img alt="https://www.linkedin.com/in/chris-f-silva/" title="#moments-automacao" src="https://media.licdn.com/dms/image/D4D2DAQH4VuA7hxM1uw/profile-treasury-image-shrink_800_800/0/1704298974179?e=1706036400&v=beta&t=lgkdphgNnvWQiqKF-svpa_8oziyZEqA5-AEYfHvhqz8" />
</p>

---

## 🚀 Como executar o projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
 - Navegador

Devido ao conteúdo sensivel presente na codificação, os códigos responsaveis pelo Power Automate e API Gupy não serão publicados.

#### 🧭 Rodando a aplicação Web
```bash

# Clone este repositório
$ git clone https://github.com/ChrisFsilva/Automacao-Onbord



```



## 🛠 Tecnologias

As seguintes tecnologias foram usadas na construção do projeto:

-   **[JavaScript](https://www.javascript.com/)** 
-   **[TypeScript](https://www.typescriptlang.org/)** 
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

Este projeto esta sobe a licença [MIT](./LICENSE)

Feito por: Christopher Silva
