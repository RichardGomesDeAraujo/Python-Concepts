<img src="Logo.png" align="Center" alt="Hands On Data" style="height: 100px; width:115px;"/>

<p>  <br>
  </p>
  
# Concepts, Application Fields and Libraries

<p>  <br>
  </p>

###### by [Richard Gomes de Araújo](https://github.com/RichardGomesDeAraujo) - 07/11/2023
[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/RichardGomesDeAraujo)](https://github.com/RichardGomesDeAraujo)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/richardaraujoanalistadedados/)](https://www.linkedin.com/in/richardaraujoanalistadedados/)
[![Youtube Badge](https://img.shields.io/badge/-YouTube-ff0000?style=flat-square&labelColor=ff0000&logo=youtube&logoColor=white&link=https://www.youtube.com/channel/UCc_jlqHut_GkXc8ahgQHOOw)](https://www.youtube.com/channel/UCc_jlqHut_GkXc8ahgQHOOw)
<p>  <br>
  </p>
  
# Index
- [**Operadores Numéricos**](README.md#Operadores-Numéricos)
- [**Operadores de Comparação**](README.md#Operadores-de-Comparação)
- [**Operadores Lógicos**](README.md#Operadores-Lógicos)
- [**Tipos de Dados**](README.md#Tipos-de-Dados)
- [**Coleções de Dados**](README.md#Coleções-de-Dados)
- [**Variáveis**](README.md#Variáveis)
- [**Condicionais**](README.md#Condicionais)
- [**Looping**](README.md#Looping)
- [**Looping (while)**](README.md#Looping-(while))
- [**Comandos de Entrada**](README.md#Comandos-de-Entrada)
- [**Comandos de Saída**](README.md#Comandos-de-Saída)
- [**Importação de Arquivos**](README.md#Importação-de-Arquivos)
- [**Funções**](README.md#Funções)
- [**Classes**](README.md#Classes)
- [**Importação de Bibliotecas**](README.md#Importação-de-Bibliotecas)
- [**Tratamento de Erros e Exceções**](README.md#Tratamento-de-Erros-e-Exceções)
- [**Manipulação de Ambientes Virtuais**](README.md#Manipulação-de-Ambientes-Virtuais)

# Application Fields and Libraries:
- [**Análise de Dados e AI (Artificial Intelligence)**](README.md#Análise-de-Dados-e-AI-(Artificial-Intelligence))
- [**Automação WEB/Scraping**](README.md#Automação-WEB/Scraping)
- [**Automação de Tarefas**](README.md#Automação-de-Tarefas)
- [**Desenvolvimento Web**](README.md#Desenvolvimento-Web)
- [**Desenvolvimento APP**](README.md#Desenvolvimento-APP)
- [**Desenvolvimento Games**](README.md#Desenvolvimento-Games)

---

### Operadores Numéricos
Visualization using SQL commands:
```python
+ Adição
- Subtração
* Multiplicação
/ Divisão
```

###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Operadores de Comparação
```python
> Maior
< Menor
>= Maior e Igual
<= Menor e Igual
== Igual
= Recebe Valor
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Operadores Lógicos
```python
4 > 3 and 4 >= 2 
5 < 6 or 4 <= 3 
not 6 < 5 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Tipos de Dados
```python
type(“tipo de dado”) = string 
type(40) = int 
type(2.0) = float 
type(True) = bool 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Coleções de Dados
```python
Listas = [a, b, c] 
Dicionários = {“chicará”, “pires”, “colher”} 
Tuplas = (10, 20, 30) 
Conjuntos = set([10, 20, 30])
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Variáveis
```python
Variável = 100 
Variável = Variável * 100 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Condicionais
```python
if 10 < 5: 
variavel = True 
else: 
variavel = False
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Looping
```python
for i in range(10): 
variavel = variavel + 5 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Looping (while)
```python
while variavel < 10: 
variavel = variavel + 5 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Comandos de Entrada
```python
Valor = int(input(“Digite um número”))
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Comandos de Saída
```python
print(“O número é {:.2f}!”.format(valor)) 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Importação de Arquivos
```python
with open(“C:/documentos/arquivo.txt”, “w”) as arquivo: 
texto = “Cotações” 
arquivo.write(texto) 
arquivo.close() 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Funções
```python
def primeira_funcao(): 
print(“Primeira Função”)
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Classes
```python
def__init__(self, nome, idade): 
self.nome = nome 
self.idade = idade 
def funcao(self): 
print(“Meu nome é”, self.nome) 
print(“Minha idade é”, self.idade)
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Importação de Bibliotecas
```python
from Biblioteca import Função
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Tratamento de Erros e Exceções
```python
for i in range(10): 
try: 
     #comandos 
except:
     print(“Erro de Digitação”) 
     continue 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Manipulação de Ambientes Virtuais
```python
Microsoft Windows [versão 10.0.22000.795] 
© Microsoft Corporation. Todos os direitos reservados.  

C:\Users\Documentos>conda create –n MeuAmbienteVirtual python=3.6 pip
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>
  
---

# Application Fields and Libraries

### Análise de Dados e AI (Artificial Intelligence)
```python
Numpy 
Pandas 
Matplotlib 
Seaborn 
Scikitlearn 
TensorFlow 
Keras 
Pytorch 
Theano 
MxNet 
Caffe 
CNTK 
Pillow
OpenCv 
ApacheSpark 
Hadoop
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Automação WEB/Scraping
```python
Urllib 
Requests 
Selenium 
Webbot 
Beautifulsoup 
Scrapy 
PyAutoGUI 
Keyboard 
Pynput 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Automação de Tarefas
```python
OS 
RPA 
APSScheduler 
Watchdog 
Paramiko 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Desenvolvimento Web
```python
Django 
Flask 
CherryPy 
Pyramid 
TurboGears 
Web2py 
Bottle 
Tornado	 
Falcon 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Desenvolvimento APP
```python
Kivy 
BeeWare 
Python-for-Android 
PyJNlus 
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

### Desenvolvimento Games 
```python
Pygame 
PyKyra 
Pyglet 
Arcade 
PyOpenGl 
Panda3D 
Ren’Py 
Cocos2d
```
###### [⏪](README.md#Index)
<p>  <br>
  </p>

