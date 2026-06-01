# Atividade de Aprendizado de Máquina - KNN com Breast Cancer Dataset

## Sobre o projeto

Esta atividade tem como objetivo aplicar o algoritmo K-Nearest Neighbors (KNN) utilizando o dataset Breast Cancer disponibilizado pela biblioteca Scikit-Learn.

Durante o desenvolvimento foram realizadas as etapas de exploração dos dados, visualização gráfica, pré-processamento com StandardScaler, treinamento do modelo utilizando diferentes valores de K e avaliação do desempenho através das métricas de classificação.

---

## Tecnologias Utilizadas

- Python 3
- Jupyter Notebook
- Pandas
- Matplotlib
- Scikit-Learn

---

## Dataset Utilizado

Dataset Breast Cancer Wisconsin disponível na biblioteca Scikit-Learn.

```python
from sklearn.datasets import load_breast_cancer
```

O conjunto de dados contém informações extraídas de exames de tumores mamários e possui duas classes:

- Malignant (Maligno)
- Benign (Benigno)

---

## Etapas Desenvolvidas

### 1. Exploração do Dataset

Foram analisadas as informações gerais do conjunto de dados:

- Quantidade de registros
- Quantidade de atributos
- Classes existentes
- Features disponíveis

### 2. Análise Gráfica

Foi criado um gráfico para visualizar a distribuição das classes presentes no dataset.

### 3. Pré-processamento

Foi utilizado o StandardScaler para padronizar os dados.

Essa etapa é importante porque o algoritmo KNN utiliza cálculos de distância e pode ser influenciado por atributos que possuem escalas muito diferentes.

### 4. Treinamento do Modelo

Foram testados valores de K entre 1 e 20 para identificar qual configuração apresenta melhor desempenho.

### 5. Avaliação

Foi gerado um gráfico de Acurácia × K para auxiliar na escolha do melhor valor.

Após a seleção do melhor K, o modelo final foi avaliado utilizando:

- Accuracy
- Precision
- Recall
- F1-Score

através do Classification Report.

---

## Estrutura do Projeto

```
atividade-knn-breast-cancer/
│
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## Como Executar

### 1. Clonar o repositório

```bash
git clone https://github.com/LucasMiura/atividade-knn-breast-cancer-lucas-miura
```

### 2. Instalar as dependências

```bash
pip install -r requirements.txt
```

### 3. Executar o Jupyter Notebook

```bash
jupyter notebook
```

Abra o arquivo:

```text
notebook.ipynb
```

---

## Vídeo de Apresentação

Link do vídeo demonstrando a execução do notebook e explicando cada etapa do desenvolvimento:

🔗 https://youtu.be/WgBA4DqV_CY

---

## Autor

Lucas Miura

Disciplina: Aprendizado de Máquina

FATEC Registro
