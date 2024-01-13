![plot](https://raw.githubusercontent.com/programacao-eletronica/img/master/banner.png)

<br /> 

** **
<br /> 

# Notebooks python �teis para DSP

Neste reposit�rio encontram-se diversos notebooks �teis para gera��o de sinais, filtros, interpreta��o, entre outros (em desenvolvimento). Os c�digos est�o desenvolvidos no formato Jupyter Notebook (em Python), e podem ser executados dentro do Google Colab. Mais informa��es sobre essas ferramentas podem ser encontradas abaixo:

- [O que faz um Jupyter Notebook? (v�deo)](https://www.youtube.com/watch?v=CFJaCB_K5bo&ab_channel=Alura)
- [O que � o Jupyter Notebook?](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html)
- [O que � o Google Colab?](https://www.alura.com.br/artigos/google-colab-o-que-e-e-como-usar)

## Importante:

O c�digo dos notebooks jupyter s�o renderizados pelo GitHub. Isso significa que � poss�vel visualizar todo o c�digo (bem como as sa�das de dados salvas) diretamente em cada notebook. Por�m, caso voc� deseje executar o c�digo ou fazer altera��es e salv�-las, � necess�rio abrir dentro do pr�prio Google Colab. Para isso, basta clicar no badge <a><img src="https://colab.research.google.com/assets/colab-badge.svg"></a> dentro de cada notebook.

## Lista de notebooks

<br /> 

- [Gerador de buffer de sinais](./Gerador%20de%20buffer%20de%20sinais/Gerador%20de%20buffer%20de%20sinais.ipynb): �til para gerar um buffer de sinais em c, de tipo configur�vel (`uint8_t`, `uint16_t`, `uint32_t`, `float` ou um n�mero espec�fico de `bits` para simular leituras AD) com base em senoides de frequencias e amplitudes tambem configuraveis. Mais informa��es [neste post](https://programacaoeletronica.wordpress.com/2024/01/02/jupyter-notebook-gerador-de-buffer-de-senoides-em-c/).
- [Gerador de janelas](./Gerador%20de%20janelas/Gerador%20de%20janelas.ipynb): �til para gerar fun��es de janelamento em c, de tipo configur�vel (`int8_t`, `uint8_t`, `int16_t`, `uint16_t`, `int32_t`, `uint32_t` ou `float`) com base em senoides de frequencias e amplitudes tambem configuraveis. Mais informa��es [neste post](https://programacaoeletronica.wordpress.com/2024/01/13/jupyter-notebook-gerador-de-janelas-em-c/).