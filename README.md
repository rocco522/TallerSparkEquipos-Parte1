# TallerSparkEquipos-Parte1
Crear un API rest usando Spark


Pruebas en PostMan

Obtener todos los equipos
GET http://localhost:4567/obtenerEquipos

Obtener un equipo
GET http://localhost:4567/obtener/id=01

Agregar un equipo nuevo
POST http://localhost:4567/agregar
Enviar en el body la información del equipo nuevo
     {
        "id": "21",
        "nombre": "Ballenita FC",
        "anioFundacion": "2017",
        "numeroTitulos": 0
    }

Eliminar un equipo 
DELETE http://localhost:4567/eliminar/id=10 

Modificar un equipo existente
PUT http://localhost:4567/modificar/id=01
Enviar en el body la información del equipo nuevo
    {
        "id": "01",
        "nombre": "Deportivo Cali",
        "anioFundacion": "1912",
        "numeroTitulos": 10
    }
