# QUIZ JS #2

### Código:

```javascript
// Declarando uma variável 'idade' e atribuindo o valor 'ano'
let idade = 'ano';

// Criando um objeto 'pessoa' com uma propriedade dinâmica usando a variável 'idade' como chave
let pessoa = { [idade]: 24 };

// Imprimindo no console o valor associado à propriedade 'idade' no objeto 'pessoa'
console.log(pessoa[idade]);
```

### Explicação:

1. **Variável 'idade':**
   - `let idade = 'ano';`: Declara uma variável chamada 'idade' e atribui a string 'ano' a ela.

2. **Objeto 'pessoa':**
   - `let pessoa = { [idade]: 24 };`: Cria um objeto chamado 'pessoa' com uma propriedade dinâmica. A chave dessa propriedade é obtida pela avaliação da expressão dentro dos colchetes `[idade]`. No exemplo, `idade` é a string 'ano', então a propriedade do objeto é criada como `{ 'ano': 24 }`.

3. **Impressão no Console:**
   - `console.log(pessoa[idade]);`: Imprime no console o valor associado à propriedade 'idade' no objeto 'pessoa'. No exemplo, o resultado será `24`, pois é o valor associado à propriedade 'ano' no objeto.

### Considerações:

- O uso de colchetes `[ ]` ao redor de `idade` ao criar a propriedade no objeto permite que o nome da propriedade seja dinâmico, baseado no valor da variável `idade`.
- A propriedade do objeto é acessada usando `pessoa[idade]` para obter o valor associado à chave dinâmica 'ano'.
- A impressão no console resultará no valor `24`.

<hr>

<span align='center'>
   
   [Licença](https://hcadeveloper.github.io/Licenca-MIT/)
   
</span>