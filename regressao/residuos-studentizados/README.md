# Resíduos studentizados ($resíduos \; studentizados$)

$$resíduos \; studentizados_{i} = \frac{resíduo_{i}}{\sqrt{MSQE \times \left( 1 - h_{ii} \right)}}$$

onde:
* $resíduo_{i}$ é o resíduo da i-ésima observação;
* $MSQE$ é a média dos quadrados dos erros;
* $h_{ii}$ é a alavancagem da i-ésima observação;

## Código

```
# Resíduos studentizados ($resíduos \; studentizados$)

$$resíduos \; studentizados_{i} = \frac{resíduo_{i}}{\sqrt{MSQE \times \left( 1 - h_{ii} \right)}}$$

onde:
* $resíduo_{i}$ é o resíduo da i-ésima observação;
* $MSQE$ é a média dos quadrados dos erros;
* $h_{ii}$ é a alavancagem da i-ésima observação;
```

# Resíduos studentizados ($resíduos \; studentizados$)

$$resíduos \; studentizados_{i} = \frac{y_{i} - \widehat{y_{i}}}{\sqrt{MSQE \times \left( 1 - h_{ii} \right)}}$$

onde:
* $y_{i}$ é a i-ésima observação;
* $\widehat{y_{i}}$ é o valor predito pelo modelo para a i-ésima observação;
* $MSQE$ é a média dos quadrados dos erros;
* $h_{ii}$ é a alavancagem da i-ésima observação;

## Código

```
# Resíduos studentizados ($resíduos \; studentizados$)

$$resíduos \; studentizados_{i} = \frac{y_{i} - \widehat{y_{i}}}{\sqrt{MSQE \times \left( 1 - h_{ii} \right)}}$$

onde:
* $y_{i}$ é a i-ésima observação;
* $\widehat{y_{i}}$ é o valor predito pelo modelo para a i-ésima observação;
* $MSQE$ é a média dos quadrados dos erros;
* $h_{ii}$ é a alavancagem da i-ésima observação;
```

# Resíduos studentizados ($r$)

$$r_{i} = \frac{y_{i} - \widehat{y_{i}}}{\sqrt{\frac{\sum_{i=1}^{n} \left(y_{i} - \widehat{y}_{i} \right)^{2}}{n-n_{p}} \times \left( 1 - h_{ii} \right)}}$$

onde:
* $y_{i}$ é a i-ésima observação;
* $\widehat{y_{i}}$ é o valor predito pelo modelo para a i-ésima observação;
* $n$ é o número total de observações;
* $n_{p}$ é o número de parâmetros do modelo;
* $h_{ii}$ é a alavancagem da i-ésima observação;

## Código

```
# Resíduos studentizados ($r$)

$$r_{i} = \frac{y_{i} - \widehat{y_{i}}}{\sqrt{\frac{\sum_{i=1}^{n} \left(y_{i} - \widehat{y}_{i} \right)^{2}}{n-n_{p}} \times \left( 1 - h_{ii} \right)}}$$

onde:
* $y_{i}$ é a i-ésima observação;
* $\widehat{y_{i}}$ é o valor predito pelo modelo para a i-ésima observação;
* $n$ é o número total de observações;
* $n_{p}$ é o número de parâmetros do modelo;
* $h_{ii}$ é a alavancagem da i-ésima observação;
```