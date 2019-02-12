# Formas de Inicializar Objetos #

1. Os atributos são inicializados com o valor padrão dos tipos os quais pertencem

```
var p1 = new Produto();
```

2.

```
var p2 = new Produto();
p2.Nome = "Caneta";
p2.Preco = 2.90;
```

3.

```
var p3 = new Produto("Caneta", 2.90);
```

4.

```
var p4 = new Produto(){
  Nome = "Caneta",
  Preco = 2.90
};
```

5.

```
var p5 = new Produto{
  Nome = "Caneta",
  Preco = 2.90
};
```

