# Sistema de Cadastro de Pessoas

Este é um projeto Java simples que demonstra o uso de construtores e encapsulamento para criar um sistema básico de cadastro de pessoas.

## Estrutura do Projeto

O projeto contém duas classes principais:

### Pessoa.java

Classe que representa uma pessoa com os seguintes atributos:

- **nome** (String, final): Nome da pessoa (imutável após criação)
- **cpf** (String, final): CPF da pessoa (imutável após criação)
- **endereco** (String): Endereço da pessoa (pode ser alterado)

#### Métodos:

- `Pessoa(String cpf, String nome)`: Construtor que recebe CPF e nome
- `getNome()`: Retorna o nome da pessoa
- `getCpf()`: Retorna o CPF da pessoa
- `getEndereco()`: Retorna o endereço da pessoa
- `setEndereco(String endereco)`: Define o endereço da pessoa

### SistemaCadastro.java

Classe principal que contém o método `main` e demonstra o uso da classe `Pessoa`:

- Cria uma instância de `Pessoa` com CPF "123" e nome "MARCOS"
- Define o endereço como "RUA DAS MARIAS"
- Exibe as informações da pessoa no console

## Saída Esperada

```bash
MARCOS - 123
```

## Conceitos Demonstrados

- **Construtores**: Uso de construtor personalizado para inicializar objetos
- **Encapsulamento**: Uso de modificadores de acesso (private) e métodos getter/setter
- **Imutabilidade**: Uso de `final` para campos que não devem ser alterados após a criação
- **Programação Orientada a Objetos**: Criação de classes e objetos em Java

## Tecnologias Utilizadas

- Java
- IntelliJ IDEA (configuração do projeto)
