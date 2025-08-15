# Exercicios de React

Lista de exercícios gerados por inteligência artificial e resolvidos por mim para complementar meus estudos autodidata em React. Cada exercício foi gerado conforme meu avanço nos estudos, e aborda um novo conceito da biblioteca, podendo incluir os conceitos anteriores.

Os estilos aplicados às páginas foram criados por IA, tendo em vista que o foco desta lista de exercícios é exclusivamente a prática do React.

Todos os exercícios resolvidos possuem um link para visualizar a resolução através da plataforma [githack.com](https://raw.githack.com/)

## Sumário


## 1. Parâmetro `props`

### 1.1. Componente de Saudação
Criar um componente `<Greeting />` que recebe via props um nome e exibe uma saudação.

### 1.2. Cartão de Produto
Criar um componente `<ProductCard />` que recebe via props os seguintes atributos:

```txt
title (string)
price (número)
description (string)
```
E renderiza um cartão de produto estilizado.

## 2. Trabalhando com Imagens

### 2.1. Avatar de Usuário
Crie um componente `<UserAvatar />` que recebe via props o nome e a url da imagem de um usuário, e exibe a foto com o nome abaixo.

### 2.2. Galeria de Imagens
Crie um componente `<ImageGallery />` que recebe via props um array de URLs e exibe todas as imagens em uma grade (`<div>` com flex ou grid).

## 3. UseState
Exercícios que envolvem o gerenciamento de estado usando useState.

### 3.1. Contador Simples
Crie um componente `<Chronometer />` que tenha um useState para minutos e outro para segundos, exiba os valores e atualize a cada segundo usando um setInterval.

## 4 Eventos

### 4.1. Botão "Ver mais"
Crie um componente que possua um parágrafo com um texto genérico, e um botão "Ver mais" que exibe um segundo parágrafo com a continuação do texto.

### 4.2. Campo de Texto Dinâmico
Crie um componente `<LiveTextInput />` com um input controlado que exibe, em um parágrafo, em tempo real o que o usuário digita.

### 4.3. Alterar cor ao passar o mouse
Crie um componente `<HoverBox />` que exibe um quadrado colorido. Ao passar o mouse (onMouseEnter), a cor muda para uma cor aleatória. Ao remover o mouse (onMouseLeave), volta para a cor original.

### 4.4. Seleção de personagem com imagem
Crie um componente `<CharacterSelector />` que exiba um `<select>` com pelo menos três personagens.

Quando o usuário selecionar um personagem (`onChange`), renderize a imagem correspondente abaixo do seletor.

As imagens podem ser passadas via array de objetos no próprio componente, cada objeto contendo `name` e `imageUrl`.

## 5. Listas

### 5.1. Lista de Tarefas
Criar um componente `<CheckList />` que recebe via props um título e um array de objetos com os itens. Exibir todos os itens da lista dentro de um elemento `<ul>`.

### 5.2. Lista de Itens com Adição
Crie um sistema para adicionar itens a uma lista exibida na tela. Construa um componente `<AddItemForm />` com a caixa de entrada de texto e um botão de confirmação. Construa um `<ItemList />` que exibirá os itens adicionados.

## 6. Objetos em State

## 7. Elevação de State

## 8. Contenção

## 9. UseEffect