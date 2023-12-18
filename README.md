# Análise de churn

Este é um case sobre análise de dados para um dataset sobre assinaturas de serviço da petlove. O objetivo é descobrir fatores que causam o churn para este serviço.

# Instruções de instalação

Para rodar a análise é importante ter o python e o jupyter notebook instalados.

### Instalando o Python

Para instalar o python, você pode seguir os passos no site:

Windows:
https://www.python.org/downloads/

Linux:
https://python.org.br/instalacao-linux/

### Instalando o Jupyter

Após ter o python instalado, instale o jupyter e as bibliotecas necessárias.
Para a instalação das bibliotecas, rode os seguintes comandos em seu terminal.

```bash
pip install jupyterlab
pip install numpy
pip install pandas
pip install matplotlib
pip install seaborn
pip install sklearn
```

### Clonando o repositório e rodando o projeto

Para clonar o repositório em sua máquina, abra o terminal e rode o seguinte comando em seu terminal.
```bash
git clone https://github.com/vitor-pelicer/churn-analysis
```

Navegue até o diretório clonado.
```bash
cd churn-analysis
```

Rode o jupyter em seu terminal.
```bash
jupyter-lab --no-browser
```

Clique no link que aparecer no seu terminal. Irá abrir uma guia do Jupyter no seu navegador mostrando o repositório.
Selecione o notebook e rode todas as células para concluir a análise.

# Lógica do código:

1 Fazer pré processamento dos dados

1.1 Descartar dados desnecessários para a análise

1.2 Uilizar one hot encoding e min-max scaller para preparar os dados

2 Análise dos dados

2.1 Visualizar a correlação entre as colunas do dataset

2.2 Visualizar o histograma da coluna recency de acordo com o status da assinatura

Para mais detalhes, olhar as células de markdown do notebook.




