
# 📊 Predição de Acordos de Cobrança com Machine Learning
![Predição de Acordos de Cobrança](https://raw.githubusercontent.com/djeannie29/cobranca/refs/heads/main/capa.webp)


🚀 Otimização de estratégias de cobrança com modelos preditivos avançados!

Este projeto utiliza Machine Learning para prever a probabilidade de um acionamento de cobrança resultar em um acordo fechado. 

🔹 Tecnologias Utilizadas
✔️ Python (Pandas, NumPy, Scikit-Learn, TensorFlow, Torch, Transformers)
✔️ Deep Learning (MLP, LSTM, Transformer)
✔️ Técnicas de Balanceamento (SMOTE-Tomek, Focal Loss, Ajuste de Thresholds)
✔️ Feature Engineering (Criação de variáveis temporais, sazonais e de comportamento de acionamento)
✔️ Visualização de Desempenho (Matplotlib, Seaborn)
✔️ Desenvolvido no Google Colab

🔹 Principais Funcionalidades
✅ Previsão de fechamento de acordos com base no histórico de acionamentos
✅ Ajuste dinâmico de thresholds para maximizar Recall e F1-Score
✅ Treinamento de múltiplos modelos e comparação de desempenho
✅ Métricas de Avaliação: Acurácia, F1-Score, Recall, Precisão, Matriz de Confusão
✅ Análises gráficas da evolução da perda e acurácia durante o treinamento

🔹 Como Utilizar
1️⃣ Carregue os dados no formato esperado (arquivo CSV ou Excel)
2️⃣ Execute o script de pré-processamento para geração das features
3️⃣ Treine os modelos utilizando mlp_model.fit(), lstm_model.fit() e transformer_model.fit()
4️⃣ Ajuste os thresholds para encontrar a melhor configuração
5️⃣ Analise os resultados com as métricas de avaliação e gráficos gerados

📌 Demonstração dos Resultados
Os modelos foram ajustados para mitigar o desbalanceamento entre acordos e não-acordos, utilizando técnicas avançadas de resampling, ajuste de thresholds e regularização.
