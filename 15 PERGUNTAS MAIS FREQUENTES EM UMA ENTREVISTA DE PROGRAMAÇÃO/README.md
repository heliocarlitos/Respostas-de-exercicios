## 1. O que é programação orientada a objetos (POO)? Explique os principais conceitos.

A Programação Orientada a Objetos (POO) é um paradigma de programação que organiza o código em unidades chamadas objetos, que representam entidades do mundo real. Esses objetos podem conter dados na forma de atributos e comportamentos na forma de métodos. A POO é amplamente utilizada devido à sua capacidade de modelar sistemas de forma mais próxima da realidade, facilitando a manutenção, reutilização e extensão do código.

### Principais Conceitos da POO

1. **Classes e Objetos**: Uma classe é uma estrutura que define o comportamento e os atributos de um tipo de objeto. Os objetos são instâncias das classes.
   
   Exemplo em Python:
   ```python
   class Carro:
       def __init__(self, marca, modelo):
           self.marca = marca
           self.modelo = modelo

   meu_carro = Carro("Toyota", "Corolla")
   ```
2. **Encapsulamento**: É o conceito de esconder os detalhes de implementação de um objeto e fornecer uma interface para interagir com ele.

3. **Herança**: Permite que uma classe herde atributos e métodos de outra classe, promovendo a reutilização de código.

   Exemplo em Python:
   ```python
   class Veiculo:
       def __init__(self, marca):
           self.marca = marca

   class Carro(Veiculo):
       def __init__(self, marca, modelo):
           super().__init__(marca)
           self.modelo = modelo

   meu_carro = Carro("Toyota", "Corolla")
   print(meu_carro.marca)  # Saída: Toyota
   ```

4. **Polimorfismo**: Permite que objetos de diferentes classes sejam tratados de maneira uniforme, facilitando a substituição de implementações.

## 2. Qual é a diferença entre linguagens de programação interpretadas e compiladas?
Uma linguagem de programação interpretada é executada linha por linha, enquanto uma linguagem compilada é traduzida integralmente para linguagem de máquina antes da execução.

## 3. O que é um banco de dados relacional e quais são suas vantagens?
Um banco de dados relacional é um tipo de banco de dados que organiza os dados em tabelas relacionadas. Suas vantagens incluem estruturação de dados consistente, integridade referencial e capacidade de realizar consultas complexas.

## 4. O que é normalização de banco de dados e por que é importante?
A normalização de banco de dados é o processo de organização das tabelas para minimizar a redundância e evitar anomalias de atualização. Isso ajuda a garantir a consistência e integridade dos dados.

## 5. Explique o conceito de herança em programação e como ele é aplicado em linguagens orientadas a objetos.
**Conceito de Herança em Programação:**

A herança é um dos conceitos fundamentais da Programação Orientada a Objetos (POO). Ela permite que uma classe (conhecida como classe derivada ou subclasse) herde atributos e métodos de outra classe (chamada de classe base, superclasse ou pai). Em outras palavras, uma classe pode estender outra classe, aproveitando suas características e comportamentos.

**Como é Aplicado em Linguagens Orientadas a Objetos:**

Em linguagens orientadas a objetos como Python, Java, C++, entre outras, a herança é aplicada de forma direta e intuitiva. Vamos ilustrar com um exemplo em Python:

```python
class Animal:
    def __init__(self, nome):
        self.nome = nome

    def emitir_som(self):
        pass

class Cachorro(Animal):
    def emitir_som(self):
        return "Au au!"

class Gato(Animal):
    def emitir_som(self):
        return "Miau!"

# Criando instâncias das classes derivadas
meu_cachorro = Cachorro("Rex")
meu_gato = Gato("Whiskers")

# Chamando o método da classe base através das classes derivadas
print(meu_cachorro.nome)  # Saída: Rex
print(meu_cachorro.emitir_som())  # Saída: Au au!

print(meu_gato.nome)  # Saída: Whiskers
print(meu_gato.emitir_som())  # Saída: Miau!
```

Neste exemplo, a classe `Animal` é a superclasse, enquanto as classes `Cachorro` e `Gato` são subclasses que herdam de `Animal`. Ambas as subclasses sobrescrevem o método `emitir_som`, fornecendo implementações específicas para cada tipo de animal.

A herança permite reutilizar código, promove a modularidade e facilita a extensão do sistema. Além disso, ela ajuda a organizar e estruturar o código de forma hierárquica, refletindo as relações entre os objetos do mundo real que estamos modelando.

## 6. O que é uma chave primária em um banco de dados e por que é crucial?
Uma chave primária é um campo ou conjunto de campos que identifica exclusivamente cada registro em uma tabela. Ela é crucial para garantir a integridade dos dados e facilitar operações de consulta e atualização.

## 7. Como você lida com a otimização de desempenho em um aplicativo ou site?
A otimização de desempenho envolve a identificação e correção de gargalos de desempenho em uma aplicação ou site. Isso pode incluir aprimoramentos no código, no design da aplicação, no uso de recursos do servidor e na otimização de consultas de banco de dados.

## 8. O que é uma API (Interface de Programação de Aplicativos) e como ela é usada?
Uma API é um conjunto de rotinas, protocolos e ferramentas para construir software e aplicativos. Ela define como componentes de software devem interagir e é amplamente usada para integração de sistemas e desenvolvimento de aplicativos.

## 9. O que é um algoritmo? Dê um exemplo de um algoritmo comum.
Um algoritmo é um conjunto de instruções passo a passo para resolver um problema. Um exemplo comum é o algoritmo de ordenação "Bubble Sort".

## 10. Descreva o processo de controle de versão e qual é a importância disso no desenvolvimento de software.
O controle de versão é o gerenciamento das alterações feitas no código-fonte de um projeto ao longo do tempo. Ele permite acompanhar as modificações, reverter para versões anteriores e colaborar de forma eficiente em equipe.

## 11. Explique a diferença entre um array e uma lista ligada (linked list).
Um array é uma estrutura de dados estática que armazena elementos contiguamente na memória, enquanto uma lista ligada é uma estrutura dinâmica onde cada elemento possui um ponteiro para o próximo elemento.

## 12. O que é a recursividade e em que situações ela é útil?
A recursividade é a capacidade de uma função chamar a si mesma. Ela é útil para resolver problemas que podem ser divididos em casos menores e para percorrer estruturas de dados como árvores e grafos.

## 13. Quais são as diferenças entre desenvolvimento web front-end e back-end?
O desenvolvimento web front-end lida com a interface do usuário e interações no navegador, enquanto o desenvolvimento web back-end trata da lógica e armazenamento de dados no servidor.

## 14. O que é virtualização e como ela é usada na computação em nuvem?
A virtualização é a criação de ambientes virtuais que imitam sistemas de hardware físicos. Na computação em nuvem, ela é usada para compartilhar recursos de hardware de forma eficiente entre várias máquinas virtuais.

## 15. Como você lida com a depuração e resolução de problemas em um código complexo?
A depuração envolve identificar e corrigir erros em um código complexo. Isso pode envolver a utilização de ferramentas de depuração, técnicas de análise de código e compreensão do fluxo de execução do programa.