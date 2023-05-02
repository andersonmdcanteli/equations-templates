# Teste de ANOVA

## Hipóteses

* $H_{0}:$ A variância explicada pela regressão é igual a variância devido aos erros de ajuste;
* $H_{1}:$ A variância explicada pela regressão é maior do que a variância devido aos erros de ajuste;

### Código

```
## Hipóteses

* $H_{0}:$ A variância explicada pela regressão é igual a variância devido aos erros de ajuste;
* $H_{1}:$ A variância explicada pela regressão é maior do que a variância devido aos erros de ajuste;
```

## Estatística do teste ($Fcalc$)

$$Fcalc = \frac{MSQR}{MSQE}$$

onde:
* $MSQR$ é a média do somatório dos quadrados da regressão;
* $MSQE$ é a média do somatório dos quadrados dos erros;

### Código

```
## Estatística do teste ($Fcalc$)

$$Fcalc = \frac{MSQR}{MSQE}$$

onde:
* $MSQR$ é a média do somatório dos quadrados da regressão;
* $MSQE$ é a média do somatório dos quadrados dos erros;
```

## Estatística do teste ($Fcalc$)

$$Fcalc = \frac{\frac{\sum_{i=1}^{n} \left(\widehat{y}_{i} - \overline{y} \right)^{2}}{k}}{\frac{\sum_{i=1}^{n} \left(\widehat{y}_{i} - y_{i} \right)^{2}}{n-n_{p}}}$$

onde:
* $n$ é o número total de observações;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$;
* $\overline{y}$ é a média de todas as observações;
* $k$ é o número de parâmetros associados à regressão;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $n_{p}$ é o número de parâmetros do modelo;

### Código

```
## Estatística do teste ($Fcalc$)

$$Fcalc = \frac{\frac{\sum_{i=1}^{n} \left(\widehat{y}_{i} - \overline{y} \right)^{2}}{k}}{\frac{\sum_{i=1}^{n} \left(\widehat{y}_{i} - y_{i} \right)^{2}}{n-n_{p}}}$$

onde:
* $n$ é o número total de observações;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$;
* $\overline{y}$ é a média de todas as observações;
* $k$ é o número de parâmetros associados à regressão;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $n_{p}$ é o número de parâmetros do modelo;
```

## Valor crítico ($Ftab$)

$$Ftab = F_{1-\alpha; \, a-k; \, n-n_{p}}$$

Obtido da distribuição F unilateral à direita com $k$ e $n-n_{p}$ graus de liberdade. Onde

* $n$ é o número total de observações;
* $k$ é o número de parâmetros associados à regressão;
* $n_{p}$ é o número de parâmetros do modelo;
* $\alpha$ é o nível de significância adotado;

### Código

```
## Valor crítico ($Ftab$)

$$Ftab = F_{1-\alpha; \, a-k; \, n-n_{p}}$$

Obtido da distribuição F unilateral à direita com $k$ e $n-n_{p}$ graus de liberdade. Onde

* $n$ é o número total de observações;
* $k$ é o número de parâmetros associados à regressão;
* $n_{p}$ é o número de parâmetros do modelo;
* $\alpha$ é o nível de significância adotado;
```

## Conclusão do teste utilizando o $pvalor$

* Se $pvalor < \alpha$, rejeita $H_{0}$;
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$;

### Código

```
## Conclusão do teste utilizando o $pvalor$

* Se $pvalor < \alpha$, rejeita $H_{0}$;
* Se $pvalor \geq \alpha$, falha em rejeitar $H_{0}$;
```

## Conclusão do teste utilizando a estatística do teste ($Fcalc$)

* Se $Fcalc > F_{1-\alpha; \, a-k; \, n-n_{p}}$, rejeita $H_{0}$;
* Se $Fcalc \leq F_{1-\alpha; \, a-k; \, n-n_{p}}$, falha em rejeitar $H_{0}$;

### Código

```
## Conclusão do teste utilizando a estatística do teste ($Fcalc$)

* Se $Fcalc > F_{1-\alpha; \, a-k; \, n-n_{p}}$, rejeita $H_{0}$;
* Se $Fcalc \leq F_{1-\alpha; \, a-k; \, n-n_{p}}$, falha em rejeitar $H_{0}$;
```