# 📊 DioInvest – Simulador de FIIs

Este projeto é uma planilha em Excel para simulação de investimentos em Fundos Imobiliários (FIIs), permitindo ao usuário calcular a **alocação de carteira por perfil de investidor**, projetar o **patrimônio acumulado** ao longo do tempo e estimar os **dividendos mensais**.

---

## 🚀 Funcionalidades

* Seleção de perfil de investidor (**Conservador, Moderado, Agressivo, etc.**) via lista suspensa.
* Alocação automática em FIIs: **Papel, Tijolo, Híbridos e FOFs**.
* Cálculo do **valor total investido por categoria**.
* Simulação de **crescimento patrimonial** com rendimento mensal.
* Estimativa de **dividendos mensais** a partir do Dividend Yield anual.
* Dashboard interativo na aba **APP**.

---

## 📂 Estrutura da Planilha

* **APP** → Interface principal de simulação, onde o usuário insere valores e vê os resultados.
* **Planilha2** → Matriz de alocação de percentuais por perfil de investidor.
* **Dados** → Fonte para listas suspensas (como seleção de perfil) e dados auxiliares.

---

## 🧮 Fórmulas e Recursos Utilizados

* **Valor Futuro do Investimento (VF)**:

```excel
=VF(taxa_mensal; qtd_anos*12; aporte*-1)
```

Exemplo na planilha:

```excel
=VF($D$19; $A24*12; $D$17*-1)
```

* `$D$19` → taxa de rendimento mensal;

* `$A24` → quantidade de anos da simulação;

* `$D$17` → valor do aporte mensal (negativo por convenção do Excel).

* **Estimativa de dividendos mensais**:

```excel
=VALOR_INVESTIDO*DIVIDEND_YIELD_ANUAL/12
```

* **Alocação por categoria**:

```excel
=VALOR_TOTAL*PERCENTUAL_CATEGORIA
```

* **Lista suspensa (Validação de Dados)**:
  Permite a seleção do **perfil do investidor** diretamente na aba **APP**, garantindo que apenas opções válidas sejam escolhidas.
* Fonte da lista: aba **Dados**.

---

## 📊 Como Utilizar

1. Abra a aba **APP**.
2. Selecione seu **perfil de investidor** na lista suspensa.
3. Insira o **valor total a investir**.
4. Visualize a **alocação automática** nos FIIs.
5. Acompanhe o **crescimento do patrimônio** e os **dividendos mensais**.
6. Ajuste os parâmetros para testar diferentes cenários de investimento.

---

## 💡 Observações

* A planilha é **uma ferramenta de simulação** e não substitui orientação financeira profissional.
* Os valores de dividendos e rendimentos são **estimativas** baseadas nos dados informados.
* É possível expandir a planilha incluindo **novos FIIs, cenários de aportes mensais e reajustes de dividendos**.

---

## 🛠 Tecnologias

* **Excel** → Fórmulas e cálculos automáticos.
* **Power Query (opcional)** → Importação e atualização de dados históricos de FIIs.
* **Dashboard interativo** → Visualização clara da alocação, patrimônio e dividendos.

---

## 📈 Próximas Evoluções

* Inclusão de **gráficos dinâmicos** por categoria.
* Simulação de **aporte mensal recorrente**.
* Integração com **dados de mercado em tempo real** via Power Query ou API.
