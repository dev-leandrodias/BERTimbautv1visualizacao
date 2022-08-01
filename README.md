# Visualização dos Embeddings do Cohebert

Visualização dos embeddings de Obras Literárias geradas pelo BERTimbau utilizando o Embedding Projector.
https://projector.tensorflow.org/

Os arquivos utilizados pelo visualizados estão divididos em duas pastas: **"compooling"** e **"sempooling"**. Quem indicam se foi utilizado o pooling dos embeddings dos tokens das palavras fora do vocabulário.

## A pasta **"sempooling"** possui os embeddings dos tokens:
- 1 - Concatenação das 4 últimas camadas do BERTimbau base

**Link** para o Embedding Projector sem pooling através do arquivo config.json:
<https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config_pool.json>

## A pasta **"compooling"** possui os embeddings das palavras e sua POS-Tag:
- 1 - Concatenação das 4 últimas camadas do BERTimbau base

**Link** para o Embedding Projector com pooling através do arquivo config_pool.json:
<https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config.json>

## Geração dos arquivos

Os arquivos utilizados pelo Embedding Projector foram gerados pelo notebook: https://github.com/dev-leandrodias/BERTimbautv1visualizacao/blob/main/ExemplosVisualizacaoEmbeddingBERT_pt_br.ipynb.
