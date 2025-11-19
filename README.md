# MOH – Motor de Orientação de Habilidades (Dynamic Programming) 🎓

Trabalho **Global Solution** da disciplina de Engenharia de Software, focado em
modelagem e resolução de problemas com **Dynamic Programming**, grafos e simulação.

---

## 👥 Equipe

- **Arthur Fellipe Estevão da Silva** – RM553320  
- **Eduardo Pires Escudero** – RM556527  
- **Leonardo Munhoz Prado** – RM556824  

---

## 🧠 Visão geral

O projeto implementa um **Motor de Orientação de Habilidades (MOH)** que auxilia
na escolha de quais habilidades estudar, considerando:

- pré-requisitos entre habilidades (grafo direcionado);  
- limite de tempo total disponível;  
- limite de complexidade total;  
- incerteza nos valores das habilidades (simulação Monte Carlo);  
- diferentes cenários de mercado para os próximos anos.

O objetivo é gerar **planos de estudo** que maximizem o valor de carreira do aluno,
dentro das restrições impostas.

---

## 🗂 Estrutura principal

- `MOH.ipynb` – notebook principal, pronto para ser aberto no Google Colab.
- `skills_base.csv` – arquivo de entrada com as habilidades usadas nos testes.
- `README.md` – este arquivo, com instruções de uso.
- (Opcional) `relatorio.pdf` – versão em PDF do relatório final, exportado a partir do notebook.

---

## ⚙️ Tecnologias e bibliotecas

O código foi escrito em **Python 3**, utilizando apenas bibliotecas comuns:

- `pandas` – organização de tabelas e resultados;
- `matplotlib` – gráficos simples (histograma da simulação);
- bibliotecas padrão da linguagem (`itertools`, `math`, `random`, etc.).

No **Google Colab** todas essas dependências já vêm instaladas.

---

## ▶️ Como executar no Google Colab

1. Faça upload dos arquivos `MOH.ipynb` e (opcional) `skills_base.csv` para o Colab.  
2. Abra o notebook `MOH.ipynb`.  
3. Execute as células em sequência:
   - Seção **1**: imports e configurações.  
   - Seção **2**: escolha se deseja usar o arquivo CSV (`usar_csv = True`) ou o dicionário interno.  
   - Seção **3–9**: execução dos desafios e análise dos resultados.  
   - Seção **10**: painel de testes rápidos (opcional, para apresentação).

4. Para gerar o relatório em PDF, use no Colab:  
   `Arquivo → Imprimir → Salvar como PDF`.

---

## 📥 Formato do arquivo `skills_base.csv`

O projeto aceita um arquivo `.csv` com a seguinte estrutura:

```text
id,valor,tempo,complexidade,prereqs
S1,10,40,3,
S2,8,30,2,
S3,15,50,4,S1
...
H12,30,90,7,S8;S9
