# Projeto-EngDados-Analise-Instagram-Influencer

## Descrição

Este projeto visa coletar dados de um perfil específico no Instagram usando a **Instagram Scraper API3** da **RapidAPI**. O objetivo é obter informações sobre postagens e interações, que serão analisadas para avaliar o desempenho do perfil. O projeto foi desenvolvido para fornecer insights detalhados sobre o perfil do Marcito Castro.

## Etapas do Projeto

### Coleta de Dados com API do Instagram

- **Utilização da API Instagram Scraper**: Coleta de dados do perfil do Marcito Castro.
- **Informações Extraídas**:
  - **Fotografias do Perfil**: Imagens do perfil, com uma requisição por dia.
  - **Últimas 24 Postagens**: Informações gerais das últimas 24 postagens, com duas requisições por dia.
  - **Última Postagem**: Detalhes da última postagem, incluindo comentários e dados gerais, com 17 requisições por dia.
- **Autenticação**: Utilização da variável `x-rapidapi-key` para autenticação, configurada no Google Colab.

### Processamento dos Dados

- **Armazenamento e Processamento**:
  - Dados extraídos são processados usando bibliotecas como `Pandas` e `PySpark` para análise.
  - Métricas analisadas incluem engajamento, crescimento de seguidores, e tipos de conteúdo.

### Exportação dos Dados

- **Exportação para Google Sheets**:
  - As métricas essenciais são exportadas para uma planilha do Google Sheets para facilitar a análise.

## Como Usar

1. **Obtenha os Dados via API**:
   - Instale as bibliotecas necessárias: `requests`, `pyspark`, `pandas` (`pip install requests pyspark pandas`).
   - Configure as credenciais da API do Instagram usando sua `x-rapidapi-key`.
   - Execute o script para coletar e processar os dados.

2. **Conecte ao Google Sheets**:
   - Exporte os dados processados para uma planilha do Google Sheets usando a API do Google.
   - Configure as credenciais de acesso à API do Google.

## Links Importantes

- **Código no Google Colab**: [Link para o Colab](#)
- **Apresentação PowerPoint**: [Link para a Apresentação](#)

## Considerações Finais

Este projeto fornece uma abordagem prática para a coleta e análise de dados de perfis do Instagram, oferecendo insights valiosos sobre o desempenho do perfil de Marcito Castro. Ele permite uma visualização clara das métricas e facilita a análise das interações e tendências.
