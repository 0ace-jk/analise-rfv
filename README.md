# Análise RFV

Este projeto é uma aplicação web desenvolvida com Streamlit para realizar a análise RFV (Recência, Frequência e Valor). A ferramenta permite o upload de dados de transações de clientes para calcular as métricas de recência, frequência e valor, segmentando-os em grupos estratégicos. Além da classificação por quartis (gerando scores como 'AAA', 'DDD'), o sistema sugere ações de marketing e utiliza o algoritmo K-Means para agrupamento (clustering) comparativo.

## Como executar

### Pré-requisitos

Certifique-se de ter o Python instalado em sua máquina.

### Instalação

1. Clone o repositório.
2. Instale as dependências listadas no arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Execução

Para iniciar a aplicação, execute o seguinte comando no terminal:

```bash
streamlit run app_RFV.py
```

A aplicação será aberta automaticamente no seu navegador padrão.
