# Ziru & Zira contra o Monstro do Desamor

![Capa do jogo](capa.png)

**[Jogar agora](https://flavio-dematos.github.io/ziru-e-zira/)**

Beat 'em up em pixel art feito para o casamento de Flávio (Ziru) e Marina (Zira).
O casal atravessa Brasília, Goiânia, Fernando de Noronha e Lisboa enfrentando os
"inimigos do namoro" até derrotar o Monstro do Desamor.

## Como jogar
Abra `index.html` num navegador (ou acesse a versão publicada).
- Teclado: setas/WASD movem · Z/J soco · X/K chute · Espaço pulo · C/L especial
- Celular: controles de toque na tela
- Modos: 1 jogador (parceiro controlado pela CPU) ou coop no mesmo teclado
- Quatro dificuldades

## Destaques técnicos
- JavaScript puro com Canvas 2D, sem bibliotecas nem build obrigatório
- Sprites próprios recortados e empacotados em atlas (Python: Pillow, NumPy, SciPy)
- Máquina de estados para cada inimigo, com golpes especiais únicos
- Cenários em paralaxe desenhados por código
- Jogável no desktop e no celular (controles de toque e áreas seguras de tela)
- Testado com partidas automáticas via Playwright

## Estrutura
- `index.html`: o jogo inteiro (código, fonte e cenários)
- `sprites/`: atlas de personagens e inimigos (WebP)
- `capa.png` / `capa.jpg`: capa do jogo
