# Fill All Selects
> É um *script* que preenche todos os `selects` do **Questionário de Avaliação da Docência** de uma vez com um valor pré-definido.

# How to do

Com o questionário aberto, insira o código abaixo no **Console** do navegador e pressione enter.

```js
const element = document.getElementsByTagName('select');
for (i = 0; i <= element.length; i++){
    element[i].value = 8;
}
```

