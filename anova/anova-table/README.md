# Tabela de ANOVA

| Fonte de variação | Soma dos quadrados | Grau de liberdade | Média dos quadrados | Estatística | Crítico | p-valor | Conclusão |
| :-: | :-: | :-: |  :-: | :-: | :-: | :-: | :-: |
| Regressão | $SQR$ | $gl_{regressão}$ | $MSQR$ | $Fcalc$ | $Ftab$ | $pvalor$ | * |
| Erros | $SQE$ | $gl_{erros}$ | $MSQE$ |  |  |  |  |
| Total | $SQT$ | $gl_{total}$ | $MSQT$ |  |  |  |  |

## Conclusão

* Se $pvalor < \alpha$, rejeita $H_{0}$; *
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$; *

## Código

```
# Tabela de ANOVA

| Fonte de variação | Soma dos quadrados | Grau de liberdade | Média dos quadrados | Estatística | Crítico | p-valor | Conclusão |
| :-: | :-: | :-: |  :-: | :-: | :-: | :-: | :-: |
| Regressão | $SQR$ | $gl_{regressão}$ | $MSQR$ | $Fcalc$ | $Ftab$ | $pvalor$ | * |
| Erros | $SQE$ | $gl_{erros}$ | $MSQE$ |  |  |  |  |
| Total | $SQT$ | $gl_{total}$ | $MSQT$ |  |  |  |  |

## Conclusão

* Se $pvalor < \alpha$, rejeita $H_{0}$; *
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$; *
```

# Tabela de ANOVA

| Fonte de variação | $SQ$ | $gl$ | $MSQ$ | $Fcalc$ | $Ftab$ | p-valor | Conclusão |
| :-: | :-: | :-: |  :-: | :-: | :-: | :-: | :-: |
| Regressão | $\sum_{i=1}^{n} \left(\widehat{y}_{i} - \overline{y} \right)^{2}$ | $k$ | $\frac{SQR}{gl_{regressão}}$ | $\frac{MSQR}{MSQE}$ | $F_{1-\alpha; \, a-k; \, n-n_{p}}$ | $pvalor$ | * |
| Erros | $\sum_{i=1}^{n} \left(\widehat{y}_{i} - y_{i} \right)^{2}$ | $n-n_{p}$ | $\frac{SQE}{gl_{errors}}$ |  |  |  |  |
| Total | $\sum_{i=1}^{n} \left(y_{i} - \overline{y} \right)^{2}$ | $n-1$ | $\frac{SQT}{gl_{totais}}$ |  |  |  |  |

* Se $pvalor < \alpha$, rejeita $H_{0}$;
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$;

* $n$ é o número total de observações;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$;
* $\overline{y}$ é a média de todas as observações;
* $k$ é o número de parâmetros associados à regressão;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $n_{p}$ é o número de parâmetros do modelo;

## Conclusão

* Se $pvalor < \alpha$, rejeita $H_{0}$; *
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$; *

## Código

```
# Tabela de ANOVA

| Fonte de variação | $SQ$ | $gl$ | $MSQ$ | $Fcalc$ | $Ftab$ | p-valor | Conclusão |
| :-: | :-: | :-: |  :-: | :-: | :-: | :-: | :-: |
| Regressão | $\sum_{i=1}^{n} \left(\widehat{y}_{i} - \overline{y} \right)^{2}$ | $k$ | $\frac{SQR}{gl_{regressão}}$ | $\frac{MSQR}{MSQE}$ | $F_{1-\alpha; \, a-k; \, n-n_{p}}$ | $pvalor$ | * |
| Erros | $\sum_{i=1}^{n} \left(\widehat{y}_{i} - y_{i} \right)^{2}$ | $n-n_{p}$ | $\frac{SQE}{gl_{errors}}$ |  |  |  |  |
| Total | $\sum_{i=1}^{n} \left(y_{i} - \overline{y} \right)^{2}$ | $n-1$ | $\frac{SQT}{gl_{totais}}$ |  |  |  |  |

* Se $pvalor < \alpha$, rejeita $H_{0}$;
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$;

* $n$ é o número total de observações;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$;
* $\overline{y}$ é a média de todas as observações;
* $k$ é o número de parâmetros associados à regressão;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $n_{p}$ é o número de parâmetros do modelo;

## Conclusão

* Se $pvalor < \alpha$, rejeita $H_{0}$; *
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$; *
```

# Tabela de ANOVA completa

| Fonte de variação | Soma dos quadrados | Grau de liberdade | Média dos quadrados | Estatística | Crítico | p-valor | Conclusão |
| :-: | :-: | :-: |  :-: | :-: | :-: | :-: | :-: |
| Regressão | $SQR$ | $gl_{regressão}$ | $MSQR$ | $Fcalc$ | $Ftab$ | $pvalor$ | * |
| Erros | $SQE$ | $gl_{erros}$ | $MSQE$ |  |  |  |  |
| Falta de ajuste | $SQFA$ | $gl_{falta \, ajuste}$ | $MSFA$ | $Fcalc$ | $Ftab$ | $pvalor$ | * |
| Erro puro | $SQEP$ | $gl_{erro \, puro}$ | $MSQEP$ |  |  |  |  |
| Total | $SQT$ | $gl_{total}$ | $MSQT$ |  |  |  |  |

## Conclusão

