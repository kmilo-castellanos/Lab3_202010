# Lab3_202010

Este repositorio contiene una plantilla del laboratorio 3 con un ejemplo de implementación de una aplicación en el esquema Modelo-Vista-Controlador que carga datos y realiza consultas usando las estructuras de datos implementadas. Para ejecutar la aplicación debe ejecutar: 
```
python App/view.py
```
*	ADT: archivos Python con la definición de los Tipos Abstractos de Datos.
*	App: aplicación Python cliente que usa las ADTs y ordenamientos para dar solución a laboratorios y retos.
    * view.py: Es el punto de entrada de la aplicación, y se encarga de la entrada y salida de datos, e interacción con el usuario
    * controller.py: Comunica la vista con el modelo a través de las operaciones invocadas por el usuario desde la vista
    * model.py: Representa el modelo del mundo.
*	Data: archivos con los datos (csv, json, txt, etc) usados en el laboratorio o reto. El contenido de esta carpeta NO se debe versionar.
*	DataStructures: archivos Python con las estructuras de datos básicas (listas enlazadas y arreglos).
*	Sorting: archivos Python que implementan los algoritmos de ordenamiento.
*	Test: pruebas unitarias en Python para validar el código desarrollado.

![Modelo-Vista-Controlador](http://sistemasproyectos.uniandes.edu.co/iniciativas/architlab/wp-content/uploads/sites/7/2020/02/MVC.png)
