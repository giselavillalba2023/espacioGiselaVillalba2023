# espacioGiselaVillalba2023
// https://www.youtube.com/watch?v=bmGPv687toc&t=454s
/// imprimir algo en la consola
console.log("hola"); //minuto 3:27
//nombre de variable nro igual a 5
//las valiables puede ser numero, decimales, texto y booleano
//var nro = 5      
// forma ideal y tecnica de nombrar una varieble es con CAMEL CASE ejemplo: miNro
var miNro = 25     // Valor nemerico
console.log(miNro);

var miTexto = "Gaspar" // valor texto
console.log(miTexto);
//minuto 7:27

var miBooleno = true //valor booleano true o false. Un bolleano es muy primitivo hacer referencia a 0 apagado y 1 prendido
console.log(miBooleno);

// crear mensajes concatenando variables
var miMsj = "Mi edad es: " + miNro + "crear mensajes concatenando variables";
console.log(miMsj);

var miSuma = 2 + 3; //sumar numeros
console.log("Mi suma es: " + miSuma);

var miResta = 2 - 3; //restar numeros
console.log("Mi resta es: " + miResta);

var miDivision = 2/3; //sumar numeros
console.log("Mi división es: " + miDivision);

var miMultiplicacion = 2 * 3; //sumar numeros
console.log("Mi multiplicación es: " + miMultiplicacion);

//Operaciones aritmeticas son la suma, resta, mutiplicación y multiplicación solo con variables
var Operador1 = 8; 
console.log("Operador 1 es: " + Operador1);

var Operador2 = 4; 
console.log("Operador 2 es: " + Operador2);

var sumarVariables = Operador1 + Operador2;
console.log("La suma de las variables/ operadores es: " + sumarVariables);

var restaVariables = Operador1 - Operador2;
console.log("La resta de las variables/ operadores es: " + restaVariables);

var divVariables = Operador1 / Operador2;
console.log("La división de las variables/ operadores es: " + divVariables);

var multiVariables = Operador1 * Operador2;
console.log("La multiplicación de las variables/ operadores es: " + multiVariables);

// minuto 16:03

//let reemplaza a var a una variables en los condicionles
let miNroo = 5;

let miNrooResult = miNroo == 5;
console.log(miNrooResult);

let miNrooResult2 = miNroo == 7;
//Si hubiera puesto 7 en let miNrooResult = miNroo == 7; me tendria que devolver false.
console.log(miNrooResult2);

let miNrooo= 6;
let miNombre = "Gisela";

// OTRO METOTODO PARA HACER CONDICIONAL CON IF

//condicional usar if
// 2 == es comparativo

//CASO DE TRUE MI NRO VALE 6

if (miNrooo == 6)
{console.log("Mi nro es igual a 6")// minuto 17:28
} else{
console.log("Mi nro NO es igual a 6")
};

//CASO DE fALSE MI NRO VALE 6

let miNroooo= 7;

if (miNroooo == 6)
{console.log("Mi nro es igual a 6")// minuto 17:28
} else{
console.log("Mi nro NO es igual a 6")
};

//El valor puede ser el mismo aunque sea texto

if (miNrooo == "6")
{console.log("Mi nro es igual a 6 aunque sea texto")// minuto 17:28
} else{
console.log("Mi nro NO es igual a 6")
};

//Agregar 3 === para que diferencie entre una variable de texto y numerica

if (miNrooo === "6")
{console.log("Mi nro es igual a 6 aunque sea texto")// minuto 17:28
} else{
console.log("Mi nro es igual a 6, pero es texto no numerico")
};

// Mi numero es distinto != a 6

if (miNrooo != 45)
{console.log("Si, mi nunero es distinto a 6")// minuto 17:28
} else{
console.log("Mi nro continua siendo 6")
};

//**************
if (miNrooo != 6)
{console.log("Si, mi nunero es distinto a 6")// minuto 17:28
} else{
console.log("NO, mi nro continua siendo 6")
};

