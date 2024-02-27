# azure-machine-learning

## Criando ambiente

- Criar assinatura/projeto Azure Machine Learning

## Configurando Trabalho

Aprendizado de máquina automatizado para previsão de aluguel de bicicletas

- Criar ML Automatizado
  
- Tipo de Tarefa: Regressão
  - Aprendizado de máquina automatizado para previsão de aluguel de bicicletas
  - Tipo de Dados: Tabular
  - Fonte de dados: Arquivos da Web
  - URL: https://aka.ms/bike-rentals
  - Cabeçalhos de coluna: Somente o primeiro arquivo tem cabeçalhos
    
- configuração de tarefa
  - Configurações adicionais
    - [ ] Métrica primaria: NormalizedRootMeanSquaredError
    - [ ] Habilitar empilhamento de ensemble
    - [ ] Usar todos os modelos suportados
    - Modelos Permitidos: RandomForest, LightGBM
  - Máximo de avaliações: 3
  - Máximo de avaliações simultâneas: 3
  - Máximo de nós: 3
  - Limite de pontuação da métrica: 0,085
  - Tempo limite do experimento (minutos): 15
  - Tempo limite de iteração (minutos): 15
  - [X] Habilitar encerramento antecipado
  - Tipo de validação: Divisão de validação de treinamento
    - Validação de percentual de dado: 10


