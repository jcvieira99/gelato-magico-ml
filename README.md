
# 🍦 Gelato Mágico - Previsão de Vendas com Machine Learning

Bem-vindo ao repositório do projeto **Gelato Mágico**, onde aplicamos Machine Learning para prever a demanda de sorvetes com base na temperatura do dia.

## 🎯 Objetivo

- Prever as vendas de sorvete com base na temperatura.
- Utilizar MLflow para rastreamento e versionamento dos modelos.
- Realizar previsões em tempo real na nuvem.
- Estruturar um pipeline reprodutível de machine learning.

## 🧠 Processo

1. Coleta de dados de temperatura e vendas.
2. Treinamento de um modelo de regressão linear.
3. Registro do modelo no MLflow.
4. Criação de um endpoint para inferência em cloud computing.

## 📁 Estrutura do Projeto

```
gelato-magico-ml/
├── inputs/
│   └── Modelo_AutoML.jpg
│   └── Modelo_Designer.jpg
|   └── sentences.txt
|   └── Dados_Sorvetes.csv
└── README.md
└── Automl-01.json
└── Automl-01.yaml
```

## 📸 Prints do Projeto

### Pipeline de Treinamento com MLflow
![pipeline](https://raw.githubusercontent.com/jcvieira99/gelato-magico-ml/refs/heads/main/inputs/Modelo_Designer.jpg)

• Abaixo está o pipeline construído no Azure ML Automatizado para treinar e avaliar o modelo de regressão linear:

![pipeline](https://raw.githubusercontent.com/jcvieira99/gelato-magico-ml/refs/heads/main/inputs/Modelo_AutoML.jpg)

## 💡 Insights

- Existe uma forte correlação entre temperatura e volume de vendas.
- Modelos simples como regressão linear já oferecem ótimos resultados nesse contexto.
- O MLflow facilita o rastreamento e comparação entre diferentes versões do modelo.

## 🚀 Próximos passos

- Integrar com dados meteorológicos em tempo real.
- Aumentar o histórico de dados para melhorar a acurácia.
- Automatizar a produção com pipelines em cloud (Azure ML, por exemplo).

---

Desenvolvido por Jean Carlos
