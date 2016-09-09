# ejercicio1_leccion23
- Declaro mi var= resultado que será mi boton  y lo llamo del html con su id=resultado y a mi boton le daré un evento donde al hacer click me ejecutará mi función anónima. Mi función anónima almacenará los datos ingresados por el usuario( nombre,edad,sexo).
- Declaro mi función constructora EntidadPersona para asignar las propiedades (nombre,edad,sexo) para ello utilizo el this y un método. Este método ejecutará si this.mayor_edad=(this.edad >=18); si es true me retornará: 
 return " Hola, mi nombre es"+ this.nombre+ ", "+ "tengo "+ this.edad+ " años y soy mayor de edad"; si es false retornará lo contrario.
-Declaro var persona= y le asigno las propiedades y métodos de EntidadPersona.
var persona = new EntidadPersona(nombre, edad, sexo);
- Declaro mi var=imprimir llamando con su id=imprimir desde el html, para que se almacene mi texto(el return ) y se visualice en el html.Para ello le doy el valor persona.datos().
