# Conhecimento Técnico Tributário - Base RAG Valor Fiscal

## 📊 CONHECIMENTO EXTRAÍDO VIA SCRAPING - PARTE 2

### METODOLOGIAS DE RECUPERAÇÃO TRIBUTÁRIA

#### 1. EXCLUSÃO ICMS DA BASE PIS/COFINS (Tema 69 STF)
```yaml
MARCO LEGAL:
- STF RE 574.706 (15/03/2017): ICMS não compõe base PIS/COFINS
- Marco temporal: efeitos a partir de 15/03/2017
- Repercussão geral reconhecida

CÁLCULO PRÁTICO:
- Empresa faturamento R$ 1.000.000/mês
- ICMS 18% + PIS/COFINS 3,65% (cumulativo)
- Recuperação mensal: R$ 6.570
- Potencial 5 anos: R$ 394.200

REQUISITOS:
- Análise documentos fiscais (não apenas somatória destacada)
- Período: março/2017 em diante
- Regime: Lucro Real (não cumulativo) tem maior potencial
```

#### 2. EXCLUSÃO ICMS-ST DA BASE PIS/COFINS (Tema 1125 STJ)
```yaml
MARCO LEGAL:
- STJ Tema 1125: ICMS-ST embutido no preço afeta base PIS/COFINS
- Modulação: efeitos desde 15/03/2017 (mesmo que Tema 69)
- Aplicável mesmo quando ICMS-ST não destacado na NF

CONTEXTO:
- Empresas revendedoras com produtos ICMS-ST
- ICMS-ST fica embutido no preço de venda
- Valor deve ser excluído da base PIS/COFINS

CONSIDERAÇÃO ESPECIAL:
- Regime da Definitividade da ST (ex: Minas Gerais)
- Todo ICMS embutido (próprio + ST) deve ser excluído
```

#### 3. CRÉDITOS PIS/COFINS NÃO-CUMULATIVO
```yaml
OPORTUNIDADES PRINCIPAIS:
- Insumos utilizados na produção
- Energia elétrica no processo produtivo
- Aluguéis de prédios
- Gastos com manutenção de máquinas
- Despesas de logística/transporte
- Fretes sobre vendas

SETORES COM MAIOR POTENCIAL:
- Indústrias (múltiplos insumos)
- Empresas de transporte
- Exportadoras (manutenção créditos)

PRAZO RECUPERAÇÃO:
- 5 anos (prazo decadencial)
- Compensação automática vs restituição
```

#### 4. RECUPERAÇÃO ICMS
```yaml
PRINCIPAIS OPORTUNIDADES:
- Mercadorias devolvidas
- Energia elétrica no processo produtivo
- Serviços de comunicação empresarial
- Operações interestaduais (diferencial alíquotas)
- Substituição tributária incorreta
- Operações de exportação

COMPLEXIDADES:
- Regras variam por estado
- Diferentes alíquotas estaduais
- Necessário controle CIAP (ativo imobilizado)
```

#### 5. RECUPERAÇÃO ISS
```yaml
OPORTUNIDADES:
- Serviços cobrados indevidamente
- Serviços isentos por lei municipal
- Exportação de serviços
- Bitributação ICMS x ISS

ESTRATÉGIA:
- Análise legislação municipal específica
- Identificação serviços não tributáveis
- Revisão local prestação vs local tributação
```

### JURISPRUDÊNCIA CONSOLIDADA

#### STF - Temas de Repercussão Geral
```yaml
TEMA 69 (RE 574.706):
- ICMS não compõe base PIS/COFINS
- Efeitos: fatos geradores após 15/03/2017
- Ressalva: ações judiciais protocoladas antes

TEMA 1.279 (RE 1452421):
- Reafirmação Tema 69
- Esclarecimento sobre marco temporal
- Aplicação só para fatos geradores pós 15/03/2017
```

#### STJ - Recursos Repetitivos
```yaml
TEMA 1125:
- ICMS-ST na base PIS/COFINS
- Modulação: efeitos desde 15/03/2017
- Ampliação prazo recuperação

TEMA 1.223:
- PIS/COFINS compõem base ICMS
- Repasse econômico vs repasse jurídico
- Confirmação entendimento STJ
```

