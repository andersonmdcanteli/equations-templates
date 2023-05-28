# Resíduos studentizados deletados ($resíduos \; deletados$)

$$resíduo \; deletado = \frac{resíduo_{i}}{\sqrt{MSQE_{i} \left(1 - h_{ii} \right)}}$$

onde:
* $resíduo_{i}$ é o resíduo da i-ésima observação;
* $MSQE_{i}$ é a média dos quadrados dos erros excluindo a i-ésima observação;
* $h_{ii}$ é a alavancagem da i-ésima observação;

## Código

```
# Resíduos studentizados deletados ($resíduos \; deletados$)

$$resíduo \; deletado = \frac{resíduo_{i}}{\sqrt{MSQE_{i} \left(1 - h_{ii} \right)}}$$

onde:
* $resíduo_{i}$ é o resíduo da i-ésima observação;
* $MSQE_{i}$ é a média dos quadrados dos erros excluindo a i-ésima observação;
* $h_{ii}$ é a alavancagem da i-ésima observação;
```

# Resíduos studentizados deletados ($resíduos \; deletados$)

$$resíduo \; deletado = resíduo \; studentizado_{i}\sqrt{\frac{n - n_{param} - 1}{n - n_{param} - resíduo \; studentizado_{i}^{2}}}$$

onde:
* $resíduo \; studentizado_{i}$ é o resíduo studentizado da i-ésima observação;
* $n$ é o número total de observações;
* $n_{param}$ é o número de parâmetros do modelo;

## Código

```
# Resíduos studentizados deletados ($resíduos \; deletados$)

$$resíduo \; deletado = resíduo \; studentizado_{i}\sqrt{\frac{n - n_{param} - 1}{n - n_{param} - resíduo \; studentizado_{i}^{2}}}$$

onde:
* $resíduo \; studentizado_{i}$ é o resíduo studentizado da i-ésima observação;
* $n$ é o número total de observações;
* $n_{param}$ é o número de parâmetros do modelo;
```

# Resíduos studentizados deletados ($t$)

$$t_{i} = \frac{y_{i} - \widehat{y_{i}}}{\sqrt{\frac{ \left( \left(n - n_{param} \right) MSQE - \frac{y_{i} - \widehat{y_{i}}}{1 - h_{ii}} \right)  \left(1 - h_{ii} \right)    }     {n - n_{param} - 1}      }}$$

onde:
* $y_{i}$ é a i-ésima observação;
* $\widehat{y_{i}}$ é o valor predito pelo modelo para a i-ésima observação;
* $MSQE$ é a média dos quadrados dos erros;
* $h_{ii}$ é a alavancagem da i-ésima observação;
* $n$ é o número total de observações;
* $n_{param}$ é o número de parâmetros do modelo;

## Código

```
# Resíduos studentizados deletados ($t$)

$$t_{i} = \frac{y_{i} - \widehat{y_{i}}}{\sqrt{\frac{ \left( \left(n - n_{param} \right) MSQE - \frac{y_{i} - \widehat{y_{i}}}{1 - h_{ii}} \right)  \left(1 - h_{ii} \right)    }     {n - n_{param} - 1}      }}$$

onde:
* $y_{i}$ é a i-ésima observação;
* $\widehat{y_{i}}$ é o valor predito pelo modelo para a i-ésima observação;
* $MSQE$ é a média dos quadrados dos erros;
* $h_{ii}$ é a alavancagem da i-ésima observação;
* $n$ é o número total de observações;
* $n_{param}$ é o número de parâmetros do modelo;
```