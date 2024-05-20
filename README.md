# Criando-um-Jogo-de-Obst-culos-no-Roblox

Criar um jogo de obstáculos no Roblox é um projeto divertido e desafiador que envolve várias etapas, desde o planejamento até a codificação e o teste. Vou dividir o processo em módulos e fornecer exemplos de código para ajudá-lo a começar.

### Módulo 1: Planejamento
Antes de começar a codificar, é importante planejar seu jogo. Decida sobre o tema, os tipos de obstáculos, o design do nível e como o jogador irá interagir com o jogo.

**Exemplo de Planejamento:**
- Tema: Aventura na selva
- Obstáculos: Poços de lava, armadilhas de espinhos, plataformas móveis
- Interação: Correr, pular, deslizar

### Módulo 2: Design de Níveis
Use o Roblox Studio para criar o layout do seu jogo. Coloque os obstáculos e defina o caminho que o jogador deve seguir.

**Exemplo de Design de Nível:**
```lua
local obstaculo = Instance.new("Part")
obstaculo.Size = Vector3.new(4, 1, 4)
obstaculo.CFrame = CFrame.new(10, 1, 10)
obstaculo.Parent = game.Workspace
```

### Módulo 3: Scripting
Agora, você vai adicionar funcionalidades ao seu jogo. Isso inclui a movimentação do jogador, a interação com os obstáculos e a lógica do jogo.

**Exemplo de Script de Movimentação:**
```lua
local jogador = game.Players.LocalPlayer.Character
local controle = jogador:WaitForChild("Humanoid"):LoadAnimation(script.Movimentacao)
controle:Play()
```

### Módulo 4: Testes
Teste seu jogo várias vezes para garantir que tudo está funcionando como deveria. Faça ajustes conforme necessário.

**Exemplo de Teste:**
- Verifique se os obstáculos estão funcionando corretamente.
- Jogue o nível várias vezes para testar a dificuldade.

### Módulo 5: Publicação
Depois de testar e refinar seu jogo, é hora de publicá-lo. Compartilhe o link do seu jogo no Roblox e submeta o código no GitHub.

**Exemplo de Publicação no GitHub:**
- Crie um repositório para o seu jogo.
- Adicione todos os arquivos de script.
- Escreva um README detalhado explicando como jogar.

Lembre-se de ser criativo e implementar o jogo no seu estilo, incluindo as exigências do expert. Espero que essas diretrizes e exemplos de código ajudem você a começar seu projeto de jogo de obstáculos no Roblox.
