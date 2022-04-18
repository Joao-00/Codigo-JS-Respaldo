##JavaScript
____________________________________________________________________________________

Esto puede ser en cualquier variable

Let = cambia el valor de la variable dentro del bloque que se está ejecutando
Var = deja el valor de la variable en toda la script
Const = son datos fijos que no cambiarán en la app
____________________________________________________________________________________

++ = operador de incremento
-- = operador de decremento
____________________________________________________________________________________

Operadores IF
if(Condicion){

}else{

}

== Comparador exacto
>  Mayor que
<  Menor que
!= Diferente a

&& AND  Si ambas son verdaderas da true
|| OR   Si una es verdadera da true
!  NOT  Si una es falsa da false
____________________________________________________________________________________

switch(condicion){

	case:
	break;

	case:
	break;

}

____________________________________________________________________________________


```for(inicializacion; evaluacion; iteracion){

}```


inicializacion: iniciamos la variable
evaluacion: hasta cuando realizar el bucle
iteracion: manera de iterar bucle
____________________________________________________________________________________
mientras la condicion se cumpla se repite el proceso
se utilizan los incrementadores o se decrementa

```while(condicion){
		
}```
____________________________________________________________________________________

```do{

}while(condicion);```
____________________________________________________________________________________

tipos de alertas JS

alertas dentro del navegador
```alert("Mensaje de alerta");```

ventanas de confirmacion
```var result = confirm("Mensaje de confirmacion");```
```alert(result);```

ventana de ingreso de datos
```var res = prompt("Mensaje","respuesta");```
```alert("mensaje" + res);```
____________________________________________________________________________________


funciones de js

```function nombrefuncion(parametros, parametros2){
	return "mensaje";
}```

```function mostrarmensaje(parametros){
	console.log("estoy dentro de la funcion");
}```

```mostrarmensaje;```
____________________________________________________________________________________

parametros REST
para usar tantos parametros como quieran

```function ListadoPaises(p1,p2, ...p){
	console.log(p1);
	console.log(p2);
	console.log(p);

}```


```ListadoPaises("españa", "Alemania", "Inglaterra", "Suiza");```
____________________________________________________________________________________

funciones anonimas o callbacks

```function sumar(n1,n2,multiplicar){
	var suma = n1 + n2:
	multiplicar(suma);
	return suma;
}```

```sumar(5,7, function(d){
	console.log("la suma es" + d);
	console.log("la multiplicacion es" + d * 2);
})```
____________________________________________________________________________________

funciones flechas

```function sumar(n1,n2,fun){
	var suma = n1 + n2:
	multiplicar(suma);
	return suma;
}```

```sumar(5,7, d => {
	console.log("la suma es" + d);
	console.log("la multiplicacion es" + d * 2);
})```

si lleva mas de un parametro si incluiremos parentesis
____________________________________________________________________________________

Array y recorrerlos

```var paises = ["espana","suiza","alemania","italia"];```
tambien se puede cambiar paises.length agregando una variable e incluyendo esta funcion dentro.

```for(var i=0; i <= paises.length; i++){
	console.log(paises[i]);
}```

____________________________________________________________________________________


____________________________________________________________________________________
