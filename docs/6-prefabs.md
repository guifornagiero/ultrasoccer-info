## Prefabs

### Nome
- Humano
- Alien
- Meteoro
- Exercito
- Bola
- Poderes

### Descrição
- Humano - Prefab dos personagens jogáveis do game. Inclui componentes básicos de física para detectar colisões com inimigos e com a bola do jogo, controlador de animações para a execução de habilidades especiais e chutes.

- Alien - Prefab dos inimigos do game. Inclui componentes básicos de física para detectar colisões com o player e com a bola do jogo, controlador de animações para a execução de habilidades especiais e chutes.

- Meteoro - Prefab utilizado em cutscenes e background do game, utilizando animações e efeitos visuais conforme necessário da cena. 

- Exercito - Prefab utilizado em cutscenes e background do game, utilizando animações e efeitos visuais conforme necessário da cena.

- Bola - Prefab da bola utilizada nas partidas do game. Inclui componentes básicos de física para detectar colisões com os personagens do player e aliens do jogo, controlador de animações para representar variações de velocidade, força e outros efeitos visuais.

- Poderes - Prefab dos poderes especiais presentes no game. Inclui componentes visuais, sons e script para controlar o comportamento das habilidades presentes no game.

### Quando são utilizados
Variando a cada partida os prefabs relacionados à jogabilidade seriam instanciados, como os de aliens, humanos, bola e poderes. Em cutscenes e background seriam instanciados os prefabs visuais como o exercito e o meteoro.

### Quais seus componentes
- **Sprites:** Personagens, bola, alienígenas
- **Colisores:** Detectam impactos e interações
- **Fontes de áudio:** Sons e trilhas
- **Scripts:**
  - Controle de movimentação
  - Ativação de habilidades
  - Comportamento da IA
  - Placar
  - Eventos de fase (gravidade, bola flamejante)
