# Heart Disease Prediction
Projeto de classificação supervisionada para predição de doenças cardíacas
🏥 Heart Disease Prediction - Predição de Doenças Cardíacas
📊 Sobre o Projeto
Projeto de classificação supervisionada para predição de doenças cardíacas usando machine learning. Implementação e comparação de três algoritmos de classificação.

🚀 Tecnologias Utilizadas
Python 3.+

Pandas - Manipulação de dados

Scikit-learn - Machine Learning

Matplotlib/Seaborn - Visualização de dados

Git/GitHub - Versionamento

📋 Algoritmos Implementados
Árvore de Decisão (Decision Tree)

K-Vizinhos Mais Próximos (K-Nearest Neighbors)

Regressão Logística (Logistic Regression)

📈 Métricas de Avaliação
✅ Acurácia (Accuracy)

✅ F1-Score

✅ Matriz de Confusão

✅ Relatório de Classificação

🗂️ Estrutura do Projeto
text
heart-disease-prediction/
├── heart.csv                 # Dataset com 16 amostras
├── heart_disease_prediction.py # Código principal
├── requirements.txt          # Dependências
├── comparacao_acuracia.png   # Gráfico comparativo
└── README.md                 # Documentação
⚡ Como Executar
bash
# Clone o repositório
git clone https://github.com/Natanael-Bezerra/heart-disease-prediction.git

# Instale as dependências
pip install -r requirements.txt

# Execute o projeto
python heart_disease_prediction.py
📊 Resultados Obtidos
Todos os modelos atingiram 100% de acurácia:

Decision Tree: 100% acurácia | 100% F1-Score

KNN: 100% acurácia | 100% F1-Score

Logistic Regression: 100% acurácia | 100% F1-Score

⚠️ Análise Crítica
Os resultados de 100% de acurácia indicam possível overfitting devido ao dataset pequeno (16 amostras). Em aplicações reais, datasets de saúde typically têm centenas de amostras e acurácias entre 70-90%.

🔮 Próximas Melhorias
Ampliar dataset com mais amostras

Implementar validação cruzada

Adicionar tuning de hiperparâmetros

Testar algoritmos ensemble (Random Forest, XGBoost)

Adicionar mais métricas de avaliação

👨‍💻 Autores
Natanael Bezerra E Lucas Morais

GitHub: @Natanael-Bezerra
@LucasMorais03

Email: windowsphoneproject@gmail.com
Email: moraislucasufs2020@hotmail.com
