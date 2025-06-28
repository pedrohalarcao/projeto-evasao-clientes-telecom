# 📉 Projeto: Análise de Evasão de Clientes de Telecom | G8 ONE - Alura & Oracle

Este projeto foi desenvolvido como parte dos desafios propostos no programa **G8 ONE**, promovido pela **Alura** em parceria com a **Oracle**.

O principal objetivo foi realizar uma **análise exploratória aprofundada** de um conjunto de dados de clientes de telecomunicações para entender os **fatores que influenciam a evasão de clientes**. Com isso, a empresa pode direcionar ações para **reter clientes e aumentar a satisfação**.

---

## 🎯 Objetivos do Projeto

- Realizar uma **análise exploratória de dados (EDA)** em um dataset real
- Identificar padrões e **fatores críticos que levam ao cancelamento de serviços**
- Explorar relações entre variáveis **numéricas e categóricas** com a evasão
- Gerar **insights acionáveis** para estratégias de retenção de clientes

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3.x**
- **Pandas** – para manipulação e análise dos dados
- **Matplotlib** – para criação de gráficos estáticos
- **Seaborn** – para visualizações estatísticas e comparação entre variáveis

---

## 🔍 Etapas da Análise

### 📥 Leitura e Preparação dos Dados

- Importação do conjunto de dados de clientes de telecomunicações
- Limpeza e padronização das variáveis

### 📊 Análise Exploratória

- Visualização da **distribuição da evasão (churn)**
- Exploração da relação entre **Tempo de Contrato (TenureMonths)** e evasão
- Análise dos **Encargos Mensais (MonthlyCharges)** e seu impacto na evasão
- Comparação de diferentes **tipos de contrato, serviços e métodos de pagamento**
- Uso de gráficos de barras, boxplots, histogramas e gráficos de dispersão para revelar padrões

---

## 📌 Principais Insights

A análise revelou que os seguintes fatores estão fortemente associados a uma **maior probabilidade de evasão**:

- 📉 **Tempo de contrato (TenureMonths)** baixo
- 💰 **Encargos mensais (MonthlyCharges)** mais altos
- 📆 **Tipo de contrato**: "Month-to-month"
- 🌐 **Tipo de internet**: "Fiber optic"
- 🚫 **Ausência de serviços adicionais** como segurança online e suporte técnico (OnlineSecurityStatus, TechSupportStatus, etc.)
- 💳 **Método de pagamento**: "Electronic check"

---

## 🧠 Conclusão

> Com base nos dados analisados, é possível concluir que clientes com contratos curtos, maiores custos mensais, sem serviços adicionais e que usam métodos de pagamento eletrônicos estão mais propensos a cancelar seus serviços. A empresa pode **direcionar estratégias de retenção** para esses perfis, como oferecer descontos, upgrades ou planos mais longos com benefícios.


---

## 🚀 Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone git@github.com:pedrohalarcao/projeto-evasao-clientes-telecom.git
   cd projeto-evasao-clientes-telecom


---

## 📝 Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais informações.


