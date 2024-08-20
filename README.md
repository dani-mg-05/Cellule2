<p align="center">
   <h1 align="center">Cellule2</h1>
</p>

<p align="center">
  Este proyecto pretende introducirnos a la criptografía
</p>
<p align="center">
  Tendremos que descifrar algunos textos con diferentes herramientas
</p>

---

## Procedimiento
### ex00
<p align="justify">
  En primer lugar, nos dan el siguiente texto codificado.
</p>

```
NDJCQ057YjQ1M182NF8xNV9jMDBsfQ==
```

<br>

<p align="justify">
  Para descifrar el texto, debemos utilizar CyberChef, por lo que entramos en la siguiente página web.
</p>

```
https://gchq.github.io/CyberChef/
```

<br>

<p align="justify">
  Debido a que la longitud de la cadena es múltiplo de 4 y termina en <b>==</b>, podemos deducir que se trata de un texto en base 64. Por eso mismo, en CyberChef ponemos <b>From Base64</b>. Al pasar la cadena, veremos lo siguiente.
</p>

![image](https://github.com/user-attachments/assets/682ca30c-c129-4ffc-91e8-81313202cdac)

<br>

<p align="justify">
  En la parte inferior derecha, encontramos la solución.
</p>

```
42BCN{b453_64_15_c00l}
```

<br>

---

### ex01
<p align="justify">
  Ahora, nos piden descifrar el siguiente texto.
</p>

```
4e 44 4a 43 51 30 35 37 59 6a 51 31 4d 31 38 32 4e 46 38 78 4e 56 39 6a 4d 44 42 73 58 32 4a 31 4e 31 39
6f 4d 33 68 66 4d 54 56 66 59 7a 41 77 62 44 4e 79 66 51 3d 3d
```

<br>

<p align="justify">
  En este caso, se trata de un texto en hexadecimal. Esto es fácil de saber ya que hay un espacio cada dos caracteres (representación común de hexadecimal) y se utilizan los dígitos del <b>0</b> al <b>9</b> y las letras entre la <b>a</b> y la <b>f</b>. Por eso mismo, en CyberChef ponemos <b>From Hex</b>. Al pasar la cadena, veremos lo siguiente.
</p>

![image](https://github.com/user-attachments/assets/85f8f7c5-e99e-427b-bed4-328eb6c08cd7)

<br>

<p align="justify">
  En la parte inferior derecha, encontramos un texto en hexadecimal. Esto quiere decir que, en este caso, debemos hacer más de una decodificación. Por eso, indicamos en CyberChef también <b>From Base64</b>. Nos encontramos lo siguiente.
</p>

![image](https://github.com/user-attachments/assets/ae2f6e18-4acf-4850-b52d-280563115206)

<br>

<p align="justify">
  En la parte inferior derecha, encontramos la solución.
</p>

```
42BCN{b453_64_15_c00l_bu7_h3x_15_c00l3r}
```

<br>

---

### ex02
<p align="justify">
  En este ejercicio, nos proporcionan el siguiente hash.
</p>

```
629cf0d815ccb448a2c7a4d3d9cc3989
```

<br>

<p align="justify">
  Para descifrar el texto, nos dicen que podemos utilizar Hashcat. Sin embargo, hay herramientas más sencillas como <a href="https://crackstation.net/">CrackStation</a>. Si ponemos el hash, obtenemos lo siguiente.
</p>

![image](https://github.com/user-attachments/assets/0d8f62b4-6a32-48d9-a5ce-a4dc870e5ac2)

<br>

<p align="justify">
  En la parte inferior derecha, encontramos la solución.
</p>

```
42BCN{palito}
```

<br>

---

### ex03
<p align="justify">
  Por último, nos dan el siguiente hash.
</p>

```
c967d488512ab5559b446f97843de1be0d615088
```

<br>

<p align="justify">
  Para descifrar el texto, nos dicen que podemos utilizar John the ripper. Sin embargo, hay herramientas más sencillas como <a href="https://hashes.com/">hashes.com</a>.
</p>

![image](https://github.com/user-attachments/assets/cc814a40-7c0b-45d7-8475-7b629a0a2306)

<br>

<p align="justify">
  Si lo enviamos, obtenemos lo siguiente.
</p>

![image](https://github.com/user-attachments/assets/bfbbb6b7-c86d-42f8-993c-1ae85217b406)

<br>

<p align="justify">
  A la derecha del hash, encontramos la solución.
</p>

```
42BCN{liamup2u}
```
