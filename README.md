# 📊 Projeto – Algoritmos de Ordenação em Java (PAA)
Projeto para fins acadêmicos.
## 📌 Sobre o projeto
Este repositório contém a **versão final e completa do projeto de Algoritmos de Ordenação**, desenvolvido para a disciplina de Projeto e Análise de Algoritmos (PAA).

O Programa V2 representa a versão consolidada e atualizada do desenvolvimento, substituindo a versão anteriormente disponibilizada, com as implementações dos cinco algoritmos de ordenação, sistema de métricas, validações, testes automatizados, demonstrações e ferramentas de comparação de desempenho.

O objetivo principal é estudar e comparar o comportamento dos algoritmos em diferentes cenários, analisando sua eficiência e complexidade computacional.

## 🚀 Algoritmos implementados
O programa contempla cinco algoritmos clássicos de ordenação:

- **Bubble Sort:** realiza comparações entre elementos adjacentes e efetua trocas quando necessário, utilizando parada antecipada.
- **Insertion Sort:** organiza os elementos por meio de inserções nas posições corretas.
- **Selection Sort:** seleciona o menor elemento da parte não ordenada e o posiciona corretamente.
- **Merge Sort:** utiliza a estratégia de divisão e conquista para dividir e intercalar os elementos.
- **Quick Sort:** utiliza pivô escolhido pela mediana de três para realizar as partições do vetor.

## 📈 Complexidade dos algoritmos

| Algoritmo | Melhor caso | Caso médio | Pior caso |
|---|---|---|---|
| Bubble Sort | O(n) | O(n²) | O(n²) |
| Insertion Sort | O(n) | O(n²) | O(n²) |
| Selection Sort | O(n²) | O(n²) | O(n²) |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) |
| Quick Sort | O(n log n) | O(n log n) | O(n²) |

## ⚙️ Funcionalidades
- Implementação completa dos cinco algoritmos.
- Contagem de comparações, trocas e movimentos.
- Medição do tempo de execução em nanossegundos e milissegundos.
- Validação da ordenação e preservação dos elementos originais.
- Demonstração passo a passo dos algoritmos Bubble Sort e Insertion Sort.
- Comparação entre os cinco algoritmos.
- Benchmark com diferentes tamanhos e organizações de vetores.
- Cálculo de médias e desvios padrão.
- Geração automática de resultados em CSV.
- Bateria de testes automatizados com 9.727 verificações.
- Visualizador gráfico e animado dos algoritmos, com testes e benchmark no navegador.

## 📁 Estrutura do projeto

| Arquivo | Descrição |
|---|---|
| `Main.java` | Execução principal dos algoritmos. |
| `BubbleSort.java` | Implementação do Bubble Sort. |
| `InsertionSort.java` | Implementação do Insertion Sort. |
| `SelectionSort.java` | Implementação do Selection Sort. |
| `MergeSort.java` | Implementação do Merge Sort. |
| `QuickSort.java` | Implementação do Quick Sort. |
| `Resultado.java` | Armazenamento dos resultados e métricas. |
| `Validador.java` | Validação dos vetores ordenados. |
| `Medicao.java` | Gerenciamento das execuções e cálculos estatísticos. |
| `Demonstracao.java` | Demonstração passo a passo e comparação dos algoritmos. |
| `Benchmark.java` | Execução dos benchmarks e geração de CSV. |
| `Testes.java` | Testes automatizados do projeto. |
| `visualizador_ordenacao.html` | Visualizador interativo dos algoritmos. |
| `EXPLICACAO.md` | Documentação técnica detalhada do projeto. |

## 💻 Tecnologias utilizadas
- Java 8 ou superior.
- HTML5.
- CSS.
- JavaScript.
- CSV para armazenamento dos resultados.

## 🔧 Como executar

### 1. Pré-requisitos

É necessário possuir o JDK 8 ou superior instalado.

### 2. Compilação

Dentro da pasta `OrdenacaoJava`, execute:

```bash
javac -encoding UTF-8 *.java
```

### 3. Programa principal

```bash
java Main
```

### 4. Demonstração dos algoritmos

```bash
java Demonstracao
```

Também é possível fornecer um vetor personalizado:

```bash
java Demonstracao 9 4 7 1 3
```

### 5. Testes automatizados

```bash
java Testes
```

O sistema executa 9.727 verificações, abrangendo casos de borda, vetores aleatórios, validações, métricas e consistência dos resultados.

## 📊 Benchmark de desempenho

Para executar o benchmark completo:

```bash
java Benchmark
```

Para limitar o tamanho máximo dos vetores a 10.000 elementos:

```bash
java Benchmark 10000
```

O benchmark considera:

**Tamanhos dos vetores:**
- 100 elementos.
- 1.000 elementos.
- 5.000 elementos.
- 10.000 elementos.
- 50.000 elementos.
- 100.000 elementos.

**Tipos de entrada:**
- Aleatório.
- Ordenado.
- Inverso.

Cada caso é executado cinco vezes, descartando a primeira execução como aquecimento da JVM. A média é calculada com as quatro execuções restantes, além do cálculo do desvio padrão amostral.

Os algoritmos quadráticos são executados somente até 50.000 elementos.

Os resultados são apresentados no terminal e exportados para:

```text
resultados_benchmark.csv
```

## 🎬 Visualizador interativo

O projeto disponibiliza uma interface gráfica para acompanhar o funcionamento dos algoritmos.

Para executar, basta abrir o arquivo:

```text
visualizador_ordenacao.html
```

A interface permite visualizar as animações dos cinco algoritmos, além de executar testes e benchmarks diretamente no navegador.

## 📏 Métricas avaliadas

Durante as execuções, são analisados:

- **Comparações:** quantidade de comparações entre elementos.
- **Trocas:** quantidade de trocas realizadas pelos algoritmos correspondentes.
- **Movimentos:** quantidade de deslocamentos ou cópias de elementos.
- **Tempo de execução:** tempo necessário para concluir a ordenação.
- **Validação:** confirmação da ordenação crescente e preservação dos elementos originais.

As métricas de trocas e movimentos possuem definições específicas para cada algoritmo, conforme explicado na documentação técnica.

## 🎯 Objetivo acadêmico

O projeto busca aplicar os conceitos de Projeto e Análise de Algoritmos por meio da implementação prática, validação e comparação de diferentes métodos de ordenação.

A análise dos resultados permite compreender as diferenças entre os algoritmos, suas complexidades e os impactos que o tamanho e a organização dos dados exercem sobre o desempenho.

## 📌 Considerações finais

Este repositório representa a **entrega final e completa do programa**, consolidando as implementações, funcionalidades, testes, demonstrações e análises de desempenho desenvolvidas durante o projeto.
O arquivo `Programa.zip` corresponde à primeira versão do programa.
O arquivo `ProgramaV2.zip` corresponde à versão atualizada que substitui a versão anterior disponibilizada no repositório.

---

**Disciplina:** Projeto e Análise de Algoritmos (PAA).
**Projeto acadêmico – Unisales**
