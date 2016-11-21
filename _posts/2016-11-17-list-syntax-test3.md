---
title: "test 3 Syntax highlight inside lists"
categories:
  - misc
tags:
  - Jekyll
  - gh-pages
excerpt: "Probando bloques código en listas"
---

``` xml
<trufo>
 kk3
</trufo>
```

    <div class="language-bash highlighter-rouge"><pre class="highlight"><code><span class="nv">JEKYLL_ENV</span><span class="o">=</span>production bundle <span class="nb">exec </span>jekyll serve --port <span class="nv">$PORT</span> --host <span class="nv">$IP</span> --config _config.yml,_cloud9_config.yml
<span class="nv">JEKYLL_ENV</span><span class="o">=</span>production bundle <span class="nb">exec </span>jekyll serve --port <span class="nv">$PORT</span> --host <span class="nv">$IP</span> --config _config.yml,_cloud9_config.yml
</code></pre>
    </div>
    
<div class="language-bash highlighter-rouge"><pre class="highlight"><code><span class="nv">JEKYLL_ENV</span><span class="o">=</span>production bundle <span class="nb">exec </span>jekyll serve --port <span class="nv">$PORT</span> --host <span class="nv">$IP</span> --config _config.yml,_cloud9_config.yml
<span class="nv">JEKYLL_ENV</span><span class="o">=</span>production bundle <span class="nb">exec </span>jekyll serve --port <span class="nv">$PORT</span> --host <span class="nv">$IP</span> --config _config.yml,_cloud9_config.yml
</code></pre>
    </div>

# Otro

A pruebas
1. 1
``` bash
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
```
2. 2
 * 2.1
 * 2.2
    <div class="language-bash highlighter-rouge">
     <pre class="highlight">
      <code>
<span class="nv">&lt;trufo&gt;
kkita
&lt;/trufo&gt;</span>
</code></pre>
    </div>
 * 2.3
3. 3

B
1. 1
``` bash
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
```
2. 2 Se respeta el orden de la sublista, pero se ve mal el código
 * 2.1
 * 2.2
 ``` bash
 JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
 JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
 ```
 * 2.3
       <jurl>ll</jurl>
3. 3

C
1. 1
``` bash
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
```
2. 2 Se respeta el orden de la sublista, pero se ve mal el código
 * 2.1
 * 2.2
  ``` bash
  JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
  JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
  ```
 * 2.3
    <jurl>ll</jurl>
3. 3

D funciona, pero hay que entrecomillar el html o xml y tenerlo en una única línea ... mientras pruebo otras cosas
1. 1
``` bash
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
   \<tralari\>prueba\</tralari\>
```
2. 2
 * 2.1
 * 2.2
~~~ xml
   <tralari>prueba</tralari>
~~~
 * 2.3
3. 3

E
1. 1
``` bash
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
```
2. 2 Se respeta el orden de la sublista, pero se ve mal el código
 * 2.1
 * 2.2
    ``` bash
    JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
    JEKYLL_ENV=production bundle exec jekyll serve --port $PORT --host $IP --config _config.yml,_cloud9_config.yml
    ```
 * 2.3
3. 3

1. a
2. b  
  * 2.1
  * 2.2
```
<tralari>prueba1</tralari>
```
  * 2.3
  
1. a
2. b  
  * 2.1
  * 2.2
 ```
 <tralari>prueba2</tralari>
 ```
  * 2.3

1. a
2. b  
  * 2.1
  * 2.2
  ```
  <tralari>prueba3</tralari>
  ```
  * 2.3

1. a
2. b  
  * 2.1
  * 2.2
   ```
   <tralari>prueba4</tralari>
   ```
  * 2.3


1. a
2. b  
  * 2.1
  * 2.2
    ```
    <tralari>prueba5</tralari>
    ```
  * 2.3

1. a
2. b  
  * 2.1
  * 2.2
    ```
    <tralari>prueba5</tralari>
    ```
  * 2.3
  
1. a
2. b  
  * 2.1
  * 2.2
     ```
     <tralari>prueba6</tralari>
     ```
  * 2.3

1. a
2. b  
  * 2.1
  * 2.2
      ```
      <tralari>prueba7</tralari>
      ```
  * 2.3

1. a
2. b  
  * 2.1
  * 2.2
       ```
       <tralari>prueba8</t9ralari>
       ```
  * 2.3

1. a
2. b  
  * 2.1
  * 2.2
       ```
       <tralari>prueba8</t9ralari>
       ```
1234567
  * 2.3

1. a
2. b  
  * 2.1
  * 2.2
       ```
       <tralari>
        prueba8
       </tralari>
       <kk>
         <jk>
         dfdf
         </jk>
       </kk>
       ```
  * 2.3

1
1. a
2. b  
  * 2.1
  * 2.2
        ```
        <tralari>prueba9</tralari>
        ```
  * 2.3
  
1. a
2. b  
  * 2.1
  * 2.2
         ```
         <tralari>prueba10</tralari>
         ```
  * 2.3
 
