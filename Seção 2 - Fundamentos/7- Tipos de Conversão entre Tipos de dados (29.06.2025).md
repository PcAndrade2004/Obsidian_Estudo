## Conversão Implícita 
 * O compilador C# converte automaticamente um tipo de dados em outro tipo.
 ```Csharp
 // Conversão Implícita
// Podemos fazer essa conversão porque os dois tipos são compatíveis.
// int ocupa 4 bytes e double ocupa 8 bytes.
// Ou seja, é possível converter de int para double sem perda de dados.
int varInt = 100;
double varDouble = varInt;
Console.WriteLine(varDouble);

SAIDA: 
100
```
 *  Podemos fazer essa conversão porque os dois tipos são compatíveis.
 *  *int* ocupa **4 bytes** e double ocupa **8 bytes**.
 *  Ou seja, é possível converter de *int* para *double* sem perda de dados.

## Conversão Explícita 
* A conversão tem que ser feita manualmente de forma explícita.
```Csharp
double varDoublee = 12.456;
int varIntt = varDoublee;
Console.WriteLine(varIntt);

```
* *double* usa *8 bits* enquanto *Int* usa *4 bits* com isso não conseguimos converter.
* Isso apresentara um erro ao ser executado.

## Usando #Casting 
Para convertemos esse um numero de **double** para um tipo menor como o **Int**.

```Csharp
double varDoublee = 12.456;
int varIntt = (int)varDoublee;
Console.WriteLine(varIntt);
```
* Devemos utilizar o **( )** dentro dele devemos adicionar o tipo que queremos converter que no caso seria o tipo neste caso : **int**  