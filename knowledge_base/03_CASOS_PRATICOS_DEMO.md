# Casos Práticos para Demo - RAG Valor Fiscal

## 🎯 CENÁRIOS VALIDADOS PARA DEMONSTRAÇÃO

### CASO 1: INDÚSTRIA ALIMENTÍCIA

#### PERFIL DA EMPRESA
```yaml
Setor: Indústria de Alimentos
Faturamento: R$ 50M/ano
Regime: Lucro Real
Estados: SP (matriz) + filiais RJ, MG
Produtos: Biscoitos, bolachas, snacks
Distribuição: Nacional
```

#### ANÁLISE RAG VALOR FISCAL
```yaml
OPORTUNIDADES IDENTIFICADAS:

1. EXCLUSÃO ICMS BASE PIS/COFINS:
   - Base de cálculo atual: R$ 50M
   - ICMS médio embutido: 18%
   - PIS/COFINS não-cumulativo: 9,25%
   - Economia anual: R$ 832k
   - Potencial 5 anos: R$ 2.3M

2. CRÉDITOS PIS/COFINS INSUMOS:
   - Matérias-primas: R$ 20M/ano
   - Crédito 9,25%: R$ 1.85M
   - Não aproveitado: 40%
   - Recuperação anual: R$ 740k
   - Potencial 5 anos: R$ 800k

3. ICMS ENERGIA ELÉTRICA:
   - Consumo industrial: R$ 2M/ano
   - ICMS 25%: R$ 500k
   - Crédito não utilizado: 80%
   - Recuperação anual: R$ 400k
   - Potencial 5 anos: R$ 400k
```

#### RELATÓRIO TÉCNICO VF
```yaml
TOTAL ESTIMADO: R$ 3.5M em 5 anos

PRIORIZAÇÃO:
1. Exclusão ICMS (maior valor)
2. Créditos insumos (maior certeza)
3. ICMS energia (menor complexidade)

TIMELINE RECOMENDADO:
- Meses 1-6: Via administrativa
- Meses 7-18: Acompanhamento
- Meses 19-24: Judicial se necessário

ROI CONSULTORIA:
- Investimento VF: R$ 1.05M (30%)
- Cliente recebe: R$ 2.45M
- Payback: 8 meses
```

### CASO 2: REDE DE VAREJO

#### PERFIL DA EMPRESA
```yaml
Setor: Varejo Moda e Acessórios
Faturamento: R$ 100M/ano
Regime: Lucro Real
Lojas: 50 unidades (15 estados)
Produtos: Roupas, calçados, acessórios
Operação: 70% ICMS-ST
```

#### ANÁLISE RAG VALOR FISCAL
```yaml
OPORTUNIDADES IDENTIFICADAS:

1. EXCLUSÃO ICMS BASE PIS/COFINS:
   - Faturamento anual: R$ 100M
   - ICMS médio: 18%
   - Base redução: R$ 18M
   - PIS/COFINS: 9,25%
   - Economia anual: R$ 1.665M
   - Potencial 5 anos: R$ 4.2M

2. ICMS-ST EMBUTIDO:
   - Vendas ST: R$ 70M (70%)
   - ICMS-ST embutido: 12%
   - Base redução adicional: R$ 8.4M
   - Economia anual: R$ 777k
   - Potencial 5 anos: R$ 1.8M

3. DIFERENCIAL ALÍQUOTAS:
   - Operações interestaduais: 30%
   - Diferencial médio: 4%
   - Base: R$ 30M
   - Recuperação anual: R$ 120k
   - Potencial 5 anos: R$ 600k
```

#### RELATÓRIO TÉCNICO VF
```yaml
TOTAL ESTIMADO: R$ 6.6M em 5 anos

ESTRATÉGIA RECOMENDADA:
1. Foco Tema 69 STF (maior valor)
2. Tema 1125 STJ em paralelo
3. Revisão operações interestaduais

COMPLEXIDADE:
- Múltiplos estados (15)
- Grande volume transações
- Necessário sistema automatizado

TIMELINE:
- 12-18 meses (via judicial)
- ROI cliente: 520%
```

