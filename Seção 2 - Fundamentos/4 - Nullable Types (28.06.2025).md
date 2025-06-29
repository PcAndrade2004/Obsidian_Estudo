# Quando usar?
Devemos utilizá-los quando precisarmos que um tipo valor (**como tipo numérico**) precise conter um #null
Ate o momento podemos dizer que algo é <font color="#ff0000">null</font> quando estamos nos referindo a tipos de referencia (String, Object)

## O que é Nullable Types
* - Um **Nullable Types** é um tipo por valor que pode receber um valor `null`.
    
- Os **Nullable Types**, ou **Tipos Anuláveis**, permitem atribuir um valor `null` a um tipo por valor.

## Sintaxe Nullable Types
```Csharp
Nullable<T><Nome> = null;
```
* Os Nullable Types suportam os valores do tipo mais o valor <font color="#ff0000">null</font>.
### Nullable Types *Inteiro*
```Csharp
Nullable<int> b = null;
```

### Nullable Types *Booleano*
```Csharp
NullableTypes<bool> = null;
```
* Neste caso, ele suportará um *true* ou *false*.
### Nullable Types *double*
```Csharp
Nullable<double> b = null;
```
* Utilizando um valor double.

## Simplificando os Nullable  Types 
* Podemos simplificar a declaração utilizando o operador <font color="#ff0000">?</font>

```Csharp
int? i = null;
double? d = null;
bool? b = null;
```

## Propriedades somente leitura: HasValue e Value
São usadas para examinar e obter um valor de uma variável de Nullable Types.

**HasValue** : <font color="#ff0000">true</font> se tiver um valor <font color="#ff0000">false</font> se não tiver um valor (Null)
**Value** : Exibe o valor atribuído.

```Csharp
if (idade.HasValue)
{
    Console.WriteLine("Idade: " + idade.Value);
}
else
{
    Console.WriteLine("Idade não informada.");
}
```
* Caso o valor não seja <font color="#ff0000">null</font> ele verifica utilizando o #HasValue é retornar a idade da pessoa utilizando o #Value