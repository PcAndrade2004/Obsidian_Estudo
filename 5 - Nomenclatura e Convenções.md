
## Case Sensitive
==A linguagem C-Sharp é sensível a letras maiúsculas e minúsculas, ou seja, a mesma letra maiúscula e minúscula é considerada diferente.==
## Identificadores 
Um <font color="#ff0000">identificador</font> é o nome que você atribui a um tipo (**classe**, **interface**, **struct**, **record**, **delagate** ou  **enum**), membro, propriedade, variável ou namespace.

Devemos utilizar nomes significativos que permitem inferir o propósito do identificador.
* *calculaDoImpostoICMS*, *valorTotalComDesconto*, *dataVencimentoFatura*
## Regras gerais para identificadores válidos
* Deve começar com letra sublinhado ( _ )
* Não pode iniciar com um número ou caracteres especiais.
* Não pode conter espaços.
* Pode usar caracteres Unicode (<font color="#ff0000">Não é recomendado</font>)
* Não pode ser uma palavra-reservada da linguagem como : <font color="#ff0000">if, int, double, string, class</font>.
* Não podem exceder 512 caracteres.

![[Pasted image 20250627194949.png]]


# Convenções

### Camel Case 
* A primeira letra da primeira palavra é iniciada com minúscula. A letra de cada palavra seguinte deve ser iniciada com maiúscula. 
<font color="#b2a2c7">Ex: valorDoDesconto, nomeCompleto, valorDoImpostoSobreServico</font>

### Pascal Case 
* A primeira letra de cada palavra é iniciada com maiúscula. (Não pode haver espaço entre as palavras) 
<font color="#b2a2c7">Ex: CalculaImpostoDeRenda, ValorDoDesconto, NomeCompleto</font>
Usado em **nomes** de **classes**, **métodos**, **interfaces**, **propriedades**

### Constantes 
* Devemos utilizar letras maiúsculas 
<font color="#b2a2c7">Ex: PI, DESCONTO, VALOR, IMPOSTO</font>  
* Caso ela tenha palavras compostas, devo separa-las utilizando o (  *_* ) Underline
### Sublinhado **( _ )** 
Usado para campos internos privados e somente leitura
Ex: _valorTotal, _calculoImposto, _precoComDesconto


