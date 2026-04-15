# Projeto: Sistema de Fluxo de Caixa e Análise de Viabilidade (VPL/Payback)

## 📌 Sobre o Projeto
Este projeto consiste no desenvolvimento de uma ferramenta de análise financeira voltada para a avaliação de projetos de investimento. O objetivo principal é transformar dados brutos de receitas e despesas em indicadores de decisão, permitindo identificar se um investimento é lucrativo e em quanto tempo o capital retornará.

## 🚀 Funcionalidades Principais
* **Estruturação de Fluxo de Caixa:** Organização cronológica de Entradas (Receitas) e Saídas (Custos, Despesas, Impostos).
* **Cálculo de Indicadores de Viabilidade:**
    * **VPL (Valor Presente Líquido):** Cálculo da riqueza gerada pelo projeto a valor presente.
    * **Payback Simples e Descontado:** Determinação do tempo de recuperação do investimento.
* **Modelagem de Amortização:** Integração com sistemas **SAC** e **Price** para previsão de parcelas de financiamento.

## 📊 Fundamentação Matemática
Para garantir a precisão dos resultados, o projeto utiliza as seguintes lógicas financeiras:

### 1. Valor Presente Líquido (VPL)
O VPL traz todos os valores futuros para o valor de hoje, descontando a taxa de juros (TMA). 
**Fórmula:**
`VPL = [Somatório de (FCt / (1 + i)^t)] - Investimento Inicial`

* **FCt:** Fluxo de caixa no período (t).
* **i:** Taxa de desconto ou TMA (Taxa Mínima de Atratividade).
* **t:** Período de tempo.
* **Investimento Inicial:** Capital aportado no início do projeto.

### 2. Payback Descontado
Diferente do payback simples, o descontado considera a desvalorização do dinheiro ao longo do tempo através do Valor Presente (VP):
`VP = Fluxo de Caixa / (1 + i)^t`

O sistema acumula esses valores até que o investimento inicial seja totalmente recuperado.

## 🛠️ Tecnologias Utilizadas
Como estudante de **Análise e Desenvolvimento de Sistemas (ADS)**, utilizei as seguintes competências neste projeto:
* **Lógica de Programação:** Automação de cálculos financeiros.
* **Excel Avançado / VBA:** Interface interativa e processamento de dados.
* **SQL:** Estruturação para armazenamento de dados financeiros (Opcional/Implementado).

## 📂 Como Utilizar
1. Insira o **Investimento Inicial** e a **TMA**.
2. Preencha as projeções de **Receitas** e **Custos**.
3. O sistema processará automaticamente os impostos e gerará o relatório de viabilidade.

---
Documentação gerada para fins acadêmicos e portfólio profissional.
