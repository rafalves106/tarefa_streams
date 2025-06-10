# Tarefa Streams

# Filtro de Pessoas com Java Streams

![Status](https://img.shields.io/badge/status-concluído-brightgreen)

Este é um projeto simples em Java desenvolvido como exercício para praticar conceitos modernos da linguagem, incluindo a API de Streams, expressões Lambda e coleções imutáveis.

## 📝 Descrição do Projeto

O objetivo do programa é, a partir de uma lista inicial de objetos `Pessoa`, criar uma nova lista contendo apenas as pessoas do sexo feminino. O processo de filtragem é realizado de forma funcional e declarativa utilizando a API de Streams do Java.

## ✨ Funcionalidades

- **Criação de Dados:** Inicia com uma lista pré-definida de pessoas para demonstração.
- **Modelo de Dados:** Utiliza uma classe `Pessoa` para encapsular os dados (nome, idade e sexo).
- **Processamento com Streams:** Usa a API de Streams para processar a coleção de pessoas.
- **Filtragem por Critério:** Aplica um filtro (`filter`) para selecionar apenas os elementos que correspondem ao sexo feminino ("F").
- **Coleta de Resultados:** Gera uma nova lista imutável (`.toList()`) com os resultados da filtragem.
- **Exibição no Console:** Imprime a lista final de mulheres no console, utilizando uma referência de método (`System.out::println`).

## 🛠️ Tecnologias Utilizadas

- `Java 17` (ou superior, pois utiliza o método `.toList()` introduzido no Java 16)
- `Java Streams API`
- `Expressões Lambda`

## 🚀 Como Executar

Para compilar e executar este projeto, você precisará ter o JDK (Java Development Kit) instalado em sua máquina.

### Pré-requisitos

- JDK 16 ou superior.
- Para verificar sua versão do Java, utilize o comando no terminal:
  ```bash
  java -version
