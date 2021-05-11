# Dados de sorteios da Lotofacil

## Codigo para receber dados do sorteio atual

```
# -*- coding: utf-8 -*-
from lotofacil import Sorteio

concurso = Sorteio()

print(concurso.listaDezenas())
````
## ou use um sorteio especifico

```
# -*- coding: utf-8 -*-
from lotofacil import Sorteio

concurso = Sorteio(2224)

print(concurso.listaDezenas())
````

## Abaixo todos os comandos

```
# -*- coding: utf-8 -*-
from lotofacil import Sorteio

concurso = Sorteio()

print(concurso.todosDados())
print(concurso.tipoJogo())
print(concurso.numero())
print(concurso.nomeMunicipioUFSorteio())
print(concurso.concursoApuracao())
print(concurso.valorArrecadado())
print(concurso.valorEstimadoProximoConcurso())
print(concurso.valorAcumuladoProximoConcurso())
print(concurso.valorAcumuladoConcursoEspecial())
print(concurso.valorAcumuladoConcurso_0_5())
print(concurso.acumulado())
print(concurso.indicadorConcursoEspecial())
print(concurso.dezenasSorteadasOrdemSorteio())
print(concurso.listaResultadoEquipeEsportiva())
print(concurso.numeroJogo())
print(concurso.nomeTimeCoracaoMesSorte())
print(concurso.tipoPublicacao())
print(concurso.observacao())
print(concurso.localSorteio())
print(concurso.concursoProximoConcurso())
print(concurso.numeroConcursoAnterior())
print(concurso.numeroConcursoProximo())
print(concurso.valorTotalPremioFaixaUm())
print(concurso.numeroConcursoFinal_0_5())
print(concurso.listaMunicipioUFGanhadores())
print(concurso.listaRateioPremio())
print(concurso.listaDezenas())
print(concurso.listaDezenasSegundoSorteio())
print(concurso.id())
```