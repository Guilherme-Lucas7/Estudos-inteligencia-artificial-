
Capítulo 2 — Agentes Inteligentes

Exercício 2.3 — Verdadeiro ou falso

a) Falso.

Mesmo sem ter todas as informações do ambiente, um agente pode tomar a melhor decisão possível com aquilo que sabe. Por exemplo, um carro autônomo pode desviar de um obstáculo sem saber tudo que está acontecendo na estrada.

b) Verdadeiro.

Porque existem situações em que o agente precisa lembrar do que aconteceu antes. Um robô em um labirinto, por exemplo, pode precisar guardar os caminhos que já percorreu para não ficar andando no mesmo lugar.

c) Verdadeiro.

Pode existir um ambiente muito simples em que qualquer agente seja racional. Por exemplo, um ambiente que tenha apenas uma ação possível e essa ação seja suficiente para cumprir o objetivo.

d) Falso.

A função de agente considera todo o histórico de informações recebidas. Já o programa recebe as informações atuais e pode guardar as anteriores na memória.

e) Falso.

Nem toda função de agente pode ser colocada em prática por um computador. Algumas podem exigir cálculos impossíveis ou uma quantidade de memória e processamento que não temos.

f) Verdadeiro.

Um agente que escolhe ações aleatórias pode ser racional se todas as opções tiverem o mesmo resultado. Por exemplo, se dois caminhos levam ao mesmo destino com o mesmo custo, qualquer escolha pode ser adequada.

g) Verdadeiro.

Um mesmo agente pode funcionar racionalmente em dois ambientes diferentes, desde que suas decisões sejam adequadas para os dois.

h) Falso.

Mesmo sem conseguir observar o ambiente, um agente ainda precisa escolher boas ações. Se ele escolher uma ação ruim quando existe outra claramente melhor, não estará sendo racional.

i) Falso.

Mesmo um agente racional pode perder no pôquer, porque existe sorte e ele não conhece as cartas dos adversários. Ser racional não significa ganhar sempre.


Exercício 2.4 — PEAS e classificação dos ambientes

O PEAS é utilizado para descrever o ambiente de trabalho de um agente.

* P: desempenho, ou seja, o que ele precisa alcançar.
* E: ambiente onde ele atua.
* A: atuadores, que são os meios utilizados para agir.
* S: sensores, que recebem as informações.

1. Jogar futebol

Desempenho: fazer gols, evitar gols e vencer a partida.

Ambiente: campo, bola, jogadores e árbitro.

Atuadores: pernas, braços e movimentos do corpo de um robô jogador.

Sensores: câmeras e sensores de movimento e posição.

Classificação: parcialmente observável, estocástico, sequencial, dinâmico, contínuo e multiagente.

Explicação: o jogo muda o tempo todo e o agente precisa tomar decisões conforme os outros jogadores se movimentam.

2. Explorar os oceanos subterrâneos de Titã

Desempenho: explorar o local, coletar informações e evitar danos ao equipamento.

Ambiente: oceano subterrâneo, água, obstáculos e regiões desconhecidas.

Atuadores: motores, propulsores e braços robóticos.

Sensores: câmeras, sonar e sensores de temperatura e pressão.

Classificação: parcialmente observável, estocástico, sequencial, dinâmico, contínuo e de agente único.

Explicação: o robô não conhece todo o ambiente e precisa descobrir o caminho enquanto realiza a exploração.

3. Comprar livros usados de IA na Internet

Desempenho: encontrar o livro correto, em bom estado e com preço acessível.

Ambiente: sites de venda, vendedores e anúncios.

Atuadores: pesquisar, selecionar produtos e realizar compras pelo sistema.

Sensores: preços, descrições, avaliações e informações dos anúncios.

Classificação: parcialmente observável, estocástico, sequencial, dinâmico, discreto e multiagente.

Explicação: os preços e a disponibilidade podem mudar. Além disso, o comprador nem sempre sabe exatamente o estado do livro.

