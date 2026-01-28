### Análise Exploratória: Selic Vs IPCA e Desempenho do E-commerce no Brasil (Olist)
---
Análise de Macroeconomia vs. E-commerce

🛠️ Tecnologias e Bibliotecas Utilizadas

    Pandas & NumPy: Processamento matricial e manipulação de séries temporais.

    Matplotlib & Seaborn: Visualização de tendências e mapas de calor de correlação.

    Python-BCB (SGS & Expectativas): * SGS: Coleta de dados históricos reais (Selic e IPCA).

        Expectativas: Acesso à API do Relatório Focus para capturar a previsão do mercado, permitindo comparar o cenário esperado versus o realizado.

    Scikit-learn (Preprocessing): * StandardScaler: Utilizado para a padronização das features. Como os dados econômicos e de vendas possuem ordens de magnitude muito diferentes, aplicamos o cálculo z=(x−μ)/σ para garantir que cada variável contribua igualmente para o modelo.

📈 Metodologia de Análise

    Coleta de Dados: Integração via API das expectativas de mercado e dados consolidados do Banco Central.

    Tratamento de Escala: Aplicação do StandardScaler para normalizar os dados, permitindo a plotagem comparativa de variáveis distintas no mesmo eixo de análise.

    Análise de Sentimento Econômico: Verificação de como a variação nas expectativas do Focus influencia o volume de novos pedidos na Olist antes mesmo da alteração real nas taxas.
    🛠️ Tecnologias e Bibliotecas Utilizadas

    Pandas & NumPy: Processamento matricial e manipulação de séries temporais.

    Matplotlib & Seaborn: Visualização de tendências e mapas de calor de correlação.

    Python-BCB (SGS & Expectativas): * SGS: Coleta de dados históricos reais (Selic e IPCA).

        Expectativas: Acesso à API do Relatório Focus para capturar a previsão do mercado, permitindo comparar o cenário esperado versus o realizado.

    Scikit-learn (Preprocessing): * StandardScaler: Utilizado para a padronização das features. Como os dados econômicos e de vendas possuem ordens de magnitude muito diferentes, aplicamos o cálculo z=(x−μ)/σ para garantir que cada variável contribua igualmente para o modelo.

Pergunta de Pesquisa

    "De que maneira as variações na taxa básica de juros (Selic) e as expectativas inflacionárias (IPCA) influenciaram o volume de vendas e o comportamento de consumo no marketplace Olist entre 2016 e 2018?"
