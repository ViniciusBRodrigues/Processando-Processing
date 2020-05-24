
#### Nome
### nfp()

#### Exemplos

```pde
int a=200, b=-40, c=90; 
String sa = nfp(a, 10); 
println(sa); // Imprime "+0000000200" 
String sb = nfp(b, 5); 
println(sb); // Imprime "-00040" 
String sc = nfp(c, 3); 
println(sc); // Imprime "+090" 
 
float d = -200.94, e = 40.2, f = -9.012; 
String sd = nfp(d, 10, 4); 
println(sd);  // Imprime "-0000000200.9400" 
String se = nfp(e, 5, 3); 
println(se);  // Imprime "+00040.200" 
String sf = nfp(f, 3, 5); 
println(sf);  // Imprime "-009.01200" 

```

#### Descrição
Função utilitária para se
formatar números em strings.É similar a**nf() m**
mas coloca um "+"em frente dos números positivos e um "-"em
frente dos números negativos.  Há duas
versões, uma
para formatar floats e outra para formatar ints. Os valores dos
parâmentros**digitos**,**esquerda**, e**direita **devem ser sempre números inteiros positivos.

#### Sintaxe
```pde
nfp(intValor, digitos)
nfp(floatValor, esquerda, direita)

```
Parâmetros
intValor
int ou int[]: o(s) número(s) a formatar
digitos
int: números de dígitos a preencher com zeros
floatValor
float ou float[]:  o(s) número(s) a formatar
esquerda
int: numero de
algarismos à esqueda do ponto decimal (n.t. em inglês se
utiliza ponto ao invés de vírgula)
direita
int: numero de
algarismos à direita do ponto decimal (n.t. em inglês se
utiliza ponto ao invés de vírgula)

#### Retorno

	
String or String[]

#### Utilização

	
Web & Applicações

#### Relacionado
[nfs()](nfs_)[nf()](nf_)[nfc()](nfc_)