<p align="center">
  <img width="300" src="FacEmotions.png">
</p>

# Projeto

Repositório responsável pelo trabalho da disciplina Tópicos Especiais de Engenharia de Software. O projeto FacEmotions tem como propósito, a partir de conceitos de Deep Learning e Redes Neurais Convolucionais (CNNs), analisar sentimentos representados por expressões faciais em filmagens de tempo real. O algoritmo pode beneficiar diversas instituições e projetos que tenham questões de segurança ou conduzam investigações.


## Grupo

|Nome | Matricula |
|:---:|:---:|
|Fernando Miranda Calil| 190106565|
|Luan Vasco Cavalcante| 190111836|
|Lameque Fernandes Azevedo | 180104390 |
| Victor Hugo Oliveira Leão | 200028367 |


# Como usar

## Treinar nova rede

O repositório deve ser clonado localmente:
  git clone git@github.com:deeplearningunb/FacEmotions.git
  
Entrar na pasta do projeto:
  cd FacEmotion

Instalar as dependencias do projeto:
  pip3 install -r requirements.txt

Abrir o notebook:
  jupyter notebook
  
Escolha o notebook CNN_PHOTOS.ipynb
Rode o código completo.

## Utilizar rede treinada

O repositório deve ser clonado localmente:
  git clone git@github.com:deeplearningunb/FacEmotions.git
  
Entrar na pasta do projeto:
  cd FacEmotion

Instalar as dependencias do projeto:
  pip3 install -r requirements.txt
  
Abrir o notebook:
  jupyter notebook
  
Escolha o notebook EmotionDetectionConsole.ipynb

Troque o endereço que é fornecido à função load_model no terceiro bloco de código, para o endereço da rede treinada.

Rode o notebook completo.
