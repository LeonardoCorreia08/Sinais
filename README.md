#  Exploração de Áudio como Sinais

Bem-vindo(a) ao projeto de **Exploração de Áudio como Sinais**! 

Este repositório contém um Jupyter Notebook voltado para iniciantes em processamento de sinais e áudio. O objetivo é fornecer uma maneira simples, visual e interativa de carregar arquivos de áudio, entender suas propriedades básicas e visualizar seus padrões sem complicações matemáticas excessivas.

##  O que este projeto faz?

O notebook incluído (`Sinais_de_Audios.ipynb`) procura automaticamente por arquivos `.wav` na mesma pasta em que está localizado e ajuda você a:

1. **Extrair Informações Básicas:** Descobrir a taxa de amostragem (Sample Rate) e a duração exata de cada arquivo.
2. **Visualizar Formas de Onda (Waveforms):** Plotar a amplitude do som ao longo do tempo, permitindo ver a "forma" do áudio, identificar picos de volume e momentos de silêncio.
3. **Analisar Espectrogramas:** Visualizar as frequências do áudio ao longo do tempo, ajudando a identificar a "assinatura" de diferentes sons (como vozes, instrumentos ou ruídos).
4. **Reproduzir o Áudio:** Ouvir os arquivos de som diretamente no próprio notebook, facilitando a comparação entre o que você ouve e o que você vê nos gráficos.

##  Estrutura do Projeto

* `Sinais_de_Audios.ipynb`: O notebook principal com todas as explicações, códigos e gráficos.
* `*.wav`: Você deve colocar os seus arquivos de áudio (formato WAV) na mesma pasta do notebook para que sejam detectados automaticamente.

##  Pré-requisitos

Para executar este projeto, você precisará ter o Python instalado, além das seguintes bibliotecas:

* `librosa` (a principal biblioteca para análise de áudio em Python)
* `matplotlib` (para gerar os gráficos)
* `numpy` (para manipulação de matrizes e cálculos matemáticos)
* `jupyter` ou `ipython` (para rodar o notebook e reproduzir o áudio)

Você pode instalar todas as dependências de uma vez executando o seguinte comando no seu terminal:

```bash
pip install librosa matplotlib numpy jupyter
```

##  Como Executar

1. Baixe o arquivo `Sinais_de_Audios.ipynb` e coloque-o em uma pasta no seu computador.
2. Adicione alguns arquivos de áudio com extensão `.wav` nessa mesma pasta.
3. Abra o terminal (ou prompt de comando), navegue até a pasta onde salvou os arquivos e digite:
   ```bash
   jupyter notebook
   ```
4. O seu navegador vai abrir. Clique no arquivo `Sinais_de_Audios.ipynb`.
5. Leia as breves explicações e execute as células de código uma por uma (usando `Shift + Enter`). O código fará o resto!

##  Dicas para Iniciantes

Se você é novo no processamento de sinais, não se assuste com os arrays de números! Pense no áudio digital como uma fotografia rápida (amostra) da pressão do ar tirada milhares de vezes por segundo. O notebook guiará você passo a passo para transformar esses números em imagens compreensíveis.
