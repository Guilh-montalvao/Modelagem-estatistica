# Modelagem Estatística

Projeto dedicado ao estudo de distribuições estatísticas e modelagem probabilística, contendo exercícios e análises de distribuições normais e binomiais.

## 📦 Estrutura do Projeto

```
.
├── Av1/
│   └── distribuicao-normal-binominal/
│       ├── atividade_distri_binomial.ipynb - Análise de distribuição binomial
│       └── atividade_distri_normal.ipynb - Estudo de distribuição normal
└── Av2/
```

## ⚙️ Configuração

1. Instale as dependências:
```bash
pip install -r requirements.txt
```

2. Execute o Jupyter Notebook:
```bash
jupyter notebook
```

## 📋 Requisitos
```
scipy>=1.10.1
numpy>=1.24.3
matplotlib>=3.7.1
jupyter>=1.0.0
```

## 🧮 Exemplos de Uso

### Distribuição Normal
```python
from scipy.stats import norm
media = 6.7
desvio = 1.2
prob = norm.cdf(6.5, media, desvio) - norm.cdf(5.5, media, desvio)
print(f"Probabilidade: {prob:.2%}")
```

### Distribuição Binomial
```python
from scipy.stats import binom
n = 1000
p = 0.4
esperado = n * (1 - p)
print(f"Esperado: {esperado:.1f} coroas")
```

## ▶️ Execução

Abra os notebooks Jupyter na pasta `Av1/distribuicao-normal-binominal` para ver as análises completas e gráficos.