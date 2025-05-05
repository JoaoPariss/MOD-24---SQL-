# 🧾 Consultas SQL — Tabela de Vendas

Este repositório contém consultas SQL simples feitas para praticar operações básicas em uma tabela de vendas. As atividades envolvem seleção de dados, uso de funções agregadas e cálculos entre colunas.

## 📌 Atividades Realizadas

1. **Consulta completa da tabela**
   - Seleção de **todas as colunas e linhas** da tabela `vendas`.

2. **Consulta parcial da coluna produto**
   - Seleção de **10 linhas da coluna `produto`** usando `LIMIT`.

3. **Cálculo de médias com alias**
   - Cálculo da **média do valor por unidade** e das **unidades vendidas**, com renomeação das colunas usando `AS`.

4. **Cálculo do valor total gasto por compra**
   - Multiplicação do valor unitário pela quantidade vendida, retornando:
     - `ID_COMPRA`
     - `ID_CLIENTE`
     - **Valor total gasto** (coluna calculada).

5. **[Desafio] Média geral do valor gasto**
   - Consulta que retorna apenas a **média total do valor gasto**, com base na multiplicação entre valor unitário e quantidade vendida.  
   - Resultado vem em uma única linha com uma única coluna.
