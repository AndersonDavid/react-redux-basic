## Exemplos Básicos de React Redux
__Repósitorio direcionado a quem estar começando a usar Redux em sua aplicação React__

Alguns exemplos da conexão de uma aplicação ReactJS (podendo tambem se aplicar a React Native) com uma `store` do Redux.

É importante notar que o não estou apenas adicionando um item em um simples state, pois isso só seria possivel se se eu fizesse toda a aplicação em um unico componente ja que o state de um componente é particular dele.

Cada input e cada lista é um elemento difenrente conectados ao um unico store compartilhando um state global em toda a aplicação.

### useDispatch e useSelector

O primeiro exemplo usa `useDispatch` e `useSelector` importados do `react-redux`.  
Essas funcções permitem a leitura e escrita de um `store` do Redux.

Para melhor utilização do `useDispatch` eu usei o __React Hooks__ para facilitar na hora de enviar o texto do `input` para o __action__ do `store`.

### connect()

Ao utilizar components em forma de classe, utilizei a função `connect()` que recebe quatro parametros mas que no entanto só precisei utilizar dois:

1. `mapStateToProps?: Function` - Para leitura do estado atual do `store`
2. `mapDispatchToProps?: Function | Object` - Para edição do estado atual do `store`

### __Referencias__

[Redux](https://redux.js.org/)  
[React Redux](https://react-redux.js.org/)  
[ReactJS](https://pt-br.reactjs.org/)




