# # Projeto Final - Análise de Dados de E-commerce

## Descrição do Projeto
Este projeto realiza uma análise abrangente de dados de e-commerce, utilizando PySpark para processamento e visualização de dados. O objetivo é extrair insights valiosos sobre vendas, clientes, pagamentos e avaliações para auxiliar na tomada de decisões estratégicas.

## Objetivos
- Analisar o comportamento de vendas ao longo do tempo.
- Calcular métricas como ticket médio e tempo de entrega.
- Identificar preferências de pagamento dos clientes.
- Avaliar a satisfação dos clientes com base em reviews.
- Visualizar a distribuição geográfica dos clientes.

## Principais Análises Realizadas
1. **Ticket Médio**: Cálculo do valor médio gasto por compra.
2. **Tempo de Entrega**: Análise do tempo entre a compra e a entrega.
3. **Métodos de Pagamento**: Distribuição das vendas por tipo de pagamento.
4. **Avaliações**: Média e variância das avaliações por mês/ano.
5. **Distribuição Geográfica**: Mapa de calor mostrando a concentração de clientes por região.

## Tecnologias Utilizadas
- **PySpark**: Para processamento distribuído de dados.
- **Matplotlib/Plotly**: Para visualização de dados.
- **Pandas**: Para manipulação de dados em DataFrames.

## Como Executar o Projeto
1. **Pré-requisitos**:
   - Python 3.x
   - PySpark
   - Bibliotecas: matplotlib, plotly, pandas

2. **Instalação**:
   ```bash
   pip install pyspark matplotlib plotly pandas
   ```

3. **Execução**:
   - Execute o notebook `ProjetoFinal.ipynb` em um ambiente compatível com Jupyter.

## Estrutura do Código
- **Importação de Bibliotecas**: Configuração do Spark e importação de funções necessárias.
- **Leitura de Dados**: Carregamento dos datasets de clientes, geolocalização, pedidos, pagamentos, etc.
- **Processamento**:
  - Limpeza e transformação de dados.
  - Cálculo de métricas (ticket médio, tempo de entrega).
  - Agregações por período e método de pagamento.
- **Visualização**:
  - Gráfico de pizza para métodos de pagamento.
  - Mapa de calor para distribuição geográfica.

## Principais Conclusões
- **Cartão de crédito** é o método de pagamento mais utilizado.
- **São Paulo (SP)** e **Rio de Janeiro (RJ)** concentram a maior quantidade de clientes.
- As avaliações médias são estáveis, com variações sazonais.

## Autor
Breno Rabelo

## Licença
Este projeto é de uso livre para fins educacionais.
