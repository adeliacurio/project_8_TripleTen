# project_8_TripleTen
Marketing Analytics project for Y.Afisha to optimize marketing expenses. Used SQL for ETL and Python for Cohort Analysis to calculate LTV, CAC, and ROMI, improving spend efficiency.

---

# Marketing Analytics: Inteligência de LTV, CAC e ROMI (Y.Afisha) 👋

## 📋 Descrição do Projeto
Este projeto foi focado na otimização das despesas de marketing da empresa Y.Afisha. Através de uma análise diagnóstica profunda, busquei identificar quando a retenção de clientes falha, quanto custa adquirir cada usuário e em quanto tempo esse investimento retorna para a empresa.

## 🎯 Objetivos Estratégicos
* Calcular métricas de produto: **DAU, WAU, MAU** e taxas de retenção.
* Analisar o **LTV (Lifetime Value)** por coortes para entender o valor do cliente ao longo do tempo.
* Apurar o **CAC (Custo de Aquisição de Clientes)** e o tempo de **Payback**.
* Avaliar o **ROMI (Retorno sobre Investimento em Marketing)** para identificar os canais mais lucrativos.

## 🛠️ Tecnologias e Ferramentas
* **SQL:** Utilizado para o processo de **ETL**, extraindo e estruturando grandes volumes de dados de logs de visitas, pedidos e despesas de marketing.
* **Linguagem:** Python.
* **Bibliotecas:** Pandas, Matplotlib e Seaborn (visualização de mapas de calor/heatmaps).
* **Técnicas:** Análise de Coortes, Análise de Funil e Saneamento de Dados (tratamento de outliers).

## 📉 Metodologia e Insights
1.  **Processamento via SQL:** Consolidação de bases de diferentes origens para criar uma visão única do comportamento do usuário.
2.  **Análise de Coortes:** Identificação de que o LTV Real sofria distorções de até 50% devido a outliers, corrigindo a visão para uma tomada de decisão precisa.
3.  **Avaliação de Canais:** Comparação entre o custo de cada fonte de tráfego e a receita gerada, revelando canais com **ROMI de até 20,03x**.
4.  **Análise de Retenção:** Identificação dos pontos de fricção onde os usuários deixavam de converter, permitindo ajustes no funil de vendas.

## ✅ Resultados
* **Otimização Orçamentária:** Recomendação estratégica para interromper investimentos em canais deficitários e escalar canais com alto retorno.
* **Eficiência Financeira:** Definição clara do tempo médio de retorno do investimento (Payback), auxiliando no planejamento de fluxo de caixa.
* **Inteligência de Negócio:** Criação de uma metodologia replicável para monitorar a saúde financeira de novos coortes de usuários.

---

### 💡 Como utilizar este repositório
1. O notebook principal detalha toda a jornada: desde as queries SQL até os heatmaps de retenção.
2. As conclusões estratégicas estão destacadas ao final de cada seção analítica.
