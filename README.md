# PDF Query Project

Este projeto utiliza Jupyter Notebooks para realizar consultas em documentos PDF, integrando tecnologias como Astra DB e OpenAI.

## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado:

- [Python 3.x](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/) ou VS Code com extensão Jupyter

## Configuração

1.  **Clone o repositório** (se aplicável) ou navegue até a pasta do projeto.

2.  **Instale as dependências**:
    Utilize o arquivo `requirements.txt` para instalar as bibliotecas necessárias.

    ```bash
    pip install -r requirements.txt
    ```

3.  **Configuração de Variáveis de Ambiente**:
    O projeto requer chaves de API para o Astra DB e OpenAI.
    
    Crie um arquivo `.env` na raiz do projeto baseando-se no arquivo de exemplo [.env.example](.env.example). O arquivo deve conter as seguintes chaves:

    ```env
    ASTRA_DB_APPLICATION_TOKEN="seu_token_astra_db"
    ASTRA_DB_ID="seu_id_astra_db"
    OPENAI_API_KEY="sua_chave_openai"
    ```

    > **Nota:** Nunca compartilhe seu arquivo `.env` publicamente.

## Como Usar

1.  Abra o arquivo [pdfquery.ipynb](pdfquery.ipynb) no seu editor de preferência (Jupyter Lab, Jupyter Notebook ou VS Code).
2.  Execute as células sequencialmente para carregar as configurações e realizar as consultas nos PDFs.

## Estrutura do Projeto

- `// filepath: c:\Users\OlavoDefendiDalberto\Projetos\pdf-query\README.md
# PDF Query Project

Este projeto utiliza Jupyter Notebooks para realizar consultas em documentos PDF, integrando tecnologias como Astra DB e OpenAI.

## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado:

- [Python 3.x](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/) ou VS Code com extensão Jupyter

## Configuração

1.  **Clone o repositório** (se aplicável) ou navegue até a pasta do projeto.

2.  **Instale as dependências**:
    Utilize o arquivo `requirements.txt` para instalar as bibliotecas necessárias.

    ```bash
    pip install -r requirements.txt
    ```

3.  **Configuração de Variáveis de Ambiente**:
    O projeto requer chaves de API para o Astra DB e OpenAI.
    
    Crie um arquivo `.env` na raiz do projeto baseando-se no arquivo de exemplo [.env.example](.env.example). O arquivo deve conter as seguintes chaves:

    ```env
    ASTRA_DB_APPLICATION_TOKEN="seu_token_astra_db"
    ASTRA_DB_ID="seu_id_astra_db"
    OPENAI_API_KEY="sua_chave_openai"
    ```

    > **Nota:** Nunca compartilhe seu arquivo `.env` publicamente.

## Como Usar

1.  Abra o arquivo [pdfquery.ipynb](pdfquery.ipynb) no seu editor de preferência (Jupyter Lab, Jupyter Notebook ou VS Code).
2.  Execute as células sequencialmente para carregar as configurações e realizar as consultas nos PDFs.

## Estrutura do Projeto

- `pdfquery.ipynb`: Notebook principal contendo a lógica de consulta.
- `.env`: Arquivo de configuração local (não versionado).
- `.env.example`: Modelo para as variáveis de ambiente necessárias.
- `requirements.txt`: Lista de dependências do Python.