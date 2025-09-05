# Movies_pproductions_DataScience-
Desenvolvimento do estudo em Ciência de Dados denominado estúdio de Hollywood PProductions, com foco em resolução de problemas de negócios, análise de dados e aplicação de modelos preditivos.

# IMDB Rating Prediction
Sistema de previsão de notas do IMDB baseado em características de filmes e dados externos.

## 🚀 Instalação

### Pré-requisitos
- Python 3.8+
- pip ou conda

### Instalação com pip
```bash
git clone https://github.com/seu-usuario/imdb-rating-prediction.git
cd imdb-rating-prediction
pip install -r requirements.txt

### Instalação com conda
conda env create -f environment.yml
conda activate imdb-prediction

📊 Estrutura de Dados
Coloque o arquivo desafio_indicium_imdb.xlsx na pasta data/raw/

🏃‍♂️ Execução
Análise Exploratória
bash
jupyter notebook notebooks/02_eda_analysis.ipynb
Treinamento do Modelo
bash
python src/model_training.py
Previsões
python
from src.model_training import predict_rating

# Exemplo de uso
prediction = predict_rating({
    'Runtime': 120,
    'Meta_score': 80,
    'Gross': 100000000,
    'Director': 'Christopher Nolan',
    'Genre': 'Action, Sci-Fi'
})
print(f"Nota prevista: {prediction}")
📈 Resultados
RMSE: 0.45

R²: 0.85

MAE: 0.35

🛠️ Tecnologias
Python 3.8

Scikit-learn

Pandas

NumPy

Matplotlib

Seaborn

Jupyter

📝 Licença
MIT License

