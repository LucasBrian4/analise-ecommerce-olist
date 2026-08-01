# Análise de Vendas — E-commerce (Olist)

Análise exploratória de dados de vendas de um marketplace brasileiro, usando Python (pandas, matplotlib).

## Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

## Como rodar

```bash
pip install -r requirements.txt
jupyter notebook notebooks/analise.ipynb
```

## Dados

Dataset público: [Brazilian E-Commerce (Olist)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Perguntas respondidas

**1. Quais categorias mais faturam?**
Beleza/saúde, relógios/presentes e cama/mesa/banho lideram em faturamento.

![Top categorias](images/top_categorias.png)

**2. Os pedidos chegam no prazo?**
A maioria chega bem antes do estimado (mediana de -12 dias), mas há casos extremos de atraso.

![Distribuição de atraso](images/distribuicao_atraso.png)

**3. Preço influencia a nota de avaliação?**
Não há relação forte — o preço médio é parecido entre todas as notas.

![Preço por nota](images/preco_por_nota.png)

**4. Como as vendas variam ao longo do tempo?**
Crescimento consistente em 2017, com pico em novembro (Black Friday).

![Vendas mensais](images/vendas_mensais.png)
