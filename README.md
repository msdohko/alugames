# AluGames

AluGames é um projeto desenvolvido durante o curso da Alura, focado em praticar lógica de programação e manipulação de DOM com JavaScript. O projeto simula um sistema de aluguel de boardgames com interface interativa.

## Sobre o Projeto

Este projeto foi criado como parte do curso da Alura para exercitar conceitos fundamentais de desenvolvimento web, incluindo:
- Manipulação de elementos HTML via JavaScript
- Estilização responsiva com CSS
- Lógica de alternância de estados
- Boas práticas de estruturação de código

## Descrição Detalhada

O AluGames apresenta uma interface moderna e intuitiva para gerenciar o aluguel de jogos de tabuleiro. Cada jogo possui:
- Imagem do jogo
- Nome do jogo
- Botão para alternar status (Alugar/Devolver)

### Funcionalidades Implementadas

1. **Alternância de Status**: Ao clicar no botão de cada jogo, o status alterna entre "Alugar" e "Devolver"
2. **Feedback Visual**: Quando um jogo está alugado, a imagem recebe um overlay escuro e o botão muda de cor
3. **Interface Responsiva**: O layout se adapta a diferentes tamanhos de tela
4. **Design Moderno**: Utiliza gradientes, sombras e efeitos visuais para uma experiência agradável

### Estrutura do Código

#### HTML (`index.html`)
- Estrutura semântica com `main`, `section` e `ul`
- Organização clara dos elementos de interface
- Integração com JavaScript através de eventos `onclick`

#### CSS (`main.css`)
- Reset CSS para consistência entre navegadores
- Sistema de cores com gradientes e transparências
- Layout flexível com Flexbox
- Media queries para responsividade
- Classes utilitárias para estados dos jogos

#### JavaScript (`app.js`)
- Função `alterarStatus(id)` para manipular o estado dos jogos
- Seleção de elementos DOM
- Adição/remoção de classes CSS
- Alteração dinâmica do texto dos botões

## Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização moderna com Flexbox, gradientes e animações
- **JavaScript**: Manipulação de DOM e lógica de interação
- **Fontes**: Google Fonts (Chakra Petch e Inter)

## Estrutura do Projeto

```
alugames/
├── css/
│   ├── _reset.css          # Reset de estilos
│   └── main.css           # Estilos principais
├── img/
│   ├── logo.svg           # Logo do projeto
│   ├── fade_bar.svg       # Elemento visual
│   ├── hachuras.svg       # Elemento visual
│   ├── monopoly.png       # Imagem do jogo
│   ├── takenoko.png       # Imagem do jogo
│   └── ticket_to_ride.png # Imagem do jogo
├── js/
│   └── app.js            # Lógica JavaScript
├── index.html            # Página principal
└── README.md            # Documentação
```

## Como Executar

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` em seu navegador preferido
3. Interaja com os botões para testar a funcionalidade de aluguel

## Aprendizados do Curso

Este projeto demonstra conceitos importantes aprendidos no curso da Alura:
- **Manipulação de DOM**: Como selecionar e modificar elementos HTML
- **Eventos JavaScript**: Responder a interações do usuário
- **CSS Classes**: Usar classes para aplicar estilos condicionalmente
- **Responsividade**: Adaptar o layout para diferentes dispositivos
- **Organização de Código**: Estruturar arquivos e pastas de forma lógica

## Créditos

Projeto desenvolvido durante o curso da Alura, focado em práticas de lógica de programação e desenvolvimento web front-end. 