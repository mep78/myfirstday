single threaded (hilo simple) y sincronico 
es un proceso unico (un camino unico) para resolver algo, y sincronico: en orden se hace cada proceso
ejemplo: hay 10 personas tratando de entrar a una casa por un camino unico, van a entrar de una a la vez

sintax parser
es un programa que lee el codigo, lo intrerpreta y lo envia a la computadora
lexical enviroment: javascript puede cambiar el comportamiento segun donde se haya escrito el codigo
function hola (){ 
    var hola = "hola" 
}
var hola = "hola" (global)

contexto de ejecucion: el entiende el codigo que se esta trabajando en cada momento

global enviroment: cada codigo en jascript corre bajo un contexto de ejecucion puede estar global o dentro de un contexto en una funcion 
var hello = "hello" // global context
function activity (){ //execution context
    var play = "play" 
    function playpiano (){ // execution context
        var playpiano = "playpiano"
        return playpiano
    }
    return playpiano ()
}
return activity ()