//**********
if (miNrooo > 5)
{console.log("Si, mi numero es mayor a 6")// minuto 17:28
} else{
console.log("NO, mi numero NO es mayor a 6")
};

//**********
if (miNrooo > 7)
{console.log("Si, mi numero es mayor a 6")// minuto 17:28
} else{
console.log("NO, mi numero NO es mayor a 6")
};

//**********
if (miNrooo >= 6)
{console.log("Si, mi numero es mayor E IGUAL a 6")// minuto 17:28
} else{
console.log("NO, mi numero NO es mayor a 6")
};

// Usar el && para unir dos respuesta o validaciones

if (miNrooo > 5 && miNombre == "Gisela")
{console.log("Si, mi numero es mayor a 6 y mi nombre es Gisela")// minuto 17:28
} else {
console.log("NO, mi numero NO es mayor a 6")
}

/*** Mi nombre no es Gisela */

if (miNrooo > 5 && miNombre == "Maria")
{console.log("Si, mi numero es mayor a 6 y mi nombre es Gisela")// minuto 17:28
} else {
console.log("NO, mi numero NO es mayor a 6 y mi nombre NO es Gisela")
}

// Usar el || (or) para unir dos respuesta o validaciones y aunque una sea correcta y la otrA NO o ambas correctas o no correctas
// Caso mi nombre no es correcto
if (miNrooo > 5 || miNombre == "Maria")
{console.log("Si, mi numero es mayor a 6 || pero mi nombre No es Gisela")// minuto 17:28
} else {
console.log("NO, mi numero NO es mayor a 6 y mi nombre NO es Gisela")
}
// Caso mi nro no es correcto

if (miNrooo > 4 || miNombre == "Gisela")
{console.log("Si, mi numero No es mayor a 6 || pero mi nombre es Gisela")// minuto 17:28
} else {
console.log("NO, mi numero NO es mayor a 6 y mi nombre NO es Gisela")
}
// ninguno es correcto
if (miNrooo > 5 || miNombre == "Maria")
{console.log("El || valida auque ambos datos son incorrectos")// minuto 17:28
} else {
console.log("NO, mi numero NO es mayor a 6 y mi nombre NO es Gisela")
}

//minuto 24:17

// caso positivo
let miNro2 = 5;
if (miNro2 > 0) {
    console.log("Mi nro es poisitivo");
} else if (miNro2 === 0) {
    console.log ("Mi numero es cero");
    
} else {
    console.log("Mi numero es negativo");
}

// caso negativo
let miNro3 = -1;
if (miNro3 > 0) {
    console.log("Mi nro es poisitivo");
} else if (miNro3 === 0) {
    console.log ("Mi numero es cero");
    
} else {
    console.log("Mi numero es negativo");
}

// caso cero
let miNro4 = 0;
if (miNro4 > 0) {
    console.log("Mi nro es poisitivo");
} else if (miNro4 === 0) {
    console.log ("Mi numero es cero");
    
} else {
    console.log("Mi numero es negativo");
}

//*************Bucles***************** Hacer cosas repetitivamente
//******** while y For ***********

//For y while sirven para hacer cosas automaticas repetitivas veces. Que son los bucles y ciclos decir que haga lo mismo muchas veces 

//minuto 27:03

let contador = 0; 
// Agregar la condición con while
// Va contar de cero a 4 porque le va sumar 1
while (contador < 5){
    console.log("Estamos usando while para generar repeticiones " + contador);
    contador = contador + 1;

}
let contador1 = -5; 
while (contador1 < 15){
    console.log("Otro ejemplo el while frena antes de llegar al 15 por a condición de hasta 15 " + contador1);
    contador1 = contador1 + 1;

}


let contador2 = 0; 
// Agregar la condición con while
// Va contar de cero a 4 porque le va sumar 1
while (contador2 <= 5){
    console.log("que mueste del 0 al 5 " + contador2);
    contador2 = contador2 + 1;
}

for (let contador3 = 0; contador3 < 5; contador3 = contador3 + 1) {
    console.log("Hecho con FOR es lo mismo que while pero cambia la estructura " + contador3);    

}

