# Análise de dados do consumo de gasolina no Brasil

## download_files.py
contém o código para fazer download da base de dados utilizada nessa
análise.

Os dados foram obtidos do portal [dados.gov.br](https://dados.gov.br/dataset/serie-historica-de-precos-de-combustiveis-por-revenda)

## gasolina.py
arquivo principal que contém os métodos para calcular e plotar a média
do consumo de gasolina no Brasil por estado

## Modo de usar

### Criando ambiente virtual do Python
```
python3 -m venv .venv
```
### Ativando o ambiente virtual
```
source .venv/bin/activate
```
### Instalando todas as dependências
```
pip install -r requirements.txt
```
### Iniciando o download do arquivo em csv
```
python download_files.py
```
### executando a pagina principal
```
python gasolina.py
```

