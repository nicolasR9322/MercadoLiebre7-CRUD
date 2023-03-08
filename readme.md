Trabajo practico integrador de Digital House : "Mercado Liebre"

El objetivo del proyecto es construir un e-commerce en Node Js usando la metodologia mobile first, este repositorio corresponde a la septima iteracion del proyecto

Metodo de uso:

    -Clonar repositorio

    -En terminal (Carpeta raiz) para instalar las dependencias, ejecutar: npm i

    -Luego ejecutar nodemon o ir a la ruta "src/bin" y ejecutar en la terminal : node www

 descripción: parte 1 del CRUD (crear, leer, actualizar y borrar) de los productos:

        desafio 1: incorporar las siguientes rutas
            
            -/
            muestra los productos del home separados en 2 secciones
            
            -/products
            lista todos los productos presentes en la base de datos JSON

            -/products/:id
            detalle de producto, cada producto debe contar con botones de BORRAR y MODIFICAR

            -/products/create
            muestra el formulario para creacion del producto

            -/products/
            recibe datos de creacion del formulario

            -/products/edit/id:
            cuenta con un boton MODIFICAR, actualizara la informacion correspondiente ingresada

            -/products/
            recibe los datos de la actualizacion

            -/products/:id
            cuenta con un boton BORRAR, eliminara el producto de la base de datos JSON