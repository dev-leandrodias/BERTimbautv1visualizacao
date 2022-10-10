# Visualização dos Embeddings da Obra As Vítimas-Algozes, de Joaquim Manuel de Macedo

Visualização dos embeddings das janelas de sentenças comtendo a palavra **"negro"** na Obra As Vítimas-Algozes, de Joaquim Manuel de Macedo geradas pelo BERTimbau utilizando o Embedding Projector.
https://projector.tensorflow.org/

Os arquivos utilizados pelo visualizador esta disponivel na pasta: **"compooling"**.


## A pasta **"compooling"** possui 7 versões de tamanhos de janelas:
- 0 - Visualizaçaõ de todas as janela de tamanho 3 ate 13 com palavra negro
- 1 - Visualizaçaõ da janela de tamanho 3 com palavra negro
- 2 - Visualizaçaõ da janela de tamanho 5 com palavra negro
- 3 - Visualizaçaõ da janela de tamanho 7 com palavra negro
- 4 - Visualizaçaõ da janela de tamanho 9 com palavra negro
- 5 - Visualizaçaõ da janela de tamanho 11 com palavra negro
- 6 - Visualizaçaõ da janela de tamanho 13 com palavra negro


**Link** para o Embedding Projector com pooling através do arquivo config_pool.json:
<https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/dev-leandrodias/BERTimbautv1visualizacao/main/config_pool.json>

## Geração dos arquivos

Os arquivos utilizados pelo Embedding Projector foram gerados pelo notebook: https://github.com/dev-leandrodias/BERTimbautv1visualizacao/blob/main/ExemplosVisualizacaoEmbeddingBERT_pt_br.ipynb.
