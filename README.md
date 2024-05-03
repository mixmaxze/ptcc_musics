# Análise de emoções e temas presentes na Música Popular Brasileira com Processamento de Linguagem Natural

## Quer reproduzir os primeiros resultados gerados?

Basta executar o Notebook 3. Ele utiliza os arquivos com os resultados dos modelos LDA e com a classificação de emoções já produzidos anteriormente. Eles estão disponíveis na pasta de artefatos do projeto.

## Quer produzir resultados mais atualizados ou com novos parâmetros?

Para isso, basta executar todos os Notebooks Python. Dessa forma, o Notebook 1 irá capturar as músicas da MPB atualizadas na página do Genius e os seguintes irão gerar novos resultados. Além disso, você pode mexer com os parâmetros utilizados para ver nos modelos e visualizações se comportam com a nova configuração escolhida.

## Para executar TUDO

1. Antes de tudo, baixe e instale o Python no seu sistema operacional. Você pode fazer a partir [daqui](https://www.python.org/downloads/).<br>
2. Depois, você precisa baixar e extrair o ZIP com a pasta do modelo BERTimbau e colocá-la na pasta ``./artefatos``, utilizado para classificar emoções de textos em português. Para baixar diretamente, você pode acessar esse [link](https://drive.google.com/file/d/1srCYkS3dMR41BY0Y3WzMpCydJECfonUj/view). Para conhecer mais desse projeto incrível, você pode acessar o repositório do próprio criador, que se encontra [aqui](https://github.com/Luzo0/GoEmotions_portuguese).<br>
3. Após isso, você deve instalar as dependências necessárias com o comando ``pip install -r ./artefatos/requirements.txt`` no terminal.<br>
4. Por fim, é só abrir o ambiente do Jupyter com o comando ``jupyter notebook`` e executar os notebooks.
