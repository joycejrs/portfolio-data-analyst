# Projeto 1 – Análise de Churn em Telecom

## Visão Geral
- Problema: Churn de 26,5% (~1.869 clientes/mês)  
- Objetivo: Identificar fatores críticos e criar um score de risco para retenção  
- Impacto: Score captura 60% dos cancelamentos analisando apenas 30% da base de clientes  

---

## Principais Insights
- Contrato mensal → 42,7% churn (15x maior que contratos longos)  
- Pagamento via electronic check → 45,3% churn vs 15,2% no cartão  
- Segmento crítico: clientes novos (≤3 meses), gasto alto (>70), sem bundle → 77,7% churn  

---

## Recomendações
1. Migrar contratos mensais → desconto de 10% → impacto estimado: -11% churn  
2. Incentivar débito automático/cartão → crédito de $10 → impacto estimado: -8% churn  
3. Intervenção emergencial → bundle grátis por 2 meses → impacto estimado: -5% churn  

---

## Impacto Financeiro Estimado
| Cenário   | Redução de Churn | Clientes Retidos/ano | Economia Anual* |
|-----------|------------------|----------------------|-----------------|
| Otimista  | -15%             | +280                 | ~$330.000       |
| Realista  | -11%             | +206                 | ~$240.000       |
| Pessimista| -8%              | +150                 | ~$175.000       |

\* Ticket médio: $70/mês  

---

## Tecnologias
- Python 3.8+  
- Pandas / NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Git / GitHub  


Data da análise: Abril/2026  
Autor: Joyce  
Dataset: Telco Customer Churn (IBM – Kaggle)  
