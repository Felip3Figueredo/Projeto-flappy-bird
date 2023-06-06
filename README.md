# Projeto-flappy-bird
 
# Produção de Jogo Flappy Bird com Inteligência Artificial NEAT
Bem-vindo ao projeto de produção do jogo Flappy Bird utilizando a abordagem de Inteligência Artificial (IA) NEAT (NeuroEvolution of Augmenting Topologies). Neste readme, você encontrará informações importantes sobre o projeto, incluindo a descrição do jogo, o conceito da IA NEAT e os passos para executar o jogo.

## Descrição do Jogo
O Flappy Bird é um jogo simples, mas desafiador, no qual o jogador controla um pássaro que deve evitar obstáculos (tubos) ao voar através deles. O jogador controla o pássaro com cliques ou toques na tela para fazê-lo voar mais alto. O objetivo é obter a maior pontuação possível, passando pelos tubos sem colidir com eles ou com o chão.

## Inteligência Artificial NEAT
NEAT é um algoritmo de neuroevolução que permite a criação e o treinamento de redes neurais artificiais. Em vez de projetar manualmente uma rede neural para resolver um problema específico, o NEAT evolui automaticamente a estrutura e os pesos das redes neurais para encontrar uma solução ótima.

No contexto do Flappy Bird, a IA NEAT será usada para treinar uma população de pássaros virtuais. Cada pássaro terá uma rede neural associada que tomará decisões sobre quando bater as asas. Os pássaros serão submetidos a uma função de avaliação que mede seu desempenho, e os melhores pássaros serão selecionados para se reproduzir e gerar a próxima geração. Ao longo das gerações, espera-se que os pássaros aprendam a voar melhor e evitem os obstáculos com mais eficiência.

## Executando o Jogo
Siga as etapas abaixo para executar o jogo Flappy Bird com a IA NEAT:

1 - Requisitos:

* Python 3.x instalado (recomenda-se a versão mais recente).
* Pacotes necessários: pygame, neat-python.

2 - Faça o download dos arquivos do projeto:

* Você pode baixar os arquivos do jogo e da IA NEAT a partir do repositório no GitHub (inserir link do repositório).

3 - Instale as dependências:

* Abra o terminal e navegue até o diretório onde você salvou os arquivos do projeto.
* Execute o seguinte comando para instalar os pacotes necessários:

````
pip install pygame neat-python
pip install pygame
````

4 - Execute o jogo:

* No terminal, execute o seguinte comando:

````python FlappyBird.py````

* O jogo Flappy Bird será iniciado, e você poderá ver os pássaros virtuais evoluindo conforme jogam.

5 - Acompanhe o progresso:

* Durante a execução, o jogo exibirá informações sobre a geração atual, o número de pássaros vivos e a pontuação máxima alcançada até o momento.

6 - Resultados e ajustes:

* Após algumas gerações, você pode acompanhar a evolução do desempenho dos pássaros e ajustar os parâmetros do NEAT, se desejar, para otimizar o processo de treinamento.

7 - Encerrando o jogo:

* Você pode encerrar o jogo a qualquer momento pressionando a tecla "Esc".

## Contribuição e Suporte
Se você quiser contribuir para o projeto ou tiver alguma dúvida, sinta-se à vontade para entrar em contato com a equipe do projeto (inserir detalhes de contato). Agradecemos qualquer contribuição e feedback que você possa fornecer.

Divirta-se jogando Flappy Bird com IA NEAT e aproveite a experiência de ver os pássaros evoluindo e aprendendo a jogar!

## Observação
Caso queira jogar manualmente o jogo, abra o codigo com um editor de codigo, e modifique a variavel ````ai_jogando```` para False.