# Pesquisa sobre a Linguagem Java

## Dados do grupo

- **Curso:** Bacharelado em Ciência da Computação
- **Unidade curricular:** Tópicos Essenciais para Programação
- **Tema:** Metodologia Ágil
- **Linguagem escolhida:** Java
- **Integrantes:** Aluno(a) 1; Aluno(a) 2; Aluno(a) 3; Aluno(a) 4
- **Link do repositório:** [inserir link do repositório GitHub após criação]

## Objetivo

Pesquisar a linguagem de programação **Java** e organizar o trabalho em formato de acompanhamento ágil, com divisão de tarefas, responsáveis, prazos, status, fontes de pesquisa e datas de conclusão.

## Metodologia ágil utilizada

O grupo utilizou uma organização simples baseada em **Scrum/Kanban**, dividindo a pesquisa em tarefas menores, com acompanhamento do progresso por status. O critério de pronto foi: tarefa pesquisada, fonte registrada, conteúdo revisado e material incluído no repositório.

## Divisão de tarefas

| Tarefa | Responsável | Prazo | Status | Fonte de pesquisa | Data de conclusão |
|---|---|---|---|---|---|
| História da linguagem | Aluno(a) 1 | 23/05/2026 | Concluída | Oracle JLS; Oracle Java | 22/05/2026 |
| Criador(es) | Aluno(a) 1 | 23/05/2026 | Concluída | Oracle JLS | 22/05/2026 |
| Principais características | Aluno(a) 2 | 24/05/2026 | Concluída | Oracle Docs; Java SE | 22/05/2026 |
| Exemplos de código | Aluno(a) 2 | 25/05/2026 | Concluída | Google Java Style Guide; Oracle Docs | 22/05/2026 |
| Áreas de aplicação | Aluno(a) 3 | 26/05/2026 | Concluída | Oracle Java; Java EE; Oracle Docs | 22/05/2026 |
| Vantagens e desvantagens | Aluno(a) 3 | 27/05/2026 | Concluída | Oracle Docs; análise do grupo | 22/05/2026 |
| Empresas que utilizam | Aluno(a) 4 | 28/05/2026 | Concluída | LinkedIn Engineering; Uber Careers; InfoQ/Netflix | 22/05/2026 |
| Curiosidades | Aluno(a) 4 | 28/05/2026 | Concluída | Oracle JLS; Oracle Java | 22/05/2026 |
| Criação do README.md | Aluno(a) 1 e Aluno(a) 2 | 29/05/2026 | Concluída | Pesquisa consolidada do grupo | 22/05/2026 |
| Montagem da apresentação PowerPoint | Aluno(a) 3 e Aluno(a) 4 | 29/05/2026 | Concluída | Documento final e fontes | 22/05/2026 |


## Conteúdo da pesquisa

### História da linguagem

Java é uma linguagem de programação de propósito geral criada no contexto da Sun Microsystems, inicialmente com o nome Oak. A proposta original era atender aplicações embarcadas e dispositivos eletrônicos de consumo, mas a linguagem foi redirecionada para a Internet e lançada publicamente em 1995. Seu lema técnico mais conhecido é a ideia de escrever o programa uma vez e executá-lo em diferentes plataformas por meio da JVM, a Java Virtual Machine.

### Criador(es)

O principal criador associado ao Java é James Gosling. A especificação da linguagem também registra contribuições relevantes de Ed Frank, Patrick Naughton, Jonathan Payne, Chris Warth, Bill Joy, Guy Steele, Richard Tuck, Frank Yellin, Arthur van Hoff, Graham Hamilton e Tim Lindholm. A linguagem surgiu na Sun Microsystems, empresa posteriormente adquirida pela Oracle, que hoje mantém uma parte importante do ecossistema Java.

### Principais características

