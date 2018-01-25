Em todos os problemas que fizemos até agora, sempre perguntamos se uma certa condição se cumpria: há alguma pedra vermelha? Posso mover para o Leste? Há mais de 3 pedras azuis?

Algo que também pode ser feito é **negar** uma condição, algo que em português pode parecer um pouco estranho mas em programação é feito muitas vezes. Os exemplos anteriores ficariam: **não** há alguma pedra vermelha? **Não** posso me  mover para o Leste? **Não** há mais de 3 pedras azuis?

E como se faz em Gobstones? Fácil, se adiciona a palavra-chave `not` antes da expressão que já tínhamos.

|Original|  |Negada|
|:------:|:-:|:----:|
|`haPedras(Vermelho)`|<i class="fa fa-arrow-right"></i>|`nothaPedras(Vermelho)`|
|`podeMover(Leste)`|<i class="fa fa-arrow-right"></i>|`not podeMover(Leste)`|
|`nroPedras(Azul) > 3`|&nbsp;&nbsp; <i class="fa fa-arrow-right"></i> &nbsp;&nbsp;|`not nroPedras(Azul) > 3`|

&nbsp;

> Escreva um procedimento `GarantirUmaPedraVerde()` que se certifique que na célula atual há pelo menos uma pedra verde. Isto é: se já existem pedras verdes não precisa fazer nada, mas se **não** há teria que colocar uma.