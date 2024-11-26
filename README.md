# Documentação do Jogo 2D “MOONWALK”

## Introdução
Este projeto consiste em um jogo 2D inspirado no clássico Mario, desenvolvido em JavaScript utilizando o elemento canvas para renderização gráfica. O objetivo do jogo é proporcionar uma experiência interativa com mecânicas de movimentação, colisão e interação com plataformas e inimigos.

## Especificação do Algoritmo
•	Movimentação do personagem: Implementada com física básica, incluindo pulo, corrida e gravidade.

•	Colisões: Algoritmo para detectar colisões entre o personagem e plataformas,  garantindo interações precisas.

•	Renderização: Uso do canvas para desenhar os elementos do jogo, como personagens, plataformas e cenários.

•  	Lógica do jogo: Controle de eventos, como vitória ou derrota, com base nas condições do jogo.

## Análise de Complexidade
•	Renderização: O desempenho depende do número de elementos ativos na tela. O uso de ciclos otimizados para atualização reduz o impacto no tempo de execução.

•	Colisões: Implementadas com verificações otimizadas para reduzir a carga computacional, mesmo em mapas com muitos objetos.

## Organização do Código
•	Estrutura modular: Código separado em funções para movimentação, colisão, renderização e lógica do jogo.

•	Clareza: O código foi dividido em 6 partes: Importação de Imagens, Configuração do **Canvas, Gravidade, Classe Player, Classe Platform, Classe GenericObject**. Feito no arquivo **Canvas.js**

## Testes e Validação
•	Casos testados: Movimentação normal, saltos, colisões em diferentes cenários, e interação com inimigos.

•	Casos limite: Testes em bordas do mapa, movimentação em alta velocidade e colisões em áreas pequenas.

•	Correções: Ajustes no comportamento do personagem e na detecção de colisões foram realizados durante os testes.

   ## História 
A história relata a missão de um astronauta que precisa ir para a lua em busca de um material que é capaz de evitar a extinção humana e um futuro apocalíptico, na lua ele enfrenta alienígenas e obstáculos para concluir seu objetivo 

## Conclusão
O jogo 2D foi concluído com uma mecânica funcional e eficiente, cumprindo os objetivos propostos. Ele pode ser expandido para incluir novos elementos e níveis, além de melhorias de design gráfico.

## Possíveis Melhorias Futuras
•	Implementação de níveis adicionais.

•	Adição de sons e música de fundo.

•	Introdução de elementos mais complexos, como power-ups e diferentes tipos de inimigos.

 ## Referências:
http://desenvolvimentodejogos.wikidot.com/criando-jogos-2d

https://youtu.be/4q2vvZn5aoo?si=ABUCnVRAdNenYoy9

## Integrates do Grupo: 
João Gabriel Paiva -29333849

João Victor - 29350301

Rodrigo Júnior- 30256593

## Video Demo

https://github.com/user-attachments/assets/c7af7b66-3a82-4660-bebd-b9768597af2e

## Getting Started

1.  Clone the repo:

        git clone https://github.com/christopher4lis/canvas-boilerplate.git

2.  Install dependencies:

        yarn

    or

        npm install

3.  Run webpack:

        npm start

##Check list

Checklist para o Projeto de Algoritmo em Computabilidade e Complexidade de Algoritmo

**Fase 1: Análise [ João Victor]**
1.	[ João Victor] Problema selecionado e definido claramente.
2.	[ João Victor ]  Compreensão aprofundada da natureza e desafios do problema.
3.	[ João Victor ] Modelo matemático ou teórico desenvolvido para representar o problema.
   
**Fase 2: Planejamento [João Gabriel ]** 
1.	 [ João Gabriel ] Objetivos do algoritmo definidos com clareza.
2.	 [ João Gabriel ] Métricas para avaliação de eficiência do algoritmo estabelecidas.
3.	 [ João Gabriel e ] Estratégia geral de resolução do problema proposta.
4.	 [ João Gabriel ] Subproblemas identificados e divididos, se aplicável.
5.	 [ João Gabriel ] Estrutura geral do algoritmo esboçada.
6.	 [ João Gabriel ] Casos limite ou situações especiais identificados.
7.	 [ João Gabriel ] Análise teórica realizada para verificar a correção do algoritmo.

**Fase 3: Desenho [ João Gabriel ]**
1.	 [ João Gabriel ] Análise de complexidade realizada para avaliar a eficiência teórica do algoritmo.
2.	 [ João Gabriel ] Pontos críticos do algoritmo identificados para otimização, se necessário.
   
**Fase 4: Programação e Teste [João Gabriel ]**
1.	[  João Gabriel ] Algoritmo traduzido com precisão em código de programação.
2.	[  João Gabriel ] Código de programação escrito de forma clara e organizada.
3.	[ João Gabriel ]  Testes rigorosos realizados em uma variedade de casos de teste.
4.	[ João Gabriel ] Casos limite e situações especiais testados.
5.	[ João Gabriel ] Erros e problemas durante o teste de programa identificados e corrigidos.


**Documentação e Avaliação do Projeto [ Rodrigo Junior]**
1.	 [ Rodrigo Junior ] Documentação completa, incluindo especificação do algoritmo e análise de complexidade.
2.	 [ Rodrigo Junior ] Documentação revisada para clareza e rigor técnico.
3.	 [ Rodrigo Junior ] Avaliação da eficácia do algoritmo em termos de tempo de execução, uso de recursos e precisão na resolução do problema.
4.	 [ Rodrigo Junior ] Avaliação da colaboração da equipe e cumprimento dos prazos.

   
**Apresentação e Conclusão do Projeto [ João Victor ]**
1.	[ João Victor ] Apresentação do projeto preparada com informações claras e objetivas.
2.	[ João Victor ] Conclusões do projeto destacando os resultados e aprendizados.
3.	[ João Victor ] Discussão sobre o projeto e respostas a perguntas da audiência.

