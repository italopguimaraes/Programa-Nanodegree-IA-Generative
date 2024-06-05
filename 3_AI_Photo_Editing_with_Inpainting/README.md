# Edição de fotos AI com I.A Inpainting 

# AI photo editing with A.I. Inpainting

## Introdução ao Projeto

Nesta aula vimos como modelos generativos podem ser usados ​​em Visão Computacional. Também vimos como usar o modelo Segment Anything para selecionar assuntos em imagens, fornecendo pontos e outras entradas.
Vamos usar um pouco desse conhecimento construindo algo interessante e divertido!

## Introduction to the Project

In this class we saw how generative models can be used in Computer Vision. We also saw how to use the Segment Anything model to select subjects in images by providing points and other inputs.
Let's use some of this knowledge by building something interesting and fun!

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <img src='https://drive.google.com/uc?id=1N4ToI9tCjGVKO3Y_zmASxGVGvbVsDPSD&export=download' width="800">
      <script src="script.js"></script>
  </body>
</html>

Com nosso app poderemos trocar o fundo de uma imagem e substituí-lo por um gerado por computador descrito em texto

With our app we will be able to change the background of an image and replace it with a computer-generated one described in text

<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <img src='https://drive.google.com/uc?id=17EU3GOiuwh8F2AYKUKtZanezLnQPyG5D&export=download' width="800">
      <script src="script.js"></script>
  </body>
</html>

# Resumo do projeto

Neste projeto vamos construir um pequeno aplicativo que permite selecionar um assunto e depois alterar seu plano de fundo, OU manter o plano de fundo e mudar de assunto.

O processo envolve o usuário fazer upload de uma imagem e selecionar o objeto principal clicando nele. O Segment Anything Model (SAM) é ativado para criar uma máscara ao redor do objeto selecionado, escolhendo a máscara mais precisa gerada. Este resultado é mostrado ao usuário para aceitá-lo ou refinar ainda mais a máscara com pontos adicionais. Assim que a máscara for finalizada, o usuário fornece uma descrição de texto (e possivelmente um aviso negativo) para especificar um novo plano de fundo para o objeto selecionado. Um modelo de preenchimento cria esse novo plano de fundo e a imagem final é exibida. Opcionalmente, o usuário pode optar por inverter a máscara e substituir o assunto mantendo o fundo, como no exemplo acima.
Este pequeno aplicativo pode ser usado para trocar fundos, trocar assuntos, remover objetos e muito mais!
Você escreverá o código que alimenta a funcionalidade principal do aplicativo: chamar o modelo SAM e processar sua saída, bem como usar um modelo de difusão text2image para gerar o novo plano de fundo ou assunto.
Vamos começar!

# Project summary

In this project we will build a small application that allows you to select a subject and then change its background, OR keep the background and change the subject.

The process involves the user uploading an image and selecting the main object by clicking on it. The Segment Anything Model (SAM) is activated to create a mask around the selected object, choosing the most accurate generated mask. This result is shown to the user to accept it or further refine the mask with additional points. Once the mask is finalized, the user provides a text description (and possibly a negative warning) to specify a new background for the selected object. A fill template creates this new background and the final image is displayed. Optionally, the user can choose to invert the mask and replace the subject while maintaining the background, as in the example above.
This small app can be used to swap backgrounds, swap subjects, remove objects and much more!
You will write the code that powers the core functionality of the application: calling the SAM model and processing its output, as well as using a text2image broadcast model to generate the new background or subject.
Let's start!

## Começando

## Starting

### Google Colab Notebook:
Salve uma cópia no google drive do notebook, à partir da url abaixo, e execute as células do notebook sequencialmente preferencialmente na gpu:

https://colab.research.google.com/drive/1Qon7-0auj_4SPNB2dXyLD4ypCqNnar_x?usp=sharing

### Google Colab Notebook:
Save a copy on the notebook's Google Drive, from the url below, and run the notebook's cells sequentially, preferably on the GPU:

https://colab.research.google.com/drive/1Qon7-0auj_4SPNB2dXyLD4ypCqNnar_x?usp=sharing

### Executar Localmente

1) Clone o repositório, em algum local da sua máquina, executando o comando via git:
git clone https://github.com/italopguimaraes/Programa-Nanodegree-IA-Generative.git

2) A partir do diretório anterior via terminal, entre no sub-diretório Programa-Nanodegree-IA-Generative
/3_AI_Photo_Editing_with_Inpainting

3) No terminal execute o comando para iniciar o jupyter notebook:
jupyter notebook.

4) Execute as células do notebook sequencialmente, para instalar as depêndencias e verificar as funcionalidades da aplicação.

### Run Locally

1) Clone the repository, somewhere on your machine, running the command via git:
git clone https://github.com/italopguimaraes/Programa-Nanodegree-IA-Generative.git

2) From the previous directory via terminal, enter the Program-Nanodegree-IA-Generative sub-directory
/3_AI_Photo_Editing_with_Inpainting

3) In the terminal, run the command to start jupyter notebook:
jupyter notebook.

4) Run the notebook cells sequentially, to install the dependencies and check the application's functionalities.