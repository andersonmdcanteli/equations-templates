# Teste t de Student unilateral à direita para comparar uma amostra (distribuição Normal e variância desconhecida) com um valor esperado/conhecido 

## Estatística do teste ( $t_{0}$ )

$$t_{0} = \frac{\left(\overline{x} - \mu_{0}\right)\sqrt{n}}{s_{x}}$$

onde:
- $\overline{x}$ é a média amostral;
- $\mu_{0}$ é o valor esperado para a amostra;
- $n$ é o tamanho da amostra;
- $s_{x}$ é o desvio padrão amostral;

### Código

```
## Estatística do teste ( $t_{0}$ )

$$t_{0} = \frac{\left(\overline{x} - \mu_{0}\right)\sqrt{n}}{s_{x}}$$

onde:
- $\overline{x}$ é a média amostral;
- $\mu_{0}$ é o valor esperado para a amostra;
- $n$ é o tamanho da amostra;
- $s_{x}$ é o desvio padrão amostral;
```

## Hipóteses

$$\begin{cases}H_{0}: & \mu = \mu_{0}\\H_{1}: & \mu > \mu_{0}\end{cases}$$

onde:
- $H_{0}$ é a hipótese nula;
- $H_{1}$ é a hipótese alternativa;
- $\mu$ é a média amostral;
- $\mu_{0}$ é o valor esperado para a amostra;


### Código

```
## Hipóteses

$$\begin{cases}H_{0}: & \mu = \mu_{0}\\H_{1}: & \mu > \mu_{0}\end{cases}$$

onde:
- $H_{0}$ é a hipótese nula;
- $H_{1}$ é a hipótese alternativa;
- $\mu$ é a média amostral;
- $\mu_{0}$ é o valor esperado para a amostra;
```

## Valor crítico ( $t_{critico}$ )

$$t_{critico}=t_{1-\alpha;n-1}$$

onde:
- $\alpha$ é o nível de significância do teste;
- $n$ é o tamanho da amostra;

### Código

```
## Valor crítico ( $t_{critico}$ )

$$t_{critico}=t_{1-\alpha;n-1}$$

onde:
- $\alpha$ é o nível de significância do teste;
- $n$ é o tamanho da amostra;
```

## Probabilidade ( $p-valor$ )

$$p-valor=P(T_{n-1}>|t_{0}|)$$

onde:
- $T_{n-1}$ é a distribuição t de Student com $n-1$ graus de liberdade;
- $t_{0}$ é a estatística do teste;
- $P$ é a função de probabilidade da distribuição t de Student;

### Código

```
## Probabilidade ( $p-valor$ )

$$p-valor=P(T_{n-1}>|t_{0}|)$$

onde:
- $T_{n-1}$ é a distribuição t de Student com $n-1$ graus de liberdade;
- $t_{0}$ é a estatística do teste;
- $P$ é a função de probabilidade da distribuição t de Student;
```


## Conclusão do teste

### Comparando o valor crítico ($t_{critico}$) com a estatística do teste ($t_{0}$)

- Se $|t_{0}| > t_{critico}$, rejeitamos a hipótese nula ($\mu > \mu_{0}$);
- Se $|t_{0}| \leq t_{critico}$, falhamos em rejeitar a hipótese nula ($\mu = \mu_{0}$)

#### Código

```
### Comparando o valor crítico ($t_{critico}$) com a estatística do teste ($t_{0}$)

- Se $|t_{0}| > t_{critico}$, rejeitamos a hipótese nula ($\mu > \mu_{0}$);
- Se $|t_{0}| \leq t_{critico}$, falhamos em rejeitar a hipótese nula ($\mu = \mu_{0}$)
```

### Comparando a probabilidade ($p-valor$) com o nível de significância adotado ($\alpha$)

- Se $p-valor < \alpha$, rejeitamos a hipótese nula ($\mu > \mu_{0}$);
- Se $p-valor \geq \alpha$, falhamos em rejeitar a hipótese nula ($\mu = \mu_{0}$)

### Código

```
### Comparando a probabilidade ($p-valor$) com o nível de significância adotado ($\alpha$)

- Se $p-valor < \alpha$, rejeitamos a hipótese nula ($\mu > \mu_{0}$);
- Se $p-valor \geq \alpha$, falhamos em rejeitar a hipótese nula ($\mu = \mu_{0}$)
```

## Referência

STUDENT. The Probable Error of a Mean. Biometrika, v. 6, n. 1, p. 1, mar. 1908. DOI: [10.2307/2331554](https://doi.org/10.2307/2331554).