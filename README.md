# Projeto: Case de SQL e Python

Este projeto foi desenvolvido como parte de um processo seletivo para estágio, com o objetivo de demonstrar habilidades em **SQL** e **Python**. Ele inclui a manipulação de dados utilizando **Pandas** e consultas **SQL**, além de um fluxo de registro de vendas e clientes.

## Funcionalidades

- Registro de clientes e vendas.
- Verificação e atualização automática de clientes existentes no sistema.
- Exibição do saldo total de um cliente (somatório das vendas).
- Manipulação de dados usando **Pandas** e **SQLite**.

---

## Estrutura do Projeto

- **`cliente.py`**: Contém a classe `Cliente`, que gerencia o registro de vendas, adição de novos clientes e exibição de saldo.
- **`vendas.csv`** e **`clientes.csv`**: Arquivos CSV que armazenam as informações iniciais dos clientes e suas vendas.
- **Jupyter Notebooks**: Arquivos `.ipynb` utilizados para a execução do código e manipulação de dados.

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
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio

2. (Opcional) Crie e ative um ambiente virtual:

   ```bash
   python -m venv venv
   .\venv\Scripts\activate  # Windows
   source venv/bin/activate  # macOS/Linux

3. Instale as dependências necessárias a partir do arquivo `requirements.txt`:
       ```bash
   python -m venv venv
   pip install -r requirements.txt


