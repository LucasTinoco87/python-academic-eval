# 🐍 Python Academic Evaluation: Problem Solving Lab

Este repositório contém a resolução de uma atividade avaliativa focada na aplicação de conceitos fundamentais de programação utilizando a linguagem Python. O projeto aborda problemas práticos do cotidiano, como análise de dados climáticos, gestão educacional, monitoramento de energia e simulação financeira.

---

## 📌 Descrição do Projeto

O objetivo principal deste projeto é demonstrar o domínio de estruturas de controle de fluxo (condicionais e loops), manipulação de listas e processamento de dados básicos em Python. Cada questão resolve um problema prático, transformando dados brutos em métricas calculadas e relatórios legíveis.

---

## 🧩 Problemas Abordados e 🧠 Explicação da Lógica

Abaixo estão os quatro problemas resolvidos no projeto e a abordagem lógica utilizada para cada um.

### 🔹 1. Classificação de Temperaturas
* **O Problema:** Classificar uma lista de temperaturas semanais em três categorias: "Frio" (< 20°C), "Agradável" (20°C a 30°C) e "Quente" (> 30°C).
* **A Lógica:** Foi utilizado um laço de repetição `for` para percorrer a lista de temperaturas. Estruturas condicionais `if-elif-else` avaliam cada valor individualmente, categorizando-o e incrementando contadores específicos para o cálculo estatístico final.

### 🔹 2. Sistema de Avaliação de Alunos
* **O Problema:** Avaliar o desempenho de alunos com base em suas notas, dividindo-os em "Reprovado" (< 5), "Recuperação" (entre 5 e 7) e "Aprovado" (≥ 7), além de calcular a taxa de reprovação.
* **A Lógica:** Semelhante à questão anterior, as notas são testadas em cascata lógica. Ao final da leitura das notas, o percentual de reprovados é extraído dividindo a quantidade de alunos reprovados pelo tamanho total da lista (função `len()`).

### 🔹 3. Monitoramento de Consumo de Energia
* **O Problema:** Analisar o consumo diário de energia (kWh), calculando a média semanal e emitindo alertas de consumo excessivo caso houvesse mais de dois dias com gasto alto (≥ 180 kWh).
* **A Lógica:** Foi aplicada a técnica de *List Comprehension* para filtrar de forma elegante os dias de alto consumo. A média e a soma foram calculadas utilizando funções nativas do Python (`sum()` e `len()`), e uma flag booleana dispara o alerta condicional.

### 🔹 4. Simulação de Carrinho de Compras
* **O Problema:** Aplicar descontos progressivos em uma lista de compras de acordo com a faixa de preço unitário do produto e calcular o preço final pago pelo cliente e o valor total economizado.
* **A Lógica:** Um loop percorre os preços originais e aplica o percentual de desconto correspondente através de blocos `if-elif-else`. O código armazena os valores com formatação de duas casas decimais e acumula a economia gerada subtraindo o preço final do original.

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3.x
* **Plataforma:** Jupyter Notebooks / Google Colaboratory

---

## ▶️ Como Executar no Google Colab

Você pode visualizar e rodar o código diretamente no navegador através do link oficial do projeto:

1. Acesse o notebook do projeto clicando no link abaixo:
   > 🔗 [Acessar o Projeto no Google Colab](https://colab.research.google.com/drive/1LhV9oH9ERCftKW5KKgyVuFN00yOrNVrN#scrollTo=B0Mh67v9Wnl3)
2. Faça login com sua conta Google (caso ainda não esteja logado).
3. Para rodar as células de código, clique no botão de **Play (▶️)** no canto esquerdo de cada bloco de código ou pressione `Shift + Enter`.

---

## 📎 Observações Acadêmicas

Este projeto foi desenvolvido como parte de uma atividade avaliativa para a disciplina de programação sob a orientação do Professor Sérgio Monteiro. Ele reflete a consolidação de conhecimentos de sintaxe limpa, lógica procedural e documentação estruturada.
