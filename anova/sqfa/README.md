# Somatório dos quadrados da falta de ajuste ($SQFA$)

$$SQFA = \sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( \widehat{y}_{ij} - \overline{y_{i}} \right)^{2}$$

onde:
* $n$ é o número total de observações;
* $n_{i}$ é o número de observações do grupo $i$;
* $a$ é o número de grupos;
* $\widehat{y_{ij}}$ é o valor predito para a i-ésima observação obtida para $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo $i$;

## Código

```
# Somatório dos quadrados da falta de ajuste ($SQFA$)

$$SQFA = \sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( \widehat{y}_{ij} - \overline{y_{i}} \right)^{2}$$

onde:
* $n$ é o número total de observações;
* $n_{i}$ é o número de observações do grupo $i$;
* $a$ é o número de grupos;
* $\widehat{y_{ij}}$ é o valor predito para a i-ésima observação obtida para $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo $i$;
```

# Grau de liberdade dos quadrados da falta de ajuste ($gl_{falta \, ajuste}$)

$$gl_{falta \, ajuste} = n - n_{param}$$

onde:
* $n$ é o número total de observações;
* $n_{param}$ é o número de parâmetros do modelo;

## Código

```
# Grau de liberdade dos quadrados da falta de ajuste ($gl_{falta \, ajuste}$)

$$gl_{falta \, ajuste} = n - n_{param}$$

onde:
* $n$ é o número total de observações;
* $n_{param}$ é o número de parâmetros do modelo;
```

# Média da soma dos quadrados da falta de ajuste ($MSQFA$)

$$MSQFA = \frac{SQFA}{gl_{falta \, ajuste}}$$

onde:
* $SQFA$ é o somatório dos quadrados da falta de ajuste;
* $gl_{falta \, ajuste}$ é o grau de liberdade do somatório dos quadrados da falta de ajuste;

## Código

```
# Média da soma dos quadrados da falta de ajuste ($MSQFA$)

$$MSQFA = \frac{SQFA}{gl_{falta \, ajuste}}$$

onde:
* $SQFA$ é o somatório dos quadrados da falta de ajuste;
* $gl_{falta \, ajuste}$ é o grau de liberdade do somatório dos quadrados da falta de ajuste;
```

# Média da soma dos quadrados da falta de ajuste ($MSQFA$)

$$MSQFA = \frac{\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( \widehat{y}_{ij} - \overline{y_{i}} \right)^{2}}{n - n_{param}}$$

onde:
* $n$ é o número total de observações;
* $n_{i}$ é o número de observações do grupo $i$;
* $a$ é o número de grupos;
* $\widehat{y_{ij}}$ é o valor predito para a i-ésima observação obtida para $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo $i$;
* $n_{param}$ é o número de parâmetros do modelo;

## Código

```
# Média da soma dos quadrados da falta de ajuste ($MSQFA$)

$$MSQFA = \frac{\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( \widehat{y}_{ij} - \overline{y_{i}} \right)^{2}}{n - n_{param}}$$

onde:
* $n$ é o número total de observações;
* $n_{i}$ é o número de observações do grupo $i$;
* $a$ é o número de grupos;
* $\widehat{y_{ij}}$ é o valor predito para a i-ésima observação obtida para $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo $i$;
* $n_{param}$ é o número de parâmetros do modelo;
```