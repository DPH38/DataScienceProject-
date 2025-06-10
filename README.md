# Data Science Project

## Sobre o Projeto
Este projeto é uma análise de dados utilizando Python e Jupyter Notebook. Ele inclui:
- Um notebook chamado `data_science.ipynb` que contém a análise de dados.
- Arquivos de dados no formato Parquet (`dados.parquet`).
- Resultados exportados em formatos HTML (`data_science.html`) e PDF (`data_science.pdf`).

## Estrutura do Projeto
- `data_science.ipynb`: Notebook principal contendo a análise.
- `dados.parquet`: Arquivo de dados utilizado na análise.
- `data_science.html`: Exportação do notebook em formato HTML.
- `data_science.pdf`: Exportação do notebook em formato PDF.
- `requirements.txt`: Lista de dependências do projeto.

## Pré-requisitos
Certifique-se de ter instalado:
- Python 3.12 ou superior
- Gerenciador de pacotes `pip`
- Ambiente virtual configurado (opcional, mas recomendado)

## Configuração do Ambiente
1. Clone este repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd DataScienceProject-
   ```

2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Como Executar
1. Ative o ambiente virtual:
   ```bash
   source .venv/bin/activate
   ```

2. Abra o notebook Jupyter:
   ```bash
   jupyter notebook data_science.ipynb
   ```

3. Execute as células do notebook para realizar a análise.

## Exportação de Resultados
Para exportar o notebook para HTML ou PDF:
- HTML:
  ```bash
  jupyter nbconvert data_science.ipynb --to html
  ```
- PDF:
  ```bash
  jupyter nbconvert data_science.ipynb --to pdf
  ```

## Contato
Caso tenha dúvidas ou sugestões, entre em contato pelo email: [halfporto@gmail.com](mailto:seuemail@dominio.com).
