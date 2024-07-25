## projeto-scraping-mercadolivre
 
Este projeto utiliza Python, Scrapy, SQLite3 e Streamlit para a coleta, transformação e visualização dos principais KPis dos dados referente ao site: https://lista.mercadolivre.com.br/tenis-corrida-masculino.

# Arquitetura do Projeto

![image](https://github.com/user-attachments/assets/648adfff-5ba4-4f56-9425-8ea8aeb52cb2)


#  Extração de Dados com Scrapy:
Utiliza o framework Scrapy para realizar a extração de dados de tênis disponíveis no Mercado Livre.
O Spider criado navega pelas páginas de busca, extrai informações como título, marca, preço, informações de avaliação de produto e link para detalhes.

# Transformação de Dados com Pandas:
Os dados extraídos são processados e limpos utilizando Pandas para melhor análise e armazenamento.
Exemplos de transformações incluem a conversão de formatos de preço e tratamento de dados faltantes.

# Armazenamento em SQLite:
Utiliza SQLite3 para criar um banco de dados local.
Os dados limpos são inseridos no banco SQLite, permitindo consultas e análises futuras.

# Visualização de Dados com Streamlit:
Cria uma interface interativa utilizando Streamlit.
A interface permite visualizar os principais KPIs dos dados coletados.