* Se $pvalor < \alpha$, rejeita $H_{0}$; *
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$; *

## Código

```
# Tabela de ANOVA completa

| Fonte de variação | Soma dos quadrados | Grau de liberdade | Média dos quadrados | Estatística | Crítico | p-valor | Conclusão |
| :-: | :-: | :-: |  :-: | :-: | :-: | :-: | :-: |
| Regressão | $SQR$ | $gl_{regressão}$ | $MSQR$ | $Fcalc$ | $Ftab$ | $pvalor$ | * |
| Erros | $SQE$ | $gl_{erros}$ | $MSQE$ |  |  |  |  |
| Falta de ajuste | $SQFA$ | $gl_{falta \, ajuste}$ | $MSFA$ | $Fcalc$ | $Ftab$ | $pvalor$ | * |
| Erro puro | $SQEP$ | $gl_{erro \, puro}$ | $MSQEP$ |  |  |  |  |
| Total | $SQT$ | $gl_{total}$ | $MSQT$ |  |  |  |  |

## Conclusão

* Se $pvalor < \alpha$, rejeita $H_{0}$; *
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$; *
```

# Tabela e ANOVA

| Fonte de variação | $SQ$ | $gl$ | $MSQ$ | $Fcalc$ | $Ftab$ | p-valor | Conclusão |
| :-: | :-: | :-: |  :-: | :-: | :-: | :-: | :-: |
| Regressão | $\sum_{i=1}^{n} \left(\widehat{y}_{i} - \overline{y} \right)^{2}$ | $k$ | $\frac{SQR}{gl_{regressão}}$ | $\frac{MSQR}{MSQE}$ | $F_{1-\alpha; \, a-k; \, n-n_{p}}$ | $pvalor$ | * |
| Erros | $\sum_{i=1}^{n} \left(\widehat{y}_{i} - y_{i} \right)^{2}$ | $n-n_{p}$ | $\frac{SQE}{gl_{errors}}$ |  |  |  |  |
| Falta de ajuste | $\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( \widehat{y}_{ij} - \overline{y_{i}} \right)^{2}$ | $a - n_{p}$ | $\frac{SQFA}{gl_{falta \, ajuste}}$ | $\frac{MSQR}{MSQE}$ | $F_{1-\alpha; \, a-k; \, n-n_{p}}$ | $pvalor$ | * |
| Erro puro | $\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( y_{i,j} - \overline{y_{i}} \right)^{2}$ | $n - a$ | $\frac{SQEP}{gl_{puro}}$ |  |  |  |  |
| Total | $\sum_{i=1}^{n} \left(y_{i} - \overline{y} \right)^{2}$ | $n-1$ | $\frac{SQT}{gl_{totais}}$ |  |  |  |  |

* Se $pvalor < \alpha$, rejeita $H_{0}$;
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$;

* $n$ é o número total de observações;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$;
* $\overline{y}$ é a média de todas as observações;
* $k$ é o número de parâmetros associados à regressão;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $n_{p}$ é o número de parâmetros do modelo;
* $a$ é o número de grupos;
* $n_{i}$ é o número de observações do grupo $i$;



## Conclusão

* Se $pvalor < \alpha$, rejeita $H_{0}$; *
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$; *

## Código

```
# Tabela e ANOVA

| Fonte de variação | $SQ$ | $gl$ | $MSQ$ | $Fcalc$ | $Ftab$ | p-valor | Conclusão |
| :-: | :-: | :-: |  :-: | :-: | :-: | :-: | :-: |
| Regressão | $\sum_{i=1}^{n} \left(\widehat{y}_{i} - \overline{y} \right)^{2}$ | $k$ | $\frac{SQR}{gl_{regressão}}$ | $\frac{MSQR}{MSQE}$ | $F_{1-\alpha; \, a-k; \, n-n_{p}}$ | $pvalor$ | * |
| Erros | $\sum_{i=1}^{n} \left(\widehat{y}_{i} - y_{i} \right)^{2}$ | $n-n_{p}$ | $\frac{SQE}{gl_{errors}}$ |  |  |  |  |
| Falta de ajuste | $\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( \widehat{y}_{ij} - \overline{y_{i}} \right)^{2}$ | $a - n_{p}$ | $\frac{SQFA}{gl_{falta \, ajuste}}$ | $\frac{MSQR}{MSQE}$ | $F_{1-\alpha; \, a-k; \, n-n_{p}}$ | $pvalor$ | * |
| Erro puro | $\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( y_{i,j} - \overline{y_{i}} \right)^{2}$ | $n - a$ | $\frac{SQEP}{gl_{puro}}$ |  |  |  |  |
| Total | $\sum_{i=1}^{n} \left(y_{i} - \overline{y} \right)^{2}$ | $n-1$ | $\frac{SQT}{gl_{totais}}$ |  |  |  |  |

* Se $pvalor < \alpha$, rejeita $H_{0}$;
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$;

* $n$ é o número total de observações;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$;
* $\overline{y}$ é a média de todas as observações;
* $k$ é o número de parâmetros associados à regressão;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $n_{p}$ é o número de parâmetros do modelo;
* $a$ é o número de grupos;
* $n_{i}$ é o número de observações do grupo $i$;



## Conclusão

* Se $pvalor < \alpha$, rejeita $H_{0}$; *
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$; *
```