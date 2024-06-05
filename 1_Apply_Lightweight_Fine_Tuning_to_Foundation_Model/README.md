# Aplicar Ajuste Fino Leve a um Modelo de Base

# Apply Light Fine Tuning to a Base Model

## Introdução ao Projeto
O ajuste fino leve é ​​uma das técnicas mais importantes para adaptar modelos de fundação, pois permite modificar modelos de fundação de acordo com suas necessidades, sem a necessidade de recursos computacionais substanciais.

Neste projeto, você aplicará o ajuste fino com eficiência de parâmetros usando a peftbiblioteca Hugging Face.

## Introduction to the Project
Light fine-tuning is one of the most important techniques for adapting foundation models, as it allows you to modify foundation models according to your needs without the need for substantial computational resources.

In this project, you will efficiently fine-tune parameters using the Hugging Face library.

## Resumo do projeto
Neste projeto, você reunirá todos os componentes essenciais de um processo de treinamento e inferência PyTorch + Hugging Face. Especificamente, você irá:

Carregue um modelo pré-treinado e avalie seu desempenho
Execute o ajuste fino com eficiência de parâmetro usando o modelo pré-treinado
Realize inferência usando o modelo ajustado e compare seu desempenho com o modelo original.

## Project summary
In this project, you will bring together all the essential components of a PyTorch + Hugging Face training and inference process. Specifically, you will:

Load a pre-trained model and evaluate its performance
Perform parameter-efficient fine-tuning using the pre-trained model
Perform inference using the fitted model and compare its performance to the original model.

## Começando

## Starting

### Google Colab Notebook:
Salve uma cópia no google drive do notebook, à partir da url abaixo, e execute as células do notebook sequencialmente preferencialmente na gpu:

https://drive.google.com/file/d/1AV61w600cbSPuWI1vmWVJ3VLc1S70-sU/view?usp=sharing

### Google Colab Notebook:
Save a copy on the notebook's Google Drive, from the url below, and run the notebook's cells sequentially, preferably on the GPU:

https://drive.google.com/file/d/1AV61w600cbSPuWI1vmWVJ3VLc1S70-sU/view?usp=sharing

### Executar Localmente

1) Clone o repositório, em algum local da sua máquina, executando o comando via git:
git clone https://github.com/italopguimaraes/Programa-Nanodegree-IA-Generative.git

2) A partir do diretório anterior via terminal, entre no sub-diretório Programa-Nanodegree-IA-Generative
/1_Apply_Lightweight_Fine_Tuning_to_Foundation_Model.

3) No terminal execute o comando para iniciar o jupyter notebook:
jupyter notebook.

4) Execute as células do notebook sequencialmente, para instalar as depêndencias e verificar as funcionalidades da aplicação.

### Run Locally

1) Clone the repository, somewhere on your machine, running the command via git:
git clone https://github.com/italopguimaraes/Programa-Nanodegree-IA-Generative.git

2) From the previous directory via terminal, enter the Program-Nanodegree-IA-Generative sub-directory
/1_Apply_Lightweight_Fine_Tuning_to_Foundation_Model.

3) In the terminal, run the command to start jupyter notebook:
jupyter notebook.

4) Run the notebook cells sequentially, to install the dependencies and check the application's functionalities.
