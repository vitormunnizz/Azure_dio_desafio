# 🎙️ Laboratório Prático: Análise de Fala e Linguagem com Azure AI

Este repositório documenta a prática e o aprofundamento no uso das ferramentas **Azure Speech Studio** e **Azure Language Studio**, focando na criação de soluções baseadas em Inteligência Artificial para voz e linguagem.

O objetivo é servir como um material de referência detalhado, consolidando as anotações e *insights* adquiridos para estudos futuros e implementações práticas.

## 🎯 Objetivos de Aprendizagem e Escopo do Desafio

Ao realizar este laboratório, foram cumpridos os seguintes objetivos:

1.  **Aplicação Prática:** Aplicar os conceitos de Azure AI em um ambiente de desenvolvimento real (Azure Speech Studio e Language Studio).
2.  **Documentação Estruturada:** Documentar processos técnicos de forma clara, organizada e estruturada.
3.  **Compartilhamento Técnico:** Utilizar o GitHub como ferramenta principal para o compartilhamento da documentação técnica e dos *artefatos* do projeto.

## ⚙️ Tecnologias e Serviços Utilizados

| Serviço / Ferramenta | Finalidade no Projeto |
| :--- | :--- |
| **Azure Speech Studio** | Análise e processamento de fala (Speech-to-Text e Text-to-Speech). |
| **Azure Language Studio** | Análise de linguagem natural (NER, Sentiment Analysis, Summarization). |
| **GitHub** | Versionamento e compartilhamento do repositório de documentação. |
| **Markdown** | Formatação estruturada dos arquivos de documentação. |

## 🛠️ Documentação do Processo Técnico

### 1. Preparação do Ambiente Azure

1.  **Criação do Recurso:**
    * Foi criado um recurso **Azure AI Services (Multi-service)** para gerenciar de forma unificada as chaves e o acesso a todos os serviços de Fala e Linguagem.
    * **Região Escolhida:** `Brazil South`
    * **Detalhe:** As chaves de API e *endpoints* foram obtidos no painel do recurso no Azure. Eles foram tratados como variáveis de ambiente e **não estão expostos neste repositório** por razões de segurança.
2.  **Configuração de Idioma:**
    * Todos os testes e análises foram realizados primariamente no idioma **Português (Brasil)**, garantindo a compatibilidade dos modelos de IA com os dados de entrada simulados.

### 2. Passo a Passo do Language Studio

* Acessado o Language Studio e selecionado a funcionalidade de **Análise de Texto** (Recursos de Linguagem pré-construídos).
* **Teste Prático:** Foi utilizado um trecho de texto de exemplo (`Um feedback de um usuário de aplicativo: "O app é ótimo, mas a última atualização está com um bug sério no login. Dei 5 estrelas porque amo o design."`).
* **Resultados Chave:**
    * O serviço identificou com sucesso **4** entidades (Produto, Pessoa, Organização, Evento, etc.). **Entidades notáveis: "5 estrelas" (Quantidade), "app" (Produto), "login" (Conceito/Feature).**
    * O sentimento geral foi classificado como **Neutro** (Score de 0.52). A Mineração de Opinião detalhou o sentimento como: **Negativo** para o aspecto "bug" e **Positivo** para o aspecto "design".

### 3. Passo a Passo do Speech Studio

* Acessado o Speech Studio e explorado a funcionalidade de **Transcrição em tempo real de Áudio + Transcrição**.
* **Teste Prático:** Foi feito o upload de um arquivo de áudio de **8 segundos** (`Gravação de um trecho de podcast com dois locutores sobre tecnologia.`).
* **Resultados Chave:**
    * A transcrição foi concluída em **3** segundos, com uma taxa de precisão percebida de **99%**. A diarização funcionou, separando o texto corretamente entre **Locutor 1** e **Locutor 2**.
    * Na síntese de fala, a voz **Francisca Neural (pt-BR)** foi utilizada para gerar um arquivo de áudio para um menu telefônico ("Para falar com o suporte, diga 'Suporte'. Para vendas, diga 'Vendas'.").
