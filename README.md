# 🚀 MOH – Motor de Orientação de Habilidades  
### Dynamic Programming • Simulação • Grafos • Otimização

📌 Sumário
- Sobre o Projeto
- Integrantes
- Contexto Acadêmico
- Arquitetura e Modelagem
- Metodologia e Técnicas Utilizadas
- Resultados Experimentais
- Estrutura do Repositório
- Como Executar
- Relatório PDF

--------------------------------------------------------------------

📘 Sobre o Projeto
O MOH – Motor de Orientação de Habilidades é uma plataforma que usa:
- Dynamic Programming
- Grafos
- Monte Carlo
- Heurísticas
- Merge Sort
- Recomendações baseadas em valor esperado

para gerar planos de estudo ótimos considerando:
tempo, complexidade, valor, dependências e projeções.

--------------------------------------------------------------------

👥 Integrantes
Arthur Fellipe Estevão da Silva – RM553320
Eduardo Pires Escudero – RM556527
Leonardo Munhoz Prado – RM556824

--------------------------------------------------------------------

🧠 Contexto Acadêmico
Projeto da Global Solution (FIAP) envolvendo:
estruturas de dados, algoritmos, modelagem e análise experimental.

--------------------------------------------------------------------

🧱 Arquitetura e Modelagem

Modelagem por grafo:
Cada skill contém valor, tempo, complexidade e pré-requisitos.

Principais estruturas:
Skill
SkillGraph
solve_deterministic_exaustivo()
simulate_monte_carlo()
merge_sort_skills()
recomendar_proximas_habilidades()

--------------------------------------------------------------------

🧪 Metodologia e Técnicas Utilizadas

1. Seleção ótima (DP/força bruta)
   Avaliação de 4096 subconjuntos.

2. Monte Carlo
   200 cenários com variação de ±10%.

3. Ordens críticas
   120 sequências válidas.

4. Guloso vs ótimo
   Comparação de adaptabilidade e tempo.

5. Merge Sort
   Sprint A (menos complexas)
   Sprint B (mais complexas)

6. Recomendações
   Baseadas em valor esperado com incerteza.

--------------------------------------------------------------------

📈 Resultados Experimentais

Seleção ótima:
Melhor valor: 99.0
Tempo total: 345h
Complexidade total: 26
Conjunto ótimo: S1, S2, S3, S4, S5, S6, S8

Monte Carlo:
Valor médio: 99.7498
Desvio padrão: 2.3055
Top soluções incluíram S1–S8 e H11.

Ordens críticas:
Top 3 ordens alcançaram valor 127.

Guloso:
S2, S1 → adaptabilidade = 18.0

Recomendações:
S8, S6, S4

--------------------------------------------------------------------

🗂 Estrutura do Repositório

projeto-MOH/
 ├─ MOH_notebook.ipynb
 ├─ Relatorio_MOH_Profissional.pdf
 ├─ skills_base.csv
 ├─ images/
 │   └─ montecarlo.png
 ├─ README.md
 └─ LICENSE (opcional)

--------------------------------------------------------------------

⚙️ Como Executar

1. Clonar repositório:
git clone https://github.com/seuusuario/moh-projeto.git

2. Abrir no Google Colab:
Enviar notebook + CSV.

3. Gerar PDF:
Executar célula automática no final do notebook.

--------------------------------------------------------------------

📄 Relatório PDF
Local: /Relatorio_MOH_Profissional.pdf
