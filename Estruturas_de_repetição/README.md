### Estruturas de repetição

#### For

##### PHP
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
