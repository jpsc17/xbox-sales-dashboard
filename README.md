# 🎮 Dashboard de Vendas — Xbox Game Pass (2024)

Projeto desenvolvido para o desafio **Criando um Dashboard de Vendas no Excel** da plataforma **DIO (Digital Innovation One)**. O objetivo é transformar dados brutos de assinaturas em um painel executivo claro, visual e orientado à tomada de decisão.

---

## 📊 Visão Geral do Projeto

O dashboard consolida **295 registros de assinaturas** do serviço Xbox Game Pass ao longo de 2024, permitindo analisar:

- **Receita Total:** R$ 7.633,00
- **Total de Assinantes:** 295
- **Ticket Médio:** R$ 25,87
- **Taxa de Renovação Automática:** 50,17% (148 ativos / 147 inativos)
- **Total de Descontos (Cupons):** R$ 2.122,00

### Principais Insights
- **Concentração de Receita no Plano Ultimate:** Embora os assinantes estejam distribuídos de forma equilibrada entre os planos (*Core*: 101, *Ultimate*: 98, *Standard*: 96), o plano **Ultimate** gera **R$ 5.388,00 (70,6% da receita total)** com ticket médio de **R$ 54,98**.
- **Recorrência Mensal Dominante:** O modelo **Monthly** concentra **139 assinantes (47,1%)** e **R$ 3.571,00** em receita, seguido por *Quarterly* (85) e *Annual* (71).
- **Força dos Add-ons (Season Passes):** O *Minecraft Season Pass* possui **194 adesões** (R$ 3.880,00) e o *EA Play Season Pass* soma **98 adesões** (R$ 2.940,00).
- **Sazonalidade:** De março a novembro a receita manteve estabilidade entre R$ 770 e R$ 832/mês, com pico em **Outubro (R$ 832,00)**.

---

## 🗂️ Estrutura da Planilha (`dashboard_xbox.xlsx`)

1. **`Assets`**: Paleta de cores oficial do projeto (tons de verde Xbox `#9BC848`, `#22C55E` e neutros `#E8E6E9`).
2. **`Bases`**: Base de dados bruta com 295 assinantes (`Subscriber ID`, `Name`, `Plan`, `Start Date`, `Auto Renewal`, `Subscription Price`, `Subscription Type`, `EA Play Season Pass`, `EA Play Season Pass Price`, `Minecraft Season Pass`, `Minecraft Season Pass Price`, `Coupon Value`, `Total Value`).
3. **`Cálculos`**: Tabelas de apoio com fórmulas dinâmicas (`SUM`, `COUNTIF`, `SUMIF`, `SUMPRODUCT`, `AVERAGE`) para alimentar o painel sem poluir a visualização principal.
4. **`Dashboard`**: Painel executivo com 5 cartões de KPIs, tabelas-resumo e 4 gráficos integrados:
   - Evolução Mensal da Receita (Gráfico de Linha)
   - Receita Total por Plano (Gráfico de Colunas)
   - Assinantes por Tipo de Assinatura (Gráfico de Pizza)
   - Adesões por Add-on / Season Pass (Gráfico de Barras)

---

## 🚀 Como Reproduzir

1. Faça o download do arquivo `dashboard_xbox.xlsx` disponível neste repositório.
2. Abra o arquivo no **Microsoft Excel** (ou **Google Sheets** / **LibreOffice Calc**).
3. Navegue até a aba **`Dashboard`** para visualizar os indicadores e gráficos.
4. Caso queira atualizar ou adicionar novos registros na aba **`Bases`**, os cálculos na aba **`Cálculos`** e os visuais no **`Dashboard`** serão recalculados automaticamente.

---

## 🛠️ Tecnologias Utilizadas

- **Microsoft Excel / Google Sheets** (Fórmulas `SUM`, `AVERAGE`, `COUNTIF`, `SUMIF`, `SUMPRODUCT` e Gráficos)
- **Git & GitHub** (Versionamento e documentação do projeto)