for (let i = 0; i < 5; i++) {
    console.log("Los contadores se repredentan con i y para incrementar con i++ " + i)
    console.log("para disminuir usa i--. El FOR es la manera más moderna para crear repeticiones, bucles o ciclos")   


}

//for (let i1 = 3; i1 < 5; i1--) {
   // console.log("Los contadores se repredentan con i y para incrementar con i++ " + i1)
   // console.log("para disminuir usa i--. El FOR es la manera más moderna para crear repeticiones, bucles o ciclos")  
//}

//******** Que es una función? 36'***********

function saludar() {
    console.log("Hola chic@s (funcion)");
}
saludar();

//Pasar valores a la funcion ejemplo Laura: Para mostrar en pantalla
function saludar2(nombre2) {
    console.log("Pasar un parametro a la función " + nombre2);
}
saludar2("Laura");

//Pasar mas de un parametro ejemplo el nombre y la edad para mostrar en pantalla

function saludar3(nombre3, edad3) {
    console.log("Pasar un parametro a la función (nombre) " + nombre3);
    console.log("Pasar otro parametro a la función (edad) " + edad3);
}
saludar3("Laura", 24);

// Funciones que retornar, usar siempre la función return 

//Multiplicar con funcion 

function Multiplicar1 (num1, num2) {
    let resultado = num1 * num2;
    return resultado;

}
let recibidor1 = Multiplicar1(2, 5);
console.log("Se creo una función de multiplicar 2*5 = " + recibidor1);

//dividir con funcion
function dividir1 (num1, num2) {
    let resultado = num1 / num2;
    return resultado;

}
let recibidor2 = dividir1(10, 5);
console.log("Se creo una función de dividir 10/5 = " + recibidor2);

function dividir1 (num1, num2) {
    let resultado = num1 / num2;
    return resultado;

}

//sumar con funcion
function sumar3 (num1, num2) {
    let resultado = num1 + num2;
    return resultado;

}
let recibidor3 = sumar3(10, 5);
console.log("Se creo una función de sumar 10+5 = " + recibidor3);

//restar con funcion
function restar4 (num1, num2) {
    let resultado = num1 - num2;
    return resultado;

}
let recibidor4 = restar4(10, 5);
console.log("Se creo una función de restar 10-5 = " + recibidor4);

// se puede tambien mostrar los resultados desde la consola tambien ejmeplo:

//restar con funcion
function restar5 (num1, num2) {
    let resultado = num1 - num2;
    return resultado;

}

console.log("Resultado de vista a la pantalla desde la consola y no desde el let como las anteriores funciones operativas (restar 10-6 =) " + restar5(10, 6));

//******** Que es un Arreglo o Arrays? 42'***********
//son listas
//Arreglo o Arrays simple

let miArreglo1 = ["Gisela", "Oscar", "Gustavo"]
console.log(miArreglo1);

//Arreglo o Arrays con bucles

let miArreglo2 = ["Alejandro", "Ruben", "Nery", "Adolfo"]
// miArreglo2[0]; muestra la posición en este caso va a mostrar primero Alejandro 
let mostrar = miArreglo2[1]; 
// Cambiamos la posición miArreglo2[1]; mostrar primero Ruben
console.log(mostrar);

//Arreglo o Arrays con bucles y for

let miArreglo3 = ["Virginia", "Nancy", "Alberto", "Franco", "Nicolas", "Milagros"];
for (let i = 0; i < 6; i++){
console.log("Accediendo al indice: " + i);
let mostrar3 = miArreglo3[i]; 
console.log(mostrar3);
}

//******** Que es un Objeto? 45'***********

let persona1 = {
    nombre: "Gisela",
    edadd: 34,
    femenino: true,

};

let persona2 = {
nombre: "Alberto",
edadd: 39,
femenino: false,
};

console.log(persona1);
console.log(persona2);

//Mostrar solo un atributo o campo
let persona3 = {
    nombre: "Gisela",
    edadd: 34,
    femenino: true,

};

console.log(persona3.nombre);
