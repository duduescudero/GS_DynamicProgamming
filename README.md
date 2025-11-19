
# 🚀 MOH – Motor de Orientação de Habilidades  
### Dynamic Programming • Simulação • Grafos • Otimização

📌 Sumário
- 📘 Sobre o Projeto
- 👥 Integrantes
- 🧠 Contexto Acadêmico
- 🧱 Arquitetura e Modelagem
- 🧪 Metodologia e Técnicas Utilizadas
- 📈 Resultados Experimentais
- 🗂 Estrutura do Repositório
- ⚙️ Como Executar
- 📄 Relatório PDF

--------------------------------------------------------------------

📘 Sobre o Projeto
O MOH – Motor de Orientação de Habilidades é uma solução que utiliza:
- Dynamic Programming
- Grafos
- Simulação Monte Carlo
- Heurísticas
- Merge Sort
- Recomendações baseadas em valor esperado

Para gerar planos de estudo ótimos respeitando dependências, tempo, complexidade e tendências futuras.

--------------------------------------------------------------------

👥 Integrantes
Arthur Fellipe Estevão da Silva – RM553320  
Eduardo Pires Escudero – RM556527  
Leonardo Munhoz Prado – RM556824  

--------------------------------------------------------------------

🧠 Contexto Acadêmico
Projeto desenvolvido para a Global Solution – Engenharia de Software (FIAP), cobrindo:
- Estruturas de dados
- Algoritmos
- Simulação
- Programação Dinâmica
- Modelagem computacional

--------------------------------------------------------------------

🧱 Arquitetura e Modelagem

Modelagem por grafo:
Cada skill contém valor, tempo, complexidade e pré-requisitos.

Principais módulos:
Skill  
SkillGraph  
solve_deterministic_exaustivo()  
simulate_monte_carlo()  
merge_sort_skills()  
recomendar_proximas_habilidades()  

--------------------------------------------------------------------

🧪 Metodologia e Técnicas Utilizadas

1️⃣ Seleção ótima (DP / força bruta)  
Avaliação de 4096 subconjuntos.

2️⃣ Simulação Monte Carlo  
200 cenários, variação ±10%.

3️⃣ Ordens críticas  
120 ordens válidas avaliadas.

4️⃣ Comparação guloso vs ótimo  
Análise de eficiência e adaptabilidade.

5️⃣ Merge Sort  
Divisão entre Sprint A (menos complexas) e Sprint B (mais complexas).

6️⃣ Recomendações  
Com base em valor esperado e pré-requisitos atendidos.

--------------------------------------------------------------------

📈 Resultados Experimentais

🔵 Seleção ótima  
Melhor valor: 99.0  
Tempo total: 345h  
Complexidade total: 26  
Conjunto ótimo: S1, S2, S3, S4, S5, S6, S8  

🟣 Monte Carlo  
Valor médio: 99.7498  
Desvio padrão: 2.3055  

🔴 Ordens críticas  
Valor máximo: 127  
Top ordens: S3 → S5 → S7 → S9 → S8  

🟢 Guloso vs Ótimo  
Guloso: S2, S1  
Ótimo: —  

🟡 Sprints  
Sprint A: S2, S1, S4, S6, S3, S9  
Sprint B: S5, S7, H10, S8, H11, H12  

🟦 Recomendações  
Baseado nas skills atuais: S1, S2, S3, S5  
Recomendadas: S8, S6, S4  

--------------------------------------------------------------------

🗂 Estrutura do Repositório

GS_DynamicProgamming/  
 ├─ MOH.ipynb  
 ├─ Relatorio_MOH.pdf  
 ├─ skills_base.csv  
 └─ README.md  

--------------------------------------------------------------------

⚙️ Como Executar

1️⃣ Clonar o repositório  
git clone https://github.com/duduescudero/GS_DynamicProgamming.git

2️⃣ Abrir no Google Colab  
Enviar MOH.ipynb  
Enviar skills_base.csv  
Executar células  

3️⃣ Gerar PDF  
Executar célula final do notebook.

--------------------------------------------------------------------

📄 Relatório PDF  
Arquivo: Relatorio_MOH.pdf
