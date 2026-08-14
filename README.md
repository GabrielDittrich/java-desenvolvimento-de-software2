# ☕ Desenvolvimento de Software — Java

Repositório com projetos, exercícios e atividades desenvolvidos durante a disciplina de **Desenvolvimento de Software**, do curso de **Análise e Desenvolvimento de Sistemas da Universidade Positivo**.

Ao longo da disciplina, os conteúdos evoluem dos fundamentos da linguagem **Java** até conceitos mais avançados de **Programação Orientada a Objetos**, incluindo encapsulamento, herança, classes abstratas, interfaces, polimorfismo, coleções, tratamento de exceções e persistência de dados em arquivos.

---

## 📚 Sobre o repositório

O repositório registra a evolução prática dos conteúdos estudados durante a disciplina através de diferentes aplicações de console.

As primeiras atividades trabalham vetores, métodos, classes, objetos e encapsulamento. Conforme o conteúdo avança, são introduzidos conceitos como **ArrayList, herança, sobrescrita de métodos, abstração, interfaces e polimorfismo**.

Nas atividades finais, também são aplicados **tratamento de exceções, validação de entrada e leitura e escrita de arquivos**, permitindo a persistência simples de dados.

---

## 🛠️ Tecnologias utilizadas

### ☕ Linguagem

* **Java**
* **JDK 17+**

### 🧩 Conceitos e recursos

* Programação Orientada a Objetos
* Classes e objetos
* Encapsulamento
* Construtores
* Getters e Setters
* Herança
* Polimorfismo
* Classes abstratas
* Interfaces
* Sobrescrita de métodos
* Arrays
* ArrayList
* Tratamento de exceções
* Entrada de dados com Scanner
* Manipulação de arquivos
* BufferedReader / BufferedWriter
* FileReader / FileWriter

### 🧰 Ferramentas

* **Visual Studio Code**
* **Git**
* **GitHub**

---

## ✨ Conceitos praticados

### Fundamentos de Java

* Variáveis e tipos de dados
* Estruturas condicionais
* `switch`
* Laços de repetição
* Métodos
* Parâmetros e retorno
* Arrays
* Entrada e saída de dados

### Programação Orientada a Objetos

* Classes
* Objetos
* Atributos
* Métodos de instância
* Construtores
* Sobrecarga de construtores
* Encapsulamento
* Getters e Setters
* `toString()`
* Uso de `this`
* Uso de `super`

### Herança e polimorfismo

* Herança com `extends`
* Sobrescrita com `@Override`
* Classes abstratas
* Métodos abstratos
* Interfaces com `implements`
* Polimorfismo
* Especialização de classes

### Estruturas de dados

* Arrays
* ArrayList
* List
* Percorrimento com `for`
* Enhanced `for`

### Tratamento de erros

* `try`
* `catch`
* `finally`
* `throws`
* `InputMismatchException`
* Validação através de exceções

### Persistência em arquivos

* `FileReader`
* `FileWriter`
* `BufferedReader`
* `BufferedWriter`
* Leitura de arquivos `.txt`
* Escrita de registros em arquivos
* Conversão dos registros armazenados para objetos Java

---

# 📈 Evolução das atividades

## 🟢 Aula 04 — Vetores e estruturas de repetição

Prática com arrays e estruturas de controle.

Entre os exercícios desenvolvidos estão:

* criação e preenchimento de vetores;
* percorrimento utilizando `for`;
* identificação de valores pares;
* validação do tamanho de um vetor;
* busca de valores;
* contagem de ocorrências;
* cálculo de média ponderada;
* utilização de menus com `switch`.

---

## 🟢 Aula 05 — Introdução a classes e objetos

Primeiro contato mais direto com Programação Orientada a Objetos através da criação da classe `Aluno`.

Foram praticados:

* definição de classes;
* criação de atributos;
* instanciação de objetos;
* construtor padrão;
* construtor parametrizado;
* utilização de `this`;
* sobrescrita do método `toString()`.

Também foi criada uma classe auxiliar para entrada de dados pelo console.

---

## 🟢 Aula 06 — Objetos e construtores

