# Computacao Grafica 2026/2 (fim de 2026 e inicio 2027 devido a greve)

## Informações gerais
- **Professor** [Ricardo Fabbri, Ph.D](http://rfabbri.github.io)
- **Datas** das avaliações teóricas
    - P1: 16/12/2026
    - P2: 7/4/2027
- **Repositorio** principal da disciplina: 
    git clone http://github.com/rfabbri/cg-fabbri-IPRJ-UERJ

## Criterio de Avaliacao

M = 0.4*P + 0.6*T

P = (P1 + P2)/2

T = nota de trabalhos e tarefas

Criterio de medias e prova final padrao UERJ

## Aulas Teoricas

- Aula 0 e Aula 1 - ministradas junto com tarefa0 e tareefa1 abaixo

## Aulas Praticas

- Ver secao Tarefas abaixo.

## Explicacao sobre este repositorio
Como compilar, etc
ver AGENTS.md
  
## Linguagem
C/C++ com CMake
Python

### Revisao de C, ponteiros, etc.
C/C++ Fabbri Parte 1 https://youtu.be/Gru0DnXWr0g

C/C++ Fabbri Parte 2 https://youtu.be/k0KfKildD-U

## IDE/Ambiente

### IA/LLMs
- Uso de IA será explorado em alguns projetos

### Vulkan

#### Instalando (2026)
- Linux e Mac: 
    - LunarG SDK
    - Tentar sem root

#### Onde aprender
1) Vulkan tutorial (em paralelo 2, vulkan guide)
2) Vulkan guide
3) Mais pratico para game engine: 
    - http://vkguide.dev
    - Sascha Willems’ How to Vulkan in 2026

4) Instalar RenderDoc https://renderdoc.org
    - Instalar usando tarball
    - Debug visual


#### Other resources
    - https://vulkan.org/learn
    - Blender vulkan backend 
        - https://developer.blender.org/docs/features/gpu/vulkan/
        - source/blender/gpu/vulkan

    - Hardware mental model: A Trip Through the Graphics Pipeline (Parts 1–6)
    - Fabian Giesen’s A Trip Through the Graphics Pipeline and 


## Trabalhos


### Envio

Os trabalhos que forem para serem entregues diretamente ao professor devem ser 
enviados para:

rfabbri@iprj...

ATENCAO: subject tem que conter: [cg-iprj]

Porem a maioria das atividades valendo nota sera semanal e avaliada diretamente
em sala de aula.

### Detalhes, Data de Entrega, etc

A informação de qual tarefa foi passada em que dia pode ser encontrada na pasta
aulas/, a aula correspondente (a de maior numero). No entanto, é
responsabilidade do aluno comparecer às aulas e ficar atento aos e-mails ou se
inteirar com os colegas que compareceram. Chegar a uma aula sem ter se inteirado
da aula anterior quase sempre irá incorrer na falta de compreensão e perda de
nota em atividades.

### Tarefa 0: contas, até 17h de 24nov26

Fazer tanto para o computador usado no LAB,
como para seu computador pessoal, caso sejam diferentes:

0.1) criar uma conta github até a mesma data, caso ainda não tenha, 

0.2) fazer fork do repositorio da disciplina (link no inicio deste arquivo)

0.3) adicionar arquivo hello.cpp manualmente

0.4) submeter a mudanca para seu github pessoal

0.5) realizar um pull request para o hello.cpp apenas a titulo de exeercicio

Teoria: Estudar pipeline geral
- O que é um shader
    - Tipos de shader (visao geral apenas)
- O que faz uma GPU
    Calculos SIMD
    Modelo -> imagem 2D
- Diferença entre Fixed Function pipeline e Compute Pipeline
- Dierença entre rasterização e ray-tracing
- Otimizada para triangulos, por padrao:
    Modelo -> triangulos -> transformacoes -> rasterizacao/oclusao/z-buffer/cor -> imagem 2D
- Fonte:
    Quadro do professor


### Tarefa 1: vulkan, até 17h de 26nov26

1.0) git pull no repo da disciplina
1.1) Conta de estudante do google gemini ou IA de sua preferencia.
1.2) Testar/Instalar o agy (Google Antigravity) na sua máquina pessoal, que foi o
assistente de programação eleito/justificado em aula.
1.3) Instalar Vulkan SDK
1.4) Testar Vulkan SDK rodando vkcube
1.5) Compilar hello

Teoria
- Pipeline lógico padrão baseado em triângulos
- Pipeline hardware parão
- Framebuffers
- Memória
- Fonte:
    - "All the pipelines - journey through the GPU" - Lou Kramer, AMD (youtube)
    - Complementar com outras arquiteturas




### Tarefa  1 para x

### Tarefa 2 para x

## TODO
- abrir ticket de suporte IPRJ (alunos tambem devem): https://atendimento.iprj.uerj.br
    - solicitar softwares ou pacotes
    - qualquer outro problema

## See also
- @AGENTS.md for other natural language / LLM instructions
- [Curso anterior](http://wiki.nosdigitais.teia.org.br/CG) (em fase de upgrade)
- Qualquer duvida, o prof. Fabbri se coloca à disposicao para google meet.
