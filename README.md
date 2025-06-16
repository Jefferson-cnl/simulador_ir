# 📊 Simulador de IR Simplificado (20%) - 2025

Este projeto em Excel tem como objetivo auxiliar no **controle de rendimentos** e na **simulação do Imposto de Renda (IR) simplificado**, com base no modelo de desconto automático de 20% sobre a receita bruta, conforme regras vigentes para o ano de 2025.

---

## 🗂 Estrutura da Planilha

A planilha contém três abas principais:

### 1. DASHBOARD

- **Descrição:** Interface principal do simulador, contendo o título **"SIMULADOR DE IR SIMPLIFICADO (20%) - 2025"**.
- **Observações:** Esta aba é visual, e provavelmente será preenchida com gráficos, totais e informações consolidadas posteriormente.

---

### 2. REGISTRO DE RENDIMENTOS

- **Descrição:** Aba onde o usuário deve lançar os rendimentos obtidos ao longo do ano.
- **Estrutura:**
  - `Data`: Data do rendimento (ex: `2025-01-31`)
  - `Descrição`: Tipo ou origem do rendimento (ex: "Salário Emp X")
  - `Valor`: Valor bruto recebido
- **Exemplo de Registro:**

| Data       | Descrição     | Valor  |
|------------|----------------|--------|
| 2025-01-31 | Salário Emp X  | 150    |
| -          | -              | 200    |
| -          | -              | 300000 |

> Os valores subsequentes podem representar rendimentos adicionais lançados sem detalhamento.

---

### 3. APOIO

- **Descrição:** Aba de apoio para os cálculos automáticos.
- **Informações principais:**
  - `VALOR BRUTO`: Soma de todos os rendimentos registrados (ex: R$ 300.350,00)
  - `DESCONTO SIMPLIFICADO (-20%)`: Cálculo do desconto de 20% aplicado sobre o total bruto (ex: R$ 240.280,00)

> Esta aba serve como base para cálculos e fórmulas que alimentam o DASHBOARD e facilita a automatização do IR a pagar.

---

## 🧮 Como Usar

1. **Registrar os rendimentos** na aba "REGISTRO DE RENDIMENTOS", preenchendo ao menos a data, descrição e valor.
2. Os valores são somados automaticamente na aba "APOIO".
3. O desconto simplificado de 20% é aplicado automaticamente com base nos valores registrados.
4. O resultado final poderá ser visualizado no "DASHBOARD", que pode conter gráficos, totais consolidados e análises.

---

## 🧾 Observações

- Ideal para quem faz a **declaração simplificada** do IR.
- Planilha manual, porém pronta para automações com fórmulas e gráficos.
- Pode ser expandida com impostos pagos, restituições, despesas dedutíveis, etc.

---

## 📅 Autor & Versão

- **Versão:** 1.0
- **Ano-Base:** 2025
- **Propósito:** Planejamento pessoal de Imposto de Renda

