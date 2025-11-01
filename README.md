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

## 📝 Anotações e Insights Adquiridos

Esta seção contém o material de apoio para estudos, detalhando os aprendizados obtidos em cada ferramenta.

### 1. Azure Speech Studio (Análise e Síntese de Fala)

| Funcionalidade Praticada | Insight / Descoberta Principal |
| :--- | :--- |
| **Speech-to-Text (Transcrição de Fala)** | **[SUBSTITUA AQUI: Ex: A precisão da transcrição melhora significativamente ao utilizar áudio de alta qualidade e modelos específicos para o sotaque/idioma.]** |
| **Text-to-Speech (Voz Sintética)** | **[SUBSTITUA AQUI: Ex: Explorei o uso da Linguagem de Marcação de Síntese de Fala (SSML) para controlar entonação e pausas, tornando a voz mais natural. Adicionei um exemplo no arquivo `ssml_exemplo.txt` (Se aplicável).]** |
| **[OUTRA FUNÇÃO]** | **[SUBSTITUA AQUI: Se você trabalhou com Custom Speech ou Reconhecimento de Intenção de Fala, adicione seu insight aqui.]** |

### 2. Azure Language Studio (Análise de Linguagem Natural)

| Funcionalidade Praticada | Insight / Descoberta Principal |
| :--- | :--- |
| **Reconhecimento de Entidades Nomeadas (NER)** | **[SUBSTITUA AQUI: Ex: O NER é crucial para extrair informações estruturadas de textos não estruturados, como nomes, locais e datas, facilitando a indexação e busca de dados.]** |
| **Análise de Sentimento e Mineração de Opinião** | **[SUBSTITUA AQUI: Ex: A mineração de opinião oferece um nível de granularidade maior que a simples análise de sentimento, identificando o alvo (aspecto) e a opinião associada a ele em frases complexas.]** |
| **Resumo Extrativo e Abstrato** | **[SUBSTITUA AQUI: Ex: O resumo abstrato é mais útil para gerar sinopses curtas e originais, enquanto o extrativo é mais seguro para garantir que as frases mais importantes do texto original sejam mantidas.]** |
| **[OUTRA FUNÇÃO]** | **[SUBSTITUA AQUI: Se você trabalhou com Classificação de Texto, Tradução ou outra função, adicione seu insight aqui.]** |

## 🛠️ Documentação do Processo Técnico

### 1. Preparação do Ambiente Azure

1.  **Criação do Recurso:**
    * Foi criado um recurso **Azure AI Services** (ou recursos separados de Speech e Language, **[ESPECIFIQUE O QUE VOCÊ FEZ]**).
    * **Região Escolhida:** `[SUBSTITUA AQUI]`
    * **Detalhe:** `[SUBSTITUA AQUI: Ex: As chaves e endpoints foram armazenados de forma segura e não estão expostas neste repositório.]`
2.  **Configuração de Idioma:**
    * Todos os testes e análises foram realizados primariamente no idioma **Português (Brasil/Portugal)**, conforme a necessidade do projeto, garantindo a compatibilidade dos modelos de IA.

### 2. Passo a Passo do Language Studio

* Acessado o Language Studio e selecionado a funcionalidade de **Análise de Texto**.
* **Teste Prático:** Foi utilizado um trecho de texto de exemplo (`[SUBSTITUA AQUI: Ex: um feedback de cliente fictício]`).
* **Resultados Chave:**
    * O serviço identificou com sucesso **[X]** entidades (Pessoa, Organização, Data, etc.).
    * O sentimento geral foi classificado como **[Positivo/Negativo/Neutro]** com pontuação de **[X]%**.
    * *Confira as capturas de tela detalhadas na pasta `/images`.*

### 3. Passo a Passo do Speech Studio

* Acessado o Speech Studio e explorado a funcionalidade de **[SUBSTITUA AQUI: Ex: Áudio + Transcrição]**.
* **Teste Prático:** Foi feito o upload de um arquivo de áudio (`[SUBSTITUA AQUI: Ex: um clipe de voz curto]`).
* **Resultados Chave:**
    * A transcrição foi concluída em **[X]** segundos, com uma taxa de precisão percebida de **[X]%**.
    * Na síntese de fala, a voz **[Nome da Voz Escolhida, Ex: Francisca Neural]** foi utilizada para gerar um arquivo de áudio.
    * *Capturas do painel do Speech Studio estão na pasta `/images`.*
