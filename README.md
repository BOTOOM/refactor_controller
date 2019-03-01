# refactor_controller

Este proyecto es un script desarrollado en python 2.7 para realizar los ajustes de los micro servicios desarrolladon en el framework Beego de forma masiva y automática.

Refactoriza los métodos POST, GETONE, GETALL, PUT, DELETE, en los controladores de una API hecha en Beego; especifican el [código de estado HTTP](https://es.wikipedia.org/wiki/Anexo:C%C3%B3digos_de_estado_HTTP) de cada solicitud y retornando siempre un JSON.

la única restricción que existe, es que **solo realiza los ajustes en micro servicios que nos se han personalizado o modificado en sus líneas**. 


A la izquierda el método por defecto en el Framewrok a la derecha el refactor


### POST
![Refactor Metodo Post](/images/post.png)

### GETONE
![Refactor Metodo GetOne](/images/getone.png)

### GETALL
![Refactor Metodo GetAll](/images/getall.png)

### PUT
![Refactor Metodo Post](/images/put.png)

### DELETE
![Refactor Metodo Post](/images/delete.png)

## Ejecutar Script

Clonamos este repositorio

    git clone https://github.com/jotavargas/refactor_controller.git

Ingresamos al proyecto para ejecutar main.py

    cd refactor_controller

Ejecutamos Script

    # Ejecutar con python 2.7
    python main.py -F ruta_controladores_del_api_a_refactoring


## Licencia

This file is part of refactor_controller.

refactor_controller is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Foobar is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Foobar.  If not, see <https://www.gnu.org/licenses/>.