Continuação dos conceitos de classes e objetos através de exemplos com `Pessoa` e `Personagem`.

A atividade trabalha:

* construtores;
* atributos de objetos;
* passagem de objetos como parâmetros;
* cópia de dados entre objetos;
* métodos responsáveis por apresentar o estado de um objeto.

---

## 🟢 Aula 07 — Métodos e modularização

Exercícios voltados à separação de responsabilidades entre diferentes classes.

Foram desenvolvidos exemplos como:

### Calculadora

Implementação de métodos para:

* soma;
* subtração;
* multiplicação;
* divisão.

### Biblioteca

Modelagem de livros através de atributos como:

* título;
* autor;
* ano.

A atividade também utiliza uma classe `Console` para centralizar a leitura de dados.

---

## 🟢 Aula 08 — Encapsulamento com Getters e Setters

Aplicação de encapsulamento através de diferentes classes.

Entre os exemplos estão:

### 🚗 Carro

* marca;
* modelo;
* ano;
* velocidade;
* aceleração;
* frenagem.

### 💰 Conta bancária

* número da conta;
* titular;
* saldo;
* depósito;
* saque.

### 🎮 Jogador

* nome;
* pontuação;
* nível;
* aumento de pontuação;
* progressão de nível.

Os atributos passam a ser privados e acessados através de **getters e setters**.

---

## 🟢 Aula 09 — Agenda de contatos

Desenvolvimento de uma agenda utilizando objetos `Contato`.

A aplicação trabalha com:

* armazenamento de objetos em array;
* cadastro de contatos;
* busca pelo nome;
* listagem;
* limpeza da agenda;
* controle da posição dos registros.

Essa atividade reforça a integração entre objetos e estruturas de dados.

---

## 🟢 Aula 10 — ArrayList

Introdução às coleções dinâmicas utilizando `ArrayList`.

Foram desenvolvidos dois exemplos principais.

### 🎮 Lista de jogos

Uma coleção de objetos `Jogo`, permitindo adicionar e visualizar os jogos armazenados.

### 🚗 Estacionamento

Gerenciamento de uma coleção de carros utilizando:

* adição de veículos;
* listagem;
* remoção;
* ArrayList.

---

## 🟢 Aula 11 — Introdução à herança

Aplicação do conceito de herança através de uma hierarquia de pessoas.

A classe base:

```text
Pessoa
```

é especializada em:

```text
Aluno
Professor
```

e `Aluno` também é especializado em:

```text
Bolsista
```

Foram utilizados:

* `extends`;
* construtores utilizando `super`;
* atributos herdados;
* sobrescrita do método `toString()`.

---

## 🟢 Aula 12 — Herança e gerenciamento de funcionários

Continuação dos conceitos de herança através de diferentes tipos de funcionários.

A atividade possui classes relacionadas como:

```text
Funcionario
├── Gerente
└── Programador
```

Também é utilizado um sistema de cadastro com:

* `ArrayList`;
* cadastro de funcionários;
* busca por matrícula;
* listagem;
* menu de operações.

---

## 🟢 Aula 13 — Especialização e sobrescrita

Exemplo utilizando uma hierarquia de personagens:

```text
Personagem
├── Heroi
└── Vilao
```

Foram praticados:

* herança;
* construtores;
* `super`;
* getters e setters;
* especialização de atributos;
* sobrescrita de `toString()`.

---

## 🟢 Aula 14 — Classes abstratas e interfaces

Introdução a duas formas importantes de abstração em Java.

### 🚗 Classes abstratas

Foi criada a classe:

```java
Veiculo
```

com métodos abstratos como:

```java
acelera()
parar()
```

implementados pelas subclasses:

```text
Carro
Moto
```

### 🔷 Interfaces

Também foi criada a interface:

```java
Forma
```

implementada por:

```text
Circulo
Quadrado
Retangulo
```

Cada forma possui sua própria implementação para:

```java
desenhar()
calcularArea()
```

A atividade também utiliza uma coleção de objetos do tipo `Forma`, demonstrando conceitos de **polimorfismo**.

---

## 🟢 Aula 15 — Interfaces, abstração e polimorfismo

