# matlab_TP1
3D tetris


Objetivo

Criação dos modelos em Matlab de peças similares à do jogo Tetris tridimensional, e implementação das transformações geométricas para a construção animada de montagens com base numa
sequência de peças lida de um ficheiro. As peças surgem sempre na sua posição de definição
(como ilustrado adiante), e devem ser animadas de forma a construir, sem colisão, uma montagem que cresce de baixo para cima por colocação e sobreposição das peças. As transformações
geométricas são translações e rotações a 3D.

Descrição

As peças possíveis são dos seguintes tipos que se distinguem pelo número assinalado:
![image](https://github.com/user-attachments/assets/09eb28e2-5df7-4232-929d-99d1c9fff826)

As peças devem iniciar o seu movimento na posição do canto superior esquerdo de uma grelha
tridimensional com uma base de 6×6 células e uma altura de 8 células. O movimento deve ser feito
de forma a ir criando camadas de peças assentes sobre a base da grelha tri-dimensional. As peças
podem ser colocadas em qualquer posição sobre uma face plana, e alinhadas com as células da
grelha, mas não podem ultrapassar os limites da grelha. A figura seguinte ilustra uma situação em
que a peça ![image](https://github.com/user-attachments/assets/ed1665fa-3b94-4189-af7d-370afdcf7d7b) entrou em cena e algumas peças já estão colocadas na grelha como resultado de
movimentações anteriores (o exemplo ilustrado é arbitrário).
