# 🎮 Xbox Game Subscriptions Sales — Dashboard de Vendas Xbox

## 📊 Dashboard de Apuração de Vendas Xbox com Excel & BI

Dashboard executivo desenvolvido como projeto do curso da **DIO**, utilizando análise de dados, métricas de assinaturas, visualizações gráficas e inteligência de negócios para acompanhamento e apuração das vendas de serviços e passes de temporada do ecossistema **Xbox**.

---

## 📊 Sobre o projeto

O projeto consolida dados transacionais de assinantes em um painel executivo e interativo, permitindo analisar o volume de vendas, faturamento por tipo de assinatura (*Annual*, *Monthly*, *Quarterly*), adesão aos passes adicionais (*EA Play Season Pass* e *Minecraft Season Pass*) e a distribuição da renovação automática (*Auto Renewal*).

A solução foi estruturada para facilitar a tomada de decisão gerencial no segmento de jogos e serviços por assinatura, unindo **KPIs dinâmicos, segmentadores de dados (slicers) e tabelas dinâmicas de suporte**.

---

## 🎯 Objetivo

Transformar uma base de dados analítica de assinantes do Xbox em uma ferramenta de apuração de vendas intuitiva, capaz de gerar métricas claras de desempenho comercial e comportamento de renovação de contratos.

---

## 🚀 Principais funcionalidades

* **Segmentação por Tipo de Assinatura (*Slicers*):** Filtro interativo no menu lateral para alternar entre planos *Annual*, *Monthly* e *Quarterly*;
* **KPI Card — Total EA Play Season Pass:** Métrica consolidada do faturamento gerado pelo passe de temporada EA Play;
* **KPI Card — Total Minecraft Season Pass:** Métrica dinâmica da receita obtida com os passes de temporada do Minecraft;
* **Análise Visual de Renovação Automática (Xbox Game Pass):** Gráfico de barras horizontais comparando a receita total proveniente de assinaturas com renovação ativa (*Yes*) versus inativa (*No*);
* **Acompanhamento de Período e Atualização:** Cabeçalho com indicativo do período de apuração e carimbo de data/hora do relatório;
* **Menu Lateral Customizado (*Sidebar*):** Interface inspirada na identidade visual oficial do Xbox com saudação personalizada.

---

## 📈 Indicadores Analisados

A dashboard apresenta indicadores operacionais e financeiros estratégicos:

* **Faturamento EA Play Season Pass:** Receita total gerada em acoplados EA Play;
* **Faturamento Minecraft Season Pass:** Volume financeiro gerado em passes adicionais do Minecraft;
* **Receita de Assinaturas Xbox Game Pass:** Distribuição financeira total com base na cobrança recorrente e fidelização (*Auto Renewal: Yes/No*);
* **Comportamento por Plano e Frequência:** Mapeamento de vendas categorizadas por tipo de contrato (*Annual*, *Monthly*, *Quarterly*).

---

## 🖼️ Demonstração

### Tela de Apuração de Vendas

![Apuração de Vendas Xbox](apuracao_vendas.png)

---

## 🗂️ Estrutura do projeto

```text
dashboard_xbox_sales/
│
├── Dashboard de Vendas do Xbox.xlsx
├── apuracao_vendas.png
└── README.md
