# Data Warehouse e Projeto Analítico

Este projeto demonstra uma solução abrangente de data warehousing e analytics, desde a construção de um data warehouse até a geração de insights acionáveis. 
Projetado como um projeto de portfólio, ele destaca as melhores práticas da indústria em engenharia de dados e análise.

## Arquitetura de Dados
A arquitetura de dados deste projeto segue a Medallion Architecture, com as camadas Bronze, Silver e Gold:
1. Camada Bronze: Armazena os dados brutos exatamente como vêm dos sistemas de origem. Os dados são ingeridos a partir de arquivos CSV para o banco de dados SQL Server.
2. Camada Silver: Inclui processos de limpeza, padronização e normalização dos dados para prepará-los para análise.
3. Camada Gold: Contém os dados prontos para o negócio, modelados em um esquema estrela necessário para relatórios e análises.
