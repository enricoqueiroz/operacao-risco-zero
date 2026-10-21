# Operação Risco Zero

Jogo cooperativo e colaborativo sobre segurança do trabalho,
com regras e fábrica de riscos, feito em HTML.

## Sobre
Os jogadores formam a equipe de Segurança do Trabalho e da CIPA
de uma fábrica. Riscos aparecem a cada turno e a equipe precisa
neutralizá-los usando cartas de solução (EPI, treinamento e
engenharia). Ninguém joga contra ninguém: a equipe vence ou perde
como um todo.

**Objetivo:** neutralizar todos os riscos da fábrica antes que ela
receba 3 advertências.

## Como jogar
O jogo é um único arquivo HTML e roda direto no navegador, sem
instalação.

1. Baixe o arquivo `Operação_Risco_Zero.html` ou clone o repositório
2. Abra o arquivo no navegador
3. Escolha de 2 a 5 jogadores e informe o nome de cada um
4. Confirme a leitura do manual para iniciar a partida

## Regras resumidas
- Jogo cooperativo para 2 a 5 jogadores
- Cada turno dura 20 segundos
- Em cada turno, o jogador escolhe uma ação:
  - **Aplicar Medida:** usa uma carta de solução da mão em um risco da fábrica
  - **Estudo Técnico:** compra uma carta e passa a vez
- Uma carta só funciona se a categoria ainda estiver pendente no risco
  e o risco aparecer na dica da carta (o Coringa vale para qualquer risco)
- Riscos simples pedem 1 medida; riscos graves pedem 2
- A fábrica comporta no máximo 5 riscos; o 6º gera 1 advertência
- Com o baralho de riscos vazio, passar a vez além da tolerância
  também gera advertência

**Vitória:** o baralho de riscos acaba e a fábrica está vazia.

**Derrota:** a fábrica recebe a 3ª advertência e é interditada.

## Componentes
- Baralho de Riscos: 10 cartas
- Baralho de Soluções: 35 cartas (13 de EPI, 10 de Treinamento,
  10 de Engenharia e 2 Coringas)
- Cargos temáticos sorteados para cada jogador

## Tecnologias
HTML, CSS e JavaScript

## Licença
Distribuído sob a licença MIT. Veja o arquivo `LICENSE`.
