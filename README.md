Tema "SaoPaulo" para beamer
===========================

Nesse diretório está um tema para a classe `beamer` seguindo as cores oficiais
da Universidade de São Paulo (USP) e da Escola Politécnica (EP) da
universidade, respectivamente, baseado no tema `Berlin`. Denomina-se
`SaoPaulo` (sede do campus) de modo a combinar com o nome dos outros
temas (`CambridgeUS`, `AnnArbor`, entre outros). Esse projeto é completamente
extraoficial, sem relação direta com a instituição em questão.

O diretório inclui um tema de cores (`southernlapwing` --- Quero-Quero, de forma
semelhante a `dove` ou `crane`), inspirado no tema `seagull`, que obedece às
[identidades](http://www.scs.usp.br/identidadevisual/)
[visuais](https://www.poli.usp.br/wp-content/uploads/2020/06/Manual2.pdf)
das instituições em questão, e um tema interno (`thinframes`) baseado no
tema `miniframes`, com algumas poucas modificações.

Uso
---

Copiar os arquivos `*.sty` no diretório no qual se localiza o código-fonte da
apresentação. Inserir no preâmbulo:

```
\usetheme{SaoPaulo}
```

Caso se queiram as cores da Escola Politécnica, deve-se substituir o
trecho acima por:

```
\usetheme[poli]{SaoPaulo}
```

É possível usar apenas o tema de cores. Para tema de cores versão "USP",
basta inserir no preâmbulo:

```
\usecolortheme{southernlapwing}
```

Para adoção do tema de cores versão "POLI", seguimos sintaxe semelhante:

```
\usecolortheme[poli]{southernlapwing}
```


Autor
-----

Pedro Callil <pedrocallil@usp.br>
