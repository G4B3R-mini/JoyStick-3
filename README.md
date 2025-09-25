## Créditos

Este projeto é baseado no [JoyStick de Roberto D'Amico (Bobboteck)](https://github.com/bobboteck/JoyStick).

Modificações feitas por Gabriel Marques:
- Conversão do código para ES6 Modules
- Adaptações para compatibilidade com import maps
- Ajustes e melhorias na organização do código

``` <script type="module">
  import { JoyStick } from './joy.js';

  let joy = new JoyStick("meuContainer", {}, (status) => {
      console.log(status);
  });
</script>
```
- [exemplo](https://g4b3r-mini.github.io/JoyStick-3/Joy.html)
