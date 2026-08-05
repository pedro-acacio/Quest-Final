# Quest Final

Protótipo inicial de um jogo em Godot Engine, ainda em estágio muito preliminar. O repositório contém apenas a montagem de cena: um plano de fundo, um "telão" decorativo e um personagem jogável (`Player`, do tipo `CharacterBody2D`) com uma animação de duas imagens (sprites com tema "Neymar"). Não há nenhum script GDScript no projeto — ou seja, ainda não existe lógica de movimento, colisão, pontuação ou qualquer regra de jogo implementada, apenas os elementos visuais posicionados na cena.

## Tecnologias

- Godot Engine 4.4 (projeto sem scripts GDScript até o momento)
- Sprites em PNG/JPG (pasta `Sprites/`)

## Como rodar

1. Abrir a pasta do projeto no Godot Engine 4.4 (ou compatível).
2. Rodar a cena principal `main.tscn` (definida como cena inicial no `project.godot`).

Como não há scripts de gameplay, ao rodar o projeto apenas as cenas e sprites serão exibidos, sem interação.
