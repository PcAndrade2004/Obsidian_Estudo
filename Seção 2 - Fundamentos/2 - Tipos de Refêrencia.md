Tempos três tipos de referência, esses tipos são armazenados na memoria RIP

### Tipo String 
* Definição
	Representam uma sequência de zero ou mais caracteres Unicode (São Imutáveis)
	* Quando declararmos um valor, não podemos alterar o valor destinado.
```C#
strig nome = "Curso Csharp Essencial";
System.String = "Curso Csharp Essencial";
```
Observação: 
* <span style="background:#ff4d4f">Se formos trabalhar com muitos textos e formos realizar muitas alterações não é recomendado utilizar  o tipo String</span>

### Object 
* Definição
	É o tipo base para todos os outros tipos
```Csharp
object nota = 10;
object valor = 8.55m;
object nome = "Curso C#";
object ativo = true;
object letra = "A";
```
* Tipo Object e útil quando não temos informação do tipo de dado que queremos utilizar
### Dynamic
* Definição 
	São resolvidos em tempo de execução. 
	Se comportam como o tipo **Object** na maioria das situações.

São tipos de referência
O valor padrão é **null**
