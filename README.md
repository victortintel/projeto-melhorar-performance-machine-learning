# PROJETO - FUNÇÕES para MELHORAR a performance dos modelos de Machine Learning - Victor Tintel
## 📌 Descrição do Projeto
#### Este projeto tem como objetivo explorar e comparar três técnicas avançadas de otimização de hiperparâmetros para modelos de Machine Learning:

- GridSearchCV

- RandomizedSearchCV

- Bayesian Optimization

Utilizando os algoritmos de classificação Random Forest e SVM (Support Vector Machine), serão criados e treinados diversos modelos preditivos para avaliar o impacto dessas funções na performance e eficiência dos modelos.

Será demonstrado passo a passo como implementar cada uma dessas técnicas, explicando suas diferenças, vantagens e desvantagens, além de análises comparativas para entender qual método se adequa melhor a diferentes cenários.

## 🔍 Métodos de Otimização de Hiperparâmetros
### 1️⃣ GridSearchCV
- Realiza uma busca exaustiva em todas as combinações de hiperparâmetros definidos.

- Garante encontrar a melhor combinação dentro do espaço de busca, mas pode ser computacionalmente caro.

### 2️⃣ RandomizedSearchCV
- Testa combinações aleatórias de hiperparâmetros dentro de um espaço definido.

- Mais eficiente computacionalmente que o GridSearch, mas não garante a melhor combinação.

### 3️⃣ Bayesian Optimization
- Utiliza métodos probabilísticos para direcionar a busca dos melhores hiperparâmetros.

- Mais inteligente e eficiente que os métodos anteriores, reduzindo o tempo de treinamento.

##  📊 Resultados Esperados
- Comparação de desempenho entre GridSearchCV, RandomizedSearchCV e Bayesian Optimization.

- Análise de tempo de execução e acurácia dos modelos.

- Identificação do melhor método para diferentes cenários.



