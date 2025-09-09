# 📊 DioInvest – Simulador de FIIs

Este projeto é uma planilha em Excel para simulação de investimentos em Fundos Imobiliários (FIIs), permitindo ao usuário calcular a **alocação de carteira por perfil de investidor**, projetar o **patrimônio acumulado** ao longo do tempo e estimar os **dividendos mensais**.

---

## 🚀 Funcionalidades
- Seleção de perfil de investidor (**Conservador, Moderado, etc.**).
- Alocação automática em FIIs: **Papel, Tijolo, Híbridos e FOFs**.
- Cálculo do **valor total investido por categoria**.
- Simulação de **crescimento patrimonial** com rendimento mensal.
- Estimativa de **dividendos mensais** a partir do Dividend Yield anual.
- Dashboard interativo na aba **APP**.

---

## 📂 Estrutura da Planilha
- **APP** → Interface principal de simulação, onde o usuário insere valores e vê os resultados.
- **Planilha2** → Matriz de alocação de percentuais por perfil de investidor.

---

## 🧮 Fórmulas Utilizadas
- **Alocação por categoria**
  ```
  Valor_Total × Percentual
  ```
- **Patrimônio acumulado**
  ```
  Valor_Anterior × (1 + Taxa_Mensal)
  ```
- **Dividendos mensais**
  ```
  Patrimônio × (Dividend_Yield_Anual ÷ 12)
  ```

---

## 📖 Exemplo de Uso
Se um investidor aplicar **R$ 100.000,00** no perfil **Conservador**:

- Papel (30%) → R$ 30.000  
- Tijolo (50%) → R$ 50.000  
- Híbridos (10%) → R$ 10.000  
- FOFs (10%) → R$ 10.000  

Com **rendimento de 0,8% ao mês** e **dividend yield de 10% ao ano**:
- Patrimônio mês 1 = R$ 100.800  
- Dividendos mês 1 = R$ 833  

---

## ⚠️ Pontos de Atenção
- Atualize sempre as taxas de rendimento e dividend yield de acordo com o mercado.  
- Não altere a aba **Planilha2** sem conhecimento técnico.  
- Use a aba **APP** como interface principal de simulação.  

---

## 📌 Histórico de Alterações
- v1.0 – 09/09/2025 – Criação inicial do simulador e documentação.
