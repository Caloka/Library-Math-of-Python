# **Math Python**
#### **Nesse repositório, será abordado algumas funções do módulo 'math'.**
#### **A biblioteca 'math', é responsável por apresentar diversas ferramentas para calcular funções matemáticas utilizando a linguagem de programação Python.**
#### **À seguir, serão abordados algumas funções para facilitar o entendimento do uso da ferramenta.**
#### **Para calcularmos funções trigonométricas no python, utilizaremos funções do módulo 'math', vejamos abaixo:**

~~~python
import math

# Declarando as variáveis
var = 30 # Vamos considerar essa variável como um ãngulo em graus
var2 = 2 # Vamos considerar essa variável como um número inteiro

# Multiplicação
multi = math.prod([var,var2])

# Utilizando funções de conversão
varRad = math.radians(var) # Grau >>> Radianos
varGra = math.degrees(varRad) # Radianos >>> Grau


# Utilizando funções de trigonometria
seno = math.sin(varRad) # Acha o seno
cos = math.cos(varRad) # Acha o cosseno
tan = math.tan(varRad) # Acha a tangente
arcoseno = math.asin(varRad) # Acha o arcoseno
arcocosseno = math.acos(varRad) # Acha o arcocosseno
arcotangente = math.atan(varRad) # Acha o arcotangente


# Raiz quadrada
raiz = math.sqrt(var) # Acha a raiz quadrada de var


# Potência
potência1 = math.pow(var,var2) # Acha a potência de var(30) elevado à var2(2)
''' Outa forma de calcular potência, é:'''
potência2 = var**var2 # Acha a potência de 30 elevado à 2

# Constantes
pi = math.pi # Declara o pi como variável
neperiano = math.e # Declara o número neperiano como variável
infinito = math.inf # Declara o valor infinito como variável


# Logarítmo
ln =  math.log(var) # Encontra o logarítmo natural(ln) da variável 'var' 
log = math.log10(var) # Encontra o logarítmo da variável 'var' na base 10
log1 = math.log(var,10) # Outra forma de encontrar o logarítmo de 'var' na base 10


# Números complexos
''' 2 formas de declarar números complexos no python, vejamos:'''
num = 3j # Apenas adicionando um 'j' ao lado do valor da variável
num2 = complex(2,1) # usando a classe complex já incluida no próprio python. Aqui ele retornar: 2 + 1j

~~~
