---
title: If-else Statement
localeTitle: Declaración if-else
---
## Introducción

If / Else es una declaración condicional donde, según la veracidad de una condición, se realizarán acciones diferentes.

> **Nota: los** paréntesis `{}` solo son necesarios si la condición tiene más de una declaración de acción.

## Declaración de IF
```
  if (condition){ 
    statement1; 
    statement2; 
  } 
```

> **Nota:** la sentencia `else` es opcional.
> 

> ## Declaración de If / Else
```
  if (condition){ 
    statement1; 
    statement2; 
  } 
  else{ 
    statement3; 
    statement4; 
  } 
```

## Declaración If / Elseif / Else
```
  if (condition){        // Se ejecuta cuando condition se evalua a true
    statement1; 
    statement2; 
  } 
  elseif (condition2){  // Se ejecuta cuando condition se evalua a false y condition2 se evalua a true
    statement3; 
    statement4; 
  } 
  else                  // Se ejecuta cuando condition y condition2 se evaluan a false
    statement5; 
```


Para más información revisa el siguiente enlace: [PHP más](http://php.net/manual/en/control-structures.elseif.php)