Continuação do estudo de abstração utilizando uma classe abstrata e uma interface.

A interface:

```java
Acoes
```

define o comportamento:

```java
estudar()
```

A classe abstrata:

```java
Pessoa
```

também define o método abstrato:

```java
falar()
```

As classes `Aluno` e `Professor` herdam de `Pessoa` e implementam os comportamentos de maneiras diferentes.

A classe `Concurseiro` demonstra que uma classe também pode implementar diretamente a interface sem fazer parte da hierarquia `Pessoa`.

---

## 🟢 Aula 16 — Tratamento de exceções

Introdução ao tratamento de erros em Java.

Foram utilizados:

```java
try
catch
finally
throws
```

Também foi utilizada `InputMismatchException` para tratar entradas inválidas pelo console.

Entre os exemplos estão:

* validação de números;
* validação de valores positivos;
* tratamento de valores nulos;
* validação de horas trabalhadas;
* validação do valor da hora de um funcionário;
* propagação de exceções através de `throws`.

---

## 🟢 Aula 17 — Polimorfismo e tratamento de exceções

Aplicação conjunta dos principais conceitos de POO.

### 💳 Sistema bancário

A classe abstrata:

```text
ContaBancaria
```

possui implementações específicas:

```text
ContaCorrente
ContaPoupanca
```

Cada tipo de conta possui seu próprio comportamento para saque e exibição de saldo.

### 📦 Controle de estoque

A interface:

```java
Estoque
```

define operações para:

```java
adicionarItem()
removerItem()
```

A classe abstrata `Produto` implementa a interface e serve como base para:

```text
ProdutoAlimenticio
ProdutoEletronico
```

A atividade combina:

* abstração;
* herança;
* interfaces;
* polimorfismo;
* sobrescrita;
* exceções;
* validações.

---

## 🟢 Aula 18 — Persistência de dados em arquivos

Introdução à leitura e escrita de arquivos em Java.

Foi desenvolvido um gerenciador de jogos utilizando:

```java
FileWriter
BufferedWriter
FileReader
BufferedReader
```

A aplicação permite:

* criar objetos `Jogo`;
* salvar jogos no arquivo `jogos.txt`;
* ler os registros armazenados;
* transformar linhas do arquivo em objetos;
* armazenar os objetos recuperados em um `ArrayList`.

Também são tratadas possíveis falhas de acesso ao arquivo utilizando `IOException`.

---

## 🟢 Aula 19 — Agenda com persistência em arquivo

Evolução do conceito apresentado na aula anterior através de uma agenda de contatos.

A aplicação possui um menu com operações para:

* cadastrar contato;
* buscar contato pelo código;
* listar contatos;
* salvar informações em `agenda.txt`;
* recuperar registros do arquivo;
* converter os registros em objetos `Contato`.

Também são utilizados:

* ArrayList;
* BufferedReader;
* BufferedWriter;
* FileReader;
* FileWriter;
* exceções;
* validação das entradas do usuário.

---

# 📝 Atividades avaliativas

## 📄 Atividade Avaliativa 01 — Folha de Pagamento

Aplicação de console para cálculo de folha de pagamento.

O sistema recebe:

* nome do funcionário;
* quantidade de horas trabalhadas;
* valor da hora.

A partir desses dados são calculados:

* salário bruto;
* INSS;
* IR;
* FGTS.

A atividade utiliza classes, objetos, métodos, encapsulamento básico, estruturas condicionais e menu de opções.

---

## 🐾 Atividade Avaliativa 02 — Sistema de Animais

Sistema de gerenciamento de animais utilizando Programação Orientada a Objetos.

A aplicação utiliza a classe base:

```text
Animal
```

e especializações como:

```text
Ave
Reptil
```

O sistema permite:

* cadastrar animais;
* buscar por identificador;
* listar registros;
* excluir um animal;
* limpar a lista de animais.

São aplicados conceitos como:

* herança;
* construtores;
* sobrescrita de `toString()`;
* ArrayList;
* polimorfismo;
* organização da lógica em diferentes classes.

---

## 👨‍💻 Atividade Avaliativa 03 — Sistema de Funcionários

