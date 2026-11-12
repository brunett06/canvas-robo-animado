# 🤖 Robô Animado em Canvas

Animação de um robô que se movimenta e **rebate nas bordas** do canvas, feita com a API Canvas 2D do HTML5. Projeto da disciplina de Computação Gráfica (Sistemas de Informação, UGB).

**▶️ [Ver animação online](https://brunett06.github.io/canvas-robo-animado/robo-prova.html)** · 🎬 [Vídeo do projeto](robo-video-final.mp4)

## O que o projeto faz
- Desenha o robô com formas básicas: retângulo (cabeça), círculos (olhos e antena) e linhas (boca e haste)
- Move o robô na diagonal com `requestAnimationFrame`
- Calcula o deslocamento pelo **tempo decorrido** entre os quadros, para a velocidade ser a mesma em qualquer computador
- Inverte a direção ao tocar nas bordas (detecção de colisão com as paredes)
- Usa `save()` e `restore()` para isolar o estilo de cada parte do desenho

## Tecnologias
HTML5 · Canvas API · JavaScript

## Como rodar
Abra o arquivo `robo-prova.html` no navegador.

---

<details>
<summary><b>🇺🇸 English</b></summary>

### Animated Robot in Canvas

A robot animation that moves diagonally and **bounces off the canvas edges**, built with the HTML5 Canvas 2D API for a Computer Graphics class (Information Systems, UGB).

- Robot drawn with basic shapes (rectangle, circles, lines)
- Animation loop with `requestAnimationFrame`
- Time-based movement (elapsed time between frames), so speed is the same on any machine
- Wall collision detection that reverses direction

**[Live demo](https://brunett06.github.io/canvas-robo-animado/robo-prova.html)** · Open `robo-prova.html` in a browser to run locally.

</details>
