Имплементација на сервер за документи

Имплементирајте сценарио на копирање на текстуални фајлови на сервер со користење на TCP протоколот. 
Серверот за документи слуша на порта 9876.
Клиентите изминуваат одреден фолдер и ги праќаат сите документи во истиот.
Сите документи кои пристигнуваат кај серверот, треба да се сместат во посебен фолдер.
Потребно е да се овозможи праќање на документи од повеќе клиенти истовремено.

Клиентот најпрво го праќа името на документот во следниот формат: пр. ###data.txt###
Потоа следи содржината на документот линија по линија.
За крај на праќање на одреден документ, го праќа следниот стринг: !!!END!!!
Потребно е да се овозможи праќање на повеќе документи во една сесија.