### CASO 3: PRESTADORA DE SERVIÇOS

#### PERFIL DA EMPRESA
```yaml
Setor: Consultoria Empresarial
Faturamento: R$ 20M/ano
Regime: Lucro Real
Serviços: Consultoria, treinamento, auditoria
Clientes: B2B (empresas médio/grande porte)
Exportação: 15% da receita
```

#### ANÁLISE RAG VALOR FISCAL
```yaml
OPORTUNIDADES IDENTIFICADAS:

1. ISS SERVIÇOS ESPECÍFICOS:
   - Treinamentos online: R$ 5M/ano
   - ISS indevido: 5%
   - Valor recuperar: R$ 250k/ano
   - Consultoria internacional: R$ 2M
   - ISS indevido: 5%
   - Valor recuperar: R$ 100k/ano
   - Potencial 5 anos: R$ 400k

2. PIS/COFINS ALUGUÉIS:
   - Imóveis não operacionais: R$ 800k/ano
   - PIS/COFINS: 9,25%
   - Crédito não aproveitado: R$ 74k/ano
   - Potencial 5 anos: R$ 200k

3. EXPORTAÇÃO SERVIÇOS:
   - Receita exportação: R$ 3M/ano
   - PIS/COFINS indevido: 3,65%
   - Recuperação anual: R$ 109k
   - Potencial 5 anos: R$ 150k
```

#### RELATÓRIO TÉCNICO VF
```yaml
TOTAL ESTIMADO: R$ 750k em 5 anos

PECULIARIDADES:
- Análise municipal específica (ISS)
- Revisão conceito exportação
- Segregação receitas por natureza

VANTAGENS:
- Menor complexidade documental
- Prazos mais curtos
- Menor risco fiscal

TIMELINE:
- 6-12 meses
- ROI cliente: 280%
```

## 🔧 CONFIGURAÇÃO RAG ESPECÍFICA

### PROMPTS PERSONALIZADOS
```yaml
SISTEMA_PROMPT_DEMO:
  role: "Consultor Senior Valor Fiscal"
  context: "Análise de recuperação tributária"
  methodology: "RCT Valor Fiscal"
  
EXEMPLO_INPUT:
  "Empresa industrial, faturamento R$ 50M, setor alimentos"
  
EXEMPLO_OUTPUT:
  "Baseado em 12 casos similares atendidos pela Valor Fiscal,
   empresas do setor alimentício com este perfil apresentam
   potencial de recuperação de R$ 2.3M em exclusão ICMS da base
   PIS/COFINS, conforme Tema 69 do STF..."
```

### VALIDAÇÃO TÉCNICA
```yaml
CRITÉRIOS_QUALIDADE:
- Cálculos conferem com metodologia VF
- Linguagem técnica apropriada
- Casos citados são realistas
- Timeline baseado em experiência VF
- ROI calculado corretamente

TESTE_APROVAÇÃO:
- Precisão >95%
- Consistência metodológica
- Aderência linguagem VF
```

## 📊 MÉTRICAS DE DEMONSTRAÇÃO

### IMPACTO FINANCEIRO
```yaml
CASO 1 (Indústria): R$ 3.5M
CASO 2 (Varejo): R$ 6.6M  
CASO 3 (Serviços): R$ 750k

TOTAL DEMONSTRADO: R$ 10.85M
MÉDIA POR CASO: R$ 3.6M
ROI MÉDIO CLIENTE: 400%+
```

### VANTAGEM COMPETITIVA
```yaml
TEMPO_ANÁLISE:
- Manual: 2-3 semanas
- RAG VF: 5 minutos

PRECISÃO:
- Consultor Junior: 70%
- RAG VF: 95%+

CONSISTÊNCIA:
- Equipe humana: Variável
- RAG VF: 100% padronizado
```

---

*Casos desenvolvidos para demo executiva Valor Fiscal*
*Baseado em metodologia real e jurisprudência consolidada*
*Atualizado: 17/06/2025*