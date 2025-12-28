# ☕ Fundamentos de Programação em Java

Resumo dos principais conceitos fundamentais da linguagem **Java**, utilizado como material de apoio para aulas e revisão.

---

## 🧱 Padrões de Desenvolvimento

Padrões de desenvolvimento são **boas práticas** que ajudam a criar código organizado, reutilizável e de fácil manutenção.

### Objetivos principais:
- Separação de responsabilidades
- Código limpo e legível
- Facilidade de manutenção
- Escalabilidade

### Padrões e princípios comuns:
- **MVC (Model-View-Controller)**: separa dados, regras de negócio e interface
- **POO (Programação Orientada a Objetos)**: baseada em classes e objetos
- **SOLID**: princípios para código orientado a objetos de qualidade
- **DRY (Don't Repeat Yourself)**: evita repetição de código
- **KISS (Keep It Simple, Stupid)**: mantenha o código simples

---

## 💡 Conceitos Fundamentais

### Algoritmo
Sequência lógica de instruções para resolver um problema.

### Classe
Modelo que define atributos e comportamentos de um objeto.

### Objeto
Instância de uma classe.

### Método
Função pertencente a uma classe que executa uma ação.

### Atributo
Variável declarada dentro de uma classe.

---

## 🔑 Keywords (Palavras-chave do Java)

Keywords são **palavras reservadas do Java** e não podem ser usadas como identificadores.

### Principais keywords:
- `class`
- `public`, `private`, `protected`
- `static`
- `void`
- `if`, `else`
- `switch`, `case`
- `for`, `while`, `do`
- `return`
- `new`
- `this`
- `package`, `import`
- `extends`, `implements`

---

## 🧩 Tipos Primitivos em Java

Java possui **8 tipos primitivos**, usados para armazenar valores simples.

| Tipo     | Descrição                 | Exemplo |
|---------|---------------------------|---------|
| `byte`  | Inteiro pequeno (8 bits)  | `10`    |
| `short` | Inteiro curto (16 bits)   | `100`   |
| `int`   | Inteiro (32 bits)         | `1000`  |
| `long`  | Inteiro longo (64 bits)   | `1000L` |
| `float` | Decimal (32 bits)         | `3.14f` |
| `double`| Decimal (64 bits)         | `3.14`  |
| `char`  | Caractere Unicode         | `'A'`   |
| `boolean` | Verdadeiro ou falso     | `true`  |

---

## ✍️ Operadores de Atribuição

Usados para **atribuir ou atualizar valores** em variáveis.

### Operadores:
- `=` → atribuição simples
- `+=` → soma e atribui
- `-=` → subtrai e atribui
- `*=` → multiplica e atribui
- `/=` → divide e atribui
- `%=` → resto e atribui

```java
int x = 10;
x += 5; // x agora vale 15
🧠 Operadores Lógicos
Utilizados em estruturas condicionais.

Operador	Significado
&&	E lógico
`	
!	NÃO lógico

java
Copiar código
if (idade >= 18 && temCarteira) {
    System.out.println("Pode dirigir");
}
➕ Operadores Aritméticos
Executam operações matemáticas básicas.

Operador	Função
+	Soma
-	Subtração
*	Multiplicação
/	Divisão
%	Resto
++	Incremento
--	Decremento

java
Copiar código
int resultado = (10 + 5) * 2;
🔢 Operadores Bitwise (Bit-a-Bit)
Operam diretamente sobre os bits dos números inteiros.

Operador	Nome
&	AND
`	`
^	XOR
~	NOT
<<	Shift à esquerda
>>	Shift à direita

java
Copiar código
int a = 5;  // 0101
int b = 3;  // 0011

int c = a & b; // resultado: 1
📌 Conclusão
Esses conceitos representam a base do desenvolvimento em Java. Dominar esses fundamentos é essencial para avançar em temas como coleções, exceções, streams, frameworks e desenvolvimento backend.

✍️ Resumo criado para fins educacionais e revisão de aulas em Java.

yaml
Copiar código

---
