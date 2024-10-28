<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


[Homepage](index.md)


# Inserarea ecuatiilor si formulelor 'MathJax'

**Sintaxa:**

Formulele 'MathJax' sunt inserate in aceeasi linie daca sunt plasate intr-O pereche de simboluri `$`

*Exemplu:* Aceasta este o ecuatie: $a=bc$

Formulele `latex` (prin MathJax) se introduc pe rand nou intre doua perechi de simboluri `$$`

*Exemplu:* 
$$a=b^c$$

# Ridicarea la putere (subscript)

Se foloseste meta-caracterul `latex` :`_`

*Exemplu:*
$$a_i = b^c$$

# Gruparea elementelor din formule 

elementele din formule se grupeaza prin meta-caracterele `{` si `{`


$$ 10^{10} $$

# Litere grecesti

*Exemple:*

`\alpha` - alpha litera mica ($$\alpha$$)

`\Alpha` - Alpha litera mare ($$\Alpha$$)

# Parantezele 

- Parantezele rotunde se scriu direct (nu au un inteles special `latex` )
- Parantezele drepte se scriu direct (nu au un inteles special `latex`)
- Acoladele, deoarece ele sunt meta-caractere de grupare, vor fi renderizate corect daca sunt `escapate` de intelesul lor special, punand in fata lor `metacaracterul` `\`

  *Exemple:*

  $$ a = (a+b)^(3x)-[3+6x] $$

# Fractiile 

`\frac{numaratotr}{numitor}`

$$ a = \frac{(a+b)}{d-c} $$

# Semnele de multiplicare si respectiv diviziune 

*Exemple:*

$$ a = c + 10 \times x $$

$$ a = c + 10 \cdot x $$

$$ a = b \div c $$



