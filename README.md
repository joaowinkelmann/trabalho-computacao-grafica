# Flappy Mario com OpenGL

Implementação do jogo Flappy Mario usando PyOpenGL para a disciplina de Computação Gráfica.

# Screenshots

#### Versão v0.4

![Gameplay](screenshots/v0.4/game_over.png)
![Game-over](screenshots/v0.4/gameplay.png)

#### Versão v0.5

![Gameplay](screenshots/v0.5/game_over.png)
![Game-over](screenshots/v0.5/gameplay.png)

#### Versão v1.2

![Gameplay](screenshots/v1.2/game_over.png)
![Game-over](screenshots/v1.2/gameplay.png)

#### Versão v1.6
![Gameplay](screenshots/v1.6/dificuldade_escolha.png)
![Gameplay](screenshots/v1.6/dificuldade_easy.png)
![Game-over](screenshots/v1.6/difuculdade_normal.png)
![Game-over](screenshots/v1.6/dificuldade_hard.png)

# Requisitos
- Deve ser feito na linguagem Python

## Será permitido utilizar somente as seguintes bibliotecas:
- PyOpenGL_accelerate
- glfw
- Pillow (PIL)
- time
- numpy
- random

---

# Critérios de avaliação
- Fazer o personagem voar apertando a tecla ESPAÇO: 1.0 pontos
- Fazer os obstáculos e personagem se movimentarem: 1.0 pontos
- Realizar o tratamento de colisão: 1.0 pontos
- Contador de quantos obstáculos já passou: 1.0 pontos
- Exibir um contador de vidas, o jogo só finaliza quando termina o número de vidas: 1.0 pontos
- Criar objetos que aparecem aleatoriamente no jogo, pode ser vidas, alternador de velocidade, etc: 1.0 ponto
- A entrega do trabalho deverá ser feita enviando os arquivos do projeto no ambiente virtual e compartilhando um link do github que conste todo o código fonte, uma explicação do projeto e algumas telas do jogo: 1+.0 ponto
- Apresentação do trabalho: 3.0 pontos

---

- Na apresentação todos devem falar, será feito perguntas específicas
para cada integrante do grupo. Será descontado pontos da nota do
trabalho caso algum integrante não responda adequadamente às
perguntas
- Devem ser utilizados os comandos vistos em aula, podem ser
utilizados comandos adicionais. Atenção! Se a estrutura do programa
for diferente do que foi visto em aula, será descontado pontos


# Funcionalidades

- Personagem que voa com a tecla ESPAÇO
- Obstáculos em movimento
- Tratamento de colisões
- Contador de obstáculos ultrapassados
- Sistema de vidas
- Itens coletáveis aleatórios

# Dicas
- Podem personalizar os personagens e obstáculos, usem a criatividade!
- Tanto o personagem quanto os obstáculos podem ser representados
por qualquer primitiva geométrica
- Fiquem livre para criar conceitos de vida, condição para terminar o jogo,
pontuação, ranking, etc
- Pode ser feito tanto no ambiente 2D quanto no 3D
- Utilizem a variável de tempo para controlar os movimentos das
primitivas
- Fiquem livres para criar múltiplas classes ou arquivos para o projeto
- Utilizem vetores para armazenar as posições
- Definam variáveis públicas para determinar o tamanho dos sprites,
range de colisão, velocidade, etc

## Como executar Linux

1. Ter Python instalado. (Python 3.12.3 recomendado)
```bash
python --version
```

2. Instale as dependências para utilizar o GLUT:
```bash
sudo apt-get install freeglut3-dev
```

3. Instalar as dependências com pip
```bash
pip install -r requirements.txt
```

4. Execute o jogo:
```bash
python main.py
```
OU
```bash
python3 main.py
```

## Como executar Windows

1. Ter Python instalado. (Python 3.12.3 recomendado)
```cmd
pip --version
```

2. Instale as dependências do glfw:
```cmd
pip install glfw
```

3. Instale as dependências do OpenGL e PyOpenGL_accelerate:
```cmd
pip install PyOpenGL PyOpenGL_accelerate
```

4. Instale o numpy:
```cmd
pip install numpy
```

5. Instale o Pillow:
```cmd
pip install Pillow
```

5. Execute o jogo:
```cmd
python main.py
```