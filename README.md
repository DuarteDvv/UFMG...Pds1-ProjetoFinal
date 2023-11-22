# ProjetoFinal-_PDS1
Lembrando que esse código foi desenvolvido a muito tempo (Quando estava aprendendo C) e possui varias falhas além de ser algo bem simples e que pode ser melhorado
A unica coisa quero destacar nesse trabalho a minha adaptação do algortimo BFS ou Busca em largura para encontrar o menor caminho entre casa-restaurantes.
Não apenas tive saber usar como adaptar ao problema.

Esse projeto se trata da resolução de um problema com o seguinte enunciado:

Considere uma cidade, representada como uma matriz. Na cidade há restaurantes e ruas.
As ruas são representadas por coordenadas (x, y) indicando se a coordenada é
pavimentada (1) ou não (0). Considere que se duas coordenadas adjacentes forem
pavimentadas, então o trecho entre essas coordenadas é pavimentado. O arquivo “ruas.txt”
fornece a informação sobre os trechos pavimentados e não-pavimentados (x, y,
pavimentado). Todos os restaurantes são acessíveis através das ruas, ou seja, há sempre
um caminho possível entre um local pavimentado e um restaurante. Mais ainda, há sempre
apenas um caminho possível.
Os restaurantes podem ser baratos/caros, e cada restaurante possui um entregador. O
entregador realiza entregas com sua moto, e a velocidade da moto é especificada. O
arquivo “restaurantes.txt” possui essa informação (x, y, nome, custo, velocidade).
A unidade de medida de distância é chamada “zambs”. A distância entre duas coordenadas
adjacentes na matriz corresponde a um “zambs”. As velocidades das motos são dadas em
zambs/minuto.
Você deve informar (via teclado) as coordenadas de sua casa. Note que sua casa deve
estar em um trecho pavimentado da cidade.
  1. Calcule a distância em “zambs” de sua casa a todos os restaurantes. Dica: sempre
  que chegar em uma esquina, escolha um caminho e guarde a coordenada da
  esquina para explorar os outros possíveis caminhos.
  2. Leia (do teclado) a preferência de custo (caro ou barato), e retorne um arranjo com
  os restaurantes em ordem de rapidez de entrega.
  3. Leia (do teclado) a preferência de custo (caro ou barato) e o tempo máximo que
  voce quer esperar (minutos), e retorne um arranjo com os restaurantes que
  respeitem a restrição de tempo de espera.
