# Análise de Viagens Públicas (Portal da transparência) - 2024

## Descrição
Este projeto realiza a análise de viagens públicas em 2024, utilizando dados extraídos do Portal da Transparência. 
O objetivo é explorar as despesas associadas às viagens de diferentes cargos públicos, identificando padrões e insights.

## Dependências
- Python 3.x
- Pandas
- Matplotlib
- OpenPyXL

## Estrutura do Código
1. **Leitura dos Dados**: Carregamento dos arquivos CSV contendo informações sobre viagens e passagens.
2. **Tratamento dos Dados**:
   - Preenchimento de valores nulos.
   - Conversão de datas.
   - Criação de novas colunas, como mês da viagem e duração.
3. **Análises Estatísticas**:
   - Cálculo de despesas totais e médias por cargo.
   - Identificação de cargos com maior proporção de viagens.
   - Consolidação de informações relevantes.
4. **Visualização**:
   - Gráficos de barras para número de viagens por cargo.
   - Scatter plot para identificar discrepâncias nos gastos.
5. **Exportação**:
   - Geração de um arquivo Excel consolidado para futuras análises.

## Uso
Execute o script em um ambiente Python configurado com as bibliotecas necessárias. Certifique-se de atualizar os caminhos dos arquivos conforme a 
estrutura do seu diretório.

```python
import pandas as pd
import matplotlib.pyplot as plt

# Código principal para análise de viagens
```

## Fonte dos Dados
Os dados foram extraídos do **Portal da Transparência**, garantindo uma análise baseada em informações oficiais.

## Autor
Este projeto foi desenvolvido para fins de transparência e análise de dados públicos. Sinta-se à vontade para contribuir e aprimorar as análises!

---
