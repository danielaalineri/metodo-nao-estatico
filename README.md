# 🛒 Atualização de Preços com Método de Instância em Java
Este é um projeto simples em Java que demonstra como usar **referência de método

---

## 🚀 Objetivo

- Aplicar um aumento de 10% no preço de produtos.
- Demonstrar o uso de **método de instância** em conjunto com `forEach`.
- Reforçar o uso de programação funcional no Java 8+.

- ---

## 🧩 Estrutura do Projeto
src/
├── app/
│ └── Program.java // Classe principal
├── entities/
│ └── Product.java // Classe representando um produto

---

## 🔧 Como funciona

1. O programa cria uma lista de produtos (`TV`, `Mouse`, `Tablet`, etc.).
2. Para cada produto, aplica-se um aumento de 10% usando:
   ```java
   list.forEach(Product::nonstaticPriceUpdate);

📌 Exemplo de Saída

Tv, 990.00
Mouse, 55.00
Tablet, 385.55
HD Case, 89.00

📚 Conceitos Utilizados

    Java 22.0.2

    Programação funcional

    Interface Consumer<T>

    Referência de método de instância (objeto::metodo)

    forEach em coleções

    ▶️ Como executar
Pré-requisitos:

    JDK 8 ou superior

    IDE Java ou terminal

Via terminal:

javac app/Program.java
java app.Program

👩‍💻 Autora

Daniela Alineri


   
