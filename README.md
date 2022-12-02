# Testando Estruturas Condicionais
## Aprendendo a usar estruturas condicionais. 
### Exercício: calcular quanto custa uma viagem de carro híbrido

```ruby
/* calcular quanto custa uma viagem de carro híbrido

  variaveis: 
  1 - preço do etanol
  2 - preço da gasolina
  3 - gasto medio de combustivel por km
  4 - distancia em km da viagem
  5 - o tipo de combustivel

  */

  const preçoEtanol = 3;
  const preçoGasolina = 5.25
  const gastoMedioCombPorKm = 14.7;
  const distKm = 3662;
  const tipoDeCombustivel = 'Etanol'

  const litrosGastos = distKm / gastoMedioCombPorKm;

  if (tipoDeCombustivel ===  'Etanol'){
    const reaisGastos = litrosGastos * preçoEtanol
    console.log(reaisGastos.toFixed(2))

  } else {
    const reaisGastos = litrosGastos * preçoGasolina
    console.log(reaisGastos.toFixed(2))

  }
  ```
