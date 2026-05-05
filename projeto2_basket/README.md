# Relatório Técnico: Market Basket Analysis - Instacart

**Data:** Maio 2026  
**Autor:** Joyce R. Santos  
**Dataset:** Instacart Market Basket Analysis (Kaggle)

---

## 1. Resumo
Análise de 3,4 milhões de pedidos para identificar produtos comprados juntos e criar bundles estratégicos.  
**Resultados principais:**
- 1.211 pares de produtos com forte associação
- 3 bundles prontos para implementação
- Produtos orgânicos com maior Lift (até 7.09)
- Potencial de aumento de 15-20% no ticket médio

---

## 2. Contexto
- **Problema:** aumentar ticket médio sem elevar custo de aquisição  
- **Objetivos:** identificar produtos complementares, criar bundles e recomendações de layout  
- **Métricas de sucesso:** Lift > 1.5, Confidence > 15%, 3 bundles acionáveis  

---

## 3. Metodologia
- **Fonte de dados:** 3 arquivos (orders, products, order_products_prior)  
- **Amostra:** 10.000 pedidos → 101.404 transações  
- **Estatísticas:** média de 10 itens/pedido, máximo 80  
- **Algoritmo:** análise de co-ocorrência (Support, Confidence, Lift)  
- **Processamento:** amostragem, top 50 produtos, cálculo de pares, ranking por Lift  

---

## 4. Conclusão
A análise revelou padrões claros de compra conjunta e bundles com alto potencial de impacto comercial.  
O resultado fornece base prática para estratégias de retenção e aumento de receita no e-commerce de supermercado.
