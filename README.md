# 🔬 Breast Cancer KNN Classifier

![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![VS Code](https://img.shields.io/badge/VS%20Code-Ready-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen.svg)

---

# 📋 Sobre o Projeto

Este projeto implementa um modelo de Machine Learning utilizando o algoritmo **K-Nearest Neighbors (KNN)** para classificação de tumores de mama em:

- ✅ Benignos
- ⚠️ Malignos

O projeto utiliza o dataset Breast Cancer Wisconsin disponível na biblioteca `scikit-learn`.

---

# 🎯 Objetivos

- Aplicar Machine Learning em diagnóstico médico
- Encontrar o melhor valor de K
- Avaliar acurácia do modelo
- Gerar gráficos e métricas de desempenho
- Demonstrar uso de Python para classificação supervisionada

---

# 📊 Dataset

O dataset contém:

| Informação | Valor |
|------------|-------|
| Amostras | 569 |
| Features | 30 |
| Classes | Benigno / Maligno |

---

# 🚀 Tecnologias Utilizadas

- Python
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

---

# 📦 Instalação

## 1️⃣ Clonar o repositório

```bash
git clone https://github.com/babi-s4ntos/breast-cancer-knn-classifier.git
```

---

## 2️⃣ Entrar na pasta

```bash
cd breast-cancer-knn-classifier
```

---

## 3️⃣ Instalar dependências

```bash
pip install -r requirements.txt
```

---

# ▶️ Como Executar

## VS Code

1. Abra o VS Code
2. Clique em:

```text
File → Open Folder
```

3. Selecione a pasta do projeto
4. Abra o arquivo:

```text
atvdd.ipynb
```

5. Clique em:

```text
Run All
```

---

## Google Colab

1. Acesse:

https://colab.research.google.com

2. Faça upload do arquivo:

```text
atvdd.ipynb
```

3. Clique em:

```text
Runtime → Run All
```

---

# 📈 Resultados

## Melhor modelo encontrado

| Métrica | Resultado |
|----------|------------|
| Melhor K | 12 |
| Acurácia | 97.66% |

---

# 📊 Exemplo de Saída

```text
MELHOR K ESCOLHIDO: K = 12
Acurácia no teste: 0.9766
```

---

# 📁 Estrutura do Projeto

```text
breast-cancer-knn-classifier/
│
├── atvdd.ipynb
├── atvdKnn.py
├── requirements.txt
└── README.md
```

---

# ⚠️ Possíveis Erros

## Erro sklearn

```bash
pip install scikit-learn
```

## Erro seaborn

```bash
pip install seaborn
```

## Erro numpy

```bash
pip install numpy pandas
```

---

# 📦 requirements.txt

```txt
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=1.0.0
jupyter>=1.0.0
```

---

# 👤 Autor

## Babi Santos

- GitHub: https://github.com/babi-s4ntos

---

# 📄 Licença

Projeto acadêmico para estudos de Machine Learning com Python.

---

⭐ Se gostou do projeto, deixe uma estrela no repositório!