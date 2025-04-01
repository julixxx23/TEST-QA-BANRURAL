Errores encontrados y corregidos

1) let randomNumber = Math.floor(Math.random() * 100)+1; // generado un numero de 1 a 10 erroneamente, fue corregido para que sea de 1  a 100

2) const ATTEMPS = 10; // estaba inicializado en 5 y tendria que estar en 10

3) const lowOrHi = document.querySelector('.lowOrHi'); // hacia falta el punto antes de llamar a la clase

4) function checkGuess() {

    let userGuess = guessField.value;
    if(isNaN(userGuess) || userGuess<1 || userGuess>100){
      alert("Escribir un valor valido");
      guessField.value = '';
      return; // antes de iniciar debe escribir una restriccion para no meter datos invalidos
    } // se creo una validacion

5) lastResult.textContent = 'Felicitaciones! adivinaste el número!'; // estaba invertido ya qeue aqui iba el felicitaciones ganaste

6) lastResult.style.backgroundColor = 'green'; // el color estaba malo, ya que tendria que ser verde

7) lastResult.textContent = '!!!Pérdistes!!!'; // aqui iba el perdiste

8)  lastResult.style.backgroundColor = 'black'; // el color debia ser negro

9) guessSubmit.addEventListener('click', checkGuess); // La segunda palabra estaba en miniscula y el error era que debia estar en mayuscula

10) resetButton.addEventListener('click', resetGame); // No estaba en mayuscula la letra E y por tanto el error

11) randomNumber = Math.floor(Math.random() * 100)+1;  // generado un numero de 1 a 10 erroneamente, fue corregido para que sea de 1  a 100

Nota: Todo lo detallado y documentado fue testeado multiples veces en la consola del navegador y tambien, analizado el funcionamiento del codigo, con la logica del programa descrita en los requerimientos tanto para el desarollador como el usuario final.