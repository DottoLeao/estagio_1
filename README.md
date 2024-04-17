## 1) Valor da variável SOMA ao final do processamento

### O valor da variável soma = 90

## 2) Verificar se um número pertence à sequência de Fibonacci

    function verificaFibonacci(numero) {
    let a = 0;
    let b = 1;

        while (b <= numero) {
            if (b === numero) {
                return `${numero} pertence à sequência de Fibonacci.`;
            }
            let temp = b;
            b = a + b;
            a = temp;
        }
        return `${numero} não pertence à sequência de Fibonacci.`;

    }

    let numero = 21; // Número a ser verificado
    console.log(verificaFibonacci(numero));

## 3) Completar a sequência lógica

### a) 1, 3, 5, 7, \*\*\_ => Sequência de números ímpares, próximo: 9

### b) 2, 4, 8, 16, 32, 64, \_\_\*\* => Sequência de potências de 2, próximo: 128

### c) 0, 1, 4, 9, 16, 25, 36, \_\*\*\_ => Sequência dos quadrados dos números naturais, próximo: 49

### d) 4, 16, 36, 64, \_\_\*\* => Sequência de quadrados perfeitos, próximo: 100

### e) 1, 1, 2, 3, 5, 8, \_\*\*\_ => Sequência de Fibonacci, próximo: 13

### f) 2,10, 12, 16, 17, 18, 19, \_\_\*\* => Sequência com adição de 8, 2, 4, 1, 1, 1, próximo: 20

## 4) Descobrir qual interruptor controla cada lâmpada

Ligue os interruptores 1 e 2 e deixe o interruptor 3 desligado. Aguarde um tempo.
Depois, desligue o interruptor 2 e entre na sala.
A lâmpada acesa estará conectada ao interruptor 1, a lâmpada quente estará conectada ao interruptor 2 e a lâmpada "fria" estará conectada ao interruptor 3.

## 5) Inverter os caracteres de uma string

```
  function inverterString(str) {
    let novaString = "";
    for (let i = str.length - 1; i >= 0; i--) {
        novaString += str[i];
    }
    return novaString;
    }

  let stringOriginal = "Hello, world!"; // String original a ser invertida
  console.log(inverterString(stringOriginal));
```
