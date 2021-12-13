# thegameoflife
The Game Of life - by - John Horton Conway


# O jogo da vida
O espaco do jogo da vida é  uma matriz ortogonal de duas dimenções com celulas quadraticas, no qual apenas exite dois estados possiveis, vivo ou morto (0 & 1 (:-) ).

Cada celula interage com os seus 8 vizinhos, nos quais são as celulas horizontais, verticais ou a adjacente diagonal.
A cada segundo os seguintes eventos ocorem:

1. - a celula que tiver menos de 2 vizinhos vivos, morre, como se fosse por haver pouca população;
2. - a celula que tiver 2 ou 3 vizinhos vivos, sobrevive na proxima geração;
3. - a celula que tiver mais de 3 vizinhos vivos, morre, como se fosse por superpopulação;
4. - a celula morta que tiver exatamente 3 celulas vivas como vizinhos, torna-se uma celula viva, como se fosse uma reprodução.

## simplificando-o

1. - a celula com 2 ou 3 vizinhos vivos  sobrevive;
2. - uma celula morta com 3 vizinhos vivos, torna-se numa celula viva;
3. - todas as outras celulas morrem na proxima geração.


O padraon inicial constitui a semente do sistema.A primeira geração é criado as regras citadas, aplicando-os simultaniamente a cada celula da semente, "para ser vivo ou morto". Nascimentos e mortes ocorem simultaniamente e cada geração é uma pura função da sua predecessora, e as regras vao continuando a ser aplicadas nas futuras gerações.
