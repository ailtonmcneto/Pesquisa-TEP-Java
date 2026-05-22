# ☕ Java — Tópicos Essenciais para Programação

> Trabalho acadêmico da disciplina **Tópicos Essenciais para Programação**  
> Curso de Ciência da Computação

---

## 👥 Grupo

| Integrante | Tarefas |
|---|---|
| Ailton Neto | Principais características, Exemplos de código, Apresentação PowerPoint |
| Luis Felipe Véras | Vantagens e desvantagens, Áreas de aplicação, README.md |
| Miguel Tavares | Empresas que utilizam, Curiosidades |
| José Paulo Sarmento | História da linguagem, Criadores, Apresentação PowerPoint |

---

## 📋 Sumário

1. [História da linguagem](#-história-da-linguagem)
2. [Principais características](#-principais-características)
3. [Exemplos de código](#-exemplos-de-código)
4. [Áreas de aplicação](#-áreas-de-aplicação)
5. [Vantagens e desvantagens](#-vantagens-e-desvantagens)
6. [Empresas que utilizam](#-empresas-que-utilizam)
7. [Curiosidades](#-curiosidades)
8. [Fontes](#-fontes)

---

## 📜 História da linguagem

A linguagem de programação Java foi desenvolvida em **1991** por **James Gosling** e sua equipe, o chamado _"Green Team"_, na Sun Microsystems. Inicialmente chamada de **Oak**, foi concebida para ser usada em dispositivos de TV interativa e automação residencial.

No início da década de 90, a Sun Microsystems iniciou um projeto secreto para desenvolver tecnologias voltadas a dispositivos inteligentes. Gosling percebeu que o C++ não oferecia a portabilidade necessária e decidiu criar uma linguagem nova — com coleta de lixo automática e total independência de plataforma.

### O nome "Java"

O projeto recebeu o nome **Oak** em homenagem a um carvalho que Gosling avistava pela janela do escritório. Como o nome já estava registrado, foi necessário mudar. Durante uma pausa para tomar café, surgiu a inspiração: **Java** — referência ao café produzido na ilha de Java, na Indonésia.

Java foi lançado publicamente em **1995** e rapidamente se tornou uma das linguagens mais populares do mundo.

---

## ⚙️ Principais características

- **Orientada a objetos** — organiza o programa em classes e objetos, tornando o código mais modular e reutilizável.
- **Portável** — o bytecode roda na JVM, reduzindo dependência do sistema operacional.
- **Fortemente tipada** — variáveis, métodos e classes seguem tipos definidos em tempo de compilação.
- **Robusta** — possui tratamento de exceções, gerenciamento automático de memória e verificação de tipos.
- **Multiplataforma** — usada em desktops, servidores, sistemas corporativos, web backend, dispositivos embarcados e aplicações Android legadas.
- **Grande ecossistema** — bibliotecas, frameworks, IDEs e uma das maiores comunidades de desenvolvedores do mundo.

---

## 💻 Exemplos de código

### Exemplo 1 — Olá, mundo

```java
public class OlaMundo {
    public static void main(String[] args) {
        String linguagem = "Java";
        System.out.println("Olá, mundo! Estamos estudando " + linguagem + ".");
    }
}
```

**Saída:**
```
Olá, mundo! Estamos estudando Java.
```

---

### Exemplo 2 — Calculadora simples

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

**Saída:**
```
Resultado: 15
```

---

## 🌐 Áreas de aplicação

### Desenvolvimento Corporativo (Enterprise Backend)
Grandes bancos, seguradoras e multinacionais utilizam Java para construir sistemas internos complexos, APIs robustas e processamento de grandes volumes de dados — devido à sua estabilidade e segurança.

### Big Data e Ciência de Dados
Grandes ferramentas de processamento e armazenamento de dados em massa foram escritas em Java ou rodam na JVM. Exemplos notáveis: **Apache Hadoop**, **Apache Spark** e **Apache Cassandra**.

### Sistemas Web
Java é amplamente utilizado no backend de grandes portais, e-commerces e plataformas de streaming que exigem alta escalabilidade e suporte a milhões de acessos simultâneos.

---

## ⚖️ Vantagens e desvantagens

### ✅ Vantagens

| Vantagem | Descrição |
|---|---|
| **Portabilidade** | Graças à JVM, o bytecode roda em Windows, Linux e macOS sem reescrita. |
| **Orientação a objetos** | Código mais modular, flexível e reutilizável — ideal para projetos grandes. |
| **Segurança** | A JVM funciona como um _sandbox_ que isola a execução do código; não permite ponteiros brutos, evitando acessos não autorizados à memória. |

### ❌ Desvantagens

| Desvantagem | Descrição |
|---|---|
| **Performance inferior a linguagens nativas** | Por depender da JVM e da compilação JIT, consome mais memória e pode ser mais lento que C ou C++. |
| **Sintaxe verbosa** | Exige mais linhas de código para tarefas simples comparado a Python ou Kotlin. |
| **Alto consumo de memória** | A própria JVM e o gerenciamento automático de memória exigem quantidade significativa de RAM. |

---

## 🏢 Empresas que utilizam

| Empresa | Uso |
|---|---|
| **LinkedIn** | Aplicações e infraestrutura de grande escala. |
| **Uber** | Plataforma interna voltada ao ecossistema Java. |
| **Netflix** | Microserviços e ferramentas internas. |
| **Oracle** | Mantém a plataforma Java e as distribuições do JDK. |
| **Setor financeiro** | Bancos e seguradoras adotam Java pela maturidade e portabilidade. |

---

## 🔍 Curiosidades

- O nome original da linguagem era **Oak**.
- O mascote do Java é chamado de **Duke**.
- Arquivos de código-fonte Java usam a extensão **`.java`**.
- O código Java é compilado para **bytecode**, executado pela JVM.
- A linguagem completou **30 anos em 2025**, considerando o lançamento público de 1995.

---

## 📚 Fontes

- [Oracle Java Documentation](https://docs.oracle.com/en/java/)
- [Oracle Java Language Specification](https://docs.oracle.com/javase/specs/)
- [Java SE Documentation](https://www.oracle.com/java/technologies/java-se-glance.html)
- [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)

---

<div align="center">
  <sub>Trabalho acadêmico — Tópicos Essenciais para Programação · 2026</sub>
</div>
