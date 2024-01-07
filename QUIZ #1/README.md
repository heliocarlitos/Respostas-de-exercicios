# QUIZ #1

```javascript
const x = 2;
const y = 4;
const z = (x < y) ? 'x' : 'y';
console.log(z);
```

Aqui estão as etapas de execução e a explicação de cada parte do código:

1. **Declaração de variáveis:**
   - `const x = 2;` define a constante `x` com o valor 2.
   - `const y = 4;` define a constante `y` com o valor 4.

2. **Operador ternário:**
   - `const z = (x < y) ? 'x' : 'y';` usa o operador ternário para comparar se `x` é menor que `y`. Se a condição for verdadeira, ou seja, se `x` for menor que `y`, então `z` recebe o valor `'x'`, caso contrário, `z` recebe o valor `'y'`.

3. **Saída no console:**
   - `console.log(z);` imprime o valor de `z` no console.

Agora, vamos verificar a condição `(x < y)`. Como 2 é de fato menor que 4, a condição é verdadeira. Portanto, `z` será igual a `'x'`. 

Assim, o output (saída) do código será:
```
x
```

Isso ocorre porque a condição `(x < y)` é verdadeira, e o operador ternário atribui `'x'` à variável `z`. Portanto, o console.log(z) imprimirá `'x'` no console. Note que há um pequeno erro de digitação no código fornecido: `conslole.log(z);`. A chamada correta seria `console.log(z);`.

<div align='center'>
[Licença](https://hcadeveloper.github.io/Licenca-MIT/)
</div>