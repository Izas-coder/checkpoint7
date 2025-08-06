# checkpoint7


function multiplicaSumas(num1, num2, num3, num4) {
    // Sumas de los dos primeros y los dos segundos números
    const sum1 = num1 + num2;
    const sum2 = num3 + num4;

    // Multiplicar sum1 y sum2 
    const result = sum1 * sum2;

    // Condicional
    if (result > 50) {
        console.log("¡El número es mayor que 50!");
    } else {
        console.log("¡El número es menor que 50!");
    }
}

// Pruebas
multiplicaSumas(3, 4, 6, 8);  // sum1=7, sum2=14 → result=98 → mayor que 50
multiplicaSumas(3, 5, 2, 2); // sum1=8, sum2=4  → result=24 → menor que 50

//Output:

//¡El número es mayor que 50!
//¡El número es menor que 50!
