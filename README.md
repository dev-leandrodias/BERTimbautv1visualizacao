# Visualização dos Embeddings de Obras Literárias

Visualização dos embeddings das Obras As Vítimas-Algozes, de Joaquim Manuel de Macedo geradas pelo BERTimbau utilizando o Embedding Projector.
https://projector.tensorflow.org/

Os arquivos utilizados pelo visualizados estão divididos em duas pastas: **"compooling"** e **"sempooling"**. Quem indicam se foi utilizado o pooling dos embeddings dos tokens das palavras fora do vocabulário.

## A pasta **"compooling"** possui 1 versão da As Vítimas-Algozes, de Joaquim Manuel de Macedo com os embeddings  das palavras e sua POS-Tag:
- 1 - Concatenação das 4 últimas camadas do BERTimbau base


**Link** para o Embedding Projector com pooling através do arquivo config_pool.json:
<https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config_pool.json>

## Geração dos arquivos

Os arquivos utilizados pelo Embedding Projector foram gerados pelo notebook: https://github.com/dev-leandrodias/BERTimbautv1visualizacao/blob/main/ExemplosVisualizacaoEmbeddingBERT_pt_br.ipynb.
