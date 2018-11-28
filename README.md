# ThinkPythonIpynbPtBr
Think Python's Jupyter notebooks in Brazilian Portuguese.

This Jupyter notebook files were developed from markdown files shared by [Luciano Ramalho](https://github.com/ramalho) at [`PenseAllen/PensePython2e/docs/`](https://github.com/PenseAllen/PensePython2e/tree/master/docs).

# Ipynbs do Pense em Python

<a href="https://novatec.com.br/livros/pense-em-python/"><img src="https://github.com/PenseAllen/PensePython2e/raw/master/img/Capa_PenseEmPython167x232.png" align="right" style="margin-left: 20px;"></a>

Adaptação do livro [Think Python](http://greenteapress.com/wp/think-python-2e/) (2ª edição), de [Allen B. Downey](https://github.com/AllenDowney), publicado sob licença [CC BY-NC 3.0](LICENSE.md) e disponibilizado em português brasileiro por [Luciano Ramalho](https://github.com/thoughtworks) no repositório [PensePython2e](https://github.com/PenseAllen/PensePython2e).

Este livro ensina programação para quem nunca programou, usando Python 3 nos exemplos. É aplicado no Olin College, IBMEC e outras faculdades de engenharia excelentes.

> __DICA__: Você pode comprar um exemplar impresso de [__Pense em Python__](https://novatec.com.br/livros/pense-em-python/) no site da [Editora Novatec](https://novatec.com.br/livros/pense-em-python/) ou em livrarias. [ISBN: 978-85-7522-508-0](https://novatec.com.br/livros/pense-em-python/).

[Versão navegável em HTML](https://PenseAllen.github.io/PensePython2e/)


## Como rodar os Ipynbs

Para executar os arquivos _.ipynb_ de forma interativa, você pode clicar no botão

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cfsouza/PensePython2e-Ipynb/master)

ou ainda baixar (ou clonar) os arquivos e os executar via internet no [CoCalc](www.cocalc.com) ou no [Microsoft Azure](https://notebooks.azure.com), ou ainda poderá instalar o [JupyterLab](https://github.com/jupyterlab/jupyterlab) para executar os arquivos no seu computador. Abra o JupyterLab a partir de um terminal (Prompt de comandos) já na pasta onde estão os arquivos baixados e bom estudo.

## Proveniência

Agradecemos a [Luciano Ramalho](https://github.com/ramalho) por ter disponibilizado os arquivos _markdown_ separados por capítulo de [Pense em Python](https://novatec.com.br/livros/pense-em-python/), publicados sob licença [CC BY-NC 3.0](LICENSE.md), em [`PenseAllen/PensePython2e/docs/`](https://github.com/PenseAllen/PensePython2e/docs/).

Cada arquivo _markdown_ foi convertido para _ipynb_ com a ferramenta [notedown](https://github.com/aaren/notedown) disponibilizada por Aaron O'Leary, sob a licença [BSD-2-Clause](https://github.com/aaren/notedown/blob/master/LICENSE), a quem também agradecemos. Para conversão, utilizamos a seguinte linha de comando:

```bash
$ notedown input.md > output.ipynb
```

A partir desse ponto, os ajustes de definição de tipo de célula por conteúdo nos capítulos foram feitos manualmente, sendo (i) incluídas em cada capítulo poucas células de código, para permitir experiência mais didática de interação com o documento, (ii) substituído o uso do módulo `turtle` pelo `mobilechelonian`, para utilizar o módulo `turtle` _inline_ no capítulo 4, e (iii) substituídas menções a números de páginas por número do capítulo.
