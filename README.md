# Desafio-AluraOne_01_Data_Science
Entrega do Desafio 01 - Alura / One - Data Science

## Relatório para Decisão de Venda de Loja

Com base nas análises realizadas, apresentamos um resumo dos principais indicadores de cada loja para auxiliar na decisão de qual unidade considerar para venda.

### 1. Faturamento Total:

*   **Loja 1:** R$${faturamento_total_loja1:.2f}
*   **Loja 2:** R$${faturamento_total_loja2:.2f}
*   **Loja 3:** R$${faturamento_total_loja3:.2f}
*   **Loja 4:** R$${faturamento_total_loja4:.2f}

A Loja 1 apresenta o maior faturamento total, enquanto a Loja 4 tem o menor.

### 2. Vendas por Categoria:

Conforme a tabela abaixo, é possível observar a performance de cada categoria em cada loja:

${vendas_por_categoria_total.to_markdown()}

Eletrônicos e eletrodomésticos são as categorias que mais contribuem para o faturamento em todas as lojas. É importante analisar a participação de cada categoria no faturamento individual de cada loja para entender as forças e fraquezas de cada uma.

### 3. Média de Avaliação das Lojas:

*   **Loja 1:** ${media_avaliacao_loja1:.2f}
*   **Loja 2:** ${media_avaliacao_loja2:.2f}
*   **Loja 3:** ${media_avaliacao_loja3:.2f}
*   **Loja 4:** ${media_avaliacao_loja4:.2f}

As médias de avaliação são relativamente próximas entre as lojas, com a Loja 3 apresentando a maior média e a Loja 1 a menor.

### 4. Frete Médio por Loja:

*   **Loja 1:** R$${media_frete_loja1:.2f}
*   **Loja 2:** R$${media_frete_loja2:.2f}
*   **Loja 3:** R$${media_frete_loja3:.2f}
*   **Loja 4:** R$${media_frete_loja4:.2f}

A Loja 4 possui o menor frete médio, o que pode indicar uma maior eficiência logística ou localização geográfica estratégica para redução de custos de envio.

### 5. Produtos Mais e Menos Vendidos (Geral e por Loja):

Analisamos os produtos mais e menos vendidos tanto no geral quanto individualmente por loja (vide outputs das células anteriores). Esta análise é crucial para entender o mix de produtos de cada loja e identificar possíveis produtos de baixo desempenho que podem impactar o resultado.

---

### Considerações para a Decisão de Venda:

Ao decidir qual loja vender, vários fatores devem ser ponderados:

*   **Faturamento:** Embora a Loja 1 tenha o maior faturamento, é importante analisar a lucratividade líquida de cada loja, considerando todos os custos operacionais.
*   **Performance por Categoria:** Uma loja com faturamento menor, mas com alta performance em categorias estratégicas ou de alta margem, pode ser mais valiosa a longo prazo.
*   **Avaliação dos Clientes:** Lojas com melhor avaliação podem ter maior fidelização de clientes e menor custo de aquisição de novos clientes.
*   **Custos Operacionais (incluindo Frete):** Lojas com menores custos operacionais podem ser mais lucrativas, mesmo com faturamento menor.
*   **Potencial de Crescimento:** Avaliar o mercado local e o potencial de crescimento de cada loja é fundamental.

**Com base apenas nos dados analisados (faturamento, vendas por categoria, avaliação e frete), a Loja 4 apresenta o menor faturamento total e o menor frete médio. No entanto, a decisão de venda deve ser tomada considerando uma análise financeira mais aprofundada, incluindo lucratividade, custos fixos e variáveis, além de fatores estratégicos e de mercado.**

Sugere-se uma análise mais detalhada da lucratividade de cada loja e do potencial de mercado antes de tomar a decisão final.
