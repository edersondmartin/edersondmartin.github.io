# Capacidade do processo

Seja o índice de capacidade do processo:

$$
C_p = \frac{LSE-LIE}{6\times\sigma} \tag{1}
$$

em que,

$LIE$: limite inferior da especificação<br>
$LSE$: limite superior da especifiação<br>
$\sigma$: desvio padrão natural do processo<br>

Isolando $\sigma$ em (1) temos: 

$$
\sigma = \frac{LSE-LIE}{6\times C_p} \tag{2}
$$





```python
!pwd
```

    /home/ederson/Dropbox/estabilidade_files/python_codes/pacote_v01



```python
!ipython nbconvert fator.ipynb --to markdown
```

    [TerminalIPythonApp] WARNING | Unrecognized alias: 'to', it will have no effect.
    [TerminalIPythonApp] WARNING | File 'nbconvert' doesn't exist
    [22;0t]0;IPython: python_codes/pacote_v01