4. Jogar uma partida de tênis

Desempenho: marcar pontos, acertar a bola e vencer a partida.

Ambiente: quadra, rede, bola e adversário.

Atuadores: braços, pernas e raquete de um robô jogador.

Sensores: câmeras e sensores de posição e movimento.

Classificação: parcialmente observável, estocástico, sequencial, dinâmico, contínuo e multiagente.

Explicação: o agente precisa acompanhar a bola e reagir aos movimentos do adversário.

5. Praticar tênis contra uma parede

Desempenho: acertar a bola na parede e conseguir devolvê-la várias vezes.

Ambiente: parede, quadra, bola e raquete.

Atuadores: braços, pernas e raquete de um robô.

Sensores: câmeras e sensores de posição e velocidade.

Classificação: parcialmente observável, aproximadamente determinístico, sequencial, dinâmico, contínuo e de agente único.

Explicação: diferente de uma partida normal, não existe um adversário tomando decisões. O movimento da bola depende principalmente da batida e das condições físicas.

6. Realizar um salto de altura

Desempenho: ultrapassar a barra sem derrubá-la e alcançar a maior altura possível.

Ambiente: pista, barra e área de salto.

Atuadores: pernas e movimentos do corpo de um robô atleta.

Sensores: câmeras e sensores de posição, velocidade e equilíbrio.

Classificação: parcialmente observável, estocástico, sequencial, dinâmico durante a execução, contínuo e de agente único.

Explicação: o agente precisa calcular a corrida, o impulso e os movimentos para conseguir passar pela barra.

7. Participar de um leilão de um item

Desempenho: conseguir comprar o item por um preço vantajoso, sem ultrapassar o orçamento.

Ambiente: leilão, participantes, lances e regras.

Atuadores: enviar lances e confirmar propostas.

Sensores: valores dos lances, tempo restante e informações do item.

Classificação: parcialmente observável, estocástico, sequencial, dinâmico, discreto e multiagente.

Explicação: o agente precisa acompanhar os lances dos outros participantes e decidir se vale a pena aumentar sua oferta.

Exercício 2.5 — Definições

1. Agente

É algo que recebe informações do ambiente e realiza ações. Pode ser um robô, um programa ou outro sistema.

2. Função de agente

É a relação que determina qual ação o agente deve escolher com base nas informações que recebeu ao longo do tempo.

3. Programa de agente

É o código que executa a função de agente em um computador ou equipamento.

4. Racionalidade

É escolher a melhor ação esperada considerando as informações disponíveis e o objetivo que precisa ser alcançado. Isso não significa acertar sempre.

5. Autonomia

É a capacidade de um agente agir utilizando suas próprias experiências e informações, sem depender somente das instruções colocadas pelo programador.

6. Agente reativo

É aquele que reage diretamente ao que percebe no momento, utilizando regras. Por exemplo, um robô que detecta um obstáculo e muda de direção.

7. Agente baseado em modelo

É um agente que mantém informações internas sobre o ambiente. Isso ajuda a tomar decisões mesmo quando não consegue observar tudo.

8. Agente baseado em objetivos

É aquele que escolhe suas ações pensando em alcançar um objetivo. Por exemplo, um robô que precisa encontrar um caminho até determinado local.

9. Agente baseado em utilidade

É um agente que compara as opções e escolhe aquela que oferece o melhor resultado esperado de acordo com seus critérios. Por exemplo, escolher uma rota considerando tempo, segurança e consumo de energia.

10. Agente com aprendizagem

É aquele que consegue melhorar seu comportamento a partir das experiências. Com o tempo, ele pode aprender quais decisões funcionam melhor em determinadas situações.

Referência

RUSSELL, Stuart; NORVIG, Peter. Inteligência Artificial: Uma Abordagem Moderna. 4ª edição. Capítulo 2 — Agentes Inteligentes.
