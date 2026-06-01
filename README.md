# Lâmpada Liga/Desliga

Projeto de interação simples com JavaScript puro: um interruptor funcional que liga e desliga uma lâmpada com efeito de luz animado.

## Sobre o projeto

Foi um dos primeiros projetos feitos com JavaScript. O objetivo era entender na prática como o JS se comunica com o HTML — manipulação de DOM, eventos de clique e alteração dinâmica de estilos via código.

Simples na proposta, mas foi aqui que o JS deixou de ser intimidador.

## Funcionalidades

- Botão **I** para ligar a lâmpada
- Botão **0** para desligar a lâmpada
- Efeito de brilho/glow animado ao ligar
- Troca dinâmica de imagem entre lâmpada acesa e apagada
- Feedback visual no interruptor (cores e bordas mudam de estado)

## Tecnologias

- HTML5
- CSS3
- JavaScript (Vanilla)

## Estrutura

```
LAMPADA_LIGA_DESLIGA/
├── css/
│   └── style.css
├── img/
│   ├── acessa.png
│   └── apagada.png
├── js/
│   └── script.js
└── index.html
```

## Como rodar

1. Clone o repositório
2. Abra o arquivo `index.html` no navegador

Ou use a extensão **Live Server** no VS Code para rodar na porta 5501.

## O que aprendi aqui

- Seleção de elementos com `getElementById`
- Manipulação de atributos (`src`, `alt`) via JS
- Alteração de estilos inline com `element.style`
- `addEventListener` para eventos de clique
- Efeitos visuais com `box-shadow` e `border-radius` dinâmicos
