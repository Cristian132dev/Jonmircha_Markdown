# **Aprendiendo Markdown 2: Documentation Edition**

- este readme ira basado en la documentacion oficial para reconocer las buenas practicas del lenguaje de marcado

- por ejemplo, las negritas y cursivas se deben hacer con asterisco `*` porque aun no se a estandarisado el metodo y puede haber incompatibilidad

se pueden crear citas anidadas, no se para que funcionan pero se puede XD

> la vida es chistosa
>
> > Proverbio Indio

los blockquotes se pueden convinar con otros marcadores y quedan muy bien

> ## ¡Esta Documentacion esta quedando muy bien
>
> 1. Aprender Markdown es sencillo
> 2. Solo me costo tiempo :sob:
>
> _todo_ va de acuerdo **al plan**

- algo nuevo :open_mouth: si una lista desordenada arranca con un numero y agragamos un punto, se bugea o algo pasa, para evitar el error solo debemos poner un punto `.`

- 1945. Inicio de la Segunda Guerra Mundial

- 1945\. Inicio de la Segunda Guerra Mundial

Se puede anidar una lista desordenada a una lista ordenada o viceversa

1. Primer item
2. Segundo item
   - Segundo item
   - Segundo item

3. Tercer item

Para agregar reglas horizontales se puede con tres o mas asteriscos `***`, guiones `---` o guiones bajos `___` en una sola linea

naturalmente se usa esta linea para cambiar de tema

---

## Enlaces

para agragar un `title` a un enlace es asi:

`El mejor programador es [Cristian132dev](https://www.linkedin.com/in/cristian132dev/ "indiscutiblemente el mejor")`

y nos quedara asi:

> El mejor programador es [Cristian132dev](https://www.linkedin.com/in/cristian132dev/ "indiscutiblemente el mejor")

de igual manera se puede hacer con las imagenes, recordemos que si ponemos informacion entre llaves cuadradas es el `alt` y dentro los parentesis ira la ruta y le `title`

![Foto del Sujeto :sunglasses:](IMG_20220718_140517.jpg "Admiralo, es gratis!!!")

---

Nuestras direcciones web y de correo se pueden agregar directamente por medio de `<>`

<https://www.linkedin.com/in/Cristian132dev>

<cristian132dev@gmail.com>

Se pueden hacer enlaces con referencias por ejemplo, este codigo lo aprendi de 3 sitios

```markdown
-  Basic Syntax | Markdown Guide [1]
-  Curso Markdown - jonmircha [2]
-  Curso de Markdown [3]

[1]: https://www.markdownguide.org/basic-syntax/
[2]: https://www.youtube.com/watch?v=FlsoBiteuPM&t=1s
[3]: https://www.youtube.com/playlist?list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ
```

Y el resultado se ve asi

> - Basic Syntax | Markdown Guide [1]
> - Curso Markdown - jonmircha [2]
> - Curso de Markdown [3]

[1]: https://www.markdownguide.org/basic-syntax/
[2]: https://www.youtube.com/watch?v=FlsoBiteuPM&t=1s
[3]: https://www.youtube.com/playlist?list=PLM4HZoZrNapsQ_f6a9275n15riyr-2AnQ

Cabe aclarar que los titulos de la refeerncia se pueden llamar como nosotros queramos

---

## Imagenes y Badges

Este gift se pone igual que una fotografia.

![Nyan Cat](https://s3-eu-west-3.amazonaws.com/web-magazines/entornos/deployment/visavis/wp-content/uploads/2021/02/22165306/ddba22b-2fad9d00-1d3f-4ec8-a65d-199a09dfa4e1.gif "El mejor virus del mundo")

pero eso no es nada comparado con los **_badges_**, que son ensignias que le podemos poner a nuestra documentacion y le dara informacion rapida a nuestros usuarios, hay dos tipos:

**1.** **Estaticos**

![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)   ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

![Maintend?](https://img.shields.io/badge/Maintained%3F-yes-green.svg) ![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)

al ser estaticos no se actualizan en vivo

**2.** **Dinammicos**

Los badges dinamicos nos permite que algunos se puedan conectar a una api que les refresca informacion para poder mostrarla en el badge

![Twitter Follow](https://img.shields.io/twitter/follow/Cristian132pro?style=social)

Y para hacer que el badge nos lleve a algun lado es con la siguiente extructura

```markdown
[![Nombre](enlace de la imagen del badge)](link donde nos dirigira el badge)
```

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/573115076487 "enlace")

cada vez mas profesionales, claro que si :sunglasses:

[![Video](https://cutt.ly/1Xt40ad)]