# Somatório dos quadrados do erro puro ($SQEP$)

$$SQEP = \sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( y_{i,j} - \overline{y_{i}} \right)^{2}$$

onde:
* $n$ é o número total de observações;
* $a$ é o número de grupos;
* $n_{i}$ é o número de observações do grupo $i$;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo i;

## Código

```
# Somatório dos quadrados do erro puro ($SQEP$)

$$SQEP = \sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( y_{i,j} - \overline{y_{i}} \right)^{2}$$

onde:
* $n$ é o número total de observações;
* $a$ é o número de grupos;
* $n_{i}$ é o número de observações do grupo $i$;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo i;
```

# Grau de liberdade dos quadrados do erro puro ($gl_{puro}$)

$$gl_{puro} = n - a$$

onde:
* $n$ é o número total de observações;
* $a$ é o número de grupos;

## Código

```
# Grau de liberdade dos quadrados do erro puro ($gl_{puro}$)

$$gl_{puro} = n - a$$

onde:
* $n$ é o número total de observações;
* $a$ é o número de grupos;
```

# Média da soma dos quadrados do erro puro  ($MSQEP$)

$$MSQEP = \frac{SQEP}{gl_{puro}}$$

onde:
* $SQEP$ é o somatório dos quadrados do erro puro;
* $gl_{puro}$ é o grau de liberdade do somatório dos quadrados do erro puro;

## Código

```
# Média da soma dos quadrados do erro puro  ($MSQEP$)

$$MSQEP = \frac{SQEP}{gl_{puro}}$$

onde:
* $SQEP$ é o somatório dos quadrados do erro puro;
* $gl_{puro}$ é o grau de liberdade do somatório dos quadrados do erro puro;
```

# Média da soma dos quadrados do erro puro  ($MSQEP$)

$$MSQEP = \frac{\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( y_{i,j} - \overline{y_{i}} \right)^{2}}{n - a}$$

onde:
* $n$ é o número total de observações;
* $a$ é o número de grupos;
* $n_{i}$ é o número de observações do grupo $i$;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo i;

## Código

```
# Média da soma dos quadrados do erro puro  ($MSQEP$)

$$MSQEP = \frac{\sum_{i=1}^{a} \sum_{j=1}^{n_{i}} \left( y_{i,j} - \overline{y_{i}} \right)^{2}}{n - a}$$

onde:
* $n$ é o número total de observações;
* $a$ é o número de grupos;
* $n_{i}$ é o número de observações do grupo $i$;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $\overline{y_{i}}$ é a média do grupo i;
```