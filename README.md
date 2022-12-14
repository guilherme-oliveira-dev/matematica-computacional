<!--
❗ ➤ References used in this Repository:
🔗 • https://github.com/juletopi/Matematica_Computacional
🔗 • https://github.com/kyechan99/capsule-render
🔗 • https://github.com/DenverCoder1/custom-icon-badges
🔗 • https://profilepicturemaker.com
🔗 • https://devicon.dev
🔗 • https://shields.io
🔗 • https://emoji.gg
🔗 • https://getemoji.com
-->

<div align="left">
<img src="https://img.shields.io/github/license/guilherme-oliveira-dev/matematica-computacional" alt="licence-badge">
</div>

<div align="center">
<img src="https://user-images.githubusercontent.com/116320626/197294433-50ac954d-170e-465e-9e9f-a76b16dc0ccd.png" width="90px" height="90px" alt="kekwcomputer">

# Algoritmos e Lógica de Programação

• Este é um repositório com o conteúdo das aulas de Matemática Computacional, ministradas pelo professor , utilizando o RStudio e a linguagem R como ferramentas de aprendizado.
</div>

###

<div align="center">
<a href="https://www.rstudio.com/about/"><img src="https://img.shields.io/badge/Made%20with%20IDE:-RStudio%20-gray.svg?colorA=7a97b2&amp;colorB=76aada&amp;style=for-the-badge" alt="RStudioIDE-badge" style="max-width: 100%;"></a>
<a href="https://www.r-project.org/"><img src="https://img.shields.io/badge/Made%20with%20language:-R%20-gray.svg?colorA=5986c7&amp;colorB=1F65CC&amp;style=for-the-badge" alt="RLanguage-badge" style="max-width: 100%;"></a>
</div>
&#8196;

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

###

<div align="left">

## 👨‍🏫 Professor:

<img align="left" height="135px" width="135px" alt="gleison-garcia-pic" src="https://user-images.githubusercontent.com/116320626/197294508-b99e57c8-8742-4644-9715-94d2054fa7a1.png">

