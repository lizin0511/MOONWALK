# Documentação do Jogo 2D “MOONWALK”

1. Introdução
Este projeto consiste em um jogo 2D inspirado no clássico Mario, desenvolvido em JavaScript utilizando o elemento canvas para renderização gráfica. O objetivo do jogo é proporcionar uma experiência interativa com mecânicas de movimentação, colisão e interação com plataformas e inimigos.

2. Especificação do Algoritmo
	•	Movimentação do personagem: Implementada com física básica, incluindo pulo, corrida e gravidade.
	•	Colisões: Algoritmo para detectar colisões entre o personagem, plataformas e inimigos, garantindo interações precisas.
	•	Renderização: Uso do canvas para desenhar os elementos do jogo, como personagens, plataformas e cenários.
	•	Lógica do jogo: Controle de eventos, como vitória ou derrota, com base nas condições do jogo.

3. Análise de Complexidade
	•	Renderização: O desempenho depende do número de elementos ativos na tela. O uso de ciclos otimizados para atualização reduz o impacto no tempo de execução.
	•	Colisões: Implementadas com verificações otimizadas para reduzir a carga computacional, mesmo em mapas com muitos objetos.

4. Organização do Código
	•	Estrutura modular: Código separado em funções para movimentação, colisão, renderização e lógica do jogo.
	•	Clareza: Nomeação clara de variáveis e funções, além de comentários explicativos para cada parte importante.

5. Testes e Validação
	•	Casos testados: Movimentação normal, saltos, colisões em diferentes cenários, e interação com inimigos.
	•	Casos limite: Testes em bordas do mapa, movimentação em alta velocidade e colisões em áreas pequenas.
	•	Correções: Ajustes no comportamento do personagem e na detecção de colisões foram realizados durante os testes.

   7. História 
A história relata a missão de um astronauta que precisa ir para a lua em busca de um material que é capaz de evitar a extinção humana e um futuro apocalíptico, na lua ele enfrenta alienígenas e obstáculos para concluir seu objetivo 

7. Conclusão
O jogo 2D foi concluído com uma mecânica funcional e eficiente, cumprindo os objetivos propostos. Ele pode ser expandido para incluir novos elementos e níveis, além de melhorias de design gráfico.

8. Possíveis Melhorias Futuras
	•	Implementação de níveis adicionais.
	•	Adição de sons e música de fundo.
	•	Introdução de elementos mais complexos, como power-ups e diferentes tipos de inimigos.

Referências:
http://desenvolvimentodejogos.wikidot.com/criando-jogos-2d

https://youtu.be/4q2vvZn5aoo?si=ABUCnVRAdNenYoy9

Integrates do Grupo: 
João Gabriel Paiva -29333849
João Victor - 29350301
Rodrigo Júnior- 30256593

https://github.com/user-attachments/assets/c7af7b66-3a82-4660-bebd-b9768597af2e

Canvas Boilerplate is the go-to solution for quickly creating modern canvas pieces using ES6 and webpack.

## Getting Started

1.  Clone the repo:

        git clone https://github.com/christopher4lis/canvas-boilerplate.git

2.  Install dependencies:

        yarn

    or

        npm install

3.  Run webpack:

        npm start

