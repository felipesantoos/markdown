# Markdown
> Minha documentação pessoal da sintaxe Markdown.
- O Markdown funciona como um conversor de texto para HTML.
- Os caracteres **não-alfabéticos** são traduzidos para as mais diversas tags HTML.
- Os **textos sem formatação** são convertidos em parágrafos simples ```<p>```.

# Titulação
```
# Título <h1>
## Título <h2>
### Título <h3>
#### Título <h4>
##### Título <h5>
###### Título <h6>
```
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
# Ênfase
```
Negrito: **texto** ou __texto__
Itálico: *texto* ou _texto_
```
- **Negrito com \*\***
- __Negrito com \_\___
- *Itálico com \**
- _Itálico com \__
# Links
```
Texto-âncora: [Exemplo](https://exemplo.com)
Link direto: <https://exemplo.com>
```
- [Ir para o Google](https://google.com)
- <https://google.com>
# Listas
```
Não ordenadas: * ou - na frente.
Ordenadas: 1., 2., 3., etc. na frente.
```
#### Lista não ordenada com *
* Item A
* Item B
* Item C
#### Lista não ordenada com -
- Item D
- Item E
- Item F
#### Lista ordenada
1. Item G
2. Item H
3. Item I
# Imagens
```
![Texto alternativo ou título da imagem](URL da imagem)
```
![Markdown icon](https://static.thenounproject.com/png/3388541-200.png)
# Citações
> Bloco de citação.
# Código
```
Código em linha: `<code>`
Código de múltiplas linhas: ```<code>...</code>``` ou ~~~<code>...</code>~~~
```
`<code>`
```html
<!-- HTML -->
<code>
...
</code>
```
~~~javascript
// JavaScript
var i = 0;
alert("Hello, World!");
~~~
```php
// PHP
$i = 0;
echo "Hello, World!";
```
~~~json
"json": true,
"name": "Felipe",
"age": 19
~~~
# Tabelas
```
Alinhado à esquerda|Centralizado|Alinhado à direita
:------------------|:----------:|-----------------:
Valor              |   Valor    |             Valor
```
Alinhado à esquerda|Centralizado|Alinhado à direita
:------------------|:----------:|-----------------:
Valor              |   Valor    |             Valor
# Linha horizontal
```
---
```
---
# Nota de rodapé
```
Esta frase tem um nota de rodapé. [^1]
[^1]: Esta é a nota de rodapé.
```
Esta frase tem uma nota de rodapé. [^1]
[^1]: Esta é a nota de rodapé.
# Heading with ID
```
### Título com ID {#titulo-com-id}
```
# Lista de definições
```
Termo 1 
: Definição 1

Termo 2 
: Definição 1
: Definição 2
```
# Texto riscado
```
Esse é um ~~texto riscado~~.
```
Esse é um ~~texto riscado~~.
# Lista de tarefas
```
- [x] Tarefa 1
- [ ] Tarefa 2
```
- [x] Tarefa 1
- [ ] Tarefa 2
