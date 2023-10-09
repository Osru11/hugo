+++
title = 'Introducción'
date = 2023-09-19T10:47:37+02:00
draft = false
weight = 10
+++

Shortcodes y Markdown **2023**

## Introducción

+ A continuación en este sitio aprenderemos a utilizar [markdown](../plantillas/markdown/) básicamente, por ejemplo a poner palabras en **negrita** , a escribir líneas de codigo o a introducir hipervínculos:

```php

echo "hola";

```

[Acceder a google](https://google.com "Google")

+ También aprenderemos a utilizar shortcodes como uno propio para otorgar color o simplemente uno para subrayar lineas de código:

{{<color>}}Color por defecto{{</color>}}  
{{<color  color= "red">}}Texto en rojo{{</color>}}  

{{< highlight lineNos="true" lineNoStart="1" color= red type="php" hl_lines="2 4">}}
# the hardest part is to start writing code; here's a kickstart; just copy and paste this; it's free; the next lines will cost you serious credits
print("Hello")
print(" ")
print("World")
print("!")
{{< /highlight >}}