### PROCESSO DE RECUPERAÇÃO (METODOLOGIA PADRÃO)

#### FASE 1: DIAGNÓSTICO FISCAL
```yaml
ANÁLISE 5 ANOS RETROATIVOS:
- Revisão apurações PIS/COFINS/ICMS/ISS
- Análise documental (NFs, livros fiscais)
- Cruzamento obrigações acessórias
- Identificação inconsistências

DOCUMENTOS CHAVE:
- SPED Fiscal
- EFD Contribuições
- ECF (Escrituração Contábil Fiscal)
- Documentos fiscais eletrônicos
- Livros de apuração
```

#### FASE 2: QUANTIFICAÇÃO
```yaml
CÁLCULOS ESPECÍFICOS:
- Exclusão ICMS: análise por documento fiscal
- Créditos PIS/COFINS: segregação por natureza
- ICMS-ST: identificação valor embutido
- ISS: revisão competência tributária

SIMULAÇÕES:
- Cenário administrativo vs judicial
- Compensação vs restituição
- Impacto fluxo de caixa
```

#### FASE 3: PROCEDIMENTOS
```yaml
VIA ADMINISTRATIVA:
- Pedido Eletrônico Restituição (PER)
- Declaração de Compensação (DCOMP)
- Retificação obrigações acessórias

VIA JUDICIAL:
- Ação ordinária
- Mandado de segurança
- Execução contra Fazenda
```

### POTENCIAL POR SETOR

#### INDÚSTRIAS
```yaml
MAIOR POTENCIAL:
- PIS/COFINS sobre insumos
- IPI recuperável
- ICMS energia elétrica
- Créditos bens capital

ESTIMATIVA RECUPERAÇÃO:
- 2-8% do faturamento anual (casos complexos)
- Timeline: 18-36 meses (judicial)
```

#### COMÉRCIO
```yaml
FOCO PRINCIPAL:
- Exclusão ICMS base PIS/COFINS
- ICMS-ST embutido
- Operações interestaduais

ESTIMATIVA RECUPERAÇÃO:
- 1-4% do faturamento anual
- Timeline: 12-24 meses
```

#### SERVIÇOS
```yaml
OPORTUNIDADES:
- ISS sobre serviços não tributáveis
- PIS/COFINS sobre aluguéis
- Exportação serviços

ESTIMATIVA RECUPERAÇÃO:
- 0.5-3% do faturamento anual
- Timeline: 6-18 meses
```

### RISCOS E LIMITAÇÕES

#### ADMINISTRATIVOS
```yaml
PRAZO HOMOLOGAÇÃO:
- 5 anos para RFB revisar compensação
- Declaração = confissão de dívida
- Necessário fundamentação sólida

FISCALIZAÇÃO:
- Possível questionamento posterior
- Exigência documentação completa
- Glosa parcial ou total
```

#### JUDICIAIS
```yaml
CUSTOS PROCESSUAIS:
- Honorários advocatícios
- Custas judiciais
- Perícia contábil

PRAZOS:
- 2-5 anos tramitação média
- Recursos podem estender
- Depósito judicial em alguns casos
```

### TECNOLOGIA E FERRAMENTAS

#### SISTEMAS ESPECIALIZADOS
```yaml
FUNCIONALIDADES ESSENCIAIS:
- Leitura SPED/EFD automática
- Cálculo automatizado exclusões
- Relatórios padronizados
- Simulação cenários

EXEMPLOS MERCADO:
- e-Recuperador (e-Auditoria)
- Sistemas ERP integrados
- Ferramentas específicas RCT
```

### VALOR AGREGADO CONSULTORIA

#### DIFERENCIAIS TÉCNICOS
```yaml
EXPERTISE NECESSÁRIA:
- Conhecimento jurisprudência atualizada
- Domínio legislação federal/estadual/municipal
- Experiência procedimentos RFB/SEFAZ
- Visão estratégica tributária

PROCESSO CONSULTORIA:
1. Diagnóstico inicial gratuito
2. Mapeamento oportunidades
3. Quantificação potencial
4. Execução procedimentos
5. Acompanhamento homologação
```

---

*Conhecimento técnico compilado via scraping múltiplas fontes especializadas*
*Atualizado: 17/06/2025*
*Base para configuração RAG Valor Fiscal*