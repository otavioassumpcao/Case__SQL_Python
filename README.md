# Projeto: Case de SQL e Python

Este projeto foi desenvolvido como parte de um processo seletivo para estágio, com o objetivo de demonstrar habilidades em **SQL** e **Python**. Ele inclui a manipulação de dados utilizando **Pandas** e consultas **SQL**, além de um fluxo de registro de vendas e clientes.

## Funcionalidades

- Registro de clientes e vendas.
- Verificação e atualização automática de clientes existentes no sistema.
- Exibição do saldo total de um cliente (somatório das vendas).
- Manipulação de dados usando **Pandas** e **SQLite**.

---

## Estrutura do Projeto

- **`Resolucao.ipynb`**: Jupyter Notebook contendo a resolução do case, incluindo a manipulação de dados e análise.
- **`clientes.csv`** e **`vendas.csv`**: Arquivos CSV que armazenam as informações dos clientes e suas vendas.
- **`clientes_vendas.db`**: Banco de dados SQLite gerado a partir dos arquivos CSV.
- **`requirements.txt`**: Arquivo de dependências Python necessárias para rodar o projeto.

---

## Pré-requisitos

Certifique-se de ter os seguintes pacotes instalados:

- **Python 3.8+**
- **Jupyter Notebook**
- **Pandas**
- **SQLite3**

### Instalação

1. Clone este repositório para o seu diretório local:
   ```bash
   git clone https://github.com/otavioassumpcao/Case__SQL_Python.git

   ```bash
   cd Case__SQL_Python

3. (Opcional) Crie e ative um ambiente virtual:

   ```bash
   python -m venv venv
   .\venv\Scripts\activate  # Windows
   source venv/bin/activate  # macOS/Linux

4. Instale as dependências necessárias a partir do arquivo `requirements.txt`:
   ```bash
   python -m venv venv
   pip install -r requirements.txt


