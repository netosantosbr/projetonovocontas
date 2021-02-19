Pacote Contas
================
José Alfredo
18/02/2021

``` r
library(Projetonovo)
```

Este é um pacote é simples e serve apenas como demonstração do
aprendizado em aula sobre como construir um pacote em R e subir para o
github. Este pacote possui duas funções: somar e subtrair.

## Instalação

Para instalar os pacotes, use os comandos abaixo.

``` r
devtools::install_github("netosantosbr/projetonovocontas")
```

Não se esqueça de rodar o pacote.

``` r
library(Projetonovo)
```

## Usando as funções

Esta função serve para somar.

``` r
somar(2, 3)
```

    ## [1] 5

Esta função subtrai.

``` r
subtrair(2,3)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax
for authoring HTML, PDF, and MS Word documents. For more details on
using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that
includes both content as well as the output of any embedded R code
chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

## Including Plots

You can also embed plots, for example:

![](README_files/figure-gfm/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to
prevent printing of the R code that generated the plot.
