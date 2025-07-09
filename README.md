# 📱 Análise de Dependência de Celular em Adolescentes

## 📋 Descrição do Projeto

Este projeto analisa o impacto do uso de smartphones no estilo de vida de adolescentes, usando técnicas de análise exploratória de dados e machine learning para identificar padrões e predizer comportamentos.

**Disciplina:** Inteligência Artificial  
**Professor:** Everton Josué Meyer da Silva  
**Alunos:** Matheus Oliveira, Rebecca Januário, Vitor Hervella

## 🎯 Objetivos

- Analisar padrões de uso de celular entre adolescentes
- Investigar relações entre uso de celular, sono, gênero e outros fatores
- Desenvolver modelos preditivos para nível de dependência
- Avaliar a capacidade de predição do desempenho acadêmico

## 📊 Dataset

**Fonte:** [Teen Phone Addiction and Lifestyle Survey - Kaggle](https://www.kaggle.com/datasets/khushikyad001/teen-phone-addiction-and-lifestyle-survey)

**Características:**
- 3.000 registros de adolescentes
- Variáveis sobre uso de celular, sono, saúde mental e desempenho acadêmico
- Dados de pesquisa sobre estilo de vida e hábitos digitais

## 🛠️ Tecnologias Utilizadas

- **Python 3.x**
- **Pandas** - Manipulação de dados
- **NumPy** - Operações numéricas
- **Matplotlib & Seaborn** - Visualizações
- **Scikit-learn** - Machine Learning
  - Regressão Linear
  - Random Forest
  - Gradient Boosting

## 📁 Estrutura do Projeto

```
├── Teen_Phone_Addiction_EDA.ipynb    # Notebook principal com análises
├── teen_phone_addiction_dataset.csv  # Dataset (baixar do Kaggle)
└── README.md                         # Este arquivo
```

## 🚀 Como Executar

1. **Clone o repositório:**
   ```bash
   git clone [seu-repositorio]
   cd [nome-do-diretorio]
   ```

2. **Instale as dependências:**
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Baixe o dataset:**
   - Acesse o [link do Kaggle](https://www.kaggle.com/datasets/khushikyad001/teen-phone-addiction-and-lifestyle-survey)
   - Baixe o arquivo `teen_phone_addiction_dataset.csv`
   - Coloque no mesmo diretório do notebook

4. **Execute o notebook:**
   ```bash
   jupyter notebook Teen_Phone_Addiction_EDA.ipynb
   ```

## 📈 Análises Realizadas

### 1ª Parte - Análise Exploratória
- Distribuição demográfica (idade e gênero)
- Padrões de uso por atividade (redes sociais, jogos, educação)
- Relações visuais entre uso de celular e sono
- Diferenças de uso entre gêneros
- Impacto da finalidade do uso no nível de dependência

### 2ª Parte - Machine Learning
- **Predição de Nível de Dependência:** Modelos conseguem prever com boa precisão
- **Predição de Desempenho Acadêmico:** Variáveis disponíveis não são suficientes
- **Comparação de Algoritmos:** Random Forest e Gradient Boosting superam Regressão Linear
- **Métricas de Avaliação:** MAE, RMSE e R² para comparação objetiva

## 🔍 Principais Descobertas

- ✅ É possível prever o nível de dependência de celular com alta precisão
- ❌ As variáveis do dataset não são suficientes para prever desempenho acadêmico
- 📊 Modelos de ensemble (Random Forest, Gradient Boosting) superam modelos lineares
- 👥 Existem diferenças nos padrões de uso entre gêneros
- 🔗 A finalidade do uso influencia o nível de dependência

## 📚 Aprendizados

Este projeto demonstra:
- Como realizar análise exploratória de dados eficaz
- Implementação de múltiplos algoritmos de machine learning
- Importância da qualidade e relevância das features para predição
- Técnicas de visualização para comunicar insights
- Avaliação crítica de resultados de modelos

## 🤝 Contribuições

Este é um projeto acadêmico. Para sugestões ou melhorias:
1. Abra uma issue
2. Faça um fork do projeto
3. Crie uma branch para sua feature
4. Faça commit das mudanças
5. Abra um Pull Request

## 📄 Licença

Este projeto é para fins educacionais e acadêmicos.

---

💡 **Nota:** Este projeto faz parte do aprendizado em Inteligência Artificial e demonstra a aplicação prática de técnicas de ciência de dados em problemas reais de saúde pública.
