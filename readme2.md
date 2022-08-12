<!--- esta monda esta mamona -->

# Aprendiendo *Markdown*
<!--- los parrafos en markdown no necesitan ningun tipo de declaraciones y no hay problemas con los saltos de linea -->

esto es un parrafo

Elit consequat amet enim elit esse pariatur proident adipisicing aliquip magna. Consequat officia aliquip exercitation cillum officia deserunt sunt sunt laboris dolor. Cillum occaecat do et deserunt ullamco aliqua duis consequat cillum laborum. Eiusmod deserunt mollit minim consectetur consequat velit velit officia ad voluptate.

Commodo veniam elit exercitation velit amet est labore enim. Duis aliqua et incididunt dolore do id minim. Quis Lorem velit laborum in qui.

## Aplicando Cursiva y Negritas

se encierra el texto en guiones bajos para las cursivas y se encierra en asteriscos para las negritas
b
Aplicando *Cursiva* y **Negritas**

***negrita curveada***

<!--- debe haber espacio entre el hash y el texto para que se muestre correctamente -->

# Encabezado 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

<!--- los enlaces se hacen con dos partes, una con llaves cuadradas y la segunda con parantesis -->

links en markdown
[esta es una ruta absoluta](https://youtube.com)

<!--- los enlaces internos solo funcionan con encabezados y al momento de ingresar el enlace se usa hash y el propio editor nos la completa, y los espacios se representan con un guion -->

[aprendiendo *markdown*](#aprendiendo-markdown)

<!--- para mostrar una imagen es igual al de html solo que al inicio se pone un signo de admiracion y lo que valla en lo guines cadrados sera el alt de la imagen -->

![This is JavaScript](IMG_20220718_140517.jpg))

<!--- semanticamete esta division es para cambiar de tema en markdown, como el hr  -->

---

este es un texto

---

y este es otro texto

1. Primavera
2. Verano
3. otoño
4. invierno

---

- Primavera
  - abril
  - mayo
  - junio
- Verano
  - julio
    - Mes Patrio
  - agosto
  - septiembre
- otoño
- invierno

---

- Primavera
  - abril
  - mayo
  - junio
- Verano
- Otoño
- Invierno

---

<!--- cita en una linea  -->

> Siempre tienes opcion de no tener opinion - Marco Aurelio

<!--- cita en bloque -->

> Todo lo que escuchamos es una opinion, no un hecho
>
>> Todo lo que vemos es una perspectiva, no la verdad
>
> Marco Aurelio

<!--- para crear tablas se usa esta estructura  -->

| NOMBRE   | EDAD | CORREO                   |
| -------- | ---- | ------------------------ |
| Cristian | 20   | cristian132dev@gmail.com |
| Juanito  | 19   | juanito22@gmail.com      |

---

<!--- para destacar codigo se usan los acentos graves y si es un bloque se puede especificar el lenguaje escrito  -->

`let` Est id velit proident commodo reprehenderit et ullamco et cupidatat et fugiat ad.

`const sumar = (a, b) => a + b`

```js
function sumar(a, b) {
   return a + b;
}
```

```html
<html>
   <head>
      <title>Aprendiendo Markdown</title>
   </head>
   <body>
      <p class="title">este es un parrafo</p>
   </body>
</html>
```

`**negrita** y _cursiva_`

<!-- para que nuestra hoja de markdown ignore los cambios a nuestros textos se pone una contra barra -->
\*\*negrita** y \_cursiva_
