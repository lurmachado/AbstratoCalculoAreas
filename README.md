# Cálculo de Áreas - Classes Abstratas

Este projeto foi desenvolvido em **C#** (Console Application) com o objetivo de demonstrar a aplicação de **Classes e Métodos Abstratos**, além dos conceitos de **Herança**, **Polimorfismo** e o uso de **Enums** na Programação Orientada a Objetos.

## 💻 Sobre o Projeto

O programa simula a leitura de dados de diferentes figuras geométricas (Formas) para calcular e exibir a área de cada uma delas no final da execução. As formas suportadas são:
- **Retângulo:** Baseado na largura e altura.
- **Círculo:** Baseado no raio.

O sistema possui uma classe abstrata genérica `Shape` (Forma) com um atributo de cor (utilizando o Enum `Color`) e um método abstrato `Area()`. As classes `Rectangle` e `Circle` herdam dessa classe base e implementam a sua própria regra de cálculo para a área. 
Isso permite armazenar todas as formas de maneira genérica em uma única lista e processar o cálculo usando polimorfismo.

## 🛠️ Tecnologias e Conceitos Utilizados

- **C# / .NET**
- **Programação Orientada a Objetos (POO):**
  - **Classes Abstratas:** `Shape`
  - **Métodos Abstratos:** Obrigando as subclasses a implementar a lógica do método `Area()`.
  - **Enumerações (Enum):** Para definir as cores das figuras (Black, Blue, Red).
  - **Herança e Polimorfismo**
- Listas Genéricas (`List<T>`)

## 🚀 Como Executar

1. Certifique-se de ter o [.NET SDK](https://dotnet.microsoft.com/download) instalado em sua máquina.
2. Clone este repositório:
   ```bash
   git clone https://github.com/lurmachado/AbstratoCalculoAreas.git
