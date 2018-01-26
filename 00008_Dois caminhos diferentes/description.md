No cotidiano, se apresentam muitas situações onde devemos escolher entre duas ações diferentes, dependendo de que se cumpra uma certa condição ou não.

* Se a camiseta está limpa eu uso, _se não_ eu lavo.
* Se tenho óleo para fritar as milanesas eu uso, _se não_ coloco um pouco de manteiga.
* Se posso me mover para o Leste eu faço, _se não_ me movo para o Norte.

Para estes casos, em Gobstones temos uma nova palavra chave que nos ajuda a cumprir nossa tarefa: o **else**. Em português significa _se não_ e faz justamente o que necessitamos, executa uma série de ações _se não se cumpre_ a condição que colocamos no `if`.

Suponhamos que queremos fazer um procedimento que se mova ao Oeste e, em caso de que não possa, que ele faça para o Norte. Fazendo uso do `else`, podemos escrever o procedimento da seguinte maneira:

``` gobstones
procedure MoverComoSeja() {
    if (podeMover(Oeste)) {
        Mover(Oeste)
    } else {
        Mover(Norte)
    }
}

```

> Escreva esse código no editor e observe como resolve o problema.
