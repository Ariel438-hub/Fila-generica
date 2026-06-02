# Implementando uma Fila Genérica em Java

**Aluno:** Ariel David de Almeida Chaves
**RA:** 1136093

## Objetivo

Desenvolver uma classe genérica `Fila<T>` utilizando Generics em Java, permitindo armazenar objetos de diferentes tipos com segurança de tipos (Type Safety).

## Classes Implementadas

### Fila<T>

Classe genérica responsável pelo gerenciamento da fila.

Métodos implementados:

* `adicionar(T item)`
* `proximo()`
* `primeiro()`
* `vazia()`
* `quantidade()`
* `listar()`

### Cliente

Atributos:

* nome
* cpf

### Chamado

Atributos:

* numero
* descricao

### Pedido

Atributos:

* numero
* valor

## Testes Realizados

Foram criadas e testadas as seguintes filas:

* `Fila<Cliente>`
* `Fila<Chamado>`
* `Fila<Pedido>`

Para cada fila foram realizados os seguintes procedimentos:

1. Adição de dois objetos.
2. Listagem dos elementos.
3. Exibição do primeiro elemento.
4. Remoção do próximo elemento.
5. Nova listagem dos elementos restantes.
6. Exibição da quantidade de elementos.

## Conclusão

A utilização de Generics permitiu criar uma única implementação de fila capaz de armazenar diferentes tipos de objetos, garantindo reutilização de código, organização e segurança de tipos durante a compilação.
