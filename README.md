# Cheatsheet
Aplicando a mesma lógica em diversas linguagens.

## Sumário

- [Declaração de funções](#declaração-de-funções)
- [Expressões Condicionais](#expressões-condicionais)
- [Estruturas de Repetição](#estruturas-de-repetição)

### Declaração de funções

##### JavaScript

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

### Estruturas de repetição

#### for

```php

for ($i = 1; $i <= 10; $i++) {
    echo "Faça enquanto $i for menor ou igual a 10";
}

// Ou 

for ($i = 1; $i <= 10; $i++):
    echo "Faça enquanto $i for menor ou igual a 10 com sintaxe alternativa";
endfor;

// Ou

for ($i = 1; ; $i++) {
    if ($i > 10) {
        break;
    }
    echo "Faça até $i for maior que 10 e o comando break para o for";
}

// Ou

for ($i = 1, $j = 0; $i <= 10; $j += $i, print "Mostrar $i = ".$i." passando como parâmetro da função for", $i++);
```

#### while

## To Do

## Licença
MIT &copy; Open School Brasil
