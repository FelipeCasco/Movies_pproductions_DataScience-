# Movies_pproductions_DataScience - Previsão de Notas IMDB

📋 Sobre o Projeto

Este projeto tem como objetivo prever as notas do IMDB para filmes com base em suas características para o estúdio de Hollywood PProductions. Utilizamos técnicas de machine learning para criar um modelo preditivo que alcançou excelentes resultados. 

O desenvolvimento deste projeto buscou aplicar os conhecimentos adiquiridos em Ciência de Dados para melhorar a resolução de problemas de negócios, análise de dados e aplicação de modelos preditivos.

🎯 Resultados Obtidos
Desempenho dos Modelos:
Linear Regression: RMSE médio = 0.6084 (± 0.0533)

Ridge Regression: RMSE médio = 0.6083 (± 0.0538)

Random Forest: RMSE médio = 0.5830 (± 0.0762)

Gradient Boosting: RMSE médio = 0.5722 (± 0.0708)

Melhor modelo: Gradient Boosting

Exemplo de Previsão:
Para o filme 'The Shawshank Redemption', o modelo previu uma nota de: 78.13

🚀 Como Executar o Projeto
Pré-requisitos
Python 3.7+

Jupyter Notebook

Git

Instalação
1.Clone o repositório:

```
bash
git clone https://github.com/seu-usuario/imdb-rating-prediction.git
cd imdb-rating-prediction
```
2.Instale as dependências:
```
bash
pip install -r requirements.txt
```
3.Execute o Jupyter Notebook:
```
bash
jupyter notebook LH_CD_FelipeCasco.ipynb
```
##Uso do Modelo
No notebook, você pode:

Executar todas as células para reproduzir toda a análise

Utilizar o modelo treinado para fazer previsões em novos dados

Substituir os dados de exemplo por informações de outros filmes

Para fazer uma nova previsão, substitua os dados do filme na seção correspondente do notebook.

📊 ##Estrutura do Repositório
imdb-rating-prediction/
│
├── LH_CD_FelipeCasco.ipynb          # Notebook principal com toda a análise
├── requirements.txt                  # Dependências do projeto
├── best_model.pkl                   # Modelo treinado (Gradient Boosting)
├── eda_report.pdf                   # Relatório de análise exploratória
└── README.md                        # Este arquivo

📦 Dependências
Consulte o arquivo requirements.txt para todas as dependências e versões específicas.

🔍 Metodologia
Análise Exploratória: Exploração dos dados e identificação de padrões

Pré-processamento: Limpeza e transformação dos dados

Engenharia de Features: Criação de novas variáveis preditivas

Modelagem: Treinamento e avaliação de múltiplos algoritmos

Seleção do Modelo: Escolha do melhor modelo baseado em performance

📈 Resultados Detalhados
O modelo Gradient Boosting foi selecionado como o melhor, alcançando um RMSE de 0.5722, o que indica uma alta precisão nas previsões das notas do IMDB.

🤝 Contribuição
Para contribuir com este projeto:

Faça um fork do repositório

Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)

Commit suas mudanças (git commit -m 'Add some AmazingFeature')

Push para a branch (git push origin feature/AmazingFeature)

Abra um Pull Request

📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

📧 Contato
Felipe Casco - [seu-email@dominio.com]

Link do Projeto: https://github.com/seu-usuario/imdb-rating-prediction