Aplicação para gerenciamento de diferentes tipos de funcionários.

A estrutura utiliza uma classe abstrata:

```text
Funcionario
├── Gerente
├── Desenvolvedor
└── Estagiario
```

A classe `Funcionario` define o método abstrato:

```java
calcularSalario()
```

Cada especialização implementa sua própria regra de cálculo.

Também foi criada uma interface para comportamentos relacionados ao trabalho:

```java
interfaceTrabalhavel
```

com os métodos:

```java
trabalhar()
relatarProgresso()
```

O sistema possui funcionalidades para:

* cadastrar funcionários;
* buscar por matrícula;
* listar funcionários;
* excluir registros;
* limpar a lista;
* calcular salários conforme o tipo do funcionário.

Essa atividade reúne conceitos de:

* classes abstratas;
* herança;
* interfaces;
* polimorfismo;
* ArrayList;
* sobrescrita;
* organização em pacotes;
* separação de responsabilidades.

---

# 📁 Estrutura do repositório

```text
java-desenvolvimento-de-software/
│
├── AtividadeAvaliativa1/      # Folha de pagamento
├── AtividadeAvaliativa2/      # Sistema de animais
├── AtividadeAvaliativa3/      # Sistema de funcionários
│
├── Aula04/                    # Vetores e exercícios
├── Aula05/                    # Classes e objetos
├── Aula06/                    # Objetos e construtores
├── Aula07/                    # Métodos e modularização
├── Aula08/                    # Encapsulamento
├── Aula09/                    # Agenda utilizando arrays
├── Aula10/                    # ArrayList
├── Aula11/                    # Herança
├── Aula12/                    # Herança e funcionários
├── Aula13/                    # Especialização e toString
├── Aula14/                    # Classes abstratas e interfaces
├── Aula15/                    # Interfaces e polimorfismo
├── Aula16/                    # Tratamento de exceções
├── Aula17/                    # Polimorfismo e exceções
├── Aula18/                    # Persistência em arquivos
├── Aula19/                    # Agenda persistida em arquivo
│
└── README.md
```

> O repositório atualmente preserva as atividades a partir da **Aula 04**, além das três atividades avaliativas.

---

# ▶️ Como executar

Os exercícios são projetos Java independentes e executados através do console.

## Pré-requisitos

* JDK 17 ou superior
* Visual Studio Code com suporte a Java ou outra IDE compatível

Clone o repositório:

```bash
git clone https://github.com/GabrielDittrich/java-desenvolvimento-de-software.git
```

Entre na pasta:

```bash
cd java-desenvolvimento-de-software
```

Escolha uma das atividades e abra seu respectivo diretório na IDE.

Por exemplo:

```text
Aula18/
```

Localize a classe que possui:

```java
public static void main(String[] args)
```

e execute a aplicação.

No Visual Studio Code, com o **Extension Pack for Java** instalado, é possível utilizar a opção **Run Java** disponibilizada pelo editor.

---

## 💾 Atividades com arquivos

As Aulas 18 e 19 utilizam arquivos `.txt` para persistência:

```text
Aula18/jogos.txt
Aula19/agenda.txt
```

Esses arquivos funcionam como uma forma simples de armazenamento local utilizada para praticar leitura e escrita de dados em Java.

---

# 🎓 Contexto acadêmico

Repositório desenvolvido durante a disciplina **Desenvolvimento de Software**, do curso de **Análise e Desenvolvimento de Sistemas da Universidade Positivo**.

As atividades registram a evolução prática desde fundamentos de Java e orientação a objetos até conceitos como **herança, abstração, interfaces, polimorfismo, tratamento de exceções e persistência em arquivos**.

---

## ⚠️ Observação

Os projetos foram desenvolvidos com **finalidade acadêmica** e representam diferentes etapas do processo de aprendizado.

Por esse motivo, algumas atividades utilizam implementações simplificadas ou possuem pontos que podem ser aprimorados com os conhecimentos adquiridos posteriormente.

O objetivo do repositório é preservar a evolução prática no desenvolvimento com Java e nos principais fundamentos de Programação Orientada a Objetos.
