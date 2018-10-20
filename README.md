# CNN-Genero-Idade

Classificação de gênero e idade utilizando Redes Neurais Convolucionais

![32332](images/photos.png)

## Instalação

1. Baixe ou clone o repositório.
2. Baixe e instale o [Miniconda](https://conda.io/miniconda.html)
3. Abra o terminal e digite o seguinte comando para instalar o ambiente:

```
$ conda create -n cnn-idade-genero-env python=3.6.5 numpy=1.14.3 pandas=0.23.0 matplotlib=2.2.2 scikit-learn=0.19.1 jupyter=1.0.0 keras=2.2.4 pillow=5.3.0
```

## Uso do ambiente

Siga os passos abaixo sempre que quiser executar os códigos desse repositório.

1. Abra o terminal e digite:

* Windows:

```
$ activate cnn-idade-genero-env
```

* Linux/Mac:

```
$ activate cnn-idade-genero-env
```

2. Execute o Jupyter Notebook:

```
$ jupyter notebook
```

## Estrutura

O repositório está organizado da seguinte maneira 

|Pasta/Arquivo|Descrição|
|---|---|
|data/|Contém apenas algumas arquivos .TXT que fazem referência as imagens do banco, nessa pasta você deve baixar e extrair o dataset/|
|images/|Algumas imagens que são utilizdas no repositório (NÃO são as imagens do banco)|
|models/|Modelos salvos no Keras|
|serializer/|Objetos pré-processados que serão utilizados na entrada da nossa rede|
|txt/|Correções nos arquivos .TXT originais do banco|
|Pre_processing| Rode todas as células desse notebook para gerar os arquivos de entrada da rede|
