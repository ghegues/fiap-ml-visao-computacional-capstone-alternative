![](https://img.shields.io/github/repo-size/michelpf/fiap-ml-visao-computacional-capstone-alternative)
![](https://img.shields.io/github/issues/michelpf/fiap-ml-visao-computacional-capstone-alternative)
![](https://img.shields.io/github/stars/michelpf/fiap-ml-visao-computacional-capstone-alternative)
![](https://img.shields.io/github/watchers/michelpf/fiap-ml-visao-computacional-capstone-alternative)
![](https://img.shields.io/github/last-commit/michelpf/fiap-ml-visao-computacional-capstone-alternative)


# MBA FIAP Inteligência Artificial & Machine Learning

Obtenha mais informações sobre a formação em inteligência artificial e a ementa completa no [portal](https://www.fiap.com.br/mba/mba-em-artificial-intelligence-e-machine-learning/) da FIAP.

## Visão Computacional Capstone

### Análise de Imagens Médicas

As tecnologias de imagens médicas estão cada vez mais integradas aos sitemas de visão computacional, incluindo as imagens de raio-x.

Modelos de equipamentos modernos geram imagens digitais deste tipo de exame, proporcionando análises mais completas e menos _ad-hoc_, com isso algumas pré-análises podem ser realizadas por aplicações baseadas em inteligência artificial para confirmar ou sugerir diagnósticos ao profissional responsável pelo exame.

No campo dos diagósticos por raios-x, a pnenumonia é uma das enfermidades onde seu uso é um dos mais aplicados para determinar o curso de tratamento.

<p align="center">
    <img src="imagens/NORMAL2-IM-1422-0001.jpeg">
</p>


## 1. Instruções

Nas aulas utilizaremos a distribuição Ananconda, com uso intensivo do Jupyter Notebook, que há vem instalado nesta distribuição.

Para instalar, acesse a sessão de [Downloads](https://www.anaconda.com/download) do Anaconda.


### 2. Repositório

Recomendamos clonar este repositório.

>**Importante**: como serão desenvolvidos modelos com arquivos grandes, é necessário ter um arquivo ```.gitignore``` com o seguinte conteúdo:

```
projeto/pesos/*
!projeto/pesos/.gitkeep 

projeto/modelos/*
!projeto/modelos/.gitkeep 

projeto/classificadores/*
!projeto/classificadores/.gitkeep 

projeto/.ipynb_checkpoints

.DS_Store
````

### 3. Template guiado

📙 Utilize o arquivo Jupyter [```projeto-final/analise-imagens-medicas.ipynb```](https://github.com/michelpf/fiap-ml-visao-computacional-capstone-alternative/blob/master/projeto-final/analise-imagens-medicas.ipynb), siga todas as instruções, completando e construindo os algoritmos necessários. Este template foi desenvolvido para ser executado localmente, em uma instalação do Anaconda.

📕 Versão Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/michelpf/fiap-ml-visao-computacional-capstone-alternative/blob/master/projeto-final/analise-imagens-medicas-colab.ipynb)

> **Atenção: o grupo/aluno que não utilizar este template (ou alterar partes indevidas) será automaticamente reprovado.**

### 4. Bibliotecas utilizadas

Este projeto requer **Python 3.5 ou superior** e as seguintes bibliotecas:

- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](http://seaborn.pydata.org/)
- [Keras](https://keras.io/)
- [Tensorflow](http://tensorflow.org/)
- [Pillow](https://pillow.readthedocs.io/en/stable/)