**Gleison Guardia - Pesquisador da Matemática, Professor de Curso Técnico e Superior & Diretor de Ensino do IFRO Campus Ji-Paraná** \
[**IFRO Campus Ji-Paraná**](https://portal.ifro.edu.br/ji-parana) • <i>Desde Julho de 2013</i> \
Linguagens & Tecnologias: `RStudio` • `R (Linguagem)` • `Google Colab` • `Python`\
Contato: **[gleison.guardia@ifro.edu.br](mailto:gleison.guardia@ifro.edu.br)**

###

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

## 💾 Conceitos Aprendidos:
### 1. Comentários, variáveis, operadores e funções "print( )" e "remove( )"

Nesta aula foram aprendidos: 
- Conceitos básicos para o uso do RStúdio
- Utilização do RStúdio para conceitos matemáticos
- Criação de algoritmos simples de definição de números Pares, Ímpares, Sucessores e Antecessores

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_aula01
```r
?print( ) # <- Executa o argumento de um valor
?remove( ) # <- Remove um valor

#Exemplo: Algoritmo para descobrir número par
#Todo número inteiro que é divisível por 2 é par, logo:
n = 7
par = 2*n
print(par)

remove(n) # <- Removido a variável "n"
remove(par) # <- Removido a variável "par"
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

### 2. Função "abs( )"

Nesta aula foram aprendidos: 
- Operações que trabalham com deslocamento, usando o comando "abs( )"
- Conceitos de divisão de números inteiros
- Conceitos de resto da divisão

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_aula02
```r
?abs( ) # <- Devolve o valor absoluto de um número inteiro.

#Exemplo: |3| e |−3|
abs(3)
abs(-3) # <- A função sempre retornará um número positivo

#Tipos de divisão em R:

5/5 # <- "Divisão Inteira"
5/2 # <- "Divisão Exata"
5/3 # <- "Divisão Infinita"

#Na "Divisão Infinita", quando dividimos 5/3, não obtivemos
#um valor exato e inteiro, quando queremos só a parte
#inteira dessa divisão, fazemos "%/%":
5%/%3
8%/%3  
11%/%3
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

### 3. Raízes multiplas, π(pi) e função "sqrt( )"

Nesta aula foram aprendidos: 
- Operações que trabalham com raízes quadradas, usando o comando "sqrt( )"
- Conceitos de operação de pontências
- Conceitos de operação utilizando o π (pi)

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_aula03
```r
?sqrt( ) # <- Determina uma raiz quadrada de um número.

#Exemplo: A raíz de 9
sqrt(9) # <- A raiz quadrada de 9 é 3, porque 3 x 3 = 9

#Mas quando precisamos encontrar uma raiz que seja maior que
#a quadrada, exemplo, cúbica, quarta e etc, podemos 
#utilizar o seguinte recurso matemático:

2**(1/3) # <- Raíz cúbica de 2
2**(1/4) # <- Raíz quarta de 2
50**(1/5) # <- Raíz quíntopla de 50
1024**(1/10) # <- Raíz décima de 1024

#Operações com o π(pi):
?pi # <- O pi é uma constante que já vem dentro da linguagem R, não sendo necessário a sua declaração

#Exemplo:
2 + 3 * pi
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

### 4. Números complexos e funções "Re( )" e "Im( )"

Nesta aula foram aprendidos: 
- Operações que trabalham com números complexos, usando os comandos "Re( )" e "Im( )"
- Conceitos de operação de Adição, Subtração e Multiplicação com números complexos

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_aula04
```r
?Re( ) # <- Extrai a parte real de um número complexo
?Im( ) # <- Extrai a parte imaginária de um número complexo

#Exemplo: z = 2+3i
z1 = 2 + 3i
Re(z) # <- Retorna "2" como a parte real
Im(z) # <- Retorna "3" como a parte imaginária

?cat( ) # <- Usada para mostrar os valores na tela.

cat("z1=",z1)
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

### 5. Variáveis matemáticas e utilização de "{ }"

Nesta aula foram aprendidos: 
- Operações que trabalham com a utilização de variáveis usando vetores
- Utilização de "{ }" para seleção de operações matemáticas específicas

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_aula05
```r
{ } # <- As chaves são comumente usadas na lógica de programação para delimitar uma instrução

#As equações podem ser feitas utilizando-se de variáveis
#das quais, tem a finalidade de armazenar valor:

{
  x = 2
  y = 2 * x        # <- Toda a equação está sendo declarada dentro das chaves, fazendo com que os
  print(y)                     # valores de equações anteriores não se sobreponham
}
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

### 6. Fórmula de bhaskara e função "If/Else"

Nesta aula foram aprendidos: 
- Operações que trabalham com fórmula de bhaskara, usando o comando "cat( )"
- Utilização da lógica de programação "If e Else" para a criação de algoritmos matemáticos

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_06
```r
#Equações de segundo grau podem ser feitas utilizando o software r.
#Por exemplo: x^2 − 7x + 10 = 0
{
  a = 1
  b = -7
  c = 10
  cat("a = ", a, "\n")
  cat("b = ", b, "\n")
  cat("c = ", c, "\n")
  
  #Agora vamos encontrar o valor de Δ:
  delta = b ** 2 - 4 * a * c
  print(delta)
  
  x_1 = (-b - (delta)**(1/2))/(2*a)
  print(x_1)
  x_2 = (-b + (delta)**(1/2))/(2*a)
  print(x_2)
  cat("x_1 = ", x_1, "x_2 = ", x_2)
  
  #Introduzindo o conceito de "if e else":
  if(delta < 0){
    print("O seu número é Complexo!")
  }else{
    print("O seu número é Real!")
  }
}
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

### 7. Áreas, volumes e função "readline( )"

Nesta aula foram aprendidos: 
- Operações que trabalham com a área e volume de formas geométricas, usando o comando "readline( )"
- Criação de algoritmos com entrada e saída de valores de cálculo fornecidos pelo usuário

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_07
```r
#Ao trabalharmos com áreas e volumes de uma forma, normalmente há aquele que irá definir
#as suas dimensões de acordo com a fórmula. Para isso, utilizamos os comandos:

?readline( ) # <- Retorna uma string para acomodar toda a linha.
?sprintf( ) # <- Formata uma string e guarda o resultado em um array.

#Exemplo: Área do Losango
{
  print("Digite o valor de D → diagonalmaior:")
  D = as.numeric(readline())
  D
  print("Digite o valor de d → diagonalmenor:")
  d = as.numeric(readline())
  d
  A = D * d / 2
  sprintf("A área da figura é %s!", A )
}
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

### 8. Algoritmo Financeiro (Juros e Porcentagem)

Nesta aula foram aprendidos: 
- Entendimento sobre conceitos matemáticos financeiros
- Criação de um algoritmo complexo com conceitos matemáticos financeiros de juros e porcentagem

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_08
```r
#Reajustes Sucessivos (Algoritmo):
{
  valor <- as.numeric(readline("Digite o valor do produto: "))
  parcelas <- as.numeric(readline("Digite a quantidade de parcelas: "))
  reajuste <- 1
  for (i in 1:parcelas) {
    taxa = as.numeric(readline(sprintf("Digite a %sª parcela: ", i)))
    reajuste = reajuste * (1+ taxa/100)
  }
  novo_valor = valor * reajuste
  sprintf("O novo valor do produto é R$%s!", novo_valor)
}

#O algoritmo acima ↑ faz com que sejam pedidos o valor, a quantidade de parcelas
#e o nº da parcela de um produto, resultando no valor final do produto.
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

### 8.2. Algoritmo Financeiro (Juros Simples e Compostos)

Nesta aula foram aprendidos:
- Criação de um algoritmo complexo com conceitos matemáticos financeiros de juros simples e compostos

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_08
```r
#Juros Simples e Compostos (Algoritmo):
{
  c = as.numeric(readline("Digite o valor da capital: ")) 
  i = as.numeric(readline("Digite o valor da taxa de juros: "))
  t = as.numeric(readline("Digite o tempo da aplicação: "))
  sn = as.numeric(readline("Escolha entre os juros, (1)simples ou (2)composto: "))
  if(sn == 1){
    m = c * (1 + (i/100) * t)
    sprintf("Seu montante será de R$%s!", m)
  }else{
    m = c * (1 + (i/100)) ^(t)
    sprintf("Seu montante será de R$%s!", m) 
  }
}

#O algoritmo acima ↑ faz com que sejam pedidos o valor da capital, taxa de juros,
#o tempo da aplicação e a escolha entre os juros simples ou composto.
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=cf1300&height=4&section=header&%20render">
</div>

### 8.3. Algoritmo Financeiro (Parcelas e Dívidas)

Nesta aula foram aprendidos:
- Criação de dois algoritmos complexos com conceitos matemáticos financeiros de valores de parcelas e dívidas

**Demais exemplos presentes no RPubs:** https://rpubs.com/Gleison_Guardia/mc_08
```r
#Valor Atual de uma Parcela (Vap) (Algoritmo 1):
{
  vn = as.numeric(readline("Digite o valor do bem: "))
  i = as.numeric(readline("Digite a taxa de juros: "))
  n = as.numeric(readline("Digite o número de parcelas: "))
  vap = (vn/ (1 + i/100) ^n)
  sprintf("O valor atual total de uma parcela será: R$%s!", vap) 
}

#Valor Atual total de uma dívida (Vat) (Algoritmo 2):
{
  r = as.numeric(readline("Digite o valor do bem: "))
  i = as.numeric(readline("Digite a taxa de juros: "))
  n = as.numeric(readline("Digite o número de parcelas: "))
  
  numerador = (1 + i/100) ^n - 1
  denominador = i/100 * (1 + i/100) ^n
  vat = r * (numerador/denominador)
  sprintf("O valor atual total de uma dívida será: R$%s!", vat) 
}

#Os algoritmos acima ↑ fazem com que sejam pedidos o valor do bem, 
#taxa de juros e o nº da parcela de um produto.
```
