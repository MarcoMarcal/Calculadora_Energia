# ☀️ Solariza — Calculadora de Consumo de Energia

> **Energia Limpa e Consciente ⚡**  
> Uma calculadora simples e responsiva que ajuda a estimar o consumo mensal de energia elétrica com base na potência dos aparelhos e tempo de uso.

---

## 🌍 Sobre o projeto

O **Solariza** é uma calculadora web desenvolvida em **HTML, CSS e JavaScript**, com foco em **simplicidade, educação energética e sustentabilidade**.  
O objetivo é permitir que qualquer pessoa estime o gasto de energia dos eletrodomésticos da sua casa e compreenda melhor o impacto no valor da conta de luz 💡.

🔗 **Repositório oficial:** [github.com/MarcoMarcal/Calculadora_Energia](https://github.com/MarcoMarcal/Calculadora_Energia)

---

## 🧠 Lógica básica da calculadora

A lógica de cálculo é baseada nas fórmulas padrões de consumo energético:

Consumo (kWh) = [ Potência (W) × Tempo de uso (h/dia) × Dias ] / 1000

### 🔹 Cálculo do consumo mensal

Custo (R$) = Consumo (kWh) × Tarifa (R$/kWh)

> 💡 A tarifa padrão considerada no projeto é **R$ 0,90/kWh**, podendo ser ajustada conforme a realidade local.

---

## 🧮 Exemplo de entrada de dados

| Eletrodoméstico    | Potência (W) | Horas/dia | Dias/mês | Tarifa (R$/kWh) |
|--------------------|--------------|------------|-----------|----------------|
| Geladeira          | 150          | 24         | 30        | 0.90           |
| TV                 | 100          | 5          | 30        | 0.90           |
| Chuveiro elétrico  | 5500         | 0.5        | 30        | 0.90           |

---

## 🧾 Saída esperada

| Eletrodoméstico   | Consumo (kWh/mês) | Custo (R$/mês) |
|-------------------|------------------:|----------------:|
| Geladeira         | 108.0             | 97.20           |
| TV                | 15.0              | 13.50           |
| Chuveiro elétrico | 82.5              | 74.25           |
| **Total**         | **205.5**         | **184.95**      |

---

## 🖥️ Tecnologias utilizadas

- **HTML5** – estrutura e conteúdo  
- **CSS3** – estilização e responsividade  
- **JavaScript (Vanilla)** – lógica de cálculo e manipulação dinâmica da tabela  

---

## 📱 Responsividade

O Solariza é totalmente responsivo e funciona bem em:
- 💻 Computadores e notebooks  
- 📱 Smartphones  
- 📟 Tablets  

A interface adapta automaticamente os campos e a tabela para telas menores, mantendo a experiência de uso confortável.

---

## 🚀 Como executar o projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/MarcoMarcal/Calculadora_Energia.git
