# Somatório dos quadrados dos erros ($SQE$)

$$SQE = \sum_{i=1}^{n} \left(\widehat{y}_{i} - y_{i} \right)^{2}$$

onde:
    
* $n$ é o número total de observações;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$

## Código

```
# Somatório dos quadrados dos erros ($SQE$)

$$SQE = \sum_{i=1}^{n} \left(\widehat{y}_{i} - y_{i} \right)^{2}$$

onde:
    
* $n$ é o número total de observações;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$
```

# Grau de liberdade dos quadrados dos erros ($gl_{erros}$)

$$gl_{erros}=n-n_{p}$$

onde:
* $n$ é o número total de observações;
* $n_{p}$ é o número de parâmetros do modelo;

## Código

```
# Grau de liberdade dos quadrados dos erros ($gl_{erros}$)

$$gl_{erros}=n-n_{p}$$

onde:
* $n$ é o número total de observações;
* $n_{p}$ é o número de parâmetros do modelo;
```

# Média dos quadrados dos erros ($MSQE$)

$$MSQE=\frac{SQE}{gl_{errors}}$$

onde:
* $SQE$ é o somatório dos quadrados dos erros;
* $gl_{erros}$ é o grau de liberdade do somatório dos quadrados dos erros;

## Código

```
# Média dos quadrados dos erros ($MSQE$)

$$MSQE=\frac{SQE}{gl_{errors}}$$

onde:
* $SQE$ é o somatório dos quadrados dos erros;
* $gl_{erros}$ é o grau de liberdade do somatório dos quadrados dos erros;
```

# Média dos quadrados dos erros ($MSQE$)

$$MSQE=\frac{\sum_{i=1}^{n} \left(y_{i} - \widehat{y}_{i} \right)^{2}}{n-n_{p}}$$

onde:
* $n$ é o número total de observações;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$
* $n_{p}$ é o número de parâmetros do modelo;

## Código

```
# Média dos quadrados dos erros ($MSQE$)

$$MSQE=\frac{\sum_{i=1}^{n} \left(y_{i} - \widehat{y}_{i} \right)^{2}}{n-n_{p}}$$

onde:
* $n$ é o número total de observações;
* $y_{i}$ é a i-ésima observação obtida em $x_{i}$;
* $\widehat{y}_{i}$ é o valor predito pelo modelo para a i-ésima observação obtida em $x_{i}$
* $n_{p}$ é o número de parâmetros do modelo;
```