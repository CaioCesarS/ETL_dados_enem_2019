# ELT de dados do Enem 2019 usando Python

Tarefa realiza no Bootcamp de Engenharia de Dados no [IGTI](https://www.igti.com.br/). O objetivo desta tarefa é realizar a extração dos microdados do Enem do ano de 2019 através do arquivo .zip disponível para download neste [link](http://download.inep.gov.br/microdados/microdados_enem_2019.zip). Posteriormente feito a transformação e análise dos dados e ao final a ingestão do mesmo no banco de dados [PostgreSQL](https://www.postgresql.org/).

## Instalação das Dependências

Utilize o gerenciador de pacotes do Python [pip3](https://pip.pypa.io/en/stable/) para instalar as dependências.

```bash
pip3 install -r requirements.txt
```

## Execução

Antes de tudo certifique-se de que o servidor do seu Jupyter Notebook ou Jupyter Lab esteja em execução.

Na pasta raiz do projeto, inicialmente possui 2 arquivos e são:
* **requirements.txt**: Arquivo que possui as dependências e suas respectivas versões utilizadas no projeto.
* **etl_enem_2019.ipynb**: Notebook que possui os códigos para realizar a extração de dados. Transformação e análise dos dados e ingestão dos mesmos no banco de dados relacional PostgreSQL. 

## Licença
[MIT](https://choosealicense.com/licenses/mit/)
