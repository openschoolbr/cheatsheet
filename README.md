# Cheatsheet
Aplicando a mesma lógica em diversas linguagens.

## Sumário

- [Declaração de funções](#declaração-de-funções)
- [Expressões Condicionais](#expressões-condicionais)
- [Estruturas de Repetição](#estruturas-de-repetição)

### Declaração de funções

#### JavaScript

```javascript
var foo = function (a) {
  return a
}

// Ou

let foo = (a) => a

// Ou

let foo = (a) => { return a }

// Ou

function foo (a) {
  return a
}
```

##### PHP

```php
$foo = function ($a) { return $a; };

// Ou

function foo($a) {
  return $a;
}
```

##### Java

```java
public int foo(int a) { return a; } // O tipo `int` pode variar para qualquer outro tipo
```

##### Python

```python
def foo(a):
  return a
```

##### C#

```cs
public string foo(int a) => a.ToString();

//ou

public string foo(int a){
  a;
  return a.ToString();
}
```

### Expressões Condicionais

#### If

##### JavaScript

```javascript
if (a === b) {
  return 'É igual!'
}
```

##### PHP

```php
if ($a === $b) {
  return "É igual!";
}
```

##### C#

```cs
if(a == b) {
    return "É igual!";
}
```

#### Else

##### JavaScript

```javascript
else {
  return 'Não é igual!'
}
```

##### PHP

```php
else {
  return "Não é igual!";
}
```

##### C#

```cs
else {
    return "Não é igual!";
}
```

#### Else if

##### JavaScript

```javascript
else if (a > b) {
  return 'É maior!';
}
```

##### PHP

```php
else if ($a > $b) {
  return "É maior!";
}

// Ou

elseif ($a > $b) {
  return "É maior!";
}
```

 ##### C#

```cs
else if (a > b) {
    return "É maior!";
}
```

#### Switch

##### C#

```cs
switch(valor){
    case 1:
        //faz algo se valor igual 1
        break;
    case 2:
        //faz algo se valor igual 2
        break;
    default:
        //faz algo se não for igual a 1 nem a 2
        break;
 }
 ```
### Estruturas de repetição

#### For

##### PHP

```php

for ($i = 1; $i <= 10; $i) {
    echo "Faça enquanto $i for menor ou igual a 10";
}

// Ou

for ($i = 1; $i <= 10; $i):
    echo "Faça enquanto $i for menor ou igual a 10 com sintaxe alternativa";
endfor;

// Ou

for ($i = 1; ; $i) {
    if ($i > 10) {
        break;
    }
    echo "Faça até $i for maior que 10 e o comando break para o for";
}

// Ou

for ($i = 1, $j = 0; $i <= 10; $j = $i, print "Mostrar $i = ".$i." passando como parâmetro da função for", $i);
```

##### Python

```python    
# faça enquanto x for menor que 10
for x in xrange(1, 10):
    print x
```

##### C#

``` cs
for(int i = 0; i < length; i){
    //faz algo enquanto i for menor que length
}

//ou

for(int i = 0; i < length; i)
    //faz algo em uma linha enquanto i for menor que length
```

#### ForEach

##### C#

``` cs
foreach(var item in collection){
    //faz algo para cada item da collection
}

//ou

foreach(var item in collection)
    //faz algo em uma linha para cada item da collection
```

#### While

##### C#

```cs
while(condicao){
    //faz algo enquanto a condicao for verdadeira
}

//ou

while(condicao)
    //faz algo em uma linha enquanto a condicao for verdadeira
```

#### Do-While

 ##### C#

```cs
do
{
    //faz algo e faz outra vez se a condição for verdadeira
} while(condicao);

//ou

do
    //faz algo em uma linha e faz outra vez se a condição for verdadeira
while(condicao);
```

## Licença

MIT &copy; Open School Brasil
