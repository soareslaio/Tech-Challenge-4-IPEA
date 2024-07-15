**Visão Geral**

Este projeto realiza uma análise detalhada dos preços do petróleo Brent e cria um dashboard interativo para apoiar decisões estratégicas no setor petrolífero.

**Dados Utilizados**
- Fonte: IPEA (Instituto de Pesquisa Econômica Aplicada)
- Período: Últimos 10 anos

**Ferramentas Utilizadas**
- Análise e Visualização: Power BI, Python
- Modelagem de Preços: ARIMA, Prophet
- Deploy: Streamlit
  
**Análise Exploratória**
- Variação Diária dos Preços:
- Observação de uma tendência geral de aumento nos últimos meses.
- Picos significativos e quedas ocasionais sugerem volatilidade no mercado de petróleo.

**Média Anual dos Preços:**
- Tendência de alta nos preços médios anuais.
- Valores recentes consistentemente superiores aos anos anteriores.
- Possível indicação de aumento na demanda ou diminuição na oferta de petróleo.

**Distribuição dos Preços (Boxplot):**
- Mediana relativamente alta, indicando metade dos valores acima de um preço significativo.
- Sem Presença de outliers.
**Modelos Utilizados:**
- ARIMA
- Prophet (selecionado pela precisão com menor erro percentual médio absoluto - MAPE de 9,98%)
  
**Deploy do Projeto**

- Plataforma: Streamlit
- **Funcionalidade:** Dashboard interativo para análise e previsão dos preços do petróleo Brent.

**Conclusão**
Este projeto oferece uma visão abrangente das tendências e variações nos preços do petróleo Brent, utilizando ferramentas robustas para análise e visualização de dados, e proporciona previsões precisas para apoiar decisões estratégicas no setor petrolífero.

Link do deploy: https://techchallenge4-emerson-e-laio.streamlit.app/
