# 📉 Churn Prediction Model

Este projeto utiliza dados de clientes para prever a probabilidade de churn (quando um cliente deixa de usar o serviço de uma empresa). O modelo é treinado com dados históricos e avaliado com técnicas de aprendizado de máquina. O projeto utiliza bibliotecas como **Pandas**, **Scikit-learn** e **Jupyter Notebooks** para análise e modelagem.

---

## 📂 Estrutura de Pastas

Previsão de Churn / ├── train_churn_.csv # Dados de treinamento do churn 
                    ├── test_churn_.csv # Dados de teste para prever churn 
                    ├── submission.csv # Arquivo com as previsões do modelo para envio 
                    ├── sample_submission_.csv # Exemplo de submissão 
                    ├── trabalho_final_Lucas_Leandro_Wall_Bruno_22251965.ipynb # Jupyter Notebook com o modelo e análise 
                    ├── trabalho-final-nome-ra.ipynb # Jupyter Notebook com análise adicional ou variações do modelo └── README.md # Este arquivo README com detalhes sobre o projeto


---

## 🛠️ Tecnologias Utilizadas

- **Python**: Para processamento de dados e construção do modelo preditivo.
- **Pandas**: Para manipulação de dados.
- **Scikit-learn**: Para construção do modelo de aprendizado de máquina.
- **Jupyter Notebooks**: Para análise e documentação interativa do projeto.

---

## 🔄 Fluxo do Projeto

1. **Análise Exploratória de Dados (EDA)**: A primeira etapa envolve a inspeção dos dados para entender as características dos clientes e a identificação de padrões que possam prever o churn.

2. **Pré-processamento de Dados**: Envolve limpar dados ausentes, transformar variáveis e preparar os dados para o modelo.

3. **Construção do Modelo**: Um modelo de aprendizado de máquina (como **Random Forest**, **Logistic Regression**, etc.) é treinado usando o conjunto de dados de treinamento.

4. **Avaliação do Modelo**: O desempenho do modelo é avaliado com métricas como **Acurácia**, **Precisão**, **Recall**, e **F1-Score**.

5. **Submissão**: As previsões do modelo para os dados de teste são geradas e salvas no formato do arquivo `submission.csv`.

---

## 📊 Descrição dos Dados

- **train_churn_.csv**: Contém dados históricos de clientes e suas informações relevantes (ex.: idade, contrato, histórico de pagamentos, etc.) e se o cliente teve churn ou não.
- **test_churn_.csv**: Contém dados de clientes para os quais as previsões de churn devem ser feitas.
- **sample_submission_.csv**: Formato de arquivo esperado para a submissão, com as previsões de churn.
- **submission.csv**: Arquivo com as previsões feitas pelo modelo, pronto para ser enviado.

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/churn-prediction-model.git

2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt

3. Abra o arquivo trabalho_final_Lucas_Leandro_Wall_Bruno_22251965.ipynb no Jupyter Notebook para visualizar o código do modelo, a análise exploratória e o processo de treinamento.

4. Execute o código do notebook para treinar o modelo e gerar as previsões para os dados de teste.

5. As previsões podem ser salvas em um arquivo submission.csv com a mesma estrutura do arquivo sample_submission_.csv.

## 📸 Exemplos de Resultados
- 📈 Gráfico de Desempenho do Modelo