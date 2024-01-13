![plot](https://raw.githubusercontent.com/programacao-eletronica/img/master/banner.png)

<br /> 

** **
<br /> 

# Notebooks python úteis para DSP

Neste repositório encontram-se diversos notebooks úteis para geração de sinais, filtros, interpretação, entre outros (em desenvolvimento). Os códigos estão desenvolvidos no formato Jupyter Notebook (em Python), e podem ser executados dentro do Google Colab. Mais informações sobre essas ferramentas podem ser encontradas abaixo:

- [O que faz um Jupyter Notebook? (vídeo)](https://www.youtube.com/watch?v=CFJaCB_K5bo&ab_channel=Alura)
- [O que é o Jupyter Notebook?](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html)
- [O que é o Google Colab?](https://www.alura.com.br/artigos/google-colab-o-que-e-e-como-usar)

## Importante:

O código dos notebooks jupyter são renderizados pelo GitHub. Isso significa que é possível visualizar todo o código (bem como as saídas de dados salvas) diretamente em cada notebook. Porém, caso você deseje executar o código ou fazer alterações e salvá-las, é necessário abrir dentro do próprio Google Colab. Para isso, basta clicar no badge <a><img src="https://colab.research.google.com/assets/colab-badge.svg"></a> dentro de cada notebook.

## Lista de notebooks

<br /> 

- [Gerador de buffer de sinais](./Gerador%20de%20buffer%20de%20sinais/Gerador%20de%20buffer%20de%20sinais.ipynb): útil para gerar um buffer de sinais em c, de tipo configurável (`uint8_t`, `uint16_t`, `uint32_t`, `float` ou um número específico de `bits` para simular leituras AD) com base em senoides de frequencias e amplitudes tambem configuraveis. Mais informações [neste post](https://programacaoeletronica.wordpress.com/2024/01/02/jupyter-notebook-gerador-de-buffer-de-senoides-em-c/).
- [Gerador de janelas](./Gerador%20de%20janelas/Gerador%20de%20janelas.ipynb): útil para gerar funções de janelamento em c, de tipo configurável (`int8_t`, `uint8_t`, `int16_t`, `uint16_t`, `int32_t`, `uint32_t` ou `float`) com base em senoides de frequencias e amplitudes tambem configuraveis. Mais informações [neste post](https://programacaoeletronica.wordpress.com/2024/01/13/jupyter-notebook-gerador-de-janelas-em-c/).