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
que a peça (1) entrou em cena e algumas peças já estão colocadas na grelha como resultado de
movimentações anteriores (o exemplo ilustrado é arbitrário).

![image](https://github.com/user-attachments/assets/7db47cf4-54a7-421f-b7b7-8f02771190df)

As restantes peças iniciam o seu movimento nas seguintes configurações respetivamente:

![image](https://github.com/user-attachments/assets/fc6d2d77-d247-4513-b2a9-acbbd4927c0c)


Funcionamento

O programa a desenvolver deve ler a sequência de peças a animar do ficheiro tp1.cfg. Nesse
ficheiro haverá um número por linha de valor entre 1 e 7, correspondendo a cada uma das peças
a processar em sequência. É garantido que as 14 primeiras peças serão duas de cada uma das
7 diferentes, mas numa ordem arbitrária. As peças restantes para além das 14 poderão ser de
qualquer tipo. O número total de peças não excederá as 50.
As peças devem partir sempre da posição ilustrada nas figuras e podem ser colocadas por animação em qualquer posição válida da grelha, mas a ideia é fazer uma montagem com a altura
mínima possível, e sem colisão de peças. As peças devem ter cores distintas e devem manter a sua
cor durante o processo.

Etapas

• O programa lê a sequência de peças do ficheiro tp1.cfg.
• Começando no ponto de partida, simula o seu movimento com as translações e rotações
necessárias para as pousar na base da grelha ou sobre outras peças que já lá estejam.
• Construir a primeira camada tentando preenchê-la com as 14 primeiras peças.
• Movimentar as peças restantes para cima das 14 primeiras, procurando manter a montagem o
mais baixa possível, sem colisões ou interferência entre peças.

Parâmetros de avaliação

• Modelação apropriada das peças (linhas, cores, geometria) (20%).
• Animação correta do movimento com translações e rotações 3D (30%).
• Grau de compactação (mínimo de células vazias) da primeira camada com 14 peças (10%).
• Ausência de colisões no movimento de peças (10%).
• Altura atingida na construção final, que deve ser a menor possível (5%).
• Outros eventuais elementos de personalização ou enriquecimento do programa (5%).
Para além do nível de verificação dos diversos parâmetros descritos, o trabalho será também
avaliado pelos seguintes elementos adicionais a entregar:
• Gerar um filme em Matlab que ilustra os movimentos animados implementados, e colocar online no youtube (10%).
– A duração máxima recomendada do filme é de 1 minuto. No filme, indicar pelo menos o
nome do autor, nome da disciplina, a data, e a Universidade.
• Um relatório em PDF (3 páginas max.) a explicar as funções desenvolvidas e os procedimentos
principais da abordagem (10%).
– Deve ser incluído o link para o filme no youtube. O documento deve ter adicionalmente
uma página de rosto com a identificação do autor e do trabalho. Recomenda-se veementemente fazer o relatório em LATEX (documentclass do tipo report ou similar).

Resumo do material a entregar no e-learning

1. Código Matlab. Incluir todas as funções necessárias à execução do trabalho. Entregar ficheiro de
arquivo empacotado (ZIP, RAR, etc.).
2. Um relatório em PDF (3 páginas max.) a explicar as funções desenvolvidas e os procedimentos
principais da abordagem, e ainda com o link do filme. Incluir uma capa adicional com o título e
identificação do autor.
