# anjanacodebusters

RESPUESTAS CORRECTAS:


function sum(a, b) {
    return a + b;
}



function factorial(n) {
    if (n === 0 || n === 1) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}


function imprimirTabla(numero) {
    for (let i = 1; i <= 10; i++) {
        console.log(numero + " x " + i + " = " + numero * i);
    }
}


function esPrimo(num) {
    if (num < 2) {
        return false;
    }
    for (let i = 2; i <= Math.sqrt(num); i++) {
        if (num % i === 0) {
            return false;
        }
    }
    return true;
}



function sumaLista(lista) {
    let suma = 0;
    for (let i = 0; i < lista.length; i++) {
        suma += lista[i];
    }
    return suma;
}
