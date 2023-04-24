# r de Pearson ( $r_{pearson}$ )

$$r_{pearson} = \frac{\sum_{i=1}^n \left(x_i - \overline{x}\right) \left(y_i - \overline{y}\right)}{\sqrt{\sum_{i=1}^n \left( x_i - \overline{x}\right)^2 \sum_{i=1}^n \left( y_i - \overline{y}\right)^2}}$$

onde
- $x_i$ é a i-ésima observação da variável independente;
- $\overline{x}$ é a média da variável independente;
- $y_i$ é a i-ésima observação da variável dependente;
- $\overline{y}$ é a média da variável dependente;
- $n$ é o número total de observações;


## Código

```
# r de Pearson ( $r_{pearson}$ )

$$r_{pearson} = \frac{\sum_{i=1}^n \left(x_i - \overline{x}\right) \left(y_i - \overline{y}\right)}{\sqrt{\sum_{i=1}^n \left( x_i - \overline{x}\right)^2 \sum_{i=1}^n \left( y_i - \overline{y}\right)^2}}$$

onde
- $x_i$ é a i-ésima observação da variável independente;
- $\overline{x}$ é a média da variável independente;
- $y_i$ é a i-ésima observação da variável dependente;
- $\overline{y}$ é a média da variável dependente;
- $n$ é o número total de observações;
```


# r de Pearson na escala transformada ( $\mu_{Z}$ )

$$\mu_{Z} = \textrm{arctanh} \left({r_{pearson}}\right) = \frac{1}{2} \ln{\left( \frac{1 + r_{pearson}}{1 - r_{pearson}} \right)}$$



## Código

```
# r de Pearson na escala transformada ( $\mu_{Z}$ )

$$\mu_{Z} = \textrm{arctanh} \left({r_{pearson}}\right) = \frac{1}{2} \ln{\left( \frac{1 + r_{pearson}}{1 - r_{pearson}} \right)}$$
```


# Desvio padrão na escala transformada ($\sigma_{Z}$)

$$\sigma_{Z} = \sqrt{\frac{1}{n-3}}$$

onde:
- $n$ é o número total de observações;

## Código

```
$$\sigma_{Z} = \sqrt{\frac{1}{n-3}}$$

onde:
- $n$ é o número total de observações;
```


# Intervalo de confiança

## Inferior ($LI_{pearson}$)

$$LI_{pearson} = \tanh{\left(\textrm{arctanh} \left({r_{pearson}}\right) - \frac{Z_{1-\alpha /2}}{\sqrt{n-3}}\right)}$$

## Superior ($LS_{pearson}$)

$$LS_{pearson} = \tanh{\left(\textrm{arctanh} \left({r_{pearson}}\right) + \frac{Z_{1-\alpha /2}}{\sqrt{n-3}}\right)}$$

onde:
- $n$ é o número total de observações;
- $Z_{1-\alpha /2}$ é o valor crítico da distribuição Normal;

## Código

```
# Intervalo de confiança

## Inferior ($LI_{pearson}$)

$$LI_{pearson} = \tanh{\left(\textrm{arctanh} \left({r_{pearson}}\right) - \frac{Z_{1-\alpha /2}}{\sqrt{n-3}}\right)}$$

## Superior ($LS_{pearson}$)

$$LS_{pearson} = \tanh{\left(\textrm{arctanh} \left({r_{pearson}}\right) + \frac{Z_{1-\alpha /2}}{\sqrt{n-3}}\right)}$$

onde:
- $n$ é o número total de observações;
- $Z_{1-\alpha /2}$ é o valor crítico da distribuição Normal;
```