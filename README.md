# Dashboard de Análise Comercial

## 📊 Sobre o Projeto

Este projeto foi desenvolvido como parte do programa **"Profissional do Futuro"** oferecido pela **Xperiun**. Trata-se de um dashboard analítico completo para monitoramento do desempenho comercial da empresa, com foco em faturamento, margem bruta e performance de vendas.

## 🎯 Objetivo

Criar uma ferramenta estratégica para tomada de decisões comerciais, permitindo:
- Acompanhamento de faturamento e margem bruta
- Identificação dos principais influenciadores de performance
- Análise de desempenho por vendedor e grupo de produto
- Otimização de resultados e crescimento da área comercial

## ⚙️ Funcionalidades Implementadas

### 📈 Métricas Principais
- **Faturamento**: R$ 2,39 BI
- **Margem Bruta**: R$ 404,82 MI
- **Evolução do Faturamento** (2023-2024-2025)
- **Ticket Médio** por vendedor
- **Quantidade de Vendas** por linha de pedido

### 🎨 Regras de Negócio - Metas de Margem Bruta
Implementação de regras condicionais para classificação de desempenho:

| Segmento | Meta de Margem | Status | Cor |
|----------|----------------|--------|-----|
| **Bebidas** | ≥ 18% | Acima/Na Meta | 🟢 Verde |
| **Alimentos** | ≥ 14% | Acima/Na Meta | 🟢 Verde |
| **Outros** | ≥ 14% | Acima/Na Meta | 🟢 Verde |
| **Não Atende** | - | Abaixo da Meta | 🔴 Vermelho |

### 📊 Análises Disponíveis
1. **Dashboard Principal**: Visão geral do desempenho comercial
2. **Principais Influenciadores**: Identificação dos fatores que impactam a margem bruta
3. **Desempenho Comercial**: Detalhamento por vendedor e produto

## 🛠️ Desenvolvimento Técnico

### Medidas Criadas (DAX)
- `Faturamento`
- `Lucro Bruto`
- `Margem Bruta %`
- `Quantidade de Vendas`
- `Quantidade de Itens`
- `Ticket Médio`
- `Custos`
- `Cor Margem Bruta` (condicional para meta)

### Estruturas de Dados
- **Tabela Calendário**: Criada via função `CALENDAR` no DAX para análises temporais
- **Coluna de Classificação**: Nova coluna para categorização da margem ("Acima/Igual à Meta" ou "Abaixo da Meta")

### Funções DAX Utilizadas
- `SUM`
- `SUMX`
- `DIVIDE`
- `SWITCH`
- Operações matemáticas básicas

## 📋 Insights Identificados

### Principais Influenciadores da Margem Bruta
Os grupos de produto que mais influenciam negativamente a margem bruta:
- **Vinho Seco** (1.27x mais probabilidade)
- **Cachaça** (1.20x mais probabilidade)
- **Café** (impacto significativo)

### Distribuição de Vendas
- **Alimentos**: 303Mil (92.24%)
- **Bebidas**: 26Mil (7.76%)

## 🚀 Como Utilizar

1. **Navegação**: Acesse as diferentes páginas do dashboard através do menu
2. **Filtros**: Utilize os filtros disponíveis para segmentar a análise
3. **Detalhamento**: Clique nos gráficos para obter informações mais específicas
4. **Tomada de Decisão**: Utilize os insights para orientar estratégias comerciais

## 👥 Público-Alvo

- Gestores comerciais
- Analistas de performance
- Diretoria executiva
- Equipe de vendas

---

**Desenvolvido como parte do programa Profissional do Futuro - Xperiun**
