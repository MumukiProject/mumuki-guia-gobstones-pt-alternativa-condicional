Analisemos o procedimento do exercício anterior:

``` gobstones
procedure RetirarAzulComMedo() {
  if (haPedras(Azul)) {
    Retirar(Azul)
  }
}

```

Como notará, introduzimos uma nova estrutura de controle: o **if**, que em português significa _se_; entendendo o _se_ como condicional ("_se_ eu tivesse fome, comeria uma pizza") e não como um pronome ("você deveria _se_ comportar"). 

Então, o que estamos dizendo ao computador é _"se há pedras azuis, retire uma pedra azul"_, que parece um pouco bobo. E de fato é! Já explicamos que o computador só sabe cumprir ordens.

> Experimente você agora: modifique o procedimento que demos para que retire uma pedra vermelha, apenas _se_ tiver alguma.