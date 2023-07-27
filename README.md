# anjanacodebusters

RESPUESTAS CORRECTAS:


1) function sum(a, b) {
    return a + b;
}



2) function factorial(n) {
    if (n === 0 || n === 1) {
        return 1;
    } else {
        return n * factorial(n - 1);
    }
}


3) function imprimirTabla(numero) {
    for (let i = 1; i <= 10; i++) {
        console.log(numero + " x " + i + " = " + numero * i);
    }
}


4) function esPrimo(num) {
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



5) function sumaLista(lista) {
    let suma = 0;
    for (let i = 0; i < lista.length; i++) {
        suma += lista[i];
    }
    return suma;
}

6) function invertirCadena(cadena) {
    let resultado = "";
    for (let i = cadena.length - 1; i >= 0; i--) {
        resultado += cadena[i];
    }
    return resultado;
}

7) function numeroMisterioso(numero) {
    return numero * 2 + 5 / (numero - 1);
}

8)function estaOrdenado(arreglo) {
    for (let i = 0; i < arreglo.length - 1; i++) {
        if (arreglo[i] > arreglo[i + 1]) {
            return false;
        }
    }
    return true;
}


