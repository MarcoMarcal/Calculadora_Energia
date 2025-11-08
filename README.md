# ☀️ Solariza — Calculadora de Consumo de Energia

> **Energia Limpa e Consciente ⚡**  
> Projeto web simples e responsivo que calcula o consumo mensal de energia elétrica com base em dados de potência, tempo de uso e tarifa.  

---

## 🌍 Sobre o projeto

O **Solariza** é uma calculadora de consumo de energia desenvolvida em **HTML, CSS e JavaScript**, com foco em **simplicidade, usabilidade e sustentabilidade**.  
O usuário pode cadastrar eletrodomésticos e visualizar quanto cada um consome por mês em **kWh** e o **custo estimado em reais (R$)**.  

---

## 🧠 Lógica básica da calculadora

A lógica é baseada nas fórmulas padrão de consumo energético:

### 🔹 Cálculo do consumo
\[
\text{Consumo (kWh)} = \frac{\text{Potência (W)} \times \text{Tempo de uso (h/dia)} \times \text{Dias}}{1000}
\]

### 🔹 Cálculo do custo total
\[
\text{Custo (R\$)} = \text{Consumo (kWh)} \times \text{Tarifa (R\$ por kWh)}
\]

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

## 🚀 Como executar

1. Baixe ou clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/solariza.git
