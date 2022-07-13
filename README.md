
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Análise Juan e Mayara - Enzimas, Estresse e Si.

## Carregando os pacotes necessários

``` r
library(ExpDes.pt)
```

## Entrada de dados

``` r
library(readxl)
enzimas <- read_excel("data/enzimas.xlsx")
#> New names:
#> * Si -> Si...1
#> * Si -> Si...6
head(enzimas)
#> # A tibble: 6 x 16
#>   Si...1 bac   def   Cultivar Estresse Si...6 Trat         Rep   Gpx    Gr   Apx
#>   <chr>  <chr> <chr>    <dbl> <chr>     <dbl> <chr>      <dbl> <dbl> <dbl> <dbl>
#> 1 sSi    sBac  sDef      3280 Controle      0 Controle-0     1  476.  2.22  70.5
#> 2 sSi    sBac  sDef      3280 Controle      0 Controle-0     2  476.  2.22  70.5
#> 3 sSi    sBac  sDef      3280 Controle      0 Controle-0     3  476.  2.22  70.5
#> 4 sSi    sBac  cDef      3280 DH            0 DH-0           1  787.  1.42 179. 
#> 5 sSi    sBac  cDef      3280 DH            0 DH-0           2  743.  1.58 163. 
#> 6 sSi    sBac  cDef      3280 DH            0 DH-0           3  698.  1.27 147. 
#> # ... with 5 more variables: Gpox <dbl>, SOD <dbl>, Prolina <dbl>, FvFm <dbl>,
#> #   MDA <dbl>
```
