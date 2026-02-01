# 📊 Relatório RH - PostgreSQL + Python + Excel + Power BI

Projeto de **Banco de Dados + Relatórios** simulando um sistema de RH profissional com:

✅ Funcionários  
✅ Departamentos / Cargos / Unidades  
✅ Salários e pagamentos mensais  
✅ Benefícios  
✅ Relatórios em Excel  
✅ Dashboard no Power BI  

---

## 🚀 Tecnologias usadas

- **PostgreSQL**
- **pgAdmin 4**
- **Python**
  - pandas
  - psycopg2
  - openpyxl
- **Excel**
- **Power BI Desktop**
- **GitHub**

---

## 🗂 Estrutura do Banco (tabelas principais)

- `funcionarios`
- `departamentos`
- `cargos`
- `unidades`
- `salarios`
- `pagamentos`
- `beneficios`
- `funcionario_beneficios`
- `promocoes`
- `frequencia`
- `performance`

---

## 📌 O que esse projeto faz?

Este projeto simula um sistema real de RH com milhares de funcionários e permite:

📍 Ver funcionários por unidade / cargo / departamento  
📍 Analisar salários e pagamentos por mês  
📍 Ver custos mensais da empresa com colaboradores  
📍 Exportar relatórios formatados em Excel  
📍 Criar visualizações e dashboards no Power BI  

---

## 📁 Arquivos do projeto

📌 **SQL**
- Scripts de criação das tabelas
- Inserts de dados (funcionários, pagamentos, etc.)

📌 **Python**
- Script para gerar relatório Excel:
  - Aba Funcionários
  - Aba Gastos Mensais
  - Aba Custo por Funcionário (mês)
  - Resumo + gráfico automático

📌 **Excel**
- Relatório final gerado automaticamente com gráficos e formatação

📌 **Power BI**
- Conexão direta com PostgreSQL
- Gráficos e cartões com indicadores de custo

---

## 🧠 Como rodar esse projeto (modo fácil)

### ✅ 1) Criar o banco no PostgreSQL
1. Abra o **pgAdmin**
2. Crie um banco chamado: `empresa_rh`
3. Execute os arquivos `.sql` dentro dele

---

### ✅ 2) Gerar Excel pelo Python
1. Abra o CMD dentro da pasta do projeto
2. Rode:

```bash
py gerar_excel.py
