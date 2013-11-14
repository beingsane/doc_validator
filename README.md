doc_validator
=============

Este plugin realiza o calculo de vericação de CNPJ/CPF e pode ser utilizado em conjunto com o [Masked Input Plugin](http://digitalbush.com/projects/masked-input-plugin/).

##Utilização##

Para utilizar o pluguin basta adicionar sua chamada como no exemplo abaixo:

```html

<script type="text/javascript" src="tests/js/doc_validator.min.js"></script>
```

Adicionar o objeto que irá receber o valor.
```html
  <input type="text" id="my-input">
```

E instanciar o objeto desejado.

```html
<script type="text/javascript">
  $("#my-input").doc_validate({doc_type:"cpf", valid:"green", invalid:"red"});
</script>
```


**Parametros:**
  
  *doc_type:* Tipo do documento que está sendo verificado (cpf, cnpj).
  
  *valid:*    Cor da fonte caso o numero seja valido.
  
  *invalid:*  Cor da fonte caso o numero seja invalido.


