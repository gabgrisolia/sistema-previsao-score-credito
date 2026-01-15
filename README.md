# Sistema de Previsão de Score de Crédito 

Projeto de Machine Learning desenvolvido para classificar o score de crédito de clientes bancários em três categorias: **Ruim**, **Ok** ou **Bom**.

## 📋 Sobre o Projeto

Este projeto foi desenvolvido como parte de um case de classificação de crédito. O sistema analisa dados históricos de clientes e utiliza algoritmos de Machine Learning para prever automaticamente o score de crédito de novos clientes, auxiliando instituições financeiras na tomada de decisões sobre concessão de crédito.

## 🎯 Objetivo

Criar um modelo de Inteligência Artificial capaz de analisar as informações de um cliente e classificar automaticamente seu score de crédito, facilitando a avaliação de risco creditício.

## 🚀 Funcionalidades

- ✅ Análise e tratamento de dados de clientes
- ✅ Pré-processamento de dados categóricos (profissão, mix de crédito, comportamento de pagamento)
- ✅ Treinamento de múltiplos modelos de Machine Learning (RandomForest e KNN)
- ✅ Comparação de modelos para seleção do melhor algoritmo
- ✅ Previsão de score de crédito para novos clientes

## 📊 Dados Utilizados

O projeto utiliza um dataset com **100.000 clientes** contendo informações como:

- Dados demográficos (idade, profissão, salário anual)
- Histórico creditício (número de contas, cartões, empréstimos)
- Comportamento financeiro (dias de atraso, pagamentos atrasados, dívida total)
- Indicadores financeiros (taxa de uso de crédito, investimento mensal, saldo final do mês)
- Tipos de empréstimos (carro, casa, pessoal, crédito, estudantil)

## 🛠️ Tecnologias Utilizadas

- **Python**
- **Pandas** - Manipulação e análise de dados
- **Scikit-learn** - Machine Learning
  - `RandomForestClassifier` - Modelo de Árvore de Decisão
  - `KNeighborsClassifier` - Modelo KNN
  - `LabelEncoder` - Codificação de variáveis categóricas
  - `train_test_split` - Divisão de dados para treino e teste
  - `accuracy_score` - Métrica de avaliação

## 📁 Estrutura do Projeto

```
.
├── inicial (1).ipynb      # Notebook principal com todo o código
├── clientes.csv           # Dataset de treinamento (100.000 clientes)
├── novos_clientes.csv     # Dataset para previsões
└── README.md              # Este arquivo
```

## 🔧 Como Usar

### Pré-requisitos

```bash
pip install pandas scikit-learn
```

### Executando o Projeto

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd <nome-do-repositorio>
```

2. Abra o notebook `inicial (1).ipynb` no Jupyter Notebook ou JupyterLab

3. Execute as células sequencialmente seguindo os passos:
   - **Passo 1**: Importação da base de dados
   - **Passo 2**: Tratamento e preparação dos dados
   - **Passo 3**: Criação dos modelos de IA
   - **Passo 4**: Avaliação e comparação dos modelos
   - **Passo 5**: Previsões para novos clientes

## 📈 Metodologia

O projeto segue uma metodologia estruturada de Machine Learning:

1. **Importação dos dados**: Carregamento do dataset de clientes
2. **Pré-processamento**: Codificação de variáveis categóricas usando LabelEncoder
3. **Divisão dos dados**: Separação em conjunto de treino (70%) e teste (30%)
4. **Treinamento dos modelos**: Criação e treinamento de RandomForest e KNN
5. **Avaliação**: Comparação dos modelos usando acurácia
6. **Predição**: Aplicação do melhor modelo em novos clientes

## 🎓 Aprendizados

- Processamento de dados para Machine Learning
- Classificação multiclasse
- Comparação de algoritmos de Machine Learning
- Métricas de avaliação de modelos
- Pipeline completo de um projeto de IA

## 📝 Observações

- O modelo RandomForest demonstrou melhor desempenho em comparação ao KNN
- O dataset possui 25 features (atributos) para previsão
- O projeto utiliza classificação supervisionada

## 👤 Autor

Desenvolvido como parte do aprendizado em Machine Learning e Inteligência Artificial.

## 📄 Licença

Este projeto é de código aberto e está disponível para fins educacionais.
