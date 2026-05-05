# Projeto 1 – Análise de Churn em Telecom

**Data:** Abril 2026  
**Autor:** Joyce R. Santos  
**Dataset:** Telco Customer Churn (IBM – Kaggle)

---

## 1. Resumo 
Análise de churn em empresa de telecom com taxa de 26,5% (~1.869 clientes/mês).  
**Resultados principais:**
- Score de risco captura 60% dos cancelamentos analisando apenas 30% da base  
- Contratos mensais e pagamento via electronic check são os maiores fatores de risco  
- Segmento crítico: clientes novos (≤3 meses), gasto alto (>70), sem bundle → 77,7% churn  

---

## 2. Contexto
- **Problema:** reduzir churn sem aumentar custo de aquisição  
- **Objetivo:** identificar fatores críticos e criar score de risco acionável  
- **Métrica de sucesso:** recomendações estratégicas com ROI estimado e score interpretável  

---

## 3. Metodologia
- **Fonte de dados:** 7.043 clientes, 21 variáveis  
- **Processo:** limpeza de dados, feature engineering, análise exploratória, score heurístico  
- **Validação:** correlação point-biserial 0,47 (p<0,001)  

---

## 4. Conclusão
O projeto demonstrou que contratos mensais e pagamentos via electronic check são os principais drivers de churn.  
O score de risco permite segmentar clientes críticos e direcionar ações de retenção com impacto financeiro relevante.  
A abordagem é interpretável, acionável e fornece base sólida para evolução em modelos de machine learning e cálculo de CLV.

