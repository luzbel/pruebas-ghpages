---
title: "A ver si me ayudan los del hacklabalmeria"
---

Después de cambiar el _config.yml ...

Este bloque de código XML fuera de una lista se ve bien

``` xml
<tag1>
 <tag2>
  mockvalue
 </tag2>
</tag1>
```
1. first
2. second
  * 2.1
  * 2.2
  * 2.3
3. third. Funciona si no hay sublista

   ``` xml
   <tag1>
    <tag2>
     mockvalue
    </tag2>
   </tag1>
   ```
   
4. fourth

Y ahora, más díficil todavía, con el código en sublistas

1. first
2. second
  * 2.1
  * 2.2
  
    ``` xml
    <tag1>
     <tag2>
      mockvalue
     </tag2>
    </tag1>
    ```
       
  * 2.3
3. third

= Sin código xml

1. first
2. second
  * 2.1
  * 2.2
  * 2.3
3. third. Funciona si no hay sublista

   ``` bash
   echo Hola mundo 
   ls > /tmp/listadofichero
   ```
   
4. fourth

Y ahora, más díficil todavía, con el código en sublistas

1. first
2. second
  * 2.1
  * 2.2

    ``` bash
    echo Hola mundo 
    ls > /tmp/listadofichero
    ```
    
  * 2.3
3. third

Otra prueba, por probar por probar

1. first
2. second
  * 2.1
  * 2.2

``` bash
echo Hola mundo 
ls > /tmp/listadofichero
```
    
  * 2.3
3. third


