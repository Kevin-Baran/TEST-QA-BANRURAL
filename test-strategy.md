el evento guessSubmit.addeventListener no se reconoce como una función ya que está mal escrita, se debe reemplazar por guessSubmit.addEventListener.

constante lowOrHi contiene un valor nulo porque se está referenciando mal el atributo class, para solucionarlo primero se agrega un punto (.) antes del nombre de la clase.

el evento resetButton.addeventListener no se reconoce como una función ya que está mal escrito, se debe reemplazar por resetButton.addEventListener.

let randomNumber = Math.random() * 10, no genera un número aleatorio entre 1 al 100, para solucionarlo se debe redondear el número entre 0 y 1 obtenido de la función Math.random, luego se multiplica por 100 y se le suma 1 al resultado de esta forma: let randomNumber = Math.floor(Math.random() * 100) + 1; 

const ATTEMPS = 5; solo permite 5 intentos, se debe cambiar el valor a 10.

las condiciones if no tienen una igualación correcta, para solucionarlo se debe utilizar === en vez de ====, los textos que se muestran en el párrafo se deben colocar en la condición correcta y con el color correcto.

label "guessField" debe tener un input type "number" para permitir el ingreso solo de números.

se debe crear una condición que compruebe si el número que se ingresa es decimal, para ello se divide el número entre 1, si el residuo es 0 es entero, de lo contrario decimal.