# Desarrollo y Despliegue en entornos colaborativos

## Tarea 01

** Crea un repositorio local y un repositorio en GitHub

_ Comandos utilizados:

> mkdir Tarea01
> cd Tarea01
> git init
> git remote add origin https://github.com/pplangaritagr/Tarea01DyD

** Estructura básica del proyecto

_ Comandos utilizados:

> nano index.html
> touch .gitignore


** Primer commit y push

_ Comandos utilizados:

> git add .
> git commit -m "Inicio del proyecto: estructura básica"
> git push -u origin main 


** Desarrollo de mejoras: 

Añadir tabla:

><table>
        <tr>
            <th>Lunes</th>
            <th>Martes</th>
            <th>Miércoles</th>
            <th>Jueves</th>
            <th>Viernes</th>
        </tr>
        <tr>
            <td>Yoga</td>
            <td>Pilates</td>
            <td>Zumba</td>
            <td>Body Pump</td>
            <td>Spinning</td>
        </tr>
        <tr>
            <td>Zumba</td>
            <td>Body Pump</td>
            <td>Yoga</td>
            <td>Spinning</td>
            <td>Pilates</td>
        </tr>
    </table>


Añadir footer:

>     <footer>
        <p>Facebook</p>
        <p>Instagram</p>
        <p>LinkedIn</p>
    </footer>

_ Comandos utilizados:

> git checkout -b feature/tabla
> git checkout -b feature/footer
> nano index.html
> git add index.html
> git commit -m "Añadir tabla"
> git commit -m "Añadir footer"
> git push origin feature/tabla
> git push origin feature/footer
