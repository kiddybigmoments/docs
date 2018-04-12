**REUNIÓN DEL 7 DE ABRIL**

Asistentes: joserramon, fede y pablovarela.

El modelo de datos será algo parecido a este objeto JSON:
```
{
        photos: [
                {
                        id: 'asdfghjklñ',
                        title: 'asd',
                        description: '',
                        createdAt: '',
                        children: [...]
                }
        ],
        users: [
                {
                        id: 1,
                        username: 'asdfg',
                        password: 'asdfg',
                        email: 'asd@asd',
                        firstName: 'Asd',
                        lastName: 'Dsa',
                        createdAt: '',
                        children: [...]
                }
        ],
        children: [
                {
                        id: 1,
                        createdAt: '',
                        firstName: 'Asd',
                        lastName: 'Dsa'
                }
        ],
        albums: [
                {
                        id: 1,
                        name: '',
                        createdAt: '',
                        description: '',
                        photos: [...],
                        users: [...]
                }
        ]
}
```

- El primer prototipo de la aplicación solo permitirá ver, crear y borrar fotos. No se podrá modificar la foto ni su descripción. Se guardará la foto en binario para poder descargarla al ordenador del usuario.

- Para el formulario de registro se usará Angular.

- Todos haremos de todo. No habrá gente que sólo toque el fontal o gente que sólo toque el API.

- Para usar un mismo estilo de código, en el frontal se usará el paquete **standardjs**, como se puede ver en el fichero *package.json* de la carpeta *client*. En el servidor, se usará el estilo de **Pycharm**.

- Es conveniente que nos reunamos una vez a la semana.

- En la página **Fecha de las entregas** del wiki de nuestro gitlab aparecen los días que tenemos que presentar el producto al cliente. Es conveniente que tengamos en cuenta estas fechas. **La primera presentación es el lunes 9 de abril**.

- La asignación de tareas se ha modificado ligeramente, como se puede ver en nuestro tablero de Trello.

- No se habló de la política de ramas en git. Habrá que tratarlo en la próxima reunión.



**PRESENTACIÓN DEL 9 DE ARIL**

Asistentes: veronica, joserramon y pablovarela.

Alberto, el profesor, indicó que íbamos un poco retrasados. Nos dio estas recomendaciones:

- Cada uno debería hacer una historia de usuario entera (back, front, etc) -> Elimina las dependencias.

- Priorizar historias de usuario en google drive (MVP)

- Romper tarea como la de API Rest en varias tareas más concretas.

- Preparar servidor de preproducción.
