# Projeto | Análise de Sentimentos 

## Descrição

Neste projeto implementamos e comparamos **4 abordagens** de análise de sentimentos, evoluindo progressivamente em complexidade:

1. **Regressão Logística** — implementada do zero com gradient descent
2. **Naive Bayes** — implementado do zero com Laplace smoothing
3. **Naive Bayes + TF-IDF** — usando scikit-learn com reviews da Kindle
4. **DistilBERT** — modelo pré-treinado via HuggingFace Transformers

## Datasets

- **Tweets NLTK** — 10.000 tweets positivos/negativos (`twitter_samples`)
- **Reviews Kindle** — 1.000 reviews da Amazon (`kindle_reviews_sampled.csv`)

## Requisitos

Antes de correr o notebook, instala as dependências no WSL:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn nltk transformers torch
```

## Submissão

- Após completar, adiciona os ficheiros ao git.
- Faz commit e push para o repositório remoto.
- Cria um pull request e cola o link no Student Portal.

<br>

