# Projeto: Construa Seu Próprio Chatbot Personalizado

# Project: Build Your Own Custom Chatbot

## Projeto: Construa Seu Próprio Chatbot Personalizado
Neste projeto você alterará o conjunto de dados para construir seu próprio chatbot personalizado.

## Project: Build Your Own Custom Chatbot
In this project you will alter the dataset to build your own custom chatbot.

## O que você construirá?
Ao concluir este projeto, você terá um chatbot OpenAI personalizado usando um cenário de sua escolha. Você será responsável por selecionar uma fonte de dados, explicar por que ela é apropriada para a tarefa, incorporar a fonte de dados ao código do chatbot personalizado e escrever perguntas para demonstrar o desempenho do prompt personalizado.

## What will you build?
When you complete this project, you will have a custom OpenAI chatbot using a scenario of your choice. You will be responsible for selecting a data source, explaining why it is appropriate for the task, incorporating the data source into your custom chatbot code, and writing questions to demonstrate the custom prompt's performance.

## Fontes de dados
Existem duas fontes de dados principais que recomendamos usar para este projeto: API da Wikipedia e dados CSV.

A API da Wikipedia será mais semelhante aos exemplos mostrados nas demonstrações e exercícios que você viu anteriormente. Você pode usar qualquer artigo diferente de 2022(abre em uma nova aba)ou Terremoto Síria-Turquia de 2023(abre em uma nova aba)desde que cumpra os requisitos.

Também fornecemos um datadiretório contendo arquivos CSV que você pode usar para o projeto. Estes são:

+ 2023_fashion_trends.csv- este arquivo contém relatórios e citações sobre tendências da moda para 2023. Cada linha inclui o URL de origem, o título do artigo e o trecho de texto.

+ character_descriptions.csv- este arquivo contém descrições de personagens de produções de teatro, televisão e cinema. Cada linha contém o nome, a descrição, a mídia e a configuração. Todos os personagens foram inventados por um modelo OpenAI.

+ nyc_food_scrap_drop_off_sites.csv- este arquivo contém locais, horários e outras informações sobre locais de entrega de restos de alimentos na cidade de Nova York. Esta informação foi recuperada no início de 2023, e você também pode obter a versão mais recente neste portal de dados abertos(abre em uma nova aba).

Você também pode obter seus próprios dados. Por exemplo, você pode querer usar web scraping ou outros documentos que tenha em mãos. O conjunto de dados deve ter pelo menos 20 linhas e deve ser composto por dados de texto . Os modelos de linguagem OpenAI não são otimizados para raciocínio numérico ou lógico, portanto, dados com muitos números, como orçamentos, dados de sensores ou inventário, não são apropriados.

## Data sources
There are two main data sources we recommend using for this project: Wikipedia API and CSV data.

The Wikipedia API will be more similar to the examples shown in the demos and exercises you saw earlier. You may use any article other than the 2022(opens in a new tab) or 2023 Syria-Turkey Earthquake(opens in a new tab) as long as it meets the requirements.

We also provide a data directory containing CSV files that you can use for the project. These are:

+ 2023_fashion_trends.csv- this file contains reports and quotes on fashion trends for 2023. Each line includes the source URL, article title, and text snippet.

+ character_descriptions.csv- this file contains descriptions of characters from theater, television and cinema productions. Each line contains the name, description, media, and configuration. All characters were invented by an OpenAI model.

+ nyc_food_scrap_drop_off_sites.csv - This file contains locations, times, and other information about food scrap drop-off locations in New York City. This information was retrieved in early 2023, and you can also get the latest version from this open data portal (opens in a new tab).

You can also obtain your own data. For example, you may want to use web scraping or other documents you have on hand. The dataset must have at least 20 lines and must consist of text data. OpenAI language models are not optimized for numerical or logical reasoning, so number-heavy data, such as budgets, sensor data, or inventory, is not appropriate.

## Cenário personalizado
Além do componente técnico de preparação e incorporação de um novo conjunto de dados, é necessário explicar por que esse conjunto de dados é apropriado para a tarefa. Se o modelo responder da mesma maneira, independentemente de dados personalizados serem fornecidos, isso significa que o conjunto de dados não era apropriado para a tarefa. Você explicará sua escolha do conjunto de dados de duas maneiras:

<ol>
<li>Primeiro, no início do notebook, você escreverá um pequeno parágrafo descrevendo sua escolha de conjunto de dados e configurando o cenário de quando essa personalização seria útil.</li>

<li>Em segundo lugar, no final do notebook, você demonstrará as perguntas e respostas do modelo antes e depois da customização ter sido realizada para destacar as alterações.</li>
</ol>

## Custom scenario
In addition to the technical component of preparing and incorporating a new dataset, it is necessary to explain why this dataset is appropriate for the task. If the model responds the same way regardless of whether custom data is provided, it means the dataset was not appropriate for the task. You will explain your choice of dataset in two ways:

<ol>
<li>First, at the beginning of the notebook, you will write a short paragraph describing your choice of data set and setting up the scenario for when this customization would be useful.</li>

<li>Secondly, at the end of the notebook, you will demonstrate the model questions and answers before and after the customization was performed to highlight the changes.</li>
</ol>

## Começando

## Starting

### Google Colab Notebook:
Salve uma cópia no google drive do notebook, à partir da url abaixo, e execute as células do notebook sequencialmente preferencialmente na gpu:

https://colab.research.google.com/drive/10lf-YFAhrgb67GFQFna4Z8UZu3Mtz6IH?usp=sharing

### Google Colab Notebook:
Save a copy on the notebook's Google Drive, from the url below, and run the notebook's cells sequentially, preferably on the GPU:

https://colab.research.google.com/drive/10lf-YFAhrgb67GFQFna4Z8UZu3Mtz6IH?usp=sharing

### Executar Localmente

1) Clone o repositório, em algum local da sua máquina, executando o comando via git:
git clone https://github.com/italopguimaraes/Programa-Nanodegree-IA-Generative.git

2) A partir do diretório anterior via terminal, entre no sub-diretório Programa-Nanodegree-IA-Generative
/2_Project_Build_Your_Own_Custom_Chatbot.

3) No terminal execute o comando para iniciar o jupyter notebook:
jupyter notebook.

4) Execute as células do notebook sequencialmente, para instalar as depêndencias e verificar as funcionalidades da aplicação.

### Run Locally

1) Clone the repository, somewhere on your machine, running the command via git:
git clone https://github.com/italopguimaraes/Programa-Nanodegree-IA-Generative.git

2) From the previous directory via terminal, enter the Program-Nanodegree-IA-Generative sub-directory
/2_Project_Build_Your_Own_Custom_Chatbot.

3) In the terminal, run the command to start jupyter notebook:
jupyter notebook.

4) Run the notebook cells sequentially, to install the dependencies and check the application's functionalities.
