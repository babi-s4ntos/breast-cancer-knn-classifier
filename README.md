# 🔬 Classificação de Tumores de Mama com KNN

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![VS Code](https://img.shields.io/badge/VS%20Code-Ready-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen.svg)

## 📋 Índice
- [Sobre o Projeto](#sobre-o-projeto)
- [Dataset](#dataset)
- [Resultados](#resultados)
- [Tecnologias](#tecnologias)
- [Pré-requisitos](#pré-requisitos)
- [Como Executar](#como-executar)
  - [Opção 1: VS Code](#opção-1-vs-code-recomendado)
  - [Opção 2: Google Colab](#opção-2-google-colab)
  - [Opção 3: Jupyter Notebook Local](#opção-3-jupyter-notebook-local)
  - [Opção 4: Terminal/Script Python](#opção-4-terminalscript-python)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Exemplo de Saída](#exemplo-de-saída)
- [Interpretação dos Resultados](#interpretação-dos-resultados)
- [Solução de Problemas](#solução-de-problemas)
- [Autor](#autor)
- [Licença](#licença)

---

## 📋 Sobre o Projeto

Este projeto implementa um classificador **K-Nearest Neighbors (KNN)** para diagnosticar tumores de mama como **benignos** (não cancerígenos) ou **malignos** (cancerígenos) utilizando o dataset Breast Cancer Wisconsin do scikit-learn.

### 🎯 Objetivos
- Demonstrar aplicação prática de Machine Learning em diagnóstico médico
- Encontrar o melhor valor de K para maximizar a acurácia
- Avaliar performance do modelo com métricas de classificação
- Visualizar padrões nos dados que diferenciam tumores benignos de malignos

### 🤔 Como funciona o KNN?
O algoritmo KNN classifica um novo tumor baseado nos K tumores mais similares (vizinhos mais próximos):
1. Calcula a distância entre o novo tumor e todos os tumores do dataset
2. Seleciona os K mais próximos
3. Faz uma "votação" - a classe majoritária entre os vizinhos é a predição

---

## 📊 Dataset

**Breast Cancer Wisconsin Dataset** (do scikit-learn)

| Propriedade | Valor |
|-------------|-------|
| Total de amostras | 569 |
| Características | 30 |
| Tumores Malignos | 212 (37.3%) |
| Tumores Benignos | 357 (62.7%) |

### Características incluídas:
| Categoria | Features |
|-----------|----------|
| **Morfologia** | radius (raio), perimeter (perímetro), area (área) |
| **Textura** | texture, smoothness (suavidade) |
| **Geometria** | compactness (compacidade), concavity (concavidade) |
| **Outras** | symmetry (simetria), fractal_dimension |

*Total: 30 features (média, erro padrão e "pior" para cada característica)*

---

## 📈 Resultados

### Melhor Modelo
| Parâmetro | Valor |
|-----------|-------|
| **Melhor K** | 12 |
| **Acurácia** | 97.66% |
| **Dataset** | 70% treino / 30% teste |

### Classification Report (Conjunto de Teste)
| Classe | Precisão | Recall | F1-Score | Suporte |
|--------|----------|--------|----------|---------|
| Maligno | 1.00 | 0.94 | 0.97 | 54 |
| Benigno | 0.96 | 1.00 | 0.98 | 117 |
| **Média** | **0.98** | **0.97** | **0.97** | **171** |

### Matriz de Confusão