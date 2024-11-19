# Desafio de Projeto: Análise de Cartões de Crédito com Azure AI ✨💳

## Visão Geral 🔎

Este projeto foi desenvolvido como parte do Bootcamp Microsoft Azure AI 102 oferecido pela DIO. O objetivo é criar uma API em Python utilizando os recursos do Azure AI para análise de documentos e contas de armazenamento (Storage Account) para identificar os campos de cartões de crédito a partir de imagens e informar se o cartão é válido ou inválido.

## Tecnologias Utilizadas 🧰

- **Azure AI**: Serviço de análise de documentos.
- **Azure Storage Account**: Para armazenamento e recuperação de imagens.
- **Python**: Linguagem de programação principal.
- **Streamlit**: Framework para criação de aplicações web interativas.
- **Bibliotecas Utilizadas**:
  - `azure.core`
  - `azure-ai-documentintelligence`
  - `azure-storage-blob`
  - `streamlit`
  - `python-dotenv`

## Funcionalidades 🎛️

- **Upload de Imagens**: Upload de imagens de cartões de crédito para análise.
- **Análise de Documentos**: Utilização do Azure AI para extrair campos relevantes dos cartões de crédito (número do cartão, data de validade, nome do titular, nome do banco).
- **Validação de Cartões**: Algoritmo para verificar a validade dos cartões de crédito com base nas informações extraídas.
- **Interface Web**: Interface web interativa para upload de imagens e visualização dos resultados da análise.

## Estrutura do Projeto 💻

1. **Configuração do Ambiente**:
    - Configurar variáveis de ambiente usando `python-dotenv`.
    - Instalar dependências listadas no arquivo `requirements.txt`.

2. **Implementação da API**:
    - Desenvolvimento da API em Python utilizando o framework Streamlit.
    - Integração com os serviços do Azure para análise de documentos e armazenamento de blobs.

3. **Processamento e Análise**:
    - Upload das imagens de cartões de crédito para a conta de armazenamento do Azure.
    - Utilização do serviço Azure AI para analisar as imagens e extrair informações dos cartões.
    - Implementação de lógica para verificar a validade dos cartões com base nas informações extraídas.

## Resultados 🎉📑

Os resultados de análise de cartão válido e inválido, podem ser vistos aqui:

[Cartão Válido](./resultados/cartao_valido.jpg)

[Cartão Inválido](./resultados/cartao_invalido.jpg)
