# Bitacora día 21-07-2026 Inicio de creacion de producto clase.

``` js
setcpm (100/5)

let capa1 = stack(
  s("oh*2:1").beat("3,5,9,13",16),
  s("hh*2").beat("0,1,4,6,8,10,12,14",16),
  s("cp").beat("4,12",16),
  s("bd").beat("0,2,3,7,9,10,15",16),
  s("lt*2").beat("0,1,4,6,8,10,12,14",16),
  ).bank("RolandTr909");

 $:capa1

let melody = note("<[c2 c3]*4 [bb1 bb2]*4 [f2 f3]*4 [eb2 eb3]*4>")
.sound("gm_fx_atmosphere").lpf(800)

$melody:melody

$: let capa1
```