- Orientada a objetos: organiza o programa em classes e objetos.
- Portável: o bytecode roda na JVM, reduzindo dependência do sistema operacional.
- Fortemente tipada: variáveis, métodos e classes seguem tipos definidos.
- Robusta: possui tratamento de exceções, gerenciamento automático de memória e verificação de tipos.
- Multiplataforma: usada em desktops, servidores, sistemas corporativos, web backend, dispositivos embarcados e aplicações Android legadas.
- Grande ecossistema: possui bibliotecas, frameworks, ferramentas, IDEs e comunidade ampla.

### Exemplos de código

#### Exemplo 1 – Olá Mundo

```java
public class OlaMundo {
    public static void main(String[] args) {
        String linguagem = "Java";
        System.out.println("Olá, mundo! Estamos estudando " + linguagem + ".");
    }
}
```

#### Exemplo 2 – Calculadora simples

```java
public class CalculadoraSimples {
    public static int somar(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        int resultado = somar(10, 5);
        System.out.println("Resultado: " + resultado);
    }
}
```

### Áreas de aplicação

- Sistemas corporativos e aplicações empresariais.
- Backend de aplicações web e APIs.
- Serviços distribuídos e microserviços.
- Aplicações desktop e ferramentas de desenvolvimento.
- Aplicações Android antigas ou projetos que mantêm código Java.
- Sistemas financeiros, bancários e de grande volume de transações.

### Vantagens

- Portabilidade entre plataformas por meio da JVM.
- Comunidade ampla e documentação abundante.
- Ecossistema maduro, com frameworks como Spring, Jakarta EE e ferramentas de build.
- Boa aceitação em sistemas corporativos e de grande escala.
- Gerenciamento automático de memória, o que reduz certos erros comuns.

### Desvantagens

- Sintaxe mais verbosa do que linguagens modernas como Python e Kotlin.
- Consumo de memória geralmente maior do que linguagens de baixo nível, como C.
- Curva de aprendizado inicial em orientação a objetos, JVM, pacotes e ferramentas.
- Alguns sistemas antigos em Java podem acumular código legado difícil de manter.

### Empresas e organizações que utilizam Java

- LinkedIn: relata uso amplo de Java em aplicações e infraestrutura de grande escala.
- Uber: possui equipe e plataforma interna voltadas ao ecossistema Java.
- Netflix: há apresentações técnicas sobre o uso de Java em microserviços e ferramentas internas.
- Oracle: mantém a plataforma Java e distribuições do JDK.
- Empresas do setor financeiro e corporativo: adotam Java pela maturidade, portabilidade e suporte a aplicações empresariais.

### Curiosidades

- O nome original da linguagem era Oak.
- O mascote do Java é conhecido como Duke.
- Arquivos de código-fonte Java usam a extensão .java.
- O código Java é compilado para bytecode, executado pela JVM.
- A linguagem completou 30 anos em 2025, considerando o lançamento público de 1995.

## Estrutura do repositório

```text
Trabalho_Java_Metodologia_Agil/
├── README.md
├── docs/
│   └── Documento_Divisao_Tarefas_Java.docx
├── slides/
│   └── Apresentacao_Java_Metodologia_Agil.pptx
└── src/
    ├── OlaMundo.java
    └── CalculadoraSimples.java
```

## Fontes de pesquisa

- [Oracle - Java Language Specification](https://docs.oracle.com/javase/specs/jls/se6/jls3.pdf)
- [Oracle - Java Documentation](https://docs.oracle.com/en/java/)
- [Oracle - Java Software](https://www.oracle.com/java/)
- [Oracle Brasil - Java Downloads](https://www.oracle.com/br/java/technologies/downloads/)
- [Oracle - Java EE at a Glance](https://www.oracle.com/br/java/technologies/java-ee-glance.html)
- [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)
- [LinkedIn Engineering - Journey to Java 11](https://www.linkedin.com/blog/engineering/infrastructure/linkedin-s-journey-to-java-11)
- [Uber Careers - Java Platform](https://www.uber.com/global/pt-br/careers/list/156819/)
- [InfoQ - How Netflix Really Uses Java](https://www.infoq.com/presentations/netflix-java/)
