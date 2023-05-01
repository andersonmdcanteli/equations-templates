# Teste para falta de ajuste

## Hipóteses

* $H_{0}:$ a fonte de erro do modelo é devida aos erros aleatórios;
* $H_{1}:$ a fonte de erro do modelo é devida a erros de ajustamento;

### Código

```
## Hipóteses

* $H_{0}:$ a fonte de erro do modelo é devida aos erros aleatórios;
* $H_{1}:$ a fonte de erro do modelo é devida a erros de ajustamento;
```

## Estatística do teste ($Fcalc_{falta \, ajuste}$)

$$Fcalc_{falta \, ajuste} = \frac{MSQFA}{MSQEP}$$

onde:
* $MSQFA$ é a média do somatório dos quadrados da falta de ajuste;
* $MSQEP$ é a média do somatório dos quadrados do erro puro;

### Código

```
## Estatística do teste ($Fcalc_{falta \, ajuste}$)


$$Fcalc_{falta \, ajuste} = \frac{MSQFA}{MSQEP}$$

onde:
* $MSQFA$ é a média do somatório dos quadrados da falta de ajuste;
* $MSQEP$ é a média do somatório dos quadrados do erro puro;
```

## Estatística do teste ($Fcalc_{falta \, ajuste}$)

$$Fcalc_{falta \, ajuste} = \frac{\frac{\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( \widehat{y}_{ij} - \overline{y_{i}} \right)^{2}}{a - n_{param}}}{\frac{\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( y_{i,j} - \overline{y_{i}} \right)^{2}}{n - a}}$$


onde:
* $a$ é o número de grupos;
* $n_{i}$ é o número de observações do grupo $i$;
* $\widehat{y_{ij}}$ é o valor predito para a i-ésima observação obtida para $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo $i$;
* $n_{param}$ é o número de parâmetros do modelo;
* $n$ é o número total de observações;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;

### Código

```
## Estatística do teste ($Fcalc_{falta \, ajuste}$)

$$Fcalc_{falta \, ajuste} = \frac{\frac{\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( \widehat{y}_{ij} - \overline{y_{i}} \right)^{2}}{a - n_{param}}}{\frac{\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( y_{i,j} - \overline{y_{i}} \right)^{2}}{n - a}}$$


onde:
* $a$ é o número de grupos;
* $n_{i}$ é o número de observações do grupo $i$;
* $\widehat{y_{ij}}$ é o valor predito para a i-ésima observação obtida para $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo $i$;
* $n_{param}$ é o número de parâmetros do modelo;
* $n$ é o número total de observações;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
```

## Valor crítico ($Ftab_{falta \, ajuste}$)

$$Ftab_{falta \, ajuste} = F_{1-\alpha; \, a-n_{param}; \, n-a}$$

Obtido da distribuição F unilateral à direita com $a-n_{param}$ e $n-a$ graus de liberdade.

onde:
* $a$ é o número de grupos;
* $n_{param}$ é o número de parâmetros do modelo;
* $n$ é o número total de observações;
* $\alpha$ é o nível de significância adotado;

### Código

```
## Valor crítico ($Ftab_{falta \, ajuste}$)

$$Ftab_{falta \, ajuste} = F_{1-\alpha; \, a-n_{param}; \, n-a}$$

Obtido da distribuição F unilateral à direita com $a-n_{param}$ e $n-a$ graus de liberdade.

onde:
* $a$ é o número de grupos;
* $n_{param}$ é o número de parâmetros do modelo;
* $n$ é o número total de observações;
* $\alpha$ é o nível de significância adotado;
```

## Conclusão do teste utilizando o $pvalor$

* Se $pvalor < \alpha$ rejeita $H_{0}$;
* Se $pvalor \geq \alpha$ falha em rejeitar $H_{0}$;

### Código

```
## Conclusão do teste utilizando o $pvalor$

* Se $pvalor < \alpha$ rejeita $H_{0}$;
* Se $pvalor \geq \alpha$ falha em rejeitar $H_{0}$;
```

## Conclusão do teste utilizando a estatística ($Fcalc_{falta \, ajuste}$)

* Se $Fcalc_{falta \, ajuste} > F_{1-\alpha; \, a-n_{param}; \, n-a}$ rejeita $H_{0}$;
* Se $Fcalc_{falta \, ajuste} \leq F_{1-\alpha; \, a-n_{param}; \, n-a}$ falha em rejeitar $H_{0}$;

### Código

```
## Conclusão do teste utilizando a estatística ($Fcalc_{falta \, ajuste}$)

* Se $Fcalc_{falta \, ajuste} > F_{1-\alpha; \, a-n_{param}; \, n-a}$ rejeita $H_{0}$;
* Se $Fcalc_{falta \, ajuste} \leq F_{1-\alpha; \, a-n_{param}; \, n-a}$ falha em rejeitar $H_{0}$;
```

## Conclusão do teste utilizando a estatística ($Fcalc_{falta \, ajuste}$)


* Se $Fcalc_{falta \, ajuste} > F_{1-\alpha; \, a-n_{param}; \, n-a}$ rejeita $H_{0}$;
* Se $Fcalc_{falta \, ajuste} \leq F_{1-\alpha; \, a-n_{param}; \, n-a}$ falha em rejeitar $H_{0}$;

### Código

```
## Conclusão do teste utilizando a estatística ($Fcalc_{falta \, ajuste}$)


* Se $Fcalc_{falta \, ajuste} > F_{1-\alpha; \, a-n_{param}; \, n-a}$ rejeita $H_{0}$;
* Se $Fcalc_{falta \, ajuste} \leq F_{1-\alpha; \, a-n_{param}; \, n-a}$ falha em rejeitar $H_{0}$;
```