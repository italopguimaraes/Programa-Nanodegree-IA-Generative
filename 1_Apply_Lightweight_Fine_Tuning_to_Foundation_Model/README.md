# Agente Imobiliário Personalizado

# Personalized Real Estate Agent

## Introdução ao Projeto
Imagine que você é um desenvolvedor talentoso da "Future Homes Realty", uma empresa imobiliária com visão de futuro. Em um setor onde a personalização é fundamental para a satisfação do cliente, sua empresa quer revolucionar a forma como os clientes interagem com os anúncios imobiliários. O objetivo é criar uma experiência personalizada para cada comprador, tornando o processo de pesquisa de imóveis mais envolvente e adaptado às preferências individuais.

## Introduction to the Project
Imagine you are a talented developer at "Future Homes Realty", a forward-thinking real estate company. In an industry where personalization is key to customer satisfaction, your company wants to revolutionize the way customers interact with real estate listings. The goal is to create a personalized experience for each buyer, making the property search process more engaging and tailored to individual preferences.

## O desafio
Sua tarefa é desenvolver um aplicativo inovador chamado "HomeMatch". Este aplicativo aproveita grandes modelos de linguagem (LLMs) e bancos de dados vetoriais para transformar listagens imobiliárias padrão em narrativas personalizadas que ressoam com as preferências e necessidades exclusivas dos potenciais compradores.

## The challenge
Your task is to develop an innovative application called "HomeMatch". This app leverages large language models (LLMs) and vector databases to transform standard real estate listings into personalized narratives that resonate with potential buyers' unique preferences and needs.

## Componentes principais do "HomeMatch"
### Compreendendo as preferências do comprador:

Os compradores inserirão seus requisitos e preferências, como localização, tipo de propriedade, orçamento, comodidades e opções de estilo de vida.
O aplicativo usa LLMs para interpretar essas entradas em linguagem natural, entendendo solicitações diferenciadas além dos filtros básicos.
Integrando com um banco de dados vetorial:

## Main components of "HomeMatch"
### Understanding Buyer Preferences:

Buyers will enter their requirements and preferences such as location, property type, budget, amenities and lifestyle choices.
The application uses LLMs to interpret these natural language inputs, understanding nuanced requests beyond basic filters.
Integrating with a vector database:

### Conecte o "HomeMatch" a um banco de dados vetorial, onde são armazenadas todas as listagens de propriedades disponíveis.
Utilize incorporações de vetores para combinar propriedades com preferências do comprador, concentrando-se em aspectos como vibrações do bairro, estilos arquitetônicos e proximidade de comodidades específicas.
Geração de descrição de listagem personalizada:

### Connect "HomeMatch" to a vector database, where all available property listings are stored.
Use vector embeds to match properties to buyer preferences, focusing on aspects like neighborhood vibes, architectural styles, and proximity to specific amenities.
Custom listing description generation:

### Para cada listagem correspondente, use um LLM para reescrever a descrição de uma forma que destaque os aspectos mais relevantes para as preferências do comprador.
Garanta que a personalização enfatize características atraentes para o comprador sem alterar as informações factuais sobre o imóvel.

### For each matching listing, use an LLM to rewrite the description in a way that highlights the aspects most relevant to the buyer's preferences.
Ensure that personalization emphasizes features that are attractive to the buyer without altering the factual information about the property.

### Apresentação da listagem:

Produza as listagens personalizadas como uma descrição de texto da listagem.

### Listing presentation:

Output the custom listings as a text description of the listing.

## Começando

## Starting

### Google Colab Notebook:
Salve uma cópia no google drive do notebook, à partir da url abaixo, e execute as células do notebook sequencialmente preferencialmente na gpu:

https://colab.research.google.com/drive/13d2Vcc9WQz-FcZKPORlOYc4_v2VsH_Ug?usp=sharing

Se preferir pode pular a execução das células que geram o arquivo 'Listagens.txt', e fazer o upload do arquivo disponível neste repositório

### Google Colab Notebook:
Save a copy on the notebook's Google Drive, from the url below, and run the notebook's cells sequentially, preferably on the GPU:

https://colab.research.google.com/drive/13d2Vcc9WQz-FcZKPORlOYc4_v2VsH_Ug?usp=sharing

If you prefer, you can skip executing the cells that generate the 'Listagens.txt' file, and upload the file available in this repository

### Executar Localmente

1) Clone o repositório, em algum local da sua máquina, executando o comando via git:
git clone https://github.com/italopguimaraes/Programa-Nanodegree-IA-Generative.git

2) A partir do diretório anterior via terminal, entre no sub-diretório Programa-Nanodegree-IA-Generative
/4_Custom_Real Estate_Agent.

3) No terminal execute o comando para iniciar o jupyter notebook:
jupyter notebook.

4) Execute as células do notebook sequencialmente, para instalar as depêndencias e verificar as funcionalidades da aplicação, se preferir pode pular a execução das células que geram o arquivo 'Listagens.txt', e usar o arquivo localmente.

### Run Locally

1) Clone the repository, somewhere on your machine, running the command via git:
git clone https://github.com/italopguimaraes/Programa-Nanodegree-IA-Generative.git

2) From the previous directory via terminal, enter the Program-Nanodegree-IA-Generative sub-directory
/4_Custom_Real Estate_Agent.

3) In the terminal, run the command to start jupyter notebook:
jupyter notebook.

4) Run the notebook cells sequentially, to install the dependencies and check the application's functionalities. If you prefer, you can skip running the cells that generate the 'Listagens.txt' file, and use the file locally.

