# Grubbs Three ( $G^{'''}$ )

$$ G^{'''} = \frac{(n-3) \times s_{upper}^{2}}{(n-1) \times s^{2}}$$

- $x_{1}, x_{2}, ..., x_{n}$ são os valores da amostra ordenados de forma crescente;
- $n$ é o número total de observações;
- $s_{upper}^{2}$ é é a variância das observações excluindo as duas observações suspeitas ($x_{n}$ e $x_{n-1}$);
- $s^{2}$ é a variância amostral;


$$ G^{'''} = \frac{(n-3) \times s_{lower}^{2}}{(n-1) \times s^{2}}$$

- $x_{1}, x_{2}, ..., x_{n}$ são os valores da amostra ordenados de forma crescente;
- $n$ é o número total de observações;
- $s_{lower}^{2}$ é é a variância das observações excluindo as duas observações suspeitas ($x_{1}$ e $x_{2}$);
- $s^{2}$ é a variância amostral;


## Código

```
# Grubbs Three ( $G^{'''}$ )

$$ G^{'''} = \frac{(n-3) \times s_{upper}^{2}}{(n-1) \times s^{2}}$$

- $x_{1}, x_{2}, ..., x_{n}$ são os valores da amostra ordenados de forma crescente;
- $n$ é o número total de observações;
- $s_{upper}^{2}$ é é a variância das observações excluindo as duas observações suspeitas ($x_{n}$ e $x_{n-1}$);
- $s^{2}$ é a variância amostral;


$$ G^{'''} = \frac{(n-3) \times s_{lower}^{2}}{(n-1) \times s^{2}}$$

- $x_{1}, x_{2}, ..., x_{n}$ são os valores da amostra ordenados de forma crescente;
- $n$ é o número total de observações;
- $s_{lower}^{2}$ é é a variância das observações excluindo as duas observações suspeitas ($x_{1}$ e $x_{2}$);
- $s^{2}$ é a variância amostral;
```