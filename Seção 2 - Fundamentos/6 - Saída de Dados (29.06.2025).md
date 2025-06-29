Podemos fazer a formatação de String de algumas maneiras. No exemplo que irei mostrar darei 4 formas de fazer isso.

## Escrevendo na mesma linha **Console.Write();** 
* Quando temos variáveis podemos junta-las na mesma linha, sendo assim podemos utilizar o comando de exibição : 
```Csharp
string nome = "Paulo";
int idade = 20;

Console.Write(nome);
Console.Write("tem");
Console.Write(idade);
Console.Write("anos");

//Saida:
Paulotem 20anos
```

## #Concatenação : Operador de (+)

* Usamos e acrescentamos uma cadeia de caracteres ao final de outra cadeia  de caracteres. Para isso usamos o operador de **+**
```Csharp
string nome = "Paulo";
int idade = 20;

Console.WriteLine(nome + " tem " + idade + " anos");

//SAIDA:
Paulo tem 20 anos 
```

## #Interpolação -> $

* Usa objetos e expressões para realizar uma interpolação de String. Para isso usa o operador de **$** para indicar a interpolação e **{}** para conter as variáveis a serem substituídas. 
```Csharp
string nome = "Paulo";
int idade = 20;

Console.WriteLine($"{nome} tem {idade} anos");

//SAIDA: 
Paulo tem 20 anos
```

## #PlacesHolders

* Usamos o *{ }* e uma numeração iniciada em 0 para indicar a ordem de substituição das variáveis que devem ser informadas na ordem a serem exibidas.
```Csharp
Console.WirteLine("{0} tem {1} anos" , idade, nome);
```


## #Escape

* Sequência de escape é uma combinação de caracteres composta por uma barra invertida ( \ ) seguidamente de uma **letra** ou sequência de dígitos.
![[Pasted image 20250628224048.png]]

